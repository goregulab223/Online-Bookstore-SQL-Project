# 📚 Online Bookstore SQL Project

## 📌 Project Overview
This project simulates an **Online Bookstore database** using SQL.  
It demonstrates database design, data import, and both basic and advanced SQL queries to analyze sales, customers, and inventory.

---

## 🎯 Project Objectives
- Design a relational database for an online bookstore
- Perform data analysis using SQL queries
- Analyze sales, customers, genres, and revenue
- Calculate inventory impact after orders

---

## 🗂 Database Schema
The database consists of **three tables**:

### 📘 Books
- Book_ID (Primary Key)
- Title
- Author
- Genre
- Published_Year
- Price
- Stock

### 👤 Customers
- Customer_ID (Primary Key)
- Name
- Email
- Phone
- City
- Country

### 🛒 Orders
- Order_ID (Primary Key)
- Customer_ID (Foreign Key)
- Book_ID (Foreign Key)
- Order_Date
- Quantity
- Total_Amount

---

## 📥 Dataset
CSV files used:
- Books.csv
- Customers.csv
- Orders.csv  

(Data imported using `COPY` command in PostgreSQL)

---

## 🔍 SQL Concepts Used
- Database & table creation
- Primary & foreign keys
- Joins (INNER, LEFT)
- Aggregate functions (SUM, AVG, COUNT)
- GROUP BY & HAVING
- Subqueries
- Date filtering
- Inventory calculations

---

## 📊 Key Analysis Performed
- Total revenue generated
- Most expensive & most ordered books
- Genre-wise book sales
- Customer purchase behavior
- Author-wise sales analysis
- Stock remaining after fulfilling orders
- High-value customers and cities

---

## 🛠 Tools Used
- PostgreSQL
- SQL
- CSV Files

---

## 👤 Author
**Gulab Gore**  
