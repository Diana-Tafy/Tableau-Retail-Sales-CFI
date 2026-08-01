# Tableau-Retail-Sales-CFI
Tableau Sales Dashboard : https://retaildash-kswu7z7j.manus.space/

# 📊 CFI Retail Analytics Dashboard

An executive-level data analytics dashboard built to monitor multi-year sales velocity, profit margins, customer concentration, and shipping logistics performance across retail operations.

---

## 📌 Project Overview

This dashboard translates over **$2.3M in raw retail transaction data** into actionable business intelligence. It provides executive stakeholders with real-time insights into top-line growth, category performance, customer purchasing behavior, and logistics efficiency—specifically addressing critical bottom-line net margin compression.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Metric Value | Status / Assessment |
| :--- | :--- | :--- |
| **Total Revenue** | **$2.3M** | 🟢 Strong Top-Line Growth across multi-year trends. |
| **Total Net Profit** | **$23.0k** | 🔴 Critical Bottom-Line Friction (Requires margin optimization). |
| **Units Sold** | **4,790** | 🔵 Healthy Volume Throughput across active product SKUs. |
| **Net Profit Margin** | **1.0%** | ⚠️ Severe Erosion driven by high fulfillment/discount costs. |

---

## 🔍 Detailed Visual Analysis & Insights

### 1. Year Sales (with YoY Growth %)
* **Observation:** Revenue expanded steadily from **~$460k in 2014** to over **$700k in 2017**.
* **Insight:** Market adoption and volume demand are consistently rising, but top-line growth is failing to yield proportional bottom-line profit.

### 2. Product Category Profitability
* **Observation:** **Technology** generates nearly **50%** of total business profit.
* **Insight:** Technology serves as the primary revenue and margin engine, while **Furniture** and **Office Supplies** operate on near-zero profit margins.

### 3. Customers by Sales (All Regions)
* **Observation:** Significant revenue concentration among top VIP accounts led by **Adrian Barton** (exceeding $14k–$16k in spend), **Adam Bellavance**, **Alex Avila**, and **Anna Andreadi**.
* **Insight:** Key B2B accounts carry a disproportionate amount of revenue weight compared to standard retail orders.

### 4. Sales by Shipping Mode
* **Observation:** **Shipping Mode 4** accounts for over **$1.3M in revenue** (dominating overall distribution volume).
* **Insight:** High fulfillment and carrier expenses associated with Mode 4 are directly eroding overall corporate profit margins down to 1.0%.

### 5. Profit vs. Sales Elasticity (Scatter Plot)
* **Observation:** High-value transactions ($12k–$16k) yield strong profits ($3k–$5k), while smaller orders ($2k–$5k) yield minimal to zero profitability.
* **Insight:** Small-order fulfillment friction and fixed order-handling fees erode profits on lower basket sizes.

---

## 💡 Strategic Recommendations

1. **Implement Pricing & Discount Controls:** Establish strict discounting rules on high-volume items to prevent net margins from dropping below target thresholds.
2. **Key Account Loyalty Programs:** Create dedicated retention and incentive programs for top-tier corporate clients (e.g., Adrian Barton tier) to prevent churn.
3. **Logistics Rate Optimization:** Leverage the massive shipment volume in **Mode 4** to renegotiate bulk freight rates or set minimum spend thresholds for free shipping.
4. **Inventory Reallocation:** Shift capital investment heavily toward high-margin **Technology** SKUs while bundling lower-margin Office Supplies to enhance basket profitability.

---

## 🎨 Design System & UI Specifications

* **Canvas Layout:** Soft off-white canvas (`#F8FAFC`) with elevated container cards (`#FFFFFF`).
* **Visual Hierarchy:** Soft drop shadows (`box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05)`) and rounded borders (`12px`).
* **Color Palette:**
  * **Primary Teal Accent:** `#0EA5E9` (Technology & High Performers)
  * **Warm Amber Accent:** `#F59E0B` (Office Supplies & Alerts)
  * **Slate Blue:** `#1E293B` (Primary Typography & Hierarchy)
  * **Muted Gray:** `#94A3B8` (Secondary Metrics & Axis Labels)
