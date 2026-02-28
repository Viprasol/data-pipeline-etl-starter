# 🔄 Data Pipeline ETL Starter

Production-ready **ETL pipeline starter** using Python, Apache Airflow, dbt, and PostgreSQL — for data warehouses and analytics backends.

> Built by [Viprasol Tech](https://viprasol.com) — custom data warehouse and analytics development.

---

## Architecture

```
Sources → Airflow DAGs → dbt transforms → PostgreSQL → BI / API
```

---

## What's Included

- **Airflow DAGs** — scheduled ingestion from APIs, DBs, and files
- **dbt models** — staging → intermediate → mart layers
- **Data quality tests** — nulls, uniqueness, referential integrity
- **Incremental loads** — only process new/changed records
- **Docker Compose** — full stack locally in one command

---

## Data Layers

| Layer | Purpose |
|-------|---------|
| `raw` | Immutable source copy |
| `staging` | Cleaned and typed |
| `intermediate` | Business logic |
| `mart` | Aggregated and query-optimised |

---

## Quick Start

```bash
git clone https://github.com/Viprasol/data-pipeline-etl-starter
docker-compose up -d
# Airflow UI: localhost:8080
```

---

## Use Cases

- Centralise 10+ SaaS tools into one warehouse
- Build analytics layer for a trading platform
- Replace spreadsheet reports with automated pipelines
- Feed ML models with clean, structured data

---

## Need a Custom Data Pipeline?

Built by [Viprasol Tech](https://viprasol.com).

👉 **[Build Your Data Pipeline →](https://viprasol.com/services/big-data-analytics)**

---

MIT License
