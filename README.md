Problem Statement
This Power BI dashboard provides an in-depth analysis of Amazon sales data. It helps in understanding sales trends, customer behavior, and product performance. Through various metrics such as revenue, order volume, customer satisfaction, and product category performance, stakeholders can identify growth opportunities, optimize inventory, and enhance customer experience.

The dashboard also highlights key insights such as best-selling products, peak sales periods, and customer preferences. This data-driven approach allows Amazon to improve its marketing strategies and operational efficiency.

Steps Followed
Step 1: Load the sales dataset (CSV format) into Power BI Desktop.

Step 2: Open Power Query Editor and enable "Column Distribution," "Column Quality," and "Column Profile" options.

Step 3: Set "Column Profiling Based on Entire Dataset" for a comprehensive view.

Step 4: Identify missing values and inconsistencies in columns like "Order Date" and "Review Score."

Step 5: Handle missing values in relevant columns by replacing or removing them.

Step 6: Apply transformations such as splitting date-time columns, standardizing category names, and converting data types.

Step 7: Apply data modeling by establishing relationships between key entities like "Orders," "Customers," and "Products."

Step 8: Select a theme in the report view for consistent visual presentation.

Step 9: Use slicers to filter data by "Product Category," "Region," "Sales Channel," and "Customer Segment."

Step 10: Add KPI cards displaying total revenue, total orders, and average order value.

Step 11: Create a bar chart to show top-selling products based on sales volume.

Step 12: Use a line chart to visualize monthly sales trends.

Step 13: Use a pie chart to display the distribution of sales across different regions.

Step 14: Implement DAX measures for advanced calculations such as:

Total Revenue = SUM(Amazon_Sales[Sales Amount])

Total Orders = COUNT(Amazon_Sales[Order ID])

Average Order Value = DIVIDE([Total Revenue], [Total Orders])
Step 15: Add customer satisfaction analysis using review scores and sentiment classification.

Step 16: Create a heatmap showing peak sales hours and days.

Step 17: Publish the report to Power BI Service for sharing and collaboration.

Insights from the Dashboard
[1] Sales Performance
Total Revenue: $XX million
Total Orders: XX,XXX
Average Order Value: $XX.XX
Best-Selling Product Category: Electronics (XX% of total sales)
Worst-Performing Category: Office Supplies
[2] Sales Trends
Highest Sales Month: November (Due to Black Friday & Cyber Monday)
Lowest Sales Month: February
Peak Sales Hours: 6 PM - 10 PM
[3] Customer Analysis
Returning Customers: XX%
New Customers: XX%
Highest Revenue Generating Region: North America
Customer Satisfaction: Average rating XX/5
[4] Inventory Insights
Top Out-of-Stock Products: XYZ
Products with High Return Rates: XYZ
Best Performing Warehouse: XYZ
Conclusion
The Amazon Sales Analysis dashboard provides valuable insights into revenue trends, customer behavior, and product performance. With data-driven decisions, Amazon can optimize inventory, enhance customer satisfaction, and increase overall profitability.
