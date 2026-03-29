# Day 1 – SQL Basics

## Objective

Learn basic SQL queries to retrieve and analyse data.

## Concepts Covered

* SELECT statement
* WHERE clause
* ORDER BY
* Aggregate functions (SUM, AVG)
* GROUP BY

## Queries Practised

### Get all data

SELECT * FROM sales_data;

### Filter Electronics category

SELECT * FROM sales_data WHERE category = 'Electronics';

### Sales greater than 10000

SELECT * FROM sales_data WHERE sales > 10000;

### Sort by highest sales

SELECT * FROM sales_data ORDER BY sales DESC;

### Total sales

SELECT SUM(sales) FROM sales_data;

### Sales by category

SELECT category, SUM(sales)
FROM sales_data
GROUP BY category;

## Key Learnings

* SQL is used to query databases
* WHERE filters data
* GROUP BY works like Pivot Tables
* Aggregate functions help in analysis

🟢Use SQL Online (Best for You Now)

👉 No installation, no setup, start immediately

Recommended:
DB Fiddle https://www.db-fiddle.com/

SQLite Online https://sqliteonline.com/
