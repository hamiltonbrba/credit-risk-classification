
# Module 12 Report

## Overview of the Analysis

This analysis aims to predict whether a loan is likely to be high risk or healthy. By predicting credit risk, lenders can make smarter decisions about approving or denying loans, which helps in managing financial risks.

The dataset includes information about various loan factors, like loan amount, interest rate, and the borrower's income. The target variable, `loan_status`, shows whether each loan is high risk (labeled as `1`) or healthy (labeled as `0`). Since most loans in the data are healthy, this presents an imbalanced dataset.

The analysis followed these main steps:
1. **Data Preparation**: We split the data into features (predictors) and labels (target) and then divided it into training and testing sets.
2. **Model Training**: We used a logistic regression model, a popular method for binary classification, to make predictions on the loan status.
3. **Evaluation**: We checked the model’s performance with metrics like accuracy, precision, and recall to see how well it predicted both high-risk and healthy loans.



## Results

* **Logistic Regression Model**:
    - **Accuracy**: 99% — showing the overall correctness of the model.
    - **Precision** (for high-risk loans): 0.84 — meaning that 84% of loans labeled as high risk by the model were actually high risk.
    - **Recall** (for high-risk loans): 0.94 — meaning the model correctly identified 94% of all actual high-risk loans.



**Classification Report**:

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

     accuracy                          0.99     19384
     macro avg     0.92      0.97      0.94     19384
     weighted avg  0.99      0.99      0.99     19384



## Summary

The logistic regression model is very effective for predicting loan status, with a high accuracy of 99%. This means it correctly identifies healthy and high-risk loans nearly all the time.

The model’s **recall** for high-risk loans is 94%, meaning it correctly catches most of the high-risk loans, which is essential in managing financial risk. The **precision** for high-risk loans is 0.84, which is solid, although it does mean that a few healthy loans might be mistakenly flagged as high risk.

Overall, this logistic regression model is a good choice for predicting credit risk. It effectively identifies risky loans, which helps lenders make safer lending choices and manage their financial exposure.


