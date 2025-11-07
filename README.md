# Customer-Shopping-Behavior-Analysis
Data Analyst project showcasing customer shopping behavior using python, sql and power-bi.

📌 Overview
This project analyzes customer shopping behavior using transactional data. It covers the full data analytics workflow—from loading and cleaning data in Python, running SQL queries in PostgreSQL, to building a Power BI dashboard. The goal is to uncover insights into customer segments, product preferences, and revenue drivers to support business decisions.

📂 Dataset
- Source: Simulated transactional dataset
- Records: 3,900 rows
- Features:
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Item, Category, Amount, Season, Size, Color)
- Behavioral metrics (Discounts, Promo Codes, Frequency, Review Ratings, Shipping Type)

🔍 Steps Performed
1. Data Preparation (Python)
- Loaded dataset using pandas
- Explored structure with .info() and .describe()
- Imputed missing review ratings using category-wise median
- Standardized column names to snake_case
- Engineered new features:
- age_group from age bins
- purchase_frequency_days from transaction history
- Dropped redundant columns (e.g., promo_code_used)
- Loaded cleaned data into PostgreSQL
2. SQL Analysis (PostgreSQL)
- Revenue breakdown by gender and age group
- High-spending customers using discounts
- Top-rated products by average review
- Shipping type comparison
- Subscriber vs. non-subscriber revenue
- Discount-dependent products
- Customer segmentation: New, Returning, Loyal
- Product popularity by category
- Subscription trends among repeat buyers
3. Dashboard (Power BI)
- Visualized key metrics:
- Total customers, average spend, review ratings
- Revenue by category, age group, subscription status
- Product performance and shipping preferences

📈 Results & Insights
- Male customers generated 2x more revenue than female customers
- Subscribers spent slightly less on average but contributed significantly to total revenue
- Express shipping correlated with higher purchase amounts
- Hats and sneakers had the highest discount usage
- Loyal customers formed the majority segment
- Young adults contributed the highest revenue

▶️ How to Run
1. 	Clone the repository
https://github.com/jerrold4/Customer-Shopping-Behavior-Analysis.git


