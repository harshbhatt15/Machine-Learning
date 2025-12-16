# 🛡️ Bought Insurance Prediction using Logistic Regression  
*A Supervised Machine Learning Binary Classification Project*

---

## 📌 Project Overview

This project applies **Logistic Regression** to predict whether a person has **bought insurance or not** based on their **age**.  
It demonstrates a simple yet effective binary classification workflow using a real-world dataset.

The project includes:
- Data loading and inspection  
- Feature visualization  
- Model training using Logistic Regression  
- Model evaluation using **Accuracy**, **ROC Curve**, and **AUC Score**

---

## 🎯 Problem Statement

Given a person’s:
- **Age**

Predict whether the person has **bought insurance**.

### Output Classes:
- `0` → Not Bought Insurance  
- `1` → Bought Insurance  

This is a **binary classification problem**.

---

## 📂 Dataset Description

- **Dataset Name:** Insurance Dataset  
- **Type:** Structured tabular data  
- **Feature:**
  - Age  
- **Target Variable:**
  - bought_insurance (Binary)

The dataset is small and ideal for understanding **probability-based classification**.

---

## 🔍 Exploratory Data Analysis (EDA)

The following steps were performed:
- Inspecting dataset shape using `shape()`  
- Checking data types using `info()`  
- Verifying missing values using `isnull().sum()`  

These steps confirm the dataset is clean and suitable for modeling.

---

## 📊 Feature Visualization

A **scatter plot** was created to visualize the relationship between:
- **Age**
- **Bought Insurance**

This visualization shows how the probability of buying insurance increases with age, supporting the use of Logistic Regression.

---

## ⚙️ Data Preparation

- Feature selected: `age`  
- Target variable: `bought_insurance`  
- Dataset split into:
  - **40% Training**
  - **60% Testing**
- Random state fixed for reproducibility  

---

## 🧠 Model Training

- **Algorithm Used:** Logistic Regression  
- Model trained on training dataset  
- Predictions generated for test data  
- Probability estimates obtained using `predict_proba()`

---

## 📈 Model Evaluation

### ✅ Accuracy Score
- Evaluates how well the model predicts insurance purchase on test data  
- Suitable for this dataset due to its small size  

---

### 📉 ROC Curve
- Plots **True Positive Rate** vs **False Positive Rate**  
- Includes a diagonal line representing random guessing  

A curve closer to the top-left corner indicates better performance.

---

### 🔢 AUC Score
- Measures the model’s ability to distinguish between classes  
- Higher AUC indicates better predictive performance  

The obtained AUC score shows the model performs **better than random guessing**.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  
Bachelor of Computer Applications (BCA)  
Machine Learning Enthusiast  

---
