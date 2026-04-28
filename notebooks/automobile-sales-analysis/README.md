# Automobile Sales Analysis — Exploratory Data Analysis

Exploratory data analysis of historical automobile sales data (1980–2013), 
examining the impact of recession periods on vehicle sales across segments, 
regions, and economic indicators.

## Overview

This notebook investigates how macroeconomic conditions affect automobile 
sales performance. Using Python's core data visualization libraries, it builds 
a series of charts that progressively tell the story of recession impact on 
the automotive industry.

## Analysis Breakdown

| Task | Chart Type | Business Question |
|------|-----------|-------------------|
| 1.1 | Line Chart | How do average sales fluctuate year over year? |
| 1.2 | Scatter Plot | Does ad spend correlate with sales in non-recession periods? |
| 1.3 | Seaborn Bar | How do vehicle segments perform during vs. outside recessions? |
| 1.4 | Subplots | How does GDP vary across recession and non-recession periods? |
| 1.5 | Bubble Chart | Which months show seasonal sales peaks? |
| 1.6 | Scatter Plot | How do consumer confidence and price affect recession sales? |
| 1.7 | Pie Chart | How does ad expenditure shift between economic periods? |
| 1.8 | Pie Chart | Which vehicle types receive the most ad spend during recessions? |
| 1.9 | Line Chart | What is the effect of unemployment rate on sales by segment? |

## Key Findings

- Sales drop sharply during recession years, most notably in 1982, 1991, and 2008
- Affordable segments (SuperMiniCar, SmallFamilyCar) are most recession-resilient
- Consumer confidence is a stronger sales predictor than advertising spend
- Ad budgets are cut during recessions, potentially worsening the sales decline
- Seasonal peaks occur in early Q1 and fall months regardless of economic cycle

## Tech Stack

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Folium (geographic visualization)

## Related Project

For the interactive dashboard version of this analysis, see:  
[`python/automobile-sales-dashboard`](../python/automobile-sales-dashboard)

## Data Source

IBM Developer Skills Network — Automobile Sales Dataset
