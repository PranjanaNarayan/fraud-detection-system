# Credit Card Fraud Detection System

## Problem Statement
Credit card companies lose millions to fraud every year.
This system detects fraudulent transactions in real time.

## Solution
Built a 3-tier fraud detection system:
- Logistic Regression (baseline)
- Random Forest
- XGBoost with SHAP Explainability (best model)

## Results
- ROC-AUC Score: 0.98
- Dataset: 284,807 transactions, only 0.17% fraud
- Handled class imbalance using SMOTE

## Tech Stack
Python | XGBoost | SMOTE | SHAP | Scikit-learn | Google Colab
