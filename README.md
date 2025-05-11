# PowerBI-Telecom-Industry-Analysis
Project Overview

This project analyzes the impact of 5G implementation on India’s telecom sector, focusing on key metrics like active users, revenue, market share, and customer behavior. The analysis compares performance before and after 5G rollout across cities, companies, and service plans. Key questions addressed:

How did 5G affect user subscriptions and revenue?

Which cities and telecom providers dominated the market post-5G?

What are the trends in plan-specific revenue and ARPU (Average Revenue Per User)?

Datasets
1. dim_cities.csv
city_code: Unique identifier for cities (e.g., DEL for Delhi).

city_name: Name of the city (e.g., Bangalore, Hyderabad).

2. dim_date.csv
date: Start date of the month (e.g., 2022-01-01).

month_name: Abbreviated month (Jan–Apr: Before 5G; Jun–Sep: After 5G).

before/after_5g: Categorizes months into pre- and post-5G periods.

time_period: Groups months for comparative analysis (e.g., Jan vs Jun).

3. dim_plan.csv
plan: Unique plan ID (e.g., P1, P11).

plan_description: Details of the internet plan (e.g., data limits, pricing).

4. fact_itv_metrics.csv
itv_revenue_crores: Revenue in crores (1 crore = ₹10 million) for ITV.

arpu: Average Revenue Per User.

active_users_lakhs: Active users in lakhs (1 lakh = 100,000).

unsubscribed_users_lakhs: Users who unsubscribed.

5. fact_market_share.csv
tmv_city_crores: Total market value of the city in crores.

company: Competitors (ITV, Airtel, DADAFONE, LIO, Others).

ms_pct: Market share percentage per company.

6. fact_plan_revenue.csv
plans: Internet plan IDs (e.g., P11).

plan_revenue_crores: Revenue generated per plan in crores.

Key Insights
User Behavior:

8.2% drop in active users post-5G (774K vs. 843K).

Unsubscriptions spiked in March and July 2022, indicating transition challenges.

Revenue Trends:

Delhi and Hyderabad saw the highest revenue growth post-5G.

Plan P11 generated the most revenue due to 5G bundling.

Market Dynamics:

Lio dominated with 40% market share, followed by DADAFONE (25%).

ARPU increased by 15% post-5G, peaking in June 2022.

Regional Disparities:

Metro cities (Delhi, Bangalore) led in 5G adoption; Tier-2 cities lagged.

Technologies Used
SQL: Data aggregation and transformation.

Power BI: Interactive dashboards for visualizing trends.

Excel: Data cleaning and preliminary analysis.


├── Data/  
│   ├── dim_cities.csv  
│   ├── dim_date.csv  
│   ├── dim_plan.csv  
│   ├── fact_itv_metrics.csv  
│   ├── fact_market_share.csv  
│   └── fact_plan_revenue.csv  
├── Dashboard.pbix    
├── Dashboard.pdf 

└── README.md  

🌟 Why This Project?

Demonstrates data storytelling skills using real-world telecom data.

Ideal for analysts exploring 5G’s business impact in emerging markets.
