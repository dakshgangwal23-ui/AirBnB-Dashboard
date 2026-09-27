# 🏡 Airbnb Business Performance Dashboard

An end-to-end Power BI dashboard analyzing Airbnb-style booking data to 
deliver executive-level insights on revenue, occupancy, host performance, 
and property trends.

## 📊 Overview

This project simulates a real-world business intelligence use case: 
transforming raw booking data into a decision-ready dashboard for both 
leadership and operations teams.

**Live demo / Screenshots:** *(add link or embed screenshots here)*

## 📁 Dashboard Pages

### 1. Executive Overview
High-level KPIs for leadership, including:
- Total Revenue, Average Nightly Rate, Occupancy Rate, Avg Review Score, Cancellation Rate
- YoY comparison for each KPI
- Monthly revenue trend (2023–2026)
- Total bookings by neighbourhood and room type
- RevPAR vs Average Nightly Rate trend

### 2. Host & Property Performance
Operational deep-dive for host management, including:
- Bookings/revenue by property type
- Superhost vs Regular host comparison (bookings & revenue split)
- Avg Nightly Rate vs Review Score by property type (bubble chart)
- Drill-through: Neighbourhood → Room Type → Property Type
- Host performance leaderboard (bookings, revenue, avg revenue/booking)

## 💡 Key Insights

- Total revenue reached **$175.7M**, up **47.4% YoY**
- **Superhosts** account for only a portion of hosts but drive **71% of 
  bookings** and **69% of revenue ($122M)** — highlighting strong ROI on 
  Superhost incentive programs
- **Bronx, Crown Heights, and Harlem** lead booking volume by neighbourhood
- **Entire home/apt** listings account for 56% of bookings vs. 31% for 
  Private rooms
- Occupancy rate held steady (~50%) YoY despite revenue growth — 
  suggesting **pricing, not volume**, is the primary revenue driver
- **20% cancellation rate** flagged as an area for further root-cause analysis

## 🛠️ Tools & Techniques

- **Power BI** — report design, data modeling, DAX
- **DAX measures**: `SAMEPERIODLASTYEAR`, `CALCULATE`, `DIVIDE`, `SUM`
- Drill-through pages, bookmarks, dynamic slicers/filters
- Data cleaning and relationship modeling (star schema)

## 📂 Data Source

Sample/public Airbnb-style dataset used for demonstration purposes 
*(not real company data)*.

## 🚀 How to Use

1. Clone this repo
2. Open `airbnb_dashboard.pbix` in Power BI Desktop
3. Refresh data source if needed
4. Explore filters, slicers, and drill-through pages

## 📌 Future Improvements

- Add forecasting for revenue and occupancy
- Connect to a live/refreshable data source
- Add a guest sentiment/review analysis page
