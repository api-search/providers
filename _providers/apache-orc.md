---
api_count: 1
api_specs:
- filename: apache-orc-tools-api.yaml
  format: yaml
  label: Apache ORC
  slug: apache-orc
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/openapi/apache-orc-tools-api.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-orc\nname: Apache ORC\ndescription: >-\n  Apache ORC is a self-describing, type-aware columnar file format designed for Hadoop workloads. It provides high compression ratios and fast read performance for large-scale data processing with support\n  for complex data types.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Big Data\n- Columnar Storage\n- Compression\n- File Format\n- Hadoop\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-orc:apache-orc\n  name: Apache ORC\n  description: >-\n    ORC provides Java and C++ APIs for reading and writing ORC columnar files, with support for predicate pushdown, column projection, compression codecs, and integration with Hive, Spark, Presto, and other\n    query\
  \ engines.\n  humanURL: https://orc.apache.org/docs/\n  tags:\n  - C++\n  - Columnar Format\n  - Java\n  - Apache\n  - Open Source\n  - Big Data\n  properties:\n  - type: Documentation\n    url: https://orc.apache.org/docs/\n  - type: OpenAPI\n    url: openapi/apache-orc-tools-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/orc\n- type: Documentation\n  url: https://orc.apache.org/\n- type: SpectralRules\n  url: rules/apache-orc-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-orc-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/orc-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-orc-context.jsonld\n- type: Features\n  data:\n  - name: Columnar Storage\n    description: Stores data by column for efficient compression and query performance\n  - name: Predicate Pushdown\n    description: Skip reading data that does not match query predicates\n  - name: Column\
  \ Projection\n    description: Read only the columns needed for a query\n  - name: ACID Support\n    description: Full ACID transactional support when used with Apache Hive\n  - name: Schema Evolution\n    description: Add, rename, and remove columns while preserving backward compatibility\n  - name: Compression\n    description: Supports ZLIB, Snappy, LZO, LZ4, and ZSTD compression codecs\n- type: UseCases\n  data:\n  - name: Hive Data Warehousing\n    description: Store Hive tables in highly efficient ORC format\n  - name: Spark Analytics\n    description: Process large ORC datasets with Apache Spark SQL\n  - name: Presto/Trino Queries\n    description: Fast analytical queries over ORC files with Presto or Trino\n  - name: Data Lake Storage\n    description: Efficient columnar storage for data lake architectures\n- type: Integrations\n  data:\n  - name: Apache Hive\n    description: Native ORC support as default Hive storage format\n  - name: Apache Spark\n    description: ORC data source\
  \ support in Spark SQL\n  - name: Presto/Trino\n    description: Fast ORC reading with native vectorized reader\n  - name: Apache Flink\n    description: ORC file format support for batch and streaming\n  - name: Apache Arrow\n    description: ORC to Arrow conversion for in-memory analytics\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/apis.yml
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
