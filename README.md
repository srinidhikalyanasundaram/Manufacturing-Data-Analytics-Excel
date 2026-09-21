## Project Development Timeline

This project was completed over three days, following a structured workflow from **data preparation and KPI development to business analysis, dashboard creation, and final recommendations**.

### Day 1 — Data Understanding, Cleaning & KPI Preparation

The first day focused on understanding the manufacturing dataset and preparing it for reliable analysis.

#### Data Understanding
- Studied the structure and purpose of the **1,000 manufacturing records**.
- Reviewed the available fields related to production, machines, production lines, shifts, products, downtime, quality, maintenance and financial performance.
- Understood the relationships between planned production, actual production, good quantity, defect quantity and scrap quantity.
- Reviewed the data requirements and identified the KPIs required for the project.

#### Data Cleaning & Validation
- Checked the dataset for duplicate records.
- Checked for missing and blank values.
- Verified the uniqueness of Record IDs.
- Validated production quantity relationships.
- Verified that:

  `Good Quantity + Defect Quantity = Produced Quantity`

- Verified that:

  `Scrap Quantity <= Defect Quantity`

- Reviewed date fields and categorical fields for consistency.
- Checked the data before using it for PivotTable analysis.

#### Data Preparation
- Created a **Data Dictionary** to document the dataset fields.
- Created **Lookup Tables** for analysis and classification.
- Prepared the calculation structure required for the project.
- Created the required calculated columns and KPIs.

#### KPI Calculations
Calculated and validated:

- Production Achievement %
- Defect Rate %
- Scrap Rate %
- Good Rate %
- Downtime Hours
- Actual Production Rate
- Availability %
- Performance %
- Quality %
- OEE %
- Cost Per Unit
- Profit Per Unit
- Maintenance Risk
- Anomaly Flag

#### Day 1 Outcome

By the end of Day 1, the raw manufacturing data had been **understood, cleaned, validated and prepared for detailed analysis**. The required KPI calculations were also created and checked in Excel.

---

### Day 2 — Production, Quality, Cost & Maintenance Analysis

The second day focused on converting the prepared data into meaningful business insights using **Excel PivotTables and PivotCharts**.

#### Production & Operations Analysis

Created PivotTables and charts to analyze:

- Production Achievement by Production Line
- Downtime by Machine
- Production Performance by Shift
- Downtime by Reason
- OEE by Machine
- Monthly Production and OEE

Analyzed:

- Production line performance
- Machine downtime
- Shift performance
- OEE
- Downtime reasons
- Actual cycle time
- Production efficiency

#### Quality, Cost & Maintenance Analysis

Created PivotTables and charts for:

- Defect Rate by Product
- Scrap by Machine
- Defect Rate by Shift
- Profit by Product
- Maintenance Status
- Maintenance Risk

Analyzed:

- Product quality performance
- Defect rates
- Scrap quantities
- Machine performance
- Profitability
- Maintenance conditions
- Maintenance risk levels

#### Key Business Findings

The analysis helped identify important operational patterns, including:

- **Line 4** achieved the highest production achievement.
- **M303** recorded the highest downtime and had the lowest OEE.
- **Morning Shift** recorded the highest production achievement.
- **Night Shift** showed the highest defect rate and required further investigation.
- **Machine Breakdown** was the major downtime reason.
- **M203** had the highest average actual cycle time.
- **Product E** recorded the highest defect rate.
- **M303** recorded the highest scrap quantity.
- **Product A** recorded the highest calculated profit.

#### Day 2 Outcome

By the end of Day 2, the manufacturing data had been transformed into **structured operational, quality, cost and maintenance analysis**, with key business findings identified through PivotTables and PivotCharts.

---

### Day 3 — Management Dashboard, Insights & Final Presentation

The third day focused on converting the analysis into an **interactive management dashboard** and preparing the final project deliverables.

#### Management Dashboard

Created an Excel Management Dashboard containing **8 key KPI cards**:

1. Total Production
2. Production Achievement %
3. OEE %
4. Defect Rate %
5. Scrap Cost
6. Downtime Hours
7. Revenue
8. Profit

#### Management Visualizations

Created **7 management-level charts**:

1. Production Trend
2. OEE by Production Line
3. Downtime by Machine
4. Defect Rate by Product
5. Scrap Cost by Production Line
6. Production by Shift
7. Maintenance Risk

These visuals were designed to help management quickly understand production performance, quality issues, downtime, profitability and maintenance risk.

#### Interactive Dashboard Controls

Added **5 slicers** to allow interactive filtering:

- Month
- Production Line
- Machine
- Shift
- Product Type

The slicers allow users to analyze the dashboard from different operational perspectives.

#### Business Recommendations

Based on the analysis, developed evidence-based recommendations related to:

- Machine downtime reduction
- Preventive maintenance
- Night Shift performance
- Product quality improvement
- Scrap reduction
- Production efficiency
- Machine OEE improvement
- Maintenance risk management

#### AI-Assisted Analysis

Used AI as an analytical assistant for:

- Excel formula development
- KPI calculation logic
- Data-cleaning approach
- Anomaly identification
- Pattern interpretation
- Business insight generation
- Recommendation development

AI-assisted findings were **validated against the Excel calculations and underlying dataset** before being included in the final analysis.

#### Final Project Preparation

- Completed the AI Usage Log.
- Reviewed KPI calculations and analysis.
- Checked dashboard charts and visual presentation.
- Prepared the final management insights.
- Prepared the project presentation.
- Organized the Excel workbook and supporting documentation.
- Prepared the project structure for GitHub.

#### Day 3 Outcome

By the end of Day 3, the complete manufacturing analytics solution was finalized, including the **Excel calculations, PivotTables, PivotCharts, interactive dashboard, business insights, recommendations, AI documentation and final presentation**.

---

## Overall Project Workflow

```text
Raw Manufacturing Data
          ↓
Data Understanding
          ↓
Data Cleaning & Validation
          ↓
KPI & Calculated Columns
          ↓
PivotTable Analysis
          ↓
PivotCharts
          ↓
Business Insights
          ↓
Management Dashboard
          ↓
Slicers & Interactive Analysis
          ↓
Recommendations
          ↓
Final Presentation

## Author

**Srinidhi K**
