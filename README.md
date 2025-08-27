# E-Commerce-Analysis


# Overview

This project performs data analysis on an e-commerce database using Python, MySQL, Pandas, Matplotlib, and Seaborn.
It provides insights into customer behavior, sales trends, product performance, and seller revenue.

# Features / Analysis Performed

List of unique customer cities and count of customers per state

Orders placed per year and per month

Average products per order by customer city

Percentage of orders paid in installments

Total sales and revenue distribution by product category

Seller revenue ranking

Correlation between product price and purchase count

Moving average of order values per customer

Cumulative sales per month and year-over-year growth

Top 3 customers by spending each year

#Prerequisites

Python 

MySQL with ecommerce database containing:

customers

orders

order_items

products

payments

# Required Python libraries:

pip install pandas matplotlib seaborn mysql-connector-python numpy

Usage

Clone the repository or download the script.

Update MySQL credentials in the Python script:

db = mysql.connector.connect(
    host="localhost",
    username="root",
    password="12345",
    database="ecommerce"
)


# Run the script:

python ecommerce_analysis.py


View output tables and charts in your Python IDE or Jupyter Notebook.

# Visualization

Bar charts: Customers per state, Orders per month, Seller revenue

Seaborn plots: Top customers per year, Monthly order trends

# Notes

Some queries, such as customer retention rate, may need debugging.

The project can be extended for seasonal trends, predictive analytics, or deeper product insights.
