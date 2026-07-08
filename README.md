# Customer Churn Analysis & Prediction

## Project Overview
This project analyzes telecom customer data to understand churn patterns and predict which customers are likely to leave. The goal is to help a business identify at-risk customers early and support retention efforts.

## Business Problem
Acquiring a new customer is more expensive than retaining an existing one. The company wants to know which customers are most likely to churn so it can take action before losing them.

## Dataset
- Dataset: IBM Telco Customer Churn
- Rows: 7,043 customers
- Target column: Churn

## Tools Used
- Python
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook
- GitHub

## Data Preparation
- Converted `TotalCharges` to numeric
- Removed rows with missing `TotalCharges`
- Converted `Churn` from Yes/No to 1/0
- Encoded categorical variables using one-hot encoding

## Exploratory Analysis
I analyzed churn by:
- Contract type
- Tenure
- Internet service
- Payment method

## Machine Learning
I tested:
- Logistic Regression
- Decision Tree

## Model Results
Logistic Regression performed better than Decision Tree and was selected as the final model because it had stronger performance on churn detection.

## Key Insights
- Customers with shorter tenure are more likely to churn.
- Month-to-month customers have higher churn risk.
- Certain payment methods and internet service types are associated with higher churn.

## Business Recommendations
- Focus retention efforts on new customers.
- Encourage month-to-month customers to move to longer contracts.
- Target at-risk customers with special offers and support.

## File Structure
```text
customer-churn-analysis/
├── notebooks/
├── data/
├── models/
├── assets/
├── README.md
└── requirements.txt
