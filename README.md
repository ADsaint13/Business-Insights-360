# Project-Business-Insights-360 (Data Analyst Challenge at Codebasics.io)
## SQL Data Exploration & Power BI Dashboard

## Link to my Dashboard

🔷 Power BI Service -https://app.powerbi.com/view?r=eyJrIjoiMGFkZjgwNWYtYjMyNS00MjA5LTk0MmUtZGRlNjg5MjUyZGRhIiwidCI6IjFhOTM3NWU4LWI4YzUtNGQ5MS04MGVlLTZmYzI4Mzk2NzAwNyJ9

## Overview:
*Project: Provide insights on Finance, Sales, Marketing, and Supply Chain to the management.*  
*Domain: Manufacturing Domain*

AtliQ Hardware is a company that manufactures and sells hardware. They have customers across the globe and offer products under various categories.  
The AtliQ team previously used MS Excel for data analysis. However, as the business expanded globally, the company's top management decided to adopt Power BI for analytics.  
They asked the analytics team to provide insights through SQL for decision-making and, as a later part of the project, create a dashboard for key departments to track important metrics and make data-driven decisions.

## Task:

* As a data analyst, I was provided with sample data and a mock-up dashboard to work on the following tasks:

  - Write SQL queries to generate important insights and reports for product owners to support data-driven decisions.
  - Create stored procedures so managers can extract reports based on filters.
  - Build a fully functional dashboard for data-driven decision-making, offering insights across Finance, Sales, Marketing, and Supply Chain.

## Tech Stack Used in the Project:

* MySQL  
* MS Excel  
* Power BI  

## Work Flow:
### SQL Workbench

* Loaded data into MySQL and designed the database using a Snowflake schema, establishing relationships between tables via an ERD.
* Data was prepared for analysis, and key metrics were derived based on requests from product owners.
* Created stored procedures for complex queries so that product owners could generate reports using necessary filters.
* Developed a data pipeline to derive metrics, implementing data cleaning techniques where necessary.
* Reports generated:
  - [Profit and Loss Metrics](https://github.com/ADsaint13/Business-Insights-360/blob/main/Sql%20Insights-1%20Advance%20Finance%20Analysis..sql)
  - [Top Performer Metrics](https://github.com/ADsaint13/Business-Insights-360/blob/main/Sql%20Insights-2%20Advance%20Top%20Performer%20Analysis..sql)
  - [Forecast Accuracy for Supply Chain](https://github.com/ADsaint13/Business-Insights-360/blob/main/Sql%20Insights-3%20Advance%20Supply%20Chain%20%20Analysis..sql)

### Power BI Dashboard

* Connected Power BI to MySQL and Excel, transformed data using Power Query, and established relationships using a Snowflake schema. Initial validation was done against benchmark values.
* Used DAX to create calculated columns and measures and built a dynamic dashboard with KPIs for Sales, Finance, Marketing, and Supply Chain.
* Published the report to Power BI Service for UAT and validated data using Excel.
* Incorporated stakeholder feedback, created an Executive Dashboard, resolved quality issues, optimized performance, and deployed with gateway setup to MySQL and Excel for automatic data refresh.
* Applied project management tools: project charter, stakeholder mapping, and Kanban board for task tracking and productivity.
* Designed a dashboard with multi-level analysis. It facilitated stakeholder engagement by answering "why" questions on top-performing products, markets, customers, % changes, trends in P&L metrics, and inventory management improvements.
* Created intuitive dashboard views for various departments to track overall company performance.

✔ Finance View  
✔ Sales View  
✔ Marketing View  
✔ Supply Chain View  
✔ Executive View  

## Key Features in Finance View:
* A Profit and Loss statement that explains various P&L metrics from Gross Sales to Net Profit. "BM" indicates the benchmark, which is either last year or the target, selectable via slicer.
* KPIs for Net Sales, Gross Margin %, and Net Profit %.
* Net Sales performance trends compared to Target/Last Year (selectable dynamically).
* Top/Bottom Products and Top/Bottom Customers based on Net Sales.

## Key Features in Sales View:
* Unit Economics 1: Net Sales vs Post-Invoice and Pre-Invoice Discount amounts provided by the company.
* Unit Economics 2: Total COGS (Cost of Goods Sold) spent by the company and the derived Gross Margin.
* Customer and Product performance analysis based on Net Sales, Gross Margin, and Gross Margin %.
* Performance Matrix for Market, Customer, and Region based on Net Sales and Gross Margin %.
* Sales trend tooltip for each customer based on Net Sales and Gross Margin %.

## Key Features in Marketing View:
* Unit Economics: Operational expenses spent per product, with Net Profit calculated after subtracting these expenses.
* Performance Matrix for Segment, Category, and Product using a dynamic toggle between:
  - Net Sales & Net Profit %
  - Net Sales & Gross Margin %

## Key Features in Supply Chain View:
* KPIs for Forecast Accuracy, Net Error, and Absolute Error (ABS Error).
* Risk factor analysis.
* Accuracy vs Net Error trend visualizations.
* Key metrics for Customers and Products: FA%, FA% LY, Net Error, Net Error %, and Risk Factor.

## Key Features in Executive View:
A high-level report page for top management to track company-wide performance metrics.

* Market Share Trend analysis for AtliQ vs competitors.
* Revenue analysis by Division and Channel.
* Top 5 Products and Top 5 Customers by Revenue.
* Sub-zone insights with Revenue Contribution % analysis.

    
## Key Learnings:

* The most insightful metrics for senior management are Gross Margin and Net Profit (Gross Margin - Operational Costs).
* Sales teams prioritize Gross Margin and Net Sales over Net Profit, as they typically have no control over operational costs.
* Marketing teams need to track changes in marketing spend and their impact on revenue and gross margin.
* For the supply chain team, KPIs such as Forecast Accuracy, Risk, Net Error, and Absolute Error are crucial.
* Managing stakeholder expectations is a key skill that enhances the value and clarity of data visualizations.

# Thank you.

## 📸 Screenshots / Demos

### 🏠 Home
![Dashboard Preview](https://github.com/ADsaint13/Business-Insights-360/blob/main/Home%20view.png)

---

### 💰 Finance View
![Finance View](https://github.com/ADsaint13/Business-Insights-360/blob/main/Finance%20View.png)

---

### 📈 Sales View
![Sales View](https://github.com/ADsaint13/Business-Insights-360/blob/main/Sales%20View.png)

---

### 📣 Marketing View
![Marketing View](https://github.com/ADsaint13/Business-Insights-360/blob/main/Marketing.png)

---

### 🚚 Supply Chain View
![Supply Chain View](https://github.com/ADsaint13/Business-Insights-360/blob/main/Supply%20chain%20View.png)

---

### 👔 Executive View
![Executive View](https://github.com/ADsaint13/Business-Insights-360/blob/main/Executive%20View.png)

 



