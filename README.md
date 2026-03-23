# Customer Retention Analysis and Churn Prediction

This project analyzes customer behavior to predict churn and identify key drivers that influence customer retention. Using a combination of data cleaning, exploratory data analysis (EDA), and machine learning models, the goal is to generate actionable insights that can inform retention strategies and improve customer lifetime value.

## Business Objective:
- Predict which customers are likely to churn
- Understand the factors driving churn behavior
- Enable targeted retention strategies to reduce revenue loss

## Data Cleaning & Preparation
- Data Cleaning & Preparation
- Standardized column formats for consistency
- Created derived features such as:
  - Engagement-related indicators
  - Churn flag (binary target variable)

## Exploratory Data Analysis
- At the basic and premium subscription levels, we can see that the average spending for consumers is lower than the standard subscription.
- Monthly contract lengths have the lowest average price, with annual and quarterly being higher and close to equal.
- Before day 20, customers who are not churned tend to have higher payment delay days compared to churned customers. Afterwards, churned customers have payment delays just over 10 times than that of not churned customers.
- Customers who are not churned choose premium or standard subscriptions.

#Churn Prediction
- Utilized logistic regression, decision tree, random forest, and k-nearest neighbors models to predict churn based on gender, subscription type, and contract length.
