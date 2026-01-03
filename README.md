# Credit Risk Analysis Dashboard (Power BI)

## Overview
This project presents a credit risk analysis dashboard built in Power BI to evaluate loan application outcomes, borrower risk profiles, and pricing behavior. The dashboard is designed to support decision-making for credit risk, lending strategy, and portfolio monitoring.

The analysis is based on a fictional lending company, **LendSight Analytics**, using simulated data for demonstration purposes.

---

## Business Questions
The dashboard was designed to answer the following questions:
- What is the overall health and risk profile of the loan portfolio?
- Which factors most strongly influence loan approval decisions?
- How is borrower risk priced across different loan products?
- Which customer characteristics are most associated with approval outcomes?

---

## Dashboard Structure

### 1. Portfolio Overview: Loan Performance & Risk Snapshot
Provides a high-level view of:
- Total loan applications and overall approval rate
- Average credit score and interest rate
- Delinquency prevalence among applicants
- Approval outcomes by loan product and loan intent

**Purpose:** Quickly assess portfolio health and incoming risk.

---

### 2. Credit Risk & Approval Drivers
Explores the key drivers behind approval and decline decisions, including:
- Credit score bands and approval likelihood
- Debt-to-income and loan-to-income impact
- Risk tier distribution of approvals and declines
- Concentration of declines among higher-risk applicants

**Purpose:** Explain *why* loans are approved or declined.

---

### 3. Loan Products, Pricing & Exposure
Analyzes how risk is priced and where exposure is concentrated:
- Interest rates by loan product
- Approval rates across products
- Average loan amounts and exposure
- Relationship between pricing and borrower credit quality

**Purpose:** Evaluate pricing consistency and risk exposure across products.

---

### 4. Customer Segments & Approval Drivers
Focuses on borrower characteristics and financial stability:
- Income, age, and employment tenure
- Credit history length
- Savings coverage
- Occupation status

**Purpose:** Identify which borrower traits most influence approval outcomes.

---

## Key Insights
- Credit score is the strongest predictor of loan approval outcomes.
- Approval probability declines significantly when debt-to-income exceeds key thresholds.
- High-risk applicants account for a disproportionate share of loan declines.
- Higher-risk products are priced at higher interest rates, indicating risk-based pricing.
- Savings coverage and credit history length matter more than income or occupation alone.

---

## Tools & Skills
- Power BI
- DAX (measures, calculated columns)
- Data modeling
- Credit risk analysis
- Business-focused data storytelling

---

## Repository Contents
- `dashboards/` – Power BI dashboard file (PBIX)
- `screenshots/` – Dashboard page previews
- `docs/` – Supporting documentation (data dictionary)
- `data/` – Sample or anonymized data (optional)

---

## Notes
This project uses simulated data and a fictional company for portfolio demonstration purposes. The analysis focuses on analytical thinking, dashboard design, and business insight generation rather than operational decision-making.
