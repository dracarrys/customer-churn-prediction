# Customer Churn Prediction

This project uses a real-world telecom dataset to predict whether a customer is likely to churn based on service usage, contract, billing, and demographic details.

## 🚀 Objective
Help businesses proactively retain customers by identifying those at high risk of churning using machine learning.

## 📂 Dataset
- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- Size: 7043 rows × 21 columns

## 🧠 Models Trained
- Logistic Regression
- Random Forest (with GridSearchCV tuning)
- SMOTE for balancing the classes

## 📊 Results
- Final Random Forest Accuracy: **76%**
- Recall for churners: **56%**

## 📈 Features Used
- MonthlyCharges
- TotalCharges
- Contract Type
- Internet Service
- Tech Support
- Tenure

## 📦 Libraries Used
- pandas, scikit-learn, seaborn, matplotlib
- imbalanced-learn (SMOTE)

## 📁 Folder Structure
