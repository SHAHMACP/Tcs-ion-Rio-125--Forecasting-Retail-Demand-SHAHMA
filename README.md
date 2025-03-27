# Tcs-ion-Rio-125--Forecasting-Retail-Demand

## Project Overview
This project, developed by **SHAHMA CP**, aims to build a forecasting system to predict product demand at retail outlets based on historical sales data. The system utilizes various forecasting models, including moving averages, ARIMA models, and time series forecasting techniques, to accurately estimate future sales trends.

## Objective
The goal is to develop a robust model that can predict future sales by training on historical sales data. By leveraging time series forecasting methods, the model will help in making data-driven decisions for inventory management and sales optimization.

## Dataset
- **Time Span:** 2013 - 2017
- **Features:**
  - Date
  - Store
  - Item
  - Sales
- **Prediction Task:** Forecast the sales data for 2018 using historical trends.
- **Key Challenges:**
  - Different products are distributed across multiple stores.
  - Sales data exhibits seasonality and discrete characteristics.

## Feature Engineering
To enhance the forecasting model, feature engineering is applied to extract meaningful patterns:
- **Yearly Trends:** Extract year-wise sales patterns to identify long-term growth or decline.
- **Monthly Trends:** Capture seasonal variations and peak demand periods.
- **Daily Trends:** Identify weekly cycles and fluctuations in sales patterns.
- **Moving Averages:** Compute rolling averages to smooth out short-term fluctuations.
- **Lag Features:** Create lagged sales variables to incorporate past sales behavior into predictions.


## Models Used
- **Moving Averages**
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **Time Series Forecasting Techniques**

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

## Results
The project focuses on accurately predicting sales for 2018 using historical data while accounting for seasonal patterns, store-wise variations, and trend analysis.




![image](https://github.com/user-attachments/assets/6bcb5435-af29-461a-9ed8-712d81179feb)
