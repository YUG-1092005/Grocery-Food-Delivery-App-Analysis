# 🛒 SwiftServe Grocery/Food Delivery Dashboard

**SwiftServe** is a dynamic and interactive **Microsoft Excel Dashboard** developed to analyze grocery mart performance metrics including sales, outlet efficiency, and item type trends. Designed for a fast delivery app, the dashboard empowers stakeholders to explore data through real-time slicer filters.

> 🚀 This is my **second data analysis dashboard** project using Microsoft Excel.

---

## 📌 Project Overview

This project provides a comprehensive visualization of key business metrics through a fully interactive dashboard.

🎯 **Key Features:**

- Real-time dynamic filters (slicers)
- Total sales analysis across outlets, locations, and item types
- Customer ratings and item sales performance
- Time-series trend for outlet establishment
- Sales distribution based on fat content and outlet size

**All metrics and visuals dynamically update based on selected filters**.

---

## 📷 Dashboard Preview

![image](https://github.com/user-attachments/assets/6861af63-610b-4309-bdfc-8d57153dec2c)


---

## 📊 Dynamic Metrics

All values change interactively when slicers are applied:

- **Total Sales:** ₹11.42 Lakhs (default view)
- **Average Sales per Transaction:** ₹141
- **Total Items:** 8098
- **Average Rating:** 4.0 stars

---

## 🔍 Insights Delivered

- 📈 Year-wise Outlet Establishment Trend (2011–2022)
- 🍽️ Sales by Item Types (e.g., Fruits, Snacks, Household)
- 🧈 Fat Content Distribution (Low Fat vs Regular)
- 🏬 Outlet Size Performance (Small, Medium, High)
- 🗺️ Location-wise Sales (Tier 1, Tier 2, Tier 3 Cities)
- 🛍️ Outlet Type Contribution (Grocery Store, Supermarkets)

All charts are responsive and interactive, giving deep insights based on user selections.

---

## 🧰 Tools & Technologies Used

- **Microsoft Excel** – Interactive dashboard development along with data cleaning and formatting
- **DAX (Data Analysis Expressions)** – Custom calculations and KPIs

---

## 🧮 Key DAX Measures

```DAX
Total Sales = SUM(Sales[Amount])
Average Sales = AVERAGE(Sales[Amount])
Total Items = COUNT(Sales[Item_ID])
Average Rating = AVERAGE(Customer[Rating])
