# 📊 SQL Project – Elevate Labs Task

<img width="1919" height="1006" alt="Screenshot 2025-09-26 175841" src="https://github.com/user-attachments/assets/f35a895a-23c6-40dc-a864-9009bfd18e68" />


## 📌 Project Overview  
This project demonstrates SQL queries in **Oracle SQL** using two tables:  

- **B_SALES** – Sales transaction data  
- **B_PRICE** – Product price details  

The queries cover data retrieval, filtering, aggregation, joins, subqueries, views, and indexing.  
The aim is to showcase **SQL skills for data analysis and reporting**.  

---

##  Imported data from Excel using sql developer

<img width="1920" height="1200" alt="Screenshot 2025-09-26 171731" src="https://github.com/user-attachments/assets/8f71df61-c3be-4cde-8533-98dbfc002026" />


## ⚡ Key Features  

### 🔎 Basic Data Selection  
- Fetch specific columns from the **B_SALES** table  
- Limit results using `FETCH FIRST n ROWS ONLY`  

### 🎯 Filtering with WHERE  
- Extract records based on conditions (e.g., **sales in July**)  

### 📑 Sorting with ORDER BY  
- Sort products based on **price in descending order**  

### 📊 Grouping and Aggregation  
- Apply `GROUP BY` with aggregate functions:  
  - `COUNT()`  
  - `SUM()`  
  - `AVG()`  

### 🔗 Joins  
- Combine data from **B_SALES** and **B_PRICE** using:  
  - `INNER JOIN`  
  - `LEFT JOIN`  
  - `RIGHT JOIN`  

### 🌀 Subquery  
- Filter sales data using **nested queries**  

### 👁️ View Creation  
- A reusable view **Sales_Price_View** combining sales and price data  
- Includes row limits for optimized reporting  

### ⚡ Indexing  
- Indexes created on join columns (`PRODCT`, `PRODUCT`)  
- Improves query performance on large datasets  

---


