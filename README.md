## 🛒 Target E-commerce Sales Analysis (SQL & Python)

Analyzing customer behavior, sales trends, and revenue growth for a Target-like e-commerce company using SQL and Python on 100K+ records.

📌 Table of Contents

<a href="#overview">Overview</a>

<a href="#business-problem">Business Problem</a>

<a href="#dataset">Dataset</a>

<a href="#tools--technologies">Tools & Technologies</a>

<a href="#project-structure">Project Structure</a>

<a href="#sql-analysis--queries-covered">SQL Analysis – Queries Covered</a>

<a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>

<a href="#key-insights">Key Insights</a>

<a href="#how-to-run-this-project">How to Run This Project</a>

<a href="#final-recommendations">Final Recommendations</a>

<a href="#author--contact">Author & Contact</a>

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project performs an end-to-end analysis of a Target-like e-commerce platform using a large transactional dataset (100,000+ records).
The analysis combines SQL for querying and business metrics calculation with Python for data cleaning, exploratory data analysis (EDA), and insights generation.

The goal is to derive actionable insights related to customer behavior, sales performance, growth trends, and retention.

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

E-commerce businesses must understand what sells, when it sells, and who their best customers are.
This project answers key business questions such as:

How are sales and orders trending over time?

Which categories and sellers contribute most to revenue?

What is the customer retention behavior?

How does pricing affect purchase frequency?

Who are the highest-value customers each year?

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

Records: 100,000+ transactions

Domain: E-commerce (Target-style retail)

Key Entities:

Customers

Orders

Products

Sellers

Payments

Order dates & prices

The dataset enables real-world scale SQL analysis similar to industry case studies.

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

SQL

Joins, Subqueries

Aggregations

Window Functions

Time-series analysis

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

Git & GitHub

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>
```
target-ecommerce-analysis/
│
├── README.md
├── .gitignore
│
├── notebooks/
│   └── python + sql Analysis.ipynb
│
├── data/
│   └── ecommerce_dataset.csv
```

<h2><a class="anchor" id="sql-analysis--queries-covered"></a>SQL Analysis – Queries Covered</h2>

The project includes Basic, Intermediate, and Advanced SQL queries, demonstrating strong analytical depth.

🔹 Basic Queries

Listed all unique customer cities

Counted total orders placed in 2017

Calculated total sales per product category

Computed percentage of installment-based payments

Counted customers by state

🔸 Intermediate Queries

Calculated monthly order counts for 2018

Computed average number of products per order by customer city

Calculated revenue contribution (%) by product category

Identified correlation between product price and purchase frequency

Calculated total revenue per seller and ranked sellers by revenue

🔺 Advanced Queries

Calculated moving average of order values per customer using window functions

Computed cumulative monthly sales per year

Calculated year-over-year (YoY) sales growth rate

Measured customer retention rate (repeat purchase within 6 months)

Identified top 3 highest-spending customers per year

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

Removed duplicate and inconsistent records

Handled missing values across customer and order data

Converted date columns into proper datetime format

Standardized numeric fields (prices, payments)

Created derived metrics:

Total revenue

Average order value (AOV)

Customer order frequency

<h2><a class="anchor" id="key-insights"></a>Key Insights</h2>

A small percentage of customers contribute a large share of total revenue

Clear seasonal patterns observed in monthly sales

Certain product categories dominate overall revenue

Repeat customers show significantly higher lifetime value

Seller revenue is highly skewed, with top sellers generating most sales

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

Clone the repository:

git clone https://github.com/Akashusha/target-ecommerce-analysis-python-sql.git


Open Jupyter Notebook:

jupyter notebook


Run:

python + sql Analysis.ipynb

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

Focus retention strategies on high-value repeat customers

Plan inventory and promotions around seasonal demand

Optimize pricing for categories with high revenue contribution

Monitor top sellers closely to reduce dependency risk

Use retention metrics to improve long-term customer value

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

Akash Usha
Data Analyst
📧 Email: akashusha17@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/akash-usha/
