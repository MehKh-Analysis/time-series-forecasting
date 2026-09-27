# 📈 Time Series Forecasting

A collection of forecasting projects applying classical statistical models and machine learning to real-world time series: weather and retail sales.

> For my most in-depth forecasting work, see **[MSTL-ARIMA vs. Amazon Chronos](https://github.com/MehKh-Analysis/mstl-arima-vs-amazon-chronos-forecasting)**, a benchmark of a classical pipeline against a zero-shot foundation model on hourly grid demand.

## Projects

| Project | Question | Methods | Result |
|---|---|---|---|
| [🌦️ Weather forecasting](weather-forecasting/) | Can ML models forecast Delhi's daily weather from its own history? | Lag features, expanding-window validation, XGBoost, Random Forest | *[best model + RMSE/MAPE]* |
| [🛒 Retail sales forecasting](retail-sales-forecasting/) | What trend and seasonality drive superstore sales, and how well can they be forecast? | Decomposition, SARIMA | *[forecast accuracy]* |

## Tech

Python · pandas · statsmodels · scikit-learn · XGBoost · Matplotlib
