# DAY 12 Aggregation using Excel FORMULAS

**EXCEL**

1. Total Revenue (Using SUMIF) 



<img width="231" height="125" alt="image" src="https://github.com/user-attachments/assets/7497dcef-13bf-458a-be9d-0b1c1b73fab8" />
<p></p>
=SUMIF(Sheet1!B:B, A2, Sheet1!E:E)

<br><br>

2. Average Price (Using AVERAGEIF)



<img width="365" height="142" alt="image" src="https://github.com/user-attachments/assets/acbb932a-b69d-40bc-b1b3-a635357c9c7a" />

<br><br>

**SQL**

SQL Concepts

- SUM()

- AVG()

- GROUP BY

<p>
</p>

1. Total Revenue

SELECT product, SUM(revenue) AS total_revenue
FROM sales
GROUP BY product;

<p> </p>

2. Average Revenue

SELECT product, AVG(price) AS avg_price
FROM sales
GROUP BY product;




