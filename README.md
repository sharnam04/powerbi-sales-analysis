# AdventureWorks Sales Analytics Dashboard | Power BI

This Power BI project analyzes AdventureWorks sales data using interactive dashboards, DAX measures, Power Query transformations, and a star schema data model.

## Overview

This project demonstrates an end-to-end Business Intelligence solution developed using Microsoft Power BI.

The report performs sales analysis on AdventureWorks data and showcases:

• Star Schema Data Modeling

• DAX Calculations

• Power Query Transformations

• Interactive Dashboards

• Currency Conversion Analysis

• Fiscal Year Analysis

• Dynamic Filtering

• ETL Concepts

## Objectives

- Analyze sales performance
- Track yearly product sales
- Analyze exchange rate impact
- Demonstrate Power Query transformations
- Build reusable DAX measures

## Tech Stack

• Power BI

• Power Query

• DAX

• Excel

## Datasets
- AdventureWorks Sales
- Exchange Rates

## Data Model

Star Schema

### Fact Table
- Sales

### Dimension Tables

- Customer
- Product
- Date
- Reseller
- Sales Territory
- Currency Rate

# 📊 Dashboard Pages

---

## 📄 Page 1 – Regional Sales Analysis

<img width="914" height="316" alt="image" src="https://github.com/user-attachments/assets/7e9b8319-9411-4f6f-b704-d309884101ca" />


### Objective
Analyze sales performance across different countries and demonstrate DAX calculations for filtering and comparing regional sales.

### Features
- Country-wise Sales Analysis
- Matrix Visualization
- Dynamic Country Filtering
- Conditional Sales Calculations
- Interactive Report Filters

### DAX Used
```DAX
SUM()
CALCULATE()
FILTER()
ALL()
SELECTEDVALUE()
```

### Business Insight
This report enables business users to compare sales across countries while dynamically excluding specific regions (such as Germany and the United Kingdom) using DAX. It demonstrates filter context manipulation and advanced analytical reporting.

---

## 📄 Page 2 – Fiscal Year Product Analysis

<img width="488" height="160" alt="image" src="https://github.com/user-attachments/assets/e01311a6-91c6-448d-9518-277b299690aa" />

### Objective
Analyze yearly sales performance along with product distribution across different fiscal years.

### Features
- Fiscal Year Sales Analysis
- Product Count
- Distinct Products Sold
- Matrix Visualization
- Fiscal Year Comparison

### DAX Used

```DAX
SUM()
COUNT()
DISTINCTCOUNT()
IF()
CALCULATE()
```

### Business Insight

Provides year-over-year sales trends and product distribution, allowing stakeholders to evaluate product adoption and revenue growth across fiscal years.

---

## 📄 Page 3 – Currency Exchange Analysis

<img width="1326" height="574" alt="image" src="https://github.com/user-attachments/assets/b072b31a-86de-422a-a418-ed2cc39ccfc5" />


### Objective

Analyze sales using multiple currencies and historical exchange rates through interactive slicers.

### Features

- Currency Selection
- Date Slicer
- Daily Sales Analysis
- Exchange Rate Analysis
- Dynamic Matrix Visual

### DAX Used

```DAX
SUM()
AVERAGE()
CALCULATE()
```

### Business Insight

This report allows users to analyze daily sales alongside exchange rates for different currencies. It demonstrates relationship modeling between Sales, Date, and Currency Rate tables and showcases dynamic filtering using slicers.

---

## 📄 Page 4 – Monthly Distribution using Power Query

<img width="870" height="602" alt="image" src="https://github.com/user-attachments/assets/7ce5703a-d57f-4d8e-aba2-2e09d9724a65" />


### Objective

Generate monthly distribution records from a single penalty record using Power Query transformations.

### Features

- Monthly Record Generation
- Cooling Period Calculation
- Penalty End Calculation
- Dynamic Date Expansion
- ETL Transformation using Power Query

### Power Query Functions Used

```PowerQuery
Date.StartOfMonth()

Date.AddMonths()

Date.EndOfMonth()

List.Transform()

Table.ExpandListColumn()

Table.TransformColumnTypes()
```

### Business Insight

A single penalty record is expanded into multiple monthly records based on the Cooling Period. The Penalty End date is automatically calculated as the last day of the final cooling month. This demonstrates real-world ETL data transformation techniques using Power Query.

---

# 📈 Skills Demonstrated

- Microsoft Power BI
- Data Modeling
- Star Schema Design
- DAX Calculations
- Power Query (M Language)
- ETL & Data Transformation
- Interactive Dashboards
- Matrix Visualizations
- Relationships
- Business Intelligence Reporting
- Data Visualization
- Excel Data Integration
