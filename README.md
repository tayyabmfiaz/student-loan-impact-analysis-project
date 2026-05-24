# Student Loan Debt & Financial Outcomes Across Demographic Groups

**Course:** INST447, Spring 2026 | Completed by Tayyab Fiaz

## Overview
This project analyzes how student loan debt affects an individual's ability to save money and build wealth after college, broken down by age group, income, education level, and race/ethnicity. Data is sourced from the Federal Reserve Board's Survey of Consumer Finances (SCF), a triennial household survey tracking income, assets, and debts since 1989.

## Key Findings
- Education loan balances have risen significantly since 2004
- Households under 35 carry the highest debt burden relative to income
- College-educated households take on more debt but tend to have higher net worth over time
- Black households carry education debt representing a disproportionately large share of their total net worth compared to other groups

## Data Source
[Federal Reserve Board – Survey of Consumer Finances](https://www.federalreserve.gov/econres/scf/dataviz/scf/chart/#series:Education_Installment_Loans;demographic:all;population:1;units:median;range:1989,2022)

Four CSV files (by demographic group) were merged into a single unified dataset (`scf_final.csv`) covering 2004–2022.

## Files
- `student-loan-financial-outcomes-final-deliverable` — Main analysis notebook (Quarto)
- `scf_final.csv` — Cleaned, merged output dataset
- Source CSVs: `interactive_bulletin_charts_agecl_median.csv`, `_edcl_`, `_inccat_`, `_racecl4_`

## Tools used
Python · pandas · matplotlib
