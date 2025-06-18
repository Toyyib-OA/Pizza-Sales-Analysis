# Pizza-Sales-Analysis
A data-driven analysis of pizza sales exploring customer behavior, top products, and time-based trends. Insights support strategic decisions in marketing, inventory, and menu planning. Cleaned and analyzed using Excel, this project highlights key metrics to optimize business performance.
# 🍕 Pizza Sales Analysis Report
![Screenshot 2025-06-18 134131](https://github.com/user-attachments/assets/5d236688-dfdd-4e7f-b614-5a4fd3f8574e)

**Prepared by:** Toyyib Adewuyi



---

## 📌 Introduction

This report presents a structured analysis of our pizza sales data, highlighting key performance indicators, product trends, and customer behavior patterns. The goal is to distill actionable insights from the numbers — identifying what sells most, when demand peaks, and which categories contribute most significantly to revenue.

---

## 🎯 Objectives

- Analyze overall sales performance (revenue, order volume, quantity sold)
- Identify high-performing products by popularity and profitability
- Discover sales trends by day and time
- Evaluate pizza category and size contributions
- Support decisions in inventory, promotions, and menu planning

---

## 🧭 Scope

The analysis includes all recorded transactions with details on:

- Product type
- Quantity sold
- Sales value
- Order timing
- Size and category preferences

> **Note:** External influences like marketing or demographics are not covered — the focus is internal sales performance.

---

## 🗃️ Dataset Overview

**Source:** Scraped from a pizza company database  
**Size:** 48,621 rows × 12 columns

### 🔑 Key Columns

| Column        | Description |
|---------------|-------------|
| `Order ID`    | Unique transaction identifier |
| `Pizza Name`  | Full name of pizza sold |
| `Category`    | Classic, Supreme, Veggie, etc. |
| `Size`        | S, M, L, XL |
| `Quantity`    | Units sold |
| `Total Price` | Revenue per line item |
| `Order Date`  | Date of order |
| `Day Name`    | Weekday derived from order date |
| `Order Time`  | Time order was placed |
| `Day Time`    | Grouped into Morning, Afternoon, Evening |

---

## 🧹 Data Cleaning Process

- **Missing Values:** `=COUNTBLANK()` function used
- **Duplicates:** None found using Excel’s Remove Duplicates
- **Data Types:** Ensured numeric & text columns are correctly typed
- **New Columns Generated:**
  - `Day Name`: via `=TEXT(Order Date, "dddd")`
  - `Day Time`: based on order time

**✅ Final Cleaned Dataset:** 48,621 rows × 14 columns

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Sales Performance Overview

- **Total Sales:** \$817,860.05  
- **Average Pizza Price:** \$16  
- **Total Pizzas Sold:** 49,574  

---

### 2. Top Performing Products

- **Most Popular (Quantity):** Classic Deluxe Pizza  
- **Most Profitable (Revenue):** Thai Chicken Pizza

---

### 3. Category & Size Trends

- **Top Category:** Classic  
- **Most Ordered Size:** Large (L)

---

### 4. Time-Based Insights

- **Busiest Day:** Friday  
- **Peak Time:** Afternoon  

---

### 5. Seasonal Sales Trends (2015)

- **Peak Months:** January & November  
- **Low Months:** September & December  

---

## 💡 Key Insights

- **Strong Revenue:** \$817K+ across 21,000+ orders
- **Customer Favorites:** 
  - *Classic Deluxe* by volume
  - *Thai Chicken* by value
- **Demand Concentration:** 
  - Classics dominate
  - Large sizes preferred
- **Peak Times:** 
  - Fridays & afternoons see the most sales
- **Seasonal Patterns:** 
  - Jan & Nov peak
  - Sep & Dec slump

---

## ✅ Recommendations

- **Promotions:** Focus on Fridays & afternoons
- **Highlight Hits:** Feature Classic Deluxe & Thai Chicken
- **Inventory Prep:** Stock for Classic & Large pizzas
- **Menu Simplification:** Review/remix low-performers (Greek, Calabrese, Alfredo)
- **Time-Based Offers:** Morning/midweek discounts
- **Expand Classics:** Add nostalgic or familiar variants
- **Seasonal Campaigns:** Boost low-demand months with themed deals

---

## 🧾 Conclusion

The analysis reveals customer behavior trends:  
Classics and large sizes dominate.  
Fridays and afternoons are busiest.  
January and November outperform, while September and December lag.

These patterns guide better promotional timing, stock planning, and menu design.

---

## ⚠️ Limitations & Future Work

- Lacks customer-level data (demographics, preferences)
- **Next Steps:**
  - Integrate customer feedback and profiles
  - Enable targeted marketing and personalization

---
