# 🛒 Vrinda / Shiv General Store — Annual Sales Analysis (2022)

> An end-to-end Excel-based data analysis project exploring sales trends, customer demographics, and channel performance for a multi-platform Indian retail store.

---

## 📌 Project Overview

This project performs a full-year sales analysis for **Shiv General Store** (also referred to as Vrinda Store) — a retail business selling ethnic and western apparel across major Indian e-commerce platforms. The dataset covers **31,000+ orders placed throughout 2022**, cleaned and analysed entirely in Microsoft Excel.

The goal was to answer key business questions that help the store understand **who their customers are**, **where they shop from**, and **which sales channels drive the most revenue** — so the business can make smarter decisions in 2023.

---

## 🗂️ Dataset Summary

| Field | Details |
|---|---|
| **Source** | Internal store order data |
| **Period** | January 2022 – December 2022 |
| **Records** | 31,047 rows |
| **Columns** | 21 (Order ID, Customer ID, Gender, Age, Age Group, Date, Month, Status, Channel, SKU, Category, Size, Qty, Amount, Ship City, Ship State, Pincode, Country, B2B flag) |
| **Tool Used** | Microsoft Excel (Pivot Tables, Charts, Formulas, Dashboard) |

---

## ❓ Business Questions Answered

1. Which month had the highest sales and order volume?
2. Who buys more — men or women?
3. What are the top-performing states by revenue?
4. What is the age group contributing most to purchases?
5. Which sales channels (Amazon, Myntra, Flipkart, etc.) drive the most orders?
6. What is the order fulfillment rate? How many orders were cancelled or returned?
7. What product categories and sizes are most popular?

---

## 🔍 Key Insights

### 📅 Monthly Trends
- **March** recorded the highest revenue (₹19.3 lakh), followed closely by February and January.
- Sales dipped in **November and December** — unusual for retail, suggesting limited festive-season participation.
- Order count was relatively stable across the year (~2,400–2,800 orders/month).

### 👩 Gender Split
- **Women account for 64% of total orders** and ~64% of total revenue (₹1.36 Cr vs ₹0.76 Cr for men).
- Women in the **Adult (30–49) age group** are the single largest revenue-generating segment.

### 📍 Top States by Revenue
| State | Revenue |
|---|---|
| Maharashtra | ₹29.9 lakh |
| Karnataka | ₹26.5 lakh |
| Uttar Pradesh | ₹21.0 lakh |
| Telangana | ₹17.1 lakh |
| Tamil Nadu | ₹16.8 lakh |

These 5 states together account for ~53% of total revenue.

### 🛍️ Sales Channels
| Channel | Revenue Share |
|---|---|
| Amazon | ₹75.2 lakh (~35.5%) |
| Myntra | ₹49.4 lakh (~23.3%) |
| Flipkart | ₹45.7 lakh (~21.6%) |
| Ajio | ₹13.3 lakh |
| Others (Nalli, Meesho) | ~₹19 lakh |

**Amazon alone drives more than 1/3rd of all revenue.**

### 📦 Order Status
- **92.3% of orders were successfully delivered** — a strong fulfillment rate.
- Cancelled: 2.7% | Returned: 3.4% | Refunded: 1.7%

### 👗 Product Categories
- **Sets** (12,391 orders) and **Kurtas** (10,446 orders) dominate — together forming ~73% of all orders.
- Western Dress (4,066) is a distant third.

---

## 📊 Dashboard Features

The Excel workbook contains the following sheets:

| Sheet | Description |
|---|---|
| `Vrinda Store` | Raw data (31,047 rows, all 21 columns) |
| `Vrindra Report 2025` | Main dashboard with charts and summary |
| `Sales Vs Order` | Pivot: monthly order count vs revenue |
| `Men vs Women` | Pivot: gender-wise revenue comparison |
| `Order Status` | Pivot: breakdown of delivery, returns, cancellations |
| `Sheet5` | Pivot: state-wise revenue ranking |

---

## 🛠️ Skills & Techniques Used

- **Data Cleaning**: Standardised date formats, derived `Month` using `TEXT()` formula, categorised age into groups using nested `IF()` formulas
- **Feature Engineering**: Created `Age Group` column (Teenager / Adult / Senior) from raw `Age` data
- **Pivot Tables**: Used for all aggregations — monthly trends, gender split, channel comparison, state-wise breakdown
- **Excel Charts**: Bar charts, line charts, pie charts visualising each business question
- **Dashboard Design**: Combined multiple pivot charts into a single summary dashboard tab

---

## 💡 Business Recommendations

Based on the analysis:

1. **Target women aged 30–49** — they are the dominant customer segment. Marketing campaigns should focus on this cohort.
2. **Prioritise Maharashtra, Karnataka, and Uttar Pradesh** — these states offer the highest revenue opportunity.
3. **Double down on Amazon and Myntra** — together they account for ~59% of revenue. Inventory and promotions on these platforms should be optimised.
4. **Investigate Nov–Dec dip** — sales fall in Q4, which is counter-intuitive for retail. This could indicate missed festive season opportunities (Diwali, Christmas).
5. **Expand Kurta and Set range** — these categories drive the majority of volume and should be the focus of new SKU launches.

---

## 📁 Project Structure

```
Vrinda_General_Store_Data_Analysis.xlsx
│
├── Vrinda Store             ← Raw data
├── Vrindra Report 2025      ← Final dashboard
├── Sales Vs Order           ← Monthly trend pivot
├── Men vs Women             ← Gender analysis pivot
├── Order Status             ← Fulfillment pivot
└── Sheet5                   ← State-wise pivot
```

---

## 🚀 How to Run / Explore

1. Download the `.xlsx` file from this repository.
2. Open in **Microsoft Excel** (2016 or later recommended).
3. Navigate to the `Vrindra Report 2025` sheet to view the dashboard.
4. Use slicers/filters (if enabled) to explore data by month, channel, or category.
5. The `Vrinda Store` sheet contains all raw data for custom pivot exploration.

---

## 👤 About

This project is part of my **Data Analyst portfolio**, demonstrating proficiency in:
- Data cleaning and transformation in Excel
- Business-oriented exploratory data analysis
- Dashboard creation and data storytelling
- Deriving actionable insights from raw transactional data

**Tools**: Microsoft Excel · Pivot Tables · Excel Charts · DAX (Power Pivot optional)

---

## 📬 Connect

If you found this useful or have suggestions, feel free to connect with me on [LinkedIn](#) or raise an issue in this repository.
