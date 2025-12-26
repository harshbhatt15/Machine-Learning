# House Rent Prediction using ElasticNet Regression

---

## Overview

This project predicts house rent prices using ElasticNet Regression.
The model uses numerical housing features to estimate rent and
evaluates performance using the R² score and visualization.

ElasticNet combines both L1 (Lasso) and L2 (Ridge) regularization,
making it suitable for datasets with multiple correlated features.

---

## Dataset

File Used:
- House_Rent_Dataset.csv

Target Variable:
- Rent

---

## Feature Selection

Removed Non-Numerical / Irrelevant Columns:
- Posted On
- Area Locality
- City
- Furnishing Status
- Tenant Preferred
- Point of Contact
- Floor
- Area Type
- Rent (removed from features, used as target)

Remaining Features:
- Numerical housing-related attributes

---

## Libraries Used

- pandas
- matplotlib
- scikit-learn

---

## Data Preparation

Steps Performed:
- Loaded dataset using Pandas
- Inspected columns and dataset shape
- Removed unnecessary and categorical columns
- Separated features (X) and target (Y)
- Checked dimensions of X and Y

---

## Train-Test Split

- Training data: 80%
- Testing data: 20%
- Random state: 42

---

## Model Used

Algorithm:
- ElasticNet Regression

Library:
- sklearn.linear_model.ElasticNet

Hyperparameters:
- alpha = 0.5
- l1_ratio = 0.5

---

## Model Training

- ElasticNet model trained using training data
- Model learned relationship between housing features and rent prices
- Regularization helps reduce overfitting

---

## Prediction

- Predictions generated on test dataset
- Output values are continuous rent values

---

## Model Evaluation

Metric Used:
- R² Score

Purpose:
- Measures how well the model explains variance in rent prices

---

## Visualization

- Scatter plot between:
  - Actual Rent (X-axis)
  - Predicted Rent (Y-axis)
- Diagonal line represents perfect prediction
- Grid added for clarity

---

## Output

- R² accuracy score printed
- Actual vs Predicted Rent plot displayed

---

## How to Run

1. Install required libraries:

   pip install pandas matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- ElasticNet is effective for rent prediction
- Combination of L1 and L2 regularization improves stability
- Visualization helps assess model performance

---

## Author

Harsh Bhatt  
BCA Student
