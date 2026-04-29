---
api_count: 1
api_specs:
- filename: apache-rocketmq-rest-api.yaml
  format: yaml
  label: Apache RocketMQ
  slug: apache-rocketmq
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/openapi/apache-rocketmq-rest-api.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-rocketmq\nname: Apache RocketMQ\ndescription: >-\n  Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal,\n  transactional, delayed, and ordered messages.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud Native\n- Messaging\n- Message Queue\n- Pub-Sub\n- Streaming\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-rocketmq:apache-rocketmq\n  name: Apache RocketMQ\n  description: >-\n    RocketMQ provides producer and consumer APIs with client SDKs in Java, Go, Python, C++, C#, Node.js, and Rust, along with a REST API and gRPC-based remoting for\
  \ message operations, topic management,\n    and cluster administration.\n  humanURL: https://rocketmq.apache.org/docs/\n  tags:\n  - Cloud Native\n  - Messaging\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://rocketmq.apache.org/docs/\n  - type: OpenAPI\n    url: openapi/apache-rocketmq-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/rocketmq\n- type: Documentation\n  url: https://rocketmq.apache.org/\n- type: SpectralRules\n  url: rules/apache-rocketmq-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-rocketmq-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/rocketmq-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-rocketmq-context.jsonld\n- type: Features\n  data:\n  - name: High Throughput\n    description: Billion-level message throughput with low latency\n  - name: Multiple Message Types\n    description:\
  \ Normal, ordered, delayed, transactional, and batch messages\n  - name: Message Filtering\n    description: Server-side tag and SQL expression filtering\n  - name: Exactly-Once Semantics\n    description: Transactional messages for exactly-once delivery\n  - name: Delayed Messages\n    description: Schedule messages with configurable delay levels\n  - name: Dead Letter Queue\n    description: Automatic dead letter queue for failed messages\n  - name: Message Tracing\n    description: End-to-end message tracing for debugging and monitoring\n- type: UseCases\n  data:\n  - name: Order Processing\n    description: Ensure ordered processing of e-commerce order events\n  - name: Event-Driven Microservices\n    description: Decouple microservices with reliable asynchronous messaging\n  - name: Log Aggregation\n    description: Aggregate application logs from distributed services\n  - name: Financial Transactions\n    description: Reliable transactional messaging for financial systems\n- type:\
  \ Integrations\n  data:\n  - name: Spring Boot\n    description: RocketMQ Spring Boot starter for easy integration\n  - name: Apache Flink\n    description: Flink connector for stream processing from RocketMQ\n  - name: Apache Spark\n    description: Spark Streaming connector for RocketMQ\n  - name: Kubernetes\n    description: RocketMQ Operator for Kubernetes-native deployment\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/apis.yml
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
