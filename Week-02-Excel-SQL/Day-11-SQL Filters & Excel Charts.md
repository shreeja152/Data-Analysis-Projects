# DAY 11 — SQL Filters & Excel



```sql

CREATE TABLE sales (

id INTEGER,

product TEXT,

quantity INTEGER,

price INTEGER

);



INSERT INTO sales VALUES (1, 'Phone', 2, 15000);

INSERT INTO sales VALUES (2, 'Headphones', 1, 2000);

INSERT INTO sales VALUES (3, 'Charger', 3, 500);

INSERT INTO sales VALUES (4, 'Phone', 1, 15000);
```

<br></br>

1. Filter all sales with price above 1000

```sql 
SELECT * 
FROM sales 
WHERE price > 1000;
```

2. Filter all sales where product is 'Phone'                      

```sql
SELECT * 
FROM sales 
WHERE product = 'Phone';
```

3. Filter all sales where product is 'Phone' AND price above 1000

```sql
SELECT * 
FROM sales 
WHERE product = 'Phone' AND price > 1000;
```

<br></br>

EXCEL 
-

1. Turn ON Filters


   <img width="506" height="146" alt="image" src="https://github.com/user-attachments/assets/58606363-cd97-4049-b9ee-6fe7110c46e8" />



2. Filter by PRODUCT

   
   <img width="505" height="125" alt="image" src="https://github.com/user-attachments/assets/18f2765a-4f78-43e2-80dd-033dbd4a253d" />
   

3. Filter by PRODUCT

   
   <img width="496" height="122" alt="image" src="https://github.com/user-attachments/assets/8276ff87-baf7-49b2-86e6-02feb5985ed2" />

4. Create the Revenue Chart

<img width="1147" height="603" alt="image" src="https://github.com/user-attachments/assets/7c98f0ab-5d36-4080-8577-3eccf97293fc" />
