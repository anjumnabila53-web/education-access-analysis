# Education Access in Developing Countries: Trends & Disparities

An exploratory data analysis of global education enrollment trends using World Bank open data, with a focus on developing countries and SDG 4 (Quality Education).

## Key Findings

- Low-income countries have made significant progress in **primary school enrollment** since 2000
- However, a large **primary-to-secondary drop-off** persists, the most critical gap remaining
- **Sub-Saharan Africa and South Asia** consistently show the lowest enrollment rates across both levels
- The data suggests policy focus should shift from access to primary education → **retention through secondary level**

## Charts

| Chart | Description |
|-------|-------------|
| `chart1_primary_enrollment_by_income.png` | Primary enrollment trends by income group (2000–2023) |
| `chart2_primary_vs_secondary_gap.png` | Primary vs secondary enrollment gap in low-income countries |
| `chart3_enrollment_by_region.png` | Regional snapshot of primary enrollment rates |

## Tools & Data

- **Python** (Pandas, Matplotlib, Seaborn, Requests)
- **Data:** [World Bank Open Data](https://data.worldbank.org) — Indicators `SE.PRM.ENRR` and `SE.SEC.ENRR`
- Data license: CC BY 4.0

## How to Run

```bash
pip install pandas matplotlib seaborn requests
jupyter notebook education_access_analysis.ipynb
```

The notebook fetches data live from the World Bank API — no manual download needed.

## Relevance to SDGs

This project directly supports analysis of **SDG 4: Quality Education**, one of the UN's 17 Sustainable Development Goals. Understanding enrollment disparities is essential for designing effective education interventions in developing countries.
