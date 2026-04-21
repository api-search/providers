---
api_count: 2
apis:
- description: The Storm UI REST API provides HTTP endpoints for monitoring and managing Storm clusters, topologies, and components. It exposes cluster summary, topology listing, topology detail, component statistic
  name: Apache Storm REST API
  slug: apache-storm-rest-api
- description: The Storm Topology API provides Java and other language bindings for building real-time processing topologies composed of spouts (data sources) and bolts (processing units). It supports various stream
  name: Apache Storm Topology API
  slug: apache-storm-topology-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/storm
- title: ''
  type: Documentation
  url: https://storm.apache.org/documentation/Home.html
- title: ''
  type: Portal
  url: https://storm.apache.org/
- title: ''
  type: GettingStarted
  url: https://storm.apache.org/releases/current/Setting-up-development-environment.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/storm/releases
- title: ''
  type: Support
  url: https://storm.apache.org/contribute/People.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Storm is a free and open-source distributed real-time computation system that makes it easy to reliably process unbounded streams of data at scale. It provides a simple programming model (topologies with spouts and bolts), guaranteed message processing, horizontal scalability, and fault tolerance. Storm integrates with queuing and database technologies including Apache Kafka and Apache Cassandra and is governed by the Apache Software Foundation.
features:
- description: At-least-once processing guarantees through ack/fail tracking mechanism.
  name: Guaranteed Message Processing
- description: Horizontally scalable stream processing topologies with configurable parallelism.
  name: Scalable Topologies
- description: High-level micro-batch processing abstraction with stateful streaming and exactly-once semantics.
  name: Trident API
- description: Distributed Remote Procedure Calls for synchronous distributed computation.
  name: DRPC
- description: Tumbling and sliding window processing over bounded time or count windows.
  name: Windowing Operations
- description: Topology components written in Java, Python, Ruby, and other languages via Multilang protocol.
  name: Multi-Language Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka Spout for consuming messages from Kafka topics as Storm data sources.
  name: Apache Kafka
- description: CassandraBolt for writing processed stream data to Cassandra.
  name: Apache Cassandra
- description: HiveBolt for streaming inserts into Apache Hive tables.
  name: Apache Hive
- description: Redis integration for stateful lookups and caching in Storm bolts.
  name: Redis
- description: ElasticsearchBolt for indexing stream data into Elasticsearch.
  name: Elasticsearch
layout: provider
modified: '2026-04-19'
name: Apache Storm
skills: []
slug: apache-storm
solutions: []
tags:
- Distributed Computing
- Event Processing
- Real-Time
- Stream Processing
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-storm/refs/heads/main/apis.yml
use_cases:
- description: Continuous computation over live event streams for operational dashboards.
  name: Real-Time Analytics
- description: Real-time data transformation and enrichment pipelines.
  name: ETL Processing
- description: Online scoring of ML models against streaming feature data.
  name: Machine Learning Scoring
- description: Low-latency fraud detection rules applied to transaction streams.
  name: Fraud Detection
---
