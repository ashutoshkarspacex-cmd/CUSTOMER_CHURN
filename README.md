
# 📊 Customer Churn Prediction using Random Forest Classifier

## 📌 Overview
This project focuses on predicting **customer churn** using Machine Learning.  
It analyzes customer data to determine whether a customer is likely to **leave a service**.

The workflow includes **Exploratory Data Analysis (EDA)** and building a **Random Forest Classifier** for accurate prediction.

---

## 🎯 Objectives
- Analyze customer behavior and patterns  
- Identify key factors influencing churn  
- Build a robust classification model  
- Improve prediction accuracy using ensemble learning  

---

## 🛠️ Libraries Used
- Scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  
- ydata-profiling  

---

## 📂 Dataset
- Customer churn dataset (included in repository)  
- Contains customer-related features such as usage, demographics, and service details  

---

## 🔍 Workflow

### 1. Data Preprocessing
- Handled missing values  
- Cleaned dataset  
- Prepared features for modeling  

---

### 2. Exploratory Data Analysis (EDA)
- Performed detailed EDA using:
  - **ydata-profiling** (auto-generated HTML report)  
- Insights include:
  - Feature distributions  
  - Correlations  
  - Data imbalance  
  - Outliers  

---

### 3. Model Building

#### 🌲 Random Forest Classifier
- Ensemble learning method  
- Combines multiple decision trees  
- Final prediction based on **majority voting**

---

### 4. Key Concepts

#### 🔁 Bagging (Bootstrap Aggregation)
- Training data is split into multiple subsets  
- Each decision tree is trained on different samples  
- Reduces variance and improves stability  

#### 🌿 Feature Randomness
- Each tree uses a different subset of features  
- Helps reduce correlation between trees  

---

### 5. Why Random Forest?
- Handles overfitting better than a single decision tree  
- More robust and accurate  
- Works well with structured/tabular data  

---

### ⚠️ Decision Tree Limitation
- A single decision tree:
  - Does not use bootstrapping  
  - Has a higher chance of overfitting  

---

### 🚀 Optimization (Future Scope)
- **Bayesian Optimization** can be applied to:
  - Tune hyperparameters  
  - Improve model performance  
  - Find optimal feature combinations  

---

## 📊 Model Evaluation
precision    recall  f1-score   support

           0       0.84      0.90      0.87      1311
           1       0.62      0.48      0.54       447
 
 
    accuracy                           0.79      1758
   macro avg       0.73      0.69      0.70      1758
weighted avg       0.78      0.79      0.78      1758

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## 💡 Features
- End-to-end ML pipeline  
- Automated EDA report generation  
- Ensemble learning using Random Forest  
- Scalable and robust model  

