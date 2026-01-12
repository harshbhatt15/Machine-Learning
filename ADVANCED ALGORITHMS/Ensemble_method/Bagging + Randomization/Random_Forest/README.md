# 🍷 Wine Quality Prediction Using Random Forest Classifier

---

## 📌 Project Overview

This project aims to predict the **quality of red wine** using **Machine Learning**, specifically the **Random Forest Classifier**.  
The model classifies wine into **good quality** and **bad quality** categories based on physicochemical properties.

This project demonstrates:
- Exploratory Data Analysis (EDA)
- Feature correlation analysis
- Binary classification
- Ensemble learning using Random Forest

---

## 📊 Dataset Description

The dataset contains physicochemical attributes of red wine samples.

### 🔹 Input Features
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

### 🔹 Target Variable
- `quality` (integer score between 0 and 10)

### 🔹 Label Binarization
- `1` → Good quality wine (quality ≥ 7)
- `0` → Bad quality wine (quality < 7)

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Machine Learning Algorithm

### 🌲 Random Forest Classifier

- Ensemble learning algorithm
- Uses bagging and feature randomness
- Reduces overfitting
- Provides robust and accurate predictions

---

## 📈 Exploratory Data Analysis (EDA)

Performed the following steps:
- Checked for missing values
- Analyzed statistical distribution
- Visualized quality distribution
- Compared features with quality
- Generated correlation heatmap

### 🔍 Key Observations
- Volatile acidity is inversely proportional to wine quality
- Citric acid and residual sugar are positively correlated with quality

---

## ⚙️ Data Preprocessing

- Separated features and labels
- Converted target variable into binary classes
- Train-test split:
  - 80% training data
  - 20% testing data

---

## 🧪 Model Training & Evaluation

- Model: Random Forest Classifier
- Evaluation Metric: Accuracy Score


---

👨‍💻 Author

Harsh Bhatt
BCA Student | Machine Learning Enthusiast

---
