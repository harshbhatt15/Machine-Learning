# 📍 Clustering using DBSCAN  
*An Unsupervised Machine Learning Project*

---

## 📌 Project Overview

This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to cluster data points based on **Weight** and **Height**.  
DBSCAN groups points that are closely packed together and identifies outliers as noise.

The project workflow includes:
- Data loading and inspection  
- Feature selection  
- Data visualization  
- DBSCAN model training  
- Cluster label analysis  

---

## 📂 Dataset Description

- **Type:** Structured tabular data  
- **Features Used:**
  - Weight  
  - Height  

The dataset is suitable for density-based clustering.

---

## 🔍 Data Collection & Analysis

The dataset was loaded from a CSV file into a Pandas DataFrame.  
Initial analysis included:
- Viewing sample records  
- Checking dataset dimensions  
- Inspecting data types  

---

## ⚙️ Feature Selection

Only the following numerical features were selected for clustering:
- **Weight**
- **Height**

These features were directly used without scaling in this implementation.

---

## 📊 Data Visualization

A scatter plot was created to visualize the data distribution:
- **X-axis:** Weight  
- **Y-axis:** Height  

This visualization helps in understanding point density before clustering.

---

## 🧠 Model Training

- **Algorithm Used:** DBSCAN  
- **Parameters:**
  - `eps = 0.5`  
  - `min_samples = 5`  

The model was fitted on the selected features to identify clusters and noise points.

---

## 📈 Clustering Results

- Cluster labels were generated for each data point  
- Noise points were labeled as `-1`  
- The number of points in each cluster was counted and displayed  
- We can also say that cluster 4 is also a noise point

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  
Bachelor of Computer Applications (BCA)  
Machine Learning Enthusiast  

---
