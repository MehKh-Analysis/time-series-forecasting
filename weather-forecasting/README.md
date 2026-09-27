#  Weather Forecasting with Machine Learning

Forecasting Delhi's weather (2013–2017) using machine learning on time series data. The dataset includes temperature, humidity, wind speed, and pressure.

## Approach

- **EDA:** trends and seasonality in each weather variable
- **Feature engineering:** lag features to turn the series into a supervised learning problem
- **Validation:** comparing a fixed lag-feature split against an expanding-window approach
- **Models:** XGBoost (lag features), XGBoost (expanding window), Random Forest
- **Evaluation:** RMSE, MAE, and MAPE



## Files

- `weather_forecasting.ipynb`: full analysis
