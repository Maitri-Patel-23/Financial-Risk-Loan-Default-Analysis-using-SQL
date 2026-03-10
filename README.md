Key Business Insights & Strategic Recommendations:

| Insight                                                              | Explanation                                                                                                                        | Actionable Recommendation                                                                                   |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **High-risk borrowers hold the largest share of loan exposure**      | Risk segmentation based on credit score shows that a significant portion of loan amounts are issued to higher-risk borrowers       | Financial institutions should review lending thresholds and apply stricter credit checks for these segments |
| **Borrowers with multiple existing EMIs receive lower loan amounts** | Loan exposure decreases significantly as the number of existing EMIs increases                                                     | Use EMI burden as an important factor in loan approval decisions                                            |
| **Loan exposure varies across cities**                               | Cities like Delhi and Chennai show higher average loan amounts compared to others                                                  | Regional lending policies may be adjusted based on borrower behavior and credit demand                      |
| **Credit risk segmentation highlights portfolio concentration**      | Categorizing borrowers into Very High, High, Medium, and Low risk segments helps identify risk concentration in the loan portfolio | Banks can rebalance lending across risk categories to reduce portfolio risk                                 |


# Loan Default Analysis

This project performs a comprehensive loan default risk analysis using SQL for data preparation and analysis and Microsoft Power BI for interactive dashboard visualization.

The goal of this project is to analyze borrower financial profiles, identify key drivers of loan defaults, and provide insights that can help financial institutions improve credit risk assessment and lending strategies.

The analysis covers:
- Data cleaning and preprocessing of raw loan data using SQL
- Risk segmentation based on credit score categories
- Loan portfolio exposure analysis by risk category
- Analysis of loan distribution across borrowers with existing EMIs
- Geographic analysis of average loan amount by city
- Identification of patterns associated with potential loan default risk
- Interactive dashboard development to highlight key financial insights


Dashboard Visualizations:

The dashboard created in Microsoft Power BI includes:
- Loan Amount by Risk Category – identifies loan exposure across risk segments
- Loan Amount by Existing EMIs and Default Status – shows relationship between borrower obligations and loan distribution
- Average Loan Amount by City – highlights geographic patterns in lending behavior
- These visualizations help convert raw financial data into actionable insights for credit risk management.

---

## Project Structure
Financial-Credit-Risk-Analysis
│
├── data
│   └── train.csv              # Raw loan dataset
│
├── sql
│   └── loan_analysis.sql      # SQL queries for data cleaning and analysis
│
├── powerbi
│   └── loan_dashboard.pbix    # Power BI dashboard file
│
└── README.md                  # Project documentation
