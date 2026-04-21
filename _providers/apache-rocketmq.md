---
api_count: 1
apis:
- description: RocketMQ provides producer and consumer APIs with client SDKs in Java, Go, Python, C++, C#, Node.js, and Rust, along with a REST API and gRPC-based remoting for message operations, topic management, a
  name: Apache RocketMQ
  slug: apache-rocketmq
capabilities:
- description: ''
  name: Rocketmq Workflow
  slug: rocketmq-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/rocketmq
- title: ''
  type: Documentation
  url: https://rocketmq.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-rocketmq-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-rocketmq-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/rocketmq-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-rocketmq-context.jsonld
created: '2026-03-16'
description: Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal, transactional, delayed, and ordered messages.
features:
- description: Billion-level message throughput with low latency
  name: High Throughput
- description: Normal, ordered, delayed, transactional, and batch messages
  name: Multiple Message Types
- description: Server-side tag and SQL expression filtering
  name: Message Filtering
- description: Transactional messages for exactly-once delivery
  name: Exactly-Once Semantics
- description: Schedule messages with configurable delay levels
  name: Delayed Messages
- description: Automatic dead letter queue for failed messages
  name: Dead Letter Queue
- description: End-to-end message tracing for debugging and monitoring
  name: Message Tracing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: RocketMQ Spring Boot starter for easy integration
  name: Spring Boot
- description: Flink connector for stream processing from RocketMQ
  name: Apache Flink
- description: Spark Streaming connector for RocketMQ
  name: Apache Spark
- description: RocketMQ Operator for Kubernetes-native deployment
  name: Kubernetes
jsonld:
- class_count: 14
  name: Apache Rocketmq Context
  property_count: 34
  slug: apache-rocketmq-context
layout: provider
modified: '2026-04-19'
name: Apache RocketMQ
rules:
- name: Apache RocketMQ API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-rocketmq-spectral-rules
skills: []
slug: apache-rocketmq
solutions: []
tags:
- Cloud Native
- Messaging
- Message Queue
- Pub-Sub
- Streaming
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/apis.yml
use_cases:
- description: Ensure ordered processing of e-commerce order events
  name: Order Processing
- description: Decouple microservices with reliable asynchronous messaging
  name: Event-Driven Microservices
- description: Aggregate application logs from distributed services
  name: Log Aggregation
- description: Reliable transactional messaging for financial systems
  name: Financial Transactions
---
