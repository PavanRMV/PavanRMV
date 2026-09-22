1|# Pavan Ramisetty
2|
3|**Data Engineer | Databricks | Apache Spark | Delta Lakehouse | Cloud Data Platforms**
4|
5|I am a Data Engineer with 5+ years of experience building governed batch and real-time data platforms using Databricks, Apache Spark, Python, and SQL across Azure, AWS, and GCP.
6|
7|My experience includes Delta Lakehouse architecture, Spark Structured Streaming, Kafka, CDC, SCD Type 2, cloud migrations, data governance, CI/CD, production monitoring, and performance and cost optimization.
8|
9|I am open to Data Engineer opportunities in the United States.
10|
11|**Arkansas, United States** · [LinkedIn](https://www.linkedin.com/in/saipavan12/)
12|
13|## What I bring
14|
15|- **Data platform engineering:** build scalable, governed batch and streaming pipelines for analytics and AI/ML use cases
16|- **Lakehouse architecture:** design Delta Lakehouse workloads using Databricks, Apache Spark, Medallion Architecture, CDC, and SCD Type 2
17|- **Cloud engineering:** deliver data workflows across Azure, AWS, and GCP using services including ADLS, Event Hubs, Glue, Lambda, S3, GCS, and BigQuery
18|- **Reliability and performance:** improve pipeline monitoring, query performance, compute efficiency, and production troubleshooting
19|- **Data governance and delivery:** apply Unity Catalog, data-quality controls, CI/CD, approval gates, and environment-specific deployment practices
20|
21|## Featured projects
22|
23|### Retail Merchandise Revenue Analytics on Snowflake
24|
25|[![Retail merchandise revenue dashboard showing sales, cancellation exposure, trends, and leading SKUs](assets/retail-revenue-analytics-preview.png)](https://github.com/PavanRMV/retail-revenue-analytics-snowflake)
26|
27|A transaction-integrity and customer analytics project built from all 541,909 rows in the UCI Online Retail dataset, with Snowflake-oriented SQL and full local validation in DuckDB.
28|
29|- Reconciled 541,909 source rows to 541,909 fact rows with no duplicate fact keys or required-dimension orphans
30|- Separated merchandise, service/accounting, and unresolved-review populations so postage, fees, bad debt, samples, and vouchers do not inflate merchandise KPIs
31|- Delivered tested dimensional models, cancellation-exposure analysis, product and country marts, purchase-only customer segmentation, reproducible acquisition, and a fail-closed Snowflake deployment plan
32|
33|[View repository](https://github.com/PavanRMV/retail-revenue-analytics-snowflake)
34|
35|### Ecommerce Growth Intelligence
36|
37|[![Ordered ecommerce conversion funnel from viewed item to purchase](assets/ecommerce-funnel-preview.png)](https://github.com/PavanRMV/ecommerce-growth-intelligence)
38|
39|An end-to-end GA4 ecommerce analytics project that turns public event data into tested BigQuery/dbt marts and four Tableau dashboards.
40|
41|- Built an ordered shopping funnel, executive KPI layer, repeat-purchase cohorts, sample-window RFM segments, and product-performance analysis
42|- Kept three different purchase measures separate so stakeholders do not compare incompatible conversion rates
43|- Validated the repository with automated tests, SQL linting, independent KPI checks, provenance hashes, and explicit limitations
44|
45|[View repository](https://github.com/PavanRMV/ecommerce-growth-intelligence) · [Open Tableau dashboards](https://public.tableau.com/views/Ecommerce_Growth_Intelligence/ExecutiveOverview?:showVizHome=no)
46|
47|### US Hospital Readmission & Community Health Risk Intelligence
48|
49|[![Healthcare readmission intelligence executive overview](assets/healthcare-executive-preview.png)](https://github.com/PavanRMV/healthcare-readmission-intelligence)
50|
51|A healthcare analytics portfolio combining CMS hospital data with CDC community-health estimates for transparent readmission screening and benchmarking.
52|
53|- Modeled 5,419 hospitals and 28,740 readmission rows while preserving measure-level context
54|- Built reproducible Python and SQLite pipelines, portable SQL analysis, generated reports, and a source-controlled Power BI project
55|- Surfaced missing data, ambiguous geographic joins, and denominator limitations instead of hiding them
56|
57|[View repository](https://github.com/PavanRMV/healthcare-readmission-intelligence)
58|
59|## Core toolkit
60|
61|| Area | Tools and methods |
62||---|---|
63|| Analytics | SQL, Python, pandas, exploratory analysis, KPI design |
64|| Data modeling | Snowflake, BigQuery, dbt, DuckDB, SQLite, dimensional modeling, grain contracts |
65|| Visualization | Power BI, DAX, Tableau, executive dashboards, data storytelling |
66|| Engineering | Git, GitHub, automated tests, CLI workflows, reproducible exports |
67|| Quality | Reconciliation, provenance, exception reporting, privacy-aware publication |
68|
69|## How I work
70|
71|I start with the decision a stakeholder needs to make, then define the data grain and metric rules before building a chart. I test the pipeline, reconcile important totals, and state where the evidence stops. The result should be useful to a business reader and reviewable by a technical team.
72|
73|## Portfolio principles
74|
75|- Clear business questions before tools
76|- Reproducible analysis instead of one-off screenshots
77|- Tested metrics instead of unexplained totals
78|- Direct findings with visible caveats
79|- Focused project scope instead of unnecessary tool sprawl
80|