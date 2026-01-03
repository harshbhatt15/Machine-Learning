# Iris Classification using Decision Tree Classifier

---

## Overview

This project demonstrates **classification on the Iris dataset**
using a **Decision Tree Classifier**.

The model classifies iris flowers into different species
based on their physical measurements and evaluates performance
using accuracy and a classification report.

---

## Dataset

Dataset Used:
- Iris Dataset (sklearn.datasets.load_iris)

Classes:
- Setosa
- Versicolor
- Virginica

Target Variable:
- target (flower species)

---

## Features

- sepal length (cm)
- sepal width (cm)
- petal length (cm)
- petal width (cm)

---

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## Data Collection and Analysis

Steps Performed:
- Loaded Iris dataset from scikit-learn
- Converted data into Pandas DataFrame
- Checked feature names and target names
- Viewed dataset samples
- Checked shape and data types
- Verified missing values
- Reviewed statistical summary

---

## Feature and Target Selection

- Features (X):
  - All columns except target
- Target (y):
  - Flower class label

---

## Train-Test Split

- Training data: 67%
- Testing data: 33%
- Random state: 42

---

## Model Used

Algorithm:
- Decision Tree Classifier

Library:
- sklearn.tree.DecisionTreeClassifier

---

## Model Training

- Decision Tree Classifier trained using training data
- Model learns decision rules from feature values

---

## Decision Tree Visualization

- Decision tree plotted using:
  - tree.plot_tree
- Shows:
  - Feature splits
  - Class labels
  - Decision paths
- Helps in understanding how the model makes decisions

---

## Prediction

- Predictions made on test dataset
- Output is the predicted iris species

---

## Model Evaluation

Metrics Used:
- Accuracy Score
- Classification Report

Classification Report Includes:
- Precision
- Recall
- F1-score
- Support

---

## Results

- Accuracy printed for test dataset
- Classification report displayed for detailed performance analysis

---

## How to Run

1. Install required libraries:

   pip install pandas numpy matplotlib scikit-learn

2. Run the Python script or Jupyter Notebook

---

## Conclusion

- Decision Tree performs well on Iris classification
- Model is easy to interpret due to tree structure
- Suitable for multi-class classification problems

---

## Author

Harsh Bhatt  
BCA Student
