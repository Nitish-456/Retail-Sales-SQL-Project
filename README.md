# 🛍️ Retail Sales Analysis using SQL

## 📌 Project Overview

This project focuses on analyzing retail sales data using **PostgreSQL**. The goal is to answer common business questions by writing SQL queries that extract meaningful insights from transactional sales data.

The project covers the complete SQL workflow, including:

* Database creation
* Table creation
* Data cleaning
* Data exploration
* Business analysis using SQL
* Aggregate functions
* Window functions
* Common Table Expressions (CTEs)

This project helped me strengthen my understanding of SQL concepts and apply them to solve real-world business problems.

---

# 🛠️ Tools Used

* **Database:** PostgreSQL
* **Language:** SQL

---

# 📂 Dataset Information

The dataset contains retail transaction records with the following columns:

| Column         | Description                     |
| -------------- | ------------------------------- |
| transaction_id | Unique transaction ID           |
| sale_date      | Date of sale                    |
| sale_time      | Time of sale                    |
| customer_id    | Customer identifier             |
| gender         | Customer gender                 |
| age            | Customer age                    |
| category       | Product category                |
| quantity       | Quantity purchased              |
| price_per_unit | Price of one unit               |
| cogs           | Cost of goods sold              |
| total_sale     | Total amount of the transaction |

---

# 📋 Project Workflow

## 1. Database Creation

* Created a PostgreSQL database.
* Created the `retail_sales` table with appropriate data types.

---

## 2. Data Cleaning

Before performing any analysis, the dataset was checked for missing values.

The following columns were validated:

* Transaction ID
* Sale Date
* Sale Time
* Gender
* Category
* Quantity
* COGS
* Total Sale

Rows containing NULL values in important columns were removed to ensure accurate analysis.

---

## 3. Data Exploration

Performed some basic exploratory analysis, including:

* Total number of sales
* Number of unique customers
* Available product categories

---

# 📊 Business Questions Solved

### Q1. Sales on a Specific Date

Retrieved all transactions made on **5 November 2022**.

---

### Q2. Clothing Sales Analysis

Retrieved all Clothing transactions where:

* Quantity sold was greater than the specified limit
* Sale occurred during November 2022

---

### Q3. Total Sales by Category

Calculated:

* Total revenue for each category
* Total number of orders

---

### Q4. Average Customer Age

Calculated the average age of customers who purchased products from the **Beauty** category.

---

### Q5. High Value Transactions

Retrieved all transactions where the total sale amount exceeded **1000**.

---

### Q6. Transactions by Gender and Category

Calculated the number of transactions made by each gender across different product categories.

---

### Q7. Best Selling Month

Calculated the average monthly sales and identified the highest-performing month in each year using SQL Window Functions.

---

### Q8. Top Customers

Identified the **Top 5 customers** based on their total purchase amount.

---

### Q9. Unique Customers by Category

Calculated the number of unique customers who purchased from each product category.

---

### Q10. Sales Shift Analysis

Classified each order into one of three shifts based on sale time:

| Shift     | Time               |
| --------- | ------------------ |
| Morning   | Before 12:00 PM    |
| Afternoon | 12:00 PM – 5:59 PM |
| Evening   | After 5:59 PM      |

Then counted the total number of orders in each shift.

---

# 💡 SQL Concepts Used

This project demonstrates practical use of:

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* DISTINCT
* Aggregate Functions

  * COUNT()
  * SUM()
  * AVG()
* Date Functions

  * EXTRACT()
  * TO_CHAR()
* CASE Statement
* Common Table Expressions (CTE)
* Window Functions

  * RANK()
* DELETE
* Data Cleaning Techniques

---

# 📈 Key Learnings

Through this project, I gained hands-on experience with:

* Writing clean and readable SQL queries
* Solving real business problems using SQL
* Working with date and time functions
* Using aggregate functions for reporting
* Applying Window Functions for ranking and analysis
* Creating Common Table Expressions (CTEs)
* Performing data cleaning before analysis

---

# 🚀 Future Improvements

Some possible enhancements for this project include:

* Building an interactive Power BI dashboard
* Creating SQL Views for reusable reports
* Adding stored procedures and functions
* Optimizing queries for large datasets
* Automating monthly sales reports

---

# 📁 Repository Structure

```text
Retail_Sales_SQL_Project/
│
├── retail_sales.sql        # Complete SQL script
├── README.md               # Project documentation
└── dataset.csv             # Dataset (if included)
```

---

# 👨‍💻 Author

**Nitish Singh**

Aspiring **Data Analyst** with a strong interest in SQL, Power BI, Excel, and Python. I enjoy solving business problems using data and continuously improving my analytical skills through hands-on projects.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
