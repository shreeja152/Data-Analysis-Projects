# Day 13 Sorting, Ranking & Top Products

**Excel**

- Sorted products by total revenue
- Ranked products using RANK()
- Identified top-performing product

**SQL**
- Used ORDER BY to sort aggregated results
  
```sql
SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC
LIMIT 1;
```
  
- Used LIMIT to fetch top product

```sql
SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC
LIMIT 1;
```

