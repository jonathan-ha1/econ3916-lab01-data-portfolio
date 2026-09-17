# The Data Portfolio — Big Mac Index Analysis

## Objective

This project evaluates global currency valuation by applying the Big Mac Index framework to 57 countries across a 24-year panel (2000–2026), using purchasing power parity theory to identify systematic over- and under-valuation in exchange rates.

## Methodology

- Sourced raw Big Mac Index data (57 countries, 45 time periods spanning July 2000 to July 2026) directly from The Economist's public GitHub repository
- Computed implied PPP exchange rates and derived valuation percentages relative to actual market exchange rates
- Classified the dataset's structure across cross-sectional (54-country July 2024 snapshot), time series, and panel dimensions to inform appropriate analytical methods
- Conducted a missing data audit, diagnosing Russia's exit from the series as Missing Not At Random (MNAR) given its conditional relationship to geopolitical events
- Built two core visualizations: a cross-sectional bar chart of currency valuations and a longitudinal time series comparison across countries

## Key Findings

- Switzerland emerged as the most persistently overvalued currency in the sample, trading **41.8% above** PPP-implied value in the July 2024 cross-section
- Japan showed sustained undervaluation, registering below PPP-implied value in **every decade** of the series — the most consistent undervaluation pattern observed
- Together, these results illustrate durable, structural divergences from PPP that outlast short-term exchange rate fluctuations

## Data Source

[The Economist — Big Mac Index](https://github.com/TheEconomist/big-mac-data)
# econ3916-lab01-data-portfolio
