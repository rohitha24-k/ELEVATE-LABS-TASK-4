# Task 4: Aggregate Functions and Grouping in SQL

## Objective

The objective of this task is to understand how to summarize and analyze tabular data using **aggregate functions**, how to group data using **GROUP BY**, and how to filter grouped results using **HAVING**. These are essential SQL skills for anyone working with large datasets.

## Key Concepts Covered

### Aggregate Functions

Aggregate functions are used to perform **calculations across multiple rows** of data. These include:

- **COUNT**: Finds how many records exist.
- **SUM**: Adds up numeric values.
- **AVG**: Calculates the average of numeric values.
- **MIN / MAX**: Finds the smallest or largest value.

These functions help us **summarize** data and answer questions like:
- How many orders were placed?
- What is the total revenue?
- What is the average product price?

### GROUP BY Clause

`GROUP BY` is used to group data based on one or more columns. Instead of getting a single summary for the whole table, this allows us to **summarize data within each group**.

For example:
- Grouping by `CustomerID` tells us the total orders or payments made by each customer.
- Grouping by `CategoryID` shows us how many products exist in each category.
- Grouping by `PaymentMethod` gives insights into how people prefer to pay.

This is useful for identifying patterns, trends, and segments in your data.

### HAVING Clause

`HAVING` is used to filter groups **after aggregation**.

While `WHERE` filters **rows** before grouping, `HAVING` filters **groups** after they’ve been formed and summarized. This allows us to focus only on groups that meet specific conditions.

Example situations:
- Find customers who placed more than 2 orders.
- Show categories where the average product price is above ₹500.
- List payment methods with a total amount above ₹1000.

## What I Did in This Task

- Used aggregate functions like COUNT, SUM, and AVG to analyze numeric columns in various tables such as `Orders`, `Payments`, and `Products`.
- Applied `GROUP BY` to categorize data by columns like `CustomerID`, `CategoryID`, and `PaymentMethod`.
- Used `HAVING` to filter those groups based on summarized data, such as only selecting groups where totals or averages exceeded certain limits.
- Practiced writing logical, efficient queries that summarize complex datasets.

## What I Learned

- How to perform data summarization with aggregate functions.
- How to group and categorize data effectively using `GROUP BY`.
- The difference between `WHERE` and `HAVING`, and when to use each.
- How to derive business insights such as:
  - Top-paying customers
  - High-value product categories
  - Preferred payment methods

##  Screenshots

I have included screenshots of each query output to demonstrate the results visually. These are saved in the `task 4 screenshots` folder.
