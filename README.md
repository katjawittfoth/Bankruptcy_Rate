# Forecasting Canadian Bankruptcy Rate with Time Series

## Project Overview
The goal of this project was to predict Canadian Bankruptcy rates for the period 2015-2017. The data 1987-2014 was given. There were also corresponding data on unemployment rates, population rates, and Housing Price Index that could be used to forecast bankruptcy rates. We used multivariate time series model (SARIMAX, VARX). 
 
The validation data is the subset data from 2011 to 2014, we then used the validation data to tune parameters for each model. Then we refit the model on whole data we have, made the prediction for the next 3 years (2015-2017) and compared it with the true value. We used RMSE as the loss function. 

## Final model won class competition
Our final model is an emsembled of top 10 SARIMAX models with RMSE 0.12. We were ranked top 1 among 22 teams in the class competition.

[Multivariate model impementation code in R](https://github.com/katjawittfoth/Bankruptcy_Rate/blob/master/Time%20Series%20Modeling.ipynb)
<br>
[Final Report](https://github.com/katjawittfoth/Bankruptcy_Rate/blob/master/Team1.7report.pdf)
