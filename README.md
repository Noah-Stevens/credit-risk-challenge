# credit-risk-challenge
Module 20 Supervised Learning Challenge

# Credit Risk Analysis Report
## Overview of the Analysis
The purpose of this analysis is to build and evaluate a machine learning model capable of identifying credit risk based on other known borrower conditions, such as borrower income, number of accounts, total debt, etc. By training a logistic regression classifier on historical lending data, the model aims to predict whether a loan is high-risk (1) or healthy (0). The values of high-risk (1) or healthy (0) loans is from the loan_status column in the dataset. This tool can assist financial institutions in making informed lending decisions and minimizing the risk of loan defaults.

## Results
### Model Used: Logistic Regression

- Accuracy Score: 0.99

- Precision Score:
  1. Healthy Loans (0): 1.00
  2. High-Risk Loans (1): 0.84

- Recall Score:
  1. Healthy Loans (0): 0.99
  2. High-Risk Loans (1): 0.98

- F1-Score for High-Risk Loans: 0.91

## Summary
The logistic regression model demonstrated exceptional overall performance, with a 99% accuracy rate. It was especially effective at identifying high-risk loans, achieving a recall score of 0.98 — meaning it successfully detected 98% of all actual high-risk loans. While the precision for high-risk loans was slightly lower at 0.84 (indicating some false positives), this trade-off is acceptable in the context of credit risk, where it's often safer to be cautious and flag potentially risky loans. There is a possibility for overfitting on this module, due to the high rate of percision and accuracy, but the high volume of data points strengthens the integrity of the model.

Given the model's high performance, especially in minimizing false negatives, such as looking over a high-risk loan, its use as a reliable tool for preliminary credit risk assessment is recommended. It can help the company reduce financial risk by more accurately identifying borrowers who are likely to default.
