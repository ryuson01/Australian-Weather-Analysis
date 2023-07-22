# Australian-Weather-Analysis

## Overview
Welcome to the Australian Weather Analysis project! In this project, we will explore ten years of Australian weather information, spanning from 2008 to 2017. The dataset consists of over 145,000 instances across 23 columns, capturing various weather attributes for different locations in Australia.

## Project Objectives
The primary objectives of this project are as follows:

1. Exploratory Data Analysis: We will conduct a comprehensive exploration of the weather dataset to gain insights into various weather patterns and trends over the ten-year period.
2. Multiple Regression Analysis: We aim to identify associated variables that contribute significantly to specific weather occurrences, such as rainfall and temperature fluctuations.
3. Classification Modeling: Utilizing the binary variables, "Rain Today" and "Rain Tomorrow," we will implement classification algorithms to predict future instances of rainfall.
4. Model Evaluation: We will evaluate the performance of our regression and classification models to assess their accuracy and predictive power.

## Dataset Description
Sourced from Kaggle, _AustraliaWeatherData.csv_ contains weather information for various locations in Australia, and consists of the following features:
- **Date**: The date of the recorded weather data.
- **Location**: The specific city or location in Australia.
- **MinTemp**: The minimum temperature in degrees Celsius.
- **MaxTemp**: The maximum temperature in degrees Celsius.
- **Rainfall**: The amount of rainfall in millimeters.
- **Evaporation**: The amount of evaporation in millimeters.
- **Sunshine**: The number of hours of bright sunshine.
- **WindGustDir**: The direction of the strongest wind gust.
- **WindGustSpeed**: The speed of the strongest wind gust in kilometers per hour.
- **WindDir9am**: The wind direction at 9 am.
- **WindDir3pm**: The wind direction at 3 pm.
- **WindSpeed9am**: The wind speed at 9 am in kilometers per hour.
- **WindSpeed3pm**: The wind speed at 3 pm in kilometers per hour.
- **Humidity9am**: The relative humidity at 9 am as a percentage.
- **Humidity3pm**: The relative humidity at 3 pm as a percentage.
- **Pressure9am**: The atmospheric pressure at 9 am in hectopascals.
- **Pressure3pm**: The atmospheric pressure at 3 pm in hectopascals.
- **Cloud9am**: The fraction of sky covered by clouds at 9 am, measured in oktas (eighths).
- **Cloud3pm**: The fraction of sky covered by clouds at 3 pm, measured in oktas (eighths).
- **Temp9am**: The temperature at 9 am in degrees Celsius.
- **Temp3pm**: The temperature at 3 pm in degrees Celsius.
- **RainToday**: A binary variable indicating whether it rained on the day the data was recorded (Yes/No).
- **RainTomorrow**: A binary variable indicating whether it is predicted to rain the day after the data was recorded (Yes/No).
