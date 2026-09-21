# Project Development Timeline

This project was completed over three days, following a structured workflow from **data understanding, cleaning and KPI preparation to operational analysis, management dashboard development, business insights and final presentation**.

### Day 1 — Data Understanding, Cleaning & KPI Preparation

The first day focused on understanding the manufacturing dataset, validating the data and preparing the required calculations for analysis.

#### Data Understanding

* Studied the structure of the **1,000 manufacturing records**.
* Reviewed the **49 available fields** covering production, machines, production lines, shifts, products, downtime, quality, maintenance and financial performance.
* Understood the relationships between planned production, produced quantity, good quantity, defect quantity and scrap quantity.
* Identified the KPIs required for production, quality, cost and maintenance analysis.

#### Data Cleaning & Validation

* Checked the dataset for duplicate records.

* Checked missing and blank values.

* Verified the uniqueness and consistency of Record IDs.

* Validated production quantity relationships.

* Verified that:

  `Good Quantity + Defect Quantity = Produced Quantity`

* Verified that:

  `Scrap Quantity <= Defect Quantity`

* Reviewed date fields and categorical fields for consistency.

* Validated the dataset before performing detailed analysis.

#### Data Preparation

* Created a **Data Dictionary** documenting the manufacturing fields.
* Created **Lookup Tables** for classifications and analysis.
* Prepared the calculation structure required for the project.
* Created calculated columns and supporting formulas.
* Organized the workbook into structured analysis sections.

#### KPI Calculations

Calculated and validated key manufacturing KPIs, including:

* Production Achievement %
* Defect Rate %
* Scrap Rate %
* Good Rate %
* Downtime Hours
* Actual Production Rate
* Availability %
* Performance %
* Quality %
* OEE %
* Cost Per Unit
* Profit Per Unit
* Maintenance Risk
* Anomaly Flag

#### Day 1 Outcome

By the end of Day 1, the manufacturing dataset had been **understood, validated and prepared for analysis**, with the Data Dictionary, Lookup Tables, calculated fields and required KPIs completed.

---

### Day 2 — Production, Quality, Cost & Maintenance Analysis

The second day focused on transforming the prepared manufacturing data into meaningful business analysis using **Excel calculations, PivotTables and PivotCharts**.

#### Production & Operations Analysis

Created analysis for:

* Production Achievement by Production Line
* Downtime by Machine
* Production Performance by Shift
* Downtime by Reason
* OEE by Machine
* Monthly Production
* Monthly OEE
* Actual Cycle Time
* Production Efficiency

Analyzed:

* Production line performance
* Machine performance
* Shift performance
* Production efficiency
* Downtime
* OEE
* Cycle time
* Operational performance

#### Quality, Cost & Maintenance Analysis

Created analysis for:

* Defect Rate by Product
* Scrap by Machine
* Defect Rate by Shift
* Profit by Product
* Maintenance Status
* Maintenance Risk

Analyzed:

* Product quality
* Defect performance
* Scrap quantity
* Machine performance
* Profitability
* Maintenance status
* Maintenance risk

#### Key Business Findings

The analysis identified several important operational patterns:

* **Line 4** achieved the highest production achievement.
* **M303** recorded the highest downtime and the lowest OEE among the analyzed machines.
* **Morning Shift** recorded the highest production achievement.
* **Night Shift** recorded the highest defect rate and required further investigation.
* **Machine Breakdown** was identified as a major contributor to downtime.
* **M203** recorded the highest average actual cycle time.
* **Product E** recorded the highest defect rate.
* **M303** recorded the highest scrap quantity.
* **Product A** recorded the highest calculated profit.

#### Day 2 Outcome

By the end of Day 2, the manufacturing dataset had been converted into **structured production, quality, cost and maintenance analysis**, with important operational findings identified through Excel calculations and analysis tables.

---

### Day 3 — Management Dashboard, Insights & Final Presentation

The third day focused on converting the completed analysis into an **interactive Management Dashboard** and preparing the final project deliverables.

#### Management Dashboard

Created an Excel Management Dashboard containing key KPI cards for:

1. Total Production
2. Production Achievement %
3. OEE %
4. Defect Rate %
5. Scrap Cost
6. Downtime Hours
7. Revenue
8. Profit

#### Management Visualizations

Developed management-level visualizations covering:

* Production Trend
* OEE by Production Line
* Downtime by Machine
* Defect Rate by Product
* Scrap Cost by Production Line
* Production by Shift
* Maintenance Risk

These visualizations were designed to provide a clear view of **production performance, quality, downtime, cost, profitability and maintenance risk**.

#### Interactive Dashboard Controls

Added interactive slicers for:

* Month
* Production Line
* Machine
* Shift
* Product Type

These controls allow users to dynamically explore manufacturing performance from different operational perspectives.

#### Business Recommendations

Developed evidence-based recommendations focusing on:

* Reducing machine downtime
* Strengthening preventive maintenance
* Improving Night Shift performance
* Reducing product defects
* Controlling scrap
* Improving production efficiency
* Improving machine OEE
* Managing maintenance risk

#### AI-Assisted Analysis

Used AI as an analytical assistant for:

* Excel formula development
* KPI calculation logic
* Data-cleaning approaches
* Anomaly identification
* Pattern interpretation
* Business insight generation
* Recommendation development

AI-assisted outputs were **checked against the Excel calculations and underlying dataset** before being included in the final project.

#### Final Project Preparation

* Completed the **AI Usage Log**.
* Reviewed KPI calculations.
* Validated analysis results.
* Checked dashboard calculations and visualizations.
* Reviewed the interactive dashboard and slicers.
* Prepared final business insights.
* Prepared management recommendations.
* Organized the completed Excel workbook.
* Prepared the project documentation for GitHub.
* Prepared the final project presentation.

#### Day 3 Outcome

By the end of Day 3, the complete manufacturing analytics project was finalized, including **data preparation, KPI calculations, operational analysis, quality and cost analysis, maintenance analysis, PivotTables, PivotCharts, interactive dashboard, business insights, recommendations, AI documentation and final presentation**.

---

## Overall Project Workflow

```text
Raw Manufacturing Data
          ↓
Data Understanding
          ↓
Data Cleaning & Validation
          ↓
Data Dictionary & Lookup Tables
          ↓
KPI & Calculated Columns
          ↓
Production & Operations Analysis
          ↓
Quality, Cost & Maintenance Analysis
          ↓
PivotTables & PivotCharts
          ↓
Business Insights
          ↓
Management Dashboard
          ↓
Slicers & Interactive Analysis
          ↓
Business Recommendations
          ↓
AI Usage Documentation
          ↓
Final Presentation
          ↓
GitHub Project Documentation
```

## Author

**Srinidhi K**

