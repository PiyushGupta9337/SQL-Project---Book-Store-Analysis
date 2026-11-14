# SQL-Project---Book-Store-Analysis
# 📚 Online Bookstore SQL Analysis

## 📌 Project Overview
This project focuses on analyzing an **Online Bookstore database** using SQL. The objective is to explore book sales, customer purchasing behavior, inventory levels, and revenue generation through SQL queries.

The project uses a relational database consisting of three interconnected tables: **Books, Customers, and Orders**. It covers basic as well as advanced SQL concepts to extract meaningful business insights from the data.

## 🗂️ Database Structure

The project consists of three tables:

### 1. Books
Stores information about books available in the bookstore.

| Column Name | Description |
|---|---|
| Book_ID | Unique ID of each book |
| Title | Name of the book |
| Author | Book author |
| Genre | Book category |
| Published_Year | Year of publication |
| Price | Price of the book |
| Stock | Available stock |

### 2. Customers
Contains customer-related information.

| Column Name | Description |
|---|---|
| Customer_ID | Unique customer ID |
| Name | Customer name |
| Email | Customer email |
| Phone | Customer contact number |
| City | Customer city |
| Country | Customer country |

### 3. Orders
Contains details of customer purchases.

| Column Name | Description |
|---|---|
| Order_ID | Unique order ID |
| Customer_ID | Reference to Customers table |
| Book_ID | Reference to Books table |
| Order_Date | Date of purchase |
| Quantity | Number of books ordered |
| Total_Amount | Total order amount |

## 🛠️ Tools & Technologies
- **PostgreSQL** – Database management system
- **SQL** – Data querying and analysis
- **GitHub** – Project documentation and version control

## 📊 SQL Concepts Used

This project demonstrates the practical application of:

- SELECT and WHERE
- ORDER BY and LIMIT
- DISTINCT
- Aggregate Functions (SUM, AVG, COUNT)
- GROUP BY and HAVING
- JOINS (INNER JOIN and LEFT JOIN)
- Subqueries
- COALESCE
- Primary Keys and Foreign Keys
- Data Import using CSV files

## 🔍 Business Questions & Analysis

The project answers 22 business questions, divided into basic and advanced SQL queries.

### Basic Analysis
1. Retrieve all books belonging to the Fiction genre.
2. Find books published after 1950.
3. List customers from Canada.
4. Retrieve orders placed in November 2023.
5. Calculate the total stock of available books.
6. Find the most expensive book.
7. Identify orders with a quantity greater than one.
8. Retrieve orders with a total amount exceeding $20.
9. List all unique book genres.
10. Find the book with the lowest stock.
11. Calculate the total revenue generated from all orders.

### Advanced Analysis
1. Calculate total books sold for each genre.
2. Find the average price of Fantasy books.
3. Identify customers who have placed at least two orders.
4. Find the most frequently ordered book.
5. Retrieve the top three most expensive Fantasy books.
6. Calculate total books sold by each author.
7. Identify cities where customers placed orders worth more than $30.
8. Find the customer who spent the most.
9. Calculate the remaining stock after fulfilling all orders.

## 📈 Key Business Insights

The SQL queries are designed to help understand:

- **Sales Performance:** Identify popular genres and frequently ordered books.
- **Customer Behavior:** Analyze repeat customers and spending patterns.
- **Revenue Analysis:** Calculate overall revenue and identify top-spending customers.
- **Inventory Management:** Track available stock and estimate remaining inventory.
- **Product Performance:** Compare book prices, authors, and sales quantities.

## 📁 Project Files

```text
Online-Bookstore-SQL-Analysis/
│
├── Book store Analysis.sql
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open PostgreSQL or pgAdmin.
3. Execute the SQL file to create the database and tables.
4. Import the Books, Customers, and Orders CSV datasets.
5. Run the SQL queries to perform the analysis.

**Note:** Update the CSV file paths in the COPY commands according to your local system before executing the data import statements.

## 🎯 Project Objective

The main objective of this project is to strengthen SQL skills through a practical business use case and demonstrate how relational databases can be used to analyze sales, customer behavior, revenue, and inventory.

---

**If you find this project useful, feel free to explore the queries and share your feedback!**
