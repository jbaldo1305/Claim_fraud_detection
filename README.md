# Claim_fraud_detection
## Project Overview

This project develops a machine learning model to detect potentially fraudulent auto insurance claims using customer, policy, incident, and claim-related data.

The objective is to improve fraud detection performance while minimizing missed fraudulent claims.

## Business Problem

Insurance fraud creates significant financial losses for insurance companies. Detecting fraudulent claims early can help reduce unnecessary payouts and improve investigation efficiency.

Because fraudulent claims are relatively rare, this project focuses heavily on improving recall to capture as many fraud cases as possible.

## Dataset

Dataset used:

Auto Insurance Claims Dataset from Kaggle

https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data

## Project Workflow

Data Cleaning

Feature Selection

Feature Engineering

Handling Missing Values

Encoding & Preprocessing

Baseline Modeling

SMOTE for Imbalance Handling

Model Comparison

Hyperparameter Tuning

Threshold Tuning

## Models Used

Logistic Regression

Random Forest

Gradient Boosting

## Key Techniques

SMOTE

One-Hot Encoding

StandardScaler

Threshold Tuning

GridSearchCV

Feature Engineering

## Final Results

### Best Model:

Logistic Regression + SMOTE + Threshold Tuning

### Improvements:

Recall improved from 0.53 → 0.81

False negatives reduced from 23 → 9

This significantly improved fraud detection performance.

## Business Impact

The final model can help insurance companies:

Identify suspicious claims earlier

Reduce fraudulent payouts

Improve investigation prioritization

## Future Improvements

XGBoost

Larger datasets

Additional behavioral features

More advanced hyperparameter tuning

## Technologies Used
Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn
Matplotlib
Seaborn
