# DAY 15 - CONDITIONAL LOGIC (Case When)

***SQL***

```sql
SELECT
id,
product,
quantity,
price,
price * quantity AS product_revenue
CASE
    WHEN product_revenue >= 20000 THEN 'HIGH REVENUE'
    WHEN product_revenue >= 10000 THEN 'MEDIUM REVENUE'
    ELSE 'LOW REVENNUE'
END AS 'revenue_category'
FROM sales
```
