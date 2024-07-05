# Customer Churn Prediction for Bank Savings Accounts

## Project Overview

This project aims to develop a machine learning model to predict customer churn for a bank's savings accounts. The goal is to identify customers who are likely to fall below the minimum balance requirement, enabling the bank to take proactive measures to retain these customers.

## Data Dictionary

The dataset consists of multiple variables categorized into three main sections:

### I. Demographic Information
- **customer_id**: Customer ID
- **vintage**: Number of days the customer has been with the bank
- **age**: Age of the customer
- **gender**: Gender of the customer
- **dependents**: Number of dependents
- **occupation**: Occupation of the customer
- **city**: City of the customer (anonymized)

### II. Customer Bank Relationship
- **customer_nw_category**: Net worth category of the customer (3: Low, 2: Medium, 1: High)
- **branch_code**: Branch code for the customer account
- **days_since_last_transaction**: Number of days since the last credit in the last year

### III. Transactional Information
- **current_balance**: Balance as of today
- **previous_month_end_balance**: End of month balance of the previous month
- **average_monthly_balance_prevQ**: Average monthly balance in the previous quarter
- **average_monthly_balance_prevQ2**: Average monthly balance in the quarter before the previous quarter
- **current_month_credit**: Total credit amount for the current month
- **previous_month_credit**: Total credit amount for the previous month
- **current_month_debit**: Total debit amount for the current month
- **previous_month_debit**: Total debit amount for the previous month
- **current_month_balance**: Average balance for the current month
- **previous_month_balance**: Average balance for the previous month
- **churn**: Indicator of whether the customer's average balance falls below the minimum balance in the next quarter (1: Yes, 0: No)

## Project Problem Statement

The objective of this project is to predict the likelihood of customers' average balance falling below the minimum balance in the next quarter. This will help the bank implement effective customer retention strategies.

## Project Workflow

1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding data distributions and relationships.
3. **Feature Engineering**: Creating new features to improve model performance.
4. **Model Training**: Building and training machine learning models.
5. **Model Evaluation**: Assessing model performance using appropriate metrics.
6. **Implementation**: Deploying the model to provide actionable insights.

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

## Conclusion

This project delivers a robust machine learning model to predict customer churn for savings accounts. By identifying high-risk customers, the bank can take targeted actions to enhance customer retention and maintain account balances above the minimum requirement.

## Contact Information

For any queries or further information, please contact:

**Name**: Shivendra Singh Thakur  
**Email**: Shivendra323@gmail.com  
**LinkedIn**: www.linkedin.com/in/shivendra-singh-thakur-09a36a1b0
