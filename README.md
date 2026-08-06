<h1 align="center">Hi, I'm Keith 👋</h1>

<p align="center">
  <strong>Data Engineering · Business Intelligence · Analytics</strong><br/>
  <em>MS Data Science @ Northeastern (Khoury) · Boston, MA</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/keithfernandes12/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:fernandes.kei@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I build **end-to-end data pipelines and the dashboards on top of them** — ingestion, modelling, and the BI layer that makes the data answer a business question. Most of my recent work is medallion-architecture lakehouses on **Databricks/PySpark** and **AWS (S3, Glue, Athena, Iceberg)**, modelled as Kimball star schemas and served to **Power BI**.

Before grad school I spent two years as an AV & Automation Consultant, with a BTech in Mechatronics Engineering (NMIMS Mumbai) — a background that got me used to making messy real-world systems work reliably.

🎯 **Currently seeking a Spring 2027 co-op** in data engineering, business intelligence, data analytics, or data science.

---

## 📌 Featured Projects

| Project | What It Does | Stack |
|---|---|---|
| 💊 **[Global Pharma Intelligence](https://github.com/keithfernandes12/pharma-data-engineering-aws)** | End-to-end AWS pipeline over 17 years of pharma data. A **SQL crosswalk layer** resolves entities across five files that don't join cleanly (`BMS` vs `Bristol-Myers Squibb`, co-development deals, disease→therapy-area bridging), then builds a Kimball star schema serving a **6-page Power BI report**. Verified row counts, grain checks, and idempotent incremental loads. | `S3` `Glue` `Athena` `Iceberg` `PySpark` `Terraform` `Power BI` |
| 🏪 **[FMCG Medallion Lakehouse](https://github.com/keithfernandes12/fmcg-medallion-lakehouse)** | Post-acquisition data integration: merges an acquired brand's dirty daily-grain data into the parent's clean monthly star schema. Typo mapping, multi-format date parsing, `sha2` surrogate keys, **daily→monthly grain reconciliation**, and idempotent `MERGE` upserts — orchestrated as a Lakeflow Jobs DAG. | `Databricks` `PySpark` `Delta Lake` `Unity Catalog` `S3` |
| 🚕 **[Transportation Lakehouse (SDP)](https://github.com/keithfernandes12/transportation-databricks-sdp)** | Bronze→silver→gold pipeline for cab ride-trip data across ten cities, built on **Databricks Lakeflow Spark Declarative Pipelines**. Auto Loader streaming ingest, declarative data-quality expectations, SCD Type 1 CDC upserts, and a star-schema fact view fanning out to per-city views. | `Databricks SDP` `PySpark` `Auto Loader` `Delta` `SQL` |
| 🏎️ **[Predicting F1 Pit Stops](https://github.com/keithfernandes12/Predicting-F1-Pit-Stops)** | Kaggle Playground S6E5 binary classification. **0.94019 OOF AUC** from a weight-optimized 4-model blend, validated with GroupKFold by race×year to prevent leakage; external-data integration was the single biggest lift (+0.010). | `LightGBM` `XGBoost` `CatBoost` `Optuna` |
| 🛒 **[Market Basket Analysis](https://github.com/keithfernandes12/Market-Basket-Analysis)** | Apriori association-rule mining on 38,765 grocery transactions — 1,376 rules surfaced with lift up to 2.18×, framed as cross-sell and product-placement recommendations. | `Python` `mlxtend` `Pandas` |
| 🩺 **[Diabetes Prediction (NHANES)](https://github.com/keithfernandes12/Healthcare-Analytics-Diabetes-Prediction-)** | Merges five CDC NHANES components into one 9,813-participant dataset, then compares six models on HbA1c-derived diabetes classes — 88.1% accuracy with ensembles. | `scikit-learn` `Pandas` |
| 🚚 **[Supply Chain Shipment Pricing](https://github.com/keithfernandes12/Supply-Chain-Shipment-Pricing)** | EDA on 10,324 ARV/HIV health-commodity shipments. Engineered a `Delivery_Delay` feature to rank countries by chronic late delivery, alongside pricing and manufacturing-site analysis. | `Python` `Pandas` `Matplotlib` |
| 👁️ **[Diabetic Retinopathy Detection](https://github.com/keithfernandes12/diabetic_retinopathy_prediction)** | *Team project.* GLCM texture features from APTOS 2019 retinal images, with a genetic algorithm driving both feature selection and LightGBM hyperparameter tuning against an all-features baseline. | `LightGBM` `OpenCV` `DEAP` |

---

## 🛠️ Tech Stack

**Data Engineering & Cloud**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logo=delta&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Languages & Databases**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

**BI & Visualization**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

**Machine Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge)

---

## 🎓 Education

- **MS, Data Science** — Northeastern University, Khoury College of Computer Sciences · Sept 2025 – Dec 2027
- **BTech, Mechatronics Engineering** — NMIMS Mumbai

---

<p align="center">
  <em>Open to Spring 2027 co-op conversations — the fastest way to reach me is <a href="mailto:fernandes.kei@northeastern.edu">email</a> or <a href="https://www.linkedin.com/in/keithfernandes12/">LinkedIn</a>.</em>
</p>
