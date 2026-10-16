# 👥 Case Study: Human Resources & Employee Analytics

## 📌 Executive Summary
* **Project Objective:** Evaluate workforce demographics, employee performance metrics, departmental attrition, and compensation distribution to support HR strategic workforce planning.
* **Target Audience:** HR Leadership, Talent Acquisition Managers, and Executive Operations.
* **Key Outcome:** Pinpointed key attrition risk factors across department tenure bands and highlighted pay equity alignments across job roles.

---

## 🗂️ Data Sources & Architecture
* **Dataset Used:** `EmployeeData.xlsx`
* **Data Volume & Granularity:** Granular employee records capturing demographic attributes, tenure, department, salary tiers, performance ratings, and status (active vs. departed).
* **Data Preparation:**
  * Anonymized sensitive personal identifiers.
  * Created tenure bins (e.g., `<1 year`, `1-3 years`, `3-5 years`, `5+ years`) for structured attrition analysis.
  * Defined attrition rate formulas using calculated fields: `COUNTD(Terminated Employees) / COUNTD(Total Staff)`.

---

## 🔍 Key Performance Indicators (KPIs) & Metrics
* **Headcount & Turnover Rate:** Total active workforce and percentage of voluntary/involuntary departures.
* **Average Salary by Role:** Compensation distribution benchmarked across departments and performance ratings.
* **Average Tenure:** Length of employment calculated from hire and termination dates.
* **Performance Score Distribution:** Percentage breakdown of performance ratings per team.

---

## 📊 Dashboard Preview & Walkthrough
![Employee Analytics Dashboard Preview](images/employee-data-preview.png)

### Core Features & Design Choices:
* **Attrition Matrix:** Heat map mapping turnover rates across department roles and tenure groups to instantly flag retention risk zones.
* **Demographic Breakdown:** Stacked bar and donut charts illustrating diversity, tenure distribution, and age groups.
* **Compensation Comparison:** Box-and-whisker plots highlighting pay spread and outlier roles within departments.

---

## 💡 Key Insights & Business Recommendations
1. **Tenure-Based Retention Risk:**
   * *Insight:* Turnover peaks noticeably among employees in the 1–2 year tenure band within technical departments.
   * *Recommendation:* Enhance onboarding mentorship programs and introduce mid-career progression touchpoints within the first 18 months.
2. **Departmental Compensation Parity:**
   * *Insight:* Salary distribution showed minor variance across departments for similar performance tiers.
   * *Recommendation:* Perform a formal HR compensation review to standardize pay bands across cross-functional units.

---

## 🚀 How to Interact with This Project
* **Interactive Workbook:** Download `EmployeeData.twbx` from the `DASHBOARDS/` directory.
* **Raw Data:** Access `EmployeeData.xlsx` from the `DATA/` folder.
