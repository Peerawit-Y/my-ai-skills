# 🚀 My AI Skills Hub

Curated collection of production-grade AI Agent Skills (`SKILL.md`) for **Claude Code**, **Antigravity**, **Cursor**, **Windsurf**, and **Codex**, managed and distributed via **[Skill Nexus](https://github.com/Peerawit-Y/skill-nexus)**.

---

## ⚡️ Quick Installation (via Skill Nexus)

Anyone can install any skill from this repository directly to their AI tools with a single command:

```bash
# Format: sn install <username>/my-ai-skills/skills/<skill-name> --sync

# Examples:
sn install Peerawit-Y/my-ai-skills/skills/diagram-design --sync
sn install Peerawit-Y/my-ai-skills/skills/impeccable --sync
sn install Peerawit-Y/my-ai-skills/skills/accidental-data-loss-prevention --sync
sn install Peerawit-Y/my-ai-skills/skills/bigquery-sql --sync
```

To update all installed remote skills to the latest version in the future:
```bash
sn update
```

---

## 📚 Skill Catalog & True Origins

All skills in this repository include full attribution to their original creators and licenses:

### 🎨 Design & Frontend Engineering

| Skill | Description | Upstream Origin / Author | License |
| :--- | :--- | :--- | :--- |
| **`diagram-design`** | Comprehensive architectural, technical, flowchart, sequence, and visual diagram design (Mermaid, SVG, HTML). | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) by Cathryn Lavery | MIT |
| **`impeccable`** | High-craft frontend UI/UX design, visual hierarchy, typography, OKLCH color systems, and eliminating AI design slop. | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) by Paul Bakaus | MIT |

---

### 🛡️ Safety & Quality Guardrails

| Skill | Description | Upstream Origin / Publisher | License |
| :--- | :--- | :--- | :--- |
| **`accidental-data-loss-prevention`** | Critical safety guardrail: STOP AND VERIFY before executing irreversible destructive commands (DROP, TRUNCATE, `rm -rf`, bucket delete). | Google Cloud Platform (`publisher: google`) | Apache-2.0 |
| **`skill-repair`** | Diagnostic and surgical repair tool for failed agent skills and manifest files. | Google Cloud Platform (`publisher: google`) | Apache-2.0 |
| **`enforcing-resource-attribution`** | Enforces resource attribution, mandatory labeling, and parameter safety on cloud CLI operations. | Google Cloud Platform (`publisher: google`) | Apache-2.0 |

---

### ☁️ Google Cloud, BigQuery & Data Engineering

Official Google Cloud Data & AI Agent Skills suite (`publisher: google`, Apache-2.0):

| Skill | Category | Description |
| :--- | :--- | :--- |
| **`bigquery-sql`** | BigQuery | Query optimization, partition/cluster strategies, and execution best practices. |
| **`bigquery-ai-ml`** | BigQuery | Time-series forecasting, outlier detection, and GenAI functions in BigQuery SQL. |
| **`bigquery-bigframes`** | Data Science | BigQuery DataFrames (pandas / scikit-learn style API) in Python notebooks. |
| **`bigquery-data-transfer-service`** | Data Ingestion | Inspects and manages BigQuery Data Transfer Service (DTS) ingestion pipelines. |
| **`bigquery-graph`** | Graph Analytics | Graph Query Language (GQL) and property graph topologies in BigQuery. |
| **`building-data-apps`** | Full-Stack Data | Builds modern data applications and interactive dashboards (React + Vite / Streamlit). |
| **`data-autocleaning`** | Data Quality | Automated cleaning, schema mapping, and validation for BigQuery/GCS data. |
| **`dataform-bigquery`** | Data Modeling | SQLX transformation workflows, incremental tables, and Dataform pipelines. |
| **`dbt-bigquery`** | Data Modeling | dbt pipeline authoring, optimization, and testing on BigQuery. |
| **`discovering-gcp-data-assets`** | Discovery | Search, explore schemas, and inspect datasets across BigQuery, Spanner, BigLake. |
| **`federate-lakehouse-catalog`** | Lakehouse | Connects BigQuery to remote Iceberg REST catalogs (Databricks Unity, AWS Glue). |
| **`gcloud-auth-verification`** | Auth & IAM | Troubleshoots ADC, OAuth tokens, and Google Cloud authentication issues. |
| **`gcp-composer-troubleshooting`** | Orchestration | Root cause analysis (RCA) and debugging for failed Cloud Composer / Airflow DAGs. |
| **`gcp-data-pipelines`** | Orchestration | General architecture guide for data pipelines (Dataflow, dbt, Dataform, Composer). |
| **`gcp-dataflow`** | Stream / Batch | Apache Beam pipeline development, flex templates, autoscaling, and diagnostics. |
| **`gcp-managed-airflow-dag-authoring`** | Airflow | Best practices for Airflow 2/3 DAG authoring on Managed Service for Apache Airflow. |
| **`gcp-managed-airflow-migrations`** | Airflow | Scans and migrates DAGs to Airflow 2.11+ / Airflow 3 without breaking changes. |
| **`gcp-managed-airflow-recommendations`** | Airflow | Performance tuning, environment scaling, and worker optimization for Composer. |
| **`gcp-pipeline-orchestration`** | Orchestration | Declarative orchestration definitions for Composer and Airflow pipelines. |
| **`gcp-pipeline-resource-provisioning`** | Infrastructure | Declarative resource provisioning via `deployment.yaml` for data pipelines. |
| **`gcp-spark`** | Big Data | Serverless Dataproc and Spark batch/interactive jobs with Iceberg and BigLake. |
| **`gcs-security-assessment`** | Security | Security posture, SAIF compliance, bucket lock, and IAM scanning for GCS. |
| **`google-cloud-storage-basics`** | Storage | Managing objects, buckets, lifecycle rules, signed URLs, and storage classes. |
| **`managing-python-dependencies`** | Python | Virtualenv isolation, uv/poetry/pip management, and notebook dependencies. |
| **`ml-best-practices`** | Machine Learning | ML model comparison, classification, regression, and data analysis rules. |
| **`notebook-guidance`** | Data Analysis | Jupyter notebook authoring, `%%bqsql` magics, and BigQuery data exploration. |

---

## 🛠️ Repository Structure

```text
my-ai-skills/
├── README.md
└── skills/
    ├── accidental-data-loss-prevention/
    │   └── SKILL.md
    ├── diagram-design/
    │   ├── SKILL.md
    │   ├── assets/
    │   ├── references/
    │   └── scripts/
    ├── impeccable/
    │   └── SKILL.md
    ├── bigquery-sql/
    ├── ... (other 28 skills)
```

---

## 📄 License & Attribution

- **Google Cloud Platform Skills:** Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0) by Google LLC.
- **Diagram Design:** Licensed under the MIT License by [Cathryn Lavery](https://github.com/cathrynlavery/diagram-design).
- **Impeccable:** Licensed under the MIT License by [Paul Bakaus](https://github.com/pbakaus/impeccable).
