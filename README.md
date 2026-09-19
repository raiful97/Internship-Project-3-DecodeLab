# 📊 DecodeLabs SQL Project 3 --- E-Commerce Sales Analysis

## Overview

This project is part of the **DecodeLabs SQL Series (Project 3)**. The
objective was to analyze an e-commerce orders dataset using
**PostgreSQL** and answer real business questions through SQL queries.

## Dataset

**Table:** `orders`

Key columns:

-   `order_id`
-   `customer_id`
-   `product`
-   `total_price`
-   `payment_method`
-   `referral_source`
-   `order_status`

## Business Questions Solved

### 1. Referral Source Performance

Identify which marketing channel generated the most orders.

**Result**

  Referral Source     Orders
  ----------------- --------
  Instagram              259
  Email                  250
  Google                 241
  Facebook               228
  Referral               222

### 2. Top 5 Highest Value Orders

Retrieve the highest revenue generating orders.

**Insight:** The highest order value reached **3456.40**.

### 3. Online Payment Analysis

Filter customers who paid using the **Online** payment method and rank
them by purchase value.

### 4. Average Order Value (AOV)

**Average Order Value:** **1053.97**

### 5. Revenue by Product

  Product       Revenue
  --------- -----------
  Chair       195620.11
  Printer     195612.61
  Laptop      192126.56
  Tablet      186568.95
  Monitor     175651.41
  Desk        167459.93
  Phone       151722.39

### 6. Order Status Distribution

  Status        Orders
  ----------- --------
  Cancelled        250
  Returned         247
  Pending          237
  Shipped          235
  Delivered        231

## SQL Concepts Used

-   SELECT
-   WHERE
-   GROUP BY
-   ORDER BY
-   COUNT()
-   SUM()
-   AVG()
-   ROUND()
-   LIMIT

## Tools

-   PostgreSQL
-   pgAdmin 4
-   SQL

## Project Outcome

This project demonstrates practical SQL skills for data analysis by
transforming raw transactional data into meaningful business insights.

------------------------------------------------------------------------

### Author

**Md. Raiful Islam Ratul**

Aspiring Data Analyst \| SQL \| PostgreSQL \| Power BI
