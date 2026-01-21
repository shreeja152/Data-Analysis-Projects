#SQL Filters & Excel Charts

Create Table (
id INTEGER,
product TEXT,
quantity INTEGER,
price INTEGER
);

INSERT INTO sales VALUES (1, 'Phone', 2, 15000);
INSERT INTO sales VALUES (2, 'Headphones', 1, 2000);
INSERT INTO sales VALUES (3, 'Charger', 3, 500);
INSERT INTO sales VALUES (4, 'Phone', 1, 15000);


#1 Filter all sales with price above 1000

SELECT * 
FROM sales 
WHERE price > 1000;

#2 Filter all sales where product is 'Phone'

SELECT * 
FROM sales 
WHERE product = 'Phone';

#3 Filter all sales where product is 'Phone' AND price above 1000

SELECT * 
FROM sales 
WHERE product = 'Phone' AND price > 1000;
