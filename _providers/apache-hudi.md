---
api_count: 2
apis:
- description: REST API for the Apache Hudi Timeline Server providing table timeline management, commit metadata inspection, and table administration for Hudi data lake tables.
  name: Apache Hudi Timeline Server API
  slug: apache-hudi-timeline-api
- description: Java API for writing Hudi tables with upserts, inserts, and deletes, plus timeline management, compaction, and Spark/Flink DataSource integration APIs.
  name: Apache Hudi Java API
  slug: apache-hudi-java-api
capabilities:
- description: ''
  name: Hudi Lakehouse Management
  slug: hudi-lakehouse-management
common:
- title: ''
  type: Documentation
  url: https://hudi.apache.org/docs/overview
- title: ''
  type: GettingStarted
  url: https://hudi.apache.org/docs/quick-start-guide
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/hudi
- title: ''
  type: SpectralRules
  url: rules/apache-hudi-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-hudi-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/hudi-lakehouse-management.yaml
created: '2026-03-16'
description: Apache Hudi is a data lake platform that provides incremental data processing primitives including upserts and incremental queries. It manages storage of large analytical datasets on distributed file systems with ACID transactions, timeline-based versioning, and integrations for Spark, Flink, and Hive.
features:
- description: Atomically insert or update records in data lake tables with ACID guarantees using record keys.
  name: ACID Upserts
- description: Immutable commit timeline tracking all mutations for time travel, rollback, and incremental queries.
  name: Hudi Timeline
- description: Query only the data changed since a given commit timestamp for efficient streaming ingestion.
  name: Incremental Queries
- description: COW table type rewrites entire Parquet files on upsert for read-optimized query performance.
  name: Copy-On-Write Tables
- description: MOR table type appends delta logs for fast writes with compaction-based read optimization.
  name: Merge-On-Read Tables
- description: Built-in cleaning, compaction, clustering, and indexing services for table maintenance.
  name: Table Services
- description: Read and write Hudi tables from Apache Spark, Flink, Hive, Presto, Trino, and Athena.
  name: Multi-Engine Support
- description: Support for adding, renaming, and dropping columns with backward-compatible schema evolution.
  name: Schema Evolution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary write and read engine with Hudi DataSource and Spark SQL extensions.
  name: Apache Spark
- description: Flink sink and source connectors for streaming writes and incremental reads.
  name: Apache Flink
- description: Hive Metastore sync for making Hudi tables queryable from HiveQL.
  name: Apache Hive
- description: Native Hudi input format support for querying Hudi tables from Presto and Trino.
  name: Presto / Trino
- description: Athena supports reading Hudi COW and MOR tables stored in Amazon S3.
  name: AWS Athena
jsonld:
- class_count: 25
  name: Apache Hudi Timeline Context
  property_count: 0
  slug: apache-hudi-timeline-context
layout: provider
modified: '2026-04-19'
name: Apache Hudi
rules:
- name: Apache Hudi API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: apache-hudi-spectral-rules
skills: []
slug: apache-hudi
solutions: []
tags:
- ACID
- Apache
- Big Data
- Data Lake
- Incremental Processing
- Lakehouse
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/apis.yml
use_cases:
- description: Ingest change data capture (CDC) events from databases into data lake tables with upsert support.
  name: CDC Pipeline Ingestion
- description: Build near-real-time data lake pipelines with Spark Structured Streaming or Flink.
  name: Streaming Data Lake
- description: Manage storage costs with automated cleaning, compaction, and clustering of Hudi tables.
  name: Data Lake Maintenance
- description: Build incremental ETL pipelines that process only changed data since the last run.
  name: Incremental ETL
- description: Implement GDPR right-to-erasure by deleting records from Hudi tables with delete operations.
  name: Regulatory Data Retention
---
