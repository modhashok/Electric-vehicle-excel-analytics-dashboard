Here is your **clean, professional, and hiring-manager-ready version**.
I’ve tightened the language, removed repetition, improved clarity, and kept it technical but concise.



# ⚡ Electric Vehicle Dashboard — Excel Analytics Project

> An interactive Excel dashboard analyzing Electric Vehicle (EV) adoption trends, market distribution, and performance metrics — built to transform raw registration data into actionable business insights.


## 📌 Overview

This project demonstrates an end-to-end data analysis workflow in Microsoft Excel — from raw dataset preparation to executive-level dashboard delivery.

The dashboard answers key market questions:

* Where is EV adoption accelerating?
* Which manufacturers dominate market share?
* How do BEVs compare to PHEVs?
* What geographic regions lead in registrations?
* How are range and pricing evolving over time?

The goal was to prove that Excel, when used strategically, can function as a powerful analytics and reporting tool.


## 🎯 Problem Statement

Electric vehicle datasets often contain thousands of rows across multiple fields — vehicle type, model year, geography, MSRP, electric range, and more.

Raw spreadsheets alone do not provide:

* Clear trends over time
* Market share comparisons
* Geographic concentration visibility
* Actionable insights for decision-makers

This project transforms flat data into structured analysis and interactive reporting.


## 🧹 Data Preparation & Cleaning

**Steps performed:**

* Removed duplicate records and blank rows
* Standardized inconsistent text using `TRIM`, `PROPER`, and `SUBSTITUTE`
* Converted date and year columns into numeric formats
* Identified and handled missing values
* Structured dataset into an Excel Table (Ctrl + T) for dynamic referencing

**Additional Enhancements:**

* Created helper columns:

  * EV Range Categories (Short / Mid / Long)
  * Price Tiers
  * Model Year Groups
* Ensured consistent categorical formatting for Pivot compatibility


## 📊 Data Modeling & Aggregation

Built a structured analytical layer using:

* PivotTables
* Calculated Fields
* Multi-criteria aggregation formulas

### Core Analyses Included:

* Total registrations by Make & Model
* BEV vs PHEV distribution
* Year-over-year adoption trends
* Top counties/cities by EV concentration
* Average electric range by manufacturer
* Market share percentage calculations


## 🧮 Advanced Excel Techniques Used

**Aggregation Functions**

* `COUNTIFS`
* `SUMIFS`
* `AVERAGEIFS`

**Dynamic & Lookup Functions**

* `INDEX` + `MATCH`
* `LARGE`
* `RANK`
* `IFERROR`

**Formatting & Presentation**

* Conditional Formatting (heatmaps, data bars)
* Custom number formatting (K/M notation)
* Named ranges for clean formulas
* Slicers connected to multiple PivotTables
* KPI cards built using formulas and shape overlays


## 📈 Dashboard Design

The final dashboard is built as a single interactive reporting view with:

### 🔹 KPI Header

* Total EV Registrations
* Top Manufacturer
* Top Model
* Average Electric Range

### 🔹 Market Split

* BEV vs PHEV distribution (Donut Chart)

### 🔹 Trend Analysis

* EV registrations by year (Line Chart)

### 🔹 Manufacturer Ranking

* Top 10 Makes (Bar Chart)

### 🔹 Geographic Distribution

* County/Regional breakdown

### 🔹 Interactive Filtering

Slicers allow filtering by:

* Vehicle Type
* Model Year
* Manufacturer
* Region

All visuals update dynamically based on user selections.


## 📊 Key Insights

* EV adoption has accelerated significantly post-2018.
* BEVs are outpacing PHEVs in recent years.
* A small number of manufacturers dominate total registrations.
* Adoption is geographically concentrated in urban/high-income regions.
* Average electric range has improved year over year.
* Mid-range priced vehicles drive the majority of volume.

## 🤖 Automation Potential

This dashboard currently uses static data, but can be automated through:

* **Power Query** for live data refresh
* **Power BI** for cloud-based scheduled updates
* **Python integration (openpyxl / xlwings)** for automated API pulls
* **Power Automate** for recurring refresh workflows

## 🚀 How To Use

1. Download the `.xlsx` file
2. Open in Excel (2016+ recommended)
3. Navigate to the **Dashboard** sheet
4. Use slicers to filter data dynamically
5. Clear filters to reset view

No macros required — fully powered by PivotTables and formulas.

## 🧠 Skills Demonstrated

* Data Cleaning & Validation
* Data Modeling in Excel
* Exploratory Data Analysis (EDA)
* KPI Development
* Interactive Dashboard Design
* Business-Focused Data Storytelling
* Advanced Excel Functions


## 🔮 Future Enhancements

* API-based live data integration
* Forecast modeling for future adoption
* Infrastructure (charging station) correlation analysis
* MSRP vs Adoption scatter modeling
* Year-over-year percentage growth metrics
* Migration to Power BI for enterprise scalability

* Make it slightly more business-focused instead of technical
* Or rewrite it specifically for Canadian data analyst job applications
