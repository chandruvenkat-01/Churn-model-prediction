## 🏦 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn prediction is a classification problem that helps organizations identify customers who are likely to leave their services. This project uses Machine Learning techniques to analyze customer information and predict whether a customer will churn.

## 🎯 Objective

The objective of this project is to build a predictive model that can identify potential customer churners using customer demographic and financial information, enabling businesses to take proactive retention measures.

 
## 📂 Dataset Information

Dataset: Bank Customer Churn Dataset

Target Variable:

Exited
0 → Customer Retained
1 → Customer Churned

Features Used:

Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary
Surname
## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

Examined dataset structure and feature types.
Analyzed class distribution of churned and retained customers.
Identified class imbalance in the target variable.
Generated correlation analysis for numerical features.
Visualized feature distributions and outliers using boxplots.
Key Observation

The dataset was highly imbalanced, with retained customers significantly outnumbering churned customers.

## ⚙️ Data Preprocessing

Several preprocessing techniques were applied:

Feature Encoding
One-Hot Encoding for:
Geography
Gender
Target Encoding
Applied Target Encoding on the Surname feature.
Feature Scaling
StandardScaler was used to normalize numerical features.
Pipeline Construction
ColumnTransformer and Pipeline were implemented to automate preprocessing and model training.
## 🤖 Machine Learning Models Implemented
1. Logistic Regression

Used as a baseline classification model for churn prediction.

2. Decision Tree Classifier

Implemented to capture non-linear relationships within the data.

3. XGBoost Classifier

Applied gradient boosting techniques to improve predictive performance.

4. K-Nearest Neighbors (KNN)

Implemented distance-based classification for customer churn prediction.

## 📊 Initial Model Evaluation

Models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Classification Report
Observation

The models showed poor performance due to severe class imbalance in the dataset.

## ⚖️ Handling Class Imbalance

To improve prediction performance, sampling techniques were applied:

SMOTE (Synthetic Minority Oversampling Technique)
Increased minority class samples.
Sampling Strategy = 0.9
Random Under Sampling
Reduced majority class samples.
Created a balanced dataset for training.
## 🚀 Improved Model

After balancing the dataset:

Logistic Regression
Trained on balanced data.
Achieved significantly better performance on both training and testing datasets.
Improved recall and overall classification capability.
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Imbalanced-Learn
XGBoost
Seaborn
Matplotlib
## 📈 Project Workflow
Data Collection
       ↓
Exploratory Data Analysis
       ↓
Data Preprocessing
       ↓
Feature Encoding
       ↓
Feature Scaling
       ↓
Model Building
       ↓
Model Evaluation
       ↓
Class Imbalance Handling
       ↓
Model Retraining
       ↓
Final Prediction
## 🏆 Conclusion

Developed a Customer Churn Prediction system using multiple machine learning algorithms and advanced preprocessing techniques. Identified class imbalance as a major challenge and improved model performance using SMOTE and Random Under Sampling. The final balanced Logistic Regression model demonstrated improved predictive capability for customer churn detection.
