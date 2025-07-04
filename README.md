Welcome to my GitHub! I specialize in building modern, modular data pipelines with **Databricks**, **Azure**, and **Delta Lake**—with a focus on clean design, automation, and secure architecture.

---

🔥 Featured Project: Modular Databricks Pipeline Framework

This project demonstrates an end-to-end batch ingestion pipeline using **Azure Databricks**, **Delta Lake**, and **Azure Key Vault**—with a clean Bronze → Silver → Gold architecture, secure mounting, and workflow orchestration.

🧪 **Includes full mock datasets** for easy testing and demonstration  
📦 [`mock_data/`](https://github.com/AstroSpiderBaby/databricks-pipelines/tree/main/mock_data) — CSV & JSON files used for Bronze layer ingestion  
🛠️ [`generate_mock_data.py`](https://github.com/AstroSpiderBaby/databricks-pipelines/blob/main/generate_mock_data.py) — Optional script to re-export files from Delta or Blob

🔗 **Live Repo:** [databricks-pipelines](https://github.com/AstroSpiderBaby/databricks-pipelines)  
📘 **Full Docs:** [Root README](https://github.com/AstroSpiderBaby/databricks-pipelines#-databricks-pipelines)

---

## 📑 Table of Contents

- [🔧 Current Capabilities](#-current-capabilities)
- [🚀 What’s Next](#-whats-next)
- [📁 Project Overview](#-project-overview)
- [🧠 About Me](#-about-me)

---

## 🔧 Current Capabilities

- 🏗️ Modular pipeline structure using `bronze/`, `silver/`, and `gold/` stages
- 🔐 Secure integration with **Azure Key Vault** and **Databricks Secret Scopes**
- 🔄 SQL Server (on-prem) to Databricks via **Ngrok + JDBC**  
- 📦 Blob storage mounting for ingestion of flat files and JSON
- 📋 Databricks Workflows orchestrating multi-step pipelines with task dependencies
- 🧩 PySpark transformations for clean enrichment, joins, and validations
- 🪵 Delta format tables and Databricks Workflows for orchestration
- 🧪 Full pipeline run documented via notebooks (and CLI support)

---

## 🚀 What’s Next

- 🌀 Auto Loader integration for real-time ingestion  
- 🔁 Incremental ingestion patterns using file metadata or watermark fields  
- 🔎 Metadata-driven configs via YAML for flexible pipeline control  
- 🧪 Layer-specific data quality checks:
  - **Bronze**: Schema enforcement, null validation, corrupt record handling  
  - **Silver**: Deduplication, referential integrity, outlier detection  
  - **Gold**: Metric validation, completeness checks, threshold alerts  
- 📦 S3 integration for cross-cloud ingestion from AWS sources  
- 🛠️ Alternate pipeline with **DBT** for declarative transformations and model versioning  
- 📊 Dashboard-ready Gold Layer with KPIs for compliance & vendor health


---

## 📁 Project Overview

```text
pipeline1_batch_delta/
├── bronze/       # Ingest mock data (finance, vendors, etc.)
├── silver/       # Clean & join (e.g., vendor compliance)
├── gold/         # Final aggregated outputs
├── utils/        # Mounts, secrets, helpers
├── transform/    # Modular transformation logic
├── docs/         # Setup instructions and scripts
```

---
💬 About Me  
I'm a data engineer passionate about building scalable data systems using open-source tools and cloud-native architectures.

📜 Certified: [Databricks Certified Data Engineer Associate](https://credentials.databricks.com/5c463e68-5e4a-41e0-a127-3f9c8501c68e#acc.xCdZN3jg)  

🌐 Let’s connect → [linkedin.com/in/brucejenks](https://linkedin.com/in/brucejenks)  

🔄 More coming soon: dbt, streaming, governance, and advanced SQL tuning!


🧪 Maintained by AstroSpiderBaby
🕒 Last updated: July 2025
"""
