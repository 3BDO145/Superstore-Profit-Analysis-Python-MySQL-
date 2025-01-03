Overview :

This project involves analyzing sales data from a Superstore dataset, which includes detailed information on orders, products, and customers. The analysis focuses on key business metrics such as sales, profit, discount, and the performance of various products, categories, regions, and customers. The goal is to gain insights into sales patterns and profitability, helping to make data-driven business decisions.

Dataset

The dataset contains 9994 entries and 21 columns, capturing the following attributes:

    Order Information: Order ID, Order Date, Ship Date, Ship Mode
    Customer Information: Customer ID, Customer Name, Segment, Country, City, Postal Code
    Product Information: Product ID, Category, Sub-Category, Product Name
    Sales Metrics: Sales, Quantity, Discount, Profit

Data Cleaning & Transformation

Before performing the analysis, the following preprocessing steps were applied to the dataset:

    Removed duplicates: There were no duplicates found in the data.
    Changed date formats: The "Order Date" and "Ship Date" columns were converted to datetime format for easier manipulation.
    Handled missing data: The dataset has no null values, ensuring completeness.
Created new columns:

	Profit Margin: Calculated as Profit divided by Sales.
	Shipping Duration: The difference between the "Ship Date" and "Order Date".

Key Insights:
1. Sales and Profit by Category:
Technology leads in total sales with $836,154.03 and $145,454.95 in total profit.
Furniture and Office Supplies follow with lower total profit margins, highlighting the profitability of certain product types.
2. Sales and Profit by Region:
The West region leads in both sales and profit with $725,457.82 in sales and $108,418.45 in profit.
South has the lowest sales, but its profit margin is relatively high.
3. Top 5 Profitable Products:
Products like Canon imageCLASS 2200 Advanced Copier and Fellowes PB500 Electric Punch are the most profitable, contributing significantly to the overall profit.
4. Average Discount by Category:
Furniture had the highest average discount rate at 0.17, while Technology had the lowest at 0.13.
5. Sales Trends by Month:
2017-12 had the highest sales at $118,447.83, showcasing a peak in year-end sales.
6. Top 10 Customers by Sales:
Customers like Sean Miller and Tamara Chand generated the most sales, with $25,043.05 and $19,052.22 respectively.
