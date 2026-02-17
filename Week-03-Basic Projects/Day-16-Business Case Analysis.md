# DAY 16 Business Case Analysis (Data Creation + Master KPI Table)

***Scenario (Mini Case Study):***

Assume you are a Data Analyst at an E-commerce company.

Your are asked to find:

1. Analyze sales performance and tell me.

TOTAL REVENUE PER PRODUCT

```sql
SELECT product,
       SUM(price * quantity) AS total_revenue,
FROM sales
GROUP BY product
ORDER BY total_revenue DESC;
```

2. Which products generate the most revenue?

REVENUE PER CATEGORY

```sql
SELECT category,
        SUM(quantity * price) AS category_revenue,
FROM sales,
GROUP BY category,
ORDER BY category_revenue DESC;
```

3.Which category performs best?

4. Are we making profit or loss overall?

5. Which customers are our top spenders?”

   
