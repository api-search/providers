---
api_count: 1
apis:
- description: The Superset REST API v1 provides programmatic access to all Superset resources including dashboards (28 endpoints), charts (20 endpoints), datasets (19 endpoints), databases (30 endpoints), SQL Lab q
  name: Apache Superset REST API
  slug: apache-superset-rest-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/superset
- title: ''
  type: Documentation
  url: https://superset.apache.org/docs/intro
- title: ''
  type: Portal
  url: https://superset.apache.org/
- title: ''
  type: GettingStarted
  url: https://superset.apache.org/docs/quickstart
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/superset/releases
- title: ''
  type: Support
  url: https://github.com/apache/superset/discussions
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: Python Package
  type: SDK
  url: https://pypi.org/project/apache-superset/
created: '2026-03-16'
description: Apache Superset is a modern data exploration and visualization platform designed to be visual, intuitive, and interactive. It provides a rich set of data visualizations, a no-code chart builder, and a SQL editor with support for most SQL-speaking databases. Superset exposes a comprehensive REST API for programmatic access to dashboards, charts, datasets, databases, and user management. It is an Apache Software Foundation top-level project.
features:
- description: Drag-and-drop chart builder with 40+ visualization types requiring no coding.
  name: No-Code Chart Builder
- description: Browser-based SQL editor with query history, saved queries, and result export.
  name: SQL Lab
- description: Interactive dashboard composition with filters, tabs, and layout customization.
  name: Dashboard Builder
- description: Centralized dataset definitions with virtual columns, metrics, and certification.
  name: Semantic Layer
- description: Fine-grained data access control with row-level security rules.
  name: Row-Level Security
- description: Embed Superset dashboards in external applications via iframe or SDK.
  name: Embedded Dashboards
- description: Scheduled PDF/image reports and threshold-based alerts via email or Slack.
  name: Alerts and Reports
- description: 40+ database connectors via SQLAlchemy including BigQuery, Snowflake, and Redshift.
  name: Database Connectivity
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native PostgreSQL support as both metadata database and data source.
  name: PostgreSQL
- description: Druid connector for sub-second OLAP queries on time-series data.
  name: Apache Druid
- description: Google BigQuery connector for cloud data warehouse analytics.
  name: BigQuery
- description: Snowflake connector for cloud analytics platform.
  name: Snowflake
- description: Spark SQL via Hive Thrift Server for distributed data analysis.
  name: Apache Spark SQL
- description: Slack integration for alerts and scheduled report delivery.
  name: Slack
- description: Airflow integration for orchestrating data pipeline and report schedules.
  name: Apache Airflow
layout: provider
modified: '2026-04-19'
name: Apache Superset
skills: []
slug: apache-superset
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-superset\nname: Apache Superset\ndescription: >-\n  Apache Superset is a modern data exploration and visualization platform designed to be visual,\n  intuitive, and interactive. It provides a rich set of data visualizations, a no-code chart\n  builder, and a SQL editor with support for most SQL-speaking databases. Superset exposes a\n  comprehensive REST API for programmatic access to dashboards, charts, datasets, databases,\n  and user management. It is an Apache Software Foundation top-level project.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - BI\n  - Dashboard\n  - Data Visualization\n  - SQL\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-superset/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-superset:apache-superset-rest-api\n\
  \    name: Apache Superset REST API\n    description: >-\n      The Superset REST API v1 provides programmatic access to all Superset resources including\n      dashboards (28 endpoints), charts (20 endpoints), datasets (19 endpoints), databases (30\n      endpoints), SQL Lab queries (7 endpoints), saved queries (17 endpoints), tags, annotation\n      layers, CSS templates, themes, row-level security, and user management. Authentication uses\n      JWT Bearer tokens obtained via POST /api/v1/security/login.\n    humanURL: https://superset.apache.org/developer-docs/api\n    tags:\n      - REST\n      - Dashboards\n      - Charts\n      - Datasets\n      - SQL\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://superset.apache.org/developer-docs/api\n      - type: APIReference\n        url: https://superset.apache.org/docs/api\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/superset\n  - type: Documentation\n    url: https://superset.apache.org/docs/intro\n\
  \  - type: Portal\n    url: https://superset.apache.org/\n  - type: GettingStarted\n    url: https://superset.apache.org/docs/quickstart\n  - type: ReleaseNotes\n    url: https://github.com/apache/superset/releases\n  - type: Support\n    url: https://github.com/apache/superset/discussions\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://pypi.org/project/apache-superset/\n    title: Python Package\n  - type: Features\n    data:\n      - name: No-Code Chart Builder\n        description: Drag-and-drop chart builder with 40+ visualization types requiring no coding.\n      - name: SQL Lab\n        description: Browser-based SQL editor with query history, saved queries, and result export.\n      - name: Dashboard Builder\n        description: Interactive dashboard composition with filters, tabs, and layout customization.\n      - name: Semantic Layer\n        description: Centralized dataset definitions with virtual columns, metrics, and\
  \ certification.\n      - name: Row-Level Security\n        description: Fine-grained data access control with row-level security rules.\n      - name: Embedded Dashboards\n        description: Embed Superset dashboards in external applications via iframe or SDK.\n      - name: Alerts and Reports\n        description: Scheduled PDF/image reports and threshold-based alerts via email or Slack.\n      - name: Database Connectivity\n        description: 40+ database connectors via SQLAlchemy including BigQuery, Snowflake, and Redshift.\n  - type: UseCases\n    data:\n      - name: Business Intelligence Dashboards\n        description: Self-service BI dashboards for business users across operational and analytical data.\n      - name: Data Exploration\n        description: Ad-hoc data exploration and visualization for data analysts.\n      - name: Embedded Analytics\n        description: White-label analytics embedded in SaaS products and internal applications.\n      - name: SQL-Based Reporting\n\
  \        description: Custom SQL-based reports and scheduled distribution.\n  - type: Integrations\n    data:\n      - name: PostgreSQL\n        description: Native PostgreSQL support as both metadata database and data source.\n      - name: Apache Druid\n        description: Druid connector for sub-second OLAP queries on time-series data.\n      - name: BigQuery\n        description: Google BigQuery connector for cloud data warehouse analytics.\n      - name: Snowflake\n        description: Snowflake connector for cloud analytics platform.\n      - name: Apache Spark SQL\n        description: Spark SQL via Hive Thrift Server for distributed data analysis.\n      - name: Slack\n        description: Slack integration for alerts and scheduled report delivery.\n      - name: Apache Airflow\n        description: Airflow integration for orchestrating data pipeline and report schedules.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-superset/refs/heads/main/apis.yml
tags:
- Analytics
- BI
- Dashboard
- Data Visualization
- SQL
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-superset/refs/heads/main/apis.yml
use_cases:
- description: Self-service BI dashboards for business users across operational and analytical data.
  name: Business Intelligence Dashboards
- description: Ad-hoc data exploration and visualization for data analysts.
  name: Data Exploration
- description: White-label analytics embedded in SaaS products and internal applications.
  name: Embedded Analytics
- description: Custom SQL-based reports and scheduled distribution.
  name: SQL-Based Reporting
---
