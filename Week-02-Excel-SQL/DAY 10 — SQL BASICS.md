# DAY 10 — SQL BASICS





CREATE TABLE sales (

&nbsp; id INTEGER,

&nbsp; product TEXT,

&nbsp; quantity INTEGER,

&nbsp; price INTEGER

);



INSERT INTO sales VALUES (1, 'Phone', 2, 15000);

INSERT INTO sales VALUES (2, 'Headphones', 1, 2000);

INSERT INTO sales VALUES (3, 'Charger', 3, 500);

INSERT INTO sales VALUES (4, 'Phone', 1, 15000);



#View all data 



SELECT \* FROM sales;





#Select specific columns 

SELECT product, price FROM sales;



#Filter data

SELECT \* FROM sales WHERE product = 'Phone';





#Simple Calculations

SELECT product, quantity \* price AS total

FROM sales;




