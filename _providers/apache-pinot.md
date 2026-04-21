---
api_count: 1
apis:
- description: The Pinot API provides REST endpoints for SQL queries, schema management, table management, segment management, cluster administration, and task management, along with a JDBC driver for SQL access.
  name: Apache Pinot REST API
  slug: apache-pinot-rest-api
capabilities:
- description: Workflow for executing real-time OLAP queries, managing schemas and tables, and monitoring the Pinot cluster.
  name: Apache Pinot Analytics Workflow
  slug: pinot-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/pinot
- title: ''
  type: Documentation
  url: https://docs.pinot.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-pinot-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-pinot-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/pinot-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-pinot-context.jsonld
created: '2026-03-16'
description: Apache Pinot is a real-time distributed OLAP datastore designed to deliver scalable real-time analytics with low latency. It ingests data from batch and streaming sources and provides fast analytical queries for user-facing applications.
features:
- description: Sub-second analytical queries over real-time and historical data
  name: Real-Time OLAP
- description: Standard SQL query interface with Pinot-specific extensions
  name: SQL Support
- description: Real-time data ingestion from Kafka, Kinesis, and Pulsar
  name: Streaming Ingestion
- description: Offline data ingestion from HDFS, S3, GCS, and local files
  name: Batch Ingestion
- description: Column-oriented storage with bitmap indexing for fast queries
  name: Columnar Storage
- description: Tenant isolation for broker and server resources
  name: Multi-Tenancy
- description: Pre-aggregated star-tree index for metric rollup queries
  name: Star-Tree Index
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Real-time stream ingestion from Kafka topics
  name: Apache Kafka
- description: Flink connector for streaming data into Pinot
  name: Apache Flink
- description: Visual analytics and dashboards via SQL
  name: Apache Superset
- description: Federated query access to Pinot via Presto connector
  name: Presto/Trino
- description: Grafana data source plugin for Pinot metrics
  name: Grafana
jsonld:
- class_count: 12
  name: Apache Pinot Context
  property_count: 34
  slug: apache-pinot-context
layout: provider
modified: '2026-04-19'
name: Apache Pinot
rules:
- name: Apache Pinot API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
  slug: apache-pinot-spectral-rules
skills: []
slug: apache-pinot
solutions: []
tags:
- Analytics
- Database
- Low Latency
- OLAP
- Real-Time
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-pinot/refs/heads/main/apis.yml
use_cases:
- description: Power user-facing dashboards like LinkedIn Who Viewed Profile
  name: User-Facing Analytics
- description: Business intelligence dashboards over streaming data
  name: Real-Time Dashboards
- description: Real-time anomaly detection over metric time series
  name: Anomaly Detection
- description: Real-time experiment analysis and statistical significance
  name: A/B Testing
---
