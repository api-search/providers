---
api_count: 1
apis:
- description: SeaTunnel provides a REST API for job management and monitoring, a Connector API for building custom data sources and sinks, and a Transform API for data transformation, supporting over 100 built-in c
  name: Apache SeaTunnel REST API
  slug: apache-seatunnel-rest-api
capabilities:
- description: ''
  name: Seatunnel Workflow
  slug: seatunnel-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/seatunnel
- title: ''
  type: Documentation
  url: https://seatunnel.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-seatunnel-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-seatunnel-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/seatunnel-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-seatunnel-context.jsonld
created: '2026-03-16'
description: Apache SeaTunnel is a high-performance, distributed data integration platform that supports real-time and batch data synchronization. It provides a connector API with support for over 100 data sources and sinks.
features:
- description: Over 200 built-in connectors for databases, warehouses, and file systems
  name: 200+ Connectors
- description: Unified API for both batch ETL and real-time streaming jobs
  name: Batch and Streaming
- description: Automatic schema detection and evolution support
  name: Schema Evolution
- description: Zeta execution engine with no external dependencies
  name: Distributed Execution
- description: Change Data Capture for real-time database synchronization
  name: CDC Support
- description: Built-in SQL and custom transform functions
  name: Transform Layer
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka source and sink connector for streaming pipelines
  name: Apache Kafka
- description: Run SeaTunnel jobs on Flink execution engine
  name: Apache Flink
- description: Run SeaTunnel jobs on Spark execution engine
  name: Apache Spark
- description: High-performance ClickHouse sink connector
  name: ClickHouse
- description: Apache Doris connector for analytical workloads
  name: Doris
jsonld:
- class_count: 10
  name: Apache Seatunnel Context
  property_count: 32
  slug: apache-seatunnel-context
layout: provider
modified: '2026-04-19'
name: Apache SeaTunnel
rules:
- name: Apache SeaTunnel API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-seatunnel-spectral-rules
skills: []
slug: apache-seatunnel
solutions: []
tags:
- Data Integration
- ETL
- ELT
- Batch
- Streaming
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml
use_cases:
- description: Migrate data between databases with schema mapping
  name: Database Migration
- description: Load and sync data into data warehouses
  name: Data Warehouse Loading
- description: CDC-based real-time sync between source and target systems
  name: Real-Time Synchronization
- description: Ingest data from multiple sources into a data lake
  name: Data Lake Ingestion
---
