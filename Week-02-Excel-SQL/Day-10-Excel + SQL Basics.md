# DAY 10 — SQL BASICS

***Table Creation***

```sql
CREATE TABLE sales (

&nbsp; id INTEGER,

&nbsp; product TEXT,

&nbsp; quantity INTEGER,

&nbsp; price INTEGER

);
```

```sql
INSERT INTO sales VALUES (1, 'Phone', 2, 15000);

INSERT INTO sales VALUES (2, 'Headphones', 1, 2000);

INSERT INTO sales VALUES (3, 'Charger', 3, 500);

INSERT INTO sales VALUES (4, 'Phone', 1, 15000);
```

<br></br>

1. View all data 

```sql
SELECT \* FROM sales;
```

2. Select specific columns 

```sql
SELECT product, price FROM sales;
```

3. Filter data

```sql
SELECT \* FROM sales WHERE product = 'Phone';
```

4. Simple Calculations

```sql
SELECT product, quantity \* price AS total

FROM sales;
```
<br></br>


Data on Excel : 
-
<img width="410" height="190" alt="image" src="https://github.com/user-attachments/assets/2ffeb70b-03eb-49e1-9274-f4626f93a598" />












