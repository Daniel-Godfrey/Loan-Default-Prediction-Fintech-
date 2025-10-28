# Loan-Default-Prediction-Fintech

A machine learning project that predicts the likelihood of loan default using fintech customer data. This project demonstrates data cleaning, feature engineering, model building, and evaluation — all built in Python.

# Overview

Goal: Predict whether a loan applicant will default or repay.

Data: Fintech customer dataset (fintech_loan_default_dataset.csv) with 20,000 records.

Models Used: Logistic Regression & Random Forest

Output: Trained model (loan_default_model.pkl) + feature importance visualization

# Tech Stack

Python · Pandas · Scikit-learn · Seaborn · Matplotlib

Jupyter / Google Colab compatible

# Results

Random Forest achieved the best ROC-AUC and PR-AUC scores.

Feature importance analysis highlights credit score, income, and previous defaults as top predictors.

# Files

loan_default_pipeline.py → main ML pipeline

fintech_loan_default_dataset.csv → dataset

loan_default_model.pkl → trained model
