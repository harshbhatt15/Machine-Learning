# 📊 Logistic Regression: Height–Weight Classification  
*A Supervised Machine Learning Binary Classification Project*

---

## 📌 Project Overview

This project demonstrates the use of **Logistic Regression** to solve a **binary classification problem** using physical attributes.  
The goal is to predict a person’s **sex** based on their **height** and **weight**.

The project includes:
- Data loading and preprocessing  
- Label encoding for categorical variables  
- Feature visualization  
- Model training using Logistic Regression  
- Performance evaluation using **Accuracy**, **ROC Curve**, and **AUC Score**

---

## 🎯 Problem Statement

Given the physical attributes:
- **Height**
- **Weight**

Predict the **sex** of an individual.

This is a **binary classification problem** defined as:

f: ℝ² → {0,1}


Where:
- **0 / 1** → Encoded gender classes (using LabelEncoder)

---

## 📂 Dataset Description

- **Dataset Type:** Structured tabular data  
- **Features:**
  - Height  
  - Weight  
- **Target Variable:**
  - Sex (categorical → encoded to numeric)

📌 Since Logistic Regression works with numerical values, **Label Encoding** is applied to the target variable.

---

## 🔍 Exploratory Data Analysis (EDA)

Initial exploration included:
- Viewing the dataset using `head()`  
- Checking dataset dimensions using `shape()`  
- Inspecting feature distributions  

---

## 📊 Feature Visualization

A **2D scatter plot** was created to visualize the relationship between:
- **Height (X-axis)**
- **Weight (Y-axis)**

This visualization helps understand:
- Feature separation  
- Class overlap  
- Suitability of Logistic Regression  

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:
- Encoding the categorical target variable using **LabelEncoder**
- Feature–target separation  
- Train–test split (80% training, 20% testing)
- Random state fixed for reproducibility  

---

## 🧠 Model Training

- **Algorithm Used:** Logistic Regression  
- Model trained on training dataset  
- Predictions generated for test data  
- Probability estimates obtained using `predict_proba()`

---

## 📈 Model Evaluation

The model was evaluated using:

### ✅ Accuracy Score
- Measures the proportion of correctly classified samples

### 📉 ROC Curve
- Plots **True Positive Rate (TPR)** vs **False Positive Rate (FPR)**
- Includes a diagonal reference line representing random guessing

### 🔢 AUC Score
- Quantifies overall model performance
- Higher AUC indicates better class separation

---

## 🧠 Key Observations

- Logistic Regression performs well when features show reasonable linear separability
- Height and weight together provide meaningful predictive power
- ROC–AUC is a more reliable metric than accuracy alone

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
