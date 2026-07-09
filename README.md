# India Banking Fraud Intelligence — Detection & Risk Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Domain](https://img.shields.io/badge/Domain-Financial%20Crime%20Analytics-red)
![Status](https://img.shields.io/badge/Status-Complete-green)

## Overview

Banking fraud in India has reached alarming levels. The Reserve Bank of India (RBI)
reported fraud losses of **Rs.21,367 crore in H1 FY2024-25** — an **8x increase**
year on year. Fraud cases tripled in 2024 compared to 2023.

This project builds an end-to-end **Banking Fraud Intelligence System** using Python,
covering fraud detection, transaction risk scoring, and regulatory compliance auditing.

---

## Project Structure

```
india-banking-fraud-intelligence/
│
├── India_Banking_Fraud_Intelligence.ipynb   ← Main notebook (run on Google Colab)
└── README.md
```

---

## What This Project Covers

### Section 1 — India Fraud Landscape
- RBI fraud trend analysis 2019 to 2025
- Fraud type distribution and trend classification
- Key insight: Fewer cases but 8x larger fraud amounts in FY2024-25

### Section 2 — Ponzi Scheme Detector (IMA Karnataka Case Study)
- ML model (Random Forest) trained on 8 Ponzi red-flag features
- ROC-AUC above 0.95
- IMA Scam profile (Rs.4,000 crore, 105 bank accounts) scores ~89% Ponzi probability
- Key finding: Early detection in 2015 could have prevented Rs.4,000 crore in losses

### Section 3 — Suspicious Transaction Risk Scorer
- 8-rule transparent scoring engine aligned to PMLA (Prevention of Money Laundering Act)
- Flags: High value, round amount structuring, unusual hours, cross-border, layering
- Explainable by design — suitable for regulatory and legal proceedings

### Section 4 — Regulatory Compliance Auditor
- 15-point checklist covering RBI, SEBI, PMLA, Income Tax, KYC
- IMA Compliance Score: 7% (1 out of 15 checks passed) = CRITICAL RISK
- Compliant NBFC Score: 100% = LOW RISK

### Section 5 — Summary and Recommendations
- Policy recommendations for RBI and regulatory bodies
- Tools, frameworks, and references used

---

## IMA Scam — Key Facts

| Detail | Value |
|--------|-------|
| Founder | Mansoor Khan |
| Total amount received | Rs.4,000 crore across 105 bank accounts |
| Promised returns | 24 to 36% per annum vs RBI benchmark ~9% |
| Regulatory gap | Called investors 'partners' to bypass PIDFE Act |
| RBI first suspected | 2015 — action taken only in 2019 (4-year gap) |
| State | Karnataka, India |

---

## Tools and Technologies

| Category | Tools |
|----------|-------|
| Language | Python 3.10 |
| Data Manipulation | Pandas, NumPy |
| Machine Learning | Scikit-learn (Random Forest), roc_auc_score |
| Visualisation | Matplotlib, Seaborn |
| Regulatory Frameworks | RBI Master Directions, PMLA 2002, Karnataka PIDFE Act, SEBI Regulations |

---

## How to Run

### Option 1 — Google Colab (Recommended)
1. Download `India_Banking_Fraud_Intelligence.ipynb`
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. File → Upload notebook → Select the file
4. Runtime → Run All

### Option 2 — Local Jupyter
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook India_Banking_Fraud_Intelligence.ipynb
```

---

## Key Findings

- India banking fraud losses increased **8x** in H1 FY2024-25 despite fewer cases
- Account Takeover accounts for **55%** of all fraud in India
- IMA Scam profile scores **~89% Ponzi probability** in the detection model
- IMA passed only **1 out of 15** regulatory compliance checks
- Transparent rule-based transaction scoring is preferred for **legal admissibility**

---

## Regulatory Framework Applied

- RBI Master Directions on Fraud Classification and Reporting (Updated 2023)
- Prevention of Money Laundering Act (PMLA) 2002
- Karnataka Protection of Interest of Depositors (PIDFE) Act
- SEBI Investment Adviser Regulations 2013
- Know Your Customer (KYC) Master Directions — RBI

---

## References

1. Reserve Bank of India — Report on Trend and Progress of Banking in India 2024-25
2. BioCatch — 2025 Digital Banking Fraud Trends in India
3. Wikipedia — IMA (I Monetary Advisory) Scam Karnataka
4. RBI Master Directions on Fraud Classification (2023)
5. KYCHub — Top 15 Banking Frauds in India 2025

---

## Disclaimer

All ML model data is synthetically generated for educational and demonstration purposes.
IMA case study analysis is based on publicly available information only.

---

## Author

**Sendhil Kumar S**
Senior L&D Manager | Finance & Analytics Professional | Bengaluru

- GitHub: [github.com/Sendhil0kumar](https://github.com/Sendhil0kumar)
- LinkedIn: [linkedin.com/in/sendhil0kumar](https://linkedin.com/in/sendhil0kumar)

---

*If you found this project useful, please give it a star!*

