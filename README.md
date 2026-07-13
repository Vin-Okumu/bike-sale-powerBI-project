## Bike Sale Power BI Project

Having completed its first quarter of operations, Star Bike (a fictional bicycle retailer) wants to understand its Q1 sales performance, profitability, customer purchasing behavior, tax liabilities, and operational efficiency in order to improve revenue and optimize sales operations.

However, while operational data is collected, and available, management currently lacks a centralized reporting solution that transforms this raw information into meaningful business insights.

Without an analytical dashboard, decision-makers spend considerable time compiling reports manually, making it difficult to identify revenue drivers, evaluate product performance, monitor operational efficiency, and estimate tax obligations. As the business grows, manual reporting becomes increasingly inefficient and prone to error.

### Project Objective

This project aims to transform the company's transactional sales data into an interactive Business Intelligence solution using Microsoft Power BI.

### Repository Structure

    Bike-Sales-PowerBI-Project/

    │
    ├── 01_project_charter/
    │   └── project_charter.md
    │
    ├── 02_business_requirements/
    │   └── business_requirement_document.pdf
    │
    ├── 03_documentation/
    │   ├── Business Questions.md
    │   ├── Data Cleaning Report.md
    │   ├── Data Dictionary.md
    │   └── Insights.md
    │
    ├── 04_data/
    │   └── data_audit/
    │       ├── data_audit_report.md
    │       ├── data_profile_summary.pdf
    │       └── data_quality_checklist.md
    │  
    │   ├── processed/
    │   └── raw/
    │       └── Quarter-One-Report-Workbook.xlsx
    │
    ├── 05_reports/
    │   ├── Bike Sales Dashboard.pbix
    │   └── 
    │
    ├── 06_power_query/
    │
    ├── 07_dax/
    │   └── Measures.md
    │
    ├── 08_images/
    │
    ├── LICENSE
    │
    └── README.md


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

However, without these insights, management risks making decisions based on assumptions rather than evidence.

## Project Goal

To design and develop an interactive Power BI dashboard that enables management to monitor sales performance, product performance, operational efficiency, and tax obligations while supporting evidence-based business decision-making.

The dashboard is, therefore, intended to enable management to monitor:

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
- Identify taxable transactions.
- Determine net revenue after tax.
- Measure tax contribution by product and category.

### Executive Reporting

Provide an interactive dashboard allowing executives to filter results by:

- Date
- Product Category
- Product
- Order Status