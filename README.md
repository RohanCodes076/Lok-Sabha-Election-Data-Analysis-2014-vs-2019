# Lok Sabha Elections Data Analysis - 2014 Vs 2019

## 📌 Project Overview
The main objective of this project is to provide a detailed examination of electoral trends, voting patterns, and key metrics across India's parliamentary constituencies during the 2014 and 2019 Lok Sabha elections. This analysis aims to enrich public understanding of the electoral process in India and highlight key insights that have shaped the country's democracy over these pivotal election years.

## 🛠️ Tools Used
* **Power BI:** Leveraged for data visualization and creating interactive dashboards to deliver technical analytics workflows.
* **Python:** Employed for advanced data cleaning, complex transformation logic, and deep statistical analytical processing.
* **Excel:** Utilized for initial data exploration, tabular structuring, and rapid sanity checks.

## 🗄️ Data & Preprocessing
* **Source:** Election data for both the 2014 and 2019 cycles was sourced directly from the **Election Commission of India (ECI)**.
* **Cleaning:** 
  * Removed duplicate records across candidate and constituency levels.
  * Handled missing numeric metrics and flagged incomplete categorical data.
  * Standardized constituency and state names to resolve spelling discrepancies and ensure accurate relational joins.
* **Transformation:** 
  * Merged the 2014 and 2019 datasets for comparative historical analysis.
  * Engineered derived metrics, notably calculating the **Voter Turnout Ratio** as `((General Votes + Postal Votes) / Total Electors) * 100`.

## 📊 Key Performance Indicators (KPIs)
* **Winning Candidate and Party:** Identification of victorious candidates and their party affiliations per constituency.
* **Voter Turnout:** Calculation and tracking of voter participation percentages aggregated at national and state levels.
* **Vote Share:** Analysis of the proportional distribution of total valid votes among contesting political parties.
* **Margin of Victory:** Measurement of the absolute vote difference between the winning candidate and the immediate runner-up.
* **Statistical Correlations:** Examination of Pearson correlation coefficients between voter turnout and external demographic factors (state literacy rates, state GDP, and postal vote utilization).

## 💡 Primary Insights
* **Turnout Disparities:** North-Eastern states (e.g., Assam, Nagaland) consistently register the highest turnout rates (>85%). Conversely, conflict-prone or heavily urbanized regions frequently fall to the bottom of the participation spectrum.
* **Incumbency & Strongholds:** Certain constituencies (e.g., Surat, Vadodara, Navsari) act as unshakeable fortresses, maintaining >70% vote shares for incumbents across multiple cycles and delivering massive margins (>500,000 votes).
* **Major Swings:** Significant vote share swings occurred in specific regions, such as Alipurduars (shifting from AITC to BJP with a 24.77% swing) and Kanniyakumari (shifting from BJP to INC with a 22.19% swing).
* **NOTA Trends:** There are shifting centers of voter dissatisfaction; Nilgiris led in 2014 (46,559 NOTA votes), while Gopalganj took the lead in 2019 (51,660 NOTA votes).

## 📈 Secondary Insights & Correlations
* **State GDP:** Exhibited a moderate negative correlation with voter turnout in 2014 (-0.49), a sign of potential "urban apathy." However, this metric completely neutralized by 2019 (0.09), suggesting a shift in affluent voter priorities or successful mobilization campaigns.
* **Literacy Rates:** Demonstrated a weak but consistent positive correlation (~0.27 to 0.29) with voter turnout, indicating that education levels play a stable role in driving democratic participation.
* **Postal Votes:** Maintained a minor positive correlation with overall turnout across both cycles.

## 🚀 Future Recommendations
* **Targeted SVEEP Campaigns:** Electoral authorities should focus awareness initiatives on low-turnout, high-GDP urban centers.
* **Automated Data Pipelines:** Transition entirely to automated Python ETL workflows for future election cycles to minimize manual data handling errors and reduce time-to-insight.

---
*Prepared by: **Rohan***
