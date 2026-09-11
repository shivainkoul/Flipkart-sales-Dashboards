# Flipkart Sales Analysis Dashboard

## 1. Project Title
Flipkart Sales Analysis Dashboard

## 2. Short Description
A Power BI dashboard analyzing **Flipkart sales performance** across India. It covers profit, orders, category-wise amount, payment mode distribution, monthly profit vs sales trends, geographic spread of customers, and top-performing states and sub-categories — with a city-level filter for deeper drill-down.

## 3. Tech Stack
- Excel (data cleaning & pivot tables)
- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- .pbix / .png

## 4. Data Source & Pipeline
**Source:** Flipkart sales dataset (Kaggle, CSV)

**Workflow:**
1. Dataset downloaded from Kaggle as a `.csv` file
2. Cleaned and pre-processed in Excel (removing inconsistencies, formatting fields)
3. Built pivot tables in Excel to validate category, state, and payment mode summaries
4. Imported the cleaned data into Power BI for modeling and visualization
5. Used DAX to create calculated columns/measures for profit, order counts, and category-level metrics

Order-level fields include:
- Location (City, State)
- Category & Sub-Category
- Payment Mode
- Order Date, Amount, Profit
- Customer details

## 5. Highlights

### i. Business Problem
With orders spread across 25 cities and 19 states, Flipkart needed a clear way to identify **where sales and profit are concentrated**, which categories and sub-categories drive profitability, and how customers pay — to guide regional and category-level business decisions.

### ii. Goal of the Dashboard
- Track overall orders, profit, and payment mode diversity at a glance
- Compare profit and sales trends on a monthly basis
- Identify top-performing states by customer count
- Highlight the most profitable sub-categories
- Understand customer and payment mode distribution across categories
- Enable filtering by city for localized analysis

### iii. Key Visuals

**KPI Overview**
- 25 Total Cities
- 37K Sum of Profit
- 1.5K Total Orders
- 5 Payment Modes
- 19 Total States

**Amount by Category**
- Bar chart comparing total amount across product categories (Furniture, Clothing, Electronics)

**Monthly Distribution of Profit vs Sales**
- Combined area/line chart tracking Sum of Profit and Sum of Amount month-over-month, showing a general decline before a late spike

**Geo Distribution**
- Map of India highlighting concentration of orders across cities/states

**Order by Payment Mode**
- Donut chart: UPI (20%), COD (20%), EMI (20%), Credit Card (20%), Debit Card (20%) — evenly split across 5 payment modes

**Customer by Category**
- Pie chart: Furniture (33.33%), Clothing (33.33%), Electronics (33.33%)

**Top 10 States by Customer**
- Treemap led by Maharashtra and Madhya Pradesh, followed by Rajasthan, Gujarat, Uttar Pradesh, Punjab, Delhi, Karnataka, West Bengal, Bihar, and Kerala

**Top 5 Profitable Sub-Category**
- Printers, Bookcases, Saree, Accessories, and Tables ranked by profit contribution

**Filters**
- City (dropdown, default "All")

### iv. Business Impact
- Pinpoints high-performing states and cities for targeted regional strategy
- Identifies most profitable sub-categories to prioritize in inventory and promotions
- Shows balanced payment mode adoption, useful for payment partnership decisions
- Tracks profit vs sales trend to flag months needing intervention
- Supports category-level decisions using customer distribution insights

## 6. Screenshots

### i. Overview Dashboard
KPI summary, category/payment mode breakdown, monthly profit vs sales trend, geo distribution, top states, and top profitable sub-categories.

<img width="603" height="370" alt="Flipkart Sales Dashboard - Overview" src="https://github.com/shivainkoul/Flipkart-sales-Dashboards/blob/main/Snapshot%20of%20dashboard.png" />
