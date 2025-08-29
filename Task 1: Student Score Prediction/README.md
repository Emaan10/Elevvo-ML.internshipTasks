# Student Score Prediction 

This project explores **student performance prediction** based on various factors such as study hours and other numeric features.  
We apply **Linear Regression** and **Polynomial Regression** models to predict students' exam scores, evaluate their performance using multiple metrics, and visualize the results.

---

## Dataset
- File used: **StudentPerformanceFactors.csv**  
- The dataset contains student-related factors (e.g., hours studied, attendance, family background, etc.)  
- Target variable: **`exam_score`**

---

## Features
- **Data Preprocessing**
  - Handles missing values
  - Renames columns to standardized lowercase format
- **Visualization**
  - Bar charts comparing R², MAE, MSE, RMSE for both models
  - Scatter plot of `hours_studied` vs `exam_score`
- **Modeling**
  - Linear Regression
  - Polynomial Regression (degree = 2 by default)
- **Evaluation Metrics**
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- **Comparison**
  - Single feature (`hours_studied`)
  - Multiple numeric features

---
## Results

### Single Feature (`hours_studied → exam_score`)

| Model       | R²    | MAE   | MSE    | RMSE |
|-------------|-------|-------|--------|------|
| Linear      | 0.205 | 2.52  | 12.17  | 3.49 |
| Polynomial  | 0.205 | 2.52  | 12.16  | 3.49 |

### Multiple Features (All numeric predictors → `exam_score`)

| Model       | R²    | MAE   | MSE   | RMSE |
|-------------|-------|-------|-------|------|
| Linear      | 0.615 | 1.31  | 5.90  | 2.44 |
| Polynomial  | 0.611 | 1.33  | 5.95  | 2.44 |

## Requirements
Install the required libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

