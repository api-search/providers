---
api_count: 2
api_specs:
- filename: apache-kylin-rest-api.yaml
  format: yaml
  label: Apache Kylin REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/openapi/apache-kylin-rest-api.yaml
apis:
- description: The Kylin REST API provides endpoints for SQL query execution, model management, project management, job management, and table management for administering the Kylin OLAP engine.
  name: Apache Kylin REST API
  slug: rest-api
- description: The Kylin JDBC driver provides SQL-over-Kylin access for BI tools and SQL clients, enabling standard JDBC connectivity to Kylin OLAP cubes.
  name: Apache Kylin JDBC Driver
  slug: jdbc-driver
capabilities:
- description: Workflow capability for data analysts and BI engineers to execute OLAP queries, manage projects, and monitor cube build jobs in Apache Kylin.
  name: Apache Kylin OLAP Analytics
  slug: olap-analytics
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/kylin
- title: ''
  type: Documentation
  url: https://kylin.apache.org/docs/
- title: ''
  type: GettingStarted
  url: https://kylin.apache.org/docs/tutorial/kylin_sample.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://kylin.apache.org/download/
- title: ''
  type: SpectralRules
  url: rules/apache-kylin-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-kylin-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/olap-analytics.yaml
created: '2026-03-16'
description: Apache Kylin is an open-source distributed analytics engine designed to provide a SQL interface and multi-dimensional analysis (OLAP) on large-scale datasets. It provides sub-second query latency on trillion-record datasets via pre-computed cubes and works on top of Hadoop, Spark, and cloud storage.
features:
- description: Pre-computed cubes enable sub-second query response on trillion-record datasets.
  name: Sub-Second OLAP Queries
- description: ANSI SQL interface for business analysts using existing SQL skills.
  name: SQL Interface
- description: Build cubes with aggregates pre-calculated for instant query response.
  name: Cube Pre-computation
- description: Works on top of Hadoop, Spark, and cloud object storage.
  name: Hadoop and Cloud Integration
- description: Standard JDBC and ODBC drivers for BI tool integration.
  name: JDBC/ODBC Drivers
- description: Incremental cube building with date-range segment management.
  name: Segment Management
- description: Project-based multi-tenancy for isolating datasets and access.
  name: Multi-Tenancy
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Reads from HDFS and executes MapReduce cube builds on Hadoop.
  name: Apache Hadoop
- description: Spark-based cube building for faster and more efficient data processing.
  name: Apache Spark
- description: Hive metastore integration for table schema and metadata.
  name: Apache Hive
- description: HBase storage for pre-computed cube data.
  name: Apache HBase
- description: Native Tableau connector via Kylin JDBC driver.
  name: Tableau
- description: Apache Superset integration via JDBC for self-service analytics.
  name: Apache Superset
jsonld:
- class_count: 10
  name: Apache Kylin Rest Api Context
  property_count: 29
  slug: apache-kylin-rest-api-context
layout: provider
modified: '2026-04-19'
name: Apache Kylin
rules:
- name: Apache Kylin API Rules
  rule_count: 12
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 2
  slug: apache-kylin-spectral-rules
skills: []
slug: apache-kylin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-kylin\nname: Apache Kylin\ndescription: >-\n  Apache Kylin is an open-source distributed analytics engine designed to provide a SQL interface and multi-dimensional analysis (OLAP) on large-scale datasets. It provides sub-second query latency on trillion-record datasets via pre-computed cubes and works on top of Hadoop, Spark, and cloud storage.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Big Data\n  - Cube\n  - OLAP\n  - Open Source\n  - SQL\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-kylin:rest-api\n    name: Apache Kylin REST API\n    description: >-\n      The Kylin REST API provides endpoints for SQL query execution, model management, project management, job management, and table management\
  \ for administering the Kylin OLAP engine.\n    humanURL: https://kylin.apache.org/docs/restapi/\n    tags:\n      - JDBC\n      - OLAP\n      - REST\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://kylin.apache.org/docs/restapi/\n      - type: OpenAPI\n        url: openapi/apache-kylin-rest-api.yaml\n\n  - aid: apache-kylin:jdbc-driver\n    name: Apache Kylin JDBC Driver\n    description: >-\n      The Kylin JDBC driver provides SQL-over-Kylin access for BI tools and SQL clients, enabling standard JDBC connectivity to Kylin OLAP cubes.\n    humanURL: https://kylin.apache.org/docs/tutorial/jdbc.html\n    tags:\n      - JDBC\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://kylin.apache.org/docs/tutorial/jdbc.html\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/kylin\n  - type: Documentation\n    url: https://kylin.apache.org/docs/\n\
  \  - type: GettingStarted\n    url: https://kylin.apache.org/docs/tutorial/kylin_sample.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Versioning\n    url: https://kylin.apache.org/download/\n  - type: SpectralRules\n    url: rules/apache-kylin-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-kylin-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/olap-analytics.yaml\n  - type: Features\n    data:\n      - name: Sub-Second OLAP Queries\n        description: Pre-computed cubes enable sub-second query response on trillion-record datasets.\n      - name: SQL Interface\n        description: ANSI SQL interface for business analysts using existing SQL skills.\n      - name: Cube Pre-computation\n        description: Build cubes with aggregates pre-calculated for instant query response.\n      - name: Hadoop and Cloud Integration\n        description: Works on top of Hadoop, Spark, and cloud object storage.\n\
  \      - name: JDBC/ODBC Drivers\n        description: Standard JDBC and ODBC drivers for BI tool integration.\n      - name: Segment Management\n        description: Incremental cube building with date-range segment management.\n      - name: Multi-Tenancy\n        description: Project-based multi-tenancy for isolating datasets and access.\n  - type: UseCases\n    data:\n      - name: Data Warehouse Query Acceleration\n        description: Accelerate slow Hive or Spark queries with Kylin cube pre-computation.\n      - name: BI Tool Integration\n        description: Connect Tableau, PowerBI, and Superset to Kylin via JDBC for analytics.\n      - name: Real-Time OLAP\n        description: Stream data into Kylin incrementally for near-real-time OLAP analytics.\n      - name: Large-Scale Reporting\n        description: Generate business reports over trillion-record datasets in seconds.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: Reads from HDFS and\
  \ executes MapReduce cube builds on Hadoop.\n      - name: Apache Spark\n        description: Spark-based cube building for faster and more efficient data processing.\n      - name: Apache Hive\n        description: Hive metastore integration for table schema and metadata.\n      - name: Apache HBase\n        description: HBase storage for pre-computed cube data.\n      - name: Tableau\n        description: Native Tableau connector via Kylin JDBC driver.\n      - name: Apache Superset\n        description: Apache Superset integration via JDBC for self-service analytics.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Cube
- OLAP
- Open Source
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/apis.yml
use_cases:
- description: Accelerate slow Hive or Spark queries with Kylin cube pre-computation.
  name: Data Warehouse Query Acceleration
- description: Connect Tableau, PowerBI, and Superset to Kylin via JDBC for analytics.
  name: BI Tool Integration
- description: Stream data into Kylin incrementally for near-real-time OLAP analytics.
  name: Real-Time OLAP
- description: Generate business reports over trillion-record datasets in seconds.
  name: Large-Scale Reporting
---
