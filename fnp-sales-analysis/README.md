# FNP Sales Analysis – Excel & Power Pivot Project

This project delivers a sales analysis for **FNP (Ferns and Petals)**, an online gifting platform that serves occasions such as Diwali, Raksha Bandhan, Holi, Valentine’s Day, Birthdays, and Anniversaries. Using Microsoft Excel and Power Pivot, the analysis quantifies sales performance, customer behavior, and product effectiveness and consolidates the results in an interactive dashboard.

## Business Problem & Objectives

FNP aims to improve its sales strategy and customer satisfaction by understanding where revenue comes from, how customers behave, and how products perform across occasions and regions. The dataset includes orders, products, customers, and dates, and the objective is to transform this raw data into insights and clear business recommendations.

The analysis is structured around 10 key business questions:

1. **Total Revenue** – What is the overall revenue generated?  
2. **Average Order and Delivery Time** – How long do orders take to be delivered?  
3. **Monthly Sales Performance** – How do sales fluctuate across the months of 2023?  
4. **Top Products by Revenue** – Which products generate the most revenue?  
5. **Customer Spending Analysis** – How much do customers spend on average per order?  
6. **Sales Performance of Top 5 Products** – How do the top 5 products perform over time?  
7. **Top 10 Cities by Orders** – Which cities place the highest number of orders?  
8. **Order Quantity vs Delivery Time** – Does higher quantity impact delivery time?  
9. **Revenue by Occasion** – How does revenue differ across occasions?  
10. **Product Popularity by Occasion** – Which products are most popular for each occasion?

## Data & Tools

- **Data**: Order‑level dataset with products, occasions, customers, cities, order dates, delivery dates, quantities, and revenue.  
- **Tools**:  
  - Excel for data cleaning, transformation, PivotTables, PivotCharts, and dashboard layout.  
  - Power Pivot for the data model, relationships, DAX measures, and KPI definitions.

## Analytical Approach

1. **Business understanding**  
   - Clarified objectives around revenue, seasonal performance, customer value, delivery efficiency, and product/occasion mix.

2. **Data extraction and preparation**  
   - Imported raw tables into Excel and standardized fields (dates, occasion names, product categories, city names).  
   - Engineered features such as Delivery Days (delivery date minus order date), order quantity, and order value.

3. **Data modeling with Power Pivot**  
   - Loaded Orders, Products, Occasions, and Cities into the Excel Data Model.  
   - Defined relationships across tables and created DAX measures for Total Revenue, Total Orders, Average Delivery Days, Average Customer Spend, and product/occasion‑level metrics.

4. **Analysis**  
   - Segmented revenue and orders by occasion, product, month, weekday, and city to address the 10 business questions.  
   - Examined the relationship between order quantity and delivery days to test operational impact.

5. **Dashboard design**  
   - Constructed a one‑page Excel dashboard with KPI cards and visuals for:  
     - Total Orders and Total Revenue  
     - Average Delivery Days and Average Customer Spending  
     - Revenue by Occasion, Product, Month  
     - Top 10 Cities by Orders  
     - Revenue by Weekday  
     - Top 5 Products by Revenue  
   - Added an Occasion slicer to allow stakeholders to slice all views by specific events.

## Key Insights

1. **Total Revenue**  
   - Total revenue is approximately ₹35,20,984 across 1,000 orders, providing a clear baseline for performance.

2. **Average Order and Delivery Time**  
   - Average delivery time is around 5.53 days, indicating that standard fulfilment is closer to a week than same‑day or next‑day delivery.

3. **Monthly Sales Performance**  
   - Revenue fluctuates across months, with peaks aligning to major gifting and festival periods, confirming strong seasonality in demand.

4. **Top Products by Revenue**  
   - A small set of products (Soft Toys and specific gift sets such as Magnum Set, Entertainment Pack, Expedit Gift) contribute a disproportionately large share of revenue.

5. **Customer Spending Analysis**  
   - Average customer spending per order is about ₹3,520.98, highlighting mid‑ticket gifting behaviour with room for strategic upselling.

6. **Sales Performance of Top 5 Products**  
   - The top 5 products show consistent demand and strong revenue contribution, forming a core portfolio that drives a significant portion of overall sales.

7. **Top 10 Cities by Orders**  
   - Orders are concentrated in a defined set of cities, with the top 10 cities accounting for most of the volume, signalling where regional strategies and logistics investments will be most impactful.

8. **Order Quantity vs Delivery Time**  
   - Higher order quantities do not appear to cause extreme delays, but variability in delivery days suggests further opportunity to stabilize operational performance.

9. **Revenue by Occasion**  
   - Personal occasions (Birthdays, Anniversaries) and certain major festivals drive higher revenue than other events, making occasion mix a key lever for growth.

10. **Product Popularity by Occasion**  
    - Product preferences vary by occasion, with specific product types and bundles strongly associated with particular events, indicating clear occasion–product alignment.

## Business Recommendations

1. **Occasion strategy**  
   - Prioritize marketing and campaign planning around high‑revenue occasions (Birthdays, Anniversaries, key festivals) to capture demand peaks and maximize ROI.  
   - Design occasion‑specific bundles and landing pages that mirror product popularity patterns for each event.

2. **Product portfolio and merchandising**  
   - Treat top‑performing products and gift sets as anchor items and position them prominently across website, app, and paid channels.  
   - Review low‑revenue SKUs and consider redesign, bundling, or discount strategies to improve performance or simplify the catalog.

3. **Customer value and upsell**  
   - Use the current average spend (~₹3,520) as a benchmark and introduce structured upsell flows (add‑on products, premium packaging, personalized cards) to lift average order value.  
   - Explore loyalty programs or subscription‑style gifting plans for high‑value customers around recurring occasions.

4. **Regional and city‑level optimization**  
   - Focus logistics and service improvements on top‑volume cities, where reductions in delivery time and enhanced reliability will impact the largest share of orders.  
   - Run city‑specific promotions or partnerships in these markets to deepen penetration and brand presence.

5. **Operational efficiency and delivery**  
   - Use the 5.53‑day average delivery metric as a baseline and set targets for reducing delivery time, especially for key occasions and priority cities.  
   - Monitor the relationship between order quantity and delivery performance to identify and address process bottlenecks early.

6. **Seasonality and calendar planning**  
   - Align inventory, staffing, and marketing calendars with observed monthly and occasion‑level demand peaks to ensure capacity is available when needed.  
   - Pre‑launch targeted campaigns ahead of high‑demand months to capture intent early and smooth fulfilment workloads.

## How to Use This Project

- Open the Excel file in a version that supports Power Pivot.  
- Refresh the Data Model to ensure relationships and measures are available.  
- Use the Occasion slicer and other filters to explore how KPIs and charts change across occasions, products, months, weekdays, and cities.  
- Apply the insights and recommendations to inform marketing, product, and operations decisions.
