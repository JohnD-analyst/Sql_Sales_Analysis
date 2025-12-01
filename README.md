-- 1. Total Sales Amount
SELECT SUM(Sales_Amount) AS Total_Sales
FROM sales_data;

-- 2. Top 5 Products by Sales
SELECT Product, SUM(Sales_Amount) AS Total_Sales
FROM sales_data
GROUP BY Product
ORDER BY Total_Sales DESC
LIMIT 5;

-- 3. Region With Highest Revenue
SELECT Region, SUM(Sales_Amount) AS Revenue
FROM sales_data
GROUP BY Region
ORDER BY Revenue DESC;

-- 4. Monthly Sales Trend
SELECT DATE_FORMAT(Order_Date, '%Y-%m') AS Month, SUM(Sales_Amount) AS Monthly_Sales
FROM sales_data
GROUP BY Month
ORDER BY Month;

-- 5. Average Quantity Per Product
SELECT Product, AVG(Quantity) AS Avg_Qty
FROM sales_data
GROUP BY Product;

📈 Key Insights
(Fill in after running your SQL queries)
Example: “North Region generated the highest revenue.”
Example: “Product A is the best-performing product.”

🛠 Tools Used
SQL
MySQL Workbench / PostgreSQL / SQL Server (pick yours)
GitHub

✍ Author
JohnD-analyst
