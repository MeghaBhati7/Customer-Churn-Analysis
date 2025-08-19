## Bank Customer Churn Analysis
This project explores bank customer churn using Python (Google Colab). The goal is to identify the factors driving customer attrition, uncover patterns in customer behavior, and suggest strategies that can improve retention.  

 ### 📌 Project Overview
#### Customer churn is one of the biggest challenges in the banking industry. By analyzing demographic and behavioral data, we can highlight the differences between customers who stay and those who leave — and generate actionable insights for retention strategies.

 ####  This project was originally completed using SQL queries and later extended into Python (Pandas, Matplotlib, Seaborn) in Google Colab for richer analysis and visualization.

 ### 🎯 Objectives
* Identify key drivers of churn (age, balance, tenure, activity, products held, etc.).

* Compare profiles of churned vs. retained customers.

* Explore correlations between customer demographics, account behaviors, and churn.

* Provide business recommendations to reduce churn and increase engagement.

 ### 📊  Dataset
Source: [Maven Analytics Challenge Dataset]

Size: ~10,000 customers

### Key Features:

CreditScore

Geography (France, Germany, Spain)

Gender

Age

Tenure

Balance

NumOfProducts

HasCrCard

IsActiveMember

EstimatedSalary

Exited (Target → 1 = churned, 0 = retained)

 ### 🔍 Key Insights
* Age: Older customers are more likely to churn (positive correlation of +0.29).

* Balance: High-balance customers churn more often, possibly due to unmet expectations.

* Active Membership: Inactive members churn at a much higher rate, highlighting the importance of engagement.

* Products: Customers with only 1 product churn more often compared to those holding multiple products.

 ### 🛠 Tools & Technologies

Python (Google Colab):

* pandas – data manipulation

* matplotlib / seaborn – data visualization

* numpy – numerical analysis

 ### 📈 Visualizations
The Python extension of this project includes charts such as:

* Churn rate by age group

* Balance distribution for churned vs retained customers

* Impact of active membership on churn

* Product usage vs churn

 ### 💡Business Recommendations
* Engage Older Customers: Offer retirement-focused financial products and proactive advisory services.

* Retain High-Balance Customers: Provide loyalty rewards, premium services, and personalized account management.

* Re-engage Inactive Members: Use targeted campaigns and incentives to encourage account activity.

* Promote Product Bundling: Encourage customers to adopt multiple products to increase stickiness.
