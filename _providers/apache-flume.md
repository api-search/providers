---
api_count: 2
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
