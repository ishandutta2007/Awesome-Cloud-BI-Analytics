# Awesome-Cloud-BI-Analytics
# Awesome-Cloud-BI-Analytics

# Awesome-Cloud-BI-Analytics

## Top Cloud BI Analytics Ecosystem



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

| Product | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | ~$3.1T Market Cap (Microsoft) | $10/user/month (Power BI Pro) | Free forever (Power BI Desktop: local authoring and personal reporting, no cloud sharing/collaboration) | Business analytics platform integrated with Microsoft Fabric. Features Power BI Desktop, Power BI Service, Copilot AI, and Direct Lake mode. |
| **[Looker (Google Cloud)](https://looker.com/)** | ~$2.1T Market Cap (Alphabet) | $35,000/year (~$2,917/month base platform fee; Looker Studio Pro is $9/user/month) | 30-day free trial on Google Cloud with $300 trial credits; Looker Studio core is free with basic connector limits | Enterprise BI platform built on LookML semantic modeling language. Features Git integration, embedded analytics, and API governance. |
| **[Salesforce CRM Analytics (Wave)](https://www.salesforce.com/analytics/)** | ~$280B Market Cap (Salesforce) | $140/user/month (CRM Analytics Growth, billed annually) | 30-day free trial (pre-configured Salesforce environment with sample CRM analytics data) | Salesforce's native BI platform for CRM data. Features dashboards, dataflows, and AI-powered insights directly on Salesforce data. |
| **[Tableau Cloud](https://www.tableau.com/products/cloud-bi)** | ~$15.7B Acquisition Value (Salesforce) | $15/user/month (Tableau Viewer; Creator starts at $75/user/month, billed annually) | 14-day free trial (full Tableau Cloud features, web authoring, and Tableau Pulse) | Fully hosted analytics solution with Tableau Agent and Tableau Pulse. Features hybrid data connectivity via Tableau Bridge. |
| **[Qlik Sense](https://www.qlik.com/)** | ~$10B+ Valuation (Thoma Bravo) | $30/user/month (Standard plan, min. 20 users / billed annually) | 30-day free trial (full Qlik Cloud Analytics capabilities, up to 5GB in-memory data capacity) | Associative analytics engine with self-service visualization, guided analytics, and embedded analytics with open APIs. |
| **[ThoughtSpot](https://www.thoughtspot.com/)** | ~$4.5B Valuation (Latest round) | $25/user/month (Essentials plan, billed annually) | 30-day free trial (access to Spotter AI agent, Search, and live query connections) | Agentic analytics platform with Spotter 3 AI agent. Features natural language search and embedded analytics via SDK/API/MCP. |
| **[Sigma Computing](https://www.sigmacomputing.com/)** | ~$1.5B Valuation (Series D) | $15,000/year (Starter package; ~$1,250/month equivalent for Creator seats) | 14-day free trial (full live warehouse querying with sample datasets or connected cloud DWH) | Cloud-native analytics platform sitting directly on Snowflake, Databricks, and BigQuery with spreadsheet-like interface. |
| **[Sisense](https://www.sisense.com/)** | ~$1.0B Valuation (Unicorn valuation) | $10,000/year (~$833/month equivalent, base self-serve package) | 14-day free trial (access to web modeler, ElastiCube, and sample dashboard builders) | BI and analytics platform designed for embedded analytics. Features ElastiCube in-memory engine and BloX widget framework. |
| **[Domo](https://www.domo.com/)** | ~$400M Asset Sale / ~$160M Market Cap | $300/month (Standard consumption tier starting package) | 30-day free trial (enterprise capabilities with unlimited credits during evaluation) | Cloud-native BI and data product platform with 1,000+ connectors, Magic ETL, and App Catalyst. |
| **[GoodData](https://www.gooddata.com/)** | ~$63M ARR / ~$350M Total Funding | $1,500/month (Professional tier platform base fee) | 30-day free trial (GoodData.AI platform with unlimited users and DuckDB/Iceberg integration) | Composable analytics platform with Analytics Lake infrastructure, FlexConnect, and multi-tenant isolation. |



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
