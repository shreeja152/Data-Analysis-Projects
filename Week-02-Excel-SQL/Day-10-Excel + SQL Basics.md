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

<p>  </p>

#1 View all data 



SELECT \* FROM sales;





#2 Select specific columns 

SELECT product, price FROM sales;



#3 Filter data

SELECT \* FROM sales WHERE product = 'Phone';





#4 Simple Calculations

SELECT product, quantity \* price AS total

FROM sales;


Data on Excel : 
-
<img width="410" height="190" alt="image" src="https://github.com/user-attachments/assets/2ffeb70b-03eb-49e1-9274-f4626f93a598" />









