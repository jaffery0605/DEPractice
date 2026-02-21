## Problem Statement

You are given a dataset containing transactional sales data with the following fields:

* `customerID`
* `orderID`
* `transactionID`
* `date`
* `saleAmount`

The objective is to **identify the top 3 customers based on total sales amount**.

### Requirements

* Aggregate total sales (`saleAmount`) for each `customerID`.
* Rank customers in descending order of total sales.
* Return only the top 3 customers with the highest total sales.
* In case of ties, apply a deterministic rule (for example, secondary sorting by `customerID`).

### Deliverables

The solutions for this problem are available in the repository:

* `sql_solution.txt` – Contains the SQL-based implementation.
* `pyspark_solution.txt` – Contains the PySpark-based implementation.

Refer to the respective files for the complete logic and query implementation.
