# Project 1. Deforestation in supply chains

This piece is part of a Capstone Data Science project I am working on modelling deforestation rates associated with soymeal production in Brazil. I started by scraping deforestation and commodity price data from publicly available sources such as deforestation databases (Trase) and a stock exchage (Nasdaq).

Part 1. [Exploring Soy Export Data: How much and where is it going?](https://github.com/angienic/My_Portfolio/blob/main/Cap_EDA_Model_Clean.ipynb)

- Used Python Pandas libraries for data wrangling and exploratory analysis of datasets with over 295K rows. 
- Engineered features to quantify and aggregate contributions from different regions and soy products.
- Created visualizations with Matplotlib and Tableau.

![Deforestation risk trends 2004-2018](https://github.com/angienic/My_Portfolio/blob/main/images/Deforestation_risk_sm.jpg)
![Global exports](https://github.com/angienic/My_Portfolio/blob/main/images/Export_map.jpg)

Part 2. Deforestion modelling

- Optimized linear and random forest regressors using GridSearch CV to  build the best models.

Part 3. Forecasting.

- Used Facebook Prophet time series analysis to predict soy meal prices.

