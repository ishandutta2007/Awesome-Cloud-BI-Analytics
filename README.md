# Awesome-Cloud-BI-Analytics
# Awesome-Cloud-BI-Analytics

# Awesome-Cloud-BI-Analytics

# Top Cloud BI Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Business Intelligence, Data Visualization & Embedded Analytics*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud BI & Analytics**. These tools help organizations connect to data sources, build interactive dashboards, perform ad-hoc analysis, and embed analytics into applications — enabling data-driven decision-making at scale.

**Examples** include Salesforce CRM Analytics (formerly Wave), Tableau Cloud, Microsoft Power BI, Looker, Domo, Qlik Sense, Sisense, ThoughtSpot, GoodData, and Sigma Computing (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom semantic layers, and open analytics pipelines — ideal for organizations seeking transparent, vendor-independent business intelligence.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce CRM Analytics (Wave)](https://www.salesforce.com/analytics/)**  
  Salesforce's native BI platform for CRM data. Formerly known as Wave Analytics, Einstein Analytics, and Tableau CRM. Provides dashboards, dataflows, and AI-powered insights directly on Salesforce data .

- **[Tableau Cloud](https://www.tableau.com/products/cloud-bi)**  
  Fully hosted, agentic analytics solution with Tableau Agent and Tableau Pulse. Features AI-powered insights delivered to Slack, Teams, and email, plus Tableau Bridge for hybrid data connectivity .

- **[Microsoft Power BI](https://powerbi.microsoft.com/)**  
  Microsoft's business analytics platform integrated with Microsoft Fabric. Features Power BI Desktop for authoring, Power BI Service for sharing, Copilot AI assistance, and Direct Lake mode for querying OneLake without data import .

- **[Looker (Google Cloud)](https://looker.com/)**  
  Google Cloud's enterprise BI platform built on LookML, a code-based semantic modeling language. Features Git integration for version control, embedded analytics, and API-driven customization .

- **[Domo](https://www.domo.com/)**  
  Cloud-native BI and data product platform with 1,000+ connectors. Features Magic ETL for data transformation, App Catalyst for pro-code apps, and AI-driven workflows integrated with Google Cloud Vertex AI .

- **[Qlik Sense](https://www.qlik.com/)**  
  Associative analytics platform with Qlik Sense Enterprise, Qlik Cloud Analytics, and Qlik Analytics Platform. Features self-service visualization, guided analytics, and embedded analytics with open APIs .

- **[Sisense](https://www.sisense.com/)**  
  BI and analytics platform for embedded analytics. Features ElastiCube for in-memory data blending, BloX widget framework for custom dashboards, and AI-powered predictive analytics .

- **[ThoughtSpot](https://www.thoughtspot.com/)**  
  Agentic analytics platform with Spotter 3 AI agent. Features natural language search, embedded analytics via SDK/API/MCP, and unified structured and unstructured data analysis .

- **[GoodData](https://www.gooddata.com/)**  
  Composable analytics platform with Analytics Lake infrastructure. Features Apache Iceberg and DuckDB integration, FlexConnect for custom data connectors, and multi-tenant workspace isolation .

- **[Sigma Computing](https://www.sigmacomputing.com/)**  
  Cloud-native analytics platform sitting on top of Snowflake, Databricks, and BigQuery. Features spreadsheet-like interface for business users, warehouse-native governance, and Sigma Agents for autonomous workflows .

## Open-Source GitHub Projects

- **[Apache Superset](https://github.com/apache/superset)**  
  Modern, enterprise-ready BI web application (Apache-2.0). No-code chart builder, SQL Editor, lightweight semantic layer, and support for nearly any SQL database. Cloud-native architecture designed for scale. One of the most widely adopted open-source BI platforms .

- **[Metabase](https://github.com/metabase/metabase)**  
  Easy-to-use open-source BI tool (AGPL-3.0) for self-service analytics. Features Query Builder for non-SQL users, Metabot AI assistant, interactive dashboards, granular permissions, and embedding options. Connects to 20+ data sources including PostgreSQL, MySQL, and Snowflake .

- **[Redash](https://github.com/getredash/redash)**  
  Open-source data visualization and dashboarding tool (BSD-2-Clause). Query editor with schema browser and auto-complete, drag-and-drop visualizations, scheduled refreshes, alerts, and REST API. Designed for SQL users to explore and share data across organizations .

- **[Knowage](https://github.com/KnowageLabs/Knowage-Server)**  
  Full open-source suite for Business Intelligence and Analytics (AGPL-3.0) by Engineering Group. Modules include Enterprise Reporting, Smart Intelligence for self-service BI, Location Intelligence, Performance Management with KPIs, and Custom Analytics with R/Python integration .

- **[Apache Druid](https://github.com/apache/druid)**  
  High-performance, real-time analytics database (Apache-2.0) for sub-second queries on streaming and batch data. Features native Kafka/Kinesis integration, SQL support, schema auto-discovery, and elastic architecture for billions to trillions of rows .

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source observability and analytics platform (AGPL-3.0). While primarily for monitoring, widely used for BI dashboards with support for SQL databases, Prometheus, and multiple data sources. Extensive plugin ecosystem.

- **[Lightdash](https://github.com/lightdash/lightdash)**  
  Open-source BI tool built for dbt users (MIT). Transforms dbt models into explorable dashboards, metrics, and self-service analytics. Features CLI-based deployment and developer-first workflow.

- **[Cube.js](https://github.com/cube-js/cube)**  
  Open-source semantic layer (Apache-2.0) for building data applications. Provides headless BI infrastructure with SQL generation, caching, and API for custom analytics frontends.

### Additional Strong Open-Source Options

- **[Databend](https://github.com/datafuselabs/databend)** — Cloud-native data warehouse with BI capabilities.
- **[Trino](https://github.com/trinodb/trino)** — Distributed SQL query engine for analytics on data lakes.
- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — Column-oriented OLAP database for real-time analytics.
- **[Apache Doris](https://github.com/apache/doris)** — MPP-based real-time analytical database.
- **[Jupyter](https://github.com/jupyter/notebook)** — Interactive computing notebooks for data analysis and visualization.
- Community **dbt** packages for semantic modeling and **Streamlit** apps for custom analytics.

**Frameworks for building custom systems**: Combine **Apache Superset** or **Metabase** as the BI frontend with **Cube.js** for semantic modeling, **Apache Druid** or **ClickHouse** for real-time analytics queries, **dbt** for data transformation, and **PostgreSQL** for metadata — creating a fully self-hosted, enterprise-grade BI stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Analytics data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, resource provisioning, and ongoing maintenance.

---

**Made for data teams, analysts, engineers, and developers building transparent analytics solutions.**  
Let's make cloud BI and analytics more open, data-driven, and accessible.
