# Project 1. Deforestation in supply chains

Intense tropical deforestation is one of the main challenges thwarting climate change and biodiversity conservation efforts worldwide. Thanks to the improved quality and resoultion of satellite imagery available, research organizations are better equipped to monitor land use changes and track their association with economic, political and social changes. The complex deforestaion dynamics in the Brazilian Amazon forest offer a great oportunity to connect different types of data and predict local future deforestation rates.  

This first portfolio piece as part of a project I worked on for a Data science program, modelling deforestation rates associated with soymeal production in Brazil. Although some of the soy production has now moved to areas previously  deforested for other cattle ranching, it continues to play an active role driving deforestion. I started by scraping deforestation and commodity price data from publicly available sources such as deforestation databases (Trase) and a stock exchage (Nasdaq).

Part 1. [Exploring Soy Export Data: How much is porduced and where is it going?](https://github.com/angienic/My_Portfolio/blob/main/Cap_EDA_Model_Clean.ipynb)

- Used Python Pandas libraries for data wrangling and exploratory analysis of datasets with over 295K rows. 
- Engineered features to quantify and aggregate contributions from different regions and soy products.
- Created visualizations with Matplotlib and Tableau.

![Deforestation risk trends 2004-2018](/images/Deforestation_risk_sm.jpg)
![Global exports](/images/Export_map.jpg)

Part 2. Deforestion modelling

- Optimized linear and random forest regressors using GridSearch CV to  build robust models.

Part 3. Forecasting.

- Used Facebook Prophet time series analysis to predict soy meal prices in the short term range.

