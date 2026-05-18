# Equinor-Financial-Green-Energy-Analysis
Equinor Financial &amp; Green Energy Analysis (2020–2024) - How much of Equinor's capital expenditure is shifting toward renewables vs oil &amp; gas — and is the green transition reflected in their financials?
---

## Project summary

Equinor is one of Europe's largest energy companies and a major supplier of oil and gas to Europe. In recent years the company has publicly committed to growing its renewable energy portfolio — including offshore wind, solar, and carbon capture. This project analyses five years of publicly reported financial data to assess how that commitment is reflected in actual capital allocation, revenue, and emissions intensity.

The analysis is intended to demonstrate the kind of financial and strategic insight relevant to energy sector, ESG, and investment analyst roles.

---

## Key questions

- How has revenue and net income changed between 2020 and 2024?
  Equinor's revenue collapsed to $45.8B in 2020 during the covid downturn before surging to an all-time high of $150.8B in 2022, driven by the European energy crisis. By 2024 revenue had normalised to $103.8B. Net         income followed the same arc — a $5.5B loss in 2020, a record $28.7B profit in 2022, falling back to $8.8B by 2024. The 2022 windfall funded much of Equinor's transition investment; the subsequent decline has put        pressure on green spending.
- What proportion of capital expenditure is allocated to renewables vs oil & gas?
  Renewables capex has grown from 4% of total spend in 2020 to 20% in 2023 — meaningful progress, but still a long way from the stated ambition. Equinor had pledged to allocate more than 50% of gross capex to              renewables and low-carbon solutions by 2030, with an interim target of 30% by 2025. Both targets look increasingly out of reach: in early 2025 Equinor halved its renewables budget to $5B for 2025–27 and formally         dropped the 50% capex target.
- Is renewable energy production (GWh) growing year on year?
  Yes — consistently. Equity renewable power production has grown every single year.
- How has CO2 emissions intensity changed over the same period?
  Upstream CO2 intensity has improved steadily from 8.0 kg CO₂/boe in 2020 to 6.2 kg CO₂/boe in 2024 — already close to the 2030 ambition of 6.0 kg/boe and well below the industry average of ~16 kg/boe. Equinor's net      carbon intensity (including scope 1, 2 and 3) is now 2% below the 2019 baseline. However, scope 3 emissions from products sold remain at ~250–251 million tonnes per year — essentially flat since 2020 — and represent     the vast majority of Equinor's total climate footprint.
- Does the financial data support Equinor's stated green transition commitments?
  Partially. The operational data shows genuine progress: CO2 intensity is falling, renewable output is growing, and Equinor remains well below industry peers on emissions per barrel. But the strategic picture is more     complicated.
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

Equinor's revenue peaked at $150.8bn in 2022 driven by post-Ukraine energy price spikes before returning to $107.2bn in 2023, while renewable power production grew steadily from 1,662 GWh in 2020 to 2,935 GWh in 2024 — a 77% increase. CO₂ intensity has declined consistently from 7.0 kg/boe in 2021 to 6.2 in 2024, already below the 2025 target of 8 kg/boe and closing on the 2030 target of 6 kg/boe. Renewables capex as a share of gross investment grew from 14% in 2022 to 20% in 2023, though the 2025 target of 30% remains a significant step up from current levels.

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
