# Employee Attrition Analysis
**IBM HR Analytics Employee Attrition & Performance**

## Project Overview
Employee attrition is an indication of several underlying issues, such as poor management and communication, which are often neglected. Ignoring them poses a significant and potentially fatal risk to a company. 

For this project, I explored the IBM HR Analytics dataset (1,470 employees) to determine the core reasons leading to employee attrition and how it can be predicted and prevented. The aim is to identify key factors that HR professionals can use to develop effective retention policies.

## Repository Structure
```text
Employee-Attrition-Analysis/
│
├── data/
│   └── employee-attrition.csv           # Raw dataset
│
├── analysis/
│   └── employee-attrition-analysis.xlsx # Cleaned data, Pivot Tables, and Dashboard
│
├── report/
│   └── final-report.pdf                 # Full presentation and strategic recommendations
│
├── visuals/
│   └── charts.png                       # Exported dashboard visualizations
│
└── README.md                            # Project documentation
```

## Data Preprocessing & Tools
* **Tool Used:** Spreadsheet software (Excel / Google Sheets) for data cleaning, modeling, and visualization.
* **Data Cleaning:** Checked and removed duplicate and missing values using conditional formatting and filtering.
* **Advanced Formulas:** Created mapping tables using `XLOOKUP` and bucketed tenure ranges using `ARRAYFORMULA`.

## Key Insights
1. **Financial & Performance Factors:** High Monthly Income and strong Performance Ratings are the most effective retention tools. Employees in lower income brackets (Under $5K) and those with lower performance ratings are significantly more likely to leave.
2. **Early Career Vulnerability:** Tenure is a major predictor of attrition. Employees in the early stages of their career at the company (less than 5 years) have the highest attrition rates (approx. 24%).
3. **The Satisfaction Paradox:** Employees reporting "High" job satisfaction exhibited a higher-than-average attrition rate (26%), suggesting turnover for this group is driven by a lack of growth opportunities or skill development rather than distress.
4. **Work Environment Matters:** Employees with poor relationship satisfaction and a "Bad" work-life balance (31% attrition) are significantly more likely to depart.

## Strategic Recommendations
To proactively reduce continuous turnover costs and stabilize the workforce, HR teams and leadership should:
* **Focus on early support:** Build robust support systems and onboarding for new hires in their first three years.
* **Review compensation:** Prioritize competitive compensation, especially for the lower-paid segments of the workforce.
* **Foster a supportive environment:** Emphasize structured performance recognition, clear career development paths, and sustainable work-life balance initiatives.

---
**Prepared by:** [Anuraag K.V](https://www.linkedin.com/in/anuraag-kv) | [GitHub](https://github.com/A-Icon23)
