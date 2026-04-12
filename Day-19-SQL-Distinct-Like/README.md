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
* _ represents a single character

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/a9e1aef7-6f5a-47f7-bb88-1e509b6c1cd2" />
<img width="841" height="308" alt="image" src="https://github.com/user-attachments/assets/84c74ebc-ee71-48a8-90ab-f70c2f886f3d" />
