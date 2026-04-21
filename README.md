# Food Delivery Market Analysis — Swiggy Dataset
**Tech Stack:** Microsoft Excel (Pivot Tables, Power Query, Dashboard Design, KPI Analysis, Data Cleaning)

## Business Problem
Food delivery platforms struggle to balance demand, workforce allocation, and customer satisfaction across multiple cities and categories. Without clear visibility into sales patterns and customer preferences, marketing spend and logistics remain inefficient.
**This project analyzes 197K+ Swiggy food delivery records to surface actionable insights across revenue, demand, geography, and customer behavior.**  

## Objectives
- Track total sales, orders, and revenue KPIs
- Identify top-performing cities and food categories
- Understand weekday vs weekend demand patterns
- Analyze Veg vs Non-Veg revenue split
- Evaluate customer satisfaction through ratings
- Support data-driven decisions for operations and marketing

## Dataset
- 197,430 food delivery records
- Fields: Orders, Cities/States, Food Categories, Ratings, Revenue
- Source: Swiggy public dataset (Kaggle)

## KPIs at a Glance
| Metric | Value |
|---|---|
| Total Sales | ₹53.01M |
| Total Orders | 197,430 |
| Average Order Value | ₹268.51 |
| Average Rating | 4.3 / 5 |
| Rating Count | 5.59 (avg per order) |


## Approach
### 1. Data Preparation
- Cleaned raw dataset — handled missing and inconsistent values
- Structured data into analytical categories
- Created calculated fields: Month, Day of Week, Quarter, Order Metrics
 
### 2. Analysis Performed
- Monthly & weekly revenue trend analysis (Jan–Aug)
- Daily demand pattern analysis (Sun–Sat)
- Quarterly performance breakdown (Q1/Q2/Q3)
- City-wise and state-wise revenue comparison
- Food type split (Veg vs Non-Veg)
- Category-level performance analysis

### 3. Dashboard Development
Built a 4-tab interactive Excel dashboard:
- **Dashboard** — Main KPI overview with all visuals
- **Charts** — Supporting chart views
- **Analysis** — Pivot table analysis layer
- **Swiggy Data** — Raw/cleaned data source

## Key Insights
### Revenue & Trends
- Total revenue of ₹53.01M across 197K+ orders (Jan–Aug)
- Monthly sales stable between ₹6.3M–₹6.8M with slight growth toward Aug (₹6.8M peak)
- Q1: ₹19.7M | Q2: ₹19.9M | Q3: ₹13.4M (Q3 partial — 3 months only)
- Saturday is the highest revenue day at ₹7.8M; Tuesday lowest at ₹7.4M

### Customer Preferences
- Non-Veg orders drive 65% of total revenue (₹34.4M) vs Veg at 35% (₹18.7M)
- Average rating consistent at 4.3 across all quarters — indicating stable service quality

### Geographic Insights
- Bengaluru leads at ₹5.5M — nearly 2x the next city
- Top 5 cities: Bengaluru (₹5.5M), Lucknow (₹3.1M), Hyderabad (₹3.0M), Mumbai (₹3.0M), New Delhi (₹2.8M)
- Top 5 cities contribute ~36% of total revenue
- Karnataka is highest revenue state; Sikkim/Mizoram at lowest (~₹0.06M)

### Demand Patterns
- Weekend (Fri–Sat) consistently outperforms weekday orders
- Weekly trend shows steady demand across all 36 weeks with peaks around weeks 8–15

## Dashboard Preview
### Main Dashboard
Main Dashboard(images/Main_dashboard.png)

### Analysis View
Analysis View(images/Analysis_dashboard.png)

## Business Impact
| Area | Insight | Recommended Action |
|---|---|---|
| Workforce | Sat–Fri peak demand | Increase delivery staff on weekends |
| Marketing | Non-veg = 65% revenue | Prioritize non-veg promotions |
| Expansion | Bengaluru dominates | Replicate model in Hyderabad/Mumbai |
| Retention | Stable 4.3 rating | Maintain quality, target 4.5+ |
| Inventory | Category concentration | Stock top categories in peak cities |


## How to Use
1. Open 'Swiggy_Dashboard.xlsx' in Microsoft Excel
2. Navigate to the **Dashboard** tab for KPI overview
3. Use slicers (Month, Category, Restaurant Name) 
   to filter views
4. Visit **Analysis** tab for pivot-level breakdowns
5. Raw data available in **Swiggy Data** tab
