Sales & Customer Intelligence Dashboard

Project Overview

This Power BI project focuses on building an interactive and data-driven dashboard to analyze Sales, Returns, Customer Behavior, and Regional Performance over the last three years. The report is designed to support business decision-making using strong data modeling and advanced DAX calculations.

---

Objectives

- Build a robust Star Schema data model
- Use DAX formulas to create KPIs and measures
- Apply Time Intelligence (YOY, MOM, YTD)
- Design an interactive multi-page dashboard
- Ensure mobile-friendly layout
- Implement data filtering and navigation features

---

Dataset Details

The project uses the following tables:

- Date_Dim
- Customer_Dim
- Product_Dim
- Region_Dim
- Sales_Fact
- Returns_Fact

---

Data Modeling

- Created relationships between fact and dimension tables using Primary and Foreign Keys
- Implemented a Star Schema structure
- Cleaned and transformed data using Power Query
- Removed unnecessary columns for better performance

---

Calculated Columns

- Customer Full Name (First + Last Name)
- Year-Month formatting
- Profit Category classification (High, Medium, Low)

---

DAX Measures

Created multiple measures using:

- CALCULATE, FILTER, ALL
- SUMX, COUNTX, AVERAGEX
- SWITCH for KPI classification
- RELATED for table relationships

Key KPIs:

- Total Sales
- Total Profit
- Total Quantity
- Total Returns

---

Time Intelligence

- Year-to-Date (YTD)
- Month-over-Month (MOM)
- Year-over-Year (YOY)
- Identified seasonal sales trends

---

Dashboard Pages

1. Main Dashboard

- KPI Cards (Sales, Profit, Returns)
- Line Chart (Sales Trend)
- Bar Chart (Sales by Region)
- Donut Chart (Category Distribution)

2. Sales Details

- Top Products by Sales
- Monthly Performance Trends
- Matrix visual with conditional formatting

3. Customer Insights

- Top Customers by Profit
- Customer segmentation analysis

4. Drillthrough Page

- Detailed view of selected customer or product

---

Filters and Interactions

- Slicers for Product, Region, Customer Segment, and Date
- Drill Up and Drill Down functionality
- Drillthrough filters
- Top N filtering for products and customers

---

UX and Navigation

- Custom buttons for page navigation
- Bookmarks for interactive experience
- Collapsible slicer panel
- Tooltips with mini visual summaries
- Advanced conditional formatting in tables and matrix

---

Mobile Layout

- Optimized key pages for mobile view
- Focused on KPI cards and top visuals for better usability

---

Security

- Implemented Role-Level Security (RLS)
- Created roles for region-based data access
- Simulated restricted data views

---

Deliverables

- Power BI Report (.pbix file)
- Mobile Layout Preview
- Documented list of DAX measures and visuals used
- Optional walkthrough video or demo

---

Conclusion

This project demonstrates the use of Power BI for creating a complete business intelligence solution. It combines data modeling, DAX calculations, and interactive visualization techniques to provide meaningful insights for business decision-making.
