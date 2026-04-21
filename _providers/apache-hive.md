---
api_count: 2
apis:
- description: WebHCat (Templeton) REST API for Apache Hive providing DDL operations, HiveQL job submission, and Hive Metastore metadata access over HTTP.
  name: Apache Hive WebHCat REST API
  slug: apache-hive-webhcat-api
- description: JDBC interface to HiveServer2 for standard SQL client connectivity, supporting parameterized queries, result sets, and connection pooling from Java and ODBC-bridge applications.
  name: Apache Hive JDBC API
  slug: apache-hive-jdbc
capabilities:
- description: ''
  name: Hive Data Querying
  slug: hive-data-querying
common:
- title: ''
  type: Documentation
  url: https://cwiki.apache.org/confluence/display/Hive/Home
- title: ''
  type: GettingStarted
  url: https://cwiki.apache.org/confluence/display/Hive/GettingStarted
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/hive
- title: ''
  type: SpectralRules
  url: rules/apache-hive-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-hive-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/hive-data-querying.yaml
created: '2026-03-16'
description: Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along with a WebHCat REST API for job submission and metastore access.
features:
- description: SQL-like query language for reading, writing, and aggregating data stored in distributed storage.
  name: HiveQL SQL Interface
- description: HTTP REST API (Templeton) for DDL operations, job submission, and metastore metadata access.
  name: WebHCat REST API
- description: Thrift-based server with JDBC and ODBC drivers for standard SQL client connectivity.
  name: HiveServer2 JDBC/ODBC
- description: Central repository for table schema, partition metadata, and storage location information.
  name: Hive Metastore
- description: Partition tables by column values for efficient query pruning and data organization.
  name: Partitioning
- description: Optimized columnar storage formats with predicate pushdown and compression support.
  name: ORC and Parquet Storage
- description: Full ACID transaction support for inserts, updates, and deletes on managed ORC tables.
  name: ACID Transactions
- description: Batch processing of rows in CPU register-width vectors for improved query throughput.
  name: Vectorized Query Execution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Hive reads and writes data stored in HDFS as the primary storage layer.
  name: Apache Hadoop HDFS
- description: Spark uses the Hive Metastore for table discovery and supports Hive UDFs.
  name: Apache Spark
- description: Hive HBase storage handler enables HiveQL queries against HBase tables.
  name: Apache HBase
- description: Apache Tez DAG execution engine replaces MapReduce for faster Hive query processing.
  name: Apache Tez
- description: Presto and Trino use the Hive Metastore for table metadata in federated SQL queries.
  name: Presto / Trino
jsonld:
- class_count: 21
  name: Apache Hive Webhcat Context
  property_count: 0
  slug: apache-hive-webhcat-context
layout: provider
modified: '2026-04-19'
name: Apache Hive
rules:
- name: Apache Hive API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: apache-hive-spectral-rules
skills: []
slug: apache-hive
solutions: []
tags:
- Apache
- Big Data
- Data Warehouse
- ETL
- Hadoop
- Open Source
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml
use_cases:
- description: Run SQL analytics on petabyte-scale datasets stored in HDFS or object storage.
  name: Data Warehouse Analytics
- description: Use HiveQL scripts to transform and load data between raw and curated data lake zones.
  name: ETL Pipeline Orchestration
- description: Query structured data interactively using Beeline or JDBC-connected BI tools.
  name: Ad-Hoc Data Exploration
- description: Parse and aggregate application logs stored as text or JSON in HDFS using Hive SerDes.
  name: Log Analysis
- description: Use the Hive Metastore as a shared schema registry for Spark, Flink, and Presto.
  name: Data Catalog Integration
---
