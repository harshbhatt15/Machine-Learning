# 💳 Customer Segmentation using K-Medoids Clustering  
*An Unsupervised Machine Learning Project*

---

## 📌 Project Overview

This project applies **K-Medoids clustering** to segment customers based on their **credit card usage behavior**.  
K-Medoids is a robust clustering algorithm similar to K-Means, but it uses **actual data points (medoids)** as cluster centers, making it less sensitive to outliers.

The project workflow includes:
- Data loading and inspection  
- Feature selection based on variance  
- Handling missing values  
- Feature scaling  
- Training the K-Medoids clustering model  
- Analyzing and visualizing cluster distribution  

---

## 📂 Dataset Description

- **Dataset Name:** Credit Card Dataset (CC GENERAL)  
- **Type:** Structured tabular data  
- **Description:** Customer-level credit card usage statistics  

The customer ID column was removed as it is not useful for clustering.

---

## 🔍 Data Collection & Analysis

The dataset was loaded into a Pandas DataFrame and analyzed using:
- Dataset structure inspection (`info()`)  
- Shape and summary checks  
- Variance analysis to identify informative features  
- Missing value inspection  

---

## ⚙️ Feature Selection

Columns with **high variance** were selected to improve clustering effectiveness.  
The selected features represent customer spending, payment behavior, and credit usage patterns.

---

## 🧹 Data Preprocessing

- Missing values in `MINIMUM_PAYMENTS` and `CREDIT_LIMIT` were filled using mean values  
- Features were standardized using **StandardScaler**  
- Scaled data was converted back into a DataFrame for consistency  

---

## 🧠 Model Training

- **Algorithm Used:** K-Medoids  
- **Number of Clusters:** 5  
- **Random State:** Fixed for reproducibility  

The model was trained on the scaled feature set, and cluster labels were generated for each data point.

---

## 📊 Clustering Results

- Each customer was assigned a cluster label  
- Cluster labels were added back to the original dataset  
- The number of customers in each cluster was calculated  

---

## 📈 Cluster Distribution Visualization

A **bar chart** was plotted to visualize:
- Cluster labels on the X-axis  
- Number of customers in each cluster on the Y-axis  

This visualization helps understand how customers are distributed across clusters.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Scikit-learn-extra  
- Matplotlib  
- Jupyter Notebook  

---

## 👨‍🎓 Author

**Harsh Bhatt**  
Bachelor of Computer Applications (BCA)  
Machine Learning Enthusiast  

---
