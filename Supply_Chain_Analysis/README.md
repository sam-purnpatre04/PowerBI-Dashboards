# 📊 Supply Chain Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Power BI dashboard** developed as part of the **Supply Chain Performance Analysis**. The objective was to analyze end-to-end supply chain operations, evaluate logistics efficiency, monitor inventory management, and assess supplier reliability using key performance indicators (KPIs) such as **Order Fulfillment Rate, Shipping Cost, Lead Time, On-Time Delivery %, Inventory Turnover, and Defect Rate**.

The dashboard enables operations managers and supply chain analysts to identify bottlenecks, optimize logistics costs, and improve overall operational efficiency through data-driven insights.

---

## 🎯 Problem Statement

As a **Supply Chain Analyst**, the goal was to evaluate operational performance across different product categories, transportation modes, and regional suppliers. Key focus areas include:

- Logistics & Carrier Performance
- Inventory & Warehousing Optimization
- Order Lead Time & On-Time Delivery Reliability
- Supplier Defect & Quality Control
- Shipping & Operational Cost Distribution

The dashboard provides a centralized view to track performance metrics, identify delays, and optimize overall supply chain costs.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- CSV Datasets
- Data Cleaning & Transformation

---


# 🚀 Project Tasks

## ✅ Task 1 – Data Preparation

Performed data cleaning and preprocessing using Power Query.

### Activities Performed

- Imported supply chain CSV files into Power BI
- Renamed columns to maintain standard business naming conventions
- Removed duplicate orders and missing tracking entries
- Handled null values in lead times and shipping costs
- Formatted date, numerical, and categorical data types
- Cleaned supplier and product classification fields

---

## ✅ Task 2 – Data Modeling

Created a relational star schema data model to link operational entities.

### Relationships Created

- **Orders_Performance → Product_Details**
  - Key: SKU / Product ID
  - Relationship: Many-to-One

- **Orders_Performance → Supplier_Performance**
  - Key: Supplier ID
  - Relationship: Many-to-One

- **Orders_Performance → Carrier_Logistics**
  - Key: Carrier ID / Route ID
  - Relationship: Many-to-One

This model facilitates dynamic cross-filtering between logistics, suppliers, and product performance metrics.

---

## ✅ Task 3 – DAX Measures

Created the following DAX measures for operational KPI calculation:

- Total Order Quantity
- Total Revenue
- Total Shipping Cost
- Average Lead Time (Days)
- On-Time Delivery Rate (%)
- Defect Rate (%)
- Order Fulfillment Rate (%)
- Inventory Turnover Ratio

These measures were utilized to drive summary metrics and custom visual logic.

---

## ✅ Task 4 – Dashboard Development

Designed an interactive, multi-section Power BI dashboard optimized for operational visibility.

### Dashboard Components

### KPI Cards

- Total Revenue
- Total Shipping Cost
- On-Time Delivery Rate (%)
- Average Order Lead Time

### Charts

- Stacked Bar Chart – Total Shipping Cost vs Revenue by Transportation Mode
- Line & Clustered Column Chart – Average Lead Time and On-Time Delivery Rate by Carrier
- Bar Chart – Defect Rate (%) by Supplier
- Donut Chart – Order Distribution by Product Category
- Gauge Chart – On-Time Delivery Rate vs Target (95%)

### Interactive Filters

- Product Category
- Transportation Mode (Air, Road, Rail, Sea)
- Supplier Location / Region

---

## 📈 Dashboard Features

- Interactive slicers for dynamic region and category filtering
- KPI summary visual metrics
- Supplier quality and defect analysis
- Carrier and logistics efficiency tracking
- Cost breakdown by shipping channel
- Clean, executive-ready dashboard UI design

---

## 💡 Business Insights

Based on the dashboard analysis:

- Air freight delivered the fastest lead times but incurred significantly higher shipping costs per unit.
- Road logistics maintained the highest volume of fulfillments, though minor delays occurred during peak routes.
- Select suppliers demonstrated higher defect rates, highlighting areas for vendor quality control interventions.
- Product categories with higher inventory turnover rates required tighter reorder point management to prevent stockouts.

---

## 🎯 Skills Demonstrated

- Data Cleaning & Preprocessing
- ETL Process via Power Query
- Relational Data Modeling
- Custom DAX Formulation
- KPI Card & Visual Hierarchy Design
- Operational Supply Chain Analytics
- Interactive Report & Slicer Configuration

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Cleaning and structuring operational supply chain datasets
- Modeling relationships between orders, carriers, and suppliers
- Formulating DAX calculations for logistics performance tracking
- Structuring analytical views tailored for supply chain and operations management
- Translating logistics metrics into actionable cost-reduction strategies
