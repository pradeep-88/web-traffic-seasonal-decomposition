# 📊 Seasonal Decomposition of Web Traffic

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/pandas-Data%20Analysis-purple?logo=pandas)
![Statsmodels](https://img.shields.io/badge/statsmodels-Time%20Series-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview
This project performs **seasonal decomposition of daily e-commerce website traffic** to extract meaningful insights into **trend**, **weekly seasonality**, and **residual anomalies**. Both **additive** and **multiplicative** decomposition models are applied and compared to determine the most appropriate representation of traffic behavior.

The analysis is designed to demonstrate **practical time-series analysis skills** commonly expected in data analyst and data science roles.

---

## 🎯 Objective
- Decompose daily website traffic into:
  - **Trend** (long-term growth pattern)
  - **Seasonality** (weekly user behavior)
  - **Residuals** (anomalies and unexplained variations)
- Compare **additive vs multiplicative models**
- Identify and interpret **traffic anomalies** using contextual signals such as advertising spend, weekends, and holidays

---

## 🗂️ Dataset Description
The dataset contains **daily e-commerce website analytics** with the following features:

- `page_views` — Daily website traffic
- `ad_spend` — Daily advertising spend
- `is_weekend` — Weekend indicator
- `day_of_week` — Day name
- `is_holiday` — Holiday indicator

📅 **Frequency:** Daily  
📈 **Duration:** Multiple years  
🧪 **Type:** Time-series (tabular)

---

## 🛠️ Tech Stack
- **Python**
- **pandas** — Data manipulation
- **statsmodels** — Seasonal decomposition
- **matplotlib** — Visualization

---

## 🧠 Methodology
1. Loaded and cleaned daily time-series data
2. Converted timestamps to a proper datetime index
3. Ensured daily frequency consistency
4. Applied:
   - **Additive decomposition**
   - **Multiplicative decomposition** (period = 7)
5. Compared model fit using **residual variance**
6. Performed **residual-based anomaly detection**
7. Interpreted anomalies using:
   - Advertising spend
   - Weekend behavior
   - Holiday effects

---

## 📈 Key Insights
- Strong **weekly seasonality** observed in website traffic
- **Multiplicative decomposition** provided a significantly better fit
- Traffic spikes frequently aligned with:
  - High advertising spend
  - Weekend user activity
- Negative anomalies occurred on regular weekdays, indicating potential campaign inefficiencies or external factors

---

## 📊 Output Highlights
- Time-series visualization of daily page views
- Additive & multiplicative decomposition plots
- Quantitative model comparison via residual variance
- Anomaly tables highlighting abnormal traffic days

---

## ▶️ How to Run
1. Clone the repository
2. Open the Jupyter notebook
3. **Run all cells sequentially**

```bash
jupyter notebook



web-traffic-seasonal-decomposition/
│
├── Seasonal_Decomposition_Web_Traffic.ipynb
├── README.md
└── (optional) final_website_stats.csv
