# Day 18 – SQL (COUNT & HAVING)

## Objective

Learn how to count records and filter grouped data using HAVING.

## Concepts Covered

* COUNT()
* GROUP BY
* HAVING clause
* Writing clean SQL queries

## Queries Practiced

### Count total records

SELECT COUNT(*) FROM sales_data;

### Orders per region

SELECT region, COUNT(*) AS total_orders
FROM sales_data
GROUP BY region;

### Sales per category

SELECT category, SUM(sales) AS total_sales
FROM sales_data
GROUP BY category;

### Filter categories with high sales

SELECT category, SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
HAVING SUM(sales) > 20000;

## Key Learnings

* COUNT is used to count rows
* GROUP BY groups data like Pivot Tables
* HAVING filters aggregated results
* Clean queries improve readability

