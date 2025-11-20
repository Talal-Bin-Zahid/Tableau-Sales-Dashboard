# 📊 Tableau-Sales-Dashboard

<img width="999" height="550" alt="Screenshot 2025-11-21 023021" src="https://github.com/user-attachments/assets/c9f3225b-e11d-4761-8b70-7403253a7a46" />

## 1. Project Overview & Goal

This project analyzes last fiscal year’s sales performance using an interactive Tableau dashboard. It helps answer key questions such as:

* **Top-selling products & subcategories**
* **Regional sales & profit performance**
* **Customer segment contribution**
* **Monthly trends in sales, profit, and quantity**
* **Identification of high-value or low-margin areas**

---

## 2. Data Sources & Preparation

### **Datasets**

* `Orders.csv` – Sales transactions
* `Products.csv` – Product details
* `Customers.csv` – Customer attributes
* `Location.csv` – Regional mapping

### **Key Fields**

* **Sales Data:** Order ID, Order Date, Sales Amount, Quantity Sold, Discount, Profit
* **Customer Data:** Customer ID, Segment, Region
* **Product Data:** Product Category, Subcategory
* **Geo Fields:** Region, State, Market

### **Preparation Steps**

* Joined Orders ↔ Products ↔ Customers ↔ Location
* Cleaned missing values in Region & Segment
* Standardized dates, added Month/Quarter/Year
* Aggregated daily → monthly for trend visuals
* Created calculated fields (Profit Margin, YoY Growth)

---

## 3. Business Parameters & KPIs

### **Core KPIs**

* **Total Sales**
* **Total Profit**
* **Quantity Sold**
* **Profit Margin (%)**
* **YoY Growth**
* **Average Order Value (AOV)**
* **Sales & Profit by Subcategory**
* **Trend Metrics (Monthly Sales/Profit/Quantity)**

These metrics highlight revenue health, product profitability, customer value, and overall growth direction.

---

## 4. Dashboard Features & Usage

### **Main Dashboard Views**

* **Executive Summary**
* **Product Deep Dive**
* **Customer Analysis**
* **Geographic Analysis**
* **Trend Explorer**

### **Interactive Features**

* Filters: Date Range, Region, Segment, Category
* Drill-down actions on product hierarchy
* Hover tooltips for detail-level insights
* Highlighting & cross-filtering across charts

---

## 5. Key Insights & Recommendations

* **Prioritize high-growth regions** showing strong YoY performance.
* **Address low-margin subcategories**—adjust pricing or vendor terms.
* **Upsell high-value customer segments** with targeted campaigns.
* **Investigate negative-profit items** for discount or return issues.
* **Use seasonal spikes** (e.g., Q4) for better stocking & forecasting.

---

## 6. Technical Details & Future Enhancements

### **Tools Used**

* Tableau Desktop (with optional Tableau Public/Server)
* CSV/Excel data sources

### **Future Enhancements**

* Add **Budget vs. Actuals** comparison
* Integrate **Predictive Forecasting** (Tableau, Python, or R)
* Incorporate **Customer Lifetime Value (CLV)**
* Enable **automated data refresh** with a live database connection


