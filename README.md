# Solar-Forecasting-SARIMAX

In Australia, the amount of energy coming from renewable sources is rising. Yet the equilibrium between energy production and consumption must be carefully managed by grid managers, otherwise causing an imbalance in the electricity supply. The aim of this project is to develop a better understanding of historical observations of solar radiation levels, and determine how they can be better forecast using the
multivarite forecasting model SARIMAX(Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors) which is an seasonal updated version of the ARIMA model family.

## Aim
This [data](http://www.bom.gov.au/) is responsible for providing weather services to Australia and surrounding areas, and we are trying to predict monthly the solar exposure rate at a certain station across Melbourne with the help of factors like it's history (22 years) of daily solar radiation and location (latitide and longtitude)etc. using SARIMAX.

|Column   | Dtype |
|------ |-------|
|Station Number |      int64  |
|Daily Solar Radiation| float64|
|Station Name |   object |
|Latitude   |   float64|
|Longitude   | float64|
|Date     |  object |
 
