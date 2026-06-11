# Online Bookstore SQL Project

## Project Overview

This project is a relational database system for an Online Bookstore developed using SQL. The database is designed to manage books, customers, and orders while supporting data retrieval, inventory management, and sales analysis.

The project demonstrates the use of SQL Data Definition Language (DDL), Data Manipulation Language (DML), filtering, aggregation functions, joins, grouping, and analytical queries.

## Database Structure

### 1. Books Table

Stores information about books available in the bookstore.

**Attributes:**

* Book_ID (Primary Key)
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### 2. Customers Table

Stores customer information.

**Attributes:**

* Customer_ID (Primary Key)
* Name
* Email
* Phone
* City
* Country

### 3. Orders Table

Stores order transactions and links customers with books.

**Attributes:**

* Order_ID (Primary Key)
* Customer_ID (Foreign Key)
* Book_ID (Foreign Key)
* Order_Date
* Quantity
* Total_Amount

## Key Features

### Data Management

* Create and manage bookstore tables
* Store book, customer, and order information
* Maintain relationships using primary and foreign keys

### Data Retrieval

* Retrieve books by genre
* Find books published after a specific year
* View customers from a particular country
* Display orders within a selected date range

### Inventory Analysis

* Calculate total stock available
* Identify books with the lowest stock
* Determine remaining stock after order fulfillment

### Sales Analysis

* Calculate total revenue generated
* Find the most frequently ordered book
* Identify top-spending customers
* Analyze books sold by genre and author

### Customer Insights

* Identify customers with multiple orders
* Locate customers based on spending patterns
* Analyze customer purchasing behavior

## SQL Concepts Used

* CREATE TABLE
* PRIMARY KEY
* FOREIGN KEY
* SELECT Statements
* WHERE Clause
* ORDER BY
* GROUP BY
* HAVING
* Aggregate Functions (SUM, AVG, COUNT)
* INNER JOIN
* LEFT JOIN
* DISTINCT
* LIMIT
* COALESCE

## Sample Queries Included

* Retrieve Fiction books
* Find books published after 1950
* Calculate total bookstore revenue
* Find the most expensive book
* Identify top customers by spending
* Calculate total books sold by genre
* Determine remaining inventory after sales

## Learning Outcomes

Through this project, the following database concepts were applied:

* Relational database design
* Entity relationship implementation
* Data filtering and sorting
* Aggregate analysis
* Multi-table joins
* Business-oriented SQL reporting
* Inventory and sales management analytics

## Author

Sumaiya

## Technologies Used

* SQL
* PostgreSQL

## Project Purpose

This project was developed for academic learning and demonstrates practical SQL skills through the design and analysis of an Online Bookstore database system.
