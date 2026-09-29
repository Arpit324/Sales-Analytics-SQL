# Sales Analytics — SQL

## Project Overview

This project uses MySQL to analyze sales data and answer 25 business-focused questions related to customers, products, orders, revenue, regional performance, and customer behavior.

## Business Objectives

The analysis was performed to understand:

- Customer and product volume
- Order volume
- Total revenue
- Average Order Value (AOV)
- Product revenue performance
- Customer revenue performance
- Regional revenue performance
- Product category performance
- Monthly revenue trends
- Salesperson performance
- Customer order behavior
- Product sales quantity
- Revenue rankings

## Analysis Performed

The project contains 25 SQL analysis questions covering:

1. Total customers
2. Total products
3. Total orders
4. Total revenue
5. Average Order Value (AOV)
6. Top 5 products by revenue
7. Top 5 customers by revenue
8. Regional revenue
9. Customers with multiple orders
10. Revenue by product category
11. Monthly revenue trend
12. Salesperson revenue performance
13. Customers generating more than ₹1,00,000 revenue
14. Average revenue per customer
15. Highest-revenue month
16. Customers with the highest number of orders
17. High-revenue customers with at least 2 orders
18. Customers who never placed an order
19. Percentage of customers who placed at least one order
20. Product with the highest quantity sold
21. Products that were never ordered
22. Product with the highest revenue
23. Regional revenue ranking
24. Customer revenue compared with average customer revenue
25. Top 3 customers by revenue with order count and rank

## SQL Concepts Used

- SELECT
- COUNT()
- SUM()
- AVG()
- ROUND()
- JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- Subqueries
- CTE (Common Table Expression)
- DATE_FORMAT()
- Window Functions
- RANK()
- AVG() OVER()

## Revenue Calculation

Revenue was calculated using:

```sql
quantity * unit_price * (1 - discount / 100)
