Inventory & Stock Analysis Dashboard

Business Intelligence & Inventory Analytics using Power BI

Altamash-Analyst | Altamash Nizamuddin

Power BI (image)
Excel (image)
DAX (image)
Status (image)

Project Overview

Inventory & Stock Analysis Dashboard is a Business Intelligence and Data Analytics project developed using Microsoft Power BI, Excel, Power Query and DAX.

The project analyzes inventory health, stock availability, product movement, inventory value, sales performance, replenishment requirements and supplier risk.

The dashboard transforms structured inventory and sales data into interactive business insights that can help decision-makers identify stock risks, monitor inventory efficiency and prioritize replenishment actions.

This project is part of the Altamash-Analyst data analytics portfolio.

Business Problem

Effective inventory management requires maintaining a balance between sufficient stock availability and excessive inventory.

Insufficient stock can result in:

Stock shortages

Lost sales opportunities

Customer dissatisfaction

Emergency replenishment

Excess inventory can result in:

Capital being tied up in stock

Higher storage requirements

Slow-moving inventory

Reduced inventory efficiency

The objective of this project is therefore to provide a centralized analytical view of inventory health and identify products requiring management attention.

Business Objectives

The project focuses on the following objectives:

Monitor overall inventory health.

Identify healthy, low-stock, critical and overstocked products.

Identify products requiring replenishment.

Quantify reorder requirements.

Analyze inventory value across categories.

Analyze product sales movement.

Identify fast-moving and slow-moving products.

Measure inventory turnover.

Analyze category and brand performance.

Evaluate supplier replenishment risk.

Monitor inventory coverage and stock efficiency.

Support data-driven inventory management decisions.

Key Business Questions

The dashboard is designed to answer questions such as:

How much inventory does the business currently hold?

What is the total inventory value?

How many products are in a healthy stock position?

Which products are critically low?

Which products require replenishment?

How many units need to be reordered?

Which products are overstocked?

Which categories hold the largest inventory investment?

Which products are moving quickly?

Which products are moving slowly?

Which categories have the highest inventory turnover?

Which brands have the greatest replenishment requirements?

Which suppliers are associated with higher replenishment activity?

How much inventory coverage is available?

Project Snapshot

MetricValue



Total Products

100

Total Stock Units

10,047

Inventory Value

117.40M

Inventory Health

61%

Products at Risk

28

Critical Products

10

Low Stock Products

18

Overstocked Products

11

Reorder Required

28

Reorder Units

665

Units Sold

44,386

Sales Revenue

720.45M

Inventory Turnover

4.75

Fast-Moving Products

42

Slow-Moving Products

58

Dataset Overview

The project uses a structured Excel workbook containing multiple business entities.

The data source is confidential and is therefore not disclosed in this documentation.

Workbook Structure

SheetPurpose



Products

Product master information

Suppliers

Supplier information and performance attributes

Inventory

Current inventory and stock-control information

Sales

Historical sales transactions

Targets

Product-level targets

Project_Info

Project metadata

Dataset Size

100 Products

25 Suppliers

100 Inventory Records

15,000 Sales Transactions

100 Target Records

Data Period

January 2025 – August 2026

Data Dictionary

Products

FieldDescription



Product_ID

Unique product identifier

Product_Name

Product name

Category

Main product category

Sub_Category

Product sub-category

Brand

Product brand

Supplier_ID

Associated supplier identifier

Cost_Price

Product cost price

Selling_Price

Product selling price

Suppliers

FieldDescription



Supplier_ID

Unique supplier identifier

Supplier_Name

Supplier name

Supplier_Type

Type of supplier

City

Supplier city

State

Supplier state

Lead_Time_Days

Supplier lead time

Supplier_Rating

Supplier rating

Inventory

FieldDescription



Product_ID

Product identifier

Current_Stock

Current available stock

Reorder_Level

Stock level at which replenishment is required

Safety_Stock

Minimum buffer stock

Max_Stock_Level

Maximum desired stock level

Warehouse

Inventory warehouse/distribution center

Last_Restock_Date

Most recent restocking date

Sales

FieldDescription



Sale_ID

Unique sales transaction identifier

Sale_Date

Date of sale

Product_ID

Product identifier

Quantity_Sold

Quantity sold

Unit_Price

Selling price per unit

Discount

Applied discount

Sales_Channel

Sales channel

Region

Sales region

Targets

FieldDescription



Product_ID

Product identifier

Monthly_Target_Units

Monthly unit target

Target_Stock_Value

Target inventory value

Target_Turnover

Target inventory turnover

Data Preparation

Data preparation was performed using Microsoft Excel and Power Query.

The preparation process focused on creating structured and analysis-ready datasets for Power BI.

Main preparation activities

Reviewing source tables

Checking column structures

Preparing product master data

Preparing supplier data

Preparing inventory data

Preparing sales transaction data

Preparing target information

Maintaining consistent Product IDs

Preparing date fields

Structuring numerical fields for analysis

Preparing data for relationships in Power BI

Data Model

The project combines multiple business tables around the Product_ID and Supplier_ID relationships.

Core analytical entities

Products

↓ Product_ID

Inventory

↓ Product_ID

Sales

↓ Product_ID

Targets

Products

↓ Supplier_ID

Suppliers

This model allows inventory, sales, target and supplier information to be analyzed together.

DAX & KPI Layer

DAX was used to create analytical measures and KPIs for the Power BI dashboard.

The dashboard focuses on measures related to:

Total Products

Total Stock Units

Inventory Value

Units Sold

Sales Revenue

Inventory Turnover

Days of Inventory

Inventory Health

Reorder Required

Reorder Units

Critical Products

Low Stock Products

Overstocked Products

Fast-Moving Products

Slow-Moving Products

Note: The documentation describes the measures according to their role in the dashboard. Exact DAX expressions should only be documented from the PBIX model when the underlying measure definitions are available.

Dashboard Pages

The Power BI report contains five main analytical pages.

1 Inventory Overview

The Inventory Overview provides a high-level view of inventory health and inventory investment.

Key information

Total products

Total stock units

Inventory value

Inventory health

Products at risk

Inventory value by category

Stock units by category

Stock health by category

Reorder requirements

Key finding

61% of products are classified as healthy, while the remaining products fall into low-stock, critical or overstock categories.

2 Stock Health & Replenishment

This page focuses on inventory risk and replenishment.

Main analysis

Critical products

Low-stock products

Reorder requirements

Reorder units

Critical replenishment units

Replenishment requirements by product

Stock coverage

Products requiring action

Supplier replenishment requirements

Key finding

28 products require replenishment, with a total reported reorder requirement of 665 units.

3 Product Inventory Analysis

This page provides product-level analysis.

Main metrics

Inventory value

Units sold

Sales revenue

Days of inventory

Inventory turnover

Stock coverage

Fast-moving products

Slow-moving products

Key finding

The dashboard identifies 42 fast-moving products and 58 slow-moving products.

This indicates that slow-moving inventory represents a significant area for inventory-efficiency monitoring.

4 Category & Brand Performance

This page evaluates inventory and sales performance across categories and brands.

Analysis includes

Demand by category

Inventory value by category

Revenue by category

Inventory turnover by category

Revenue by brand

Brand replenishment requirements

Stock health by category

Category highlights

Home & Kitchen has the highest inventory value at approximately 30.72M.

Sports has the highest reported inventory turnover at approximately 54.48.

5 Replenishment & Management

This page focuses on operational inventory management.

Main analysis

Supplier replenishment risk

Reorder units

Overstocked products

Highest overstock inventory value

Replenishment action list

Supplier lead time

Supplier performance

Key finding

The dashboard identifies 11 overstocked products and 28 products requiring replenishment.

Inventory Health

The dashboard divides the 100 products into four stock-health categories:

Stock StatusProductsShare





Healthy

61

61%

Low Stock

18

18%

Overstock

11

11%

Critical

10

10%

This classification allows inventory managers to prioritize products according to stock condition.

Category Analysis

CategoryStock UnitsInventory ValueInventory Turnover







Home & Kitchen

2,868

30.72M

18.15

Beauty

2,175

29.01M

19.22

Fashion

2,096

23.39M

23.83

Electronics

1,738

24.05M

23.18

Sports

1,170

10.23M

54.48

Insight

Home & Kitchen represents the largest inventory investment, while Sports reports the highest inventory turnover.

Brand Analysis

The dashboard evaluates replenishment requirements across brands including:

Apex

FitPro

GlowCare

HomeCraft

Nova

PrimeTech

StyleHub

TrendLine

UrbanX

Zenith

HomeCraft and Nova have the highest reported number of products requiring replenishment.

Supplier Analysis

Supplier analysis covers:

Supplier name

Supplier rating

Lead time

Products requiring replenishment

Reorder units

The dataset contains 25 suppliers.

Supplier analysis helps connect inventory problems with the supply side of the business.

Key Business Insights

1. Majority of products are healthy

61% of products are currently classified as healthy.

2. Inventory risk remains significant

39 products fall into low-stock, critical or overstock categories.

3. Replenishment is required

28 products require replenishment, representing 665 reorder units according to the dashboard.

4. Critical stock requires immediate attention

10 products are classified as critical.

5. Overstock needs monitoring

11 products are classified as overstocked.

6. Home & Kitchen carries the highest inventory investment

Home & Kitchen has approximately 30.72M in inventory value.

7. Sports has strong inventory turnover

Sports reports an inventory turnover of approximately 54.48.

8. Slow-moving products dominate the portfolio

58 products are classified as slow-moving compared with 42 fast-moving products.

9. Supplier analysis supports replenishment planning

Supplier-level analysis allows management to understand where replenishment activity is concentrated.

Business Recommendations

Based on the dashboard findings:

Prioritize critical products

Critical products should be reviewed first because they represent the highest stock-risk category.

Monitor low-stock products

Products approaching or falling below reorder thresholds should be monitored regularly.

Review overstock

Overstocked products should be investigated to understand whether purchasing levels, demand forecasts or sales strategies need adjustment.

Improve slow-moving inventory management

The large number of slow-moving products suggests the need for:

Demand analysis

Promotional strategies

Inventory reduction plans

Better purchasing decisions

Monitor high-value inventory

Categories with large inventory investments should receive additional working-capital monitoring.

Use supplier analysis for replenishment planning

Supplier lead time and replenishment requirements should be considered when prioritizing purchase orders.

Limitations

The project has several limitations:

The underlying data source is confidential.

The analysis is dependent on the quality and completeness of the supplied dataset.

The dashboard represents the available data period and does not guarantee future demand.

Inventory health classifications depend on the defined stock thresholds.

Supplier risk analysis is limited to the supplier attributes available in the dataset.

The documentation does not expose confidential source information.

Future Improvements

Possible future enhancements include:

Automated data refresh

Real-time inventory monitoring

Demand forecasting

Machine-learning-based stock prediction

Automated reorder recommendations

Supplier risk scoring

ABC inventory classification

Safety-stock optimization

Lead-time variability analysis

Regional demand analysis

Sales-channel performance analysis

Inventory aging analysis

Automated Power BI alerts

Technology Stack

Data Preparation

Microsoft Excel

Power Query

Business Intelligence

Microsoft Power BI

DAX

Design

Figma

GIMP

AI Assistance

ChatGPT

ChatGPT was used for documentation assistance and project-development support.

Repository Structure

Inventory-Stock-Analysis/
│
├── README.md
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


Project Files

Power BI Report

Inventory_Stock_Analysis.pbix

Contains the Power BI data model, calculations and interactive dashboard.

Excel Dataset

Inventory_Stock_Analysis.xlsx

Contains the structured project dataset.

PDF Report

Inventory_Stock_Analysis.pdf

Contains the exported dashboard pages.

Dashboard Images

Five PNG exports are provided for quick visual inspection.

Skills Demonstrated

This project demonstrates practical experience in:

Data Analysis

Business Intelligence

Microsoft Power BI

Excel

Power Query

DAX

Data Modeling

KPI Development

Data Visualization

Inventory Analytics

Stock Health Analysis

Replenishment Analysis

Product Performance Analysis

Category Analysis

Brand Analysis

Supplier Analysis

Business Reporting

Business Decision Support

About the Analyst

Altamash Nizamuddin

Data Analyst

Power BI • Python • MySQL

Based in Mumbai, India.

Altamash Nizamuddin is a Data Analyst focused on transforming business data into meaningful insights through analytics, visualization and Business Intelligence.

Career Focus

Currently looking for opportunities in:

Data Analysis

Business Analysis

Business Intelligence

Power BI Development

Open to Work

Yes — Remote opportunities

Connect

GitHub

https://github.com/altamash-analyst

Email

altamash9876@gmail.com

LinkedIn: Not available

Portfolio Website: Not available

Credits

Project development included assistance from ChatGPT, particularly for documentation and analytical/project-development support.

SEO Keywords

Altamash-Analyst
Altamash Nizamuddin
Data Analyst
Power BI Data Analyst
Power BI Dashboard
Inventory Stock Analysis
Inventory Analytics
Inventory Management Dashboard
Stock Health Analysis
Inventory Replenishment
Inventory Turnover
Product Inventory Analysis
Supplier Performance Analysis
Business Intelligence
Business Analytics
Sales Analytics
Data Visualization
Power BI
DAX
Excel
Power Query
Data Analytics Portfolio
Power BI Portfolio Project
Inventory Risk Analysis
Stock Replenishment Dashboard


Project Status

Completed

Project Duration: 3 Days

Role: Data Analyst

Project Type: Business Intelligence / Data Analytics / Power BI Dashboard

⭐ If you find this project useful, feel free to explore the repository and connect with Altamash-Analyst on GitHub.
