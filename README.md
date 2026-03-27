# Created by: David Callaghan
# Creation date: 3/27/2026
Sample dataset provided by Leila Gharani
https://www.youtube.com/watch?v=c7LrqSxjJQQ

📊 Sales Performance Dashboard (Power BI)

📌 Overview
This project is an interactive Power BI dashboard designed to analyze sales performance using transactional invoice data and customer master data.
The dashboard provides a comprehensive view of:
Sales trends over time
Category-level performance
Geographic distribution of sales
Year-over-year growth and cumulative performance
It demonstrates core data analytics skills including data modeling, DAX calculations, and business insight generation.

🎯 Business Problem
The dashboard answers the key question:
How is sales performance trending across time, categories, and regions, and where are the strongest growth opportunities?
This enables stakeholders to:
Monitor overall revenue performance
Identify high-performing product categories
Track seasonal trends and demand fluctuations
Evaluate regional sales distribution
📂 Dataset
Type: Sales / Transactional Data
Sources:
Invoice-level transaction data
Customer master data
Key Fields:
Sales amount
Quantity sold
Date (month/year)
Product category
Customer location (province)

🧰 Tools & Technologies
Power BI Desktop
Power Query (ETL & Data Cleaning)
DAX (Data Analysis Expressions)
Data Modeling (Relational Schema)
🔄 Data Preparation & Modeling
Key steps performed:
Cleaned and structured invoice-level data
Joined customer master data for geographic analysis
Created relationships between fact and dimension tables
Built calculated measures for:
Total Sales
Year-over-Year (YoY %) Growth
Year-to-Date (YTD) Sales
Total Quantity Sold

📊 Dashboard Features
1. Sales by Category
Horizontal bar chart showing total sales by category
Quickly identifies top-performing segments
Example insight:
Novelty Shop significantly outperforms other categories
2. Monthly Sales Performance Table
Displays:
Total Sales
YoY % Growth
YTD Sales accumulation
Enables detailed time-series analysis
3. Sales by Province (Geographic Map)
Visualizes regional distribution of sales
Highlights geographic concentration and market coverage
Supports regional strategy decisions
4. Monthly Quantity Trend (Line Chart)
Tracks total quantity sold over time
Identifies seasonality and demand spikes
5. Year Slicer (Interactive Filter)
Allows users to:
View all years
Drill into a specific year (e.g., 2019)
Enables dynamic, self-service analysis

📈 Key Insights
Total annual sales exceed $50M, indicating strong overall performance
Peak sales periods occur mid-year and toward year-end
Certain months show slower growth or slight decline (e.g., early-year variability)
One category dominates revenue contribution, suggesting:
Potential over-reliance
Opportunity for diversification
Sales are geographically concentrated, indicating potential expansion opportunities

💡 Lessons Learned (From Project & Tutorial)
1. Structuring Data is Critical
Building a clean data model with proper relationships is essential for accurate reporting and performance.
2. DAX Enables Advanced Analytics
Custom measures like YoY % and YTD transform raw data into meaningful business insights.
3. Design Drives Usability
Clear layout and hierarchy improve readability
Combining visuals (chart + table + map) provides a holistic view
4. Interactivity Adds Value
Slicers allow users to explore data without needing technical knowledge.
5. Focus on Business Questions
The most effective dashboards are built around decision-making, not just visualization.

🚀 How to Use
Open the .pbix file in Power BI Desktop
Use the Year slicer to filter data
Explore:
Category performance
Monthly trends
Regional sales distribution
Review YoY % and YTD metrics for deeper insights

📤 Sharing & Deployment
Publish to Power BI Service for stakeholder access
Export to PDF for reporting
Embed in business presentations
📚 Future Enhancements
Add profit and margin analysis
Introduce customer segmentation (e.g., high-value customers)
Implement drill-through pages for deeper analysis
Add forecasting models for predictive insights
