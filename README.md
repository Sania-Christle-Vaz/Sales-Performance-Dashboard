Sales Performance Dashboard

Overview
The Sales Performance Dashboard is an analytical tool designed to evaluate and visualize the sales performance of a global vehicle manufacturer over the course of a year. The dashboard allows users to analyze key metrics such as total sales, revenue, pricing strategies, customer concentration, and regional performance. The insights derived from this analysis can help optimize sales, enhance pricing strategies, and improve inventory management, ensuring the company can make more informed, data-driven decisions to boost profitability and market presence.

Objective
Purpose: To analyze sales performance and uncover actionable insights for better decision-making.

Key Goals:

Optimize sales performance and pricing strategies.

Mitigate risks such as revenue concentration and inconsistent pricing.

Enhance inventory management and customer base diversification.

Data Preparation
Data Source: The data was sourced from the Kaggle Sales Dataset.

Data Cleaning & Processing:

Standardized data formats (e.g., currency).

Removed unnecessary columns.

Ensured data consistency before exporting it to Power BI.

Limitations:

The dataset lacks profit data, which would have provided deeper insights into the company’s financial performance.

Features
The dashboard consists of the following key components:

KPI Cards:

Displays metrics like Total Sales, Total Quantity Ordered, and Average Price for overall sales performance.

Product Line Slicer:

Allows filtering by product line for focused analysis.

Sales Trend (Line Chart):

Shows sales performance over time.

Insight: December sales drop, likely due to holidays and supply chain issues. A suggestion for mitigation is implementing on-demand inventory for December.

Sales by Region (Map):

Visualizes sales performance across different countries.

Insight: USA leads in sales, followed by Spain.

Price Sensitivity by Order Quantity (Scatter Plot):

Analyzes price fluctuations relative to order quantity.

Insight: Inconsistent pricing strategy indicates the need for better pricing consistency.

Top Customers Revenue Concentration (Bar Chart):

Visualizes customer contribution to total sales.

Insight: A few customers contribute heavily to revenue, representing a revenue concentration risk.

Deal Size Breakdown:

Shows the distribution of small and medium-sized deals.

Data Validation
DAX Functions were used to calculate and validate KPIs such as Total Sales and Price per Product (Efficiency Ratio) to ensure accuracy and consistency in data analysis.

Key Insights
Revenue Concentration Risk:

The business is highly dependent on a small number of customers. For example, the USA contributes 36.16% of total customers, and 15% of sales come from just 2 customers, posing a revenue concentration risk.

Inconsistent Pricing Strategy:

The pricing strategy is inconsistent, requiring a more structured and effective approach to pricing to ensure uniformity and profitability.

Seasonality Impact:

December sales consistently underperform due to holidays and supply chain disruptions.

Recommendation: Implement on-demand inventory for December to mitigate the impact of these seasonal factors.

Missing Profit Data:

The absence of profit data in the dataset limits the ability to analyze the true financial performance of the business, highlighting the importance of including profit figures for more accurate assessments.

Tools and Technologies Used
Power BI: Used for creating interactive visualizations and reports.

Kaggle Sales Dataset: The data source for this analysis.

DAX: Used for creating calculations and validating key metrics.

Excel: Used for initial data cleaning and exporting to Power BI.

Conclusion
Conclusion
The Sales Performance Dashboard provides a comprehensive view of the company's sales data, highlighting key performance indicators and potential areas for improvement. By using this dashboard, the company can make informed decisions to enhance its sales strategy, improve customer diversification, and optimize pricing and inventory management practices.

How to Use
Load the provided dataset into Power BI.

Use the KPI cards to quickly view key sales metrics.

Use the Product Line Slicer to filter data by specific product categories.

Visualize trends and performance in various regions using the Sales by Region map.

Dive deeper into pricing and customer data to identify areas of improvement.
