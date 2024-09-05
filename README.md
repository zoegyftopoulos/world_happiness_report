# Prediction & Geospatial Analysis of the World Happiness Report

# Motivation
The World Happiness Report lacks a presentation of the Happiness Scores per country on a world map. Plus, I was interested in how Gross Domestic Product could predict Happiness Scores. 

# Data
Five data sets from the WHR 2015-2019, containing 155-158 entries of countries, their Happiness Scores, and six contribu-ting factors (GDP, life expectancy, generosity, social support, freedom and corruption).

Source: World Happiness Report by Gallup, the Oxford Wellbeing Research Centre and the UN Sustainable Development Solutions Network

For the geospatial analysis, I used a vector map generated from https://geojson-maps.kyd.au which are sourced from https://www.naturalearthdata.com/.

For the time-series analysis of GDP, I used the Federal Reserve Economic Data Set – a project by the Economic Research department of the Federal Reserve Bank of St Louis.

Source: https://data.nasdaq.com/data/FRED-federal-reserve-economic-data/documentation

# Steps 
* Consistency checks
* Data wrangling
* Explore relationships
* Create a choropleth map
* Conduct a Linear Regression
  
# Findings 
Gross Domestic Product was able to explain R² = 61,7% of the variance of the Happiness Score in the test set and R² = 62,5% in the training set (RMSE = 0,7 for both).

Find a Tableau Storyboard I created for this project here (coming soon). The Storyboard doesn't contain every step I took in the analysis but highlights only those relevent to the final results. 
