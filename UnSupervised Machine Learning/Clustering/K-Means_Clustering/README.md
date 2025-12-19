# 🛍️ Customer Segmentation using K-Means Clustering  
*An Unsupervised Machine Learning Project*

---

## 📌 Project Overview

This project applies **K-Means clustering** to segment mall customers based on their **Annual Income** and **Spending Score**.  
The goal is to group customers into meaningful clusters using **unsupervised learning**, without any target labels.

The workflow includes:
- Data loading and inspection  
- Feature selection  
- Finding the optimal number of clusters using the **Elbow Method**  
- Training the K-Means model  
- Visualizing clusters and centroids  

---

## 📂 Dataset Description

- **Dataset Name:** Mall Customers Dataset  
- **Type:** Structured tabular data  
- **Key Columns Used:**
  - Annual Income (k$)  
  - Spending Score (1–100)  

---

## 🔍 Data Collection & Analysis

The dataset was loaded from a CSV file into a Pandas DataFrame.  
Initial analysis included:
- Viewing sample records  
- Checking dataset dimensions  
- Inspecting data types  
- Verifying missing values  

The dataset was found to be clean with no missing values.

---

## ⚙️ Feature Selection

Only the following features were selected for clustering:
- **Annual Income (k$)**  
- **Spending Score (1–100)**  

These features are commonly used for customer segmentation.

---

## 📉 Choosing the Number of Clusters (Elbow Method)

- **WCSS (Within-Cluster Sum of Squares)** was calculated for cluster counts ranging from 1 to 10  
- WCSS values were stored and plotted  
- An **Elbow Graph** was used to identify the optimal number of clusters  

📌 Based on the elbow point, the **optimal number of clusters was chosen as 5**.

---

## 🧠 Model Training

- **Algorithm Used:** K-Means Clustering  
- **Initialization Method:** k-means++  
- **Number of Clusters:** 5  
- **Random State:** Fixed for reproducibility  

Each data point was assigned a cluster label.

---

## 📊 Cluster Visualization

- All clusters were visualized using a scatter plot  
- Each cluster is represented with a different color  
- **Centroids** of the clusters were plotted in black  

The visualization clearly shows customer groups based on income and spending behavior.

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
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
