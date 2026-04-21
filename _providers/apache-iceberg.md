---
api_count: 3
apis:
- description: The Iceberg REST Catalog API defines the specification for catalog server implementations, enabling table discovery, creation, metadata management, namespace management, and multi-table transactions o
  name: Apache Iceberg REST Catalog API
  slug: rest-catalog-api
- description: The Iceberg Java API provides programmatic access to table operations, schema management, partition management, and catalog implementations. It is the primary library for integrating Iceberg with JVM-
  name: Apache Iceberg Java API
  slug: java-api
- description: PyIceberg is the official Python implementation of the Apache Iceberg table specification. It provides programmatic access to Iceberg table metadata and data, with integrations for PyArrow, Pandas, Du
  name: PyIceberg Python API
  slug: python-api
capabilities:
- description: Workflow capability for data engineers and lakehouse architects to manage namespaces, tables, and views in Apache Iceberg catalogs via the REST Catalog API.
  name: Apache Iceberg Catalog Management
  slug: catalog-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/iceberg
- title: ''
  type: Documentation
  url: https://iceberg.apache.org/docs/latest/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Blog
  url: https://iceberg.apache.org/blogs/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@ApacheIceberg
- title: ''
  type: Versioning
  url: https://iceberg.apache.org/releases/
- title: ''
  type: ReleaseNotes
  url: https://iceberg.apache.org/releases/
- title: ''
  type: SpectralRules
  url: rules/apache-iceberg-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-iceberg-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/catalog-management.yaml
created: '2026-03-16'
description: Apache Iceberg is an open table format for large analytic datasets that provides ACID transactions, schema evolution, hidden partitioning, and time travel. It works with Spark, Flink, Hive, Presto, Trino, DuckDB, ClickHouse, and many more compute engines. Governed by the Apache Software Foundation under the Apache 2.0 license.
features:
- description: Full ACID transaction support with serializable isolation for concurrent readers and writers.
  name: ACID Transactions
- description: Add, drop, update, or rename columns without rewriting existing data files.
  name: Schema Evolution
- description: Automatic partition management that prevents common user mistakes and silently incorrect results.
  name: Hidden Partitioning
- description: Change partition layout over time without rewriting existing data.
  name: Partition Evolution
- description: Query historical snapshots of tables and roll back to any prior version.
  name: Time Travel
- description: Supports upserts, deletes, and updates at the row level via merge-on-read and copy-on-write modes.
  name: Row-Level Updates
- description: Works with Spark, Flink, Hive, Trino, Presto, Impala, DuckDB, ClickHouse, and more.
  name: Multi-Engine Support
- description: Native support for S3, ADLS, GCS, and HDFS with no filesystem dependencies.
  name: Cloud-Native Storage
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Full read/write support for Iceberg tables in Spark batch and streaming workloads.
  name: Apache Spark
- description: Streaming and batch integration with exactly-once write support.
  name: Apache Flink
- description: Read and write Iceberg tables from Hive queries using the Iceberg Hive integration.
  name: Apache Hive
- description: Query Iceberg tables from Trino with full partition pruning and predicate pushdown.
  name: Trino
- description: Use AWS Glue as the Iceberg catalog backend with full metadata management.
  name: AWS Glue Catalog
- description: Query Iceberg tables stored in S3 using Amazon Athena.
  name: AWS Athena
- description: Git-like catalog branching and versioning via Nessie catalog integration.
  name: Project Nessie
- description: Local analytics on Iceberg tables via the DuckDB Iceberg extension.
  name: DuckDB
- description: Query Iceberg tables from ClickHouse via the ClickHouse Iceberg integration.
  name: ClickHouse
- description: Access Iceberg tables managed in Snowflake's Polaris catalog.
  name: Snowflake
- description: Use BigQuery as a compute engine over Iceberg tables with BigLake Metastore.
  name: Google BigQuery
- description: Create and query Iceberg tables on Databricks using Unity Catalog.
  name: Databricks
jsonld:
- class_count: 119
  name: Apache Iceberg Rest Catalog Open Api Context
  property_count: 190
  slug: apache-iceberg-rest-catalog-open-api-context
layout: provider
modified: '2026-04-19'
name: Apache Iceberg
rules:
- name: Apache Iceberg API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 5
    warn: 12
  slug: apache-iceberg-spectral-rules
skills: []
slug: apache-iceberg
solutions: []
tags:
- ACID
- Analytics
- Apache
- Data Lake
- Lakehouse
- Open Source
- Table Format
url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/apis.yml
use_cases:
- description: Build open lakehouse architectures with ACID guarantees across petabyte-scale datasets.
  name: Lakehouse Analytics
- description: Stream data into Iceberg tables via Flink or Kafka Connect with exactly-once semantics.
  name: Real-Time Data Pipelines
- description: Use time travel to audit historical data states and implement regulatory compliance.
  name: Data Versioning and Auditing
- description: Query the same Iceberg tables from multiple engines (Spark, Trino, DuckDB) without data duplication.
  name: Multi-Engine Query Federation
- description: Migrate on-premises Hive workloads to cloud-native Iceberg tables with full compatibility.
  name: Cloud Data Migration
---
