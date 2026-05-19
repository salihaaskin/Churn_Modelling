# Bank Customer Churn Prediction

## Project Overview

This project predicts customer churn for a bank using machine learning classification models. The goal is to identify customers who are likely to leave the bank and provide data-driven business recommendations to improve customer retention.

The analysis combines Exploratory Data Analysis (EDA), predictive modeling, model evaluation, and business interpretation.

## Business Problem

Customer churn leads to revenue loss and increased customer acquisition costs. The main business question is:

> Which customers are most likely to churn, and what actions can the bank take to reduce customer loss?

## Dataset

The dataset contains customer-level banking information, including demographic, financial, and behavioral attributes.

## Models Used

Three classification models were trained and compared:

1. Logistic Regression
2. Random Forest
3. XGBoost

GridSearchCV was applied to tune hyperparameters and improve model performance.

## Model Evaluation

Models were evaluated using:

- Precision
- Recall
- ROC AUC
- Confusion Matrix

## Selected Model

Random Forest was selected as the final model because it achieved the highest recall while maintaining strong ROC AUC performance.

This means the model is better at identifying customers who are likely to churn, which is important for reducing customer loss.

## Feature Importance

Random Forest feature importance and permutation importance were used to identify the most important churn drivers.

Top churn drivers:

- Age
- Number of Products
- Balance
- IsActiveMember
- Geography

Business interpretation:

- Older customers are more likely to churn.
- Product usage significantly impacts customer retention.
- Inactive customers are more likely to leave.
- Account balance influences churn risk.
- Geographic differences affect churn behavior.

## Business Outcome

By leveraging predictive analytics and targeted retention strategies, the bank can reduce customer churn while establishing a sustainable approach to long-term customer engagement and growth.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Statsmodels

