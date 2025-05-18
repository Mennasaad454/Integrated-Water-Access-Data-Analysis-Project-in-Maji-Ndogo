# Integrated-Water-Access-Data-Analysis-Project-in-Maji-Ndogo
## 📘 Project Overview
This project analyzes water service delivery and data integrity in Maji Ndogo, a fictional country, using SQL. It was completed in two phases:

### Phase 1: Service Evaluation
Analyzed water source quality, community access, and employee performance. Leveraged SQL to clean and aggregate data, uncover bottlenecks, and generate actionable insights for infrastructure and operational improvements.

### Phase 2: Corruption Detection
Cross-referenced internal records with an auditor’s report to detect inconsistencies. Used CTEs, subqueries, and views to:

- Identify above-average data entry errors,

- Flag potentially corrupt employees,

- Link irregularities to specific surveyed locations.

## 🗂️ Data Sources
The primary dataset used for this analysis is the ["md_water_services"](https://drive.google.com/file/d/1nXeoG9nnSs4oiVvft3K9VFUfRiYzvTJF/view?usp=sharing) data, containing detailed information about each water source, employee performance and water quality and tools.
["adult_report.csv"](https://drive.google.com/file/d/1IbJZyDn_-8qf-N74kfXLwY4d-Vw9reQz/view?usp=sharing) was also added to the table in the second phase to conduct deep analysis on data inconsistencies.

## ⚙️ Tools & Techniques
SQL: Data cleaning, joins, filtering, CTEs, views, subqueries

MySQL Server: Database management and querying

## 🧹 Data Preparation
Removed null and invalid entries

Split and reformatted misaligned columns

Added calculated fields (e.g., email, population brackets)

Merged auditor report into main dataset for Phase 2 analysis

## 🔍 Key Insights
Based on the analysis, the following actions are recommended to improve water access and system integrity in Maji Ndogo:

- River-dependent communities: Deploy water trucks as a short-term solution. Begin well drilling in these areas to establish long-term access to clean water.

- Contaminated wells: Install appropriate filtration systems—UV filters for biological contaminants and reverse osmosis systems for chemical pollution. Further investigation is needed to identify pollution sources and prevent recurrence.

- Shared taps (high demand): Use queue-time data to schedule water tankers during peak hours. Begin expanding tap infrastructure in areas where wait times exceed the UN-recommended 30-minute maximum.

- Shared taps (low demand): Reducing wait times further is inefficient. Long-term investment in household taps is a more strategic solution, though resource-intensive.

- Broken infrastructure: Prioritize repairs that have broad impact—such as damaged reservoirs or pipes serving multiple taps. Identify and target the most affected areas for efficient resource allocation.

- Data integrity concerns: Analysis revealed irregularities linked to four officials suspected of falsifying reports or accepting bribes. Recommend initiating a formal audit and strengthening data validation processes.
