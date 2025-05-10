## Table of Contents

- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Project Objectives](#project-objectives)
- [Techniques Applied](#Techniques-Applied)
- [Interactive DashBoard](#Interactive-DashBoard)
- [Key Insights](#key-insights)
- [Tools Used](#tools-used)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Author](#author)
  
# Loan-Portfolio-Analysis
An interactive dashboard project that analyzes loan defaults to uncover risk factors related to borrower profiles, loan purposes, and geography. Built with Power BI, this project showcases data modeling, DAX, and storytelling with data for portfolio demonstration.

## Project Overview
This project presents a visual analysis of loan application and repayment data, utilizing **Power BI** to explore patterns behind loan defaults. It aims to identify key risk factors associated with borrower profiles, loan types, and geographic regions. The interactive dashboard provides stakeholders with valuable insights to monitor default trends, improve risk management processes, and optimize loan approval strategies.

## Tools Used
- **Power BI**: For creating interactive data visualizations and dashboards.
- **Excel / SQL** (if applicable): For data cleaning and preprocessing.

**Data Source**: The analysis uses a publicly available sample dataset that simulates real-world loan applications and repayment outcomes. The dataset has been adapted for analysis in Power BI for educational purposes.

## Project Objectives
- Identify borrower characteristics (e.g., income, employment type, credit score) that contribute to loan defaults.
- Examine the impact of loan purposes on default rates.
- Analyze the geographic distribution of loan defaults across U.S. states.
- Provide actionable insights to improve loan screening processes.
- Showcase advanced Power BI skills, including data modeling, DAX, and dashboard design, as part of a professional portfolio.

## Techniques Applied
- **Data Cleaning & Transformation**: Used Power Query to handle missing values, standardize column names, and transform raw loan data for analysis.
- **Data Modeling**: Built a well-structured data model in Power BI, establishing relationships between fact and dimension tables.
- **DAX (Data Analysis Expressions)**: Created custom measures to calculate key metrics such as:
  - High Risk And Low Risk(%)
  - Average Income by Loan Status
  - Total Loans by State
  - Loan Default Breakdown by Purpose
- **Interactive Visualizations**: Integrated slicers, drill-throughs, and tooltips to enhance user experience and allow for dynamic filtering by credit grade, loan purpose, and geography.
- **Geospatial Analysis**: Applied map visualizations to analyze loan performance across different U.S. states.
- **Dashboard Design**: Developed a clean, responsive layout that features KPIs, charts, and summaries for easy consumption of insights.

## Interactive Dashboard
[**Explore the Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiOTBmZGQxOGUtMTYxOC00MzAzLWIxZjgtMGIyNjE5YjllMTg4IiwidCI6ImZlNGY2MDAyLTAzMjktNGI4Yi04NTZmLThhM2YzMGRiYjhkZiJ9)

## Key Insights
1. **Higher Default Rates Among Lower Credit Grades**: Borrowers with credit grades E, F, and G exhibit significantly higher default rates compared to those in grades A–C, highlighting the importance of creditworthiness in predicting repayment behavior.
2. **Impact of Loan Purpose on Defaults**: Loan purposes such as "small business," "debt consolidation," and "renewable energy" are associated with higher default rates, likely due to greater financial uncertainty or longer ROI periods.
3. **Self-Employed Borrowers Face Higher Risk**: Self-employed individuals, as well as those with undefined employment types, have a higher tendency to default, possibly due to irregular income streams and less financial documentation.
4. **Vulnerabilities of Low-Income Borrowers with High Loan Amounts**: Borrowers earning below the median income, especially those receiving higher loan amounts, show a greater likelihood of default. This indicates a risk of over-lending in low-income segments.
5. **Geographic Hotspots for Defaults**: States like California, Florida, Texas, and New York report the highest default volumes, potentially due to high loan activity and specific economic factors. In contrast, states such as Massachusetts and Virginia display lower default rates.
6. **Minimal Impact of Loan Term**: Default rates show only a slight difference between 36-month and 60-month loan terms, suggesting that loan term alone may not be a strong predictor of default risk.

## Recommendations
1. **Refine Credit Grade Criteria**: Consider limiting loan approval or increasing interest rates for applicants with credit grades D and below, particularly if other risk factors (e.g., low income, high loan amount) are present.
2. **Incorporate Purpose-Based Risk Weighting**: Loan purpose should be integrated into risk models, with high-risk purposes (like "small business") triggering stricter screening or collateral requirements.
3. **Implement Income-to-Loan Ratio Thresholds**: Enforce minimum income-to-loan ratio policies to ensure borrowers have sufficient financial capacity to repay based on their income levels.
4. **Adjust Screening for Self-Employed Applicants**: Flag self-employed individuals for more thorough financial evaluation, requesting proof of consistent income or additional documentation.
5. **Geographic Segmentation in Risk Models**: Introduce state-level risk tiers in the approval logic, with higher-risk states requiring stricter criteria for loan approval.
6. **Deploy Predictive Modeling**: Use machine learning techniques to build models that predict loan default probability, enhancing the risk assessment process and enabling automated scoring during loan approvals.

## Conclusion
This loan default analysis reveals several critical factors that lenders should consider when evaluating risk: borrower credit grade, loan purpose, employment type, income levels, and geographic location. By leveraging these insights, financial institutions can adopt smarter lending strategies to reduce default risks and improve overall portfolio health. The interactive dashboard enables stakeholders to identify high-risk segments quickly and make data-driven decisions.

## Author
**Amarachi Amankwe**  
Data Analyst | Excel & Power BI Enthusiast | Storytelling with Data  
Project developed using Microsoft Power BI, based on publicly available data for educational and portfolio purposes.
