📊 Sales Performance Analysis — Excel Dashboard

An interactive, multi-dimensional sales performance dashboard built entirely in Microsoft Excel using Pivot Tables, Slicers, and a structured data model — designed to give quick, filter-driven visibility into sales, profit, and order trends.

📌 Project Overview

The goal of this project was to take raw, transaction-level sales order data and transform it into a decision-ready dashboard that business users can filter and explore without needing any technical skills — entirely within Excel.

🗂️ Dataset
Orders analyzed: 42,736 sales order line items (10,684 unique orders)
Supporting tables: Sales Orders, Products, Customers, Regions, and a custom State-to-Region mapping table
Data structure: Multiple related tables linked together (similar to a relational data model), enabling cross-table analysis
🧹 Data Preparation
Consolidated raw order, customer, product, and region data into clean, structured tables
Built a dedicated "Clean Data" sheet to standardize and validate data before feeding it into the dashboard
Created a custom State → Region mapping table to enable geographic roll-up analysis (State-level detail rolling up to Region-level summaries)
📈 Dashboard & KPIs

Built on a dedicated KPI's sheet using Pivot Tables, the dashboard tracks:

Total Sales
Total Profit
Profit Margin % (37.4%)
Total Order Quantity
Average Sale Value
🔍 Analysis Breakdowns

Using Pivot Tables and interactive Slicers, the dashboard allows filtering and breakdown by:

Category — which product categories drive the most sales and profit
Month — month-over-month sales trends
Sales Channel — Distributor, Export, and Wholesale performance comparison
Region / State — geographic performance, powered by the custom State-Region mapping table
🛠️ Tools & Techniques

Microsoft Excel · Pivot Tables · Slicers · Data Modeling (multi-table) · Lookup Functions

📁 Repository Structure
├── Varsha_Karma_Sales_Performance_Analysis_Excel_Dashboard.xlsx
├── screenshots/                # Dashboard views (add screenshots here)
└── README.md

Note: GitHub does not render .xlsx dashboards or slicers in preview. Screenshots of the dashboard views are included in the screenshots/ folder so viewers can see the interactive dashboard without downloading the file.

🚀 How to Use
Download Varsha_Karma_Sales_Performance_Analysis_Excel_Dashboard.xlsx
Open in Microsoft Excel (2016 or later recommended for full Slicer support)
Go to the DashBoard sheet
Use the Slicers to filter by Category, Month, Channel, or Region/State and explore the KPIs update live
📈 Future Improvements
Migrate the same data model into Power BI for a more scalable, shareable dashboard
Add year-over-year comparison and trend forecasting
Automate data refresh using Power Query instead of manual paste/update
