# Customer Segmentation

This project applies **unsupervised machine learning** techniques to segment mall customers based on their **Annual Income** and **Spending Score**.  
The goal is to identify distinct customer groups that businesses can use for **targeted marketing and strategy planning**.

---

## Features
- Loads and preprocesses the **Mall Customers dataset**
- Scales features using `StandardScaler`
- Applies **K-Means clustering** with the Elbow Method for optimal `k`
- Applies **DBSCAN clustering** for density-based segmentation
- Visualizes clusters before and after modeling
- Computes **Silhouette Score** for clustering performance
- Provides **cluster summaries** with mean income, mean spending score, and counts

---

## Dataset
The dataset used is `Mall_Customers.csv`  
It contains the following columns:
- `CustomerID`  
- `Annual Income (k$)`  
- `Spending Score (1-100)`  

> Place the dataset in the project root folder or adjust the `file_path` in the script.

---

##  Requirements
Install dependencies via `requirements.txt`.

