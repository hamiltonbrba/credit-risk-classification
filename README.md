Here's the updated README file with a section for the Credit Risk Report file:

---

# Credit Risk Analysis with Logistic Regression

## Overview

This project applies a logistic regression model to predict the credit risk of loans, aiming to assist lenders in identifying loans that may be high risk versus healthy. Using historical loan data, this analysis provides insights into factors that contribute to loan risk, allowing for data-driven decision-making.

## Data

The dataset includes financial information about each loan, such as:
- Loan amount
- Interest rate
- Borrower’s income level
- Loan status (`0` = healthy, `1` = high risk)

## Objectives

1. **Data Preparation**: Split the data into features (`X`) and target labels (`y`), then separate it into training and testing datasets.
2. **Model Training**: Create a logistic regression model using the training data.
3. **Evaluation**: Evaluate the model's performance using accuracy, precision, and recall to understand its ability to identify high-risk loans.

## Results

The logistic regression model produced the following key metrics:

- **Accuracy**: 99% (Overall correctness of predictions)
- **Precision** (High-risk loans): 0.84 (How often high-risk loans were correctly predicted as high risk)
- **Recall** (High-risk loans): 0.94 (Percentage of actual high-risk loans correctly identified)

### Interpretation

- **Healthy loans (0)**: The model performed very well, correctly identifying almost all healthy loans.
- **High-risk loans (1)**: The model showed high recall, successfully identifying most high-risk loans, though with slightly lower precision, meaning a small number of healthy loans were flagged as high risk.

## Summary

With a high accuracy of 99% and strong recall for high-risk loans, this logistic regression model is highly effective for predicting credit risk. The model’s reliability in identifying high-risk loans helps lenders make safer, more informed lending decisions. Based on these results, this model is recommended for credit risk assessment.

---

## Getting Started

### Prerequisites

This project uses Python and the following libraries:
- `pandas` for data manipulation
- `sklearn` for machine learning and evaluation metrics

### Installation

1. Clone this repository.
   ```bash
   git clone https://github.com/hamiltonbrba/credit-risk-classification.git
   ```
2. Install the necessary packages.
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the Jupyter Notebook located in the `Credit_Risk/` folder to view the code and model output.
2. The model’s performance metrics, including the confusion matrix and classification report, will display in the notebook output.

---

## Code and Report Files

- **Notebook**: All code used in this project, including data preparation, model training, and evaluation, can be found in the Jupyter Notebook file located in the `Credit_Risk/` directory:
  - **File Location**: `Credit_Risk/credit_risk_classification.ipynb`
  
- **Credit Risk Report**: The detailed Credit Risk Analysis Report can be found as a separate file in the repository. This report includes the overview, results, and model recommendation, formatted for easy readability:
  - **File Location**: `credit_risk_report.md`

This README, notebook, and report file contain all necessary information to understand, reproduce, and interpret the results of this credit risk analysis project.

--- 

This setup gives clear guidance on where to find each component of the project, including the new `credit_risk_report.md`.
