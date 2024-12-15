# Loan Default Dataset

## Introduction
The **Loan Default Dataset** provides information on loan applications and their outcomes, particularly focusing on whether a loan was defaulted. This dataset is ideal for building and evaluating machine learning models to predict loan defaults, analyze credit risks, and explore factors contributing to defaults.

The data is publicly available on Kaggle, and the original dataset can be found here: [Loan Default Dataset on Kaggle](https://www.kaggle.com/datasets/nikhil1e9/loan-default).

## Dataset Overview
The dataset contains information about loan applicants, their demographic details, financial status, loan characteristics, and repayment outcomes. It includes both categorical and numerical features suitable for classification and regression analyses.

### Key Features:
- **Loan Application Details**: Loan amount, purpose, term, and interest rate.
- **Applicant Characteristics**: Age, income, employment type, credit score, and education level.
- **Financial Indicators**: Debt-to-Income ratio (DTI), number of credit lines, and mortgage details.
- **Target Variable**: `Default` - Indicates whether the applicant defaulted on their loan.

### Applications:
1. Predicting loan defaults to assist financial institutions in assessing credit risk.
2. Analyzing feature importance to understand which factors contribute most to loan defaults.
3. Demonstrating preprocessing techniques such as encoding, scaling, and feature engineering for machine learning workflows.

## Preprocessing
For our analysis, the dataset has undergone the following preprocessing steps:

1. **Data Splitting**:
   - The dataset is split into `test` and `other` sets to ensure robust evaluation.

2. **Encoding**:
   - **Ordinal Encoding**: The `Education` feature is encoded using the categories:
     - High School, Bachelor's, Master's, PhD.
   - **One-Hot Encoding**: Categorical features such as `EmploymentType`, `MaritalStatus`, and others are encoded with one-hot encoding.

3. **Scaling**:
   - Numerical features such as `Income`, `LoanAmount`, `CreditScore`, and others are standardized using a Standard Scaler.

4. **Feature Engineering**:
   - Additional transformations may include interaction terms, binning, or derived features to enhance model performance.

## Usage
The dataset can be used to:
- Train machine learning models for classification tasks.
- Analyze correlations between applicant characteristics and loan defaults.
- Experiment with various preprocessing and feature engineering techniques.

## License
Please refer to the Kaggle dataset page for licensing details. Ensure appropriate attribution if used in projects or publications.

## Contributions
Feel free to fork this repository, raise issues, or submit pull requests if you would like to contribute to improving the dataset or its documentation.

---
For more information, visit the [dataset source](https://www.kaggle.com/datasets/nikhil1e9/loan-default).

