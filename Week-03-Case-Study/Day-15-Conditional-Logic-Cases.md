# DAY 15 - CONDITIONAL LOGIC (Case When)

***SQL***

Classify each order based on how much revenue it generated.

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

***Excel***

```
=IF(C2>=20000,"High Revenue",
IF(C2>=10000,"Medium Revenue","Low Revenue"))
```
