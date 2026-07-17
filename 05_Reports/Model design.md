## Design Philosophy

The model follows a start schema design, which is intended to separate transactional facts from descriptive dimensions. This model halps reduce redundancy, improve query performance and simplifies DAX calculations, considering it aligns with dimensional modeling best practices.

## Fact Table

- FactSales

## Dimension Tables

- DimDate
- DimCustomer
- DimProduct
- DimPaymentMethod
- DimOrderStatus

## Relationship Status

- One-to-many relationships.
- Single-direction filter propagation
- Surrogate keys where appropriate
- Dedicated date dimension for time intelligence

## Data Model Blueprint

### Fact Measures

    Column              |   Fact        |   Reason
    --------------------|---------------|------------------
    Order Quantity      |   Yes         |   Sum
    Retail Price        |   Yes         |   Monetary Value
    Wholesale Price     |   Yes         |   Cost Analysis
    Total (Before Tax)  |   Yes         |   Revenue
    Tax Due             |   Yes         |   Tax
    Order Total         |   Yes         |   Customer payment

These belong to the FactSales table

## Dimensions

Everything descriptive belongs to the dimension

### Product

    Product ID
    Product Name
    Product Category
    Subcategory
    Description
    Size
    Weight

These all belong together, becoming DimProduct

### Customer

Will contain
    Customer ID

This becomes DimCustomer

### Date

Will contain
    Order Date

This becomed DimDate

### Payment

Will contain 
    Payment Method

This becomes DimPaymentMethod

### Order Status

Will contain
    Order Status

This becomes DimOrderStatus


