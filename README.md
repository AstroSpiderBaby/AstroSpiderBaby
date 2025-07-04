Welcome to my GitHub! I specialize in building modern, modular data pipelines with **Databricks**, **Azure**, and **Delta Lake**—with a focus on clean design, automation, and secure architecture.

---

## 🔥 Featured Project: Modular Databricks Pipeline Framework

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Databricks](https://img.shields.io/badge/Platform-Databricks-orange)
![Azure](https://img.shields.io/badge/Cloud-Azure-blue)

> This project demonstrates an end-to-end batch ingestion pipeline using **Azure Databricks**, **Delta Lake**, and **Azure Key Vault**—with a clean Bronze → Silver → Gold architecture, secure mounting, and workflow orchestration.

📍 **Live Repo**: [databricks-pipelines](https://github.com/AstroSpiderBaby/databricks-pipelines)  
📘 **Full Technical Docs**: [Root README](https://github.com/AstroSpiderBaby/databricks-pipelines/blob/main/README.md)

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
- 📦 Blob storage mounting for ingestion of flat files and JSON
- 🧩 Clean enrichment and transformation layers using PySpark
- 🪵 Delta format tables and Databricks Workflows for orchestration
- 🧪 Full pipeline run documented via notebooks (and CLI support)

---

## 🚀 What’s Next

- 🌀 Auto Loader integration for real-time ingestion  
- 🔄 SQL Server (on-prem) to Databricks via **Ngrok + JDBC**  
- 🔎 Metadata-driven config via YAML  
- 📊 Dashboard-ready gold layer with compliance + vendor metrics

---

## 📁 Project Overview

```text
pipeline1_batch_delta/
├── bronze/         # Ingest mock data (finance, vendors, etc.)
├── silver/         # Clean & join (e.g., vendor compliance)
├── gold/           # Final aggregated outputs
├── utils/          # Mounts, secrets, helpers
├── transform/      # Modular transformation logic
└── docs/           # Setup instructions and scripts
🧠 About Me
I'm a data engineer passionate about building scalable data systems using open-source tools and cloud-native architectures. I thrive at the intersection of pipelines, analytics, and automation.

🌐 Let’s connect → linkedin.com/in/brucejenks
🐍 More coming soon: dbt, streaming, governance, and advanced SQL tuning!


🧪 Maintained by AstroSpiderBaby
🕒 Last updated: July 2025
"""
