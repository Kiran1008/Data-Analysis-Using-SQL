# Data-Analysis-Using-SQL
**Electronics Products Data Analysis using SQL**

**Project Overview
**
This project focuses on analyzing an electronics product dataset containing 6,000+ records using SQL. The goal is to clean, transform, and analyze product data to extract insights about pricing strategies, brand performance, discounts, ratings, and customer reviews.

Using advanced SQL techniques such as feature engineering, statistical analysis, and window functions, the project uncovers patterns and relationships between product attributes across multiple brands and categories.

**Business Problem
**
E-commerce platforms contain large volumes of product data including price, discounts, ratings, and reviews. However, raw data often contains inconsistencies and lacks structure for meaningful analysis.

This project aims to:

Clean and standardize product data

Engineer useful analytical features

Identify pricing patterns and outliers

Analyze relationships between price, ratings, and customer reviews

Compare performance across multiple brands and product categories

**Dataset Information
**
Total Records: 6,000+ electronics products

Attributes: Product name, price, discount, rating, review count, brand, category, etc.

Brands Covered: 20+ brands across multiple electronics categories

**Tools & Technologies
**
SQL

MySQL Workbench

**Key Analysis Performed
**1. Data Cleaning and Transformation

Processed and standardized 6,000+ product records

Cleaned inconsistencies in pricing, discount, and rating fields

Applied SQL functions such as:

REPLACE

CASE

CAST

TRIM

REGEXP

**2. Feature Engineering
**
Created 6 analytical features to enable deeper analysis, including:

MRP (Maximum Retail Price)

Discount Percentage

Discount Category

Average Rating

Review Count

Brand Extraction

These features enabled structured comparison across 20+ brands.

**3. Exploratory Data Analysis (EDA)
**
Performed exploratory analysis across 10+ attributes, including:

Summary statistics

Distribution of product prices

Rating distribution across brands

Review count trends

**4. Outlier Detection
**
Applied the IQR (Interquartile Range) method to detect pricing outliers

Identified unusually priced products that deviate from the overall distribution

5. Bivariate & Multivariate Analysis

Performed deeper statistical analysis using SQL queries:

Correlation analysis

Covariance analysis

Grouped statistics

Brand-level performance comparison

Category-wise pricing analysis

This analysis helped uncover relationships between:

Price vs Ratings

Price vs Reviews

Brand vs Discount strategies

Key Insights

Certain brands maintain premium pricing with higher ratings

Products with higher review counts tend to show more stable rating distributions

Some brands offer aggressive discount strategies compared to competitors

Outlier pricing patterns indicate potential mispriced or premium products

**SQL Concepts Used
**
SQL Joins

Aggregate Functions (AVG, SUM, COUNT)

Window Functions

GROUP BY and HAVING

CASE WHEN statements

Subqueries

Correlation and covariance calculations

IQR-based outlier detection

Exposure / Skills Demonstrated

SQL Data Cleaning

Feature Engineering

Exploratory Data Analysis

Statistical Analysis

Window Functions

Data Transformation

**Future Improvements
**
Build a Power BI or Tableau dashboard for product insights

Perform price prediction using machine learning

Implement customer sentiment analysis from product reviews

Automate analysis using Python + SQL pipelines
