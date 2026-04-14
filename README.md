# Hey, I'm Steve Lopez 👋

**Analytics Engineer** based in Redlands, CA

I build data products end-to-end — from production reporting pipelines to generative BI platforms powered by LLMs. Former Principal Technical Product Manager who delivered enterprise platforms at Zelle, First American, ADP, and Kaseya before pivoting fully into data. Strong SQL across dialects — MySQL, PostgreSQL, SQL Server, and Databricks SQL — with enough depth to build a curriculum around it.

---

## 🚀 Live Portfolio

### [CC GenBI — Contact Center Intelligence Platform](https://cc-genbi-poc.vercel.app)
> Generative BI platform for global contact center analytics. Ask questions in plain English, get AI-interpreted results, and drill into 20+ KPIs across 16 sites and 4 regions.

**[→ Try the Live Demo](https://cc-genbi-poc.vercel.app)** &nbsp;|&nbsp; **[→ View the Code](https://github.com/BigZeeke/cc-genbi-poc)**

- **Natural language to SQL** — powered by Claude with a semantic layer and 10 few-shot examples for ~95% accuracy
- **AI narrative layer** — benchmark-aware executive interpretation on every query result
- **20+ contact center KPIs** — AHT, FCR, CSAT, NPS, CES, SLA, occupancy, sentiment, cost per contact, and more
- **Star schema data mart** — 116K interactions across 16 global sites, 4 regions, 729 days
- **Self-contained SQLite** — entire database runs in the browser via WebAssembly, zero infrastructure
- Built on Next.js 14 + Vercel with a production SaaS dark-theme UI

---

### [Marketing Attribution Intelligence Platform](https://marketing-attribution.streamlit.app)
> Full-lifecycle B2C subscription analytics — acquire, convert, retain, reactivate — across 14 tables and 105,895 rows of realistic marketing data.

**[→ Try the Live Demo](https://marketing-attribution.streamlit.app)** &nbsp;|&nbsp; **[→ View the Code](https://github.com/BigZeeke/marketing-attribution)**

- Simulates **GA4, Meta Ads, Google Ads, HubSpot, Klaviyo, Segment, and Mixpanel** in a single unified schema
- **AI-powered channel recommendations** — Claude analyzes attribution patterns and surfaces optimization opportunities
- **Intentional data quality issues** built into the dataset — designed to demonstrate audit and profiling skills
- Multi-touch attribution modeling across the full customer lifecycle
- Deployed to Streamlit Community Cloud with a 14-table SQLite schema

---

### [Marketing Analytics Assistant](https://marketing-analytics-assistant.streamlit.app)
> Ask questions about marketing data in plain English. Get SQL, results, and charts instantly.

**[→ Try the Live Demo](https://marketing-analytics-assistant.streamlit.app)** &nbsp;|&nbsp; **[→ View the Code](https://github.com/BigZeeke/marketing_analytics_assistant)**

- Natural language → SQL powered by **Claude (Anthropic)**
- Queries a **23-table marketing analytics schema** on Databricks
- Multi-turn conversation memory with full context
- Three analyst persona question banks: CMO · Digital Marketing Manager · Analytics Engineer
- Deployed to Streamlit Community Cloud with SQLite demo mode

---

## 📚 SQL Training Curriculum

### [Marketing Analytics SQL — Training Course](https://github.com/BigZeeke/marketing_analytics_MySQL)
> 12 modules · 11 hours · every query tied to a real CMO business question

Built a complete self-paced SQL training course on top of a production-grade 25-table marketing analytics database. Each module covers one digital marketing discipline, teaches the SQL techniques needed to analyze it, and connects every query to the kind of question a senior marketing leader asks in a real meeting.

**[→ View the Curriculum](https://github.com/BigZeeke/marketing_analytics_MySQL)**

Every module includes:
- 🔧 **Engineering Lens** — EXPLAIN-driven thinking and data profiling before writing a query
- 📊 **Marketing Nuggets** — business context explaining *why* each metric matters to a CMO
- 🎯 **CMO Questions** — the actual executive question your SQL answers
- 💡 **Tips & Tricks** — patterns, shortcuts, and gotchas
- ✅ **Test Yourself** — graded exercises with full worked answers

| Module | Topic | Key SQL Skills |
|---|---|---|
| 00B | Engineering Workflow | EXPLAIN, data profiling, index strategy |
| 01 | SEO Analytics | LAG(), LEAD(), RANK(), NTILE(), multi-step CTEs |
| 02 | PPC & Paid Ads | Running totals, composite indexes, EXPLAIN |
| 03 | Email Marketing | Views, conditional aggregation, moving averages |
| 04–10 | GTM · Content · Audiences · Attribution · A/B Testing · CRO | Stored procs · UDFs · Triggers · Funnel CTEs |

---

## 🛠️ Tech Stack

**Languages**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logo=powerbi&logoColor=black)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL_8.0-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)

**Data Platforms**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Data_Lake-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)

**BI & Visualization**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22b5bf?style=flat&logoColor=white)

**Frameworks & Deployment**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**AI & LLMs**

![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=flat&logo=anthropic&logoColor=white)

---

## 📂 Projects

| Project | Description | Stack |
|---|---|---|
| [CC GenBI](https://github.com/BigZeeke/cc-genbi-poc) | Generative BI · 20+ contact center KPIs · NL-to-SQL · AI narrative · [Live demo](https://cc-genbi-poc.vercel.app) | Next.js · Claude · SQLite · Vercel |
| [Marketing Attribution Intelligence Platform](https://github.com/BigZeeke/marketing-attribution) | Full-lifecycle B2C attribution · AI recommendations · intentional DQ issues · [Live demo](https://marketing-attribution.streamlit.app) | Streamlit · Claude · SQLite |
| [Marketing Analytics Assistant](https://github.com/BigZeeke/marketing_analytics_assistant) | NL-to-SQL chat app · [Live demo](https://marketing-analytics-assistant.streamlit.app) | Streamlit · Claude · Databricks |
| [Marketing Analytics SQL Training](https://github.com/BigZeeke/marketing_analytics_MySQL) | 12-module SQL curriculum · 25-table production schema · CMO question bank | MySQL 8.0 |
| SQL Query Optimization Lab *(coming soon)* | Execution plan analysis, index strategy, normalization case studies | MySQL · PostgreSQL · Databricks SQL |
| Medallion Architecture Build *(coming soon)* | Bronze/Silver/Gold data layers on Databricks | Databricks · dbt · Unity Catalog |
| Marketing Data Marts *(coming soon)* | Reporting views, stored procs, materialized views | Databricks SQL · dbt |

---

## 🔧 SQL Depth

Advanced SQL across multiple dialects and platforms:

- **MySQL 8.0** — window functions, stored procedures, triggers, scalar UDFs, EXPLAIN execution plans, covering indexes, normalization
- **PostgreSQL** — EXPLAIN ANALYZE, CTEs, lateral joins, generate_series date spines
- **Databricks SQL** — Delta Lake, Unity Catalog, QUALIFY clause, Spark UI profiling
- **SQL Server** — T-SQL, execution plans, query tuning
- **dbt Core** — SQL models, tests, lineage, incremental strategies

---

## 🎓 Certifications & Training

| Program | Hours | Timeline |
|---|---|---|
| SQL Server DBA & MSBI → Microsoft Fabric Migration Bootcamp | ~200–240 hrs | 2025–2026 |
| Data-Focused SDET Bootcamp — Rahul Shetty Academy | ~150–180 hrs | 2025–2026 |

**SQL Server DBA & MSBI → Fabric Migration Bootcamp**
Full legacy-to-modern SQL Server consulting track in two acts: T-SQL · SQL Server Admin · Performance Tuning · High Availability · SSRS · SSIS · SSAS → Azure SQL · Azure Data Factory · Power BI / PL-300 · Microsoft Fabric. Outcome: certified ability to assess a legacy SQL Server estate, validate migration parity, and own the full modernization engagement end to end.

**Data-Focused SDET Bootcamp**
Automated data pipeline testing: pytest · Behave BDD · TDD · Python (SQLAlchemy · pandas) · Postman · Newman · Git · Docker · Jenkins CI/CD. Outcome: write, run, and own data validation test suites — closing the loop between PM-defined quality requirements and engineering-delivered test coverage.

---

## 📈 Currently Pursuing

- **Azure Data Engineer Associate** certification
- **General Assembly** — Data Engineering · Database Management · Digital Marketing *(May 2025)*
- **dbt Core** — building production SQL models on Databricks

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/stevelopezenterprise)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/BigZeeke)
