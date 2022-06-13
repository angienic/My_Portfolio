# Project 1. Deforestation in supply chains

Intense tropical deforestation is one of the main challenges thwarting climate change and biodiversity conservation efforts worldwide. Thanks to the improved quality and resoultion of satellite imagery available, research organizations are better equipped to monitor land use changes and track their association with economic, political and social changes. The complex deforestaion dynamics in the Brazilian Amazon forest offer a great oportunity to connect different types of data and predict local future deforestation rates.  

This first portfolio piece as part of a project I worked on for a Data science program, modelling deforestation rates associated with soymeal production in Brazil. . For this project, I started scraping deforestation and commodity price data from publicly available sources such as deforestation databases (Trase) and a stock exchage (Nasdaq) and then completed analysis in three parts.

Part 1. [Exploring Soy Export Data: How much is porduced and where is it going?](https://github.com/angienic/My_Portfolio/blob/main/Cap_EDA_Model_Clean.ipynb)

- Used Python Pandas libraries for data wrangling and exploratory analysis of datasets with over 295K rows of 10-14 years of data. 
- Engineered features to quantify and aggregate contributions from different regions and soy products.
- Created visualizations with Matplotlib and Tableau.

![Deforestation risk trends 2004-2018](/images/Deforestation_risk_sm.jpg)

*Brazilian soymeal deforestation risk trends, 2004-2018*

![Global exports](/images/Export_map.jpg)
*Brazilian soymeal export destinations. Darker shades indicate highest transaction value (FOB) in USD* 

What the data showed: With very few exceptions, most countries buy soy from Brazil. After a soy moratorium agreement, some soy production moved to areas previously deforested for cattle ranching, but the largest proportion of soymeal transactions were carried out by producers or buyers that did not subscribe to no-deforestation commitments. To this day soy crops continue to play an active role driving deforestion in the Amazon. 

Part 2. Deforestion modelling

- Optimized linear and random forest regressors using GridSearch CV to  build robust models.

What the data showed: fluctuations in soymeal prices explained almost 20% of the variance in deforestation risk, illustrating the dynamic nature of incentives for deforestation despite international agreements and policy advances. 

Part 3. Forecasting.

- Used Facebook Prophet time series analysis to predict soy meal prices in the short term range.

What the analysis shows: Based on the period studied, deforestation is forecasted to continue in the near future, partially in response to increasing soy prices. Time series predictions would benefit from a more accurate selection of lag-time.
