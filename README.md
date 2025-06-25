# Modular Databricks Pipeline Framework

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Databricks](https://img.shields.io/badge/Platform-Databricks-orange)
![Azure](https://img.shields.io/badge/Cloud-Azure-blue)

This repository showcases an end-to-end modular data pipeline built on Databricks. It supports secure credential management, organized processing stages, and reusable code modules.

---

## 📑 Table of Contents

- [Current Capabilities](#-current-capabilities)
- [Coming Enhancements](#-coming-enhancements)
- [Repository Structure](#-repository-structure)
- [Setup Instructions](#-setup-instructions)
- [How to Run](#-how-to-run)
- [Contributing](#-contributing)

---

## ✅ Current Capabilities

- 📥 Batch ingestion of flat files & JSON using `dbutils.fs` and secure mounts  
- 🔐 Secure mounting via **Secret Scopes** and **Azure Key Vault**
- 🪵 Delta Architecture: Bronze → Silver → Gold
- 🧩 Databricks Workflows for orchestration
- 📁 Modular folder structure (`/utils`, `/docs`, `/transform`)
- 📓 Notebooks documenting setup and CLI usage

---

## 🔮 Coming Enhancements

- ⚙️ Integration with **Auto Loader** for streaming file support
- 🌐 Simulated **on-prem SQL Server** ingestion + **multi-cloud connectors** (AWS, GCP)
- 🧪 Unit testing, data validation, and monitoring hooks
- 🧬 YAML-based metadata config system to automate pipeline execution

---

## 📁 Repository Structure

```text
pipeline1_batch_delta/
│
├── bronze/                 # Raw ingestion logic
├── silver/                 # Cleaned and structured transformations
├── gold/                   # Aggregated or curated outputs
├── transform/              # Additional reusable transformation logic
├── utils/                  # Helper scripts (mounts, writes, secrets)
│   ├── mount_lv426_blobstorage.py
│   ├── write_to_delta.py
│   └── README.md
├── docs/                   # Setup notes and instructional notebooks
│   ├── azure_key_vault_setup
│   ├── databricks_env_setup
│   ├── secret_scope_setup
│   ├── token_generation
│   └── mounting_blobstorage_notes
└── notebooks/              # Interactive development and test runs
