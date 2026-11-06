# 🗄️ SQL Data Analysis Project

## 📖 Overview

This project was completed as part of a Level 3 Data Technician Bootcamp, where I developed practical SQL skills by querying and analysing data from relational databases, including the **Northwind** and **World** datasets. The project focused on extracting insights, filtering data, combining tables, and generating business reports using SQL.

---

## 🚀 Key Skills Demonstrated

### 🔍 SQL Query Fundamentals

Created and executed SQL queries using:

- ✅ `SELECT`
- ✅ `FROM`
- ✅ `WHERE`
- ✅ `ORDER BY`
- ✅ `DISTINCT`
- ✅ `AND`
- ✅ `OR`
- ✅ `IN`
- ✅ `BETWEEN`
- ✅ `LIKE`
- ✅ `LIMIT`

#### 📌 Examples
- Retrieved customer, product, and order information.
- Filtered records based on business requirements.
- Sorted datasets in ascending and descending order.
- Identified unique values using `DISTINCT`.
- Limited result sets for concise reporting.
- Applied conditional logic to answer real-world business questions.

---

### 📊 Data Filtering & Analysis

Applied SQL filtering techniques to analyse data and answer business-focused questions:

- 💰 Products priced above specified values.
- 🌍 Customers located in selected countries and cities.
- 📅 Orders placed within defined date ranges.
- 🏙️ Cities with target population ranges.
- 🔎 Text-based searches using `LIKE`.

These queries helped uncover patterns, trends, and actionable insights from large datasets.

---

### 🔗 SQL Joins

Combined data across multiple related tables using:

- ✅ `INNER JOIN`
- ✅ `LEFT JOIN`

Gained understanding of:

- 📌 `RIGHT JOIN`
- 📌 `FULL JOIN`
- 📌 `CROSS JOIN`

#### Join Applications
- Linked products with suppliers.
- Connected products to categories.
- Combined customer and order information.
- Built multi-table business reports.
- Retrieved related records using primary and foreign key relationships.

---

### 📈 Aggregation & Reporting

Used aggregate functions to summarise business data:

select *
from customers
where country IN ('USA', 'UK');

select
products.productid,
products.productname,
categories.categoryname
from products
inner join categories
on products.categoryid = categories.categoryid;

- `
