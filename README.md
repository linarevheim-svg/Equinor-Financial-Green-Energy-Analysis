# Equinor-Financial-Green-Energy-Analysis
Equinor Financial &amp; Green Energy Analysis (2020–2024) - How much of Equinor's capital expenditure is shifting toward renewables vs oil &amp; gas — and is the green transition reflected in their financials?
---

## Project summary

Equinor is one of Europe's largest energy companies and a major supplier of oil and gas to Europe. In recent years the company has publicly committed to growing its renewable energy portfolio — including offshore wind, solar, and carbon capture. This project analyses five years of publicly reported financial data to assess how that commitment is reflected in actual capital allocation, revenue, and emissions intensity.

The analysis is intended to demonstrate the kind of financial and strategic insight relevant to energy sector, ESG, and investment analyst roles.

---

## Key questions

- How has Equinor's revenue and net income changed between 2020 and 2024?
- What proportion of capital expenditure is allocated to renewables vs oil & gas?
- Is renewable energy production (GWh) growing year on year?
- How has CO2 emissions intensity changed over the same period?
- Does the financial data support Equinor's stated green transition commitments?

---

## Tools used

| Tool | Purpose |
|------|---------|
| Python (pandas, matplotlib) | Data cleaning, trend analysis, visualisations |
| SQL (BigQuery) | Aggregation and year-on-year calculations |
| Tableau Public | Interactive financial dashboard |
| Excel / CSV | Manual data entry from annual reports |

---

## Data sources

| Dataset | Source | Licence |
|---------|--------|---------|
| Equinor Annual Reports 2020–2024 | [equinor.com/investors/annual-reports-archive](https://www.equinor.com/investors/annual-reports-archive) | Public |
| Equinor ESG / Sustainability Data | [equinor.com/sustainability](https://www.equinor.com/sustainability) | Public |

All data is sourced directly from Equinor's publicly published annual reports and sustainability disclosures. No proprietary or non-public data is used.

---

## Data governance & ethics

**Public financial data only.** All figures are drawn from Equinor's official published annual reports, which are freely available and intended for public use by investors, analysts, and researchers.

**No forward-looking claims.** This analysis is retrospective only. No investment advice is given or implied. All figures are reported in USD millions as published by Equinor.

**Limitations.** Segment definitions and accounting policies may change year on year. Where Equinor has restated prior figures, the restated values are used. Green energy capex figures represent Equinor's reported Renewables & Low Carbon Solutions segment only — some cross-segment green investments may not be captured.

**Attribution.** All financial figures cited in this analysis are sourced from Equinor ASA official publications and should be verified against the original reports before use in any formal context.

---

## Key findings

*(To be completed after analysis)*

---

## Project structure

```
├── data/
│   └── equinor_financials_2020_2024.csv
├── sql/
│   └── equinor_analysis.sql
├── notebooks/
│   └── equinor_analysis.ipynb
└── dashboard/
    └── tableau_public_link.md
```

---

## Dashboard

[View on Tableau Public](#) 
https://public.tableau.com/authoring/Equinor-Financial-Green-Energy-Analysis/CO2IntensityvsTargets/Equinor%20%E2%80%94%20Financial%20%26%20Green%20Energy%20Analysis%202020%E2%80%932024#2

---

## What I'd do next

- Add share price data to correlate green investment announcements with market reaction
- Compare Equinor's green capex % against BP, Shell and TotalEnergies
- Model future capex scenarios based on stated 2030 targets
