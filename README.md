# Pizza-Sales-Dashboard

1. Project Title / Headline
🍕 Slice of Success: Global Pizza Sales Insights Dashboard
A dynamic Power BI solution designed to transform raw transaction data into actionable business intelligence—focusing on revenue optimization, peak-hour performance, and inventory management through menu popularity.

2. Short Description / Purpose
The Pizza Sales Report is a comprehensive analytical tool that provides a 360-degree view of retail performance over a 12-month period. Its primary purpose is to help restaurant stakeholders identify volume trends, recognize high-value customer preferences (by pizza size and category), and pinpoint underperforming menu items to drive strategic operational improvements.

3. Tech Stack
📊 Power BI Desktop – Used for building the end-to-end interactive dashboard and UI/UX design.

📂 SQL / Power Query – Utilized for data cleaning, handling missing values, and standardizing date/time formats for time-series analysis.

🧠 DAX (Data Analysis Expressions) – Implemented for complex measures including Average Order Value, Total Revenue, and rolling growth metrics.

📝 Data Modeling – Star schema architecture connecting transactional sales data with pizza categories and sizing dictionaries.

4. Data Source
Source: Retail Transactional Database (Dataset containing ~21,350 orders and 49,500+ individual pizza sales).
Attributes: The dataset includes Order IDs, Pizza Names, Categories (Classic, Supreme, Veggie, Chicken), Sizes (S, M, L, XL, XXL), Unit Prices, and timestamps (Date/Time).

5. Features / Highlights
• Business Problem
-Restaurant managers often struggle to balance inventory and staffing because they lack visibility into:
-Peak Periods: Which days and hours require more staff?
-Menu Fatigue: Which pizzas are not selling and should be removed or rebranded?
-Customer Value: Are customers buying premium pizzas or opting for budget-friendly sizes?

• Goal of the Dashboard
To deliver an interactive visual tool that enables managers to:
Track the Average Order Value (AOV) to measure marketing effectiveness.
Identify Best and Worst Sellers to optimize kitchen prep and inventory.
Analyze Seasonal Trends (Monthly/Daily) to forecast sales accurately.

• Walkthrough of Key Visuals
Executive KPIs (Top Header): Real-time tracking of Total Revenue ($817.86K), Total Orders (21,350), and Average Pizzas per Order (2).
Busiest Days & Times (Bar/Line Charts): Identifies that Friday and Saturday evenings are peak windows, allowing for better staff scheduling.
Sales by Category & Size (Donut Charts): Visualizes that the "Classic" category and "Large" size pizzas contribute the highest percentage to total revenue.
Inventory Optimization (Funnel Chart): Shows the volume distribution across different pizza categories to streamline supply chain orders.
Top/Bottom 5 Sellers (Ranking Visuals): A dedicated "Best/Worst Sellers" page that highlights the "Spicy Italian" as a top earner while identifying underperformers like the "Brie Carre" pizza.

• Business Impact & Insights
Operational Efficiency: Identified Friday/Saturday as high-traffic days, suggesting that prep work should be increased by 20% on those mornings.
Menu Engineering: Recommendations to bundle "Bottom 5" pizzas with high-margin "Classic" pizzas to clear slow-moving inventory.
Revenue Growth: By analyzing the AOV ($38.31), the business can implement "upsell" triggers for orders slightly below the average.
