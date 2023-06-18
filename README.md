# Bike Sharing Demand Prediction

## Project Overview

In this project, we aim to predict bike rental demand in the Capital Bikeshare program in Washington, D.C using historical usage patterns in relation to weather, time, and other data. The dataset is available from the UCI Machine Learning Repository.

## Data

The dataset includes the hourly and daily count of rental bikes between the years 2011 and 2012 in the Capital Bikeshare system with the corresponding weather and seasonal information.

## Features

- `instant`: record index
- `dteday`: date
- `season`: season (1:spring, 2:summer, 3:fall, 4:winter)
- `yr`: year (0: 2011, 1:2012)
- `mnth`: month (1 to 12)
- `hr`: hour (0 to 23)
- `holiday`: whether the day is considered a holiday
- `weekday`: day of the week
- `workingday`: if day is neither weekend nor holiday
- `weathersit`: weather situation
- `temp`: normalized temperature in Celsius
- `atemp`: normalized feeling temperature in Celsius
- `hum`: normalized humidity
- `windspeed`: normalized wind speed
- `casual`: count of casual users
- `registered`: count of registered users
- `cnt`: count of total rental bikes including both casual and registered

## Methods Used

- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation
- Model Interpretation
- Cross Validation
- Hyperparameter Tuning

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Model Performance

The best performing model was Gradient Boosting Regressor with a mean squared error of 5.80 on the test data after hyperparameter tuning.
