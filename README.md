# Executive Finance Power BI Dashboard

An interactive management dashboard built in Microsoft Power BI to turn finance and operating data into concise executive reporting.

> **Portfolio disclosure:** This project uses a fictional company and synthetic financial data created solely for portfolio demonstration.

## Project Objective

The dashboard provides management with a quick view of financial performance and working-capital trends, with interactive filtering by reporting period and product line.

It is designed to answer practical questions such as:

- How is actual revenue performing against budget?
- Which products and customers generate the most revenue?
- How are cash, receivables, payables and inventory developing?
- How does performance change across periods and product lines?

## Dashboard Highlights

- Actual Revenue KPI
- Budget Revenue KPI
- Cash KPI
- Inventory KPI
- Actual vs Budget revenue comparison
- Revenue by product
- Revenue by customer
- AR vs AP vs Inventory analysis
- Interactive date filtering
- Product-line filtering
- Dimensional model with finance fact and supporting dimension tables

## Data Model

The report uses a simple star-schema approach with:

- **Fact_Finance** — finance and operating measures
- **Dim_Date** — reporting calendar
- **Dim_Product** — product and product-line attributes
- **Dim_Customer** — customer attributes
- **Dim_Department** — organizational dimensions
- **KPI_Targets** — management KPI reference data

Relationships are structured as one-to-many from the dimension tables to the finance fact table.

## Tools & Skills Demonstrated

**Microsoft Power BI · Power Query · Data Modeling · Financial Analysis · Management Reporting · Budget vs Actual Analysis · KPI Reporting · Data Visualization · Interactive Dashboards**

## Portfolio Context

This project complements my Excel-based FP&A, ERP finance, three-statement modeling and strategic business-case projects by demonstrating the ability to translate financial data into an interactive management reporting experience.

## Files

- `Project_4_Executive_Finance_KPI_Dashboard.pbix` — Power BI report
- `Project_4_PowerBI_Executive_KPI_Data_Model.xlsx` — synthetic source data/model workbook

## Author

**Raza Saleem**

Finance & FP&A Portfolio Project
