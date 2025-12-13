### 🫀 End-to-End Heart Disease Classification

A Research-Oriented Machine Learning Project

### 📌 Abstract

Heart disease is one of the leading causes of mortality worldwide. Early and accurate prediction can significantly improve clinical outcomes by identifying high-risk patients and prioritizing timely intervention. This project implements an end-to-end machine learning pipeline to predict the presence of heart disease from clinical data using supervised classification techniques. The focus is on data preprocessing, model development, evaluation, and comparative analysis of algorithms to determine their effectiveness in a real-world scenario. 
Rig Place


### 🎯 Problem Statement

In this project, the goal is to build a predictive model that classifies whether a patient has heart disease based on features such as age, sex, blood pressure, cholesterol, and other clinical measures. The task is a binary classification problem:

              𝑓:𝑅𝑛→{0,1}

Where:


`n` = number of clinical features

Output 0 = No heart disease

Output 1 = Heart disease present


### 📂 Dataset Overview

1. age - age in years

2. sex - 1 = male; 0 = female

3. cp - chest pain type

    * 0: Typical angina: chest pain related decrease blood supply to the heart

    * 1: Atypical angina: chest pain not related to heart

    * 2: Non-anginal pain: typically esophgael spasms (non heart related)

    * 3: Asymptomatic: chest pain not showing signs of disease

4. trestbps - resting blood pressure (in mm Hg on admission to the hospital)

5. chol - serum cholestoral in mg/dl

    * serum = LDL + HDL + .2 * triglycerides

    * above 200 is cause for concern

6. fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

    * '>126' mg/dL signals diabetes

7. restecg - resting electrocardiographic results

    * 0: Nothing to note

    * 1: ST-T Wave abnormality

        * can range from mild symptoms to severe problems

        * signals non-normal heart beat

    * 2: Possible or definite left venticular hypertrophy

        * Enlarged heart's main pumping chamber

8. thalach - maximum heart rate achieved

9. exang - exercise induced angina (1 = yes; 0 = no)

10. oldpeak - ST depression induced by exercise relative to rest

    * looks at stress of heart during excercise

    * unhealthy heart will stress more

11. slope - the slope of the peak exercise ST segment

    * 0: Unsloping: better heart rate with excercise (uncommon)

    * 1: Flatsloping: minimal change (typical healthy heart)

    * 2: Downsloping: Signs of unhealthy heart

12. ca - number of major vessels (0-3) colored by flourosopy

    * colored vessel means the doctor can see the blood passing through

    * the more blood movement the better (no clots)

13. thal - thalium stress result

    * 1,3 = normal 

    * 6 = fixed defect: Used to be defect but ok now 

    * 7 = reversable defect: no proper blood movement when excercising

14. target - have disease or not (1=yes, 0=no)


### 🧠 Exploratory Data Analysis (EDA)

EDA includes:

Checking for missing values and handling them appropriately

Evaluating feature distributions and class imbalance

Visualizing relationships between features and the target

Using plots such as histograms, correlation matrices, and scatter plots


### ⚙️ Preprocessing and Feature Engineering

Typical preprocessing steps:

Imputation of missing values (if any)

Encoding of categorical features

Feature scaling (e.g., Standard Scaling or Min-Max Scaling)

Splitting data into training and testing sets

Proper preprocessing ensures that models receive well-conditioned input


### 🛠 Technologies Used

Python

NumPy & Pandas

Scikit-Learn

Matplotlib / Seaborn

Jupyter Notebook


### 👨‍🎓 Author

Harsh Bhatt

Bachelor of Computer Applications (BCA)

Machine Learning & Data Science Enthusiast