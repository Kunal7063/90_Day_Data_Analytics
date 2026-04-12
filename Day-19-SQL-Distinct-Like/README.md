# Day 19 – SQL (DISTINCT & LIKE)

## Objective

Learn how to remove duplicates and search data using patterns.

## Concepts Covered

* DISTINCT
* LIKE operator
* Pattern matching

## Queries Practiced

### Unique categories

SELECT DISTINCT category FROM sales_data;

### Unique regions

SELECT DISTINCT region FROM sales_data;

### Customers starting with A

SELECT * FROM sales_data WHERE customer LIKE 'A%';

### Products containing 'top'

SELECT * FROM sales_data WHERE product LIKE '%top%';

## Key Learnings

* DISTINCT removes duplicate values
* LIKE helps in searching text data
* % represents multiple characters
* _ represents single character

