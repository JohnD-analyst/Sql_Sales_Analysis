📊 Sales Data Analysis (SQL Project)
This project showcases my ability to use SQL for real-world data analysis.
I worked with a sales dataset containing customer purchases, product information, quantities, prices, and order dates.

The goal of this project is to practice:
Data cleaning
SQL querying
Summarizing sales performance
Generating insights for business decision-making

📁 Dataset Description
Table name: sales_data

Column	Description
id	Unique order ID
customer_name	Name of the customer
product	Item purchased
quantity	Number of units bought
price	Price per unit
order_date	Date of the transaction

🛠️ Tools Used
MySQL Workbench
SQL Queries
CSV Data File

🧠 Key SQL Tasks Performed
✔ Total revenue
✔ Total quantity sold
✔ Top-selling products
✔ Top customers
✔ Monthly sales trends (%Y-%m for grouping by month)
✔ Revenue by product
✔ Revenue by customer
✔ Daily revenue trends

These queries demonstrate practical analysis that businesses rely on for decision-making.

📌 Sample SQL Query (Monthly Trend)
SELECT
    DATE_FORMAT(order_date, '%Y-%m') AS month,
    SUM(quantity * price) AS total_revenue
FROM sales_data
GROUP BY month
ORDER BY month;

🧾 Conclusion
This project demonstrates my growing skills in:
Data analysis using SQL
Structuring datasets
Extracting meaningful business insights
Presenting findings professionally
More SQL projects coming soon as I continue building my data analyst portfolio.

✍ Author
JohnD-analyst
