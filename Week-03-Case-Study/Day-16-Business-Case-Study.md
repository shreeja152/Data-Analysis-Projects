# DAY 16 Business Case Study (Data Creation + Master KPI Table)

***Scenario (Case Study):***

Assume you are a Data Analyst at an E-commerce company.
Your are asked to create the data of the company's sales as well as analyze the trends in their data.

**MASTER PERFORMANCE TABLE CREATION**

```sql
CREATE TABLE Sales (
    id INT,
    product VARCHAR(50),
    category VARCHAR(50),
    customer_name VARCHAR(50),
    price DECIMAL(10,2),
    quantity INT,
    cost DECIMAL(10,2)
);

INSERT INTO Sales VALUES
(1, 'Laptop', 'Electronics', 'Rahul', 50000, 1, 42000),
(2, 'Phone', 'Electronics', 'Priya', 20000, 2, 15000),
(3, 'Tablet', 'Electronics', 'Amit', 15000, 1, 12000),
(4, 'Chair', 'Furniture', 'Rahul', 5000, 3, 3000),
(5, 'Desk', 'Furniture', 'Sneha', 10000, 1, 7000),
(6, 'Phone', 'Electronics', 'Rahul', 20000, 1, 15000),
(7, 'Laptop', 'Electronics', 'Priya', 50000, 1, 42000),
(8, 'Chair', 'Furniture', 'Amit', 5000, 2, 3000);

```

<img width="1519" height="378" alt="image" src="https://github.com/user-attachments/assets/786fe21d-d5a8-4cf7-b8ae-e04f00d9fe5c" />

---

**EXCEL**


<img width="1133" height="333" alt="image" src="https://github.com/user-attachments/assets/7bc7cfc9-2962-4a90-a0f1-35a6d2a8ebec" />


   
