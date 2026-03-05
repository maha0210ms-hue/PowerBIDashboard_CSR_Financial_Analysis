# CSR Financial Analysis Dashboard – Power BI
A comprehensive analysis of Corporate Social Responsibility (CSR) fund allocation across sectors, states, companies, and years.
## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

## 📊 Project Overview
This project analyzes how companies allocate Corporate Social Responsibility (CSR) funds across various sectors, states, and years.
The primary objectives were:
- To identify which sector receives maximum CSR funding
- To examine year-wise CSR spending trends
- To analyze state-wise CSR distribution
- To evaluate CSR utilization efficiency
- To identify top contributing companies

An interactive Power BI dashboard was developed to provide multi-level insights using drill-down, slicers, and bookmarks.
## 🗂️ Data Source
- **Source:** https://indiadataportal.com/p/corporate-social-responsibility-csr/r/mca-csr_projects-dt-yr-iuo
- **Format:** .csv
- **Size:** 34,000+ rows
- **Key Variables:**
  - year
  - state_name
  - state_code
  - district_name
  - district_code
  - csr_project_name
  - development_sector
  - company_name
  - cin
  - company_class
  - company_type
  - roc
  - company_category
  - listing_status
  - project_outlay_amount_in_lakhs
  - amount_spent_in_lakhs

The dataset contains multi-year CSR financial information across companies and sectors in India.
## 🛠️ Tools & Technologies
- **Visualization Tool:** Power BI Desktop
- **Data Preparation:** Microsoft Excel
- **Data Modeling:** Star-schema logic (Fact-based dataset)
- **DAX:** Custom measures (Total Spent, Utilization Rate, etc.)
- **Interactive Features:** Drill-down, Slicers, Bookmarks

## 🧹 Data Cleaning & Preparation
The following steps were performed before analysis:
1.	Removed unnecessary columns (IDs, redundant metadata fields).
2.	Standardized sector names for consistency.
3.	Extracted year and created financial_year column.
4.	Handled inconsistent text values (e.g., "Not Mentioned").
5.	Applied winsorization to reduce impact of extreme outliers.
6.	Created calculated measures in Power BI:
    - Total Outlay
    - Total Spent
    - Total Gap
    - Utilization Rate
    
This ensured clean, structured, and analysis-ready data.
## 🔍 Exploratory Data Analysis (EDA)
The following business questions were explored:
- Which sector receives the highest CSR allocation?
- How has CSR spending changed year over year?
- What is the utilization efficiency of allocated funds?
- Which states receive the highest CSR investments?
- Which companies are the top CSR contributors?

Interactive visuals created:
- Bar Charts (Sector Allocation)
- Pie Charts (Fund Distribution)
- Line Charts (Year-wise Trend)
- Map Visualization (State Distribution)
- Top 10 Company Analysis
- Matrix with Year → Sector Drill-down
## 💡 Key Insights
- Education & Skill Development and Health sectors together account for nearly 64% of total CSR spending.
- CSR spending steadily increased from 2014 to 2019, peaking in 2019.
- 2020 shows a decline, likely due to economic disruption.
- Overall utilization rate is 70.24%, with the highest efficiency in 2020.
- CSR allocation is concentrated in major industrial states like Maharashtra, Karnataka, and Tamil Nadu.
- Infosys Ltd is the highest CSR contributor among top companies.
## 🚀 Recommendations
- Increase CSR allocation toward underfunded sectors such as Women & Child Welfare and Social Inclusion.
- Improve monitoring systems to reduce the gap between outlay and actual spending.
- Encourage CSR investment in underdeveloped and North-East regions to ensure regional balance.
- Promote participation from mid-sized companies to reduce concentration among top contributors.
- Implement structured impact measurement frameworks to enhance CSR effectiveness.
## ⚙️ How to Use
To explore this project:
1.	Download the .pbix file from this repository.
2.	Open it using Power BI Desktop.
3.	Use slicers to filter by:
    - Year
    - Sector
    - Company Type
    - State
4.	Use drill-down features to explore:
    - Year → Sector
5.	Click the Reset Filters button (Bookmark) to clear selections.

No additional dependencies are required beyond Power BI Desktop.

