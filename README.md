# Executive-Sales-Operations-Analytics-PowerBI
# 📊 Executive Sales & Operations Analytics Dashboard

An end-to-end, highly interactive Power BI dashboard designed to bridge the gap between complex data analysis and intuitive user experience (UI/UX). This project focuses on delivering actionable business insights for sales performance, customer behavior, product profitability, and logistics efficiency.

---

## 🎬 Project Demo
### 🎥 Watch the Project Walkthrough
[![Watch on LinkedIn](https://lnkd.in/p/ebJM8U9K)]

*Click the button above to watch the full interactive walkthrough video on LinkedIn.*
---

## 🎯 Project Overview & Objective

The main objective of this project is to build a complete analytical ecosystem that combines robust data modeling, advanced DAX measures, and modern executive UI/UX design principles. 

Key focuses include:
* **Visual Hierarchy & Styling:** Custom color palette, rounded container borders, soft shadows, and clean spatial alignment.
* **Seamless Navigation:** Header page navigator replacing default bottom tabs.
* **Interactive Tooltips & Drill-Throughs:** Providing context-driven detailed views on demand without cluttering the main dashboard canvas.
* **Custom Bookmarks & Selection Control:** Pop-up filter panel and quick reset buttons to optimize dashboard real estate.

---

## 📐 Report Architecture & Structure

The project consists of **3 main interactive report pages** supported by **2 utility pages** and a dedicated **Landing Page**:

### 🏠 0. Home / Landing Page
* Project metadata, introduction, personal links (LinkedIn / GitHub), and an `Explore Dashboard` call-to-action button.

### 📈 1. Executive & Sales Overview
* **High-Level KPIs:** Total Revenue, Total Profit, Total Orders, Profit Margin %, and Average Order Value.
* **Core Visuals:**
  * Quarterly Revenue vs. Order Volume trends.
  * Product category breakdown with **Drill-Down** support (Year $\rightarrow$ Quarter $\rightarrow$ Month $\rightarrow$ Day).
  * Sales Channel performance (Online vs. Store).
  * Regional distribution across major cities.
* **Interactive Features:**
  * **Pop-Up Filter Panel:** Collapsible slicer drawer using Bookmarks and Selection Pane (`Month`, `SalesChannel`, `SalesRegion`, `InvoiceStatus`).
  * **Reset Button:** One-click clear filter action (`Reset_Filters`).
  * **Q&A Visual:** Natural language query capability.

### 👥 2. Customers & Products
* **Key Metrics:** Total Revenue, Total Orders, Total Units Sold, Total Customers, and Average Discount %.
* **Core Visuals:**
  * Top 5 Customers by Revenue.
  * Revenue & Order Distribution by Customer Age Groups.
  * Orders by Customer Segment (Gold, Silver, Bronze) and Gender Breakdown.
  * Top Products by Volume Sold.
* **Interactive Features:**
  * **Report Page Tooltip (`Tooltip_CustomerSegmentDetails`):** Hovering over customer segments surfaces dynamic mini KPI cards and the top 3 customers for that segment on the fly.

### 🚚 3. Logistics & Operations
* **Key Metrics:** Total Orders, Average Delivery Days, Total Drivers, Delivered %, and Total Suppliers.
* **Core Visuals:**
  * Profitability & Volume by Employee / Sales Force performance.
  * Supplier Revenue contribution.
  * Delivery Company Performance (Volume & Late Delivery Rate %).
  * Delivery Status (Delivered vs. In Transit) and Warehouse Late Processing Rates.

### 🔎 4. Drill-Through Utility Page (`Category Overview`)
* A dedicated detail page accessible by right-clicking any category across the dashboard.
* Contains granular monthly profit trends, sales channel breakdown, brand performance, and an itemized product table.
* Features a built-in **Back Button** for fluid user experience.

---

## 🛠️ Tech Stack & Power BI Features Used

* **Business Intelligence Tool:** Power BI Desktop
* **Data Transformation:** Power Query (Data cleaning, type casting, custom columns)
* **Data Modeling:** Star Schema architecture (Fact table linked to Dimension tables)
* **Calculations:** Advanced DAX (Time Intelligence, Iterative aggregations, Dynamic KPIs)
* **UX/UI Components:**
  * Page Navigator
  * Report Page Tooltips
  * Drill-Through & Drill-Down Hierarchies
  * Selection Pane & Bookmarks (Pop-up Panels & Toggle States)
  * Native Q&A AI Visual
  * Custom Themes, Soft Containers & Shadows

---
### Contact
For any questions Contact via email **hagersalah.r39@gmail.com**.
