---
api_count: 1
apis:
- description: ORC provides Java and C++ APIs for reading and writing ORC columnar files, with support for predicate pushdown, column projection, compression codecs, and integration with Hive, Spark, Presto, and oth
  name: Apache ORC
  slug: apache-orc
capabilities:
- description: Workflow capability for reading, writing, converting, and analyzing Apache ORC columnar files.
  name: Apache ORC File Processing Workflow
  slug: orc-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/orc
- title: ''
  type: Documentation
  url: https://orc.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-orc-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-orc-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/orc-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-orc-context.jsonld
created: '2026-03-16'
description: Apache ORC is a self-describing, type-aware columnar file format designed for Hadoop workloads. It provides high compression ratios and fast read performance for large-scale data processing with support for complex data types.
features:
- description: Stores data by column for efficient compression and query performance
  name: Columnar Storage
- description: Skip reading data that does not match query predicates
  name: Predicate Pushdown
- description: Read only the columns needed for a query
  name: Column Projection
- description: Full ACID transactional support when used with Apache Hive
  name: ACID Support
- description: Add, rename, and remove columns while preserving backward compatibility
  name: Schema Evolution
- description: Supports ZLIB, Snappy, LZO, LZ4, and ZSTD compression codecs
  name: Compression
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native ORC support as default Hive storage format
  name: Apache Hive
- description: ORC data source support in Spark SQL
  name: Apache Spark
- description: Fast ORC reading with native vectorized reader
  name: Presto/Trino
- description: ORC file format support for batch and streaming
  name: Apache Flink
- description: ORC to Arrow conversion for in-memory analytics
  name: Apache Arrow
jsonld:
- class_count: 12
  name: Apache Orc Context
  property_count: 37
  slug: apache-orc-context
layout: provider
modified: '2026-04-19'
name: Apache ORC
rules:
- name: Apache ORC API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: apache-orc-spectral-rules
skills: []
slug: apache-orc
solutions: []
tags:
- Big Data
- Columnar Storage
- Compression
- File Format
- Hadoop
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/apis.yml
use_cases:
- description: Store Hive tables in highly efficient ORC format
  name: Hive Data Warehousing
- description: Process large ORC datasets with Apache Spark SQL
  name: Spark Analytics
- description: Fast analytical queries over ORC files with Presto or Trino
  name: Presto/Trino Queries
- description: Efficient columnar storage for data lake architectures
  name: Data Lake Storage
---
