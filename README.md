# Integrated-Water-Access-Data-Analysis-Project-in-Maji-Ndogo
## 📘 Project Overview
This project analyzes water service delivery and data integrity in Maji Ndogo, a fictional country, using SQL. It was completed in two phases:

### Phase 1: Service Evaluation
Analyzed water source quality, community access, and employee performance. Leveraged SQL to clean and aggregate data, uncover bottlenecks, and generate actionable insights for infrastructure and operational improvements.

### Phase 2: Corruption Detection
Cross-referenced internal records with an auditor’s report to detect inconsistencies. Used CTEs, subqueries, and views to:

Identify above-average data entry errors,

Flag potentially corrupt employees,

Link irregularities to specific surveyed locations.

## 🗂️ Data Sources
md_water_services: Main dataset on water sources, quality, and employee records.

auditor_report.csv: External report for validating internal data.

## ⚙️ Tools & Techniques
SQL: Data cleaning, joins, filtering, CTEs, views, subqueries

MySQL Server: Database management and querying

## 🧹 Data Preparation
Removed null and invalid entries

Split and reformatted misaligned columns

Added calculated fields (e.g., email, population brackets)

Merged auditor report into main dataset for Phase 2 analysis

## 🔍 Key Insights
River users: Recommend immediate water truck delivery and long-term well drilling

Contaminated wells: Install UV or reverse osmosis filters, investigate pollution sources

Shared taps: Use queue-time data to deploy extra tankers; add taps in high-demand areas

Broken infrastructure: Prioritize repairs with high user impact (e.g., shared reservoirs)

Corruption: Identified four officials with suspicious data manipulation patterns

## ✅ Outcome
This project demonstrated the power of SQL for real-world public service analysis—combining operational insights with data integrity checks to support more equitable and efficient water access.
