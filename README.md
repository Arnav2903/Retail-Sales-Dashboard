Retail Sales Analysis Dashboard

Overview

This project is an interactive Power BI dashboard built to analyze retail sales data, providing insights into regional performance, sales trends, and product profitability. The dashboard enables stakeholders to identify top-performing regions, track monthly sales trends, and understand profit distribution across product categories, with interactive filtering by product. This project demonstrates proficiency in Power BI, data visualization, data modeling, DAX, and Power Query, making it a strong portfolio piece for data analyst roles.

Skills Used:-
Power BI: Designed interactive dashboards with bar, line, and pie charts.
Power Query: Cleaned and transformed data, including adding a calculated Profit column.
DAX: Created measures for Total Sales and Total Profit.
Data Modeling: Built a data model with a DateTable and relationships for time-based analysis.
Data Visualization: Developed visuals to communicate insights effectively.
Data Analysis: Derived actionable insights (e.g., top sales regions, profit by category).

Dataset
The dataset (retail_sales_100.csv) contains 100 rows of retail sales data with columns:

OrderDate: Date of the sale.
Product: Product sold (Monitor, Keyboard, Mouse, Headphones).
Category: Product category (Electronics, Accessories).
Region: Sales region (North, East, South, West).
CustomerID, Quantity, UnitPrice, SalesAmount, Cost: Sales metrics.
Calculated Profit column added in Power Query (SalesAmount - Cost).

Download Dataset

Methodology
Data Loading: Imported retail_sales_100.csv into Power BI Desktop.
Data Cleaning:
Used Power Query to convert OrderDate to Date type and add Profit column.
Checked for duplicates and missing values (none found).

Data Modeling:
Created a DateTable for time-based analysis.
Established a relationship between DateTable[Date] and retail_sales_100[OrderDate].

DAX Measures:
Created Total Sales = SUM('retail_sales_100'[SalesAmount]).
Created Total Profit = SUM('retail_sales_100'[Profit]).

Visualizations:
Bar Chart: Total Sales by Region (Region on X-Axis, Total Sales on Y-Axis).
Line Chart: Sales Trend by Month (Month on X-Axis, Total Sales on Y-Axis).
Pie Chart: Profit by Product Category (Category on Legend, Total Profit on Values).
Slicer: Filter by Product for interactivity.

Dashboard Design: Arranged visuals with a professional theme and added a title.

Insights
Regional Performance: North region likely leads in sales, driven by high-value Mouse orders.
Sales Trends: Sales peak in months like July and September, indicating potential seasonality.
Profit Distribution: Electronics (Monitors) contribute significantly more profit than Accessories due to higher margins.
Interactivity: The slicer allows filtering by product, enabling targeted analysis (e.g., Monitor sales by region).

Screenshots
Full Dashboard: Shows all visuals and slicer.
Filtered View: Dashboard filtered by Monitor.
Power Query: Adding the Profit column.
Data Model: Relationship between tables.


Files
Power BI File: The complete dashboard.
Dataset: The raw data.
DAX Measures: DAX code for measures.

How to Run
Download Power BI Desktop (free).
Download Retail_Sales_Dashboard.pbix and open it in Power BI Desktop.
Use the slicer to filter by product and interact with visuals.
Explore the bar, line, and pie charts to analyze sales and profit.

Future Improvements
Add drill-downs to explore product-level details within regions.
Include KPI cards for metrics like total profit or average sales per order.
Publish to Power BI Service for online sharing.

Contact

For questions or to discuss this project, connect with me on LinkedIn[www.linkedin.com/in/arnav-mehta-43b790230] or email [arnavmehta@2903.com].
