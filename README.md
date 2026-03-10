# Customer-churn-analysis
Customer churn analysis and prediction using telecom subscription data.
Customer Churn Analysis & Prediction
Overview

Customer churn is a major challenge for subscription-based businesses such as telecom companies. This project analyses customer behaviour to identify the key drivers of churn and build a predictive model to help businesses proactively retain customers.

The dataset contains 7,000+ telecom customers with information about services, contracts, billing behaviour, and churn status.

Key Findings: 

Contract Type

Customers on month-to-month contracts show the highest churn rate (43%), compared to 11% for one-year contracts and only 3% for two-year contracts.

Customer Tenure

Nearly 48% of customers churn in their first year, while churn drops significantly after two years.

Tech Support

Customers without technical support show significantly higher churn rates.

Pricing Sensitivity

Customers with higher monthly charges are more likely to churn.

High-Risk Customer Segment

A particularly vulnerable segment was identified:

Month-to-month contract

Tenure less than 12 months

No tech support

This segment has:

62% churn rate

Represents 18.7% of customers

Generates approximately £88,000 in monthly revenue

Equivalent to £1M+ annual revenue exposure

Predictive Modeling

A logistic regression model was built to predict customer churn.

Model performance:

Accuracy: 81%

Precision (Churn): 70%

Recall (Churn): 58%

ROC-AUC: 0.86

The model demonstrates a strong ability to distinguish between customers who churn and retained customers.

Business Recommendations

Based on the analysis, telecom companies can reduce churn by:

Encouraging longer-term contracts

Providing onboarding support for new customers

Bundling tech support with internet services

Targeting high-risk customers with attractive retention offers

Tools Used

Python

Pandas

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook
