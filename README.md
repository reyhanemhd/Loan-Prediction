# Loan-Prediction
# Logistic Regression Model for Loan Approval Prediction

## Project Overview

This project aims to predict loan approval outcomes based on various factors such as credit history, income, marital status, education, and more. Using a logistic regression model, we analyze how these factors influence the likelihood of loan approval.

## Dataset

The dataset includes the following features:
- `Gender`: Male/Female
- `Married`: Yes/No
- `Dependents`: Number of dependents
- `Education`: Graduate/Not Graduate
- `Self_Employed`: Yes/No
- `Applicant_Income`: Income of the applicant
- `Coapplicant_Income`: Income of the co-applicant
- `Loan_Amount`: Loan amount in thousands
- `Term`: Term of the loan in months
- `Credit_History`: Credit history meets guidelines (1: Yes, 0: No)
- `Area`: Urban/Semiurban/Rural
- `Status`: Loan approved (Y/N)

## Model

The logistic regression model was chosen for its interpretability and effectiveness in binary classification tasks. The model predicts the probability of loan approval (`Status`) based on the features mentioned above.

### Feature Importance

The model revealed that `Credit_History` is the most significant predictor of loan approval, followed by variables like `Married`, `Education`, and `Dependents`.

## Requirements

- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

To set up the project environment, run the following commands:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
