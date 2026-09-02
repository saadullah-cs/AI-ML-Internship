# Week 2: EDA & Baseline Regression Modeling

## Overview
This week's project involved a deep dive into the **Steel Industry Energy Consumption Dataset**. The goal was to extract actionable features from time-series data and establish a predictive baseline for energy consumption. 

## Workflow
1.  **Exploratory Data Analysis (EDA):** Identified extreme usage spikes and mapped the correlation between reactive power metrics and total energy consumption.
2.  **Feature Engineering:** Extracted temporal features (hour, day of week, weekend indicator) from datetime strings and engineered a custom `Power_Factor_Ratio`.
3.  **Baseline Modeling:** Evaluated four regression architectures (Linear, Ridge, Decision Tree, Random Forest) using One-Hot Encoded categorical variables.

## Summary of Findings
The **Random Forest Regressor** significantly outperformed the linear models, achieving the lowest Test RMSE and successfully capturing the non-linear operational shifts of the heavy machinery. The data showed that energy spikes are highly dependent on specific operational hours and Maximum Load categorizations rather than random anomalies.

## Files in this Directory
*   `week2_eda.ipynb` - Data exploration and feature engineering pipeline.
*   `week2_baseline_models.ipynb` - Regression model training and evaluation.
*   `requirements.txt` - Project dependencies.
