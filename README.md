# Retail Sales Data Analysis Dashboard (HTML + EDA Project)
## Project Overview

This project is an end-to-end retail sales analysis built using a dataset of 1,200+ transactions.
It combines data cleaning, exploratory data analysis (EDA), and an interactive HTML dashboard to uncover insights into customer behavior, product performance, and sales trends.

The goal is to transform raw data into actionable business insights using a web-based dashboard.

## Business Objectives
- Analyze sales performance over time
- Identify top-performing products and categories
- Understand customer purchasing behavior
- Evaluate revenue distribution across cities
- Segment customers based on income and loyalty

## Dataset Overview

The dataset includes retail transactions with the following features:
- Order details (Order ID, Date)
- Customer information (Gender, Age, City)
- Product data (Category, Product Name, Quantity, Price)
- Financial metrics (Total Sales)
- Behavioral attributes (Payment Method, Income Level, Loyalty Score)
- <a href="https://github.com/Makamarudeen4/Data-Analysis-Dashboard-EDA/blob/main/Retail%20EDA.xlsx">Dataset<a/>

## Data Cleaning & Preparation
### Missing Values Handling
- Age → filled with median
- City → filled with mode 
- Product Name → inferred
- Payment Method → filled with mode
### Outlier Treatment
- Identified using IQR method
- Extreme Unit Price and Sales values were capped
