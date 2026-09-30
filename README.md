# Mouhamadou Lamine NDIAYE

### Data & AI Engineer · Data Engineering · Data Science/Machine Learning · LLM Agents

I build data systems end to end — from multi-source pipelines to forecasting models and LLM agents — and I measure whether they actually work.

Currently pursuing an **M2 DataScale (large-scale data management and knowledge extraction)** at **Université Paris-Saclay**.

📍 Île-de-France area · 

🔎 **Looking for a 6-month end-of-studies internship in Data / ML / AI Engineering starting March 2027**

---

## 🚀 Featured Projects

Three end-to-end projects built on real French public data, each designed around a concrete problem and evaluated against a meaningful baseline.

### ⚡ French Electricity Demand Forecasting · *ML + MLOps*

**[france-electricity-forecasting](https://github.com/mlndiaye/france-electricity-forecasting)**

Day-ahead probabilistic forecasting of French electricity consumption, benchmarked daily against RTE's official forecast. Full pipeline built and backtested over a full year: gradient-boosted point forecast beats a seasonal-naive baseline by 65% MAE and matches RTE's own forecast (1,286 vs. 1,298 MW MAE); error analysis by day type and a first multi-quantile prediction interval, evaluated and found under-calibrated — a documented, unresolved limitation motivating a follow-up conformal-prediction pass. Now runs automatically once a day via Airflow, with every prediction tracked in MLflow and served through a read-only API and a Streamlit dashboard. Next: deploying it publicly.

`Python` `pandas` `LightGBM` `scikit-learn` `MLflow` `FastAPI` `Airflow` `Streamlit` `Docker`

---

### 🏢 Unified French Business Registry · *Data Engineering + Big Data* · 🚧 In progress

**[french-business-registry](https://github.com/mlndiaye/french-business-registry)**

A multi-source ELT platform that ingests, cleans and links French public business data (SIRENE, BODACC, public procurement, certifications) into a single, historized company registry. Includes incremental loading, layered data modeling, data quality testing and large-scale entity resolution.

`Python` `PySpark` `dbt` `Airflow` `DuckDB` `MinIO` `Parquet` `Docker`

---

### 🤖 Energy Analyst Agent · *AI Engineering* · 🚧 In progress

**[energy-analyst-agent](https://github.com/mlndiaye/energy-analyst-agent)**

An LLM agent that answers analytical questions about the French power system by querying a data warehouse, calling a forecasting model and combining the results into verifiable answers. Evaluated on a custom benchmark for accuracy, tool use, cost and latency, comparing API-based and local models.

`Python` `LangGraph` `MCP` `FastAPI` `Ollama` `Langfuse`

---

## 🔬 Technical Labs

Experimental repositories exploring specific technologies and approaches.

* **[Data Engineering Lab](https://github.com/mlndiaye/data-engineering-lab)** — Data pipelines, ELT, orchestration and analytics workflows.

---

## 🧰 Technical Stack

**Languages** — `Python` · `SQL` · `Java` · `JavaScript`

**Data Engineering** — `Airflow` · `dbt` · `Airbyte` · `PySpark` · `PostgreSQL` · `BigQuery` · `DuckDB`

**Machine Learning** — `Scikit-learn` · `LightGBM` · `TensorFlow`

**AI Engineering** — `LangChain` · `LangGraph` · `RAG` · `Embeddings` · `Vector Search` · `Ollama` · `Langfuse`

**MLOps & Software** — `MLflow` · `FastAPI` · `Docker` · `GitHub Actions` · `OpenShift` · `Spring Boot` · `Microservices`

---

## 🏆 Awards

* 🥇 **1st Prize — SENELEC Hackathon**
* 🥇 **1st Prize — Africa T-Awards**
* 🥇 **1st Prize — SALTIS Innovation Contest**
* 🥇 **1st Prize, Innovation Award — JOJ Dakar 2026**

---

## 🎓 Education

**M2 DataScale — Large-Scale Data Management and Knowledge Extraction**
Université Paris-Saclay · 2026–2027

**Engineering Degree in Computer Science and Telecommunications — Highest Honors (Mention Très Bien)**
École Polytechnique de Thiès, Senegal

---

## 🌍 Languages

French (fluent) · English (B2, IELTS 6.0) · Wolof (native)

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/mouhamadou-lamine-ndiaye/) · [Email](mailto:mouhamadou-lamine.ndiaye16@ens.uvsq.fr)
