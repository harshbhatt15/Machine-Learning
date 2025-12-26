# Advertising Sales Prediction using Linear Regression

---

## Overview

This project predicts product sales using Linear Regression
based on advertising expenditure across different media channels.

The model analyzes how TV, radio, and newspaper advertising
affect sales and evaluates performance using regression metrics.

---

## Dataset

File Used:
- Advertising (1).csv

Target Variable:
- sales

Input Features:
- TV
- radio
- newspaper

---

## Libraries Used

- numpy
- pandas
- matplotlib
- scikit-learn

---

## Data Preparation

Steps Performed:
- Loaded dataset using Pandas
- Selected input features and target variable
- Checked feature and target values
- Split data into training and testing sets

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

- Linear Regression model trained on training data
- Model learned relationship between advertising spend and sales

---

## Prediction

- Predictions generated on test dataset
- Output values are continuous numerical values

---

## Residual Analysis

- Residuals calculated as:
  - residual = actual value − predicted value
- Scatter plot created:
  - X-axis → Predicted sales
  - Y-axis → Residuals
- Red horizontal line at y = 0 indicates ideal model fit

---

## Model Evaluation

Metrics Used:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

Purpose:
- R² → Explains variance in sales
- MAE → Average absolute error
- MSE → Penalizes large errors

---

## Output

- R² accuracy score printed
- Residual scatter plot displayed

---

## How to Run

1. Install required libraries:

   pip install numpy pandas matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Linear Regression effectively models sales prediction
- TV and radio ads significantly influence sales
- Residual plot helps validate model assumptions

---

## Author

Harsh Bhatt  
BCA Student
