# 🩻 Breast Cancer Classification using Logistic Regression  
*A Supervised Machine Learning Binary Classification Project*

---

## 📌 Project Overview

This project implements **Logistic Regression** to classify breast cancer tumors as **malignant or benign** using the built-in **Breast Cancer dataset** from Scikit-learn.

The project demonstrates:
- Working with a real medical dataset  
- Feature analysis and visualization  
- Training a Logistic Regression model  
- Model evaluation using **ROC Curve** and **AUC score**

---

## 🎯 Problem Statement

Given multiple numerical features extracted from breast mass images, the objective is to **predict whether the tumor is malignant or benign**.

### Input:
- 30 numerical features such as:
  - Mean radius  
  - Mean texture  
  - Mean perimeter  
  - Mean area  
  - And other related features  

### Output:
- `0` → Malignant  
- `1` → Benign  

This is a **binary classification problem**.

---

## 📂 Dataset Description

- **Dataset:** Breast Cancer Wisconsin Dataset  
- **Source:** Scikit-learn (`load_breast_cancer`)  
- **Number of Features:** 30  
- **Target Classes:** Malignant and Benign  

The dataset is widely used for evaluating classification algorithms in medical diagnosis.

---

## 🔍 Exploratory Data Analysis (EDA)

The following analysis steps were performed:
- Inspecting feature names and target labels  
- Creating a DataFrame from the dataset  
- Computing mean values for numerical features  
- Inspecting data types and structure  

EDA helps understand feature distributions and data quality.

---

## 📊 Feature Visualization

A **scatter plot** was created using:
- **X-axis:** Mean Radius  
- **Y-axis:** Mean Texture  

This visualization helps observe:
- Feature relationships  
- Class separability  
- Suitability of Logistic Regression  

---

## ⚙️ Data Preparation

- Features selected by removing the target column  
- Target variable extracted as tumor class  
- Data split into:
  - **70% Training**
  - **30% Testing**
- Random state fixed for reproducibility  

---

## 🧠 Model Training

- **Algorithm Used:** Logistic Regression  
- Maximum iterations set to `10000` to ensure convergence  
- Model trained on training dataset  

Predictions generated using:
- `predict()` for class labels  
- `predict_proba()` for probability scores  

---

## 📈 Model Evaluation

### 📉 ROC Curve
- Plots **True Positive Rate** vs **False Positive Rate**
- Includes diagonal reference line for random guessing

### 🔢 AUC Score
- Measures overall classification performance  
- Higher AUC indicates better class separation  

The obtained AUC score shows the model performs **significantly better than random guessing**.

---

## 🧠 Key Observations

- Logistic Regression performs well for high-dimensional medical data  
- Increasing `max_iter` improves convergence  
- ROC–AUC is a strong metric for medical classification tasks  

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