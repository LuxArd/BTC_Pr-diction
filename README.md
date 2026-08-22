# Bitcoin Price Forecasting

## Data Science Course Project - Pilot Study

This repository documents an educational pilot study that explores historical Bitcoin price forecasting with time-series and machine-learning techniques.

It is a course project, not a trading system, investment product, or financial recommendation.

## Project status

The original course work was completed with historical data available through January 2024. This portfolio edition documents the project scope, data dependencies, and limitations before any new performance claims are made.

No past metric in the original notebook should be interpreted as a current or independently validated forecasting result.

## Research question

Can selected historical market and on-chain variables be used to explore a five-day-ahead Bitcoin price forecasting task?

## Original study scope

- Target: a five-day-ahead Bitcoin price value.
- Data: historical Bitcoin, selected on-chain indicators, and selected market variables.
- Approaches explored: regression models, tree-based ensembles, neural-network models, and SARIMAX.
- Time coverage in the source material: Bitcoin-related data from 2009 through January 2024; selected market data from 2015 through January 2024.

## What this repository does and does not show

This repository is a transparent project record. It documents the original analytical direction and the work required for a reproducible, time-aware refresh.

It does not claim:

- profitable trading performance;
- investment suitability;
- a live or production-ready forecasting service;
- current prediction accuracy;
- medical, financial, or professional advice of any kind.

## Documentation

- DATA_SOURCES.md - the source categories and access boundaries.
- REPRODUCIBILITY.md - how the original study can be reconstructed responsibly.
- LIMITATIONS.md - the important methodological and portfolio limitations.
- requirements.txt - the Python package families used by the original study.
- notebooks/bitcoin_price_forecasting_course_project.ipynb - the English, output-free portfolio notebook.
- presentation/bitcoin-price-forecasting-course-project.pdf - the English portfolio presentation.

## Planned methodological refresh

Before any revised metric is published, the working version will:

1. keep data preparation strictly within each training window;
2. use walk-forward validation or TimeSeriesSplit;
3. report errors in the original price scale as well as any transformed scale;
4. retain an untouched final holdout period;
5. document exact data retrieval dates and package versions.

## Disclaimer

This is an educational Data Science course project and pilot study. Cryptocurrency markets are volatile. Nothing in this repository is financial advice, investment advice, or a recommendation to buy, sell, or hold any asset.
