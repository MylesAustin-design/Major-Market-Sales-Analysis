Major Market Sales Analysis - Power BI Dashboard
📊 A Data-Driven Business Intelligence Dashboard for Major Market Sales Analysis

🚀 Project Overview
This project delivers an interactive Power BI dashboard to analyze sales trends, customer growth, product performance, and retention across multiple store locations. The end-to-end data pipeline leverages Visual Studio (SSIS), SQL Server, and Power BI for efficient ETL processing and business intelligence reporting.

🔹 Key Features
Total & Max Sales Insights - Track total revenue and highest transaction values.
Customer Growth Analysis - Understand unique customers and retention trends.
Sales Activity by Store Location - Compare performance across different cities.
Product Growth Trends - Identify top-selling products and revenue patterns.
Time-Series Analysis - Track sales performance over time.
Interactive Filtering - Drill down into specific regions and time periods.
🔄 ETL Process: Extract, Transform, Load
The project follows a structured ETL workflow using SQL Server and Visual Studio (SSIS).

1️⃣ Extract
Data was extracted from multiple source files and external databases.
SQL Server Integration Services (SSIS) in Visual Studio was used as a data transfer tool to bring in data from flat files, APIs, and external databases into SQL Server.
2️⃣ Transform
Transformations were performed using SQL Server Management Studio (SSMS) and SSIS Data Flow tasks:
Cleaning and filtering data (removing duplicates, handling null values).
Creating calculated fields (Customer Growth MoM, Moving Average Sales, Retention Rate).
Aggregating sales by store location and time periods.
3️⃣ Load
The processed data was loaded into SQL Server tables.
Power BI was connected to SQL Server via Direct Query mode for real-time updates.
DAX calculations in Power BI were used to refine KPIs.
🖥️ Tech Stack
SQL Server - Data storage, transformations, and aggregations.
Visual Studio (SSIS) - Automating ETL processes and moving data into SQL Server.
Power BI - Data visualization and interactive reports.
GitHub Pages - Hosting project documentation.
📈 Power BI Dashboard Overview
The final Power BI dashboard includes:

KPIs - Total Sales, Max Sales, Customer Growth, and Retention.
Charts & Graphs - Line charts, bar charts, pie charts, and trend analysis.
Interactive Filters - Allows filtering by store location and product category.
Live Dashboard Link
🔗 Embed Power BI Report (Insert link when published)

🔗 Repository Structure
bash
Copy
Edit
/major-market-sales-analysis
│── /SQL_Scripts          # SQL Queries for transformations
│── /SSIS_ETL             # SSIS packages for data transfer
│── /PowerBI_Dashboard    # Power BI PBIX file
│── /Visuals              # Dashboard Screenshots
│── index.html            # GitHub Pages (optional)
│── README.md             # Project Documentation
📌 How to Use
Clone this repository:
bash
Copy
Edit
git clone https://github.com/yourusername/major-market-sales-analysis.git
Open SQL Server Management Studio (SSMS) and run the provided ETL scripts.
Open Visual Studio (SSIS) and deploy the ETL package for data processing.
Open Power BI and connect to the SQL Server database.
Publish the Power BI report and embed it in a web application.
📩 Contact & Feedback
