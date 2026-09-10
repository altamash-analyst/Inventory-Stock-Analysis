# Inventory & Stock Analysis Dashboard

## Business Intelligence & Inventory Analytics using Power BI

**Altamash Nizamuddin**  
**Data Analyst | Altamash-Analyst**

GitHub: https://github.com/altamash-analyst  
Email: altamash9876@gmail.com

---

## Project Overview

Inventory & Stock Analysis Dashboard is a Business Intelligence and Data Analytics project developed using Microsoft Power BI, Excel, Power Query and DAX.

The project focuses on analyzing inventory health, stock availability, inventory value, product movement, sales performance, replenishment requirements, category performance, brand performance and supplier risk.

The dashboard transforms structured business data into interactive visualizations and KPIs that can support inventory monitoring, stock-risk identification and replenishment decision-making.

This project is part of the Altamash-Analyst Data Analytics portfolio.

---

## Business Problem

Effective inventory management requires maintaining the right balance between product availability and excess inventory.

Low inventory levels can create stock shortages and potential lost sales, while excessive inventory can result in capital being tied up in stock and increased inventory-management requirements.

The purpose of this project is to provide a centralized analytical view of inventory and identify products and categories that require management attention.

---

## Business Objectives

The main objectives of this project are:

1. Monitor overall inventory health.
2. Identify healthy, low-stock, critical and overstocked products.
3. Identify products requiring replenishment.
4. Analyze reorder requirements.
5. Measure total inventory value.
6. Analyze product-level inventory performance.
7. Identify fast-moving and slow-moving products.
8. Analyze inventory turnover and days of inventory.
9. Compare category performance.
10. Analyze brand-level performance.
11. Analyze supplier replenishment requirements.
12. Support data-driven inventory management decisions.

---

## Key Business Questions

The dashboard is designed to answer the following questions:

- How many products are currently being monitored?
- How many stock units are available?
- What is the total inventory value?
- What percentage of products have healthy inventory?
- Which products are low-stock or critical?
- Which products require replenishment?
- How many units need to be reordered?
- Which products are overstocked?
- Which categories have the highest inventory value?
- Which products are fast-moving?
- Which products are slow-moving?
- What is the overall inventory turnover?
- Which categories have stronger inventory turnover?
- Which brands require replenishment?
- Which suppliers have higher replenishment requirements?

---

## Project Snapshot

| Metric | Value |
|---|---:|
| Total Products | 100 |
| Total Stock Units | 10,047 |
| Inventory Value | 117.40M |
| Inventory Health | 61% |
| Products at Risk | 28 |
| Critical Products | 10 |
| Low Stock Products | 18 |
| Overstocked Products | 11 |
| Reorder Required | 28 |
| Reorder Units | 665 |
| Units Sold | 44,386 |
| Sales Revenue | 720.45M |
| Inventory Turnover | 4.75 |
| Fast-Moving Products | 42 |
| Slow-Moving Products | 58 |

---

## Dashboard Screenshots

### Dashboard 1 - Inventory Overview

![Dashboard 1](PNG/Dashboard%201.PNG)

---

### Dashboard 2 - Stock Health & Replenishment

![Dashboard 2](PNG/Dashboard%202.PNG)

---

### Dashboard 3 - Product Inventory Analysis

![Dashboard 3](PNG/Dashboard%203.PNG)

---

### Dashboard 4 - Category & Brand Performance

![Dashboard 4](PNG/Dashboard%204.PNG)

---

### Dashboard 5 - Replenishment & Management

![Dashboard 5](PNG/Dashboard%205.PNG)

---

## Dashboard PDF

A complete PDF export of the Power BI dashboard is available in the Dashboard folder.

File:

`Dashboard/Inventory_Stock_Analysis.pdf`

---

## Dataset Overview

The project uses a structured Excel workbook containing multiple business entities.

The underlying data source is confidential and is not disclosed in this documentation.

### Workbook Sheets

| Sheet | Description |
|---|---|
| Products | Product master information |
| Suppliers | Supplier information |
| Inventory | Current stock and inventory information |
| Sales | Historical sales transactions |
| Targets | Product-level target information |
| Project_Info | Project information |

### Dataset Size

- 100 Products
- 25 Suppliers
- 100 Inventory Records
- 15,000 Sales Transactions
- 100 Target Records

### Data Period

January 2025 - August 2026

---

## Data Dictionary

### Products

| Field | Description |
|---|---|
| Product_ID | Unique product identifier |
| Product_Name | Product name |
| Category | Main product category |
| Sub_Category | Product sub-category |
| Brand | Product brand |
| Supplier_ID | Associated supplier identifier |
| Cost_Price | Product cost price |
| Selling_Price | Product selling price |

### Suppliers

| Field | Description |
|---|---|
| Supplier_ID | Unique supplier identifier |
| Supplier_Name | Supplier name |
| Supplier_Type | Supplier type |
| City | Supplier city |
| State | Supplier state |
| Lead_Time_Days | Supplier lead time |
| Supplier_Rating | Supplier rating |

### Inventory

| Field | Description |
|---|---|
| Product_ID | Product identifier |
| Current_Stock | Current available stock |
| Reorder_Level | Inventory level used for replenishment monitoring |
| Safety_Stock | Minimum buffer stock |
| Max_Stock_Level | Maximum desired stock level |
| Warehouse | Warehouse information |
| Last_Restock_Date | Last restocking date |

### Sales

| Field | Description |
|---|---|
| Sale_ID | Unique sales transaction identifier |
| Sale_Date | Date of sale |
| Product_ID | Product identifier |
| Quantity_Sold | Quantity sold |
| Unit_Price | Selling price per unit |
| Discount | Applied discount |
| Sales_Channel | Sales channel |
| Region | Sales region |

### Targets

| Field | Description |
|---|---|
| Product_ID | Product identifier |
| Monthly_Target_Units | Monthly target units |
| Target_Stock_Value | Target inventory value |
| Target_Turnover | Target inventory turnover |

---

## Data Preparation

Data preparation was performed using Microsoft Excel and Power Query.

The preparation process involved structuring the source data for analysis and preparing the tables for use within the Power BI data model.

The workflow included:

- Reviewing source tables
- Preparing product information
- Preparing supplier information
- Preparing inventory information
- Preparing sales transaction data
- Preparing target information
- Maintaining consistent identifiers
- Preparing date fields
- Preparing numerical fields
- Structuring data for Power BI analysis

---

## Data Model

The project combines product, inventory, sales, supplier and target information.

The primary analytical relationships are based around product and supplier identifiers.

### Main entities

- Products
- Inventory
- Sales
- Suppliers
- Targets

The model allows inventory performance to be analyzed together with product, sales and supplier information.

---

## Power BI and DAX

Microsoft Power BI was used to build the interactive dashboard and analytical model.

DAX was used for KPI and analytical calculations.

The dashboard includes measures and calculations related to:

- Total Products
- Total Stock Units
- Inventory Value
- Units Sold
- Sales Revenue
- Inventory Turnover
- Days of Inventory
- Inventory Health
- Reorder Requirements
- Reorder Units
- Critical Products
- Low Stock Products
- Overstocked Products
- Fast-Moving Products
- Slow-Moving Products

---

## Inventory Health Analysis

The dashboard classifies products into four inventory-health categories.

| Stock Status | Products | Percentage |
|---|---:|---:|
| Healthy | 61 | 61% |
| Low Stock | 18 | 18% |
| Overstock | 11 | 11% |
| Critical | 10 | 10% |
| Total | 100 | 100% |

The analysis shows that 61% of products are classified as healthy, while the remaining products require monitoring because they are low-stock, critical or overstocked.

---

## Category Analysis

The project analyzes five major product categories:

- Home & Kitchen
- Beauty
- Electronics
- Fashion
- Sports

### Inventory by Category

| Category | Stock Units | Inventory Value | Inventory Turnover |
|---|---:|---:|---:|
| Home & Kitchen | 2,868 | 30.72M | 18.15 |
| Beauty | 2,175 | 29.01M | 19.22 |
| Fashion | 2,096 | 23.39M | 23.83 |
| Electronics | 1,738 | 24.05M | 23.18 |
| Sports | 1,170 | 10.23M | 54.48 |

Home & Kitchen has the highest inventory value, while Sports has the highest reported inventory turnover.

---

## Product Inventory Analysis

The product analysis page evaluates inventory performance at the individual product level.

The analysis includes:

- Inventory value
- Units sold
- Sales revenue
- Days of inventory
- Inventory turnover
- Stock coverage
- Product stock status

The dashboard identifies:

- 42 fast-moving products
- 58 slow-moving products

This provides an overview of product movement and inventory efficiency.

---

## Replenishment Analysis

Replenishment analysis identifies products where stock levels require attention.

The dashboard reports:

- 28 products requiring replenishment
- 665 reorder units
- 10 critical products
- 18 low-stock products

The replenishment section also provides product-level information such as current stock, reorder level, safety stock, reorder quantity, stock status, category and brand.

---

## Brand Analysis

The dashboard analyzes brand performance and replenishment requirements.

The brands included in the analysis are:

- Apex
- FitPro
- GlowCare
- HomeCraft
- Nova
- PrimeTech
- StyleHub
- TrendLine
- UrbanX
- Zenith

HomeCraft and Nova have the highest reported number of products requiring replenishment.

---

## Supplier Analysis

Supplier analysis is used to monitor replenishment requirements and supplier-related inventory information.

The dataset contains 25 suppliers.

The dashboard analyzes:

- Supplier name
- Supplier rating
- Lead time
- Reorder requirements
- Reorder units

This analysis provides an additional operational perspective by connecting inventory requirements with suppliers.

---

## Key Business Insights

### Inventory Health

61% of the 100 products are classified as healthy.

### Inventory Risk

28 products are identified as being at risk or requiring action.

### Critical Inventory

10 products are classified as critical.

### Low Stock

18 products are classified as low-stock.

### Overstock

11 products are classified as overstocked.

### Replenishment

28 products require replenishment, with a reported reorder requirement of 665 units.

### Inventory Investment

Home & Kitchen has the highest inventory value at approximately 30.72M.

### Inventory Efficiency

Sports has the highest reported inventory turnover at approximately 54.48.

### Product Movement

The dashboard identifies 42 fast-moving products and 58 slow-moving products.

---

## Business Recommendations

Based on the dashboard analysis, the following actions can be considered:

1. Prioritize critical products for immediate inventory review.
2. Monitor low-stock products regularly.
3. Review replenishment requirements before stock reaches critical levels.
4. Investigate overstocked products to reduce unnecessary inventory investment.
5. Analyze slow-moving products for possible inventory optimization.
6. Monitor high-value categories because they represent significant inventory investment.
7. Use supplier information when planning replenishment.
8. Monitor inventory turnover across categories to identify efficiency differences.
9. Review product-level demand before increasing stock levels.
10. Use the dashboard as a recurring inventory-management monitoring tool.

---

## Project Limitations

- The underlying data source is confidential.
- The analysis is dependent on the supplied dataset.
- Inventory classifications depend on the stock thresholds defined in the project.
- The dashboard represents the available data period.
- Supplier analysis is limited to the supplier attributes available in the dataset.
- The dashboard should be interpreted as an analytical decision-support tool rather than a guarantee of future demand.

---

## Future Improvements

Potential future improvements include:

- Automated data refresh
- Real-time inventory monitoring
- Demand forecasting
- Automated reorder recommendations
- Supplier risk scoring
- ABC inventory classification
- Safety-stock optimization
- Inventory aging analysis
- Lead-time variability analysis
- Regional demand analysis
- Sales-channel analysis
- Automated Power BI alerts
- Predictive inventory analytics

---

## Tools and Technologies

### Data Preparation

- Microsoft Excel
- Power Query

### Business Intelligence

- Microsoft Power BI
- DAX

### Design

- Figma
- GIMP

### AI Assistance

- ChatGPT

ChatGPT was used for project documentation and development assistance.

Python and SQL were not used in this particular project.

---

## Repository Structure

```text
Inventory-Stock-Analysis/
│
├── README.md
│
├── Inventory_Stock_Analysis.pbix
├── Inventory_Stock_Analysis.xlsx
│
├── Background/
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   └── Color_Palette.png
│
├── Dashboard/
│   ├── Inventory_Stock_Analysis.pdf
│   ├── Dashboard_1.png
│   ├── Dashboard_2.png
│   ├── Dashboard_3.png
│   ├── Dashboard_4.png
│   └── Dashboard_5.png
│
└── Documentation/
    └── PROJECT_DOCUMENTATION.md
