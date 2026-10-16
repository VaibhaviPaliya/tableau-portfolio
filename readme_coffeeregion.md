# ☕ Case Study: Coffee Region Performance & Market Analysis

## 📌 Executive Summary
* **Project Objective:** Analyze regional coffee sales, product performance, and profitability drivers across key territories to identify top-performing product lines and optimize regional supply distribution.
* **Target Audience:** Operations Managers, Regional Sales Directors, and Supply Chain Leads.
* **Key Outcome:** Uncovered specific product-region combinations yielding high volume but low profitability due to operational overhead, enabling targeted pricing and distribution strategy adjustments.

---

## 🗂️ Data Sources & Architecture
* **Dataset Used:** `Coffee Region.xlsx`
* **Data Volume & Granularity:** Multi-year transaction logs tracking product sales, profits, costs, inventory, and territorial metadata.
* **Data Preparation:**
  * Standardized geographical region labels and mapped product categories (e.g., Espresso, Herbal Tea, Coffee, Coffee Beans).
  * Calculated custom metrics in Tableau for Profit Margin (`SUM([Profit]) / SUM([Sales])`) and Budget Variance.

---

## 🔍 Key Performance Indicators (KPIs) & Metrics
* **Total Sales Revenue:** Overall monetary value generated from coffee and beverage sales.
* **Profit Margin (%):** Ratio of net profit relative to revenue, evaluating operational efficiency across regions.
* **COGS & Expenses:** Direct cost of goods sold combined with marketing and payroll allocations per region.
* **Budget vs. Actual Variance:** Comparison of projected targets against actual revenue achieved.

---

## 📊 Dashboard Preview & Walkthrough
![Coffee Region Dashboard Preview](images/coffee-region-preview.png)

### Core Features & Design Choices:
* **Geographic Map View:** Visualizes total sales and profit distribution across regions using color intensity and circle sizing for quick spatial evaluation.
* **Category Breakdown:** Interactive bar charts comparing sales volume vs. profit margin for specific coffee beans and tea products.
* **Interactive Filtering:** Allows stakeholders to filter dynamically by state, product line, and date range.

---

## 💡 Key Insights & Business Recommendations
1. **Underperforming Regional Lines:**
   * *Insight:* Certain high-volume product categories in specific central territories exhibit squeezed margins due to high shipping expenses.
   * *Recommendation:* Adjust regional pricing tiers or renegotiate regional logistics routes to protect profit margins.
2. **Top-Growth Categories:**
   * *Insight:* Espresso and specialty roast sales demonstrated steady year-over-year profit growth across urban regions.
   * *Recommendation:* Reallocate marketing budget towards high-performing specialty products in emerging territories.

---

## 🚀 How to Interact with This Project
* **Interactive Workbook:** Download `Coffee-Region-Dashboard.twbx` from the `dashboards/` directory.
* **Raw Data:** Access `Coffee Region.xlsx` from the `data/` folder.
