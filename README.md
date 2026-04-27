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

## Exploratory Data Analysis (EDA)
### Sales Trends
- Revenue trends over time
- Peak sales periods identified
### Product Performance
- Top categories by revenue
- Most purchased products
### Customer Insights
- Age group spending behavior
- Gender-based analysis
- City-wise revenue contribution
### Payment Behavior
- Distribution of payment methods
- Transaction value comparison
### Customer Segmentation
- High-value customers identified
- Loyalty score analysis

## Key Performance Indicators (KPIs)
- Total Revenue
- Total Orders
- Average Order Value (AOV)
- Total Quantity Sold
- Unique Customers

## Interactive HTML Dashboard
The project includes a fully interactive HTML dashboard with embedded visualizations.
- <a href="https://github.com/Makamarudeen4/Data-Analysis-Dashboard-EDA/blob/main/Dashboard%201.jpeg">DashBoard<a/>


### Dashboard Features
#### KPI Cards
- Total Revenue
- Total Orders
- Average Order Value
- Total Customers

## Key Insights
- Electronics generated the highest revenue due to high unit price products
- Groceries had the highest purchase frequency but lower revenue per order
- Lagos and Abuja contributed the highest total sales
- Customers aged 26–35 are the highest spending group
- High-income customers drive a significant portion of revenue
- Card payments are more common for high-value transactions

## Business Conclusions
- Revenue is strongly driven by premium product categories
- Customer demographics significantly influence spending behavior
- Geographic location is a key driver of sales performance
- Loyalty score is positively associated with higher spending

## Recommendations
- Focus marketing on high-income and loyal customer segments
- Expand product offerings in high-performing categories (Electronics)
- Improve sales strategies in underperforming cities
- Introduce customer loyalty reward programs
- Optimize pricing strategy for mid-tier customers

## Tools & Technologies
- HTML (Dashboard Development)
- CSS (Styling & Layout)
- JavaScript (Interactivity, if used)
- Excel (Data Cleaning)

<img width="1360" height="603" alt="Dashboard 1" src="https://github.com/user-attachments/assets/a60790c7-92e2-4825-b5c0-aed14cd0de4b" />

