# Diabetes Prediction using Ridge Regression

---

## Overview

This project uses Ridge Regression to predict diabetes disease progression
using the built-in Diabetes dataset from scikit-learn.

The model is trained on multiple medical features and evaluated
using the R² (coefficient of determination) score.

---

## Dataset

Source:
- sklearn.datasets.load_diabetes

Features:
- age
- sex
- bmi
- bp
- s1
- s2
- s3
- s4
- s5
- s6

Target:
- target (diabetes disease progression)

---

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## Data Preparation

Steps:
- Load the dataset
- Convert data into a Pandas DataFrame
- Separate features (X) and target (Y)
- Split data into training and testing sets

Train-Test Split:
- Training data: 80%
- Testing data: 20%
- Random state: 42

---

## Model

Algorithm:
- Ridge Regression

Regularization:
- L2 regularization

Alpha value:
- 0.1

---

## Model Training

- The Ridge Regression model is trained using training data
- Model learns optimal weights for all input features

---

## Prediction

- Predictions are made on test data
- Output values are continuous numerical values

---

## Evaluation

Metric Used:
- R² Score

Purpose:
- Measures how well the model explains variance in the target variable

---

## Visualization

- Scatter plot between:
  - Actual values
  - Predicted values

- Red diagonal line indicates perfect prediction

---

## Output

- R² score printed in console
- Graph showing actual vs predicted diabetes progression

---

## How to Run

Install required libraries:

pip install pandas numpy matplotlib scikit-learn

Run the Python script or Jupyter Notebook.

---

## Conclusion

- Ridge Regression handles multicollinearity well
- Regularization helps reduce overfitting
- Model performance can be visually analyzed using plots

---

## Author

Harsh Bhatt  
BCA Student
