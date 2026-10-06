# Swynex Sales Analytics – Complete Analytics Case Study

## Project Overview
This project combines my Swynex internship work from Tasks 1–3 into one complete sales analytics case study for Task 4.

The workflow is:

**Raw Data → Data Cleaning → EDA → Dashboard → Business Insights**

## Problem Statement
The goal is to analyze sales transaction data, clean inconsistent records, identify sales trends and business patterns, and present the results through an Excel dashboard.

## Dataset
The dataset contains sales transaction fields such as Order ID, Customer ID, Order Date, Product, Category, Quantity, Unit Price, City, Payment Method, Order Status and Total Sales.

- Total orders analyzed: **300**
- Total sales: **₹11,366,007**
- Dashboard average order value: **₹37,886.69**

## Data Cleaning
The following cleaning tasks were completed:
- Handled blank City values
- Removed duplicate records
- Standardized City names
- Standardized Product names
- Standardized Payment Methods
- Corrected invalid Quantity values
- Corrected Unit Price formatting
- Standardized Order Date format
- Calculated Total Sales using Quantity × Unit Price

## EDA Highlights

### Category Sales
- Electronics: ₹10,303,520
- Wearables: ₹642,387
- Accessories: ₹420,100

### Top Products
- Laptop: ₹5,156,878
- Smartphone: ₹2,744,389
- Tablet: ₹1,313,215

### Order Status
- Cancelled: 103
- Pending: 101
- Completed: 91
- Unknown: 5

### Monthly Trend
December had the highest monthly sales at **₹1,296,007**, while March had the lowest at **₹780,000**.

## Data Quality
The analysis identified:
- 3 unknown quantities
- 6 unknown payment methods
- 2 blank payment methods
- 5 unknown order statuses
- Mixed/invalid dates
- 3 zero-sales orders
- 32 sales outliers using the IQR method

## Key Business Insights
1. Electronics is the main sales category.
2. Laptop is the highest-selling individual product.
3. Cancelled orders are slightly higher than pending and completed orders.
4. Debit Card and Net Banking are the most frequently used payment methods.
5. December is the strongest sales month.
6. Data-quality issues and outliers should be considered when interpreting the results.

## Dashboard
The Excel dashboard summarizes:
- Total Sales
- Total Orders
- Average Order Value
- Category and product performance
- Other sales analysis

## Tools Used
- Microsoft Excel
- Excel formulas
- Pivot tables
- Exploratory Data Analysis
- Data cleaning
- Dashboard creation

## Files
- `Swynex_Sales_Analytics_Final.xlsx`
- `Swynex_Task4_Final_Analytics_Case_Study.pdf`
- `Swynex_Task4_Final_Analytics_Case_Study.docx`
