# 📊 Company Sales Analysis Dashboard 📊

This repository contains the data, Power BI dashboard, and supporting documentation for the Sales and Revenue Analysis Dashboard. The dashboard provides comprehensive insights into sales and revenue metrics, including total revenue, sales quantity, profit margins, and more. It is designed to be easily accessible and understandable, with both desktop and mobile views.

## 📋 Table of Contents
- [📝 Project Planning](#project-planning)
- [📊 Power BI Dashboard](#power-bi-dashboard)
- [🏛️ Data Warehouse Design](#data-warehouse-design)
- [🔗 Database Connection](#database-connection)
- [🔍 Data Modeling](#data-modeling)
- [🛠️ Data Transformation](#data-transformation)
- [📏 Measure Creation](#measure-creation)
- [📉 Visualizations](#visualizations)
- [📱 Mobile View](#mobile-view)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## 📝 Project Planning
1. Planned the project using the AIMS Grid (Actions, Information, Methods, Systems).

## 📊 Power BI Dashboard
1. Created a Power BI dashboard to visualize sales and revenue data.

## 🏛️ Data Warehouse Design
1. Designed a minimal data warehouse to prevent corruption of the main OLTP data.
2. Performed ETL (Extract, Transformation, and Load) to store data in the data warehouse.

## 🔗 Database Connection
1. Connected Power BI to a MySQL database using SQL Workbench.

## 🔍 Data Modeling
1. Established relationships between tables according to the schema.
2. Achieved a star schema for the project, completing data modeling.

## 🛠️ Data Transformation
1. Used Power BI's Transform Data feature for ETL, data cleaning, data merging, and data wrangling.

## 📏 Measure Creation
1. Created new measures for dashboard visualization:
   - Total revenue for all years
   - Total sales quantity for all years
   - Total revenue %
   - Profit margin %
   - Profit margin contribution
   - Total profit margin
   - Calculated revenue

## 📉 Visualizations
1. **Main Dashboard**:
   - Revenue by each customer
   - Sales quantity by customer
   - Revenue by market
   - Top 5 markets and top 5 products
   - Revenue trend by years and months

2. **Detailed Dashboard**:
   - Revenue, sales quantity, total profit margin
   - Revenue contribution by top 5 markets
   - Profit contribution by top 5 markets
   - Profit % by market
   - Revenue by years
   - Pie chart on type of customers
   - Table with details of all key measures

3. **Target and Trend Dashboard**:
   - Revenue contribution by top 5 markets with a target slider
   - Highlight markets not achieving targets
   - Revenue to profit margin trend by month and year
   - Key measures at the top for quick reference

## 📱 Mobile View
1. Created a mobile view for the dashboard to ensure accessibility from any device.

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.
