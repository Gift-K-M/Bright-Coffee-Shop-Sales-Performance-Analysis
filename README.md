# Bright-Coffee-Shop-Sales-Performance-Analysis

**Objective**

This repository contains analysis of transactional sales data from Bright Coffee Shop, focusing on uncovering store performance trends. 
The main objective is to help stakeholders understand which store locations perform best by revenue, product mix, and time-based patterns.

## 📊 Analytical Structure

1. **Data Cleaning & Preparation**
   - Cleaned CSV loaded into Snowflake
   - Null checks and formatting
   - Derived fields: `hour_bucket`, `time_of_day`, `day_of_week`, `month`, `total_amount`

2. **Store-Level Analysis**
   - Revenue grouped by `store_location`
   - Trends broken down by `time_of_day`, `hour`, `day_of_week`, and `month`
   - Top N filters applied to focus on highest-impact segments

3. **Export for Dashboarding**
   - Final flat table: `bright_sales_analysis`
   - CSV exported for Excel pivot tables and charts

## 📈 Insights Delivered

- 🔺 **Top-performing stores** by total revenue and units sold  
- 🕒 **Peak sales hours** and time-of-day trends per store  
- 📦 **Best-selling product types and categories** by store location  
- 🗓️ **Day-of-week and monthly performance patterns** for each store  
- 🎯 **Recommendations** on staffing, inventory, and local promotions


## 🛠 Tools Used

- **Snowflake & PostgreSQL** – Data processing and transformation  
- **Excel** – Pivot tables and chart-based dashboards  
- **Miro** – Initial planning and architecture diagram  
- **PowerPoint / Canva** – Final presentation for executive stakeholders  
