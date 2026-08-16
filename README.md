# AirCast-Delhi-AI-Powered-Air-Quality-Forecasting-System

AirCast Delhi is a machine learning system that forecasts **ground-level O₃ (Ozone) and NO₂ (Nitrogen Dioxide) concentrations** for **7 monitoring sites across Delhi, up to 24 hours in advance**, using satellite observations, reanalysis data, historical pollution data, and machine learning.

---

##  Problem Statement

Short-term **24-hour hourly forecasting** of ground-level O₃ and NO₂ using:

* **SAC-ISRO reanalysis data**
* **Sentinel-5P satellite observations**
* Historical air-quality observations
* Meteorological and temporal features

Accurate air-quality forecasts can enable **early warnings, better environmental decision-making, and improved pollution monitoring** in highly polluted urban areas.

---

##  Features

* **24-hour hourly O₃ and NO₂ predictions**
* **Site-specific forecasts** for 7 Delhi monitoring locations
* Integration of **satellite and reanalysis data**
* Temporal and lag-based feature engineering
* Machine learning-based forecasting using **XGBoost and LightGBM**
* Interactive **Streamlit dashboard**
* Visualization of site-wise pollution trends and forecasts
* Data-driven insights for environmental monitoring

---

##  Machine Learning Approach

The project uses an ensemble of:

* **XGBoost**
* **LightGBM**

Temporal, meteorological and lag-based features are engineered from the available datasets to capture historical pollution patterns and improve forecasting performance.

The final predictions are generated using a **weighted ensemble of XGBoost and LightGBM models**.

---

##  Dashboard

The project includes an interactive **Streamlit dashboard** that allows users to explore:

* O₃ and NO₂ forecasts
* Site-wise pollution levels
* Historical pollution trends
* Forecasted pollution patterns
* Model performance and relevant insights

### Run Locally

```bash
streamlit run app.py
```

---

##  Technologies Used

**Python | XGBoost | LightGBM | Pandas | NumPy | Feature Engineering | EDA | Data Preprocessing | Streamlit | GitHub**

---

## 🌍 Project Objective

The primary objective of AirCast Delhi is to develop a data-driven system capable of providing **short-term air-quality forecasts** that can support pollution monitoring, early-warning systems, and informed environmental decision-making.
