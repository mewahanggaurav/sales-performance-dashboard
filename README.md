# Sales Performance Dashboard (SQL + Power BI)

This is an end-to-end data analytics portfolio project that simulates a real-world business
request from a sales manager. The project covers everything from data extraction and
transformation in SQL to dashboard development in Power BI.

![Sales Overview](11.png)

![Customer Details](12.png)

![Product Details](13.png)

---

## 🔍 Project Overview

| Field | Details |
|-------|---------|
| **Client** | Sales Manager |
| **Request** | Replace static Excel reports with an interactive dashboard showing internet sales performance |
| **Tools** | SQL Server, Power BI, Excel |

---

## 🛠️ Tools & Technologies

- **SQL Server Express + SSMS**
- **Power BI Desktop**
- **AdventureWorksDW 2019/2022**
- **Excel** (for budget integration)

---

## 🔄 Project Workflow

### 1. Business Request & Planning

- Parsed a stakeholder email into a formal **Business Demand Overview**
- Defined **User Stories** for sales managers and sales representatives

### 2. Data Cleaning in SQL

Created cleaned dimension and fact tables using SQL best practices (joins, filtering, CASE statements, formatting):

| Table | Description |
|-------|-------------|
| `Dim_Calendar` | Date dimension for time-based filtering |
| `Dim_Customers` | Customer attributes and segments |
| `Dim_Products` | Product hierarchy and categories |
| `Fact_InternetSales` | Core transactional sales data |

### 3. Power BI Data Model

- Imported all cleaned CSV files alongside the Excel budget file
- Built a **star schema** with many-to-one relationships
- Created reusable **DAX Measures** organized in a dedicated "Key Measures" table:
  - Sales & Budget totals
  - Sales vs. Budget variance (absolute and %)

### 4. Interactive Dashboard

Three report pages, each with slicers for City, Product, and Time:

| Page | Visuals |
|------|---------|
| **Sales Overview** | KPI cards, bar chart (Top 10), line chart, map |
| **Customer Details** | Customer breakdown, donut chart, trend line |
| **Product Details** | Product performance, Top 10 ranking, filters |

### 5. Publishing

- Published to **Power BI Service**
- Embedded for web portfolio sharing

---

## 📁 File Structure

| Folder | Content |
|--------|---------|
| `data/` | Cleaned CSV files + Excel budget |
| `sql/` | All SQL transformation queries |
| `powerbi/` | `.pbix` dashboard file |

---

## 💡 Key Skills Demonstrated

- Translating business requirements into a structured data model
- Data cleansing and transformation in SQL
- KPI design and dashboard UX in Power BI
- Building interactive, filterable, and well-structured reports
