# Revenue Metrics Analysis

Revenue and cash-flow analysis for a gaming company, built in three stages:
exploration in PostgreSQL, metric evaluation in Python, and an interactive
Tableau dashboard.

**[Report](https://onurdoker.github.io/Revenue-Metrics-Analysis/)** · 

**[Tableau Public Dashboard](https://public.tableau.com/views/RevenueMetricAnalysis/Dashboard12?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)** ·

Dashboard preview
<img width="1584" height="886" alt="SCR-20261012-bpdw" src="https://github.com/user-attachments/assets/9fdf3829-f02c-4866-975a-84d515c2d9c1" />


## Approach

1. **Exploration (PostgreSQL):** queries to inspect the data, check quality and
   examine metric values. See [`sql/`](sql/).
2. **Metric evaluation (Python):** [metrics computed, e.g. monthly revenue,
   ARPU, ...] with pandas and [matplotlib/seaborn]. See [`notebooks/`](notebooks/).
3. **Dashboard (Tableau):** results visualized in a dashboard published on
   Tableau Public. Workbook in [`workbook/`](workbook/).

## Data

The three CSV files in [`data/`](data/) were provided by a company in the
gaming industry and consist of publicly available data without commercial
value. They are included for reproducibility and are not relicensed here.


## Repository structure

```
sql/         exploratory queries
notebooks/   metric evaluation and visualizations
workbook/    Tableau workbook
docs/        GitHub Pages report (HTML)
data/        source CSV files
```

## Limitations

- [Metric definitions and assumptions used]
- [Data gaps or quality issues found]
- No forecasting or statistical testing in this analysis
