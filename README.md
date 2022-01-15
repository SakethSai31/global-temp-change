# PROJECT - GLOBAL TEMPARATURE CHANGE 

## INTRODUCTION 

United Nations Climate Change Conference, more commonly referred to as COP(CONFERENCE OF PARTIES) it is a decision-making body responsible for monitoring and reviewing the implementation of the United Nations Framework Convention on Climate Change.

The COP26 summit brings parties together to speed up action towards the goals of the Paris Agreement and the UN Framework Convention on Climate Change. Its aims are: To secure global net zero by mid-century and keep 1.5 degrees within reach

## OVERVIEW 

The goal of this project is to forecast temperature change based on prior temperature change trends acquired from the data set.

Analysed ~10k records of real time climate change data from FAOSTAT and NASA GI SS websites and established trends of
top 10 countries having highest and least temperature change

### Gathering Data

The Global Surface Temperature Change data distributed by the National Aeronautics and Space Administration Goddard Institute for Space Studies (NASA-GISS) is publicly available.
Data in the Temperature Change domain can be reachable from the Food and Agriculture Organization of the United Nations' web data portal.
The FAOSTAT Temperature Change domain shows statistics of mean surface temperature change by country, with annual updates. The below data covers the time period of 1961–2019. Statistics are available for monthly and annual mean temperature anomalies, i.e., temperature change with respect to a baseline climatology.
It includes areas of all the countries and territories of the world. (In 2019: 190 countries and 37 other territorial entities) The data covers monthly and yearly temperature changes as Celsius degrees °C between 1961 and 2019. The frequency of dissemination and Release calendar of the data is the yearly base.
While the first seven columns include information about temperature changes, the other columns show temperature change numbers between 1961 and 2019. And, all years have some missing values. When we examined the first seven columns, below are the description of the columns



### Data Wrangling

The Data set FAOSTAT_data have country codes(ISO 3166 standard published by the International Organization for Standardizationⁱ ). Added this from another CSV that is provided by FAOSTAT.

#### Cleaning and wrangling activities included:

Data columns and some rows rename

Deleting of columns and some rows

Manipulating data frame

### Exploratory Data Analysis 

To Analyse and Establish trends of the top 10 Countries having highest and least temperature change also made a heat map for the past 100 years which can be simulated to see the temparature difference.

### Predictive Modelling

Applied multiple modelling techniques such as Linear Regressor, Polynomial Regressor, Auto Regressor, Moving Average, ARIMA to find the best fit for the model.

Predicted into the future to estimate the temparature change on a global scale.

## CONCLUSION

From this project, it can be cocluded that there will be a 2°C difference in temperature in the future, which is significant. While a 2°C or 3°C temperature change may not appear to be significant, it has far-reaching repercussions on a global scale since it might affect the sustainability of water, food supplies, ecosystems, coastal stability, and public health.
