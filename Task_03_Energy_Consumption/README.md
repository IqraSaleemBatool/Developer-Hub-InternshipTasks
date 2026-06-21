
# Energy Consumption Forecasting (Time Series Project)

## Overview

This project focuses on forecasting household energy consumption using historical time-series data. The goal is to compare multiple models and identify the best-performing approach.

---

## Objective

* Analyze energy usage patterns over time
* Perform feature engineering on time-series data
* Build forecasting models
* Compare performance using MAE and RMSE

---

## Dataset

Household Power Consumption Dataset
Contains:

* Date & Time
* Global Active Power
* Voltage, Intensity
* Sub-metering values

---

## Tools & Libraries Used

Python, Pandas, NumPy, Matplotlib
Statsmodels (ARIMA), Prophet, XGBoost, Scikit-learn

---

## Workflow

* Data preprocessing & datetime conversion
* Time-series resampling (hourly data)
* Feature engineering (hour, day, month)
* Model training (ARIMA, Prophet, XGBoost)
* Evaluation using MAE & RMSE

---

##  Results

| Model   | MAE    | RMSE   |
| ------- | ------ | ------ |
| Prophet | 0.6656 | 0.9357 |
| ARIMA   | 0.8933 | 1.1131 |
| XGBoost | 0.8971 | 1.2351 |

---

##  Conclusion

Prophet performed best with the lowest error, making it the most suitable model for this dataset.

---
