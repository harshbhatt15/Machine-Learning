# 📊 Logistic Regression on Social Ads Dataset  
*A Supervised Machine Learning Classification Project*

---

## 📌 Project Overview

This project demonstrates the application of **Logistic Regression** for solving a **binary classification problem** using a real-world **Social Ads dataset**.

The goal is to predict whether a user **purchases a product or not** based on their:
- **Age**
- **Estimated Salary**

### The project covers:
- Data loading and visualization  
- Model training using Logistic Regression  
- Model evaluation using:
  - Accuracy
  - ROC Curve
  - AUC Score  

---

## 🎯 Problem Statement

Given a user’s demographic information:
- **Age**
- **Estimated Salary**

Predict whether the user will **purchase a product**.

This is a **binary classification problem** defined as:

\[
f: \mathbb{R}^2 \rightarrow \{0,1\}
\]

Where:
- **0** → Not Purchased  
- **1** → Purchased  

---

## 📂 Dataset Description

- **Dataset Name:** Social Ads Dataset  
- **Features:**
  - Age  
  - EstimatedSalary  
- **Target Variable:**  
  - Purchased (Binary)

This dataset is suitable for demonstrating:
- Decision boundaries  
- Probability-based classification  

---

## 🔍 Exploratory Data Analysis (EDA)

Initial exploration included:
- Viewing sample records using `head()`  
- Inspecting column names  
- Checking dataset dimensions using `shape()`  

### Feature Visualization
A scatter plot was used to visualize feature distribution:
- **X-axis:** Age  
- **Y-axis:** Estimated Salary  

This visualization helps understand:
- Class overlap  
- Model complexity  

---

## 📊 Observations from Visualization

- Younger users with lower salaries tend to **not purchase**
- Older users with higher salaries show **higher purchase probability**

This confirms the suitability of **Logistic Regression** for this problem.

---

## 🧠 Model Training & Evaluation

- **Algorithm used:** Logistic Regression  
- Model trained on training dataset  
- Predictions made on test data  

### Evaluation Metrics:
- Accuracy Score  
- ROC Curve  
- AUC Score  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

### 👨‍🎓 Author

Harsh Bhatt

Bachelor of Computer Applications (BCA)

Machine Learning & Data Science Enthusiast