## Customer Shopping Behavior Analysis

A comprehensive data analysis project exploring customer purchasing behavior, product preferences, and subscription trends using Python, SQL, and Power BI. This project uncovers actionable insights to support data-driven business decisions.

📌 Project Overview

This project analyzes 3,900 transactional records across multiple product categories. It examines spending patterns, customer segments, discount behavior, and revenue drivers. The end-to-end workflow includes data cleaning, exploratory data analysis (EDA), SQL-based business insights, and dashboard visualization.

📂 Dataset Summary

Total Rows: 3,900

Total Columns: 18

Key Attributes:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase attributes: Item Purchased, Category, Amount Spent, Season, Size, Color

Behavioral factors: Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type

Missing Values: 37 missing entries in review_rating

🧹 Data Preparation & EDA (Python)

Key steps performed in Python:

✔ Data Loading

Imported using pandas and performed structure checks using df.info() and df.describe().

✔ Data Cleaning

Imputed missing review ratings using category-wise median values.

Standardized column names into snake_case.

✔ Feature Engineering

Created customer age_group categories.

Computed purchase_frequency_days from timestamps.

✔ Data Consistency Checks

Removed redundant promo_code_used after validating overlap with discount_applied.

✔ Database Integration

Loaded the cleaned DataFrame into PostgreSQL for SQL analysis.

🧮 SQL-Based Business Analysis

A series of SQL queries were performed to answer key business questions, including:

Revenue by Gender – Comparison of total spending by male vs. female customers.

High-Spending Discount Users – Identified discount users exceeding the mean spending amount.

Top 5 Products by Rating – Ranked by average review scores.

Shipping Type Insights – Analyzed differences in spending across shipping methods.

Subscribers vs. Non-Subscribers – Compared total and average revenue.

Discount-Dependent Products – Items frequently purchased with discounts.

Customer Segmentation – Classified users as New, Returning, or Loyal.

Top 3 Products per Category – Identified category-wise bestsellers.

Repeat Buyers & Subscription – Correlation between high purchase frequency and subscription.

Revenue by Age Group – Breakdown of revenue contribution per age segment.

📊 Power BI Dashboard

A fully interactive Power BI dashboard visualizes:

Revenue trends

Customer segments

Product performance

Discount vs. non-discount behavior

Shipping insights

Subscription analysis

The dashboard enhances decision-making through intuitive visual analytics.

💡 Business Recommendations

Based on insights:

Increase Subscription Adoption through exclusive benefits.

Strengthen Loyalty Programs to convert repeat buyers into loyal customers.

Optimize Discount Strategy for improved margin control.

Highlight Top-Rated & Best-Selling Products in marketing.

Run Targeted Campaigns focused on high-revenue customer groups and express shipping users.

🛠 Tech Stack
Component	Tools Used
Data Analysis	Python, Pandas, NumPy
Database	MySQL
Visualization	Power BI
Other	SQL, Jupyter Notebook
