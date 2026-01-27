# Day 13 Sorting, Ranking & Top Products

**Excel**

- Sorted products by total revenue
  

  <br></br>
- Ranked products using RANK()
- Identified top-performing product

**SQL**
- Used ORDER BY to sort aggregated results

SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC;

<br></br>
  
- Used LIMIT to fetch top product

SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC
LIMIT 1;
