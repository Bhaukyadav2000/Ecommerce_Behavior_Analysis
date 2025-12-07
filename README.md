📊 Customer Shopping Behavior Analysis – Project Description (GitHub Ready)
📝 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights about spending patterns, customer demographics, product preferences, and subscription trends to support data-driven business decisions.

📂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription status

Purchase details: Item purchased, Category, Purchase amount, Season, Size, Color

Behavioral data: Discount applied, Previous purchases, Frequency, Review rating

Logistics: Shipping type

Missing Values: 37 missing entries in Review Rating column

🐍 Exploratory Data Analysis (Python)

Performed extensive EDA and data preprocessing:

✔ Data Loading & Exploration

Imported dataset using pandas

Used .info() and .describe() to inspect structure and summary stats

✔ Data Cleaning

Identified missing values

Imputed review ratings per product category using the median

Converted column names to snake_case for consistency

✔ Feature Engineering

Created age_group by binning customer ages

Created purchase_frequency_days

Validated and removed redundant fields (e.g., dropped promo_code_used)

✔ Database Integration

Connected Python with PostgreSQL

Loaded the cleaned dataset into the database for advanced SQL analytics

🗂 SQL Analysis (PostgreSQL)

SQL queries were used to extract meaningful business insights:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Average Review Rating

Shipping Type Revenue Comparison

Subscribers vs Non-Subscribers Spend Analysis

Products Most Dependent on Discounts

Customer Segmentation: New, Returning, Loyal

Top 3 Products in Each Category

Subscription Likelihood for Repeat Buyers

Revenue Contribution by Age Group

📈 Power BI Dashboard

A fully interactive Power BI dashboard was built to visualize:

Revenue insights

Customer segments

Product performance

Subscription patterns

Seasonal and demographic trends

📌 Business Recommendations

Based on the analysis:

Boost Subscriptions with better member-exclusive benefits

Strengthen Loyalty Programs to retain repeat buyers

Reassess Discount Strategy to protect margins

Promote Best-Rated Products for higher conversions

Use Targeted Marketing for high-value age groups & express-shipping users
