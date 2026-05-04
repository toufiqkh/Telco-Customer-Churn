Telco Customer Churn: Predictive Analysis & Retention Insights

A data science project focused on identifying high-risk customers and uncovering the key drivers of attrition for a telecommunications provider.

2. Project Overview
Provide a high-level summary of the problem and  solution.

The Challenge: High customer turnover is costly. The goal is to analyze customer behavior to predict who is likely to leave.  

The Solution: Developed an end-to-end pipeline including data cleaning, exploratory data analysis (EDA), and feature engineering to prepare data for machine learning.  

Dataset: Based on the IBM Telco Churn dataset containing 7,043 rows and 21 features.  

3. Tech Stack
List the tools you used to demonstrate your technical proficiency:

Language: Python
Libraries: Pandas (Data Manipulation), Matplotlib/Seaborn (Visualization), Scikit-Learn (Preprocessing & Scaling).  
Environment: Jupyter Notebook

4. Detailed Data Workflow
This is where you explain your "Data Manager" approach to the problem:

A. Data Cleaning & Transformation
Handling Nulls: Identified and handled 11 missing values in TotalCharges by converting them from objects to numeric and applying median imputation.  

Feature Selection: Removed customerID as it provides no predictive value.  

Normalization: Applied StandardScaler to ensure features like MonthlyCharges and tenure are on a consistent scale for modeling.  

B. Exploratory Data Analysis (EDA)
Describe the patterns you found:

Contract Influence: Found that Month-to-Month contracts are the leading indicator of churn.  

Tenure: Customers in their first 6 months have the highest probability of leaving.  

Service Usage: Analyzed how features like fiber optic internet and tech support impact loyalty.  

5. Key Insights & Recommendations
Summarize the "Business Analytics" value of your work:

Targeted Retention: Customers on month-to-month plans should be incentivized to move to 1-year or 2-year contracts.

Price Sensitivity: High monthly charges correlate with higher churn; consider loyalty discounts for long-tenure customers.



