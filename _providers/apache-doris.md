---
api_count: 1
apis:
- description: Apache Doris provides a MySQL-compatible protocol for SQL queries, a REST API for cluster management and monitoring, Stream Load HTTP API for real-time bulk data ingestion, Routine Load for continuous
  name: Apache Doris
  slug: apache-doris
common:
- title: ''
  type: Portal
  url: https://doris.apache.org/
- title: ''
  type: Documentation
  url: https://doris.apache.org/docs/dev/
- title: ''
  type: GettingStarted
  url: https://doris.apache.org/docs/dev/install/
- title: ''
  type: Blog
  url: https://doris.apache.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/doris
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-doris
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/vocabulary/apache-doris-vocabulary.yaml
created: '2026-03-16'
description: Apache Doris is a high-performance, real-time analytical database based on MPP (Massively Parallel Processing) architecture, governed by the Apache Software Foundation. It provides MySQL-protocol-compatible SQL queries, sub-second query latency on large-scale data, columnar storage with vectorized execution, real-time upsert via Stream Load and Routine Load APIs, and federated querying over data lakes (Hive, Iceberg, Hudi). It supports both shared-nothing and storage/compute-separated deployment modes.
features:
- description: Massively parallel processing with columnar storage and vectorized execution engine for high-concurrency sub-second analytical queries.
  name: MPP Columnar Analytics
- description: HTTP-based bulk data ingestion API that loads CSV, JSON, and Parquet data in real time with transactional guarantees.
  name: Stream Load API
- description: Fully MySQL-wire-protocol compatible, enabling use of standard MySQL clients, drivers, and BI tools without modification.
  name: MySQL Protocol Compatibility
- description: Query external data in Hive, Iceberg, Hudi, and Delta Lake tables without data movement using Multi-Catalog.
  name: Federated Data Lakehouse Queries
- description: Primary key based upsert model supports real-time CDC data ingestion with micro-second latency row-level updates.
  name: Real-Time Upsert (Unique Key Model)
- description: Continuous data ingestion from Apache Kafka topics with automatic offset management and exactly-once semantics.
  name: Routine Load from Kafka
- description: Hot/warm/cold data tiering with object storage (S3, HDFS) for cost-optimized storage at scale.
  name: Tiered Storage
- description: Model Context Protocol (MCP) server enabling AI agents to query Doris databases through natural language.
  name: MCP Server
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Flink Connector for reading from and writing to Doris in real-time Flink streaming pipelines.
  name: Apache Flink
- description: Official Spark Connector for batch ETL and analytics workflows using Apache Spark.
  name: Apache Spark
- description: Kafka Connector and Routine Load for continuous real-time data ingestion from Kafka topics.
  name: Apache Kafka
- description: Multi-Catalog feature enables federated queries over Iceberg, Hudi, and Hive Metastore data lakes.
  name: Apache Iceberg / Hudi / Hive
- description: Official Kubernetes Operator for automated Doris cluster lifecycle management.
  name: Kubernetes
- description: OpenTelemetry demo integration for observability and tracing in Doris deployments.
  name: OpenTelemetry
jsonld:
- class_count: 4
  name: Apache Doris Context
  property_count: 38
  slug: apache-doris-context
layout: provider
modified: '2026-04-19'
name: Apache Doris
skills: []
slug: apache-doris
solutions: []
tags:
- Analytics
- Apache
- Database
- Lakehouse
- MPP
- OLAP
- Open Source
- Real-Time
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/apis.yml
use_cases:
- description: Power business intelligence dashboards with sub-second query latency on live data updated continuously.
  name: Real-Time Dashboards and Reporting
- description: Ingest and analyze high-volume log, metric, and event data in real time using inverted indexes and full-text search.
  name: Log and Event Analytics
- description: Consolidate customer behavioral and transactional data from multiple sources for real-time segmentation and analytics.
  name: Customer Data Platform
- description: Federate queries across data lake (Hive, Iceberg) and operational databases without ETL movement.
  name: Data Lakehouse Analytics
- description: Enable data analysts to run complex exploratory SQL queries on petabyte-scale datasets with fast response times.
  name: Ad-Hoc Analytics
---
