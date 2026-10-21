# Indian_Supply_Chain-Analytics_Project_Power_BI


## Project Tasks: Shipment Analysis Dashboard

An interactive Power BI dashboard that gives a clear, at-a-glance view of product shipments: what was shipped, to whom, when, and how much it was worth.

---

## 📌 Project Overview

This dashboard analyzes shipment data from **February 1, 2018 to January 31, 2022**. It helps business teams quickly understand sales performance, identify their most important customers and products, and spot shipping trends over time.

Users can narrow down the data using three interactive filters, and every chart updates automatically.

---

## 🎯 Key Business Questions Answered

- How much product was shipped, and what was its total value?
- Which customers receive the largest shipments?
- Which products are shipped the most?
- Which sales channel (Mainstream or Ethnic) generates more value?
- Do Frozen or Dry products contribute more to total value?
- How has shipped quantity changed from year to year?

---

## 📊 Headline Numbers

| Metric | Value |
|---|---|
| Total Value of Shipped Product | ₹ 6.13M |
| Total Quantity Shipped | 223.11K units |
| Reporting Period | 2 Jan 2018 – 31 Jan 2022 |

---

## 🔍 Dashboard Sections Explained

### 1. Filters (Top of the Dashboard)
| Filter | What It Does |
|---|---|
| **Product Code Filter** | Focus the dashboard on a specific product code |
| **Product Description Filter** | Focus on a specific product by its name |
| **Date Filter** | Choose a custom date range using the date boxes or slider |

All filters are currently set to **"All"**, showing the complete data set.

### 2. Total Value by Channel (Donut Chart)
Shows how shipment value is split between the two sales channels:
- **Mainstream:** ₹3.15M (51.39%)
- **Ethnic:** ₹2.98M (48.61%)

**Takeaway:** Both channels contribute almost equally. Mainstream leads by a small margin.

### 3. Total Value by Type (Pie Chart)
Shows value split by product type:
- **Frozen:** ₹3.97M (64.82%)
- **Dry:** ₹2.16M (35.18%)

**Takeaway:** Frozen products generate nearly two-thirds of total value.

### 4. Top 5 Customers by Shipped Quantity (Bar Chart)
| Rank | Customer | Quantity |
|---|---|---|
| 1 | Wal-Mart Canada Corporation | 96K |
| 2 | Sobey's | 16K |
| 3 | Loblaws Inc. | 11K |
| 4 | Iqbal Foods Halal Superstore | 3K |
| 5 | Chef's Depot (TFI Foods Ltd) | 3K |

**Takeaway:** Wal-Mart Canada is by far the largest customer, receiving more than the other four combined. This shows a strong dependence on a single customer.

### 5. Shipped Quantity by Year (Treemap)
Each block's size represents the quantity shipped in that year:
- **2021:** 81.05K (highest)
- **2020:** 58.21K
- **2018:** 38.86K
- **2019:** 36.94K
- **2022:** smallest block (the data covers only January)

**Takeaway:** Shipments peaked in 2021. Because 2022 only includes January, it should not be compared directly with full years.

### 6. Top 5 Products by Shipped Quantity (Bar Chart)
- Four of the top five products are from the **Camel Pickle** range, with quantities of 1,094, 918, 842 and 791.
- The fifth is an **Oak Frozen Samosa** product with 47 units.

**Takeaway:** Camel Pickle products dominate the best-seller list.

---

## 💡 Key Insights

1. **Balanced channels:** Mainstream and Ethnic channels are almost evenly matched in value.
2. **Frozen leads:** Frozen products make up about 65% of total shipment value.
3. **One major customer:** Wal-Mart Canada accounts for roughly 43% of all units shipped (96K of 223K).
4. **Growth peak in 2021:** Shipped quantity was highest in 2021.
5. **Product concentration:** Camel Pickle items account for most of the top-selling products.

---

## 🛠️ Tools Used

- **Microsoft Power BI**: dashboard design, data modeling and visualization

---

## 📝 Notes

- Values are shown in Indian Rupees (₹). M = million, K = thousand.
- Product names in the top 5 chart are shortened for display and may be cut off.
- 2022 data covers January only.

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the filters at the top to explore specific products or time periods.
3. Hover over any chart to see detailed figures.
