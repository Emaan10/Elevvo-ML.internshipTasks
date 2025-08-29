# Movie Recommendation System

A movie recommendation system built on the **MovieLens 100K dataset** using multiple approaches:  
- User-based Collaborative Filtering  
- Item-based Collaborative Filtering  
- Matrix Factorization (SVD)  

The project evaluates different methods using **Precision@K** and provides recommendation examples.

---

##  Dataset

- **Source:** [MovieLens 100K Dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)  
- **Contents:**  
  - `u.data` → user ratings (`userId`, `movieId`, `rating`, `timestamp`)  
  - `u.item` → movie metadata (`movieId`, `title`, …)  

This dataset contains **100,000 ratings** from **943 users** on **1,682 movies**.

---

## Features

- Data preprocessing (train-test split, cold-start handling).  
- User-Item rating matrix construction.  
- Collaborative Filtering:  
  - User-based similarity (cosine similarity).  
  - Item-based similarity (cosine similarity).  
- Dimensionality reduction using **Truncated SVD**.  
- Evaluation using **Precision@K**.  
- Recommendation output with movie titles.  

---

##  Results

### Precision@5 (first 10 users)

| userId | User-based Precision@5 | Item-based Precision@5 | SVD Precision@5 |
|--------|-------------------------|-------------------------|-----------------|
| 1      | 0.60                    | 0.40                    | 0.20            |
| 2      | 0.40                    | 0.60                    | 0.40            |
| ...    | ...                     | ...                     | ...             |

### Mean Precision@5
- **User-based:** ~0.52  
- **Item-based:** ~0.47  
- **SVD:** ~0.35  

> *Values may vary slightly depending on the random train-test split.*

---

## Requirements

Install dependencies:

```bash
pip install -r requirements.txt
