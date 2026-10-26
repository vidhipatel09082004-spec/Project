# Superstore Sales Analysis

## Project Overview

This project analyzes Superstore sales data to understand sales performance, profitability, product categories, customer demand, and regional performance.

The project uses Excel, MySQL, and Python to convert raw sales data into meaningful business insights and recommendations.

## Business Objectives

- Analyze total sales and profit.
- Identify top-performing product categories.
- Analyze city-wise sales performance.
- Identify high-performing products.
- Understand monthly sales trends.
- Analyze payment methods.
- Calculate key performance indicators (KPIs).
- Provide data-driven business recommendations.

## Dataset

The project uses a Superstore sales dataset containing the following columns:

- `order_id` — Order identifier
- `order_date` — Date of the order
- `city` — City of the order
- `category` — Product category
- `product` — Product name
- `quantity` — Quantity sold
- `sales` — Sales amount
- `profit` — Profit earned
- `payment_mode` — Payment method

## Tools & Technologies

- Microsoft Excel
- MySQL
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- GitHub

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Orders (Records) | 10 |
| Total Units Sold | 37 |
| Total Sales | ₹45,500.00 |
| Total Profit | ₹6,150.00 |
| Average Sales per Record | ₹4,550.00 |
| Profit Margin | 13.52% |

*Note: The results above are based on the current 10 records in the SQL table.*

## SQL Analysis

SQL was used to calculate total sales, total profit, total quantity sold, and average sales.

The analysis includes:

- Total sales and profit
- Category-wise sales and profit
- City-wise sales performance
- Top-performing products
- Monthly sales trends
- Payment mode analysis
- High-profit transactions
- Product ranking using window functions

SQL concepts used include `SELECT`, `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, aggregate functions, subqueries, CTEs, and window functions.

## Python Analysis

Python and Pandas are used to analyze and summarize sales data.

The analysis includes:

- Loading the dataset
- Checking missing values and duplicates
- Calculating sales and profit KPIs
- Grouping sales by category and city
- Identifying top products
- Analyzing monthly sales
- Creating charts using Matplotlib

## Key Business Insights

### 1. Overall Performance

The dataset contains 10 order records, with total sales of ₹45,500 and total profit of ₹6,150.

### 2. Product Demand

A total of 37 units were sold. Quantity analysis can help identify products with higher demand.

### 3. Profitability

The overall profit margin is approximately 13.52%, based on total profit divided by total sales.

### 4. Category Performance

Category-wise sales and profit analysis can identify the strongest and weakest product categories.

### 5. Regional Performance

City-wise sales analysis can highlight high-performing cities and opportunities for regional growth.

### 6. Payment Methods

Payment mode analysis can help understand which payment methods are most frequently used.

*Category, city, product, monthly, and payment-specific findings require the corresponding query results.*

## Business Recommendations

- Focus on categories that generate higher sales and profit.
- Monitor profit margins before offering discounts.
- Maintain sufficient stock of high-demand products.
- Use monthly sales trends to plan promotions.
- Improve marketing in cities with growth potential.
- Review payment mode preferences to improve the checkout experience.
- Continue monitoring KPIs to measure business performance.

## Project Structure

```text
Superstore-Sales-Analysis/
│
├── Data/
│   └── Superstore_Sales_Data.csv
│
├── SQL/
│   └── sales_analysis.sql
│
├── Python/
│   └── sales_analysis.ipynb
│
├── Excel/
│   └── Superstore_Sales_Analysis.xlsx
│
└── README.md
```

## Conclusion

This project demonstrates how Excel, MySQL, and Python can be used together to analyze Superstore sales data.

The analysis provides an overview of sales, profit, quantity sold, and profit margin. Further category-wise, product-wise, city-wise, and monthly analysis can help identify business opportunities and support better decision-making.

## Author

**Superstore Sales Analysis**

Tools: Excel | MySQL | Python | Pandas | NumPy | Matplotlib
