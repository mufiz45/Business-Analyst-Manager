📊 Sales & Customer Intelligence Dashboard — Power BI Final Project
🏢 Project Background
This project was developed as the Final Capstone Project for the Data Analysis programme at Red and White Institute, assigned by Ananya Mehta (Business Analyst Manager, InsightPro Analytics Pvt Ltd). The objective was to simulate a real-world business intelligence scenario where a data analyst is tasked with building a fully functional, enterprise-grade Power BI dashboard from raw Excel data.
🎯 Project Objectives
Build a robust data model using Star Schema architecture
Use a variety of DAX formulas and patterns for measures and KPIs
Apply Time Intelligence, filtering, and formatting techniques
Create a fully interactive multi-page Power BI report
Ensure mobile compatibility and provide an enhanced user experience
🗂️ Dataset Overview
The dataset was imported from Excel files and structured into 6 tables:
Table
Type
Date_Dim
Dimension
Customer_Dim
Dimension
Product_Dim
Dimension
Region_Dim
Dimension
Sales_Fact
Fact
Returns_Fact
Fact
✅ Tasks Breakdown

1️⃣ Data Modeling
Created relationships between Fact and Dimension tables using Primary & Foreign Keys
Hidden unnecessary fields from the report view for a clean experience
Ensured a clean Star Schema layout with consistent naming conventions

2️⃣ DAX Measures & Calculated Columns
Measures created using:
CALCULATE, FILTER, ALL, SUMX, COUNTX, AVERAGEX
SWITCH for KPI classification logic
RELATED for joining values across tables
Calculated Columns created for:
Profit margin classification
Customer full names (First + Last)
Year-Month formatting for time-based visuals

3️⃣ Time Intelligence
Implemented Year-over-Year (YOY), Month-over-Month (MOM), and Year-to-Date (YTD) calculations for both Sales and Returns
Identified and visualized seasonal trends across the dataset

4️⃣ Dashboard Layout
Sketched layout with 1 Main Page, 2 Detail Pages, and 1 Drillthrough Page
Used Cards, KPI Cards, Line Charts, Bar Charts, and Donut Charts
Incorporated Trend lines and Forecasts for sales projections
Used Matrix visuals with conditional formatting
Added Top N Products by Sales and Top N Customers by Profit rankings

5️⃣ Filtering & Interaction
Added Slicers for Product, Customer Segment, Region, and Date
Used Drill Up/Down and Drillthrough filters for deeper analysis
Implemented Numeric Range Parameters for custom filtering

6️⃣ Navigation & UX
Added Custom Buttons & Bookmarks for smooth page navigation
Built a collapsible Slicer Panel for better screen real estate
Enabled Tooltips with mini visual summaries on hover
Used Advanced Conditional Formatting in Matrix/Table views

7️⃣ Mobile Layout
Optimized key pages for mobile viewing
Prioritized KPI Cards and Top N visuals for the mobile layout

8️⃣ Security
Added Roles for Region Managers using Row-Level Security (RLS)
Simulated row-level security to restrict regional data visibility per role

📦 Deliverables
✅ Power BI Report file (.pbix)
✅ Mobile Layout Preview
✅ Documented list of all DAX measures and visuals used
⬜ Final walkthrough video/demo (optional)
🛠️ Tools & Technologies
Tool
Usage
Power BI Desktop
Report building, data modeling, DAX
Microsoft Excel
Source data (imported as flat files)
DAX
Measures, calculated columns, time intelligence
Power BI Mobile
Mobile layout optimization
Row-Level Security
Role-based data access control
