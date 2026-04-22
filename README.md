🚗 BMW Sales & Performance Dashboard

An end-to-end Business Intelligence project built with Power BI, covering data cleaning, data modeling, and interactive dashboard development to analyze BMW sales performance and profitability.

📁 Repository Structure
BMW-project/
│
├── 📂 Dashboard/           # Power BI report file (.pbix)
├── 📂 datamodeling/        # Data model, relationships, and DAX measures
├── 📂 uncleandData/        # Raw data before cleaning
├── 📄 README.md            # Project documentation
🎯 Project Overview

This project delivers a comprehensive BMW Sales & Performance Dashboard designed to analyze sales data and extract actionable insights. It follows the full BI lifecycle, starting from raw data to a fully interactive dashboard that supports data-driven decision-making.

The dashboard enables stakeholders to monitor performance, track KPIs, and explore trends across products, regions, and time periods.

🔄 Project Workflow
1. 🗃️ Data Collection & Exploration
Collected raw BMW sales data from multiple sources
Explored dataset structure and identified data quality issues
2. 🧹 Data Cleaning & Transformation
Handled missing values and duplicates
Standardized formats and column names
Applied transformations using Power Query (M Language)
3. 🔗 Data Modeling
Built a structured Star Schema
Created relationships between tables
Developed calculated columns and DAX measures
4. 📈 Dashboard Development
Designed an interactive Power BI dashboard
Added slicers, filters, and drill-through features
Created visuals for clear and effective storytelling
📌 Key Metrics & KPIs
KPI	Description
Total Sales	Total revenue generated
Total Profit	Net profit after costs
Profit Margin %	Profit relative to sales
Sales Growth	Performance over time
Top Models	Best-selling BMW models
Regional Performance	Sales by region
📊 Dashboard Features
Sales Overview — KPIs with trends
Profit Analysis — Margin insights
Product Performance — Top & low-performing models
Time Analysis — Monthly & yearly trends
Interactive Filters — Dynamic exploration
Drill-Through — Detailed analysis
🛠️ Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard & modeling
Power Query (M)	Data transformation
DAX	Measures & KPIs
Excel / CSV	Data source
Git & GitHub	Version control
💡 DAX Measures (Examples)
Total Sales = SUM(Sales[SalesAmount])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

YTD Sales = TOTALYTD([Total Sales], 'Date'[Date])

Sales PY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date]))
🚀 Getting Started
Prerequisites
Power BI Desktop
Steps
Clone the repository
git clone https://github.com/Salma-rar/BMW-project.git
Open .pbix file in Power BI
Explore dashboard and interact with filters
📂 Data Description
Folder	Description
uncleandData/	Raw dataset
datamodeling/	Data model & DAX
Dashboard/	Final dashboard
👩‍💻 Author

Salma Elhwary

GitHub: https://github.com/Salma-rar
📄 License

MIT License

Built with ❤️ using Power BI
