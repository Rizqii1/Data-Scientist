# Final Project - Data Scientist : Home Credit Indonesia x Rakamin Academy
This project focuses on predicting credit default risks based on historical data. The analysis includes data cleaning, exploratory data analysis (EDA), and predictive modeling using machine learning techniques.


## Project Overview
1. Problem Statement:
- Financial institutions face significant risks from customers who fail to repay their loans.
- There is a need for better methods to predict customers who may default before loan approval.
2. Objectives:
- Predict potential loan defaulters based on historical data.
- Help businesses mitigate loan default risks without hindering loans to creditworthy customers.

## Project Steps
### 1.  Data Preprocessing:
- Clean data: handle missing values, duplicates, and outliers.
- Label categorical data.
- Feature selection to identify important factors.
- Handle imbalanced data with SMOTE.
### 2. Exploratory Data Analysis (EDA):
- Perform Bivariate and Multivariate analysis.
- Investigate relationships like work duration, income, and default risk.
### 3. Model Building:
- Logistic Regression and Random Forest models.
- Evaluate models using accuracy and ROC-AUC.
  
## KEY INSIGHTS
### 1. Work Duration vs. Default Risk:
- Customers with shorter work durations (less than 3 years) are more likely to default.
- Recommendation: Prioritize customers with longer work durations for loan approval.
### 2. Income vs. Default Risk:
- No significant difference in average income between defaulters and non-defaulters.
- Recommendation: Consider other factors like work duration and credit history for risk assessment.

## MODEL PERFORMANCE
### 1. Random Forest:
- Training Accuracy: 1.00
- Testing Accuracy: 0.93
- ROC-AUC: 0.98
### 2. Logistic Regression:
- Training Accuracy: 0.69
- Testing Accuracy: 0.69
- ROC-AUC: 0.76

## BUSINESS RECOMMENDATIONS
- Target customers with higher external credit scores who own homes.
- Perform extra verification for customers from high-risk areas or with short work durations.
- Strengthen relationships with reliable customers through incentives and financial education.
