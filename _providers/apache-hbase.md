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
source_yaml: "aid: apache-hbase\nname: Apache HBase\ndescription: >-\n  Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable. It provides random, real-time read/write access to big data and runs on top of Apache Hadoop HDFS, offering a REST API (Stargate), Thrift API, and Java client API for table and cell-level operations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Big Data\n  - Bigtable\n  - Database\n  - Hadoop\n  - NoSQL\n  - Open Source\n  - Wide Column\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-hbase:apache-hbase-rest-api\n    name: Apache HBase REST API\n    description: >-\n      REST API (Stargate) for Apache HBase distributed NoSQL database, providing\
  \ table management, row and cell operations, and table scanning via HTTP with JSON or XML encoding.\n    humanURL: https://hbase.apache.org/book.html#_rest\n    baseURL: http://localhost:8080\n    tags:\n      - Cells\n      - NoSQL\n      - REST\n      - Rows\n      - Tables\n    properties:\n      - type: Documentation\n        url: https://hbase.apache.org/book.html#_rest\n      - type: OpenAPI\n        url: openapi/apache-hbase-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/hbase-rest-tableschema-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-hbase-rest-context.jsonld\n\n  - aid: apache-hbase:apache-hbase-java-api\n    name: Apache HBase Java Client API\n    description: >-\n      Java client API for all HBase data operations including table administration, filters, coprocessors, batch operations, and async client for high-throughput workloads.\n    humanURL: https://hbase.apache.org/apidocs/\n    tags:\n      - Java\n      - NoSQL\n      - SDK\n\
  \    properties:\n      - type: Documentation\n        url: https://hbase.apache.org/apidocs/\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.hbase/hbase-client\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://hbase.apache.org/book.html\n  - type: GettingStarted\n    url: https://hbase.apache.org/book.html#quickstart\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/hbase\n  - type: SpectralRules\n    url: rules/apache-hbase-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-hbase-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/hbase-data-access.yaml\n  - type: Features\n    data:\n      - name: Wide-Column NoSQL Storage\n        description: Store sparse, semi-structured data in a distributed wide-column table model inspired by Google Bigtable.\n      - name: REST API (Stargate)\n        description:\
  \ HTTP REST gateway for language-agnostic table and row operations using JSON or XML.\n      - name: Thrift API\n        description: High-performance Thrift interface for cross-language HBase access with compact binary encoding.\n      - name: Row-Level Consistency\n        description: Strong consistency guarantees for single-row get, put, and delete operations.\n      - name: Coprocessors\n        description: Server-side coprocessor framework for custom observers and endpoints analogous to stored procedures.\n      - name: HBase Shell\n        description: JRuby-based interactive shell for administrative and data manipulation operations.\n      - name: Scanner API\n        description: Flexible server-side scan API with filters, time ranges, and column family projections.\n      - name: Replication\n        description: Asynchronous multi-cluster replication for disaster recovery and geographic distribution.\n  - type: UseCases\n    data:\n      - name: Time-Series Data Storage\n \
  \       description: Store high-velocity time-series sensor or log data with row keys designed for time range scans.\n      - name: Event Logging\n        description: Persist event streams from web applications or IoT devices for analytics and audit.\n      - name: User Profile Storage\n        description: Store sparse user profile attributes at scale with efficient random access by user ID.\n      - name: Graph Storage Backend\n        description: Use HBase as a backend storage engine for graph databases like Apache TinkerPop/JanusGraph.\n      - name: Machine Learning Feature Store\n        description: Store and serve pre-computed ML features at low latency for online prediction.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop HDFS\n        description: HBase uses HDFS as its underlying distributed file system for WAL and HFile storage.\n      - name: Apache Phoenix\n        description: SQL skin over HBase providing JDBC access, secondary indexes, and query optimization.\n\
  \      - name: Apache Spark\n        description: Spark-HBase connector for reading and writing HBase tables as Spark DataFrames.\n      - name: Apache Hive\n        description: HBase storage handler for using HBase tables as external Hive tables.\n      - name: Apache Flink\n        description: Flink HBase connector for reading and writing HBase tables in streaming pipelines.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml
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
