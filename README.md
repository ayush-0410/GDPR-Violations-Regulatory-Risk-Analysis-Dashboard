# GDPR Compliance & Violation Analytics Dashboard (Power BI)

## Project Overview

This project analyzes GDPR enforcement cases across Europe and visualizes key compliance trends using **Power BI**. The dashboard provides insights into regulatory actions, violation patterns, enforcement authorities, and financial penalties issued under the General Data Protection Regulation.

The objective of this project is to demonstrate how **data visualization and analytics can support privacy, compliance, and governance teams** in monitoring regulatory risks and identifying areas requiring stronger data protection controls.

---

## Dataset

The dataset used in this project contains recorded GDPR violations and fines issued by data protection authorities.

Source: Kaggle

Dataset files included:

* **gdpr_violations.csv** – Contains enforcement cases and violation details
* **gdpr_text.csv** – Contains structured text of GDPR articles (not used in dashboard analysis)

Key dataset fields used in the analysis:

* **Date** – Date when the GDPR violation occurred
* **Price** – Fine amount issued to the organization
* **Authority** – Data Protection Authority that issued the fine
* **Controller** – Organization responsible for the violation
* **Article Violated** – GDPR article breached
* **Type** – Type/category of violation
* **Summary** – Brief description of the violation

---

## Project Objectives

The dashboard aims to:

* Monitor GDPR enforcement trends
* Identify the most frequently violated GDPR articles
* Analyze fine distributions across countries
* Understand regulatory authority enforcement patterns
* Highlight organizations receiving the largest penalties

---

## Tools & Technologies

* **Power BI** – Data visualization and dashboard development
* **Power Query** – Data cleaning and transformation
* **DAX (Data Analysis Expressions)** – KPI and metric calculations
* **CSV Dataset** – GDPR violations dataset

---

## Key Performance Indicators (KPIs)

The dashboard tracks the following metrics:

* **Total GDPR Violations**
* **Total Fine Amount**
* **Average Fine per Violation**
* **Number of Countries with Recorded Violations**

Example DAX Measures:

Total Violations
COUNTROWS(gdpr_violations)

Total Fines
SUM(gdpr_violations[price])

Average Fine
AVERAGE(gdpr_violations[price])

---

## Dashboard Visualizations

The Power BI dashboard includes the following visual components:

1. **Violations by Country**
   Displays which countries have recorded the highest number of GDPR violations.

2. **Fines by Country**
   Shows the total monetary penalties issued across different countries.

3. **Most Violated GDPR Articles**
   Identifies the GDPR provisions most frequently breached.

4. **Violations by Regulatory Authority**
   Highlights which Data Protection Authorities are most active in enforcement.

5. **Violation Trends Over Time**
   A timeline showing how GDPR enforcement has evolved.

6. **Top Penalized Organizations**
   Lists companies that received the largest fines.

---

## Key Insights

* Certain European countries account for a significant portion of GDPR enforcement cases.
* Violations related to data processing principles and security safeguards appear most frequently.
* GDPR enforcement activity increased after the regulation began being actively enforced.
* Large multinational companies have received some of the highest penalties, indicating the importance of strong compliance frameworks.

---

## Business Value

This dashboard demonstrates how compliance teams can:

* Track regulatory enforcement activity
* Monitor high-risk compliance areas
* Identify frequently violated regulations
* Support governance and risk management initiatives
* Improve organizational awareness of data protection risks

---

## Future Improvements

Potential enhancements for this project include:

* Integration with additional GDPR datasets
* Industry-level violation analysis
* Predictive risk modeling for compliance monitoring
* Automated compliance reporting dashboards

---

## Author

Project developed as part of a **Data Privacy and Compliance Analytics portfolio** to demonstrate skills in regulatory data analysis, governance reporting, and privacy-focused business intelligence.
