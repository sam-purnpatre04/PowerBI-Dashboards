# 📊 Marketing Campaign Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Power BI dashboard** developed as part of the **Sharpener Mini Project – Marketing Campaign Analysis**. The objective was to analyze the performance of marketing campaigns across different regions and campaign types, helping businesses evaluate campaign effectiveness using key performance indicators (KPIs) such as **Revenue, Spend, ROI, Impressions, Clicks, and Conversions**.

The dashboard enables users to compare campaign performance, identify high-performing marketing strategies, and gain actionable business insights through interactive visualizations.

---

## 🎯 Problem Statement

As a **Marketing Analyst**, the goal was to study how different marketing campaigns performed across various regions and marketing platforms such as:

- Digital Marketing
- Social Media Marketing
- Search Engine Advertising
- Email Marketing
- Influencer Marketing
- Traditional Marketing

The dashboard provides a comprehensive analysis of campaign performance by comparing spending, revenue generation, and return on investment (ROI).

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- CSV Files
- Data Cleaning & Transformation

---

## 📂 Dataset

The project uses the following datasets:

- **Marketing_Campaign_Details.csv**
- **Marketing_Campaign_Performance.csv**
- **Region_Performance.csv**

These datasets include campaign information, performance metrics, and regional details used for building relationships and creating interactive visualizations.

---

# 🚀 Project Tasks

## ✅ Task 1 – Data Preparation

Performed data cleaning and preprocessing using Power Query.

### Activities Performed

- Imported all three CSV datasets into Power BI
- Renamed columns for better readability
- Removed duplicate records
- Handled missing values
- Corrected data types
- Cleaned and transformed data for analysis

---

## ✅ Task 2 – Data Modeling

Created relationships between the datasets to enable efficient reporting.

### Relationships Created

- **Marketing_Campaign_Performance → Marketing_Campaign_Details**
  - Key: Campaign Name
  - Relationship: One-to-Many

- **Marketing_Campaign_Performance → Region_Performance**
  - Key: Region
  - Relationship: One-to-Many

This data model allows seamless cross-table analysis and interactive filtering.

---

## ✅ Task 3 – DAX Measures

Created the following DAX measures for business analysis:

- Total Impressions
- Total Clicks
- Total Conversions
- Total Revenue
- Total Spend
- Total ROI
- Average ROI
- Best Campaign

These measures were used to calculate business KPIs and drive dashboard insights.

---

## ✅ Task 4 – Dashboard Development

Designed an interactive Power BI dashboard following modern dashboard design principles.

### Dashboard Components

### KPI Cards

- Total Revenue
- Total Spend
- Average ROI
- Best Performing Campaign

### Charts

- Stacked Column Chart – Total Spend vs Total Revenue by Region
- Combo Chart – Total Spend and Average ROI by Campaign
- Bar Chart – Total ROI by Campaign
- Pie Chart – Campaign Count by Campaign Type
- Gauge Chart – Total ROI vs Average ROI

### Interactive Filters

- Region
- Campaign Type

---

## 📈 Dashboard Features

- Interactive filtering using slicers
- KPI summary cards
- Campaign-wise ROI comparison
- Region-wise revenue analysis
- Marketing spend analysis
- Campaign type distribution
- Business-focused visual storytelling
- Clean and professional dashboard layout

---

## 💡 Business Insights

Based on the dashboard analysis:

- Influencer Marketing generated the highest ROI.
- Africa recorded the highest total revenue among all regions.
- South America showed comparatively lower campaign performance.
- Digital marketing campaigns delivered better overall ROI than traditional campaigns.
- Campaign performance varied significantly across different marketing channels.
- Interactive filters allow deeper regional and campaign-specific analysis.

---


## 🎯 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Power Query
- DAX Measures
- KPI Design
- Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Thinking
- Interactive Reporting

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Importing and cleaning multiple datasets
- Building relationships between tables
- Writing DAX measures for business KPIs
- Designing professional dashboards in Power BI
- Creating interactive reports using slicers and filters
- Presenting business insights through data visualization

---
