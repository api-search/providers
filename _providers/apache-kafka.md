---
api_count: 3
apis:
- description: 'The Kafka REST Proxy provides a RESTful interface to a Kafka cluster for producing and consuming messages, managing topics, partitions, consumer groups, and viewing cluster state without native Kafka '
  name: Kafka REST Proxy API
  slug: kafka-rest-proxy-api
- description: Kafka Connect REST API for managing connectors, their configurations, tasks, and offsets for integrating Kafka with external data systems including databases, object stores, and search indexes.
  name: Kafka Connect REST API
  slug: kafka-connect-api
- description: The core Kafka messaging protocol for producing and consuming records to/from topics using the native Kafka binary protocol, supporting exactly-once semantics, compaction, and partitioned log storage.
  name: Apache Kafka Messaging API
  slug: kafka-messaging-api
asyncapis:
- description: 'Apache Kafka is a distributed event streaming platform capable of handling trillions of events a day. This spec describes the core messaging protocol for producing and consuming records to/from Kafka '
  name: Apache Kafka Messaging API
  slug: kafka-messaging
capabilities:
- description: Workflow capability for data engineers and platform architects to manage Kafka topics, produce and consume messages, and manage connectors via Kafka REST Proxy and Connect APIs.
  name: Apache Kafka Event Streaming
  slug: event-streaming
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/kafka
- title: ''
  type: Documentation
  url: https://kafka.apache.org/documentation/
- title: ''
  type: GettingStarted
  url: https://kafka.apache.org/quickstart
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://kafka.apache.org/downloads
- title: ''
  type: SpectralRules
  url: rules/apache-kafka-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-kafka-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/event-streaming.yaml
created: '2025-06-05'
description: Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides a REST Proxy API, Kafka Connect REST API, and AsyncAPI for event streaming.
features:
- description: Handle millions of messages per second with low latency at massive scale.
  name: High Throughput
- description: Guarantee exactly-once message delivery with idempotent producers and transactional APIs.
  name: Exactly-Once Semantics
- description: Automatic replication across brokers for fault tolerance and high availability.
  name: Distributed Replication
- description: Real-time stream processing via Kafka Streams library and KSQL.
  name: Stream Processing
- description: 200+ pre-built Kafka Connect connectors for databases, clouds, and SaaS.
  name: Connector Ecosystem
- description: Retain the latest value for each key with topic log compaction.
  name: Log Compaction
- description: Horizontally scalable consumers with automatic partition rebalancing.
  name: Consumer Groups
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spark Structured Streaming integration for batch and streaming analytics.
  name: Apache Spark
- description: Native Flink Kafka connector for low-latency stream processing.
  name: Apache Flink
- description: CDC platform using Kafka Connect to capture database change events.
  name: Debezium
- description: Kafka Connect Elasticsearch sink for indexing event data.
  name: Elasticsearch
- description: Kafka Connect S3 sink for archiving event streams to object storage.
  name: Amazon S3
- description: HDFS sink connector for streaming data into Hadoop data lake.
  name: Apache Hadoop
jsonld:
- class_count: 2
  name: Apache Kafka Kafka Connect Config Context
  property_count: 3
  slug: apache-kafka-kafka-connect-config-context
- class_count: 5
  name: Apache Kafka Kafka Connect Connector Context
  property_count: 7
  slug: apache-kafka-kafka-connect-connector-context
- class_count: 2
  name: Apache Kafka Kafka Connect Create Context
  property_count: 1
  slug: apache-kafka-kafka-connect-create-context
- class_count: 2
  name: Apache Kafka Kafka Connect Task Context
  property_count: 7
  slug: apache-kafka-kafka-connect-task-context
- class_count: 10
  name: Apache Kafka Kafka Rest Proxy Context
  property_count: 41
  slug: apache-kafka-kafka-rest-proxy-context
layout: provider
modified: '2026-04-19'
name: Apache Kafka
rules:
- name: Apache Kafka API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 3
  slug: apache-kafka-spectral-rules
skills: []
slug: apache-kafka
solutions: []
tags:
- Distributed Systems
- Event Streaming
- Messaging
- Open Source
- Pub-Sub
url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml
use_cases:
- description: Build event-driven microservices with reliable message delivery.
  name: Event-Driven Architecture
- description: Move data between systems at scale with exactly-once delivery guarantees.
  name: Data Pipeline
- description: Process and analyze event streams in real time with Kafka Streams.
  name: Real-Time Analytics
- description: Centralize application and infrastructure logs for analysis and alerting.
  name: Log Aggregation
- description: Capture database changes and stream them to data warehouses and caches.
  name: CDC (Change Data Capture)
---
