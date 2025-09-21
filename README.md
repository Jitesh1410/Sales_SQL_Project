# Sales SQL Project

## Project Overview
This project uses SQL to create and analyze a Sales dataset.  
It includes table creation, data cleaning, and exploratory data analysis (EDA) queries.

---

## Table Structure
The `sales` table includes:

- transactions_id (Primary Key)  
- sale_date  
- sale_time  
- customer_id  
- gender  
- age  
- category  
- quantity  
- price_per_unit  
- cogs  
- total_sale  

---

## Data Cleaning
- Check for NULL values.  
- Delete rows with NULL values.  

---

## Exploratory Data Analysis (EDA) Queries
1. Sales on a specific date (`2022-11-05`).  
2. High-quantity Clothing sales in Nov-2022.  
3. Total sales per category.  
4. Average age of Beauty category customers.  
5. Transactions with total_sale > 1000.  
6. Transactions by gender in each category.  
7. Best-selling month per year.  
8. Top 5 customers by total sales.  
9. Unique customers per category.  
10. Sales by shift (Morning, Afternoon, Evening).  

---

## How to Use
1. Import `sales.sql` into your SQL database.  
2. Run the script to:
   - Create the `sales` table.  
   - Clean the data.  
   - Execute EDA queries.  
