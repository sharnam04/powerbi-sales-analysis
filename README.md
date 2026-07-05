<h1 align="center">📊 AdventureWorks Sales Analytics Dashboard</h1>

<p align="center">
An interactive Business Intelligence dashboard built using <b>Microsoft Power BI</b> to analyze AdventureWorks sales data through data modeling, DAX, Power Query, and insightful visualizations.
</p>

<p align="center">

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-005C9C?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Star_Schema-Data_Model-blue?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-Analytics-success?style=for-the-badge)

</p>

---

# 📌 Project Overview

This project demonstrates an end-to-end Business Intelligence solution developed using **Microsoft Power BI**.

The dashboard analyzes AdventureWorks sales data to uncover valuable business insights through interactive reports, data modeling, DAX calculations, and Power Query transformations.

The solution follows BI best practices by implementing a **Star Schema**, reusable DAX measures, and dynamic filtering to enable effective decision-making.

---

# 🎯 Business Problem

AdventureWorks operates across multiple countries and currencies. Business users require a centralized dashboard to monitor sales performance, compare yearly trends, analyze exchange rate impact, and explore product distribution.

This dashboard enables users to answer important business questions through interactive visualizations and dynamic reports.

---

# 🚀 Project Objectives

- Analyze regional sales performance
- Compare yearly product sales
- Track product distribution across fiscal years
- Analyze currency exchange rate impact
- Build reusable DAX measures
- Perform ETL transformations using Power Query
- Design interactive business dashboards

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard Development |
| Power Query (M) | Data Cleaning & Transformation |
| DAX | Business Calculations |
| Excel | Data Source |
| Star Schema | Data Modeling |

---

# 📂 Dataset

The project uses the **AdventureWorks** sample dataset.

### Fact Table

- Sales

### Dimension Tables

- Customer
- Product
- Date
- Reseller
- Sales Territory
- Currency Rate

---

# ⭐ Data Model

The report follows a **Star Schema** design to improve query performance and simplify report development.

```
                Customer
                    │
                    │
Product ─── Sales ─── Date
                    │
                    │
        Sales Territory
                    │
                    │
            Currency Rate
                    │
                    │
              Reseller
```

---

# 🔄 Project Workflow

```
AdventureWorks Dataset
          │
          ▼
Power Query (ETL)
          │
          ▼
Data Cleaning
          │
          ▼
Star Schema Modeling
          │
          ▼
DAX Measures
          │
          ▼
Interactive Dashboards
          │
          ▼
Business Insights
```

---

# 📊 Dashboard Pages

---

# 📄 Page 1 — Regional Sales Analysis

<img width="914" height="316" alt="Regional Sales Dashboard" src="https://github.com/user-attachments/assets/7e9b8319-9411-4f6f-b704-d309884101ca"/>

## Objective

Analyze sales performance across different countries and compare regional sales using advanced DAX calculations.

### Features

- Country-wise Sales Analysis
- Matrix Visualization
- Dynamic Country Filtering
- Interactive Report Filters
- Conditional Sales Calculations

### DAX Functions Used

```DAX
SUM()

CALCULATE()

FILTER()

ALL()

SELECTEDVALUE()
```

### Business Insight

This dashboard enables users to compare sales across countries while dynamically excluding specific regions using DAX filter context manipulation.

---

# 📄 Page 2 — Fiscal Year Product Analysis

<img width="488" height="160" alt="Fiscal Year Dashboard" src="https://github.com/user-attachments/assets/e01311a6-91c6-448d-9518-277b299690aa"/>

## Objective

Analyze yearly sales performance and product distribution across different fiscal years.

### Features

- Fiscal Year Sales
- Product Count
- Distinct Products Sold
- Matrix Visualization
- Year-over-Year Comparison

### DAX Functions Used

```DAX
SUM()

COUNT()

DISTINCTCOUNT()

IF()

CALCULATE()
```

### Business Insight

Provides year-over-year sales trends while helping stakeholders understand product growth and revenue distribution.

---

# 📄 Page 3 — Currency Exchange Analysis

<img width="1326" height="574" alt="Currency Dashboard" src="https://github.com/user-attachments/assets/b072b31a-86de-422a-a418-ed2cc39ccfc5"/>

## Objective

Analyze sales using multiple currencies and historical exchange rates.

### Features

- Currency Slicer
- Date Slicer
- Exchange Rate Analysis
- Daily Sales Analysis
- Dynamic Matrix Report

### DAX Functions Used

```DAX
SUM()

AVERAGE()

CALCULATE()
```

### Business Insight

Demonstrates relationship modeling between Sales, Date, and Currency Rate tables while enabling dynamic currency-based reporting.

---

# 📄 Page 4 — Monthly Distribution using Power Query

<img width="870" height="602" alt="Power Query Dashboard" src="https://github.com/user-attachments/assets/7ce5703a-d57f-4d8e-aba2-2e09d9724a65"/>

## Objective

Generate monthly records from a single penalty record using Power Query transformations.

### Features

- Monthly Record Generation
- Cooling Period Calculation
- Penalty End Date Calculation
- Dynamic Date Expansion
- ETL Transformation

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

Demonstrates real-world ETL transformations where a single business record is expanded into multiple monthly records using Power Query.

---

# 📈 Key KPIs

- Total Sales
- Sales by Country
- Fiscal Year Sales
- Product Count
- Distinct Products Sold
- Average Exchange Rate
- Daily Sales
- Currency-wise Performance

---

# 💡 Skills Demonstrated

- Microsoft Power BI
- Data Modeling
- Star Schema Design
- DAX Calculations
- Power Query (M Language)
- ETL & Data Transformation
- Interactive Dashboards
- Business Intelligence
- Data Visualization
- Matrix Reports
- Relationships
- Currency Analysis
- Fiscal Year Analysis
- Excel Data Integration

---

# 📚 Key Concepts Implemented

- Star Schema Modeling
- One-to-Many Relationships
- Active Relationships
- Dynamic Filtering
- Context Transition
- Filter Context Manipulation
- DAX Measures
- Power Query Transformations
- Interactive Reporting
- Business Storytelling

---

# 📖 What I Learned

Throughout this project, I gained practical experience in:

- Designing scalable Power BI data models
- Building reusable DAX measures
- Performing ETL transformations using Power Query
- Creating business-friendly dashboards
- Working with Star Schema architecture
- Developing interactive reports using slicers and filters
- Converting business requirements into visual analytics

---

# 🚀 Future Enhancements

- Drill-through Reports
- KPI Cards
- Bookmarks & Navigation
- Row-Level Security (RLS)
- Incremental Refresh
- Performance Optimization
- Mobile Layout Optimization

---

# 📂 Repository Structure

```
PowerBI-Sales-Analysis/

│

├── AdventureWorks Dashboard.pbix

├── README.md

└── assets/
    ├── regional-sales.png
    ├── fiscal-analysis.png
    ├── currency-analysis.png
    └── power-query.png
```

---

# 👨‍💻 Author

## Sharnam Kansal

**Data Engineer**

Experienced in building modern data solutions using Azure Databricks, Microsoft Fabric, PySpark, SQL, Azure Data Factory, Delta Lake, and Power BI.

📧 **Email:** your-email@example.com

💼 **LinkedIn:** https://linkedin.com/in/your-profile

🐙 **GitHub:** https://github.com/sharnam04

---

## ⭐ If you found this project useful, consider giving it a star!
