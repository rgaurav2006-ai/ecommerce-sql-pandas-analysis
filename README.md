# 🛒 E-Commerce Sales Analysis (SQL + Pandas)

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-purple)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Project Overview

This project performs an **end-to-end exploratory analysis of an e-commerce sales dataset** using **SQL and Python (Pandas)**.

The goal of this project is to simulate the work of a **data analyst in a real business environment**, where raw transaction data is analyzed to uncover insights related to **revenue, customer behavior, product performance, and operational trends**.

The analysis demonstrates how **SQL and Python complement each other** in modern data analytics workflows.

---

# 🎯 Business Questions Answered

This project answers several key business questions:

* What is the **total revenue generated**?
* How many **unique customers** placed orders?
* Which products are the **top sellers**?
* Which **product categories generate the most revenue**?
* Who are the **highest spending customers**?
* What payment methods are customers using the most?
* What does the **monthly revenue trend** look like?
* How many orders were **cancelled**?
* What is the **Average Order Value (AOV)**?

These insights are commonly used by businesses to improve **marketing strategies, inventory planning, and customer experience**.

---

# 🛠️ Tools & Technologies

| Tool                 | Purpose                               |
| -------------------- | ------------------------------------- |
| **SQL (MySQL)**      | Data querying and aggregation         |
| **Python**           | Data analysis                         |
| **Pandas**           | Data manipulation                     |
| **Jupyter Notebook** | Analysis environment                  |
| **Git & GitHub**     | Version control and project portfolio |

---

# 📂 Dataset

The dataset represents **transaction-level sales data from an e-commerce platform**.

File used:

`ecommerce_sales_dataset.csv`

### Dataset Features

| Column           | Description                   |
| ---------------- | ----------------------------- |
| Order_ID         | Unique order identifier       |
| Customer_ID      | Unique customer identifier    |
| Product_Name     | Name of the purchased product |
| Product_Category | Product category              |
| Quantity         | Number of units purchased     |
| Total_Price      | Total price of the order      |
| Order_Date       | Date of the order             |
| Payment_Type     | Payment method used           |
| Order_Status     | Status of the order           |

---

# 📊 SQL Analysis

SQL was used to perform **core data aggregation and business metric calculations**.

### SQL Insights Generated

1. **Total Records** – Number of transactions in the dataset
2. **Total Revenue** – Overall revenue generated
3. **Unique Customers** – Number of distinct customers
4. **Top Selling Products** – Highest quantity sold products
5. **Revenue by Category** – Revenue contribution by product category
6. **Top Spending Customers** – Customers with the highest spending
7. **Orders by Payment Type** – Distribution of payment methods
8. **Monthly Revenue Trend** – Revenue growth across months
9. **Cancelled Orders** – Total cancelled transactions
10. **Average Order Value (AOV)** – Average revenue per order

SQL queries are available in:

`sql_queries.sql`

---

# 🐼 Pandas Analysis

The same business questions were analyzed using **Python and Pandas** to demonstrate a complete analytical workflow.

### Key Pandas Operations

* Data loading using `pd.read_csv()`
* Dataset exploration using:

  * `head()`
  * `info()`
  * `describe()`
* Aggregations using:

  * `sum()`
  * `mean()`
  * `nunique()`
* Grouping using `groupby()`
* Sorting insights using `sort_values()`
* Datetime analysis using `dt.month`
* Filtering cancelled orders
* Revenue analysis and customer insights

All Python analysis is contained in:

`analysis.ipynb`

---

# 📁 Project Structure

```
ecommerce-sql-pandas-project
│
├── data
│   └── ecommerce_sales_dataset.csv
│
├── sql_queries.sql
├── analysis.ipynb
└── README.md
```

---

# 📈 Key Insights

* A small group of customers contributes significantly to total revenue.
* Certain product categories dominate overall sales.
* Monthly revenue trends reveal potential seasonal patterns.
* Payment methods highlight customer preferences.
* Cancelled orders provide operational insights for improvement.

---

# 🚀 How to Run This Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/ecommerce-sql-pandas-project.git
```

### 2️⃣ Navigate to the Project Directory

```
cd ecommerce-sql-pandas-project
```

### 3️⃣ Open the Jupyter Notebook

Run the following notebook:

```
analysis.ipynb
```

Execute all cells to reproduce the analysis.

---

# 📌 Future Improvements

Potential improvements for this project include:

* Adding **data visualizations using Matplotlib / Seaborn**
* Creating an **interactive dashboard**
* Applying **advanced SQL techniques**

  * Window functions
  * Ranking functions
  * Customer segmentation
Performing predictive analysis on sales trends



👨‍💻 Author

Gaurav Rai

Data Analyst building real-world projects using:

* SQL
* Python
* Pandas
* Data Visualization

⭐ If you found this project interesting, consider **starring the repository**.
