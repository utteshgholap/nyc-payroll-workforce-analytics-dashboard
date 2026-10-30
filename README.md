# 🏛️ NYC Municipal Payroll & Workforce Analytics Dashboard (Power BI)

An executive public-sector workforce intelligence dashboard built in **Microsoft Power BI** analyzing municipal employee compensation, headcount trends, agency distributions, and overtime expenditures across New York City departments.

---

## 📊 Dashboard Preview

![NYC Payroll Analytics Dashboard](images/dashboard_overview.png)

---

## 📌 High-Level Municipal KPIs

* **Total Gross Payroll:** $1.07 Billion
* **Active Workforce Headcount:** 17,150 Employees
* **Average Base Salary:** $43.66K
* **Average Overtime Expenditure:** $937.79K

---

## 🔍 Key Analytical Findings & Operational Insights

### 1. Agency Compensation & Overtime Dominance
* **Police Department (NYPD):** Represents the single largest municipal financial footprint, capturing **$0.43 Billion** in regular gross pay.
* **Secondary Agencies:** The Department of Environmental Protection, Department of Parks, and Department of Health collectively represent critical municipal operations, each operating between $0.01B and $0.06B in payroll segments.

### 2. Workforce Growth & Historical Trajectory
* Headcount historical analysis highlights significant municipal hiring expansions post-1980, peaking between **2000 and 2016** (peaking at **1,508 active hires** in tracked cohorts).

### 3. Departmental Overtime Distribution
* While the Police Department drives total regular gross pay, major overtime expenditure clusters in:
  1. **Administration for Children's Services (ACS)**
  2. **Bronx District Attorney**
  3. **Department of Environmental Protection**

---

## 🛠️ Power BI Technical Stack & DAX Architecture

* **Data Transformation & Modeling:**
  * Ingested and transformed municipal payroll transactional data using **Power Query (M)**.
  * Established star-schema dimensional relationships linking agency master files, fiscal calendar hierarchies, and employee payroll logs.
* **Key DAX Formulations:**
  * Dynamic regular vs. overtime expense variance calculations.
  * Workforce headcount rolling summaries and fiscal year-over-year growth metrics.
* **Interactive Visualization Design:**
  * Implemented dynamic multi-select slicers for **Fiscal Year** and **Borough Location (e.g., Bronx)**.
  * Designed tree maps for agency workforce density, horizontal bar charts for overtime variance, and dual-axis historical trend lines.

---

## 🚀 How to View & Explore

1. Clone this repository:
   ```bash
   git clone [https://github.com/utteshgholap/nyc-payroll-analytics-dashboard.git](https://github.com/utteshgholap/nyc-payroll-analytics-dashboard.git)
