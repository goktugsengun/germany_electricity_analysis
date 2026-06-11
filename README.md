# Solar's Impact on the German Electricity Market

An exploratory data analysis of how the growth of solar energy is reshaping electricity prices in Germany, using 15-minute interval data from 2020 to 2025.

## Dashboard

👉 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/g.ktu.eng.n/viz/Project-Electricity/SolarsImpactontheGermanElectricityMarket)

## Key Findings

- Solar production in Germany nearly doubled between 2020 and 2025
- Higher solar output consistently correlates with lower spot prices — when solar peaks at midday, prices drop to their daily minimum
- Since 2023, renewable energy has surpassed fossil fuel production for the first time
- Intraday analysis shows a clear inverse relationship: prices peak at ~19:00 when solar output falls to zero, creating a strong incentive for battery storage solutions
- Seasonal pattern: summer months bring both peak solar output and lowest average prices

## Data Sources

Both datasets are publicly available from [SMARD.de](https://www.smard.de/home/downloadcenter/download-marktdaten/) (German Federal Network Agency):

- **Realisierte Erzeugung** — Actual electricity production by source (15-min intervals)
- **Großhandelspreise** — Day-ahead spot prices (15-min intervals)

Period: January 2020 – December 2025

## Tools

- **Python** — Data cleaning, preprocessing, and EDA (Pandas, Matplotlib, Seaborn)
- **Tableau** — Interactive dashboard

## Project Structure

```
germany-electricity-analysis/
│
├── germany_electricity_analysis.ipynb   # Full analysis notebook
└── README.md
```

## How to Run

1. Download the raw data from SMARD.de (links above)
2. Place the CSV files in the same directory as the notebook
3. Run all cells in order
