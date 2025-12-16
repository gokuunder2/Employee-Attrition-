#🧠 Employee Attrition Analysis & Prediction
📌 Project Overview

Employee attrition is a major challenge for organizations, leading to increased recruitment costs and loss of experienced talent.
This project focuses on analyzing employee attrition patterns and building a machine learning model to predict whether an employee is likely to leave the organization.

The project uses Exploratory Data Analysis (EDA), feature engineering, and Logistic Regression to uncover key factors influencing attrition and evaluate model performance using multiple metrics.

#🎯 Objectives

Understand employee attrition patterns using data visualization

Perform feature engineering and encoding

Build and evaluate a classification model

Identify the most influential factors affecting attrition

Provide actionable HR insights

#📂 Dataset

Source: HR Employee Attrition Dataset

Format: CSV

Target Variable: Attrition

1 → Employee left

0 → Employee stayed

🛠️ Technologies & Libraries Used

Python

Pandas, NumPy

Matplotlib

Scikit-Learn

Google Colab

🔄 Project Workflow
1️⃣ Data Loading & Inspection

Loaded dataset from Google Drive

Checked data types, missing values, and descriptive statistics

2️⃣ Data Preprocessing

Binary encoding using lambda functions

One-hot encoding for categorical features

Removal of irrelevant columns

Feature scaling using StandardScaler

3️⃣ Feature Engineering

Created:

TenureBucket

MonthlyGroup

AgeGroup

Transformed them into dummy variables

4️⃣ Exploratory Data Analysis (EDA)

Key visualizations include:

Overall attrition distribution

Attrition rate by gender

Attrition rate by overtime

Department-wise attrition

Tenure, age, and income-based attrition trends

5️⃣ Model Building

Logistic Regression classifier

Stratified train-test split

Model training on standardized features

6️⃣ Model Evaluation

Evaluation metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Score

Visual evaluation:

Confusion Matrix

ROC Curve

7️⃣ Feature Importance Analysis

Used Logistic Regression coefficients

Identified top features influencing employee attrition

Visualized:

Impact strength (absolute coefficients)

Direction of influence (positive / negative)

📊 Key Insights

OverTime is one of the strongest predictors of attrition

Employees with lower tenure are more likely to leave

Income level and job role significantly impact attrition

Logistic Regression provides good interpretability for HR decision-making

#✅ Model Performance (Sample)
Accuracy  : ~0.86
Precision : ~0.75
Recall    : ~0.70
F1 Score  : ~0.72
ROC AUC   : ~0.84


(Exact values may vary depending on data split)

#📁 Repository Structure
📦 Employee-Attrition-Analysis
 ┣ 📜 README.md
 ┣ 📓 Employee_Attrition_Analysis.ipynb
 ┣ 📂 data
 ┃ ┗ 📄 HR-Employee-Attrition.csv

#🚀 Future Enhancements

Add Balanced Logistic Regression

Apply XGBoost / Random Forest

Perform hyperparameter tuning

Build a dashboard using Streamlit or Power BI

Deploy model as a web application

#🧠 Business Impact

This analysis helps HR teams:

Identify high-risk employees

Reduce attrition through proactive interventions

Improve employee retention strategies

#📬 Contact

Author: Prashant Pal
📧 Email:prashantpal029@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/prashant-pal-855b09268
