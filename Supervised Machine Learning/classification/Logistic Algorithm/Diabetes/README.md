# 🩺 Diabetes Prediction using Logistic Regression  
*A Supervised Machine Learning Classification Project*

---

## 📌 Project Overview

This project applies **Logistic Regression** to predict whether a patient is **diabetic or not** using medical and demographic features.  
It demonstrates a complete machine learning workflow including data exploration, model training, and evaluation using **ROC Curve** and **AUC score**.

The project includes:
- Data loading and inspection  
- Feature visualization  
- Train–test splitting  
- Logistic Regression model training  
- Model evaluation using Accuracy, ROC Curve, and AUC  

---

## 🎯 Problem Statement

Given medical and demographic information about a patient, the goal is to predict whether the patient has **diabetes**.

### Input Features:
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  

### Output:
- `0` → Not Diabetic  
- `1` → Diabetic  

This is a **binary classification problem**.

---

## 📂 Dataset Description

- **Dataset Name:** Diabetes Dataset  
- **Type:** Structured tabular data  
- **Target Variable:** Outcome (Binary)  

The dataset contains health-related attributes commonly used for diabetes diagnosis.

---

## 🔍 Exploratory Data Analysis (EDA)

The following steps were performed:
- Viewing the dataset using `df.info()`  
- Checking dataset dimensions using `df.shape`  
- Calculating mean values using `df.mean()`  
- Checking missing values using `df.isnull().sum()`  

These steps help understand data quality and feature characteristics.

---

## 📊 Feature Visualization

A **scatter plot** was created to visualize feature relationships:
- **X-axis:** Age  
- **Y-axis:** Glucose  

This plot helps in understanding:
- Feature distribution  
- Potential separation between diabetic and non-diabetic cases  

---

## ⚙️ Data Preparation

- Selected relevant medical features as input  
- Target variable set as `Outcome`  
- Data split into:
  - **60% Training**
  - **40% Testing**
- Random state fixed for reproducibility  

---

## 🧠 Model Training

- **Algorithm Used:** Logistic Regression  
- Maximum iterations set to `1000` for better convergence  
- Model trained using training data  

Predictions were generated using:
- `predict()` for class labels  
- `predict_proba()` for probability estimates  

---

## 📈 Model Evaluation

### ✅ Accuracy Score
Measures how many predictions were classified correctly.

---

### 📉 ROC Curve
The **Receiver Operating Characteristic (ROC) Curve** plots:
- True Positive Rate (TPR)  
- False Positive Rate (FPR)  

A diagonal line represents random guessing, while a curve closer to the top-left indicates better performance.

---

### 🔢 AUC Score
The **Area Under the Curve (AUC)** summarizes the ROC curve into a single value.

- AUC close to 1 → Strong classifier  
- AUC close to 0.5 → Weak classifier  

The calculated AUC shows the model performs **better than random guessing**.

---

## 🧠 Key Observations

- Logistic Regression works well for binary medical classification problems  
- Glucose and Age are influential features  
- ROC–AUC provides better insight than accuracy alone  
- Increasing `max_iter` helps avoid convergence issues  

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
