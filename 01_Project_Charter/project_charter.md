# Bike Sales Business Intelligence & Performance Analytics Dashboard

## Background

Starter Bike LLC (a fictional company) is a bicycle retailer that sells various types of bicycles to its emerging consumer niche. Having just completed its first quarter of operations for the second year running, the executive wants to utilize recorded transactional sales data, product information, pricing details, quantities sold, order status, and sales dates to design a data-driven sales drive. While operational data is readily available, the management still lacks a centralized reporting solution that can transform this raw information into meaningful business insights.

The company executives believe that an analytical dashboard can help decision-makers spend considerablly less time compiling reports manually, making it a little simpler to identify revenue drivers, evaluate product performance, monitor operational efficiency, and estimate tax obligations. 

Therefore, this project is intended to transform the company's transactional sales data into an interactive Business Intelligence solution using Microsoft Power BI.

## Business Problem

The company generates sales every day but lacks visibility into its overall business performance.

Management cannot easily answer critical operational questions such as:

- How much revenue has been generated?
- Which products contribute the most to revenue?
- Which product categories are the most profitable?
- How much tax liability has the business incurred?
- Which products trigger the highest tax expense?
- How are sales changing over time?
- Which orders are successfully completed versus cancelled?
- Where are operational inefficiencies occurring?

Without these insights, management risks making decisions based on assumptions rather than evidence.

## Business Context

The company operates under the following tax rule:

Any individual sale order whose value exceeds $2,000 attracts a 5% tax, payable by the company to the Internal Revenue Service (IRS). This tax is treated as a business expense and added to the sales. Sales valued at $2,000 or below are exempt from this tax.

## Project Goal

To design and develop an interactive Power BI dashboard that will enable management to monitor sales performance, product performance, operational efficiency, and tax obligations while supporting evidence-based business decision-making.

## Project Objectives

The dashboard will enable management to monitor:

### Sales Performance
- Measure total revenue generated.
- Monitor sales trends over time.
- Evaluate average order value.
- Track order volumes.

### Product Performance
- Identify top-performing products.
- Compare product categories.
- Measure product profitability.
- Analyze product contribution to total revenue.

### Operational Performance
- Monitor order status distribution.
- Identify cancelled orders.
- Evaluate operational efficiency.
- Highlight products associated with higher cancellation levels.

### Tax Analysis
- Calculate tax liability.
- Determine net revenue after tax.
- Measure tax contribution by product and category.

### Executive Reporting

Provide an interactive dashboard allowing executives to filter results by:

- Date
- Product Category
- Order Status

## Scope

This project will include:

- Data cleaning using Power Query
- Data transformation
- Data modeling
- DAX calculations
- Interactive dashboard development
- KPI development
- Executive reporting
- Tax calculations

## Success Criteria

The project will be considered successful if it delivers:

- Interactive Power BI dashboard
- Accurate tax calculations
- Executive KPI page
- Customer analytics page
- Operational dashboard
- Product performance dashboard
- Fully documented GitHub repository
- Reproducible workflow

## Deliverables

- A Clean dataset
- Data dictionary
- Power Query documentation
- Data model
- DAX measures documentation
- Power BI dashboard
- Executive summary
- GitHub repository

## Risks

- Missing values: Mitigated by data ceaning procedures
- Duplicate orders: Mitigated by duplicate detection
- Incorrect data types: Mitigated by data validation
- Inconsistent customer information: Mitigated by standardization
- Tax calculation errors: Mitigated by validation against business rules

## Assumption

1. Dataset represents completed business transactions.
2. Customer IDs uniquely identify customers.
3. Order IDs uniquely identify orders.
4. Product prices are accurate.
5. Tax is calculated using pre-tax order value.

## Business Rule

Sales Tax Rule

If an order value is greater than $2000, then the sales tax is 5%. Otherwise the sales tax is 0%

The tax is imposed on the customer but does not constitute company revenue as it is remitted to the IRS by the company.
