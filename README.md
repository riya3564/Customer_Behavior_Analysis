🛍️ Customer Shopping Behavior Analysis


📌 Executive Summary

In a competitive retail environment, understanding customer behavior is essential for improving revenue and long-term customer loyalty.

This project presents an end-to-end data analytics solution that transforms raw transactional data into actionable insights. By analyzing 3,900 customer transactions, it identifies key patterns in purchasing behavior, customer segmentation, and revenue drivers.

The findings support businesses in optimizing marketing strategies, customer engagement, and product positioning.




❓ Business Problem

The company observed changing customer behavior across demographics, product categories, and sales channels but lacked clarity on key drivers of purchase decisions.


🎯 Core Question

How can customer data be leveraged to identify trends, improve engagement, and optimize business strategies?



🎯 Objectives
Identify high-value customer segments
Analyze purchase drivers (discounts, reviews, seasonality)
Evaluate the impact of subscriptions on revenue
Discover top-performing products and categories



📊 Dataset Overview
Records: 3,900
Features: 18
Missing Values: 37 (Review Rating)

Data includes:

Customer demographics (Age, Gender, Location, Subscription)
Purchase details (Product, Category, Amount, Season)
Behavioral attributes (Discounts, Frequency, Reviews, Shipping Type)




🧹 Data Engineering (Python)
Cleaned and validated dataset
Imputed missing values using category-wise median
Standardized column names
Created features: age_group, purchase_frequency_days
Removed redundant fields and loaded data into PostgreSQL




🗄️ Data Analysis (SQL)

Performed structured analysis to extract business insights:

Revenue analysis by gender
Customer segmentation (New, Returning, Loyal)
Subscription vs non-subscription behavior
Discount impact on purchasing
Top products and category performance
Revenue contribution by age group




📈 Dashboard (Power BI)

Developed an interactive dashboard to visualize:

Key KPIs (Revenue, Orders, Average Spend)
Customer segments and behavior
Product performance and trends
Impact of discounts and subscriptions




🔍 Key Insights
Loyal customers contribute the highest revenue
Subscribers exhibit higher spending behavior
Discounts increase sales but may reduce margins
Some products are highly dependent on discounts
Certain customer segments and age groups drive significant revenue





🚀 Strategic Recommendations
Enhance subscription benefits to improve retention
Implement loyalty programs for repeat customers
Optimize discount strategies to balance revenue and margins
Promote high-performing and top-rated products
Apply targeted marketing based on customer segments



🛠️ Tech Stack
Python (Data Cleaning & Feature Engineering)
PostgreSQL (Data Analysis)
Power BI (Visualization)
GitHub (Version Control)



📁 Project Structure
customer-shopping-analysis/
 ┣ data/
 ┣ notebooks/
 ┣ sql/
 ┣ dashboard/
 ┣ scripts/
 ┗ README.md




🎯 Business Impact

This project demonstrates how data analytics can enable:

Improved customer retention
Better decision-making
Revenue optimization
Stronger business strategies



👩‍💻 Author

Riya Pandey
🎓 BCA Student | 📊 Aspiring Data Analyst
