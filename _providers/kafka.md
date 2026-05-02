---
api_count: 5
apis:
- description: API for publishing streams of records to Kafka topics.
  name: Kafka Producer API
  slug: producer-api
- description: API for subscribing to topics and processing streams of records.
  name: Kafka Consumer API
  slug: consumer-api
- description: API for building stream processing applications and microservices on top of Kafka.
  name: Kafka Streams API
  slug: streams-api
- description: REST API for integrating Kafka with external systems through connectors.
  name: Kafka Connect REST API
  slug: connect-api
- description: API for managing and inspecting topics, brokers, configurations, and ACLs.
  name: Kafka Admin API
  slug: admin-api
common:
- title: ''
  type: Website
  url: https://kafka.apache.org
- title: ''
  type: Documentation
  url: https://kafka.apache.org/documentation/
- title: ''
  type: Getting Started
  url: https://kafka.apache.org/quickstart
- title: ''
  type: GitHub Organization
  url: https://github.com/apache/kafka
- title: ''
  type: Blog
  url: https://kafka.apache.org/blog
- title: ''
  type: Community
  url: https://kafka.apache.org/contact
created: '2024-01-01'
description: Apache Kafka is a distributed event streaming platform for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides high-throughput, fault-tolerant, publish-subscribe messaging.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Apache Kafka
skills: []
slug: kafka
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kafka\nname: Apache Kafka\ndescription: >-\n  Apache Kafka is a distributed event streaming platform for high-performance\n  data pipelines, streaming analytics, data integration, and mission-critical\n  applications. It provides high-throughput, fault-tolerant, publish-subscribe\n  messaging.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Systems\n  - Event Driven\n  - Messaging\n  - Real-Time\n  - Streaming\nurl: https://raw.githubusercontent.com/api-evangelist/kafka/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kafka:producer-api\n    name: Kafka Producer API\n    description: API for publishing streams of records to Kafka topics.\n    humanURL: https://kafka.apache.org/documentation/#producerapi\n    tags:\n      - Messaging\n      - Producer\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/#producerapi\n\
  \  - aid: kafka:consumer-api\n    name: Kafka Consumer API\n    description: API for subscribing to topics and processing streams of records.\n    humanURL: https://kafka.apache.org/documentation/#consumerapi\n    tags:\n      - Consumer\n      - Messaging\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/#consumerapi\n  - aid: kafka:streams-api\n    name: Kafka Streams API\n    description: >-\n      API for building stream processing applications and microservices on top\n      of Kafka.\n    humanURL: https://kafka.apache.org/documentation/streams/\n    tags:\n      - Processing\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/streams/\n  - aid: kafka:connect-api\n    name: Kafka Connect REST API\n    description: >-\n      REST API for integrating Kafka with external systems through connectors.\n    humanURL: https://kafka.apache.org/documentation/#connect\n\
  \    baseURL: http://localhost:8083\n    tags:\n      - Connectors\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/#connect_rest\n  - aid: kafka:admin-api\n    name: Kafka Admin API\n    description: >-\n      API for managing and inspecting topics, brokers, configurations, and ACLs.\n    humanURL: https://kafka.apache.org/documentation/#adminapi\n    tags:\n      - Administration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/#adminapi\ncommon:\n  - type: Website\n    url: https://kafka.apache.org\n  - type: Documentation\n    url: https://kafka.apache.org/documentation/\n  - type: Getting Started\n    url: https://kafka.apache.org/quickstart\n  - type: GitHub Organization\n    url: https://github.com/apache/kafka\n  - type: Blog\n    url: https://kafka.apache.org/blog\n  - type: Community\n    url: https://kafka.apache.org/contact\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kafka/refs/heads/main/apis.yml
tags:
- Distributed Systems
- Event Driven
- Messaging
- Real-Time
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/kafka/refs/heads/main/apis.yml
use_cases: []
---
