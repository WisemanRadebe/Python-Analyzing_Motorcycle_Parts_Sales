# 🏍️ Analyzing Motorcycle Parts Sales — SQL Project

This project explores motorcycle parts sales data using **SQL**. It was completed as part of a **DataCamp SQL portfolio project** and showcases real-world data querying, aggregation, and business insight skills using a retail dataset.

## 🎯 Objective

The goal of this project is to analyze motorcycle parts sales data to help the company:

- Understand key revenue drivers
- Identify top/worst-selling products and regions
- Spot trends across time, product categories, and customer segments
- Support data-driven sales and marketing strategies

## 🗂️ Dataset Overview

The dataset contains one table: `sales`, with the following structure:

| Column        | Data Type | Description                                                |
|---------------|-----------|------------------------------------------------------------|
| `order_number`| VARCHAR   | Unique ID for each order                                   |
| `date`        | DATE      | Date of the order (from June to August 2021)               |
| `warehouse`   | VARCHAR   | Order origin: North, Central, or West                      |
| `client_type` | VARCHAR   | Either `Retail` or `Wholesale`                             |
| `product_line`| VARCHAR   | Category/type of product                                   |
| `quantity`    | INT       | Number of items ordered                                    |
| `unit_price`  | FLOAT     | Price per unit in USD                                      |
| `total`       | FLOAT     | Total cost of the order                                    |
| `payment`     | VARCHAR   | Payment method (Credit card, Transfer, Cash)               |
| `payment_fee` | FLOAT     | Fee % charged for the payment method                       |

---

## 🔍 Key Questions Answered

- 📦 What are the top-selling motorcycle parts by revenue?
- 🌍 Which regions generate the most sales?
- 💵 What is the total profit by product category?
- 🧾 Which parts are ordered the most?
- 📈 How do monthly sales trend over time?


## 🧠 Sample Insights

- The seems to be **little to no difference** in the revenue generated across the different months.
- Most sales came from **wholesale buyers market**.
- The *engines* are the worst selling part in terms of units but it is the best selling product in terms revenue.
- **Customers in Central and North Region** placed the highest-value orders.



