Sales Data Analysis using SQLite & Python
This project demonstrates how to perform basic sales data analysis using SQLite and Python within a Jupyter Notebook. It includes database creation, data insertion, SQL queries for insights, and data visualization using matplotlib.

🧰 Tools Used
Python

SQLite (sqlite3)

Jupyter Notebook

pandas

matplotlib

📁 Project Overview
The project simulates a basic retail sales environment by:

Creating a local SQLite database

Storing sample sales data

Running SQL queries to extract insights such as:

Total revenue per product

Total quantity sold

Average price per product

Visualizing these insights using bar charts

✅ Steps Performed
1. Library Imports
The project starts by importing the necessary libraries for database handling, data manipulation, and visualization.

2. Database Creation
A new SQLite database file (sales_data.db) is created and a connection is established using sqlite3.

3. Table Setup
A table named sales is created with the following fields:

id (Primary Key)

product (Product name)

quantity (Units sold)

price (Price per unit)

4. Data Insertion
A sample dataset containing multiple entries for products like Apple, Banana, Orange, and Grapes is inserted into the database.

5. Query: Total Quantity & Revenue
An SQL query is executed to calculate:

Total quantity sold (SUM(quantity))

Total revenue (SUM(quantity * price))
Grouped by product.

6. Visualization: Revenue by Product
A bar chart is created to visualize the total revenue for each product.

7. Query: Total Quantity Sold
A second SQL query calculates the total quantity sold per product, which is also visualized using a bar chart.

8. Query: Average Price
A third SQL query calculates the average price of each product using AVG(price) and displays the results.

📊 Output
Sales Summary Table: Product-wise total quantity and revenue

Bar Chart: Revenue by product

Total Quantity Chart: Visual representation of product sales volume

Average Price Table: Mean price of each product

📌 Key Learnings
How to integrate SQLite with Python

Writing and executing SQL queries inside Jupyter

Using pandas for data handling

Basic data visualization with matplotlib
