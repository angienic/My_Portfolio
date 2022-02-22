# # Deforestation in supply chains

This piece is part of a Capstone Data Science project I am working on modelling deforestation rates associated with soymeal production in Brazil. I started by scraping deforestation and commodity price data from publicly available sources such as deforestation databases (Trase) and a stock exchage (Nasdaq).

Part 1. [Exploratory Data Analysis] (https://github.com/angienic/My_Portfolio/blob/main/Cap_EDA_Model_Clean.ipynb)

- Used pandas for EDA, wrangling datasets of > 295K rows. 
- Engineered features to quantify and aggregate contributions from different regions and products.
- Created visualizations with matplotlib and Tableau.

Part 2. Deforestion modelling

- Optimized linear and random forest regressors using GridSearch CV to reach best models.

Part 3. Forecasting.

- Used Facebook Prophet time series analysis to predict soy meal prices.

