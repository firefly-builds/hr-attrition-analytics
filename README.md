# HR Attrition Analytics

**Business question:** Why are employees leaving — and which teams are at risk next?

## Live Dashboard
[View on Tableau Public](YOUR_TABLEAU_URL_HERE)

## Summary
Analyzed IBM HR Analytics dataset (1,470 employees) to identify attrition 
drivers and at-risk departments. Built end-to-end pipeline: PostgreSQL for 
SQL analysis, Python (pandas) for EDA, Tableau Public for KPI dashboard.

**Attrition rate: 16.12%** | **Highest-risk dept: Human Resources (20.63%)** 
| **Top driver: Overtime burden**

## Key Findings
1. Human Resources has the highest attrition at 20.63%
2. Employees working overtime leave at nearly 3x the rate of non-overtime employees
3. Employees who left earned $2,045/month less on average than those who stayed
4. Sales department shows the highest overtime + attrition combination — flagged as critical risk

## Tools
- PostgreSQL — SQL analysis and data storage
- Python (pandas, matplotlib, seaborn) — EDA and CSV exports
- Tableau Public — KPI dashboard and visualization

## Files
- `sql/` — SQL query files (exploration, attrition analysis, predictors)
- `python/hr_eda.ipynb` — EDA notebook with visualizations
- `exports/` — CSV files used for Tableau dashboard
- `docs/` — findings memo (coming soon)

## Resume Bullet
Analyzed HR attrition across 1,470 employees using PostgreSQL and Tableau; 
identified Human Resources as highest-risk department at 20.63% attrition, 
with overtime burden and $2,045 salary gap as primary drivers.
