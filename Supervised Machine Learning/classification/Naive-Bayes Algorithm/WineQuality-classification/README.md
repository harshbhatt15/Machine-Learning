# 🍷 Wine Quality Prediction using Naive Bayes  
*A Supervised Machine Learning Multi-Class Classification Project*

---

## 📌 Project Overview

This project implements the **Gaussian Naive Bayes** algorithm to predict the **quality of red wine** based on its physicochemical properties.  
The goal is to classify wine samples into different **quality ratings** using probability-based learning.

The project demonstrates:
- Data loading and inspection  
- Feature–target separation  
- Training a Naive Bayes classifier  
- Model evaluation using **Accuracy** and **Confusion Matrix**

---

## 🎯 Problem Statement

Given several chemical properties of red wine, predict the **quality score** assigned to the wine.

### Input Features:
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

### Output:
- Wine quality score (multi-class label)

This is a **multi-class classification problem**.

---

## 📂 Dataset Description

- **Dataset Name:** Wine Quality – Red Wine  
- **Source:** Public wine quality dataset  
- **Type:** Structured tabular data  
- **Target Variable:** `quality`  

The dataset contains physicochemical test results of wines and corresponding quality ratings.

---

## 🔍 Exploratory Data Analysis (EDA)

The following analysis steps were performed:
- Inspecting dataset structure using `info()`  
- Checking dataset dimensions using `shape()`  
- Viewing class distribution using `value_counts()`  
- Previewing records using `head()`  

EDA helps understand **class imbalance** and data characteristics.

---

## ⚙️ Data Preparation

- Selected all numerical chemical attributes as features  
- Target variable set as wine quality  
- Dataset split into:
  - **80% Training**
  - **20% Testing**
- Random state fixed for reproducibility  

---

## 🧠 Naive Bayes Model

- **Algorithm Used:** Gaussian Naive Bayes  
- Suitable for continuous numerical features  
- Assumes features follow a **Gaussian distribution** and are conditionally independent  

The model was trained using the training dataset and tested on unseen data.

---

## 📈 Model Evaluation

### ✅ Accuracy Score
- Measures the proportion of correctly classified wine samples  

---

### 📊 Confusion Matrix
- Shows class-wise prediction performance  
- Helps identify which quality classes are frequently misclassified  

A visual confusion matrix was plotted to clearly interpret classification results across multiple classes.

---

## 🧠 Key Observations

- Naive Bayes performs reasonably well despite its strong independence assumptions  
- Accuracy is limited due to:
  - Class imbalance  
  - Overlapping feature distributions  
- Confusion matrix provides deeper insight than accuracy alone  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  
Bachelor of Computer Applications (BCA)  
Machine Learning Enthusiast  

---
