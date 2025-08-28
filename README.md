# Sales Analysis and Forecasting

## Overview
This repository contains the code, datasets, and documentation for the **Pharmaceutical Sales Analysis and Forecasting** project, developed by a team of nine for the **Cognizant Nurture Partner Network (NPN) Hackathon 2026**. The project validates time series data preparation, analysis, and forecasting methods to recommend sales and marketing strategies for pharmaceutical drug sales, leveraging trends, seasonality, and exogenous factors like holidays. The datasets are sourced from [Kaggle](https://www.kaggle.com/code/shresthabababuram/pharma-sales-timeseries-analysis/notebook).

### Objectives
- Perform Exploratory Data Analysis (EDA) to identify trends, seasonality, and stationarity.
- Develop and validate forecasting models, including a hybrid LSTM + XGBoost approach.
- Recommend inventory and marketing strategies based on insights (e.g., holiday sales drops, seasonal peaks).
- Deploy interactive visualizations via Streamlit and Power BI.

## Repository Structure
The repository is organized as follows (files to be added):

- **Dataset/**: Datasets for analysis and forecasting.
  - `SalesDaily.csv`: Daily sales for 8 drug categories (M01AB, M01AE, N02BA, N02BE, N05B, N05C, R03, R06).
  - `Saleshourly.csv`, `Salesweekly.csv`, `Salesmonthly.csv`, `SalesWeeklyScaled.csv`: Aggregated sales data.
  - `DatasetCreation.ipynb`: Seasonal decomposition, ACF/PCF plots, stationarity tests.
  - `Holiday.csv`: Holiday indicators for exogenous modeling.
- **Models/**: Jupyter notebooks for and modeling.
  - `models`: CatBoost Model, SARIMA Model, Random forest regressor Model, XGBoost Model, ARIMA Model, Auto ARIMA Model, LSTM x XGBoost Hybrid Model, GRU x XGBoost Hybrid Model, Naive forecast Model, Exponential Smoothing Model (Single, Double, Triple), Prophet Model, Dlinear Model, Tbats x prophet Hybrid Model, Light GBM, NBeats+LightGBM Hybrid implementations.
- **EDA**: Python scripts for Exploratory Data Analysis.
  - `initial_EDA.ipynb`: Data cleaning, feature engineering (lags, rolling stats).
  - `Holiday_seasonal_impact.ipynb`: Holiday indicators for exogenous modeling.
- **Documentation/**: Documentation and deliverables.
  - `Team Progress Document.pdf`: Daily progress (August 20–27, 2025).

## Installation
To set up the project environment (once files are uploaded):

1. Clone the repository:
   ```bash
   git clone https://github.com/Arun-hanzo/Sales_Analysis_and_Forecasting.git
   cd Sales_Analysis_and_Forecasting
