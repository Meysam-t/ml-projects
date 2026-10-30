# ML & Analytics Projects

End-to-end data science projects I designed and built for a large residential real estate portfolio: marketing analytics, customer satisfaction analytics, and utility anomaly detection — covering the full ML lifecycle.

## Projects

- **Ad Source Contribution Analysis** (`ad_source_contribution_rate_01.ipynb`) — leads are cleaned and merged with contracts to compute monthly, per-site contribution rates by advertising channel, plus overall conversion rates. Stack: pandas, PySpark, MLflow, Delta Live Tables.
- **Utility Gas Anomaly Detection** (`utility_anomaly_detection_gas_04.ipynb`) — yearly gas consumption patterns are clustered with dynamic time warping (DTW), then anomalous years and months are flagged with an ensemble of clustering, IQR, and standard-deviation methods. Stack: pandas, scikit-learn, tslearn, MLflow.
- **Resident Satisfaction Analytics** (`satisfaction/`) — a four-notebook pipeline from ticket preprocessing to efficiency metrics, satisfaction trends, and sentiment scoring. Stack: PySpark, Microsoft Fabric lakehouse.

## What this work delivered

- Budget optimization across 100+ sites using mathematical optimization.
- Churn and vacancy forecasting, marketing attribution, and resident satisfaction analytics.
- A weather-normalized energy analytics platform saving roughly $200K per year.

## ML lifecycle

Data preparation (Databricks, Fabric lakehouse) → modeling → experiment tracking (MLflow) → outputs to Delta Live Tables / Azure Data Lake → monitoring through trend and anomaly outputs.

## Toolbox

Python, SQL, PySpark, R, Gurobi, scikit-learn, Databricks, MLflow, Fabric, Azure ML, Power BI.

## Notes on this repo

- Company names, employee details, site IDs, and internal paths are anonymized.
- Notebook outputs are cleared because the originals ran on internal data; the code and documentation are the portfolio.
- All projects here were designed and built by me.
