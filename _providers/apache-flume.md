---
api_count: 2
api_specs:
- filename: apache-flume-monitoring-openapi.yml
  format: yaml
  label: Apache Flume Monitoring API
  slug: apache-flume-monitoring-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/openapi/apache-flume-monitoring-openapi.yml
apis:
- description: REST API for monitoring Apache Flume agents, retrieving component metrics for sources, channels, and sinks, and accessing agent health information.
  name: Apache Flume Monitoring API
  slug: apache-flume-monitoring-api
- description: Java API for building custom Flume sources, channels, sinks, and interceptors. Provides interfaces for developing pluggable data ingestion components.
  name: Apache Flume Java API
  slug: apache-flume-java-api
capabilities:
- description: Capability for monitoring Apache Flume log collection agents — tracking source throughput, channel fill levels, and sink drain rates. Designed for data engineers and platform operators managing log ag
  name: Apache Flume Log Collection
  slug: flume-log-collection
common:
- title: ''
  type: Documentation
  url: https://flume.apache.org/documentation.html
- title: ''
  type: GettingStarted
  url: https://flume.apache.org/FlumeUserGuide.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/flume
- title: ''
  type: SpectralRules
  url: rules/apache-flume-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-flume-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/flume-log-collection.yaml
created: '2026-03-16'
description: Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log and event data. It provides a simple and flexible architecture based on streaming data flows with pluggable sources, channels, and sinks, plus a REST monitoring API for agent metrics.
features:
- description: Extensible source architecture supporting Avro, Thrift, Exec, Taildir, Kafka, HTTP, Syslog, and custom sources.
  name: Pluggable Sources
- description: Multiple channel implementations including memory, file-backed, and Kafka-backed channels for different durability requirements.
  name: Durable Channels
- description: Write events to HDFS, HBase, Solr, Elasticsearch, Kafka, and custom sink destinations.
  name: Multi-Destination Sinks
- description: Aggregate events from multiple agent sources into a single destination for centralized log collection.
  name: Fan-In Consolidation
- description: Route events from a single source to multiple channel/sink combinations for parallel processing.
  name: Fan-Out Distribution
- description: Event transformation interceptors for filtering, enrichment, and routing based on event content.
  name: Interceptors
- description: TLS encryption support across Avro, Thrift, Kafka, HTTP, and Syslog components.
  name: SSL/TLS Security
- description: HTTP monitoring endpoint exposing source, channel, and sink metrics for agent health monitoring.
  name: Monitoring REST API
- description: Chain multiple Flume agents via Avro/Thrift RPC for tiered log aggregation architectures.
  name: Multi-Hop Flows
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka source and channel for consuming events, and Kafka sink for writing events to topics.
  name: Apache Kafka
- description: Primary sink for writing log data to Hadoop Distributed File System for batch analytics.
  name: Apache HDFS
- description: HBase sink for writing events directly to HBase tables for random-access analytics.
  name: Apache HBase
- description: Solr sink for indexing log events for full-text search capabilities.
  name: Apache Solr
- description: Elasticsearch sink for indexing and searching aggregated log data.
  name: Elasticsearch
jsonld:
- class_count: 2
  name: Apache Flume Monitoring Context
  property_count: 18
  slug: apache-flume-monitoring-context
layout: provider
modified: '2026-04-19'
name: Apache Flume
rules:
- name: Apache Flume API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 2
  slug: apache-flume-spectral-rules
skills: []
slug: apache-flume
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-flume\nname: Apache Flume\ndescription: >-\n  Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log and event data. It provides a simple and flexible architecture based on streaming data flows with pluggable sources, channels, and sinks, plus a REST monitoring API for agent metrics.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Data Collection\n  - ETL\n  - Log Aggregation\n  - Open Source\n  - Streaming\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-flume:apache-flume-monitoring-api\n    name: Apache Flume Monitoring API\n    description: >-\n      REST API for monitoring Apache Flume agents, retrieving component metrics\
  \ for sources, channels, and sinks, and accessing agent health information.\n    humanURL: https://flume.apache.org/FlumeUserGuide.html\n    baseURL: http://localhost:41414\n    tags:\n      - Monitoring\n      - Metrics\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://flume.apache.org/FlumeUserGuide.html\n      - type: OpenAPI\n        url: openapi/apache-flume-monitoring-openapi.yml\n      - type: JSONSchema\n        url: json-schema/flume-monitoring-agent-metrics-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-flume-monitoring-context.jsonld\n\n  - aid: apache-flume:apache-flume-java-api\n    name: Apache Flume Java API\n    description: >-\n      Java API for building custom Flume sources, channels, sinks, and interceptors. Provides interfaces for developing pluggable data ingestion components.\n    humanURL: https://flume.apache.org/FlumeDeveloperGuide.html\n    tags:\n      - Java\n      - SDK\n      - Extension\n    properties:\n\
  \      - type: Documentation\n        url: https://flume.apache.org/FlumeDeveloperGuide.html\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.flume/flume-ng-core\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://flume.apache.org/documentation.html\n  - type: GettingStarted\n    url: https://flume.apache.org/FlumeUserGuide.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/flume\n  - type: SpectralRules\n    url: rules/apache-flume-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-flume-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/flume-log-collection.yaml\n  - type: Features\n    data:\n      - name: Pluggable Sources\n        description: Extensible source architecture supporting Avro, Thrift, Exec, Taildir, Kafka, HTTP, Syslog, and custom sources.\n      - name: Durable Channels\n      \
  \  description: Multiple channel implementations including memory, file-backed, and Kafka-backed channels for different durability requirements.\n      - name: Multi-Destination Sinks\n        description: Write events to HDFS, HBase, Solr, Elasticsearch, Kafka, and custom sink destinations.\n      - name: Fan-In Consolidation\n        description: Aggregate events from multiple agent sources into a single destination for centralized log collection.\n      - name: Fan-Out Distribution\n        description: Route events from a single source to multiple channel/sink combinations for parallel processing.\n      - name: Interceptors\n        description: Event transformation interceptors for filtering, enrichment, and routing based on event content.\n      - name: SSL/TLS Security\n        description: TLS encryption support across Avro, Thrift, Kafka, HTTP, and Syslog components.\n      - name: Monitoring REST API\n        description: HTTP monitoring endpoint exposing source, channel, and\
  \ sink metrics for agent health monitoring.\n      - name: Multi-Hop Flows\n        description: Chain multiple Flume agents via Avro/Thrift RPC for tiered log aggregation architectures.\n  - type: UseCases\n    data:\n      - name: Centralized Log Aggregation\n        description: Collect application logs from hundreds of servers and aggregate them into HDFS, Kafka, or Elasticsearch.\n      - name: Real-Time Log Tailing\n        description: Tail application log files in real time using Taildir source for immediate event processing.\n      - name: Syslog Ingestion\n        description: Ingest RFC-3164 and RFC-5424 syslog events from network devices into centralized storage.\n      - name: Kafka Event Ingestion\n        description: Bridge Kafka topics to HDFS or other storage for batch analytics on streaming event data.\n      - name: Multi-Tier Architectures\n        description: Build tiered data collection with edge collectors forwarding to aggregation agents and final destinations.\n\
  \  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Kafka source and channel for consuming events, and Kafka sink for writing events to topics.\n      - name: Apache HDFS\n        description: Primary sink for writing log data to Hadoop Distributed File System for batch analytics.\n      - name: Apache HBase\n        description: HBase sink for writing events directly to HBase tables for random-access analytics.\n      - name: Apache Solr\n        description: Solr sink for indexing log events for full-text search capabilities.\n      - name: Elasticsearch\n        description: Elasticsearch sink for indexing and searching aggregated log data.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml
tags:
- Apache
- Data Collection
- ETL
- Log Aggregation
- Open Source
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml
use_cases:
- description: Collect application logs from hundreds of servers and aggregate them into HDFS, Kafka, or Elasticsearch.
  name: Centralized Log Aggregation
- description: Tail application log files in real time using Taildir source for immediate event processing.
  name: Real-Time Log Tailing
- description: Ingest RFC-3164 and RFC-5424 syslog events from network devices into centralized storage.
  name: Syslog Ingestion
- description: Bridge Kafka topics to HDFS or other storage for batch analytics on streaming event data.
  name: Kafka Event Ingestion
- description: Build tiered data collection with edge collectors forwarding to aggregation agents and final destinations.
  name: Multi-Tier Architectures
---
