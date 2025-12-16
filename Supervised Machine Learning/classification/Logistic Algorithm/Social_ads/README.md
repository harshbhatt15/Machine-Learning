### 📊 Logistic Regression on Social Ads Dataset

A Supervised Machine Learning Classification Project




### 📌 Project Overview

This project demonstrates the application of Logistic Regression for solving a binary classification problem using a real-world Social Ads dataset.
The goal is to predict whether a user purchases a product or not based on their Age and Estimated Salary.

The project covers:
Data loading and visualization
Model training using Logistic Regression
Model evaluation using Accuracy, ROC Curve, and AUC score




### 🎯 Problem Statement

Given a user’s demographic information:

Age

Estimated Salary

Predict whether the user will purchase a product.

This is a binary classification problem defined as:

         f:R2→{0,1}

Where:

0 → Not Purchased
1 → Purchased



### 📂 Dataset Description

Dataset Name: Social Ads Dataset
Features:
Age
EstimatedSalary
Target Variable:
Purchased (Binary)
The dataset is suitable for demonstrating decision boundaries and probability-based classification.




### 🔍 Exploratory Data Analysis (EDA)

Initial exploration included:

Viewing sample records using head()

Inspecting column names

Checking dataset dimensions using shape

A scatter plot was used to visualize feature distribution:

X-axis: Age

Y-axis: Estimated Salary

This visualization helps understand class overlap and model difficulty.

### 📊 Feature Visualization

A 2D scatter plot was created to observe how data points are distributed across the feature space:

Younger users with lower salaries tend to have fewer purchases

Older users with higher salaries show higher purchase probability

This confirms the suitability of Logistic Regression.



### 🧠 Model Training

Algorithm used: Logistic Regression
Model trained on training dataset
Predictions made on test data
Model performance was evaluated using:
Accuracy score
ROC Curve
AUC score


### 🛠️Technologies Used

Python
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook