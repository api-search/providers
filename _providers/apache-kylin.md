---
api_count: 2
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
