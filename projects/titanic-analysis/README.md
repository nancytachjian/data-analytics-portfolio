# Titanic Survival Analysis

This project explores the Titanic dataset to analyze which factors influenced passenger survival.

## Tools Used
- Python (Pandas, Matplotlib/Seaborn)
- SQL (for querying structured data)
- Tableau (for dashboard visualization)

## Project Steps
1. Data cleaning and preprocessing
2. Exploratory data analysis (EDA)
3. Feature analysis: gender, class, age
4. Survival rate visualization

## Dashboard
(Tableau link will be added here)


## Key Findings

- Passenger class had a major impact on survival outcomes. First-class passengers had nearly *3x higher survival rate* compared to third-class passengers.
- When analyzing percentages instead of raw counts, first-class survival becomes even more significant (~60%).
- Age also played a critical role:
  - *Second-class children:* 100% survival rate  
  - *First-class children:* 80%  
  - *Third-class children:* 40%
- Senior passengers (65+) had extremely low survival across classes:
  - *First class seniors:* 17% (1 survivor only)  
  - *Second & third class seniors:* 0% survival

## Recommendations
- Improve emergency accessibility for lower classes to reduce survival inequality.
- Prioritize evacuation planning for vulnerable groups (children & seniors).
- A follow-up statistical test (e.g., chi-square) is recommended to verify whether the class-based survival differences are statistically significant.

