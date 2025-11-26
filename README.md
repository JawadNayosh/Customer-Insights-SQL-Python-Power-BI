# Customer-Insights-SQL-Python-Power-BI
Python • SQL • PostgreSQL • SQL Server • Power BI

<img width="676" height="382" alt="Image" src="https://github.com/user-attachments/assets/4a0ed2d6-9f7e-4ffd-9b41-0e8ed97892a0" />

This project analyzes 3,900 retail transactions to uncover patterns in customer behavior, product performance, subscription usage, and revenue drivers. It demonstrates an end-to-end data analytics workflow—from data cleaning in Python to SQL business analysis and interactive visualization in Power BI.

 # Project Overview

The goal of this project is to identify actionable insights that help businesses improve customer engagement, optimize product strategy, and increase revenue.
Key steps include:
Data cleaning and preparation
Feature engineering
Database integration
SQL business analysis
Interactive dashboard creation

# Dataset Summary
Rows: 3,900
Columns: 18

# Key Features:
Customer demographics (age, gender, location)
Shopping behavior (discounts, frequency, previous purchases)
Purchase details (category, amount, season, size, rating)
Subscription & shipping information

# Tools & Technologies
Python (pandas, numpy) — data cleaning, preprocessing
SQL Server — business analysis queries
Power BI — dashboard and data visualization
GitHub — project documentation

# Data Cleaning & Preparation (Python)
Performed using pandas:
Handled missing values (imputed review ratings by category median)
Renamed columns to snake_case

# Created new features:
age_group
purchase_frequency_days
Dropped redundant columns
Loaded cleaned data into SQL Server for further analysis

# Key SQL Analyses
Structured SQL queries were used to answer core business questions, including:
Revenue differences between male vs. female customers
High-spending customers using discounts
Top 5 products based on review ratings
Standard vs. Express shipping comparison
Subscriber vs. non-subscriber spending behavior
Products most dependent on discounts
Customer segmentation (New, Returning, Loyal)
Top 3 items per category
Correlation between repeat buyers and subscription
Revenue contributions by age group

# Power BI Dashboard
A complete interactive dashboard visualizes:
Customer segmentation
Revenue by category
Average purchase amount
Age-based revenue insights
Shipping behavior
Subscription impact
Product category performance

# Business Insights
Based on the analysis, the following insights were identified:
Subscribers spend more and purchase more frequently
Clothing and Accessories generate the highest revenue
Young Adults contribute the most revenue
Discount usage significantly influences buying decisions
Express shipping customers tend to spend more

# Business Recommendations
Increase subscription sign-ups using exclusive perks
Build loyalty programs for repeat buyers
Promote top-rated and best-selling products
Offer targeted marketing to high-value age segments
Review discount strategy to balance revenue and margins
Encourage more non-subscribers to join the subscription program since subscribers clearly spend more and purchase more frequently.
Promote economy shipping with small incentives, as many customers prefer it and it can reduce operational costs.
Create targeted marketing for Young Adults, the age group generating the highest revenue.
Expand the top-performing product categories (Clothing and Accessories) by offering more variety or premium options.

# Author
Mohammad Jawad Nayosh
jnayosh@gmail.com

