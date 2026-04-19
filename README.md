# Retail Sales SQL Analytics

## Overview

This project analyzes a retail sales dataset using SQL to extract meaningful business insights. It focuses on revenue trends, customer behavior, and store performance.

---

## Objectives

* Analyze overall business performance
* Handle missing and inconsistent data
* Perform segmentation of customers and stores
* Generate insights using advanced SQL techniques

---

## Dataset

The dataset includes:

* Customers
* Stores
* Products
* Sales transactions

Key fields:

* `amount`, `quantity`, `discount`, `sale_date`

---

## Key SQL Concepts Used

* Aggregations (SUM, AVG, COUNT)
* Joins (INNER, LEFT)
* Window Functions (RANK, LAG, LEAD, NTILE)
* CASE WHEN (Segmentation)
* Data Cleaning (NVL, COALESCE)
* Filtering (WHERE, HAVING)

---

## Key Analysis Performed

* Revenue analysis by store, category, and customer
* Identification of high-value customers
* Customer segmentation (High / Medium / Low spenders)
* Store performance comparison
* Time-based sales trends (daily, monthly)
* Running totals and growth analysis

---

## Key Insights

* A small segment of customers contributes a major share of revenue
* Certain stores generate higher transactions but lower average order value
* Product categories show uneven revenue distribution
* Discounts significantly impact net revenue

---

## Project Structure

```
retail-sales-sql-analytics/
│
├── datasets/
├── sql_queries.sql
├── insights.md
└── README.md
```

---

## How to Run

1. Create tables using the provided schema
2. Insert data using SQL scripts
3. Run queries from `sql_queries.sql`
4. Analyze outputs for insights

---

## Tools Used

* Oracle SQL / SQL Developer



