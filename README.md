# Credit Risk Analysis with Logistic Regression

## Overview
This project applies a logistic regression model to predict the credit risk of loans, aiming to assist lenders in identifying loans that may be high risk versus healthy. Using historical loan data, this analysis provides insights into factors that contribute to loan risk, allowing for data-driven decision-making.

## Data
The dataset includes financial information about each loan, such as:

Loan amount
Interest rate
Borrower’s income level
Loan status (0 = healthy, 1 = high risk)
Objectives
Data Preparation: Split the data into features (X) and target labels (y), then separate it into training and testing datasets.
Model Training: Create a logistic regression model using the training data.
Evaluation: Evaluate the model's performance using accuracy, precision, and recall to understand its ability to identify high-risk loans.
Results
The logistic regression model produced the following key metrics:

Accuracy: 99% (Overall correctness of predictions)
Precision (High-risk loans): 0.84 (How often high-risk loans were correctly predicted as high risk)
Recall (High-risk loans): 0.94 (Percentage of actual high-risk loans correctly identified)
Interpretation
Healthy loans (0): The model performed very well, correctly identifying almost all healthy loans.
High-risk loans (1): The model showed high recall, successfully identifying most high-risk loans, though with slightly lower precision, meaning a small number of healthy loans were flagged as high risk.
