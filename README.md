# Hourly-Bike-Rental-Predictions

1. Performed Exploratory Data Analysis on weather data including statistical insights and visualizations.
2. Implementation of Machine Learning algorithms including Linear Regression and Decision Tree Regressor to predict hourly boke rental demand based on different features. Got Test RMSLE equals to 0.16


##   Problem Statement
In this project, We are asked to combine historical usage patterns with weather data in order to forecast hourly bike rental demand.

## Data
1. train.csv : Use this dataset to train the model. This file contains all the
weather related features as well as the target variable “count”. Train
dataset is comprised of first 18 months.
2. test.csv : Use the trained model to predict the count of total rentals for
each hour during the next 6 months.

##  Data Dictionary
Here is the description of all the variables :
# Variable - Definition
1. datetime: hourly date + timestamp
2. season: Type of season (1 = spring, 2 = summer, 3 = fall, 4 = winter)
3. holiday: whether the day is considered a holiday
4. workingday: whether the day is neither a weekend nor holiday
5. weather: weather
6. temp: temperature in Celsius
7. atemp: "feels like" temperature in Celsius
8. humidity: relative humidity
9. windspeed: wind speed
10. casual: number of non-registered user rentals initiated
11. registered: number of registered user rentals initiated
12. count: number of total rentals

## How good are your predictions?
# Evaluation Metric
The Evaluation metric for this project is Root Mean Squared Logarithmic
Error (RMSLE).

