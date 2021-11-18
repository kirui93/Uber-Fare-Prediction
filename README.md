# Uber-Fare-Prediction

## Project Objective: 
Design an algorithm which will tell the fare to be charged for a passenger.

## Problem Statement Scenario: 

A fare calculator helps a customer in identifying the fare valid for the trip. They are often used by passengers who are new to a city or tourists to get an estimate of travel costs. You are provided with a dataset with features like fare amount, pickup and drop location, passenger count, and so on.

### Actions to be performed

The following actions are to be performed:

* Understand the type of data.
* Identify the output variable.
* Identify the factors which affect the output variable.
* Check if there are any biases in your dataset.
* Count the null values existing in columns.
* Remove the null value rows in the target variable.
* Perform train test split.
* Predict the accuracy using regression models.
* Check and compare the accuracy of the different models.

## Description of Data and Variables

There are **8** variables in the train dataset.
* key - Key
* fare_amount - Amount of fare paid by the passanger
* pickup_datetime - Date and time of pick up
* pickup_longitude - Pick up longitude
* pickup_latitude - Pick up latitude
* dropoff_longitude - Drop off longitude
* dropoff_latitude - Drop off latitude
* passanger_count - The number of passangers in the cab

The test dataset has **7** variables. This is the dataset that we will be using to make prediction.

The train dataset has more than 5 Million observations. For the sake of demonstration of this project, we will be using a sample of this dataframe for training.

## Models

We will generate 2 models and make comparison.
* Linear regression
* Rondom Forest regression

## Conclusion

Random Forest Regression performs better than Linear Regression in this case and therefore we will be using the Random Forest Regression Model to make predictions on the test dataset provided.

