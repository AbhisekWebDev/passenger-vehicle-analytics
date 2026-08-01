# passenger-vehicle-analytics
# 🚗 Global & Indian Passenger Vehicle Market Analytics

An exploratory data analytics project examining global automotive production dynamics, powertrain transitions, and the rapid rise of Electric Vehicles (EVs) in India. This project demonstrates the complete data lifecycle—from initial Excel cleansing and SQL querying to Python data manipulation (Pandas) and visualization (Matplotlib).

---

## 📌 Project Overview

This repository analyzes multi-year passenger car data across two core dimensions:
1. **Global Production Trends (2019 – 2026):** Leveraging International Organization of Motor Vehicle Manufacturers (OICA) dataset to evaluate post-pandemic recovery and market leadership across major vehicle-producing nations.
2. **Electric Vehicle (EV) Adoption in India (2010 – 2023):** Utilizing the International Energy Agency (IEA) Global EV Dataset to track the shift toward pure Battery Electric Vehicles (BEVs) versus Plug-in Hybrids (PHEVs).

---

## 📊 Key Analytical Insights

* **China Dominates Production Volume:** Q1 2026 data shows China producing ~5.9M passenger cars, outstripping the next four major regions combined.
* **India's Accelerated Growth:** India experienced a **~46% production growth** between Q1 2022 (~1.08M units) and Q1 2026 (~1.57M units), making it the fastest-growing major manufacturing hub in the dataset.
* **Pure BEVs Lead India's EV Surge:** Analysis of 12,000+ records from IEA reveals that India's passenger EV market heavily favors pure BEVs over PHEVs, spiking from ~3,100 units in 2020 to over **82,000 units in 2023**.

---

## 🛠️ Tech Stack & Methodology

* **Data Cleaning & Wrangling:** Microsoft Excel, Python (Pandas, NumPy)
* **Database & Querying:** SQLite (`sqlite3` in-memory database)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab, Jupyter Notebooks

---

## 📁 Repository Structure

```text
passenger-vehicle-analytics/
├── passenger_car_analysis.ipynb          # ETL pipeline, SQL queries, and Global Production charts
├── passenger_car_analysis_ev_trend.ipynb # Real Kaggle/IEA dataset analysis on Indian EV trends
├── IEA Global EV Data 2024.csv            # Supplementary dataset from IEA/Kaggle
└── README.md                             # Project documentation
