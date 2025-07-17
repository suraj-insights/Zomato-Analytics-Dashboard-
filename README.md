# 🍽️ Zomato Analytics Dashboard - Power BI Project

## 📊 Project Overview

This project presents a comprehensive **Power BI analytics dashboard** for **Zomato**, a leading food delivery platform. The goal is to uncover key business insights by analyzing customer behavior, restaurant performance, sales trends, and cuisine popularity. 

The report is designed to help stakeholders make data-driven decisions that enhance **user engagement**, **operational efficiency**, and **sales growth**.

---

## 🎯 Problem Statement

Zomato required an interactive dashboard that answers the following key business questions:

- What are the **total sales** and **order volumes**?
- Which **cities and cuisines** contribute most to revenue?
- How do **demographics** (gender, age, occupation) affect spending?
- Are **restaurant ratings** correlated with sales performance?
- What are the **top-performing restaurants and food items**?

---

## 🧪 Dataset and Limitations

### Data Sources:
- Orders
- Users
- Restaurants
- Menu
- Food
- Order Type

### Limitations:
- Limited time range and static data (no real-time updates)
- Missing demographic fields and null values in ratings/sales
- No delivery time/distance or customer sentiment data
- Financial details like commission/profit margin not available

---

## 🔧 Data Preprocessing

- **Data Loading:** Imported and joined 6 datasets.
- **Data Modeling:** Built relationships between user, order, food, and restaurant tables.
- **Data Cleaning:** Removed duplicates, handled nulls, formatted dates and sales columns.
- **Feature Engineering:** Created age bins and cleaned occupation data for better analysis.

---

## 📈 Power BI Report Pages

### 📄 **Dashboard 1: Overview**
- KPIs: Total Sales, Orders, Avg. Order Value, Unique Users
- Visuals: Sales Trend, City-wise Sales, Order Type Distribution

![Dashboard1](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard1%20-%20overview.png)

---

### 🧑‍🤝‍🧑 **Dashboard 2: User Demographics**
- Visuals: Gender-wise sales, Age group performance, Occupation, Marital Status

![Dashboard2](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard2%20-%20User%20Demographics.png)

---

### 🍱 **Dashboard 3: Cuisine Analysis**
- Visuals: Top cuisines, Cuisine sales by city, Rating-based insights

![Dashboard3](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard3%20-%20Cuisine%20Analysis.png)

---

## 🧮 Key DAX Measures

| Measure Name       | Formula                                      |
|--------------------|----------------------------------------------|
| Total Sales        | `SUM(Orders[sales_amount])`                  |
| Total Orders       | `COUNTROWS(Orders)`                          |
| Avg. Order Value   | `DIVIDE([Total Sales], [Total Orders])`      |
| Total Users        | `DISTINCTCOUNT(Orders[user_id])`             |
| Total Quantity     | `SUM(Orders[sales_qty])`                     |

Additional measures:
- Sales by Gender, Age Group, Occupation, Cuisine, and City
- Time-based trend analysis using DAX time intelligence

---

## 🔍 Insights Summary

- **Total Sales:** ₹987 Million+  
- **Total Orders:** 150,000+
- **Top Cities:** Tirupati, Bangalore, Pune  
- **Top Cuisines:** North Indian, Chinese, Fast Food  
- **Demographic Trends:**
  - Males spend slightly more than females
  - Age group 25-35 generates the most revenue
  - Working professionals and students dominate the user base
- **Ratings Impact:** High-rated restaurants drive higher sales

---

## 📁 Resources

- 📄 [Full Report (PDF)](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Zomato%20Report.pdf)
- 🖼️ [Dashboard 1 - Overview](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard1%20-%20overview.png)  
- 🖼️ [Dashboard 2 - User Demographics](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard2%20-%20User%20Demographics.png)  
- 🖼️ [Dashboard 3 - Cuisine Analysis](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/Dashboard3%20-%20Cuisine%20Analysis.png)  
- 🖼️ [Logo](https://github.com/suraj-insights/Zomato-Analytics-Dashboard-/blob/40952d6fa05f698f9788981d2553605e0c09b8bf/zz.png)

---

## 👨‍💼 About the Author

**Suraj Patil**  
Business Analyst | Data Enthusiast | Power BI Developer  
📍 Pune, India  
📧 surajpatil@outlook.com  
🔗 [LinkedIn Profile](https://linkedin.com/in/thesurajpatil)

---

## 📌 Conclusion

This dashboard project highlights how food delivery data can be transformed into **actionable insights** using **Power BI**, allowing business stakeholders to make informed strategic decisions.

For feedback or collaboration, feel free to reach out!
