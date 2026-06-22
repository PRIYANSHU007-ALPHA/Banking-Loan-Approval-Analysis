
# Banking Loan Approval Analysis using Python

## Project Overview

This project analyzes a banking loan dataset to identify the key factors influencing loan approval decisions. The analysis includes data cleaning, handling missing values, exploratory data analysis (EDA), visualization, and business insights generation using Python.

## Objective

The primary objective of this project is to understand the factors that affect loan approval and help financial institutions make data-driven lending decisions.

## Dataset Information

* Total Records: 614
* Features: 13
* Target Variable: Loan_Status (Approved / Rejected)

### Features Included

* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area
* Loan_Status

## Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

## Project Workflow

### 1. Data Cleaning

* Identified missing values
* Treated missing values using Mean, Median, and Mode
* Checked data types and data quality
![Uploading Banking Loan Approval Analysis using Python - visual selection.png…]()

### 2. Exploratory Data Analysis (EDA)

* Loan Approval Distribution
* Gender vs Loan Status
* Education vs Loan Status
* Self Employment vs Loan Status
* Property Area vs Loan Status
* Income Analysis
* Loan Amount Analysis
* Credit History Analysis
* Correlation Analysis

### 3. Data Visualization

* Count Plots
* Bar Charts
* Box Plots
* Heatmaps
* Crosstab Analysis

## Key Findings

### Credit History is the Strongest Factor

* Applicants with good credit history had a 79.05% approval rate.
* Applicants with poor credit history had only a 7.87% approval rate.

### Income and Loan Amount Relationship

* Correlation = 0.57
* Higher-income applicants tend to request larger loans.

### Gender Impact

* Minimal impact on loan approval decisions.

### Self Employment Impact

* Little difference observed between self-employed and non-self-employed applicants.

### Loan Amount Impact

* Loan amount alone is not a strong predictor of loan approval.

## Business Recommendations

1. Give higher priority to credit history during loan evaluation.
2. Introduce programs for applicants with poor credit history.
3. Use multiple factors together instead of relying only on income.

## Conclusion

The analysis revealed that Credit History is the most important factor influencing loan approval decisions. Income and Loan Amount show a moderate positive relationship, while demographic factors such as Gender and Self Employment have relatively little impact.

## Author

Priyanshu Ranjan
Aspiring Data Analyst
