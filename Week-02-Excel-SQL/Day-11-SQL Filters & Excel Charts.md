#SQL Filters & Excel Charts

Create Table (










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
