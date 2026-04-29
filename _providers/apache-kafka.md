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
source_yaml: "aid: apache-kafka\nname: Apache Kafka\ndescription: >-\n  Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides a REST Proxy API, Kafka Connect REST API, and AsyncAPI for event streaming.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Systems\n  - Event Streaming\n  - Messaging\n  - Open Source\n  - Pub-Sub\ncreated: '2025-06-05'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-kafka:kafka-rest-proxy-api\n    name: Kafka REST Proxy API\n    description: >-\n      The Kafka REST Proxy provides a RESTful interface to a Kafka cluster for producing and consuming messages, managing\
  \ topics, partitions, consumer groups, and viewing cluster state without native Kafka clients.\n    humanURL: https://docs.confluent.io/platform/current/kafka-rest/\n    baseURL: http://localhost:8082\n    tags:\n      - Consumer Groups\n      - Proxy\n      - REST\n      - Topics\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/kafka-rest/api.html\n      - type: OpenAPI\n        url: openapi/kafka-rest-proxy.yml\n\n  - aid: apache-kafka:kafka-connect-api\n    name: Kafka Connect REST API\n    description: >-\n      Kafka Connect REST API for managing connectors, their configurations, tasks, and offsets for integrating Kafka with external data systems including databases, object stores, and search indexes.\n    humanURL: https://kafka.apache.org/documentation/#connect_rest\n    baseURL: http://localhost:8083\n    tags:\n      - Connect\n      - Connectors\n      - Integration\n    properties:\n      - type: Documentation\n        url:\
  \ https://kafka.apache.org/documentation/#connect_rest\n      - type: OpenAPI\n        url: openapi/kafka-connect.yml\n\n  - aid: apache-kafka:kafka-messaging-api\n    name: Apache Kafka Messaging API\n    description: >-\n      The core Kafka messaging protocol for producing and consuming records to/from topics using the native Kafka binary protocol, supporting exactly-once semantics, compaction, and partitioned log storage.\n    humanURL: https://kafka.apache.org/documentation/#producerapi\n    tags:\n      - Messaging\n      - Pub-Sub\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/\n      - type: AsyncAPI\n        url: asyncapi/kafka-messaging.yml\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/kafka\n  - type: Documentation\n    url: https://kafka.apache.org/documentation/\n  - type: GettingStarted\n    url: https://kafka.apache.org/quickstart\n\
  \  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Versioning\n    url: https://kafka.apache.org/downloads\n  - type: SpectralRules\n    url: rules/apache-kafka-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-kafka-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/event-streaming.yaml\n  - type: Features\n    data:\n      - name: High Throughput\n        description: Handle millions of messages per second with low latency at massive scale.\n      - name: Exactly-Once Semantics\n        description: Guarantee exactly-once message delivery with idempotent producers and transactional APIs.\n      - name: Distributed Replication\n        description: Automatic replication across brokers for fault tolerance and high availability.\n      - name: Stream Processing\n        description: Real-time stream processing via Kafka Streams library and KSQL.\n      - name: Connector Ecosystem\n        description: 200+ pre-built\
  \ Kafka Connect connectors for databases, clouds, and SaaS.\n      - name: Log Compaction\n        description: Retain the latest value for each key with topic log compaction.\n      - name: Consumer Groups\n        description: Horizontally scalable consumers with automatic partition rebalancing.\n  - type: UseCases\n    data:\n      - name: Event-Driven Architecture\n        description: Build event-driven microservices with reliable message delivery.\n      - name: Data Pipeline\n        description: Move data between systems at scale with exactly-once delivery guarantees.\n      - name: Real-Time Analytics\n        description: Process and analyze event streams in real time with Kafka Streams.\n      - name: Log Aggregation\n        description: Centralize application and infrastructure logs for analysis and alerting.\n      - name: CDC (Change Data Capture)\n        description: Capture database changes and stream them to data warehouses and caches.\n  - type: Integrations\n    data:\n\
  \      - name: Apache Spark\n        description: Spark Structured Streaming integration for batch and streaming analytics.\n      - name: Apache Flink\n        description: Native Flink Kafka connector for low-latency stream processing.\n      - name: Debezium\n        description: CDC platform using Kafka Connect to capture database change events.\n      - name: Elasticsearch\n        description: Kafka Connect Elasticsearch sink for indexing event data.\n      - name: Amazon S3\n        description: Kafka Connect S3 sink for archiving event streams to object storage.\n      - name: Apache Hadoop\n        description: HDFS sink connector for streaming data into Hadoop data lake.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/apis.yml
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
