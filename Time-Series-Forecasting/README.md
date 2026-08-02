# Time Series Analysis & Forecasting
Forecasting daily retail sales using ARIMA, SARIMA, and regression with ARIMA errors in R.

## Overview
Comparison of six time series forecasting models using the Corporación Favorita Store Sales dataset.

## Methods
- Data preparation
- EDA
- Stationarity testing (ADF, KPSS)
- ARIMA & SARIMA
- Regression with ARIMA Errors
- Model evaluation

## Key Results
- Best in-sample fit: Regression with ARIMA Errors (AIC = 43,123)
- **Final model: SARIMA(2,0,0)(0,1,2)[7]** — selected for deployment since it
  forecasts from sales history alone, without depending on future values of
  Transactions/Oil Price that aren't available at forecast time
- Test RMSE: 90,042.94
- Test MAPE: 7.05%

## Tools
- R
- forecast
- tseries
- ggplot2

## Repository Contents
- `Report.pdf` — Project report
- `Time_Series_Forecasting.Rmd` — R Markdown source


