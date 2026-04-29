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
source_yaml: "aid: apache-storm\nname: Apache Storm\ndescription: >-\n  Apache Storm is a free and open-source distributed real-time computation system that makes it\n  easy to reliably process unbounded streams of data at scale. It provides a simple programming\n  model (topologies with spouts and bolts), guaranteed message processing, horizontal scalability,\n  and fault tolerance. Storm integrates with queuing and database technologies including Apache\n  Kafka and Apache Cassandra and is governed by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Computing\n  - Event Processing\n  - Real-Time\n  - Stream Processing\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-storm/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-storm:apache-storm-rest-api\n\
  \    name: Apache Storm REST API\n    description: >-\n      The Storm UI REST API provides HTTP endpoints for monitoring and managing Storm clusters,\n      topologies, and components. It exposes cluster summary, topology listing, topology detail,\n      component statistics, supervisor info, nimbus info, and topology actions (activate, deactivate,\n      rebalance, kill). The API serves the Storm UI dashboard and can be used programmatically.\n    humanURL: https://storm.apache.org/releases/current/STORM-UI-REST-API.html\n    tags:\n      - REST\n      - Monitoring\n      - Cluster Management\n      - Topologies\n    properties:\n      - type: Documentation\n        url: https://storm.apache.org/releases/current/STORM-UI-REST-API.html\n  - aid: apache-storm:apache-storm-topology-api\n    name: Apache Storm Topology API\n    description: >-\n      The Storm Topology API provides Java and other language bindings for building real-time\n      processing topologies composed of spouts (data\
  \ sources) and bolts (processing units). It\n      supports various stream groupings, windowing operations, Trident micro-batch processing,\n      and DRPC (Distributed Remote Procedure Calls) for synchronous request/response patterns.\n    humanURL: https://storm.apache.org/documentation/Tutorial.html\n    tags:\n      - Java\n      - Topology\n      - Streaming\n      - Processing\n    properties:\n      - type: Documentation\n        url: https://storm.apache.org/documentation/Tutorial.html\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.storm\n        title: Maven Java SDK\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/storm\n  - type: Documentation\n    url: https://storm.apache.org/documentation/Home.html\n  - type: Portal\n    url: https://storm.apache.org/\n  - type: GettingStarted\n    url: https://storm.apache.org/releases/current/Setting-up-development-environment.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/storm/releases\n\
  \  - type: Support\n    url: https://storm.apache.org/contribute/People.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Guaranteed Message Processing\n        description: At-least-once processing guarantees through ack/fail tracking mechanism.\n      - name: Scalable Topologies\n        description: Horizontally scalable stream processing topologies with configurable parallelism.\n      - name: Trident API\n        description: High-level micro-batch processing abstraction with stateful streaming and exactly-once semantics.\n      - name: DRPC\n        description: Distributed Remote Procedure Calls for synchronous distributed computation.\n      - name: Windowing Operations\n        description: Tumbling and sliding window processing over bounded time or count windows.\n      - name: Multi-Language Support\n        description: Topology components written in Java, Python, Ruby, and other languages via Multilang protocol.\n\
  \  - type: UseCases\n    data:\n      - name: Real-Time Analytics\n        description: Continuous computation over live event streams for operational dashboards.\n      - name: ETL Processing\n        description: Real-time data transformation and enrichment pipelines.\n      - name: Machine Learning Scoring\n        description: Online scoring of ML models against streaming feature data.\n      - name: Fraud Detection\n        description: Low-latency fraud detection rules applied to transaction streams.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Kafka Spout for consuming messages from Kafka topics as Storm data sources.\n      - name: Apache Cassandra\n        description: CassandraBolt for writing processed stream data to Cassandra.\n      - name: Apache Hive\n        description: HiveBolt for streaming inserts into Apache Hive tables.\n      - name: Redis\n        description: Redis integration for stateful lookups and caching in Storm bolts.\n\
  \      - name: Elasticsearch\n        description: ElasticsearchBolt for indexing stream data into Elasticsearch.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-storm/refs/heads/main/apis.yml
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
