# ADDING KPIs IN TABLE

Q. Give me performance metrics by Product, by Category, and by Customer — all in one report.

So now, we will find and add the KPIs by finding the
- total revenue per product
- quantity sold per product
- total profit per product

```sql
SELECT 
    'Product' AS dimension_type,
    product AS dimension_value,
    SUM(quantity * price) AS total_revenue,
    SUM(quantity) AS total_units,
    SUM((price - cost) * quantity) AS total_profit
FROM Sales
GROUP BY product

UNION ALL

SELECT 
    'Category' AS dimension_type,
    category AS dimension_value,
    SUM(quantity * price) AS total_revenue,
    SUM(quantity) AS total_units,
    SUM((price - cost) * quantity) AS total_profit
FROM Sales
GROUP BY category

UNION ALL

SELECT 
    'Customer' AS dimension_type,
    customer_name AS dimension_value,
    SUM(quantity * price) AS total_revenue,
    SUM(quantity) AS total_units,
    SUM((price - cost) * quantity) AS total_profit
FROM Sales
GROUP BY customer_name;

```
