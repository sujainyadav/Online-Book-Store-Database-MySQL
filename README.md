# Online-Book-Store-Database-MySQL
**********************************************************************************
📚 Online Bookstore SQL Project
📌 Overview

This project is a relational database system built using SQL to manage an online bookstore. It covers database creation, data import, and querying for extracting meaningful business insights.

The project demonstrates:

Database design using multiple tables
Data handling using SQL queries
Business insights using analytical queries

***********************************************************************************
📁 Project Structure
Online-Bookstore-SQL/
│
├── bookstore.sql
├── Books.csv
├── Customers.csv
├── Orders.csv
└── README.md


***********************************************************************************

🗂️ Database Schema
📖 Books Table

Stores information about all available books.

Book_ID (Primary Key)
Title
Author
Genre
Published_Year
Price
Stock

***********************************************************************************

👤 Customers Table

Stores customer details.

Customer_ID (Primary Key)
Name
Email
Phone
City
Country

***********************************************************************************
🛒 Orders Table

Stores all order transactions.

Order_ID (Primary Key)
Customer_ID (Foreign Key)
Book_ID (Foreign Key)
Order_Date
Quantity
Total_Amount

***********************************************************************************

🔍 Key Queries
📌 Basic Queries
Retrieve all books in a specific genre
Find books published after a certain year
List customers by country
Get total available stock
Identify most expensive and least stocked books

***********************************************************************************
📊 Intermediate Queries
Orders within a specific date range
Customers ordering multiple quantities
Total revenue calculation
Unique genres available

***********************************************************************************
🚀 Advanced Queries
Total books sold by genre
Average price by genre
Customers with multiple orders
Most frequently ordered book
Top 3 expensive books in a genre
Total books sold per author
High spending customers
Customer with highest total spending
Remaining stock after fulfilling orders

***********************************************************************************
📈 Insights Generated
Best-selling genres
Top customers based on spending
Inventory management (low stock detection)
Overall revenue analysis

***********************************************************************************
🛠️ Technologies Used
SQL (PostgreSQL)
CSV Data Files
Relational Database Concepts
