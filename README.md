# 📊 Stock Analysis Platform (Lab 2)

This project is an end-to-end data analytics system built to analyze and visualize historical stock data using **Apache Airflow**, **Snowflake**, **dbt**, and **Tableau**. It automates data ingestion, transformation, and visualization for actionable insights, supporting investment decisions with metrics like **Moving Averages**, **RSI**, and **Momentum**.

---

## 🚀 Project Structure

```bash
STOCK_ANALYSIS_DBT_LAB2/
├── airflow/                # Airflow DAGs and pipeline scripts
│   └── etl_full_refresh_stock_prices.py
├── dbt/                    # dbt project for ELT logic
│   ├── models/
│   │   ├── stock_metrics.sql
│   │   └── ...
│   └── dbt_project.yml
├── datasets/               # CSV data sources (Moving Average, RSI)
│   ├── MovAvg_14_50.csv
│   └── RSI_14_50.csv
├── screenshots/            # Visuals of dashboard, DAG, dbt CLI
│   ├── airflow_dag.png
│   ├── tableau_dashboard_1.png
│   └── ...
└── README.md               # This file
