# DAY 15 - CONDITIONAL LOGIC (Case When)

***SQL***

```sql
SELECT
id,
product,
quantity,
price,
price * quantity AS product_revenue,
CASE
    WHEN price * quantity >= 20000 THEN 'HIGH REVENUE'
    WHEN price * quantity >= 10000 THEN 'MEDIUM REVENUE'
    ELSE 'LOW REVENNUE'
END AS revenue_category
FROM sales;
```
