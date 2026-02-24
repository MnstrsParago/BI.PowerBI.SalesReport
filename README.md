# Sales Report
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/51ca9f70-ee5f-4e36-a2b1-044e5248e2d9" />


**Subject:** Business Intelligence (Microsoft Power BI)  
**Name:** Abdanur

## 📌 Project Description
This repository contains a Power BI sales analytics report built from an Excel dataset.  
The data is cleaned in Power Query, related tables are connected in the data model, and key business metrics are calculated using measures.  
The final result is an interactive dashboard with charts and a table for performance review.

## 💡 Features
- Data cleaning and normalization in Power Query (remove empty/extra rows, fix data types)
- Data model with relationships between tables
- DAX measures for key metrics:
  - Revenue
  - Profit
  - Profitability (%)
  - Active Customer Base (unique customers)
  - Average Check (avg purchase value)
  - Logistics Cost
- Visuals:
  - KPI trends over time
  - Metrics by customer segment
  - Map-based distribution
- Table to identify managers with negative profit and number of such orders

## 📦 Technologies
- Microsoft Power BI (Power Query + Data Model + DAX)
- Microsoft Excel (`.xlsx`) as a data source

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MnstrsParago/BI.PowerBI.SalesReport.git
   cd BI.PowerBI.SalesReport
   ```
2. Open `Sales Report.pbix` in **Power BI Desktop**.
3. If Power BI asks for the data source path, re-link the Excel file `База данных.xlsx` from the repository folder.
4. Refresh the report to load data and recalculate measures.

## 📘 Reflection
This project helped me practice a complete BI workflow: cleaning data, building a model, writing measures, and designing visuals.  
It also improved my understanding of how to turn raw sales data into clear insights for decision-making.
