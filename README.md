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

 Business Recommendations

Based on the patterns found in the Telco-Customer-Churn.csv data, here are four data-driven strategies to reduce churn and a final summary of your project deliverables.
________________________________________
1. Incentivize Long-Term Contracts
The Data: Month-to-month customers churn at a rate of 42.7%, while two-year contract customers churn at only 2.8%.
•	Strategy: Offer small monthly discounts or "loyalty bonuses" to customers who switch from month-to-month to 1 or 2-year plans.
•	Target: Focus on high-value month-to-month customers who have a tenure of 6–12 months.
2. Bundle Tech Support & Security Services
The Data: Customers who do not have Tech Support churn at 41.6%, compared to only 15.2% for those who do.
•	Strategy: Create "Peace of Mind" bundles that include Online Security and Tech Support for a low add-on fee.
•	Target: New customers and those currently using only "Fiber Optic" internet without additional protection.
3. Review the Fiber Optic Pricing Model
The Data: Monthly charges are higher for churned customers (avg. $74.44) than for those who stay (avg. $61.27). High-speed Fiber Optic users show high churn sensitivity.
•	Strategy: Implement a "Seniors & Students" discount or a low-tier Fiber Optic plan to prevent price-sensitive customers from leaving for competitors.
4. Optimize the Digital Billing Experience
The Data: Customers with Paperless Billing churn at 33.6%, more than double the rate of those with paper bills (16.3%).
•	Strategy: Investigate if digital bill layouts are confusing or if auto-pay failures are causing accidental churn. Encourage "Automatic Bank Transfer" over "Electronic Check" to improve payment success rates.


Summary of Suggested Workflow Change:
1.	Cleaning: Handle TotalCharges and drop customerID.
2.	EDA: Visualize relationships (Contract, Tenure, Monthly Charges).
3.	Split: Use train_test_split.
4.	Pre-processing: Scale and Encode within the split.
5.	Modeling: Train and evaluate.



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



