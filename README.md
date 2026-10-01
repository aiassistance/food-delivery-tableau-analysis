# 🍽️ Food Delivery Business Performance Analysis

## 📊 Project Overview

This project analyzes food delivery business performance using Tableau.

The dashboard focuses on revenue, orders, customer ratings, delivery time, discounts, food categories, cities, and monthly performance to identify useful business patterns.

## 🎯 Business Problem

A food delivery business wants to understand:

- Which food categories generate the most revenue?
- Which cities contribute the most revenue?
- How does delivery time vary across categories?
- Which categories receive higher customer ratings?
- How does revenue change over time?
- Is there a visible relationship between customer ratings and revenue?

## 🛠️ Tools & Skills

- Tableau
- Data Visualization
- Calculated Fields
- Filters
- Parameters
- Dashboard Design
- Data Cleaning
- Business Analysis

## 🧹 Data Cleaning

The dataset contained a category value with inconsistent capitalization (`pizza`).

A calculated field was created to standardize category names:

`Clean Category`

This ensured that Pizza records were grouped consistently during analysis.

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | ₹12,670 |
| Total Orders | 30 |
| Average Customer Rating | 4.33 |
| Average Delivery Time | 35.73 min |

## 📈 Analysis

### Revenue by Category

- Biryani: ₹5,600
- Pizza: ₹4,520
- Burger: ₹2,550

### Revenue by City

- Hyderabad: ₹5,120
- Bengaluru: ₹4,800
- Chennai: ₹2,750

### Average Rating by Category

- Biryani: 4.57
- Burger: 4.32
- Pizza: 4.01

### Average Delivery Time by Category

- Pizza: 41.60 minutes
- Burger: 37.38 minutes
- Biryani: 29.75 minutes

### Monthly Revenue

- January: ₹3,350
- February: ₹2,989
- March: ₹2,940
- April: ₹3,400

## 🔍 Key Insights

- Biryani generated the highest revenue among the three categories.
- Hyderabad generated the highest city-level revenue.
- Pizza had the highest average delivery time.
- Biryani had the highest average customer rating.
- Revenue decreased from January to March and recovered in April.
- The small sample does not show a clear relationship between customer rating and revenue.

## 💡 Business Recommendations

- Investigate why Pizza has a higher delivery time than other categories.
- Examine opportunities to increase revenue in Chennai.
- Continue monitoring Biryani performance because it contributes strongly to revenue.
- Analyze customer ratings together with other factors rather than treating ratings alone as a driver of revenue.
- Use a larger dataset before making major business decisions.

## 🖼️ Dashboard

![Food Delivery Business Performance Dashboard](dashboard.png)

## 📁 Project Files

- `dashboard.png` — Final Tableau dashboard
- `Food_Delivery_Business_Performance.twb` — Tableau workbook
- `food_delivery_data.txt` — Dataset used for the analysis

## 🎯 Objective

The objective of this project is to demonstrate practical skills in Tableau, data visualization, data cleaning, dashboard development, and business-oriented data analysis.
