# Customer Churn Analysis Using Python

## Project Overview

This project analyzes customer churn in a telecommunications company using Python. The objective is to understand customer behavior, identify groups with higher churn rates, and derive insights that may help improve customer retention.

The analysis uses the IBM Telco Customer Churn dataset and includes data cleaning, exploratory data analysis (EDA), visualizations, and business recommendations.

## Objectives

- Understand the overall customer churn rate.
- Analyze churn by contract type and customer tenure.
- Investigate churn patterns by internet service and payment method.
- Compare churn rates by gender, senior-citizen status, and paperless billing.
- Examine the relationship between churn and monthly charges.
- Develop business recommendations based on the findings.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

**Dataset:** IBM Telco Customer Churn

**Source:** Kaggle  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains 7,043 customer records and 21 columns describing customer demographics, subscribed services, account information, charges, and churn status.

## Data Cleaning

- Checked for duplicate records.
- Inspected missing and inconsistent values.
- Converted `TotalCharges` to a numeric data type.
- Handled 11 blank `TotalCharges` values by replacing them with zero.

## Exploratory Data Analysis

The project explores customer churn across several dimensions:

- Overall churn distribution
- Contract type
- Customer tenure and tenure groups
- Monthly charges
- Payment method
- Internet service
- Senior-citizen status
- Gender
- Paperless billing

Visualizations were created using Matplotlib to compare customer groups and identify churn patterns.

## Key Findings

1. **Overall churn:** 1,869 of 7,043 customers churned, representing approximately 26.54%.
2. **Contract type:** Month-to-month customers had a churn rate of 42.71%, compared with 11.27% for one-year contracts and 2.83% for two-year contracts.
3. **Customer tenure:** Customers with 0–12 months of tenure had the highest churn rate at 47.44%. Customers with 49–72 months of tenure had a churn rate of 9.51%.
4. **Monthly charges:** Customers who churned had average monthly charges of approximately 74.44, compared with 61.27 for customers who stayed.
5. **Internet service:** Fiber-optic customers had a churn rate of 41.89%, while DSL customers had a rate of 18.96%.
6. **Payment method:** Customers using electronic checks had the highest churn rate at 45.29%.
7. **Senior citizens:** Senior customers had a churn rate of 41.68%, compared with 23.61% for non-senior customers.
8. **Paperless billing:** Customers using paperless billing had a churn rate of 33.57%, compared with 16.33% for customers not using it.
9. **Gender:** Churn rates were similar for female customers (26.92%) and male customers (26.16%).

## Business Recommendations

- Improve onboarding and customer support for customers during their first year.
- Investigate the reasons behind higher churn among month-to-month contract customers.
- Review customer satisfaction, service quality, and pricing for fiber-optic customers.
- Investigate the higher churn rate among electronic-check users.
- Explore targeted retention strategies for customer groups with higher churn rates.

## Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize customer data. The findings highlight customer segments associated with higher churn and provide practical starting points for customer-retention strategies.

## Project Files

- `Customer_Churn_Analysis.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- Dataset — Available from the Kaggle link above.

## Author

Pranali Pakere

Aspiring Data Analyst | Python | SQL | Excel | Power BI
