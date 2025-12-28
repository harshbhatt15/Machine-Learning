# California Housing Price Prediction using Lasso Regression

---

## Overview

This project predicts housing prices using **Lasso Regression**
on the California Housing dataset provided by scikit-learn.

Lasso Regression applies **L1 regularization**, which helps in
feature selection by shrinking less important feature coefficients
to zero.

---

## Dataset

Source:
- sklearn.datasets.fetch_california_housing

Target Variable:
- target (Median House Value)

---

## Features Used

- MedInc      → Median income
- HouseAge    → Average house age
- AveRooms    → Average number of rooms
- AveBedrms   → Average number of bedrooms
- Population  → Population
- AveOccup    → Average occupants
- Latitude    → Latitude
- Longitude   → Longitude

---

## Libraries Used

- pandas
- matplotlib
- scikit-learn

---

## Data Preparation

Steps Performed:
- Loaded California Housing dataset
- Converted dataset into Pandas DataFrame
- Selected input features and target variable
- Checked dataset columns and structure

---

## Train-Test Split

- Training data: 80%
- Testing data: 20%
- Random state: 42

---

## Model Used

Algorithm:
- Lasso Regression

Library:
- sklearn.linear_model.Lasso

Hyperparameter:
- alpha = 0.1

---

## Model Training

- Lasso Regression model trained using training data
- L1 regularization helps reduce overfitting
- Some feature coefficients may become zero

---

## Prediction

- Predictions generated on test dataset
- Output values are continuous housing prices

---

## Model Evaluation

Metric Used:
- R² Score

Purpose:
- Measures how well the model explains variance in housing prices

---

## Visualization

- Scatter plot between:
  - Actual values (X-axis)
  - Predicted values (Y-axis)
- Diagonal line represents perfect prediction
- Helps visualize model accuracy

---

## Output

- R² accuracy score printed
- Actual vs Predicted plot displayed

---

## How to Run

1. Install required libraries:

   pip install pandas matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Lasso Regression is effective for housing price prediction
- Useful for feature selection due to L1 regularization
- Visualization confirms model performance

---

## Author

Harsh Bhatt  
BCA Student
