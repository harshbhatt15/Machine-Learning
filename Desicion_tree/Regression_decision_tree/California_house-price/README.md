# California Housing Price Prediction using Decision Tree Regressor

---

## Overview

This project predicts **median house values** using a
**Decision Tree Regressor** on the California Housing dataset.

The project demonstrates:
- Decision Tree training
- Visualization of the tree
- Overfitting analysis
- Cost–Complexity Pruning
- Hyperparameter tuning using GridSearchCV

---

## Dataset

Source:
- sklearn.datasets.fetch_california_housing

Target Variable:
- MedHouseVal (Median House Value)

---

## Features Used

- MedInc      → Median Income
- HouseAge    → Average House Age
- AveRooms    → Average Rooms
- AveBedrms   → Average Bedrooms
- Population  → Population
- AveOccup    → Average Occupancy
- Latitude    → Latitude
- Longitude   → Longitude

---

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## Data Preparation

Steps Performed:
- Loaded California Housing dataset
- Converted data into Pandas DataFrame
- Separated features (X) and target (Y)
- Checked dataset shape and summary statistics

---

## Train-Test Split

- Training data: 60%
- Testing data: 40%
- Random state: 42

---

## Model Used

Algorithm:
- Decision Tree Regressor

Library:
- sklearn.tree.DecisionTreeRegressor

Initial Parameters:
- max_depth = 3
- random_state = 42

---

## Model Training

- Decision Tree trained on training data
- Tree depth limited to avoid overfitting
- Learned nonlinear relationships in data

---

## Tree Visualization

- Decision tree plotted using:
  - plot_tree
- Features displayed at each split
- Nodes colored based on predicted value
- Helps interpret model decisions

---

## Model Evaluation

Metric Used:
- R² Score

Purpose:
- Measures how well the model explains variance in house prices

---

## Overfitting Demonstration

Evaluation Metrics:
- Mean Squared Error (MSE)

Calculated:
- Training MSE
- Testing MSE

Observation:
- Training and testing MSE values are close
- Indicates the model generalizes well
- No significant overfitting observed

---

## Cost–Complexity Pruning (CART)

Steps:
- Extracted cost–complexity pruning path
- Obtained different alpha (ccp_alpha) values
- Alpha controls tree complexity
- Higher alpha → simpler tree

Purpose:
- Reduce overfitting
- Improve generalization

---

## Hyperparameter Tuning

Technique Used:
- GridSearchCV with 5-fold cross-validation

Parameters Tuned:
- criterion
- max_depth
- splitter
- max_features

Scoring Metric:
- R² Score

Outcome:
- Best hyperparameters selected automatically
- Improved model performance on test data

---

## Final Evaluation

- Predictions made using best estimator
- R² score calculated on test dataset
- Model performance improved after tuning

---

## How to Run

1. Install required libraries:

   pip install pandas numpy matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Decision Trees handle nonlinear data well
- Depth control is crucial to avoid overfitting
- Pruning improves model stability
- GridSearchCV helps find optimal hyperparameters

---

## Author

Harsh Bhatt  
BCA Student
