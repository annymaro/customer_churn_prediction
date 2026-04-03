# Customer Churn Prediction

## Overview
This project builds a machine learning model to predict customer churn using operational and behavioral data. The goal is to help businesses proactively 
identify at-risk customers and take action to improve retention and reduce revenue loss.

## Objective
The goal of this project is to identify the main factors that increase churn risk and build a model that can help a business proactively flag at-risk customers.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset Features
The dataset includes the following fields:
- customer_id
- vendor_id
- region
- order_volume
- avg_delivery_time
- on_time_rate
- defect_rate
- support_tickets
- monthly_revenue
- customer_tenure_months
- churn_risk

## Project Steps
1. Generated a realistic business dataset
2. Cleaned and explored the data
3. Performed exploratory data analysis
4. Built a Logistic Regression model
5. Evaluated model performance using accuracy, confusion matrix, and ROC-AUC
6. Identified the top drivers of churn risk

## Results
- Accuracy: 91%
- ROC-AUC Score: 0.85

## Top Drivers of Churn
The strongest predictors of churn were:
1. defect_rate
2. support_tickets
3. avg_delivery_time

## Key Insights
- Customers with higher defect rates are significantly more likely to churn
- Increased support tickets strongly correlate with churn risk
- Longer delivery times contribute to customer dissatisfaction and churn
- Reducing false negatives is critical to prevent revenue loss

## Business Insight
The model suggests that customers experiencing more defects, more support issues, and slower delivery times are more likely to churn. 
This can help a business prioritize quality improvement, customer support, and service performance to improve retention.

## Files Included
- Customer_Churn_Prediction.ipynb
- customer_vendor_data.csv
- README.md
