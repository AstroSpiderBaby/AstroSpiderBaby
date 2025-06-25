# Modular Databricks Pipeline Framework

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Databricks](https://img.shields.io/badge/Platform-Databricks-orange)
![Azure](https://img.shields.io/badge/Cloud-Azure-blue)

This repository showcases an end-to-end modular data pipeline built on Databricks, leveraging Azure Blob Storage and Delta Lake. It is designed to scale with secure credential handling, organized structure, and orchestration for production-grade workflows.

---

## 👋 Hi there

### 🚀 Project Roadmap

This repository is the foundation for a complete modular pipeline built in Databricks.

---

## 📑 Table of Contents
- [Current Capabilities](#-current-capabilities)
- [Coming Enhancements](#-coming-enhancements)

---

### ✅ Current Capabilities

- 📥 Batch ingestion of flat files & JSON using `dbutils.fs` and secure mounts  
- 🔐 Mounting via **Secret Scopes** and **Azure Key Vault**
- 🪵 Layered Delta Architecture (Bronze → Silver → Gold)
- 🧩 Workflow orchestration for reliable execution
- 📁 Organized folder structure with `/utils`, `/docs`, and `/transform` code
- 📓 Notebooks with setup instructions and CLI walkthroughs

---

### 🔮 Coming Enhancements

- ⚙️ Integration with **Auto Loader** for streaming-like file handling
- 🌐 **Multi-cloud support** (AWS S3, Google Cloud) + simulated **on-prem** SQL Server ingestion
- 🧪 Adding **unit tests**, **data validation**, and pipeline **monitoring hooks**
- 🧬 Metadata-driven config system (YAML-based) for pipeline automation
