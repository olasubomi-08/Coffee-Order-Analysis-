# ☕ Coffee Order Analysis — Power BI Dashboard

An interactive Power BI dashboard analyzing coffee order transactions to surface revenue trends, customer behavior, and product performance across markets.

## 📊 Overview

This project analyzes **1,000 coffee orders** placed between **January 2019 and August 2022**, across **3 markets** (United States, Ireland, United Kingdom), covering **4 coffee types** (Arabica, Robusta, Liberica, Excelsa) in **3 roast levels**, (Light, Medium, Dark).

The dashboard was built to answer questions like:
- Which countries and coffee types drive the most revenue?
- How does revenue trend over time?
- How does customer loyalty (Loyalty Card membership) relate to purchasing patterns?
- What's the overall order volume, revenue, and profit picture at a glance?

## 🗂️ Data Model

The dataset is structured as three related tables:

| Table | Description | Rows |
|---|---|---|
| `orders` | Transaction-level order data (Order ID, Date, Customer ID, Product ID, Quantity) | 1,000 |
| `customers` | Customer details (ID, location, loyalty status) | 1,000 |
| `products` | Product catalog (Coffee Type, Roast Type, Size, Unit Price, Profit) | 48 |

Relationships were built between `orders` → `customers` (via Customer ID) and `orders` → `products` (via Product ID), enabling cross-table analysis in Power BI.

## 📈 Dashboard Features

The report page includes:

- **KPI cards** — Total Revenue, Total Orders, Total Customers, and Profit at a glance
- **Revenue by Country** (column chart) — compares performance across the US, Ireland, and UK
- **Revenue by Roast Type** (donut chart) — Light vs. Medium vs. Dark roast contribution
- **Revenue by Coffee Type** (clustered column chart) — Arabica, Robusta, Liberica, Excelsa comparison
- **Revenue Trend by Month** (line chart) — seasonality and growth over the order history
- **Customers by Coffee Type** (bar chart) — which coffee types attract the most customers
- **Slicers** — filter the entire report by Year and by Loyalty Card status

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query** — data shaping and table relationships
- **DAX** — creating measures and performing calculations for revenue, orders, customers, and profit
- **Excel** — source data preparation

## 📁 Repository Contents

```
├── Coffee_Order_Analysis.pbix   # Power BI dashboard file
├── Coffee-Order-Data.xlsx       # Source data (orders, customers, products)
├── screenshots/                 # Dashboard preview images
└── README.md
```

## 🚀 How to View

**Option 1 — Download and open:**
Option 1 — Power BI Dashboard
Download the Coffee_Order_Analysis.pbix file from this repository.
Open the file using Power BI Desktop to explore the interactive dashboard.

**Option 2 — Dashboard Screenshots**
Screenshots of the dashboard are available in the screenshots/ folder for a quick preview of the analysis.

## 📝 Notes on the Data

This dataset is a sample/practice dataset used for BI portfolio purposes and is not real customer data.
 name and links (LinkedIn, portfolio site, GitHub) here.*            
