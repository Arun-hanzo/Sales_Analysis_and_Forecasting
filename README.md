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

- **data/**: Datasets for analysis and forecasting.
  - `SalesDaily.csv`: Daily sales for 8 drug categories (M01AB, M01AE, N02BA, N02BE, N05B, N05C, R03, R06).
  - `Saleshourly.csv`, `Salesweekly.csv`, `Salesmonthly.csv`: Aggregated sales data.
  - `Holiday.csv`: Holiday indicators for exogenous modeling.
- **notebooks/**: Jupyter notebooks for EDA and modeling.
  - `eda.ipynb`: Seasonal decomposition, ACF/PCF plots, stationarity tests.
  - `modeling.ipynb`: LSTM + XGBoost, Prophet, ARIMA, SARIMA, CatBoost implementations.
- **src/**: Python scripts for modular code.
  - `preprocess.py`: Data cleaning, feature engineering (lags, rolling stats).
  - `train_model.py`: Model training and prediction.
  - `app.py`: Streamlit app for interactive forecasts.
- **docs/**: Documentation and deliverables.
  - `progress_report.pdf`: Daily progress (August 20–27, 2025).
  - `presentation.pptx`: Hackathon PPT slides.
  - `architecture.png`: System architecture diagram.
- **requirements.txt**: Python dependencies (to be added).
- **LICENSE**: MIT License (to be added).

## Installation
To set up the project environment (once files are uploaded):

1. Clone the repository:
   ```bash
   git clone https://github.com/Arun-hanzo/Sales_Analysis_and_Forecasting.git
   cd Sales_Analysis_and_Forecasting
