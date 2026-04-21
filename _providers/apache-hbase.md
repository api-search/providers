---
api_count: 2
apis:
- description: REST API (Stargate) for Apache HBase distributed NoSQL database, providing table management, row and cell operations, and table scanning via HTTP with JSON or XML encoding.
  name: Apache HBase REST API
  slug: apache-hbase-rest-api
- description: Java client API for all HBase data operations including table administration, filters, coprocessors, batch operations, and async client for high-throughput workloads.
  name: Apache HBase Java Client API
  slug: apache-hbase-java-api
capabilities:
- description: ''
  name: Hbase Data Access
  slug: hbase-data-access
common:
- title: ''
  type: Documentation
  url: https://hbase.apache.org/book.html
- title: ''
  type: GettingStarted
  url: https://hbase.apache.org/book.html#quickstart
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/hbase
- title: ''
  type: SpectralRules
  url: rules/apache-hbase-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-hbase-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/hbase-data-access.yaml
created: '2026-03-16'
description: Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable. It provides random, real-time read/write access to big data and runs on top of Apache Hadoop HDFS, offering a REST API (Stargate), Thrift API, and Java client API for table and cell-level operations.
features:
- description: Store sparse, semi-structured data in a distributed wide-column table model inspired by Google Bigtable.
  name: Wide-Column NoSQL Storage
- description: HTTP REST gateway for language-agnostic table and row operations using JSON or XML.
  name: REST API (Stargate)
- description: High-performance Thrift interface for cross-language HBase access with compact binary encoding.
  name: Thrift API
- description: Strong consistency guarantees for single-row get, put, and delete operations.
  name: Row-Level Consistency
- description: Server-side coprocessor framework for custom observers and endpoints analogous to stored procedures.
  name: Coprocessors
- description: JRuby-based interactive shell for administrative and data manipulation operations.
  name: HBase Shell
- description: Flexible server-side scan API with filters, time ranges, and column family projections.
  name: Scanner API
- description: Asynchronous multi-cluster replication for disaster recovery and geographic distribution.
  name: Replication
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: HBase uses HDFS as its underlying distributed file system for WAL and HFile storage.
  name: Apache Hadoop HDFS
- description: SQL skin over HBase providing JDBC access, secondary indexes, and query optimization.
  name: Apache Phoenix
- description: Spark-HBase connector for reading and writing HBase tables as Spark DataFrames.
  name: Apache Spark
- description: HBase storage handler for using HBase tables as external Hive tables.
  name: Apache Hive
- description: Flink HBase connector for reading and writing HBase tables in streaming pipelines.
  name: Apache Flink
jsonld:
- class_count: 26
  name: Apache Hbase Rest Context
  property_count: 0
  slug: apache-hbase-rest-context
layout: provider
modified: '2026-04-19'
name: Apache HBase
rules:
- name: Apache HBase API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: apache-hbase-spectral-rules
skills: []
slug: apache-hbase
solutions: []
tags:
- Apache
- Big Data
- Bigtable
- Database
- Hadoop
- NoSQL
- Open Source
- Wide Column
url: https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml
use_cases:
- description: Store high-velocity time-series sensor or log data with row keys designed for time range scans.
  name: Time-Series Data Storage
- description: Persist event streams from web applications or IoT devices for analytics and audit.
  name: Event Logging
- description: Store sparse user profile attributes at scale with efficient random access by user ID.
  name: User Profile Storage
- description: Use HBase as a backend storage engine for graph databases like Apache TinkerPop/JanusGraph.
  name: Graph Storage Backend
- description: Store and serve pre-computed ML features at low latency for online prediction.
  name: Machine Learning Feature Store
---
