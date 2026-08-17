# AI Data Career Operating System
### Master Roadmap — Data Analyst → Analytics Engineer → Data Engineer

**Owner:** Arun Pandian | **Base:** Coimbatore / Chennai, Tamil Nadu
**Primary target:** Data Analyst / BI Analyst / Power BI Analyst
**Certification path:** PL-300 → DP-600 → DP-700
**Long-term target:** Analytics Engineer → Data Engineer (Microsoft Fabric track)

---

## 1. Operating Principle

Nothing is taught as an isolated tool. Every concept is anchored to the real business data lifecycle:

```
BUSINESS QUESTION → DATA REQUIREMENT → DATA SOURCE → DATA INGESTION →
DATA CLEANING → DATA MODEL → SQL / PYTHON → DAX → POWER BI →
INSIGHT → BUSINESS RECOMMENDATION → PRODUCTION DATA PIPELINE
```

**Do not force Data Engineering before Data Analyst fundamentals are solid.** DA is the immediate target; DE is the long-term destination reached *through* DA + Analytics Engineering.

**Learning ratio (70/20/10):** 70% hands-on projects · 20% exercises/problems · 10% theory. Avoid tutorial hell.

**Teaching pattern for every concept:**
```
CONCEPT → WHY IT EXISTS → BUSINESS USE CASE → SYNTAX/TOOL → SMALL EXAMPLE
→ HANDS-ON TASK → MINI PROJECT → INTERVIEW QUESTION → REAL-WORLD SCENARIO
→ COMMON MISTAKES → ASSESSMENT
```

**Learning loop:** Learn → Build → Break → Debug → Explain → Document.

---

## 2. The 32-Topic Learning Architecture

| # | Topic | # | Topic |
|---|---|---|---|
| 1 | Excel | 17 | Git/GitHub |
| 2 | Statistics | 18 | Data Warehousing |
| 3 | SQL | 19 | Dimensional Modeling |
| 4 | Data Cleaning | 20 | dbt |
| 5 | Power Query | 21 | ETL/ELT |
| 6 | Data Modeling | 22 | Microsoft Fabric |
| 7 | Power BI | 23 | OneLake |
| 8 | DAX | 24 | Lakehouse |
| 9 | Power BI Service | 25 | Data Pipelines |
| 10 | PL-300 Prep | 26 | Dataflows Gen2 |
| 11 | Python | 27 | PySpark |
| 12 | Pandas | 28 | KQL |
| 13 | PostgreSQL | 29 | Monitoring |
| 14 | APIs | 30 | Data Quality |
| 15 | Data Automation | 31 | Security/Governance |
| 16 | Advanced SQL | 32 | Production Data Engineering |

---

## 3. Phase Breakdown

### PHASE 1 — Data Analyst Foundations (Topics 1–10)

**Excel**
Spreadsheet fundamentals, Tables, data cleaning, IF, SUMIFS, COUNTIFS, XLOOKUP, INDEX/MATCH, text functions, date functions, PivotTables, PivotCharts, Power Query, Power Pivot, Data Models, dashboard design.
→ **Project:** Sales Performance Dashboard

**Statistics** (every concept needs a business example)
Mean, median, mode, variance, standard deviation, percentiles, quartiles, IQR, outliers, correlation, covariance, probability, sampling, confidence intervals, hypothesis testing, bias, correlation vs. causation.

**SQL**
SELECT, WHERE, DISTINCT, ORDER BY, GROUP BY, HAVING, aggregations, CASE, NULL handling, string/date functions, JOINs, SELF JOIN, subqueries, CTEs, UNION, EXISTS, window functions (ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD), query optimization.
→ **Projects (min. 30 business questions each):** E-commerce Analytics · HR Analytics · Banking Analytics

**Data Cleaning** — integrated throughout Excel/Power Query/SQL/Pandas work, not a standalone module.

**Power Query**
Data sources, profiling, data types, cleaning, filtering, splitting, merging, appending, grouping, pivot/unpivot, parameters, custom & conditional columns, functions, M language. Build reusable transformation pipelines.

**Data Modeling**
Fact tables, dimension tables, primary/foreign keys, relationships, cardinality, filter direction, star schema, snowflake schema, date tables, slowly changing dimensions, granularity. **Design the schema before building any Power BI report.**

**Power BI**
Data sources, Power Query, semantic models, relationships, visuals, slicers, drillthrough, tooltips, bookmarks, buttons, dynamic titles, field parameters, conditional formatting, accessibility, mobile layouts, Performance Analyzer, DAX optimization.

**DAX**
Measures, calculated columns/tables, SUM, COUNT, AVERAGE, CALCULATE, FILTER, ALL, REMOVEFILTERS, VALUES, SUMX, AVERAGEX, COUNTX, RANKX, variables, row context, filter context, context transition, time intelligence (YTD, MTD, QTD, YoY, MoM). Every DAX expression must come with an explanation of *why* it works.

**Power BI Service**
Workspaces, semantic models, reports, dashboards, Apps, publishing, refresh, gateway, sharing, subscriptions, alerts, row-level security, permissions, governance.

**PL-300 Preparation Mode**
Four exam domains, each gets concept lessons, hands-on labs, scenario questions, case studies, MCQs, troubleshooting questions, practical tasks, and mock exams:
1. Prepare the data
2. Model the data
3. Visualize and analyze the data
4. Manage and secure Power BI

Not "exam ready" until practical competency is demonstrated — not quiz memorization.

---

### PHASE 2 — Analyst → Analytics Engineer Bridge (Topics 11–21)

**Python**
Fundamentals, functions, collections, exceptions, files, modules, NumPy, Pandas, Matplotlib, Plotly, Requests, SQLAlchemy.

**Pandas**
`read_csv`, `read_excel`, `read_sql`, filtering, `loc`/`iloc`, `groupby`, `merge`, `join`, `concat`, `pivot_table`, `melt`, `fillna`, `dropna`, `drop_duplicates`, `astype`, `apply`.
→ **Project:** Automated Job Market Intelligence Pipeline

**PostgreSQL**
Database design, tables, constraints, keys, indexes, views, materialized views, transactions, query plans, optimization.

**APIs / Data Automation / Advanced SQL / Git-GitHub** — supporting skills woven into the projects above.

**Analytics Engineering**
OLTP vs OLAP, data warehouse, data lake, lakehouse, ETL vs ELT, dimensional modeling, data marts, dbt, Git, testing, documentation, lineage.
→ **Project:** Production Analytics Warehouse

---

### PHASE 3 — Microsoft Fabric & Data Engineering (Topics 22–32)

**Microsoft Fabric**
OneLake, Lakehouse, Warehouse, Data Factory, Pipelines, Dataflows Gen2, Notebooks, Spark/PySpark, Semantic Models, Direct Lake, Eventhouse, KQL, security, governance, monitoring.

**Data Engineering**
- *Ingestion:* batch, incremental, API, database, file, streaming basics
- *Transformation:* SQL, PySpark, Dataflows, Notebooks
- *Orchestration:* pipelines, scheduling, dependencies, parameters, dynamic expressions, error handling
- *Optimization:* partitioning, query/Spark/warehouse/pipeline optimization
- *Monitoring:* pipeline monitoring, data quality, refresh failures, alerts, logging, observability

Certification progression once DA fundamentals are solid: **PL-300 → DP-600 → DP-700**

---

## 4. Project Engine (increasing difficulty)

**Beginner**
1. Excel Sales Dashboard
2. Excel HR Dashboard

**Intermediate**
3. SQL E-commerce Analytics
4. SQL Banking Analytics
5. Power BI Sales Intelligence
6. Power BI HR Analytics

**Advanced Analyst**
7. Job Market Intelligence
8. Customer Analytics
9. Financial Analytics

**Analytics Engineering**
10. PostgreSQL Data Warehouse
11. dbt Analytics Project

**Data Engineering**
12. API → Lakehouse → Spark → Warehouse → Power BI

Every project includes: business problem, stakeholders, requirements, dataset, data dictionary, architecture, data cleaning, data model, SQL, Python (where relevant), dashboard, KPIs, insights, recommendations, README, screenshots, GitHub repo, and a rehearsed interview explanation.

**Real-time project standard** — simulate the full pipeline and inject realistic messiness:
```
Source → Ingestion → Raw → Cleaning → Transformation → Storage →
Modeling → Analytics → Dashboard → Business Decision
```
Realistic problems to handle: missing data, duplicate records, nulls, incorrect types, late-arriving records, duplicate transactions, schema changes, API failures, refresh failures, incorrect relationships, performance problems, security requirements.

**Portfolio structure (every project):**
```
README.md
architecture.png
data_dictionary.md
sql/
python/
powerbi/
docs/
screenshots/
```
README sections: Business Problem, Objective, Dataset, Architecture, Data Model, Data Cleaning, Analysis, Dashboard, KPIs, Insights, Recommendations, Challenges, Future Improvements, Technologies.

---

## 5. Cadence Systems

### Daily
- 1–3 concepts learned
- Practice: 5 beginner + 5 intermediate + 2 advanced questions
- 3 SQL problems
- 1 Power BI hands-on task
- 3 interview questions
- 1 project task
- Revision of previous concepts

### Weekly
Weekly objectives, learning modules, practice tasks, project milestones, SQL problems, Power BI tasks, interview questions, assessment, weakness report. End-of-week scorecard:
```
Concept mastery %      Power BI score %
Practical mastery %    Project completion %
SQL score %             Interview readiness %
```

### Monthly
Technical test, SQL test, Power BI test, business case study, project review, interview simulation → classify as:
```
Weak → Beginner → Developing → Intermediate → Job Ready → Advanced → Production Ready
```

---

## 6. Interview Engine (target bank sizes)

| Area | Target |
|---|---|
| Excel | 50+ |
| SQL | 150+ |
| Power BI | 150+ |
| DAX | 100+ |
| Python | 100+ |
| Statistics | 75+ |
| Data Modeling | 75+ |
| Data Engineering | 100+ |

Plus: HR/behavioral questions, project questions, case studies, stakeholder scenarios, troubleshooting scenarios.

---

## 7. Business Case Engine

Rotate cases across industries: E-commerce, SaaS, FinTech, Banking, Healthcare, Retail, Manufacturing, Logistics, Telecom, EdTech, HR, Marketing.

Each case must define: business problem, stakeholder, KPIs, data required, data quality problems, analysis, visualization, insight, recommendation, expected business impact.

---

## 8. Job-Readiness Checklist

Not "job ready" just for finishing tutorials. Ready when able to:

- [ ] Write complex SQL independently
- [ ] Build a Power BI semantic model
- [ ] Write DAX measures
- [ ] Clean messy data
- [ ] Explain business KPIs
- [ ] Build an end-to-end dashboard
- [ ] Explain projects fluently
- [ ] Debug data problems
- [ ] Communicate insights to non-technical stakeholders
- [ ] Handle stakeholder requirements
- [ ] Work with Git
- [ ] Build an ETL pipeline
- [ ] Explain warehouse architecture

---

## 9. Career Tracking Dashboard (fields to maintain)

```
Skills · Certifications · Projects · GitHub · Interview readiness
SQL score · Power BI score · Python score · Data Engineering score
Applications · Interviews · Offers · Weak areas
```

---

## 10. Master Capstone — Real-Time BI Data Platform

```
APIs / Databases / CSV / Web Data
          ↓
  Python / API Ingestion
          ↓
       Raw Layer
          ↓
   Data Lake / OneLake
          ↓
     Transformation
          ↓
     PySpark / SQL
          ↓
      Silver Layer
          ↓
       Gold Layer
          ↓
      Warehouse
          ↓
    Semantic Model
          ↓
          DAX
          ↓
       Power BI
          ↓
  Executive Dashboard
```

Includes: incremental loading, data quality checks, logging, error handling, scheduling, monitoring, security, row-level security, documentation, Git, CI/CD basics, performance optimization.

---

## 11. How Study Sessions Should Run (assistant operating mode)

1. Determine current skill level.
2. Explain the concept.
3. Give a realistic business example.
4. Assign a task.
5. Wait for the answer before revealing solutions, when appropriate.
6. Review the work, identify mistakes, explain *why* they're mistakes.
7. Show a better solution.
8. Increase difficulty gradually.

**Anti-tutorial-hoarding rule:** when stuck, diagnose the specific gap → give a targeted explanation → give practice → test → return to the project. Only point to an external course when it solves a named, specific gap — never as a default response to struggle.

---

## 12. Final Outcome

**PL-300-ready + Data Analyst job-ready + strong BI portfolio + foundation for Analytics Engineering + foundation for Microsoft Fabric Data Engineering.**

Optimize for: **skills → projects → proof → interviews → job → advanced engineering** — not certificate collection.
