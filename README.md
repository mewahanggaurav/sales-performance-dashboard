# 📊 Sales Performance Dashboard (SQL + Power BI)

This is an end-to-end data analytics portfolio project that simulates a real-world business request from a sales manager. The project covers everything from data extraction and transformation in SQL Server to dashboard development in Power BI.

## 🔍 Project Overview

- ✅ Client:  Sales Manager (Stephen)
- ✅ Request: Replace static Excel reports with an interactive dashboard showing internet sales performance
- ✅ Tools: SQL Server, Power BI, Excel

---

## 🛠️ Tools & Technologies
- **SQL Server Express + SSMS**
- **Power BI Desktop**
- **AdventureWorksDW 2019/2022**
- **Excel (for budget integration)**

---

## 🧱 Project Workflow

### 1. **Business Request & Planning**
- Parsed stakeholder email into a formal **Business Demand Overview**
- Created **User Stories** for sales managers and representatives

### 2. **Data Cleaning in SQL**
- Created cleaned dimension and fact tables:
  - `Dim_Calendar`
  - `Dim_Customers`
  - `Dim_Products`
  - `Fact_InternetSales`
- Applied SQL best practices: joins, filtering, formatting, renaming, CASE statements

### 3. **Power BI Data Model**
- Imported all cleaned CSV files + Excel budget
- Built relationships (many-to-one, star schema)
- Defined reusable **Measures** for:
  - Sales
  - Budget
  - Sales vs Budget %
  - Sales Variance
- Organized measures into a dedicated “Key Measures” table

### 4. **Interactive Dashboard**
- Main Pages:
  - ✅ Sales Overview
  - ✅ Customer Details
  - ✅ Product Details
- Visuals Used:
  - KPI cards
  - Bar charts (Top 10)
  - Line charts
  - Map visualization
  - Donut chart
  - Slicers (City, Product, Time)

### 5. **Publishing**
- Published to Power BI Service
- Embedded for web portfolio sharing

---

## 📁 File Structure

| Folder | Content |
|--------|---------|
| `data/` | Cleaned CSV + Excel budget |
| `sql/` | All transformation queries |
| `powerbi/` | `.pbix` file + public link |
| `screenshots/` | UI previews of dashboards |

---

## 🔗 Live Dashboard (Power BI Web)
> 📌 [Click to View Dashboard](https://YOUR-POWERBI-EMBED-LINK.com)

---

## 🧠 Key Skills Demonstrated
- Translating business requirements into data models
- Data cleansing and transformation in SQL
- KPI design and dashboard UX in Power BI
- Building interactive, filterable, and well-structured reports
