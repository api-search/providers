---
api_count: 1
apis:
- description: Druid exposes REST APIs for Druid SQL (POST /druid/v2/sql), native JSON queries (POST /druid/v2), batch and streaming data ingestion tasks, supervisor management for Kafka/Kinesis ingestion, data segm
  name: Apache Druid REST API
  slug: apache-druid-rest-api
common:
- title: ''
  type: Portal
  url: https://druid.apache.org/
- title: ''
  type: Documentation
  url: https://druid.apache.org/docs/latest/
- title: ''
  type: GettingStarted
  url: https://druid.apache.org/docs/latest/tutorials/
- title: ''
  type: Blog
  url: https://druid.apache.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/druid
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/druid
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/vocabulary/apache-druid-vocabulary.yaml
created: '2026-03-16'
description: Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) and batch (S3, HDFS, local) data ingestion, and provides a SQL query interface plus a native JSON query API via REST. Druid is optimized for sub-second queries at petabyte scale with high concurrency.
features:
- description: Columnar storage with bitmap indexes, dictionary encoding, and pre-aggregation (rollup) enables sub-second queries on billions of events.
  name: Sub-Second OLAP Queries
- description: REST endpoint for submitting standard SQL queries with ANSI SQL support, time-based filtering, and streaming response options.
  name: Druid SQL API
- description: Druid-native query format (Timeseries, TopN, GroupBy, Scan, Search) for maximum control and performance.
  name: Native JSON Query API
- description: Real-time data ingestion from Apache Kafka and Amazon Kinesis with supervisor-managed offset tracking and exactly-once semantics.
  name: Streaming Ingestion
- description: Parallel batch indexing tasks from local files, S3, GCS, HDFS, and other external storage systems.
  name: Batch Ingestion
- description: Pre-aggregates metrics at ingestion time to reduce storage and query time, configurable per datasource.
  name: Automatic Rollup
- description: All data is partitioned by time interval (segments), enabling efficient time-range query pruning.
  name: Time-Based Partitioning
- description: Query isolation and resource management via query lanes, scheduler priorities, and row-level access control.
  name: Multi-Tenancy
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: KafkaSupervisor for real-time continuous ingestion from Kafka topics into Druid datasources.
  name: Apache Kafka
- description: KinesisSupervisor for real-time data ingestion from AWS Kinesis data streams.
  name: Amazon Kinesis
- description: Native Hadoop batch indexing task for bulk loading data from HDFS or MapReduce job outputs.
  name: Apache Hadoop / HDFS
- description: Batch and streaming ingestion from object storage (S3, GCS, Azure Blob) using index tasks.
  name: Amazon S3 / GCS
- description: Druid-Hive integration for querying Druid datasources from HiveQL and performing joins.
  name: Apache Hive
- description: Official Kubernetes operator for deploying and managing Druid clusters on Kubernetes.
  name: Kubernetes
- description: Imply provides a commercial managed Druid service with additional features and enterprise support.
  name: Imply (Commercial)
jsonld:
- class_count: 5
  name: Apache Druid Context
  property_count: 32
  slug: apache-druid-context
layout: provider
modified: '2026-04-19'
name: Apache Druid
skills: []
slug: apache-druid
solutions: []
tags:
- Analytics
- Apache
- Database
- Kafka
- OLAP
- Open Source
- Real-Time
- SQL
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml
use_cases:
- description: Analyze click streams, IoT events, application logs, and user behavior data with sub-second query latency.
  name: Real-Time Event Analytics
- description: Power interactive BI dashboards with high-concurrency low-latency queries backed by Druid's columnar engine.
  name: Business Intelligence Dashboards
- description: Ingest and analyze network flow data and security events in real time for threat detection and capacity planning.
  name: Network and Security Monitoring
- description: Process advertising impression, click, and conversion events at high volume with real-time aggregation.
  name: Ad Tech Analytics
- description: Monitor application performance metrics and operational data with drilldown and filtering capabilities.
  name: Operational Analytics
---
