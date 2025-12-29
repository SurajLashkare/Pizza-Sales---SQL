# Pizza-Sales---SQL

# Pizza Sales Analysis

This project analyzes Pizza Hut’s sales performance using SQL for data queries and Power BI for data modeling.

***

## Project Overview

- Title: PIZZA SALES ANALYSIS
- Objective: Solve complex business questions around pizza sales using SQL, with Power BI used for robust data modeling to establish a relational schema.

---

## Data Modeling (Power BI)

A relational schema with four interconnected tables was built in Power BI:

- **Orders**: Records the date and time of each order.
- **Order_details**: Tracks the specific `pizza_id` and quantity for every order.
- **Pizzas**: Contains details on pizza sizes and their respective prices.
- **Pizza_types**: Includes the name, category, and ingredients.

***

## SQL Analysis & Business Insights

Key metrics and insights derived from SQL queries:

### Sales Performance
- **Total Revenue**: \$817,860.05
- **Total Orders**: 21,350
- **Highest-Priced Pizza**: The Greek Pizza at \$35.95
- **Revenue Contribution by Category**: 
  - Classic: 26.91%
  - Supreme: 25.46%
  - Chicken: 23.96%

### Customer Preferences
- **Popular Size**: Large (L) with 18,526 orders
- **Top Best Sellers**: 
  - The Classic Deluxe Pizza (2,453 quantity)
  - The Barbecue Chicken Pizza
  - The Hawaiian Pizza
- **Category Volume**: Classic category with 14,888 orders

### Time-Based Trends
- **Peak Hours**: Lunch (12:00 PM – 1:00 PM) and Evening (5:00 PM – 7:00 PM)
- **Daily Average**: 138 pizzas ordered per day

***

## Tools & Technical Skills

- **SQL (Main Tool)**: Data aggregation, multi-table joins, subqueries, and window functions (e.g., `RANK()`, `SUM() OVER()`).
- **Power BI**: Data modeling to visualize relationships and schemas.
- **Data Analysis**: Trend analysis, revenue growth tracking, and distribution studies.

---

## Repository Structure

- `pizza_sales_sql_queries.sql` — All SQL code used for the analysis.
  
- `pizza_sales.zip/` — CSV files used for this analysis.

***

## About the Author

Developed by: Suraj Lashkare
