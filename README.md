# Online Retail Exploratory Data Analysis with Python

## Overview
This project demonstrates exploratory data analysis (EDA) on transactional data from an online retail company. The analysis helps uncover trends, customer behaviors, and popular products, driving strategic business decisions to optimize operations and enhance customer satisfaction.

## Case Study
The dataset contains customer purchase data from an online retail store during 2010-2011. It includes information such as:
- Products purchased
- Quantities sold
- Prices
- Transaction timestamps
- Customer demographics

By conducting EDA, this project identifies patterns, outliers, and correlations in the data to provide actionable insights, including:
- The busiest sales months
- Best-selling products
- Most valuable customers
- Anomalous transactions

## Objectives
1. Analyze sales trends over time.
2. Identify top-selling products and high-sales countries.
3. Detect outliers and anomalies in transactions.
4. Provide data-driven recommendations to improve business performance.

---

## Dataset
The dataset used is the **Online Retail Dataset**, which contains:
- **InvoiceNo**: Invoice number of the transaction.
- **StockCode**: Unique product code.
- **Description**: Product description.
- **Quantity**: Number of items sold.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique customer identifier.
- **Country**: Country where the transaction occurred.

Download the dataset [here](https://archive.ics.uci.edu/ml/datasets/Online+Retail) or use the included dataset in the provided Jupyter Notebook.

---

## Project Structure
1. Data Loading
Load the dataset into a Pandas DataFrame.
Display the first few rows to understand the structure and features.
2. Data Cleaning
Handle missing values, particularly in columns like CustomerID.
Remove duplicate or unnecessary columns.
3. Descriptive Analysis
Compute statistics such as mean, median, and standard deviation.
Analyze data distributions for key features like Quantity and UnitPrice.
4. Data Visualization
Visualize sales trends over time (months and days of the week).
Identify the top-selling products using bar plots.
Analyze sales by country to determine geographical hotspots.
5. Outlier Detection
Identify anomalies in UnitPrice and Quantity that may indicate errors or unusual transactions.
6. Insights and Recommendations
Based on the analysis:

Busiest Months: Identify peak sales months for targeted marketing.
Best-Selling Products: Optimize inventory for high-demand items.
High-Value Customers: Target repeat buyers with loyalty programs.
International Expansion: Focus on countries with high sales for growth.
Outlier Handling: Investigate and resolve anomalies in transactions.
