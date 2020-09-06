# Gift-Card-Traffic-Data

Following data-set provides the count of transactions per day for gift-card business.  
Input Data: https://pastebin.com/F4g5dmnn

Required outcome:
- Based on the data provided, assert & recommend the model which will be most suitable to do forecasting for the traffic (number of transactions per day).
- Share the outcome in the same format as the input file & also provide a graph for the upcoming traffic projection.

## Introduction

The data given represents the number of gift-card transactions made per day from 1st January 2016 to 8th July 2019.
The aim is to find a suitable model for forecasting the future traffic data, i.e. number of transactions made per day from 9th July 2019 to 6th September 2020.

### Dataset
<img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Dataset_head.PNG">

The data provided has two fields:
1) _Date_: 
    * String Object type
    * It ranges from 01-01-2016 to 08-07-2019
    * Format: %d-%m-%Y %H-%M
2) _Transaction Count_:
    * Integer type
    * Number of transactions made per day
    
### Exploratory Data Analysis

- The trends in the data were observed as follows:
<img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Transaction_Count_per_day(2016-2019).PNG">

- Monthly Analysis for the same is as follows:
    - Transaction Count per month for 2016   
      <img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Transaction_Count_per_month_2016.PNG">
   
    - Transaction Count per month for 2017   
      <img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Transaction_Count_per_month_2017.PNG">
   
    - Transaction Count per month for 2018   
      <img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Transaction_Count_per_month_2018.PNG">
   
    - Transaction Count per month for 2019   
      <img src = "https://github.com/18abhinavkumar/Gift-Card-Traffic-Data/blob/master/Screenshots/Transaction_Count_per_month_2019.PNG">
    
## Models Used

### Linear Regression
Linear regression attempts to model the relationship between variables by fitting a linear equation to observed data. One variable is considered to be a dependent variable, and the others are considered to be explanatory variables.

### ARIMA (Autoregressive Integrated Moving Average Model)
ARIMA is actually a class of models that ‘explains’ a given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that equation can be used to forecast future values.

## References

1. [Time Series Forecasting Methods](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/)
2. [ARIMA model for Time Series Forecasting](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/#:~:text=ARIMA%20with%20Python&text=Define%20the%20model%20by%20calling,or%20times%20to%20be%20predicted)
3. [Making out-of-sample forecasts with ARIMA](https://machinelearningmastery.com/make-sample-forecasts-arima-python/)

## Contact

For any comments or questions, please contact me at 18abhinav.kumar@gmail.com
