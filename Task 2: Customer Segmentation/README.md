# Customer Segmentation

This project applies **unsupervised machine learning** techniques to segment mall customers based on their **Annual Income** and **Spending Score**.  
The goal is to identify distinct customer groups that businesses can use for **targeted marketing and strategy planning**.


## Features
- Loads and preprocesses the **Mall Customers dataset**
- Scales features using `StandardScaler`
- Applies **K-Means clustering** with the Elbow Method for optimal `k`
- Applies **DBSCAN clustering** for density-based segmentation
- Visualizes clusters before and after modeling
- Computes **Silhouette Score** for clustering performance
- Provides **cluster summaries** with mean income, mean spending score, and counts


## Dataset
The dataset used is `Mall_Customers.csv`  
It contains the following columns:
- `CustomerID`  
- `Annual Income (k$)`  
- `Spending Score (1-100)`  

> Place the dataset in the project root folder or adjust the `file_path` in the script.


##  Requirements
Install dependencies via `requirements.txt`

## Results  

### K-Means Clustering (k=5)  

| Cluster | Avg. Annual Income (k$) | Avg. Spending Score | Count |
|---------|--------------------------|---------------------|-------|
| 0       | ~55.3                   | ~49.5               | 81    |
| 1       | ~86.5                   | ~82.1               | 39    |
| 2       | ~25.7                   | ~79.4               | 22    |
| 3       | ~88.2                   | ~17.1               | 35    |
| 4       | ~26.3                   | ~20.9               | 23    |

**Silhouette Score (K-Means):** ~0.555  


## Visualizations  

- Elbow Method curve (for optimal K)  
- K-Means clusters with centroids  
- DBSCAN clusters with noise points  
