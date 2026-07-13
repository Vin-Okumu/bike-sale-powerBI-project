## Dataset Overview

Item    Description
Dataset Name    Quarter One Bike Sales Report
Source  Internal Sales System
Format  Microsoft Excel(.xlsx)
Reporting Period    Quarter 1
Number of Rows  245
Number of Columns   21
Date Audited    July 2026
Analyst Vincent Okumu

### Dataset Description

The dataset contains transactional sales records for Star Bike (fictional) Bicycle Company during Quarter One. Each record represents an individual customer order and includes customer information, product details, payment method, sales amount, and order status.

## Dataset Inventory

Every variable documented

Column  Description Expected Data Type Business Purpose
Product ID  Unique product identifier   Number Primary key
Product category Raw    identifier of product category  Text Product descriptor
Product category    Refined identifier of product category  Text    Operations
Product Subcategory Identifier of product subcategory   Text    OPerations
Product Name    Product identifier  Text    Product descriptor
Order Date  Date of customer order  Date    Trend analysis
Month   Month of customer order Date    Trend analysis
Year    Year of product order   Date    Trend analysis
Wholesale Price Wholesale price of product  Currency Revenue calculation
Retail Price    Retail price of product Currency Revenue calculation
Order Quantity  Units sold for the order    Number    Sales
Total (Before Tax)  Revenue amount  Currency Revenue
Tax Due Tax payable for order   Currency Tax calculation
Order Total Total revenue amount    Currency Gross revenue
Payment Method  Type of preferred payment   Text    Customer behavior
Order Status    Order completion    Text    Operations
Order ID    Unique order identifier Number    Foreign Key
Customer ID Unique customer identifier  Number  Foreign key
Product Description Product description Text    Operations
Product Size    Product size    Text    Operations
Product Weight  Product weight  Number    Operations

## Data Profiling

Here, we are essentially examining each variable to answer the question as to whether the variables are stored in their correct data types

Variable    Current Type    Expected Type   Action
Product ID  General Text    Convert
Product Category Raw    General Text    Convert
Product Category    General Text    Convert
Product Subcategory General Text    Convert
Product Name    General Text    Convert
Order Date  General Date    Convert
Month   General Date    Convert
Year    General Date    Convert
Wholesale Price General Currency    Convert
Retail Price    General Currency    Convert
Order Quantity  General Number  Convert
Total (Before Tax)  General Currency    Convert
Tax Due General Currency    Convert
Order Total General Currency    Convert
Payment Method  General Text    Convert
Order Status    General Text    Convert
Order ID    General Number  Convert
Customer ID General Number Convert
Product Description General Text    Convert
Product SIze    General Text    Convert
Product Weight  General Number  Convert

## Missing Values

Variable    Missing Count   Missing %   Action



## Uniqueness Test

For identifiers, Order ID should be unique while Product ID and Customer ID should repeat.

## Invalid values

Negative quantities, negative prices, negative revenue, blank payment methods etc., should be flagged for cleaning.

## Outlier detection




