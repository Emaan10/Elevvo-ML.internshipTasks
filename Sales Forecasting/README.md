# Walmart Sales Forecasting

This project focuses on **time series forecasting** of Walmart's weekly sales using machine learning models.  
We explore historical sales data, engineer features such as lags and rolling averages, and apply regression models to predict future sales.



## Project Overview

- **Dataset:** [Walmart Sales Forecast (Kaggle)](https://www.kaggle.com/aslanahmedov/walmart-sales-forecast)  
- **Objective:** Predict future weekly sales based on historical data and store features.  
- **Techniques:**  
  - Time series feature engineering (lags, rolling averages)  
  - Seasonal decomposition  
  - Regression-based forecasting models  


## Features

- Download and preprocess Walmart sales data automatically with `kagglehub`.
- Merge multiple datasets (`train.csv`, `features.csv`, `stores.csv`) into a single dataset.
- **Feature engineering:**
  - Time-based features (year, month, week, day)  
  - Rolling averages (7, 14, 30 days)  
  - Lag features (1, 2, 3 weeks)
- **Visualization of:**
  - Total weekly sales trend  
  - Seasonal decomposition of sales  
  - Actual vs predicted sales  
- **Models applied:**
  - Random Forest Regressor  
  - XGBoost Regressor
  - LightGBM Regressor

## Visualizations

The code generates plots such as:

- Total Walmart Weekly Sales Over Time  
- Seasonal Decomposition of Weekly Sales  
- Actual vs Predicted Sales (RF, XGB, LGBM)

 
## Results

The models were evaluated using **RMSE (Root Mean Squared Error)** and **R² Score**.  

| Model         | RMSE      | R² Score |
|---------------|-----------|----------|
| RandomForest  | 18726.53  | 0.8721   |
| XGBoost       | 19345.67  | 0.8614   |
| LightGBM      | 18230.15  | 0.8795   |

- **Best Model → LightGBM** (lowest RMSE, highest R²)  
- Visualizations (Actual vs Predicted) confirm LightGBM provides the closest fit to real sales trends.
