# 📈 Case Study: Commercial Sales & Revenue Performance

## 📌 Executive Summary
* **Project Objective:** Track multi-channel sales performance, order fulfillment efficiency, customer segmentation, and quarterly revenue growth.
* **Target Audience:** Chief Commercial Officer, Sales Strategy Teams, and Regional Account Executives.
* **Key Outcome:** Identified key revenue concentration risks and optimized discount strategy guidelines to improve overall net revenue.

---

## 🗂️ Data Sources & Architecture
* **Dataset Used:** `SalesData.xlsx`
* **Data Volume & Granularity:** Detailed sales order transactional data capturing customer IDs, order dates, ship modes, discount percentages, revenue, and product categories.
* **Data Preparation:**
  * Cleaned date formats and joined order details with customer segment tables.
  * Constructed calculated metrics for Net Revenue (`Sales - Discount`), Average Order Value (AOV), and Order Cycle Time.

---

## 🔍 Key Performance Indicators (KPIs) & Metrics
* **Total Sales & Net Revenue:** Overall gross revenue generated minus Applied Discounts.
* **Average Order Value (AOV):** Revenue per individual completed transaction.
* **Order Fulfillment Time:** Days elapsed between Order Date and Ship Date.
* **Discount Impact Ratio:** Relationship between discount rate percentage and net profitability.

---

## 📊 Dashboard Preview & Walkthrough
![Sales Performance Dashboard Preview](images/sales-data-preview.png)

### Core Features & Design Choices:
* **Quarterly Trend Line:** Dual-axis timeline comparing month-over-month sales growth against order volume targets.
* **Customer Segment Breakdown:** Comparative views showing sales split across Consumer, Corporate, and Home Office segments.
* **Scatter Plot Analysis:** Correlation chart mapping Discount Percentage vs. Profitability to flag erosion in margin.

---

## 💡 Key Insights & Business Recommendations
1. **Discount Erosion Effect:**
   * *Insight:* Orders with discounts exceeding 20% consistently resulted in negative net profit without a significant increase in order volume.
   * *Recommendation:* Cap maximum allowable sales rep discount authority at 15% without prior executive approval.
2. **Top Customer Concentration:**
   * *Insight:* Top 10% of enterprise accounts account for over 40% of total quarterly revenue.
   * *Recommendation:* Implement key account management strategies to retain and upsell top-tier enterprise accounts.

---

## 🚀 How to Interact with This Project
* **Interactive Workbook:** Download `SalesData.twbx`.
* **Raw Data:** Access `SalesData.xlsx`.
