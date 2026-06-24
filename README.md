# Electricity Consumption Forecasting

## Project Overview

This project predicts electricity consumption using Machine Learning techniques. Historical electricity consumption data from Tetouan City was analyzed to build forecasting models.

## Dataset

The dataset contains:

* Temperature
* Humidity
* Wind Speed
* General Diffuse Flows
* Diffuse Flows
* Zone 1 Power Consumption
* Zone 2 Power Consumption
* Zone 3 Power Consumption

Total Records: 52,416

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab
* Git
* GitHub

## Feature Engineering

Created additional features:

* Month
* Day
* Hour
* Weekday
* IsWeekend

## Models Used

### Linear Regression

* MAE: 3343.82
* R² Score: 0.649

### Random Forest Regression

* MAE: 611.79
* R² Score: 0.983

## Feature Importance

Top Features:

1. Hour
2. Temperature
3. Month

## Model Persistence

The trained Random Forest model was saved using Pickle and reused for future predictions.

## Results

Random Forest significantly outperformed Linear Regression and achieved high prediction accuracy.

## Future Improvements

* Time Series Forecasting
* Streamlit Web Application
* Real-time Power Consumption Prediction
