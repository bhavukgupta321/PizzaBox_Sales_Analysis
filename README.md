# 🍕 PizzaBox Sales Analysis – SQL Project
## 📌 Project Overview
This project analyzes PizzaBox sales data using SQL to generate Key Performance Indicators (KPIs) and actionable insights.
The aim is to explore customer ordering patterns, revenue generation trends, and top-performing products to help optimize business decisions.

## 📂 Dataset Description
The project uses four main tables:

order_details – Contains the order details including pizza ID and quantity.

orders – Contains the order date and time details.

pizza_types – Contains pizza names, categories, and descriptions.

pizzas – Contains pizza IDs, type IDs, sizes, and prices.

## 🎯 Objectives
Identify key metrics like total orders, total revenue, and most popular pizzas.

Determine revenue and order distribution patterns over time.

Analyze category performance and size preferences.

Discover high-value pizzas and customer buying trends.

## 📊 Key KPIs
Total Orders Placed – Number of orders in the dataset.

Total Revenue Generated – Sum of all sales (quantity × price).

Highest-Priced Pizza – Identifies premium product.

Most Common Pizza Size Ordered – Helps in inventory planning.

Top 5 Most Ordered Pizza Types – Based on quantity sold.

Category-Wise Pizza Distribution – Number of pizzas in each category.

Orders by Hour of the Day – Helps in staffing and operational planning.

Average Pizzas Ordered Per Day – Demand forecasting metric.

Top 3 Pizza Types by Revenue – High-value revenue drivers.

Revenue Contribution by Category – Percentage breakdown of total sales.

Cumulative Revenue Over Time – Tracks revenue growth trend.

Top 3 Revenue Pizzas per Category – Identifies category leaders.

## 📈 Insights & Findings
Popular Sizes – Medium pizzas had the highest demand, indicating a customer preference for moderately sized portions.

Top Sellers – The Thai Chicken Pizza and Barbecue Chicken Pizza ranked among the highest-selling.

Revenue Leaders – Premium pizzas in the Chicken and Classic categories contributed most to total sales.

Peak Hours – Most orders occurred during evening hours.

Category Trends – Chicken and Classic pizzas dominate in both sales volume and revenue share.

## 🛠 SQL Techniques Used
JOIN operations to merge data from multiple tables.

Aggregate Functions (SUM, COUNT, AVG, ROUND) for KPI calculations.

Window Functions (RANK() OVER, SUM() OVER) for ranking and cumulative revenue.

GROUP BY and ORDER BY for grouping and sorting data.

Subqueries for nested analysis.
