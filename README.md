# Bike Sharing Demand Forecasting

This repository houses a comprehensive project focusing on demand forecasting for a bike-sharing service. This exercise employs machine learning techniques to predict hourly bike rental demand, utilizing data provided by the Capital Bikeshare program in Washington D.C.

## Table of Contents
1. [Overview](#Overview)
2. [Data Description](#Data-Description)
3. [Data Processing](#Data-Processing)
4. [Exploratory Data Analysis](#Exploratory-Data-Analysis)
5. [Feature Engineering](#Feature-Engineering)
6. [Modeling](#Modeling)
7. [Model Evaluation](#Model-Evaluation)
8. [Conclusion and Future Work](#Conclusion-and-Future-Work)

## Overview

Understanding demand for a bike-sharing system can greatly enhance its success and improve customer satisfaction. By predicting the volume of customers in different seasons, weather conditions, and times of the day, we can aid the organization in maintaining optimal operations.

## Data Description

The dataset comprises hourly rental data spanning two years. It includes the following features:
1. datetime - hourly date + timestamp  
2. season - 1 = spring, 2 = summer, 3 = fall, 4 = winter 
3. holiday - whether the day is considered a holiday
4. workingday - whether the day is neither a weekend nor holiday
5. weather - categorized into 4 types from clear to severe
6. temp - temperature in Celsius
7. atemp - "feels like" temperature in Celsius
8. humidity - relative humidity
9. windspeed - wind speed
10. casual - number of non-registered user rentals initiated
11. registered - number of registered user rentals initiated
12. count - number of total rentals

## Data Processing

Data Processing involved converting the 'date' column into a format that could be processed by a machine learning model. Missing values were dealt with accordingly.

## Exploratory Data Analysis

Comprehensive exploratory data analysis was conducted to understand the relationships and patterns in the data. Data visualization tools were employed to aid in this process.

## Feature Engineering

Feature Engineering was performed to create features from existing data that better represent the underlying problem to the predictive models. This can lead to an improvement in model performance.

## Modeling

Several machine learning models were used in this project, such as Decision Trees, Random Forests, Gradient Boosting and XGBoost.

## Model Evaluation

Models were evaluated using different evaluation metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and the Coefficient of Determination (R^2 score). Cross-validation was also used to ensure the robustness of the models.

## Conclusion and Future Work

This project provided a comprehensive analysis and prediction of bike rental demand. For future work, hyperparameter tuning and the utilization of more sophisticated models could potentially improve model performance.

Please feel free to explore this project and provide any feedback or questions.

## Acknowledgements

Capital Bikeshare ([Link](https://www.capitalbikeshare.com/system-data)) for providing the dataset.
