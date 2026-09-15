# Pizza Sales Analysis (SQL + Power BI)

## Project Overview

This project analyses pizza sales data using SQL to extract insights related to customer behaviour, sales performance, and revenue trends. The findings were then brought into an interactive Power BI dashboard, with KPIs, product and category breakdowns, and a 30-day revenue forecast.

## Dashboard Preview

![Dashboard Screenshot](Pizza%20Sales%20Analysis.png)

The full interactive Power BI file is available here: [Pizza Sales Analysis.pbix](Pizza%20Sales%20Analysis.pbix)

## Business Questions Addressed

- Total number of orders placed and total revenue generated
- Peak ordering hours and busiest days of the week
- Revenue contribution by pizza category
- Most popular pizza types and sizes
- Top-performing pizzas by quantity and revenue, overall and per category
- Cumulative and forecasted revenue trends

## Tools Used

- SQL (joins, aggregations, window functions - RANK() OVER PARTITION BY, subqueries)
- Power BI (DAX measures, interactive visuals, time-series forecasting)

## Key Insights

- Friday is the highest-revenue day of the week, with Sunday the lowest
- Orders peak around lunch (12-1 PM) and dinner (5-7 PM) hours
- Classic pizzas lead in revenue share (26.9%), closely followed by Supreme, Chicken, and Veggie
- Large pizzas are by far the most popular size, while XL and XXL make up a small fraction of orders
- Applied exponential smoothing in Power BI to forecast revenue for the next 30 days, with confidence intervals
