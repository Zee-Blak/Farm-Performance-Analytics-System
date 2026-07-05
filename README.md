# Comprehensive Farm Performance & Profitability System 🌾📊

## Project Overview
This project is an end-to-end data analytics solution evaluating the operational efficiency and financial viability of 500 farms across Sub-Saharan Africa. As the capstone project for my DataverseAfrica internship, the goal was to transform raw agricultural data into actionable insights for two distinct stakeholders: **Farmer Cooperatives** and **Agribusiness Investors**. 

Cultivating staples firsthand provides a unique lens for data analysis; this dashboard was built to bridge the gap between dirt-and-soil realities (like the physical labor required for tuber mounds) and high-level corporate investment strategy.

## Tech Stack & Skills
*   **Data Processing & ETL:** SQL (Google BigQuery)
*   **Data Visualization & Modeling:** Power BI (DAX, Data Modeling)
*   **Analytical Concepts:** Yield Gap Analysis, Financial Stress-Testing, Profitability Modeling, Precision Agriculture Metrics.

## The Dashboard: Dual-Stakeholder Views

### 1. Operational Performance (Cooperative View)
Focused on ground-level realities, yield optimization, and input costs. 
*   **The Leak:** Identified an $806.58K total revenue leak caused by yield gaps, representing nearly 25% of potential agricultural revenue left in the dirt.
*   **Biological Insights:** High-value crops like Tomatoes showed massive yield gaps due to their fragile, high-maintenance nature. Conversely, resilient legumes like Cowpea consistently met baseline benchmarks without requiring flawless operational environments.
*   **Actionable Recommendation:** Advised redirecting cooperative funds toward targeted extension services (irrigation/stem cuttings) and establishing shared mechanization to lower the disproportionately high manual labor costs in subsistence farming.
<img width="2075" height="1200" alt="Comprehensive Farm Performance   Profitability System (Capstone Project) Final_page-0001" src="https://github.com/user-attachments/assets/466fc75b-5465-47af-847f-472ecb088d0c" />


### 2. Financial Viability & Risk (Investor View)
Focused on bottom-line returns, gross margins, and market vulnerability.
*   **The Stress Test:** While the portfolio boasts a highly attractive 272% average ROI, it carries significant systemic risk. A simulated 20% market price crash instantly wiped out profitability for 5.39% of the farms.
*   **Revenue Concentration:** Heatmap analysis revealed extreme top-heavy reliance on Tomatoes and Yams. 
*   **Actionable Recommendation:** Recommended aggressive capital deployment into resilient processing facilities (e.g., garri or flour production) to protect high-margin crops, alongside mandated crop diversification to cross-subsidize operations during market shocks.
<img width="2075" height="1200" alt="Comprehensive Farm Performance   Profitability System (Capstone Project) Final_page-0002" src="https://github.com/user-attachments/assets/d56f39f1-d897-4b0f-b04b-1e0bb85b8cf4" />


## Repository Contents
*   `📁 sql_scripts`: Contains all BigQuery SQL queries used to clean the raw data, execute row-by-row gross margin calculations, and run the 20% market crash simulation.
*   `📁 dashboard`: Contains the raw `.pbix` Power BI file and a high-resolution PDF export of the final minimalist, executive-grade dashboards.
*   `📁 data`: Contains the data dictionary and schema used for this analysis.

## Conclusion
This system proves that precision data can directly influence food security and investment strategy, ensuring capital is deployed where it has the highest operational and financial impact.
