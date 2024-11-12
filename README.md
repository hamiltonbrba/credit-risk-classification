# Credit Risk Analysis with Logistic Regression

## Overview

This project uses a logistic regression model to predict loan credit risk, helping lenders identify which loans might be high risk and which are likely safe. By analyzing historical loan data, this project sheds light on factors that influence credit risk, offering a data-driven approach to decision-making.

## Data

The dataset includes various financial details about each loan, such as:
- Loan amount
- Interest rate
- Borrower’s income level
- Loan status (`0` = healthy, `1` = high risk)

## Objectives

1. **Data Preparation**: Separate the data into features (`X`) and target labels (`y`), then split it into training and testing sets.
2. **Model Training**: Train a logistic regression model using the training data.
3. **Evaluation**: Evaluate how well the model performs in identifying high-risk loans using accuracy, precision, and recall metrics.

## Results

The logistic regression model produced the following results:

- **Accuracy**: 99% — the overall correctness of the model.
- **Precision** (for high-risk loans): 0.84 — showing how often high-risk loans were correctly identified.
- **Recall** (for high-risk loans): 0.94 — showing how well the model captured actual high-risk loans.

### Interpretation

- **Healthy loans (0)**: The model performs very well in recognizing healthy loans, correctly identifying almost all of them.
- **High-risk loans (1)**: The model also performs well in identifying high-risk loans, with a strong recall of 94%. The slightly lower precision means that some healthy loans might be flagged as high risk, though this is minimal.

## Summary

With an accuracy of 99% and strong recall for high-risk loans, this logistic regression model is highly effective for predicting credit risk. Its reliable identification of high-risk loans can help lenders make safer, more informed lending decisions, making it a solid choice for credit risk assessment.

---

## Getting Started

### Prerequisites

This project requires Python and the following libraries:
- `pandas` for data handling
- `sklearn` for machine learning and evaluation metrics

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/hamiltonbrba/credit-risk-classification.git
   ```


### Usage

1. Open and run the Jupyter Notebook in the `Credit_Risk/` folder to see the code and results.
2. The notebook will display performance metrics like the confusion matrix and classification report.

---

## Code and Report Files

- **Notebook**: All code for data preparation, model training, and evaluation can be found in `Credit_Risk/credit_risk_classification.ipynb`.
  
- **Credit Risk Report**: The detailed Credit Risk Analysis Report is available as `credit_risk_report.md`. It includes an overview, results, and model recommendation for easy reference.

