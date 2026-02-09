# DAY 14 — Filtering Aggregated Data (HAVING)

**SQL** 

Show me only those products whose total revenue is greater than 2000.
```sql
SELECT product,
SUM (price * quantity)
AS total_revenue
FROM sales
GROUP BY product
HAVING total_revenue > 20000;
```

🔍 HAVING SUM (price * quantity) > 20000

Filters after aggregation
<br> Keeps only products whose total revenue exceeds 20,000. </br>

🔍 This is why WHERE won’t work here:

WHERE runs before SUM
<br> HAVING runs after SUM </br>

