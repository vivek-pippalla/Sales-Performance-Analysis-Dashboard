# Sales-Performance-Analysis-Dashboard
A comprehensive end-to-end data analytics project that explores sales trends, product performance, regional profitability, and discount impacts using Python, Power BI, and SQL. This dashboard provides business decision-makers with key insights and actionable intelligence.
# Features
* EDA with Python
* Interactive Dashboard with Power BI
* SQL Integration & Query Design
* Streamlit Web App
* KPIs like Total Profit, Average Profit Margin
* Monthly Sales Trend, Profit by Region, Top Categories
 # Technologies Used
* Python (Pandas, Plotly, Streamlit)
* Power BI
* MySQL
* Excel
* SQL
* Jupyter Notebook / VS Code

# Dashboard Highlights

   * Total Profit and Avg. Profit Margin shown as KPI cards

   * Monthly Sales Trend using line chart

   * Profit by Region using bar/map visuals

   * Top Categories by Profit

   * Slicers for filtering by Region, Segment, Category

   * Answers critical business questions like:

         “Which region is underperforming?”

         “How do discounts impact profit?”

# Streamlit Dashboard

Run the Streamlit app with:

    "streamlit run app.py"

Make sure the cleaned_superstore_data.csv and powerbi_dashboard.png are in the same directory.

# SQL Insights (MySQL)

Sample Queries:

Top 5 Profitable States:

    SELECT State, SUM(Profit) AS TotalProfit
    FROM sales_data
    GROUP BY State
    ORDER BY TotalProfit DESC
    LIMIT 5;

Average Profit by Segment:

    SELECT Segment, AVG(Profit) AS AvgProfit
    FROM sales_data
    GROUP BY Segment;
  
# To Stand Out
  * Integrated MySQL data import using LOAD DATA INFILE

  * Cleaned currency & percentage values programmatically

  * Export-ready dashboard for recruiters or client demos
