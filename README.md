# 🧭 SalesPulse: Power BI Sales Performance & YOY Analytics Dashboard

## 📊 Overview  
**SalesPulse** is an interactive **Power BI dashboard** designed to analyze and compare **2023 vs 2024 sales performance** across multiple dimensions such as products, cities, states, and customer segments.  
The dashboard delivers end-to-end **sales analytics, YOY comparison, KPI tracking, and target achievement monitoring**, enabling stakeholders to make informed, data-driven business decisions.

---

## 🚀 Key Features  

- **YOY Performance Comparison (2024 vs 2023)**  
  - Compare revenue, orders, quantity sold, and customer growth across years.  
  - Analyze trends at yearly, quarterly, and monthly levels using DAX time-intelligence.

- **KPI & Target Tracking**  
  - Tracks core KPIs: **Total Sales, Total Orders, Quantity Sold, Customer Count**.  
  - Implements a **Target Achievement Framework** with annual & quarterly goals, achieved vs pending metrics, and variance analysis.

- **Toolkit Page (Enhanced User Experience)**  
  - Dedicated **Toolkit Page** with slicers, bookmarks, navigation buttons, and dynamic filters.  
  - Improves dashboard usability and enables fast drill-down and ad-hoc analysis.

- **Customer & Category Insights**  
  - **Top 100 Customer Leaderboard** based on revenue and quantity sold.  
  - Performance breakdown by **product category, city, and state**.  
  - Identification of high-performing regions, products, and key customers.

- **Interactive Visuals**  
  - KPI cards, line charts, bar charts, donut charts, and map visuals.  
  - Dynamic filtering by year, quarter, category, location, and customer.

---

## 📂 Dataset Details  

The analysis is based on two structured CSV datasets:

- **Sales data 2023** – `Sales data 2023.csv`  
- **Sales data 2024** – `Sales data 2024.csv`  

**Combined Dataset Highlights:**  
- **Total Records:** 2,178+ sales transactions  
- **Years Covered:** 2023 and 2024  
- **Unique Customers:**  
  - 2023 → 509  
  - 2024 → 582  
- **Products:** 20 product IDs  
- **Product Categories:** 5  
- **Cities:** 10  
- **States:** 6  
- **Quarters:** Q1–Q4  

Core columns include:
- `order_id`, `customer_id`, `product_id`  
- `date` / `Date`  
- `city` / `City`, `state` / `State`  
- `product_category` / `Product_Category`  
- `sales` / `Sales`  
- `quantity_sold` / `Quantity_Sold`  
- `Quarter`  

---

## 🛠️ Tools & Technologies  

- **Power BI** – Data modeling, dashboard design, visualization  
- **DAX (Data Analysis Expressions)** – Custom measures, KPIs, YOY and time-intelligence calculations  
- **Power Query** – Data loading, cleaning, transformation  
- **Excel / CSV** – Source data preparation and storage  

---

## 📈 Analytics & KPIs  

SalesPulse computes and visualizes key business metrics, including:

- **Total Sales**  
- **Total Orders**  
- **Total Quantity Sold**  
- **Customer Count**  
- **YOY Growth % (2024 vs 2023)**  
- **Month-over-Month Trends**  
- **Category-wise and City-wise Sales Contribution**  
- **Top Customer Rankings (Top 100 customers)**  
- **Target vs Achieved Metrics** (annual & quarterly)

---

## ⚙️ How It Works  

1. **Data Import**  
   - Load `Sales data 2023.csv` and `Sales data 2024.csv` into Power BI.  

2. **Data Cleaning & Modeling**  
   - Standardize column names (city/city, state/State, etc.) and data types.  
   - Create relationships between fact tables and any supporting dimension tables (e.g., Date, Products, Customers).

3. **DAX Measures & Calculations**  
   - Create DAX measures for total sales, orders, quantity, YOY growth %, MoM trends, category share %, customer ranking, and target tracking.  

4. **Dashboard Design**  
   - Build multiple report pages:
     - **Overview / KPI Page**  
     - **YOY Comparison Page (2024 vs 2023)**  
     - **Category & Region Analysis Page**  
     - **Customer Insights / Top 100 Customers**  
     - **Toolkit Page** for navigation and advanced filtering  

5. **Publishing & Sharing**  
   - Publish the report to **Power BI Service** for access via web and mobile.  
   - Configure row-level filters and usage metrics if required.

---

## 📷 Dashboard Preview  

> *Add screenshots or GIFs from your Power BI report here (Overview Page, YOY Page, Toolkit Page, etc.)*

---

## 🧠 Skills Demonstrated  

- Power BI  
- DAX (Time Intelligence, Ranking, KPIs)  
- Data Modeling & Relationships  
- Data Cleaning & Transformation (Power Query)  
- YOY & Trend Analysis  
- KPI Development & Target Tracking  
- Dashboard Design & UX (Toolkit Page, navigation)  
- Business Intelligence & Storytelling with Data  
- Exploratory Data Analysis (EDA)  

---

## 👤 Author  
**Bhaskar Sri Gopi Pedamalli**  
💼 *Aspiring Data Analyst | Power BI Developer | Machine Learning Enthusiast*  

---

## 🏁 Project Impact  

SalesPulse transforms raw multi-year sales data into an intuitive, interactive BI solution that supports:  

- Faster and more accurate **performance monitoring**  
- Clear visibility into **YOY changes and target achievement**  
- Identification of **high-value customers, products, and regions**  
- **Data-driven decision-making** for planning, forecasting, and strategy.  

---
