# 🛍️ Customer Segmentation using Hierarchical Clustering  
*An Unsupervised Machine Learning Project*

---

## 📌 Project Overview

This project applies **Hierarchical (Agglomerative) Clustering** to segment mall customers based on their **Annual Income** and **Spending Score**.  
The objective is to group customers into meaningful clusters without using labeled data.

The project includes:
- Data loading and inspection  
- Data preprocessing  
- Exploratory visualization  
- Dendrogram construction  
- Agglomerative clustering using Ward linkage  

---

## 📂 Dataset Description

- **Dataset Name:** Mall Customers Dataset  
- **Type:** Structured tabular data  
- **Key Columns:**
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)

---

## 🔄 Data Preprocessing

- The `Gender` column was converted into numerical form:
  - Male → 1  
  - Female → 0  
- Dataset was checked for missing values  
- Only numerical columns were used for clustering  

---

## 🔍 Exploratory Data Analysis (EDA)

The following visualizations were created:
- Pair plot to observe relationships between numerical features  
- Scatter plot between:
  - Annual Income  
  - Spending Score  

These plots help understand customer distribution before clustering.

---

## 🌳 Dendrogram Analysis

A **dendrogram** was plotted using:
- Ward linkage method  
- Euclidean distance  

The dendrogram helps visualize how clusters are formed and assists in choosing the number of clusters.

---

## 🧠 Clustering Model

- **Algorithm Used:** Agglomerative Clustering  
- **Linkage Method:** Ward  
- **Number of Clusters:** 3  
- **Features Used:**
  - Annual Income (k$)  
  - Spending Score (1–100)  

Cluster labels were assigned to each customer.

---

## 📊 Cluster Visualization

- A scatter plot was created to visualize clusters  
- Each cluster is shown using a different color  
- Customers with similar income and spending behavior are grouped together  

---

## 📈 Cluster Distribution

The number of customers in each cluster was calculated to understand cluster size and distribution.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SciPy  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  
Bachelor of Computer Applications (BCA)  
Machine Learning Enthusiast  

---
