# Student Performance Prediction using Linear Regression

---

## Overview

This project predicts a student's Performance Index using
Linear Regression based on study habits, past performance,
sleep hours, practice, and extracurricular activities.

---

## Dataset

File Used:
- Student_Performance.csv

Target Variable:
- Performance Index

Input Features:
- Hours Studied
- Previous Scores
- Sleep Hours
- Sample Question Papers Practiced
- Extracurricular Activities

---

## Data Preprocessing

Steps Performed:
- Loaded dataset using Pandas
- Checked dataset information and shape
- Converted categorical values:
  - Yes → 1
  - No  → 0
- Selected features (X) and target (y)

---

## Libraries Used

- numpy
- pandas
- matplotlib
- scikit-learn

---

## Train-Test Split

- Training data: 70%
- Testing data: 30%
- Random state: 42

---

## Model Used

Algorithm:
- Linear Regression

Library:
- sklearn.linear_model.LinearRegression

---

## Model Training

- Model trained on training dataset
- Learned relationship between features and performance index

---

## Prediction

- Predictions made on test data
- Output is continuous numerical values

---

## Residual Analysis

- Residuals calculated as:
  - residual = actual value − predicted value
- Scatter plot created:
  - X-axis → Predicted values
  - Y-axis → Residuals
- Red horizontal line at y = 0 indicates ideal fit

---

## Model Evaluation

Metric Used:
- R² Score (Coefficient of Determination)

Purpose:
- Measures how well the model explains variance in data

---

## Output

- R² accuracy score printed
- Residual plot displayed

---

## How to Run

1. Install required libraries:
   
   pip install numpy pandas matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Linear Regression effectively predicts student performance
- Residual plot helps verify model assumptions
- R² score evaluates overall model performance

---

## Author

Harsh Bhatt  
BCA Student
