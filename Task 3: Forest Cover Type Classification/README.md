# Forest Cover Type Classification

This project classifies forest cover types using the Covertype dataset (from scikit-learn).  
It applies Random Forest and XGBoost classifiers, evaluates performance, visualizes feature importance, and performs hyperparameter tuning for improved accuracy.

## Features  

- Loads dataset directly from `sklearn.datasets.fetch_covtype`  
- Implements two models:  
  - **Random Forest** (Baseline & Tuned)  
  - **XGBoost** (Baseline & Tuned)  
- Evaluates models with **Accuracy** and **Weighted F1-score**  
- Visualizes:  
  - Confusion Matrices (Random Forest & XGBoost)  
  - Top 30 Feature Importances for both models  
- Compares **baseline vs tuned models** in a final results table  

## Dataset  

- **Dataset:** Forest Cover Type  
- **Source:** UCI Covertype dataset
  - Available on **Kaggle** as a competition dataset  
  - Also available in **scikit-learn** via `sklearn.datasets.fetch_covtype()`    
- **Target:** Predict the type of forest cover (7 classes)  

