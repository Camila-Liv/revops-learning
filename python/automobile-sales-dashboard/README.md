# Automobile Sales Performance Dashboard

An interactive dashboard built with Python and Plotly Dash analyzing historical 
automobile sales data from 1980–2013, with a focus on recession impact, 
advertising efficiency, and vehicle segment performance.

## Overview

This project explores how macroeconomic conditions — particularly recession periods — 
affect automobile sales across vehicle segments. The dashboard enables dynamic 
filtering between yearly trends and recession-specific insights, simulating the kind 
of revenue intelligence reporting used in sales operations and RevOps environments.

## Business Questions Answered

- How do automobile sales fluctuate during recession vs. non-recession periods?
- Which vehicle segments are most resilient during economic downturns?
- How does advertising expenditure correlate with sales performance?
- What is the relationship between unemployment rate and vehicle sales by segment?
- How does consumer confidence impact purchasing behavior during recessions?

## Dashboard Features

**Yearly Statistics Report**
- Yearly automobile sales trend (1980–2013)
- Monthly sales breakdown for any selected year
- Average units sold by vehicle type
- Advertising expenditure share by vehicle segment

**Recession Period Statistics**
- Sales fluctuation across all recession years
- Vehicle type performance during downturns
- Ad spend distribution during recession periods
- Unemployment rate impact on sales by segment

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data wrangling and aggregation |
| Plotly Express | Chart generation |
| Dash | Interactive web dashboard framework |
| Matplotlib / Seaborn | Exploratory analysis |

## Key Findings

- Smaller, affordable vehicle segments (SuperMiniCar, SmallFamilyCar) show 
  greater recession resilience than executive or sports vehicles
- Advertising expenditure is significantly reduced during recessions, potentially 
  compounding sales decline
- Consumer confidence is a stronger predictor of sales than advertising spend 
  during economic downturns
- Unemployment rate above ~7% correlates with measurable drops across all segments

## How to Run

```bash
pip install dash pandas plotly
python DV0101EN-Final-Assign-Part-2-Questions.py
```

Then open `http://127.0.0.1:8050` in your browser.

## Data Source

IBM Developer Skills Network — Automobile Sales Dataset  
Variables include: Recession indicator, GDP, Consumer Confidence, 
Unemployment Rate, Advertising Expenditure, Vehicle Type, and monthly sales figures.

## Author
**Camila Livia**
[LinkedIn](https://www.linkedin.com/in/camilalivia/)
