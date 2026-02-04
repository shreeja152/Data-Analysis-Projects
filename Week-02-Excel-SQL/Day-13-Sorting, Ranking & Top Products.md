# Day 13 Sorting, Ranking & Top Products

**Excel**

- Sorted products by total revenue
- Ranked products using RANK()
- Identified top-performing product


  <img width="443" height="114" alt="image" src="https://github.com/user-attachments/assets/a6d9baa9-ef01-4173-bf89-b300c086a370" />


```
=RANK(B2,$B$2:$B$4,0)+COUNTIF($B$2:B2,B2)-1
```
<br></br>

**SQL**
- Used ORDER BY to sort aggregated results
  
```sql
SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC;

```
  
- Used LIMIT to fetch top product

```sql
SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC
LIMIT 1;

```

