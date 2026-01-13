# Ecommerce_PowerBi_Dashboard
This Power BI project is a comprehensive E-commerce Sales Dashboard designed to track and analyze key business performance metrics. It uses a modern, dark-themed aesthetic with a purple-to-blue gradient background, focusing on high-level KPIs and granular breakdowns of sales, profit, and customer behavior.
Here is a detailed breakdown of the project:

1. Key Performance Indicators (KPIs)
At the top of the dashboard, four high-level "card" visuals provide an immediate snapshot of the business's health:
•	Sum of Amount: 438K (Total Revenue)
•	Sum of Profit: 37K
•	Sum of Quantity: 6K (Total items sold)
•	Sum of Average: 121.014K (Likely average order value or a similar internal metric)

2. Visual Analysis Breakdown
The dashboard is divided into several sections to answer specific business questions:
•	Profitability Trends: A bar chart showing Sum of Profit by Month. It highlights seasonality, showing a significant dip in profit during the summer months (June/July) and a peak in November/December.
•	Product Performance: * Bar Chart: Displays Sum of Amount by Sub-Category, showing that "Printers" and "Saree" are the top revenue generators.
o	Donut Chart: Breaks down Sum of Quantity by Sub-Category to show which items move the most volume.
•	Customer & Geography:
o	Line Chart: Shows Sum of Amount by State, identifying Maharashtra and Madhya Pradesh as the leading regions for sales.
o	Horizontal Bar Chart: Lists the Top Customers by Amount, with "Harivansh" being the highest spender.
•	Operational Metrics: * Donut Chart: Analyzes Sum of Quantity by Payment Mode, indicating that "COD" (Cash on Delivery) and "UPI" are popular payment methods.
•	Slicers (Filters): On the right side, there is a Quarterly Slicer (Qtr 1–4), allowing the user to filter the entire report by specific time periods.

3. Data Structure (Backend)
Looking at the Data Pane on the far right, the project appears to be built using two main tables:
•	Details: Contains transactional data like Amount, Profit, Category, Payment Mode, and Sub-Category.
•	Orders: Contains logistical and customer data such as City, Customer Name, Order Date, and State.

4. Design & Tooling
•	Tool: Power BI Desktop.
•	Interactivity: The dashboard is built for "drill-through" and cross-filtering, meaning clicking on a specific state or category will update all other visuals.
•	Visual Style: High-contrast design using white text on dark backgrounds for readability, with consistent color coding for different categories.


