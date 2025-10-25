Superstore Analytics Dashboard (Tableau)

An interactive Tableau dashboard built using the Superstore dataset, designed to analyze Sales, Profit, Customer, and Shipping trends.  
This project demonstrates end-to-end data visualization, business analysis, and dashboard design skills — ideal for portfolio or interview presentation.

Project Overview

This dashboard provides a comprehensive performance view of Superstore operations across multiple business dimensions.

Key Objectives:
- Visualize Sales and Profit trends across time, region, and category.
- Identify top-performing customers and products.
- Analyze shipping cost efficiency and its impact on profit.
- Provide actionable insights for business stakeholders through interactivity and drill-down capabilities.

Features

| Feature | Description |
|----------|--------------|
| KPI Overview Cards | Displays total Sales, Profit, Profit Ratio, and Avg Shipping Cost. |
| Sales Trend (YoY Growth) | Line chart showing monthly sales with year-over-year comparison. |
| Profit by Region (Map) | Geographic analysis with interactive filtering. |
| Category & Sub-Category Analysis | Stacked bar chart showing sales and profit contribution. |
| Top N Customers | Parameter-driven chart to view top customers by profit. |
| Profit vs Shipping Cost | Scatter plot highlighting efficiency and outliers. |
| Dynamic Filters & Actions | Region, Category, Segment filters + highlight actions. |

Key Calculations Used

| Metric | Formula | Description |
|--------|----------|-------------|
| Profit Ratio | `SUM([Profit]) / SUM([Sales])` | Profitability measure |
| Customer Lifetime Value (LTV) | `SUM([Sales])` | Total sales per customer |
| Customer Rank | `RANK_DENSE(SUM([Profit]))` | Ranking customers by profit |
| YoY Sales Growth | `(SUM([Sales]) - LOOKUP(SUM([Sales]), -12)) / LOOKUP(SUM([Sales]), -12)` | Year-over-year % growth |
| Avg Shipping Cost | `SUM([Shipping Cost]) / COUNT([Order ID])` | Average cost per order |


- Calculated Fields & Parameters
- Table Calculations (YoY Growth, Rank)
- Interactive Dashboards (Filter & Highlight Actions)
- Performance Optimization Techniques
- Dashboard Design Best Practices

---

https://public.tableau.com/app/profile/sabareeshwari.kumar/viz/SuperstoreSalesProfitPerformanceDashboard_17613984198340/Dashboard3

 🗺️ Dashboard Layout

