---
api_count: 2
apis:
- description: The Pulsar Admin API provides REST endpoints for managing tenants, namespaces, topics, subscriptions, functions, connectors, and cluster configuration.
  name: Apache Pulsar Admin REST API
  slug: apache-pulsar-admin-rest-api
- description: Pulsar messaging protocol for producing and consuming messages on topics, with support for multiple subscription types (Exclusive, Shared, Failover, Key_Shared), schema enforcement, and both persisten
  name: Apache Pulsar Messaging API
  slug: apache-pulsar-messaging-api
asyncapis:
- description: 'Apache Pulsar is a cloud-native, multi-tenant, high-performance messaging and streaming platform. This spec describes the messaging patterns for producing and consuming messages on Pulsar topics with '
  name: Apache Pulsar Messaging API
  slug: pulsar-messaging
capabilities:
- description: ''
  name: Pulsar Workflow
  slug: pulsar-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/pulsar
- title: ''
  type: Documentation
  url: https://pulsar.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-pulsar-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-pulsar-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/pulsar-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-pulsar-context.jsonld
created: '2026-03-16'
description: Apache Pulsar is a cloud-native, distributed messaging and streaming platform that provides server-to-server messaging with multi-tenancy, high performance, and geo-replication. It combines messaging and stream processing in a single platform.
features:
- description: Native multi-tenancy with tenant and namespace isolation
  name: Multi-Tenancy
- description: Durable message storage with Apache BookKeeper
  name: Persistent Messaging
- description: Built-in geo-replication across data centers and clouds
  name: Geo-Replication
- description: Lightweight serverless compute natively integrated with messaging
  name: Pulsar Functions
- description: Offload old data to object storage (S3, GCS) for cost efficiency
  name: Tiered Storage
- description: Built-in schema registry for producers and consumers
  name: Schema Registry
- description: Exclusive, Shared, Failover, and Key_Shared subscription modes
  name: Multiple Subscription Types
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Pulsar connector for Flink stream processing
  name: Apache Flink
- description: Spark Streaming integration via Pulsar connector
  name: Apache Spark
- description: Kafka-compatible protocol support for migration
  name: Apache Kafka
- description: Native Kubernetes deployment via Helm charts
  name: Kubernetes
- description: Built-in metrics exposed to Prometheus and Grafana
  name: Grafana
jsonld:
- class_count: 7
  name: Apache Pulsar Context
  property_count: 51
  slug: apache-pulsar-context
layout: provider
modified: '2026-04-19'
name: Apache Pulsar
skills: []
slug: apache-pulsar
solutions: []
tags:
- Cloud Native
- Messaging
- Multi-Tenant
- Pub-Sub
- Streaming
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/apis.yml
use_cases:
- description: Stream events between microservices with guaranteed delivery
  name: Real-Time Event Streaming
- description: Use Shared subscription as a traditional message queue
  name: Message Queue
- description: Store and replay event streams for event-driven architectures
  name: Event Sourcing
- description: Ingest high-volume IoT telemetry into Pulsar topics
  name: IoT Data Ingestion
---
