# customer_behaviour_analysis

# Overview

This project simulates a real-world retail analytics workflow — cleaning and exploring data in Python, answering business questions with SQL, and visualizing findings in an interactive Power BI dashboard — to turn raw purchase data into insights and recommendations.

# Dataset

- **3,900 transactions** across 18 features
- Includes customer demographics (age, gender, location, subscription status), purchase details (item, category, amount, season), and shopping behavior (discounts, frequency, ratings, shipping)
- 37 missing values in `Review Rating`, cleaned and imputed using category-level median

# Tools

- **Python (pandas)** — data cleaning, EDA, feature engineering
- **PostgreSQL** — SQL analysis of business questions
- **Power BI** — interactive dashboard
- **Canva** — executive summary presentation


# Steps

1. Loaded and explored the dataset in Python
2. Cleaned data — imputed missing ratings, standardized columns, removed redundant fields
3. Engineered new features (`age_group`, `purchase_frequency_days`)
4. Loaded cleaned data into PostgreSQL
5. Answered 10 business questions using SQL (revenue drivers, discount behavior, top products, customer segments, repeat buyers)
6. Built a Power BI dashboard and summarized findings in a report and presentation


# Dashboard

Interactive Power BI dashboard with filters for subscription status, gender, category, and shipping type, showing KPIs (customers, average purchase, review rating) and revenue/sales breakdowns by category and age group.

# Results & Key Insights

- Male customers generate ~2.1x the revenue of female customers.
- Non-subscribers drive 73% of total revenue, spending nearly the same as subscribers ($59.87 vs. $59.49).
- 80% of customers are "Loyal," but most repeat buyers still aren't subscribed — a conversion opportunity.
- Discount dependency is concentrated in a few products (Hat, Sneakers, Coat), up to 50% discount rates.
- Express shipping customers spend ~3.4% more per order than Standard shipping customers

Recommendations: boost subscriptions, launch loyalty programs, review discount policy, spotlight top-rated products, and target high-revenue age groups and express-shipping users.
