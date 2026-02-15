# online_bookstore_sql_analysis
# Online Bookstore SQL Analysis

## Project Overview

This project demonstrates SQL-based data analysis using a online bookstore database.
The database contains information about books, customers, and orders, and is used to perform business-oriented analysis such as revenue calculation, customer behavior, and inventory tracking.

## Objectives

* Import structured CSV data into PostgreSQL
* Perform analytical SQL queries
* Extract business insights from transactional data

## Database Structure

The database consists of three main tables:

### 1. Books

* Book_ID (Primary Key)
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### 2. Customers

* Customer_ID (Primary Key)
* Name
* Email
* Phone
* City
* Country

### 3. Orders

* Order_ID (Primary Key)
* Customer_ID (Foreign Key)
* Book_ID (Foreign Key)
* Order_Date
* Quantity
* Total_Amount

## Key Business Questions Answered

* Total revenue generated
* Most frequently ordered book
* Top-spending customer
* Sales by genre
* Remaining stock after orders

## Example Insights

* Identified the most popular genre based on quantity sold
* Calculated total revenue from all transactions
* Found high-value customers and cities with large orders

## Tools Used

* PostgreSQL
* SQL (joins, aggregations, filtering)
* CSV data sources

## How to Run the Project

1. Create the database:

   ```sql
   CREATE DATABASE OnlineBookstore;
   ```
2. Connect to the database.
3. Run `schema.sql` to create tables.
4. Import CSV files from the `data/` folder.
5. Run queries from the `queries/` folder.

## Project Skills Demonstrated

* Database design
* Data import and validation
* SQL joins and aggregations
* Business-focused data analysis

## Author

Himaj S. Deshmukh
GitHub: https://github.com/your-username
