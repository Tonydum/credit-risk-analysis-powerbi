# Data Dictionary — Credit Risk Analysis Dataset

This document describes the fields used in the Credit Risk Analysis Dashboard for the fictional lending company **LendSight Analytics**. The dataset represents individual loan applications and related borrower, credit, and loan characteristics.

---

## Customer & Demographic Fields

| Column Name | Description |
|------------|-------------|
| customer_id | Unique identifier for each loan applicant |
| age | Age of the applicant in years |
| occupation_status | Employment status of the applicant (Employed, Self-Employed, Student) |
| years_employed | Number of years the applicant has been employed (may include decimals) |

---

## Income & Financial Capacity

| Column Name | Description |
|------------|-------------|
| annual_income | Applicant’s annual income |
| savings_assets | Total reported savings or liquid assets |
| current_debt | Total outstanding debt at time of application |
| debt_to_income_ratio | Ratio of current debt to annual income |
| loan_to_income_ratio | Ratio of requested loan amount to annual income |
| payment_to_income_ratio | Estimated loan payment relative to income |

---

## Credit Profile

| Column Name | Description |
|------------|-------------|
| credit_score | Applicant’s credit score |
| credit_history_years | Length of credit history in years |
| defaults_on_file | Indicator of prior defaults (1 = Yes, 0 = No) |
| delinquencies_last_2yrs | Number of delinquencies in the past two years |
| derogatory_marks | Count of derogatory credit marks |

---

## Loan Details

| Column Name | Description |
|------------|-------------|
| product_type | Type of financial product requested (e.g., Credit Card, Personal Loan, Line of Credit) |
| loan_intent | Purpose of the loan (e.g., Education, Medical, Business, Debt Consolidation) |
| loan_amount | Requested loan amount |
| interest_rate | Interest rate offered on the loan (percentage) |

---

## Loan Outcome

| Column Name | Description |
|------------|-------------|
| loan_status | Loan decision outcome (1 = Approved, 0 = Declined) |

---

## Derived & Calculated Fields (Created in Power BI)

| Field Name | Description |
|-----------|-------------|
| Age Band | Categorizes applicants into age groups for analysis |
| Credit Score Band | Groups credit scores into standard risk tiers |
| Income Band | Segments applicants by income range |
| Employment Tenure Band | Groups applicants by length of employment |
| Credit History Band | Segments applicants by credit history length |
| DTI Band | Risk grouping based on debt-to-income ratio |
| LTI Band | Risk grouping based on loan-to-income ratio |
| Savings Coverage Ratio | Savings divided by current debt |
| Savings Coverage Band | Categorized financial cushion level |
| Risk Tier | Overall borrower risk classification (Low, Medium, High) |

---

## Notes & Assumptions
- All monetary values are represented in consistent units; currency is not specified.
- Ratio fields are provided or derived for analytical purposes and used to assess borrower risk.
- The dataset uses simulated data and does not represent real individuals or institutions.
- Calculated fields were created to support segmentation, filtering, and risk analysis in Power BI.

---
