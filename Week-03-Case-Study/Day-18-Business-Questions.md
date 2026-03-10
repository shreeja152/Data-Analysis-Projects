# Business Questions

### Revenue Questions

1. What is the total revenue of the business?
```sql

SELECT 
    SUM(quantity * price) AS total_revenue
FROM Sales;
```

2. What is total profit?

```sql
SELECT 
    SUM((price - cost) * quantity) AS total_profit
FROM Sales;
```

3. What is total number of units sold?

```sql
SELECT 
    SUM(quantity) AS total_units_sold
FROM Sales;
```

---

### Product Performance

4. Which product generates the highest revenue?

```sql
SELECT 
    product,
    SUM(quantity * price) AS total_revenue
FROM Sales
GROUP BY product
ORDER BY total_revenue DESC
LIMIT 1;

```

5. 
