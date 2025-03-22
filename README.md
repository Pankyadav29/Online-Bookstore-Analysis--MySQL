# Online Bookstore Analysis using MySQL

## Project Overview
This project focuses on analyzing an Online Bookstore dataset using MySQL. The dataset consists of three key tables:

- **Orders.csv** – Contains details of all book purchases.

- **Customers.csv** – Stores customer information.

- **Books.csv** – Maintains book details such as title, genre, price, and stock.

By using SQL queries, this project extracts meaningful insights from sales, customers, and inventory data. The study is divided into Basic Queries and Advanced Queries, covering various aspects such as book sales, customer behavior, and revenue analysis.

## Dataset Description

| Table Name   | Description |
|-------------|------------|
| **Books**    | Holds book-specific details such as book ID, title, genre, author, price, and stock. |
| **Customers** | Contains customer details like customer ID, name, email, country, and city. |
| **Orders**   | Stores all order transactions with details like order ID, customer ID, book ID, quantity, total amount, and order date. |

## SQL Queries & Analysis

**🔹 Basic Queries**

1️⃣ Retrieve all books in the **"Fiction"** genre.  
2️⃣ Find books published after the year **1950**.  
3️⃣ List all customers from **Canada**.  
4️⃣ Show orders placed in **November 2023**.  
5️⃣ Retrieve the **total stock** of books available.  
6️⃣ Find the details of the **most expensive book**.  
7️⃣ Show customers who ordered **more than 1 quantity** of a book.  
8️⃣ Retrieve all orders where the **total amount exceeds $20**.  
9️⃣ List all **genres** available in the books table.   
🔟 Find the book with the **lowest stock**.  
1️⃣1️⃣ Calculate the **total revenue** generated from all orders.  

**🔹 Advanced Queries**

1️⃣ Retrieve **the total number of books sold** for each genre.  
2️⃣ Find the **average price** of books in the "Fantasy" genre.   
3️⃣ List customers who have placed **at least 2 orders**.  
4️⃣ Find the **most frequently ordered book**.  
5️⃣ Show the **top 3 most expensive books** in the "Fantasy" genre.  
6️⃣ Retrieve the **total quantity of books sold by each author**.  
7️⃣ List the **cities** where customers who spent over **$30** are located.  
8️⃣ Find the **customer who spent the most** on orders.  
9️⃣ Calculate the **stock remaining** after fulfilling all orders.  

## Key Insights & Findings

1. Total Revenue Generated: 💲 X,XXX (calculated using SQL query)
2. Most Expensive Book: "XYZ" priced at $XX.XX
3. Most Frequently Ordered Book: "ABC" with XXX orders
4. Highest Spending Customer: "John Doe" spent $XXX
5. Top 3 Cities with Highest Sales: City A, City B, City C
6. Genre with Highest Sales: Fiction with XXX books sold
7. Stock Left After All Orders: XXX books remaining

