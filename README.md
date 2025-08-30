# Elevvo-ML.internshipTasks  

This repository contains Machine Learning projects completed during my **Elevvo Internship**.  
Each task focuses on solving a different ML problem and demonstrates my skills in data preprocessing, model building, evaluation, and visualization.  


## Repository Structure  


- **Task 1: Student Score Prediction**  
  Predicts student exam scores based on study hours and other features using **Linear & Polynomial Regression**.  
  - Includes **single vs multiple feature comparisons**  
  - Evaluation with **MAE, MSE, RMSE, R²**  
  - Visualizations: Scatter plots & Metric comparison charts  

- **Task 2: Customer Segmentation**  
  Segments mall customers using **K-Means** and **DBSCAN clustering**.  
  - Scales features with **StandardScaler**  
  - Uses **Elbow Method & Silhouette Score** for model selection  
  - Provides insights into distinct customer groups  
  - Visualizations: Clusters, Centroids, Noise points  

- **Task 3: Forest Cover Type Classification**  
  Classifies forest cover types using the **Covertype dataset**.  
  - Models: **Random Forest & XGBoost (Baseline & Tuned)**  
  - Evaluation: **Accuracy, Weighted F1-score**  
  - Visualizations: Confusion matrices & Top 30 feature importances  
  - Results: Random Forest achieved ~95% accuracy in baseline  

- **Task 4 – Walmart Sales Forecasting**  
  Time series forecasting of Walmart’s weekly sales.  
  - Feature engineering: **Lag features, Rolling averages, Time-based features**  
  - Models: **Random Forest, XGBoost, LightGBM**  
  - Evaluation: **RMSE & R² Score**  
  - Visualizations: Sales trends, Seasonal decomposition, Actual vs Predicted  
  - Best model: **LightGBM (R² ~0.88)**  

- **Task 5 – Music Genre Classification (GTZAN Dataset)**  
  Classifies music into **10 genres** (rock, jazz, classical, etc.) using audio features.  
  - Feature extraction: **MFCCs (Mel-Frequency Cepstral Coefficients)**  
  - Baseline: Random Forest on MFCCs  
  - Deep Learning: CNN on spectrogram-like MFCCs  
  - Visualizations: Confusion matrix, CNN training history, Spectrograms  

- **Task 6 – Movie Recommendation System**  
  Builds a recommender using **MovieLens 100K dataset**.  
  - Techniques:  
    - User-based Collaborative Filtering  
    - Item-based Collaborative Filtering  
    - Matrix Factorization (SVD)  
  - Evaluation: **Precision@K**  
  - Results: User-based achieved highest mean Precision@5 (~0.52)  

##  Key Skills Demonstrated  

- **Data Preprocessing**: Cleaning, handling missing values, scaling, encoding  
- **Supervised Learning**: Regression & Classification models  
- **Unsupervised Learning**: Clustering (K-Means, DBSCAN)  
- **Time Series Forecasting**: Feature engineering, seasonal decomposition  
- **Recommendation Systems**: Collaborative filtering & Matrix factorization  
- **Deep Learning**: CNNs for audio classification  
- **Evaluation Metrics**: MAE, MSE, RMSE, R², Accuracy, F1, Silhouette Score, Precision@K  
- **Visualization**: Scatter plots, Heatmaps, Confusion Matrices, Clusters, Time Series Trends  

  
##  Visualizations  

These projects include insightful visualizations such as:  

- Trends & distributions of features  
- Correlation heatmaps 
- Scatter plots of features vs targets  
- Clustering results (K-Means, DBSCAN)  
- Feature importance rankiings
- Confusion Matrices  
- Actual vs Predicted trends for forecasting models  
- CNN training curves & spectrograms
- Seasonal decomposition of time series  
- Recommendation results comparison  


##  Tools & Libraries  

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, XGBoost, LightGBM, TensorFlow/Keras
- **Environment:** Google Colab  
