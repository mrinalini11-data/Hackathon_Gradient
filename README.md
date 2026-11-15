# Hackathon_Gradient
# ⚡ VoltRelay Energy: Why Is Growth Not Turning Into Profit?

Analysis of ~3.9M battery swaps across 6 Indian cities (Jan 2024 to Jun 2025).
Built for the Gradient Learnings Data Analytics Hackathon.

## Problem
Swaps and revenue are growing, but failures are rising faster, new riders are leaving, and profit per swap is shrinking. Leadership doesn't know why or where to invest.

## What I Did
- Cleaned 8 datasets: firmware timestamp bug, duplicate swaps, test stations, city spellings, bad sensor readings, missing telemetry
- Built KPIs with clear formulas: revenue, margin per swap, failure rate, queue time, retention
- Found where failures are concentrated (stations, hours, equipment)
- Tested the pricing pilot with difference-in-differences
- Analysed new-rider churn with cohorts and regression

## Key Findings
1. Swaps grew [X]x, but margin per swap changed [±X%].
2. Failure rate rose from [X%] to [Y%]; the worst 10% of stations cause [X%] of failures.
3. Churn is most linked to [factor].
4. The largest fleet partner ranks #[X] by revenue but #[Y] by margin.

## Recommendation
1. Fix reliability at busy stations first
2. Add batteries only where stockouts are proven
3. Roll out pricing only if the pilot supports it
4. Don't sign the exclusive fleet deal until its margin beats [benchmark]

## Run It
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
jupyter notebook voltrelay_analysis.ipynb
```
Put the 8 data files in `./data` and set `DATA_DIR` in the first cell.

## Note
Data is synthetic and observational, so results show association, not proven cause. Data files are not included in this repo.

**Author:** Mrinalini Tripathi
