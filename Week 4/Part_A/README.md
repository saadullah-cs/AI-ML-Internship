# Week 4, Part A: Time-Series Forecasting Models

## Overview
This module establishes a production-grade time-series forecasting pipeline. The objective is to analyze univariate temporal data, confirm stationarity properties, and benchmark classical statistical methods against modern additive models. 

## Architectures Implemented
1.  **ARIMA (Auto-Regressive Integrated Moving Average):** Utilizes `pmdarima` for automated differencing ($d$) and grid-search hyperparameter selection ($p, q$) based on the Akaike Information Criterion (AIC).
2.  **Prophet:** Developed by Meta, this additive regression model decomposes the time series into trend and seasonal components, robustly handling missing data and non-linear trends.

## Data Pipeline
*   **Dataset:** Daily Minimum Temperatures (10-year span, 3650 observations).
*   **Validation:** Augmented Dickey-Fuller (ADF) test for stationarity; Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) profiling.
*   **Evaluation:** 80/20 chronological train/test split. Benchmarked via Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).