# Insurance Charges Prediction using Linear Regression

---

## Overview

This project predicts medical insurance charges using
Linear Regression based on personal and health-related factors.

The model is trained on numerical and encoded categorical data
and evaluated using the R² score.

---

## Dataset

File Used:
- insurance.csv

Target Variable:
- charges

Input Features:
- age
- bmi
- children
- sex
- smoker

---

## Data Understanding

Steps Performed:
- Viewed dataset head
- Checked data types and non-null values
- Verified missing values
- Reviewed statistical summary
- Checked dataset shape and columns
- Observed region value counts

---

## Data Preprocessing

Categorical Encoding:
- sex:
  - male   → 0
  - female → 1
- smoker:
  - yes → 1
  - no  → 0

Selected Features:
- age
- bmi
- children
- sex
- smoker

---

## Libraries Used

- pandas
- matplotlib
- scikit-learn

---

## Train-Test Split

- Training data: 80%
- Testing data: 20%
- Random state: 42

---

## Model Used

Algorithm:
- Linear Regression

Library:
- sklearn.linear_model.LinearRegression

---

## Model Training

- Linear Regression model trained using training data
- Model learned relationship between input features and insurance charges

---

## Prediction

- Predictions generated on test dataset
- Output values are continuous numerical values

---

## Residual Analysis

- Residuals calculated as:
  - residual = actual value − predicted value
- Scatter plot created:
  - X-axis → Predicted charges
  - Y-axis → Residuals
- Red horizontal line at y = 0 indicates ideal fit

---

## Model Evaluation

Metric Used:
- R² Score

Purpose:
- Measures how well the model explains variance in insurance charges

---

## Output

- R² accuracy score printed
- Residual scatter plot displayed

---

## How to Run

1. Install required libraries:

   pip install pandas matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Linear Regression can effectively model insurance charges
- Encoding categorical variables is essential
- Residual analysis helps validate model assumptions

---

## Author

Harsh Bhatt  
BCA Student
GGIT