📊 Sales Summary Using SQLite & Python
🎯 Objective
To extract, analyze, and visualize sales data using SQL inside Python (Jupyter Notebook).
This project demonstrates how SQL queries can be integrated with Python for data analysis and visualization.
🛠 Tools & Technologies Used
Python
SQLite (sqlite3)
Pandas
Matplotlib
Jupyter Notebook
📂 Project Workflow
1️⃣ Database Creation
Created a SQLite database
Designed a sales table with required columns (Product, Quantity, Price, etc.)
2️⃣ Data Insertion
Inserted sample sales records into the table
3️⃣ SQL Analysis
Used SQL GROUP BY query to:
Calculate total sales
Calculate total revenue per product
Example Query:
SQL
Copy code
SELECT product, SUM(quantity) AS total_quantity,
       SUM(quantity * price) AS total_revenue
FROM sales
GROUP BY product;
4️⃣ Data Processing with Pandas
Loaded SQL query result into a Pandas DataFrame
Displayed summary table
5️⃣ Data Visualization
Created a revenue bar chart using Matplotlib
📈 Output
✔ Sales Summary Table
✔ Revenue Bar Chart Visualization
🎓 Learning Outcomes
Understood how to connect SQLite database with Python
Executed SQL queries within Python environment
Converted SQL output into Pandas DataFrame
Visualized revenue insights using Matplotlib
Improved practical data analysis workflow skills
🚀 Skills Demonstrated
SQL Aggregation (GROUP BY, SUM)
Database handling in Python
Data cleaning & transformation
Data visualization
Analytical thinking
