# Day 03 – Data Sources in Companies

## Databases

Databases store structured data in tables.

Example:

| Customer ID | Product | Price | Date |
|-------------|--------|------|------|
| 101 | Mobile | 15000 | 10-03-2026 |
| 102 | Shoes | 2500 | 11-03-2026 |

Common databases used by companies:
- MySQL
- PostgreSQL
- Oracle
- SQL Server

Data analysts retrieve data using SQL queries.

Example query:

SELECT product, price
FROM orders
WHERE price > 5000;

---

## Application Data

User actions on websites or apps generate data.

Examples:
- Search activity
- Product views
- Cart additions
- Purchases

Example:

| User ID | Action | Product | Time |
|--------|--------|--------|------|
| 201 | Search | iPhone | 10:15 AM |
| 201 | Add to Cart | iPhone | 10:18 AM |

---

## APIs

APIs allow systems to exchange data automatically.

Example API response:

{
 "city": "Kolkata",
 "temperature": 31,
 "humidity": 70
}

APIs are commonly used for payment processing, shipping updates, and external services.

---

## Logs

Logs record system events and user activity.

Example:

User logged in  
Item added to cart  
Payment successful

Logs help track errors and system performance.

---

## External Data Sources

Companies also use external data such as:

- Government datasets
- Social media data
- Market research data
- Public datasets

These sources help businesses make better decisions.


## Practice Example – Food Delivery App

### Data from Users
- Search history
- Favorite foods
- Order history
- Payment status
- Ratings and reviews

### Data from Restaurants
- Menu items
- Food prices
- Preparation time
- Order acceptance status
- Restaurant ratings

### Data from Delivery Partners
- Pickup time
- Delivery time
- GPS tracking
- Distance travelled
- Delivery completion status
