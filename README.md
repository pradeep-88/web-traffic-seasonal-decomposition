# Seasonal Decomposition of Web Traffic

## Objective
Analyze and decompose daily website traffic into trend, seasonality, and residual components using time-series decomposition techniques.

## Dataset
Daily e-commerce website traffic data including page views, ad spend, weekend, and holiday indicators.

## Tech Stack
- Python
- pandas
- statsmodels
- matplotlib

## Methodology
- Cleaned and indexed daily time-series data
- Applied additive and multiplicative seasonal decomposition (period = 7)
- Compared models using residual variance
- Identified anomaly candidates from residuals
- Interpreted anomalies using ad spend and temporal factors

## Key Insights
- Strong weekly seasonality observed
- Multiplicative model provided better fit
- Residual spikes aligned with high ad spend and weekends

## To Run
Open the notebook and run all cells sequentially.

