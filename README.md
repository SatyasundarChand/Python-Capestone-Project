# Python Capstone Project 📊

## 🖼️ Project Output Preview
![Pipeline Data Preview](Python%20Project.png)

---

## 📌 Project Overview
This repository hosts an end-to-end automated data pipeline built within **Jupyter Notebook** to process, clean, and consolidate raw corporate transactional records into a structured, analytics-ready master schema. 

## 🎯 Business Metrics & Objectives
* Automated processing across multi-source historical corporate project records.
* Eradicated manual data cleaning bottlenecks by implementing automated value imputation.
* Synthesized operational cost metrics to track resource allocation and calculate corporate payouts.

## 🛠️ Tech Stack & Skills Validated
* **Language:** Python 3.x
* **Core Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook
* **Methodologies:** Data Imputation, ETL Architecture, Relational Joining, Vectorization

## 💡 Engineering Implementation (What I Did)
* **Data Imputation & Look-Ahead Logic:** Engineered a custom look-ahead scanning module to identify missing records and dynamically patch missing financial `Cost` fields using rolling averages (seamlessly resolving `NaN` entries).
* **Multi-Source Relational Consolidation:** Used `pd.merge()` relational operations to structurally integrate three isolated datasets—**Project Dataframes**, **Employee Demographics**, and **Seniority Mappings**—into a centralized data warehouse schema.
* **Vectorized Financial Logic:** Deployed high-performance vectorized operations (`np.where`) and string pattern matching (`str.contains`) to execute conditional 5% bonus calculations on `Finished` project milestones and auto-format staff titles.
