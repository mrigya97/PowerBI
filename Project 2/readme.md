# Dormancy Analysis in REC-SSEC Bank

## Project Overview
REC-SSEC Bank, a government-aided bank operating across 40+ regions in India, faces challenges related to dormant accounts — accounts with reduced activity that can signal potential disengagement. This project leverages transaction data from 2022 to analyze dormancy patterns and provide actionable insights using Power BI and DAX. The goal is to empower REC-SSEC Bank to identify low-activity accounts and regions, ultimately supporting efforts to boost engagement and reduce dormancy.

## Case Study Goal
The objective of this case study is to analyze and identify:
- Regions and domains with low transaction counts and values (potential dormancy indicators)
- Seasonal and domain-specific patterns in transaction activity
- The contribution of dormant vs. active accounts to overall transaction values
- Key insights that can help the bank proactively reduce dormancy and strengthen customer engagement

This case study involves multiple Power BI visualizations, interactive dashboards, and advanced DAX functions for accurate dormancy classification and analysis.

## Data Source
The data for this project is sourced from the Kaggle dataset: [Massive Bank Dataset (1 Million+ Rows)](https://www.kaggle.com/datasets/ksabishek/massive-bank-dataset-1-million-rows).

## Key Visualizations Created
- **Stacked Column Chart – Transactions by Domain**  
  Shows transaction volumes by domain over time (monthly analysis) and highlights dormancy patterns.

- **Clustered Bar Chart – Dormant Regions Analysis**  
  Highlights regions with the lowest transaction activity, using conditional formatting to visualize dormancy intensity.

- **Donut Chart – Dormancy by Domain Contribution**  
  Displays the percentage contribution of each domain to total transactions, emphasizing dormant account proportions.

- **Matrix – Dormancy and Transaction Correlation**  
  Compares transaction counts and values across different domains and regions, with conditional formatting to highlight variances.

- **Map – Dormancy Heatmap**  
  Visualizes the geographic distribution of transaction activity, with tooltips showing both transaction counts and values.

- **KPI and DAX Aggregate Visuals – Transaction Insights**  
  Summarizes active and dormant account transaction values and calculates the share of retail transactions.

- **Slicer – Multi-Selector for Locations**  
  Enables location-based analysis, dynamically adjusting visualizations for selected cities.

- **Pie Chart – Dormancy Distribution by Domain**  
  Highlights the percentage distribution of dormant accounts across different business domains.

- **100% Stacked Chart – Regional Contribution by Domain**  
  Illustrates the proportional contribution of each domain to total transactions within each region.

- **Funnel Chart – Transaction Flow and Dormancy Analysis**  
  Depicts how total transaction counts flow from overall activity to dormant and active stages based on defined thresholds.

## Technologies Used
- **Power BI**: Interactive dashboards and insightful visualizations  
- **DAX (Data Analysis Expressions)**: Advanced calculations for dormancy classification and percentage shares  

## Key Insights Provided
- Dormancy rates vary by month, with May showing the highest transaction activity and February the lowest.  
- Domains like Education consistently have lower dormancy trends, while Retail and Restaurants show higher dormancy.  
- Regions such as Goa, Ajmer, and Lunglie display the highest activity (lowest dormancy), while Buxar, Indore, and Madurai exhibit the highest dormancy rates.  
- Dormant accounts contribute to **16.96%** of the total transaction counts, while active accounts contribute **83.04%** — revealing a significant opportunity for customer re-engagement.

## Conclusion
This data-driven approach provides REC-SSEC Bank with actionable insights to reduce dormancy across its network. By understanding which regions and domains have higher dormancy activity, the bank can tailor its outreach strategies to boost engagement and strengthen overall customer relationships.


