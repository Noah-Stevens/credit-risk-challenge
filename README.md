# Credit Risk Challenge — Loan Default Prediction — M20

This project involves training and evaluating a supervised learning model to assess borrower credit risk.

## Project Overview

### Objective  
Develop a logistic regression classifier to predict loan default risk (high‑risk = 1 vs healthy = 0), using borrower-related features such as income, number of accounts, debt, etc.

### Model Performance  
- **Accuracy**: 0.99  
- **Precision**  
  - Healthy loans (0): 1.00  
  - High‑risk loans (1): 0.84  
- **Recall**  
  - Healthy loans (0): 0.99  
  - High‑risk loans (1): 0.98  
- **F1‑Score (High‑risk loans)**: 0.91  

The model achieves exceptional overall performance. It demonstrates strong ability to detect high-risk loans (recall = 0.98), though precision is slightly lower (0.84), meaning some false positives—an acceptable trade-off when aiming to minimize false negatives in credit risk assessment.

## Repository Contents  
- Credit_Risk — Jupyter notebook performing data preprocessing, model training, evaluation, and reporting  
- README.md — This file  
- LICENSE — GPL‑3.0 License  

## Tools & Libraries  
- Python & Jupyter Notebook  
- scikit-learn — for model training, evaluation  
- Pandas, NumPy — for data manipulation  
- Matplotlib / seaborn — for visualizations (if applicable)  

## Quick Start  
1. Clone the repo:  
   ```bash
   git clone https://github.com/Noah-Stevens/credit-risk-challenge.git
   cd credit-risk-challenge
   ```  
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```  
3. Run analysis:  
   - Open `Credit_Risk.ipynb` in Jupyter and execute the notebook to reproduce results.

## Summary & Caveats  
The logistic regression model achieves strong performance metrics, particularly in minimizing false negatives. Given the extremely high accuracy and recall, there is potential for overfitting. However, the sizable dataset should mitigate that risk. This model is recommended for preliminary screening in credit risk workflows.

## License  
GPL‑3.0 License. See LICENSE file.

## Author  
Noah Stevens  
[LinkedIn](https://www.linkedin.com/in/noah-stevens-2a47a3331/)
