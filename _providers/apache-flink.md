---
api_count: 2
apis:
- description: The REST API provides programmatic access to monitor and control Flink jobs and clusters. It supports job submission, cluster management, metrics retrieval, checkpoint management, and TaskManager admi
  name: Apache Flink REST API
  slug: apache-flink-rest-api
- description: Monitoring REST API for accessing job metrics, checkpoints, and cluster statistics for Apache Flink deployments.
  name: Apache Flink Monitoring API
  slug: apache-flink-monitoring
capabilities:
- description: Unified capability for managing and monitoring Apache Flink streaming and batch jobs — submitting, tracking, monitoring metrics, and managing the cluster. Designed for data engineers and platform oper
  name: Apache Flink Job Management
  slug: flink-job-management
common:
- title: ''
  type: GettingStarted
  url: https://nightlies.apache.org/flink/flink-docs-stable/docs/try-flink/local_installation/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/flink
- title: ''
  type: Blog
  url: https://flink.apache.org/blog/
- title: ''
  type: Support
  url: https://flink.apache.org/community.html
- title: ''
  type: Training
  url: https://nightlies.apache.org/flink/flink-docs-stable/docs/learn-flink/overview/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-flink
- title: ''
  type: X
  url: https://twitter.com/apacheflink
- title: ''
  type: SpectralRules
  url: rules/apache-flink-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-flink-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/flink-job-management.yaml
created: '2024-01-01'
description: Apache Flink is a framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It provides a REST API for job management, cluster operations, metrics collection, and checkpoint management for real-time streaming and batch processing workloads.
features:
- description: Single engine for both unbounded stream processing and bounded batch workloads with a unified API.
  name: Unified Stream and Batch Processing
- description: Rich stateful processing with managed state backends (RocksDB, heap), exactly-once guarantees, and state versioning.
  name: Stateful Computations
- description: End-to-end exactly-once processing guarantees with distributed snapshots and transactional sinks.
  name: Exactly-Once Semantics
- description: Native event-time support with watermarks for out-of-order event handling in streaming workloads.
  name: Event Time Processing
- description: Automatic fault-tolerance via checkpointing and manual savepoints for job migration and upgrades.
  name: Checkpointing and Savepoints
- description: JobManager HA via ZooKeeper or Kubernetes for zero-downtime cluster operations.
  name: High Availability
- description: Horizontally scalable TaskManagers with fine-grained resource management and dynamic slot allocation.
  name: Scalable Architecture
- description: Comprehensive REST API for job submission, monitoring, metrics collection, and cluster administration.
  name: REST API Management
- description: Declarative SQL and Table API for streaming analytics with connector ecosystem support.
  name: SQL and Table API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka source and sink connectors for high-throughput event streaming ingestion and output.
  name: Apache Kafka
- description: HDFS integration for batch data reading and writing in distributed storage.
  name: Apache Hadoop / HDFS
- description: Hive catalog integration and batch SQL queries over Hive tables.
  name: Apache Hive
- description: Native Kubernetes deployment with FlinkDeployment CRD and the Flink Kubernetes Operator.
  name: Kubernetes
- description: Iceberg table format integration for lakehouse workloads with ACID guarantees.
  name: Apache Iceberg
- description: Elasticsearch sink connector for real-time search index updates from Flink jobs.
  name: Elasticsearch
- description: Kinesis source and sink connectors for AWS-native streaming pipelines.
  name: Amazon Kinesis
jsonld:
- class_count: 52
  name: Apache Flink Rest Context
  property_count: 130
  slug: apache-flink-rest-context
layout: provider
modified: '2026-04-19'
name: Apache Flink
rules:
- name: Apache Flink API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 5
  slug: apache-flink-spectral-rules
skills: []
slug: apache-flink
solutions: []
source_yaml: "aid: apache-flink\nname: Apache Flink\ndescription: >-\n  Apache Flink is a framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It provides a REST API for job management, cluster operations, metrics collection, and checkpoint management for real-time streaming and batch processing workloads.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Batch Processing\n  - Big Data\n  - Open Source\n  - Real-Time Analytics\n  - Stateful Computing\n  - Stream Processing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apache-flink:apache-flink-rest-api\n    name: Apache Flink REST API\n    description: >-\n      The REST API provides programmatic access to monitor and control Flink jobs and clusters. It supports job submission,\
  \ cluster management, metrics retrieval, checkpoint management, and TaskManager administration.\n    humanURL: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/\n    baseURL: http://localhost:8081\n    tags:\n      - Big Data\n      - Distributed Computing\n      - Job Management\n      - Real-Time Processing\n      - REST API\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/\n      - type: OpenAPI\n        url: openapi/apache-flink-rest-openapi-original.yml\n      - type: JSONSchema\n        url: json-schema/flink-rest-job-details-info-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-flink-rest-context.jsonld\n\n  - aid: apache-flink:apache-flink-monitoring\n    name: Apache Flink Monitoring API\n    description: >-\n      Monitoring REST API for accessing job metrics, checkpoints, and cluster statistics for Apache Flink deployments.\n    humanURL:\
  \ https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/monitoring/\n    baseURL: http://localhost:8081\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/monitoring/\n      - type: Documentation\n        url: https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/metrics/\n        title: Metrics Reference\n\ncommon:\n  - type: GettingStarted\n    url: https://nightlies.apache.org/flink/flink-docs-stable/docs/try-flink/local_installation/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/flink\n  - type: Blog\n    url: https://flink.apache.org/blog/\n  - type: Support\n    url: https://flink.apache.org/community.html\n  - type: Training\n    url: https://nightlies.apache.org/flink/flink-docs-stable/docs/learn-flink/overview/\n  - type: StackOverflow\n \
  \   url: https://stackoverflow.com/questions/tagged/apache-flink\n  - type: X\n    url: https://twitter.com/apacheflink\n  - type: SpectralRules\n    url: rules/apache-flink-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-flink-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/flink-job-management.yaml\n  - type: Features\n    data:\n      - name: Unified Stream and Batch Processing\n        description: Single engine for both unbounded stream processing and bounded batch workloads with a unified API.\n      - name: Stateful Computations\n        description: Rich stateful processing with managed state backends (RocksDB, heap), exactly-once guarantees, and state versioning.\n      - name: Exactly-Once Semantics\n        description: End-to-end exactly-once processing guarantees with distributed snapshots and transactional sinks.\n      - name: Event Time Processing\n        description: Native event-time support with watermarks for out-of-order event\
  \ handling in streaming workloads.\n      - name: Checkpointing and Savepoints\n        description: Automatic fault-tolerance via checkpointing and manual savepoints for job migration and upgrades.\n      - name: High Availability\n        description: JobManager HA via ZooKeeper or Kubernetes for zero-downtime cluster operations.\n      - name: Scalable Architecture\n        description: Horizontally scalable TaskManagers with fine-grained resource management and dynamic slot allocation.\n      - name: REST API Management\n        description: Comprehensive REST API for job submission, monitoring, metrics collection, and cluster administration.\n      - name: SQL and Table API\n        description: Declarative SQL and Table API for streaming analytics with connector ecosystem support.\n  - type: UseCases\n    data:\n      - name: Real-Time Analytics\n        description: Process and analyze event streams in real time for dashboards, alerts, and operational intelligence.\n      - name:\
  \ ETL Pipelines\n        description: Build scalable ETL pipelines for data lake ingestion, transformation, and enrichment.\n      - name: Fraud Detection\n        description: Detect fraudulent transactions in real time using stateful pattern matching over event streams.\n      - name: IoT Data Processing\n        description: Process high-volume IoT device telemetry with stateful aggregations and time-window computations.\n      - name: Machine Learning Inference\n        description: Serve ML model predictions at scale with streaming feature computation and online inference.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Kafka source and sink connectors for high-throughput event streaming ingestion and output.\n      - name: Apache Hadoop / HDFS\n        description: HDFS integration for batch data reading and writing in distributed storage.\n      - name: Apache Hive\n        description: Hive catalog integration and batch SQL queries over Hive\
  \ tables.\n      - name: Kubernetes\n        description: Native Kubernetes deployment with FlinkDeployment CRD and the Flink Kubernetes Operator.\n      - name: Apache Iceberg\n        description: Iceberg table format integration for lakehouse workloads with ACID guarantees.\n      - name: Elasticsearch\n        description: Elasticsearch sink connector for real-time search index updates from Flink jobs.\n      - name: Amazon Kinesis\n        description: Kinesis source and sink connectors for AWS-native streaming pipelines.\nmaintainers:\n  - FN: Apache Software Foundation\n    email: user@flink.apache.org\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/apis.yml
tags:
- Apache
- Batch Processing
- Big Data
- Open Source
- Real-Time Analytics
- Stateful Computing
- Stream Processing
url: https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/apis.yml
use_cases:
- description: Process and analyze event streams in real time for dashboards, alerts, and operational intelligence.
  name: Real-Time Analytics
- description: Build scalable ETL pipelines for data lake ingestion, transformation, and enrichment.
  name: ETL Pipelines
- description: Detect fraudulent transactions in real time using stateful pattern matching over event streams.
  name: Fraud Detection
- description: Process high-volume IoT device telemetry with stateful aggregations and time-window computations.
  name: IoT Data Processing
- description: Serve ML model predictions at scale with streaming feature computation and online inference.
  name: Machine Learning Inference
---
