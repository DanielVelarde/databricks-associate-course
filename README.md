# Databricks Data Engineering Associate: Study & Implementation

![Databricks](https://img.shields.io/badge/Platform-Databricks-blue?style=flat-square&logo=databricks)
![Spark](https://img.shields.io/badge/Framework-PySpark-orange?style=flat-square&logo=apachespark)
![Certification](https://img.shields.io/badge/Target-Associate_Data_Engineer-green?style=flat-square)

## 📖 Project Overview
This repository serves as a technical log for my journey through the **Databricks Certified Data Engineer Associate** curriculum, guided by **Derar Alhussein**. The goal is to master the Lakehouse Platform by building production-ready data pipelines.

## 🏗️ Technical Architecture: The Medallion Pattern
I am implementing a multi-hop architecture to process data from raw ingestion to business-ready insights:

* **Bronze (Raw):** Ingesting raw data (JSON/CSV) into Delta tables with minimal transformation to preserve data lineage.
* **Silver (Filtered/Cleaned):** Applying schema enforcement, deduplication, and data validation rules.
* **Gold (Business):** Aggregating and joining tables to provide high-level insights for BI and Analytics.

## 🛠️ Key Concepts Mastered
- **Delta Lake:** ACID transactions, Time Travel, and Vacuuming.
- **Unity Catalog:** Data governance, securing objects, and managing lineage.
- **Workflow Orchestration:** Scheduling jobs and monitoring DLT (Delta Live Tables).
- **Security:** Implementing Column-level and Row-level security.

## 📂 Repository Structure
* `notebooks/`: Structured by module (Setup, Ingestion, Transformation, Loading).
* `configs/`: Cluster settings and environment variables.
* `tests/`: Unit tests and data quality checks (Expectations).

---
*Last Updated: February 2026*