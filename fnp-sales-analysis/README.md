FNP Sales Analysis – Excel & Power Pivot Dashboard
This project is an end‑to‑end sales analytics dashboard for FNP (Ferns N Petals), built entirely in Microsoft Excel using Power Pivot for the data model and PivotCharts for visualization. The aim is to translate raw order data into clear insights and business recommendations for a gifting e‑commerce business.

1. Business Understanding
Before touching the data, I focused on understanding the business problem and expectations:

Business context: Online gifting platform selling products for occasions such as Anniversary, Birthday, Diwali, Holi, Raksha Bandhan, and Valentine’s Day.

Main objective: Identify which occasions, products, months, cities, and weekdays drive orders and revenue, and how delivery performance impacts customer experience.

Key questions:

Which occasions and products generate the most revenue?

How does revenue vary by month and weekday?

Which cities contribute the most orders?

What is the average delivery time and customer spending per order?

Deliverable: A single Excel dashboard that summarizes KPIs, trends, and actionable business recommendations.

2. Data Extraction
Extracted raw order data from the source file into Excel.

Brought in all relevant tables (orders, products, occasions, cities) needed for analysis.

Ensured each table had clear column names and appropriate data types for further processing.

3. Data Cleaning and Transformation
Checked for missing values, inconsistent occasion names, and incorrect date formats; corrected or removed problematic records where necessary.

Standardized categorical values (e.g., occasion labels, product names, city names) for consistency.

Created calculated columns:

Delivery Days = Delivery Date – Order Date

Customer Spending per order (order value)

Verified basic statistics (min/max/average) to ensure the data looked reasonable before modeling.

4. Data Modeling with Power Pivot
Loaded cleaned tables into the Excel Data Model using Power Pivot.

Defined relationships between tables (e.g., Orders linked to Products, Occasions, and Cities using keys).

Created DAX measures for core KPIs:

Total Revenue

Total Orders

Average Delivery Days

Average Customer Spending per order

Used these measures to power all PivotTables and PivotCharts so the dashboard remains dynamic and consistent.

5. Analysis
Using the Power Pivot model and PivotTables:

Segmented revenue by occasion, product category, month, weekday, and city.

Identified top 10 cities by order volume and top 5 products by revenue.

Analyzed monthly revenue trends to understand seasonality and festival‑driven spikes.

Evaluated delivery performance and average customer spending to gauge operational efficiency and customer value.

6. Dashboard Design (Excel)
Built a single‑page dashboard in Excel with:

KPI cards:

1000 Total Orders

₹35,20,984 Total Revenue

5.53 Average Delivery Days

₹3,520.98 Average Customer Spending per order

Visuals:

Revenue by Occasion

Revenue by Product

Revenue by Months

Top 10 Cities by Orders

Revenue by Weekday

Top 5 Products by Revenue

Interactive controls:

Occasion slicer to filter the entire dashboard by a specific event (e.g., Anniversary, Diwali).

Everything is created with PivotTables, PivotCharts, slicers, and Power Pivot measures inside Excel, without any external BI tools.

7. Key Insights
High‑revenue occasions (e.g., Birthdays and Anniversaries) are major drivers of sales and should be prioritized for campaigns.

Soft Toys and curated gift sets are among the top revenue‑generating products.

Revenue shows clear peaks around certain months, indicating strong seasonality aligned with festivals and celebrations.

Orders and revenue are concentrated in a limited set of cities, offering opportunities for city‑focused strategies.

Average delivery time of about 5–6 days suggests room to improve logistics to enhance customer satisfaction.

8. Business Recommendations
Based on the insights, the following recommendations are proposed:

Occasion strategy

Focus marketing efforts on high‑performing occasions (Birthdays, Anniversaries) with personalized campaigns and bundles.

Design special offers around key festivals (Diwali, Holi, Raksha Bandhan, Valentine’s Day) to leverage seasonal demand and increase average order value.

Product optimization

Promote top‑performing products (Soft Toys, high‑revenue gift sets) more prominently on the website, app, and ads.

Review and improve low‑performing products through redesign, price adjustments, or bundling, based on their revenue contribution.

City‑level focus

Use top‑city insights to run localized campaigns and partnerships, prioritizing high‑volume locations for faster delivery and better service.

Explore regional warehousing or logistics partnerships in core cities to reduce delivery days and support same‑day/next‑day delivery options.

Timing and promotions

Align major promotions with high‑revenue months and weekdays to maximize conversion.

Introduce time‑bound offers like “order today for delivery by X day” to improve predictability and customer trust.

Delivery and customer value

Optimize operational processes and courier SLAs to bring average delivery days down and improve customer experience.

Use upsell recommendations (add‑on products, premium packaging) to lift average order value beyond ₹3,520 per order.
