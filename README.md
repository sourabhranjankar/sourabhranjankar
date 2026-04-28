# Hi there, I'm Sourabh Kar 👋  
### Data Engineer | Real-time Pipelines | Snowflake • Databricks • AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sourabhkde/)
[![Email](https://img.shields.io/badge/Email-sourabh.kar%40workwebmail.com-red?style=flat&logo=gmail&logoColor=white)](mailto:sourabh.kar@workwebmail.com)
![Location](https://img.shields.io/badge/Dallas%2C%20TX-555?style=flat)

---

## 👨‍💻 About Me
Data Engineer with **5+ years** of experience building **production-grade, real-time data pipelines** on **Snowflake, Databricks, and AWS**.  
I’ve reduced **pipeline failure rates from 18% to <4%**, cut **data latency from hours to minutes**, and delivered **medallion lakehouses processing 1TB+/day**.

I’m especially focused on:
- **Kafka + Snowflake** near-real-time ingestion (CDC, Snowpipe, Streams/Tasks, Dynamic Tables)
- **Airflow** orchestration standards (SLA monitoring, retries, alerting, DLQ patterns)
- **dbt** analytics engineering (incremental models, snapshots, tests, freshness, data contracts)
- **ML data engineering** (feature store design, point-in-time correctness, training vs serving pipelines)

---

## 🧰 Tech Stack
**Cloud Data Platform:** Snowflake (Snowpipe, Streams, Tasks, Dynamic Tables, RBAC, Dynamic Data Masking) • Databricks (Delta Lake, Unity Catalog, Workflows)  
**Pipelines & Orchestration:** Airflow (DAG standards, SLAs, sensors, retries, callbacks, XCom) • Kafka • Spark (PySpark, Spark SQL)  
**Transformation & Modeling:** dbt (incremental, snapshots, tests, freshness) • Snowpark • Dimensional modeling • SCD Type 1/2 • CDC  
**Languages:** Python (Pandas, Boto3, pytest, SQLAlchemy) • SQL (CTEs, window functions, MERGE, UDFs, stored procedures)  
**Cloud & DevOps:** AWS (S3, IAM, Lambda, Glue, CloudWatch) • Terraform • GitHub Actions • dbt Cloud CI  
**BI:** Power BI (DAX, Power Query) • Tableau  

---

## 🏢 Professional Experience

### Target — Data Engineer  
*Oct 2024 – Present | Remote (USA)*  
- Reduced pipeline failure rate from **18% to <4%** across **30+ production workloads** by establishing an org-wide **Airflow DAG standard** (retry policies, SLA callbacks, dead-letter routing).  
- Cut data availability from **4+ hours to under 4 minutes** across **15+ critical feeds** by implementing **Kafka → Snowpipe** ingestion with **Streams-based CDC**, enabling near-real-time feature freshness for ML serving pipelines.  
- Migrated **12+ Streams/Tasks workflows** to **Snowflake Dynamic Tables**, reducing maintenance by **60%** and shrinking transformation lag from **45 minutes to <5 minutes** (zero orchestration code).  
- Prevented schema-breaking changes from reaching **50+ dbt models** by implementing **data contracts**, null-rate assertions, and **CI/CD quality gates** in **GitHub Actions**.  
- Built the feature layer for a **1TB+/day medallion lakehouse** on Databricks + Snowflake, delivering **audit-ready, point-in-time-correct** training datasets to ML and analytics consumers.  

### BNY Mellon — Data Engineer  
*Jun 2021 – Jul 2023 | Hyderabad, India*  
- Built a regulatory data platform from greenfield using **AWS Glue + S3** to process **500GB+/day** across **20+ trade sources**, with full **SEC audit trail**, closing **3 SOX exceptions**.  
- Achieved **99.6% uptime** across **20+ compliance Airflow DAGs** by integrating **CloudWatch alerting** and automated retries (failure detection reduced from 2+ hours to ~8 minutes).  
- Implemented a self-serve **dbt SCD Type 2 snapshot** layer across **15+ position tables**, enabling on-demand SOX/SEC audit requests.  
- Standardized ingestion from **REST APIs, flat files, and RDBMS** into a single Snowflake schema with consistent typing, null handling, and audit columns—reducing integration errors by **70%**.  
- Prevented silent data errors by building a **Kafka-integrated source-to-target reconciliation layer** catching count mismatches and late-arriving records before compliance consumption.  

### Abbott India — Business Intelligence Analyst  
*Jan 2020 – Jun 2021 | Hyderabad, India*  
- Built Power BI dashboards tracking **50+ supply chain KPIs**, driving a **15% reduction** in procurement inefficiencies.  
- Owned the ML data pipeline for **ARIMA demand forecasting** in Python (point-in-time training dataset assembly + scheduled retraining), reducing overstock costs by **6%**.  
- Automated ingestion from **SAP ERP to SQL Server** using Python (Pandas, SQLAlchemy), cutting manual data prep effort by **40%**.  

---

## 🎓 Education
**M.S. in Advanced Data Analytics** — University of North Texas (Denton, TX)  
*Aug 2023 – May 2025*

---

## 🧾 Certifications
- **SnowPro Core** — Snowflake  
- **AWS Certified Data Engineer – Associate (DEA-C01)** — AWS  

---
### 🧩 Featured Projects
- **[Portfolio](https://github.com/sourabhranjankar/portfolio)** — My personal developer portfolio built with React and TypeScript. *(Development stage: Maintained)*  
- **[Application Tracker](https://github.com/sourabhranjankar/applicationTracker)** — A job tracking app for managing applications and offers. *(Development stage: Maintained)*  
- **[Chronic Disease Prediction & Wellness Analytics](https://github.com/sourabhranjankar/Chronic_Disease_Prediction_and_Wellness_Analytics)** — ML-driven health insights using CDC datasets. *(Development stage: Maintained)*  
- **[ADTA5410 Team 10](https://github.com/sourabhranjankar/ADTA5410Team10)** — Predictive analytics project using regression and clustering models. *(Development stage: Maintained)*  

**Planned / In Development (next builds):**
- **[Realtime Kafka → Snowflake CDC Pipeline](https://github.com/sourabhranjankar/realtime-kafka-snowflake-cdc)** — Reference architecture for near-real-time ingestion using Kafka, Snowpipe, Streams/Tasks, and exactly-once-ish processing patterns. *(Development stage: Planned)*  
- **[Airflow DAG Standards & Observability Kit](https://github.com/sourabhranjankar/airflow-dag-standards-kit)** — Opinionated DAG templates with SLAs, retry policies, alerting callbacks, and dead-letter routing examples. *(Development stage: Planned)*  
- **[dbt Data Contracts & Quality Gates](https://github.com/sourabhranjankar/dbt-data-contracts-quality-gates)** — dbt tests + CI pipeline to block schema-breaking changes (freshness, null-rate assertions, contract checks). *(Development stage: Planned)*  
- **[Medallion Lakehouse Starter (Databricks + Delta)](https://github.com/sourabhranjankar/medallion-lakehouse-starter)** — Bronze/Silver/Gold framework with incremental processing, CDC patterns, and audit-ready lineage. *(Development stage: Planned)*  
- **[Feature Store + Point-in-Time Correctness Demo](https://github.com/sourabhranjankar/feature-store-pit-demo)** — Training vs serving pipeline demo with PIT joins, feature freshness SLAs, and reproducible offline datasets. *(Development stage: Planned)*
---

## 📊 GitHub Stats
![Sourabh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=sourabhranjankar&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sourabhranjankar&layout=compact&theme=tokyonight)

---

⭐ If you’re building reliable streaming + lakehouse data platforms, let’s connect.
