# Sales Performance & Business Intelligence Solution


## 📊 Project Overview

An end-to-end Business Intelligence solution developed in Microsoft Power BI to analyze sales, profitability, customers, products, stores, employees, marketing performance, promotions, and operational performance.

The project was designed around a set of business requirements from different stakeholder perspectives, transforming business questions into data preparation, analytical models, DAX measures, interactive dashboards, and decision-oriented insights.

The solution combines **data modeling, Power Query, DAX, time intelligence, KPI development, interactive visualization, drill-through analysis, and business intelligence storytelling**.

---

# 🎯 Business Objectives

The main objectives of the project were to:

* Monitor overall business and sales performance.
* Track revenue, cost, profitability, orders, and other key KPIs.
* Compare actual performance against targets.
* Analyze year-over-year performance and growth.
* Identify sales trends and performance drivers.
* Evaluate store and employee performance.
* Analyze product and subcategory demand.
* Understand customer and geographic performance.
* Evaluate marketing activity and customer engagement.
* Monitor promotions over time.
* Analyze scheduled delivery performance across different time horizons.
* Provide detailed drill-through analysis for deeper investigation.
* Create an interactive reporting environment for business decision-making.

---

# ❓ Business Questions

The dashboard was developed to answer business questions from multiple perspectives.

## Executive Management

* How is the business performing overall?
* What are the current revenue, cost, profit margin, and order levels?
* How does current performance compare with the previous year?
* Which KPIs are achieving their targets?
* Where are the largest performance gaps?
* How is business performance changing over time?

## Sales Management

* How are sales changing over time?
* Which stores contribute the most to sales?
* Which employees generate the strongest sales performance?
* Which products or subcategories have high or low demand?
* Which countries contribute most to sales?
* How does average order value change across the business?
* What areas require further investigation?

## Marketing

* How is marketing activity performing?
* How many clicks/engagements are being generated?
* How does marketing performance change across selected periods?
* How does the selected period compare with the previous year?
* How does performance change when different time ranges are selected?

## Promotions

* How many promotions are available during a selected month?
* Which promotions are active during a given period?
* How does promotion availability change over time?

## Operations & Delivery

* How many orders are scheduled for delivery within:

  * The next 1 week?
  * The next 15 days?
  * The next 1 month?
  * The next 6 months?
* How does the selected delivery horizon affect the number of scheduled orders?

## Detailed Analysis

* Which countries or business areas require deeper investigation?
* What additional information can be obtained through drill-through analysis?
* How do high-level KPIs translate into detailed operational performance?

---

# 🛠️ Tools & Technologies

### Business Intelligence

* Microsoft Power BI
* DAX
* Power Query
* Data Modeling
* Data Visualization

### Data & Analysis

* SQL
* MySQL
* Time Intelligence
* KPI Analysis
* Business Performance Analysis

### Design

* Figma

---

# 🔄 End-to-End Workflow

The project followed a complete Business Intelligence workflow:

```text
Business Requirements
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI & Target Development
        ↓
Interactive Dashboard Development
        ↓
Drill-through & Advanced Analysis
        ↓
Business Insights
```

---

# 🧹 Data Preparation

Power Query and data preparation techniques were used to transform the available data into analysis-ready structures.

The preparation process included:

* Reviewing the available datasets and fields.
* Preparing fields for analytical use.
* Transforming data types where required.
* Structuring data for business analysis.
* Preparing date-related structures for time-based analysis.
* Creating the required relationships between analytical entities.

---

# 🧩 Data Modeling

A structured Power BI data model was developed to support interactive analysis across multiple business dimensions.

The analytical model supports analysis across areas including:

* Sales
* Products
* Customers
* Stores
* Employees
* Countries
* Dates
* Marketing
* Promotions
* Deliveries

The model was designed to allow users to move from high-level business KPIs into detailed analytical views while maintaining consistent filtering and calculations.

---

# 📐 DAX & Analytical Logic

DAX was used to create the core analytical measures and dynamic functionality of the dashboard.

Key calculations and analytical functionality included:

* Revenue
* Cost
* Profitability
* Orders
* Average Order Value
* Return Rate
* Year-to-Date analysis
* Previous-Year analysis
* Year-over-Year comparisons
* Growth calculations
* Target values
* Variance analysis
* KPI achievement
* Dynamic KPI selection
* Dynamic time-period comparisons
* Delivery-horizon calculations
* Promotion analysis

Advanced DAX logic was also used to control filtering behavior and support interactive business scenarios.

---

# 📈 Dashboard Pages

## 1. Executive Overview

The executive page provides a high-level view of business performance.

It focuses on:

* Revenue
* Cost
* Profitability
* Orders
* Return Rate
* Target achievement
* Historical performance
* Business trends

<img width="1093" height="537" alt="Executive Dashboard" src="https://github.com/user-attachments/assets/6f4371de-e09e-45ce-afa0-9951998059d0" />


---

## 2. Sales Analysis

The sales analysis page provides a deeper view of sales performance across different business dimensions.

The analysis includes:

* Sales trends
* Store performance
* Employee performance
* Product performance
* Subcategory analysis
* Country performance
* Orders
* Average Order Value
* Demand analysis

<img width="1093" height="539" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/c6da57c6-e478-41dd-b531-43929adf976c" />


---

## 3. KPI & Target Analysis

The KPI analysis provides a structured view of business performance against assumed targets.

The page supports:

* Actual KPI performance
* Target performance
* Variance
* KPI achievement
* Dynamic KPI selection
* Performance monitoring

<img width="931" height="546" alt="KPI Analysis" src="https://github.com/user-attachments/assets/52169b2f-10f8-4e16-8a42-a4a588a3b6ee" />


---

## 4. Marketing Analysis

The marketing analysis focuses on marketing engagement and performance over selected periods.

The page supports:

* Marketing activity analysis
* Click analysis
* Time-range selection
* Previous-year comparison
* Dynamic period analysis

<img width="934" height="546" alt="Marketing Analysis" src="https://github.com/user-attachments/assets/3a2b46d1-4deb-40f3-a23b-40eb296bbc70" />


---

## 5. Operational & Delivery Analysis

Operational analysis was used to investigate scheduled deliveries across different future time horizons.

The analysis supports:

* Next 1 week
* Next 15 days
* Next 1 month
* Next 6 months

This allows management to understand upcoming delivery workload based on a selected reference date.

<img width="931" height="547" alt="Scheduled Orders" src="https://github.com/user-attachments/assets/c0cbc771-eeed-4c1d-b8c0-258c44e28703" />


---

## 6. Drill-through Analysis

Drill-through functionality was implemented to allow users to move from summarized information into more detailed analysis.

This creates a more interactive self-service BI experience and allows users to investigate specific business dimensions without overcrowding the main dashboard pages.

<img width="930" height="547" alt="Drillthrough" src="https://github.com/user-attachments/assets/a9855fa1-9f92-4b9e-8f26-7b375bc3e1b7" />


---

# ⚙️ Interactive Features

The dashboard incorporates several advanced Power BI features:

* Interactive slicers
* Dynamic KPI selection
* KPI target tracking
* Target vs. actual analysis
* Year-over-year analysis
* Time intelligence
* Dynamic time-period comparisons
* Drill-through pages
* Custom tooltips
* Dynamic filtering
* Disconnected tables
* Delivery-horizon analysis
* Promotion monitoring
* Interactive dashboard navigation

---

# 📊 Key Analytical Capabilities

The project demonstrates the ability to move beyond basic dashboard creation by connecting business requirements with analytical logic.

The solution covers the complete process of:

**Business Question → Data → Transformation → Data Model → DAX → Visualization → Analysis → Decision Support**

---

# 💡 Business Value

The solution provides stakeholders with an interactive environment for monitoring performance and investigating business drivers.

Instead of relying on static reports, users can:

* Monitor KPIs dynamically.
* Compare performance across periods.
* Investigate underperforming areas.
* Analyze sales across multiple dimensions.
* Examine marketing activity.
* Monitor promotions.
* Assess upcoming delivery workload.
* Drill into detailed business information.

This supports faster and more informed data-driven decision-making.

---

# 📸 Dashboard Preview

Additional dashboard screenshots are available in the [`Screenshots`](Screenshots/) folder.

The complete Power BI `.pbix` source file is not included in this repository because of GitHub's file-size limitations. The source file is available upon request.

---

# 📁 Repository Structure

```text
Sales-Performance-Business-Intelligence/
│
├── README.md
│
├── Screenshots/
│   ├── Executive Dashboard.png
│   ├── Sales Dashboard.png
│   ├── KPI Analysis.png
│   ├── Marketing Analysis.png
│   ├── %of Continent.png
│   ├── Promotions.png
│   ├── Scheduled Orders.png
│   ├── Top Category.png
│   ├── Sales Trend Tooltip.png
│   ├── KPI Vs Target.png
│   ├── KPI Vs Target Tooltip.png
│   └── Drillthrough.png
│ 
└── Documentation/
    └── Business_Questions.md
```

---

# 🔗 Related Links

**LinkedIn Project Post:**
https://lnkd.in/p/d4GRfQyi

**GitHub Profile:**
https://github.com/sophiamaher7

---

# 👩‍💻 Author

**Sophia Maher Gerges**

Economics Graduate | Data Analytics | Business Intelligence

GitHub: https://github.com/sophiamaher7

