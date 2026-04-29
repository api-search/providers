---
api_count: 1
api_specs:
- filename: apache-seatunnel-rest-api.yaml
  format: yaml
  label: Apache SeaTunnel REST API
  slug: apache-seatunnel-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/openapi/apache-seatunnel-rest-api.yaml
apis:
- description: SeaTunnel provides a REST API for job management and monitoring, a Connector API for building custom data sources and sinks, and a Transform API for data transformation, supporting over 100 built-in c
  name: Apache SeaTunnel REST API
  slug: apache-seatunnel-rest-api
capabilities:
- description: ''
  name: Seatunnel Workflow
  slug: seatunnel-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/seatunnel
- title: ''
  type: Documentation
  url: https://seatunnel.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-seatunnel-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-seatunnel-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/seatunnel-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-seatunnel-context.jsonld
created: '2026-03-16'
description: Apache SeaTunnel is a high-performance, distributed data integration platform that supports real-time and batch data synchronization. It provides a connector API with support for over 100 data sources and sinks.
features:
- description: Over 200 built-in connectors for databases, warehouses, and file systems
  name: 200+ Connectors
- description: Unified API for both batch ETL and real-time streaming jobs
  name: Batch and Streaming
- description: Automatic schema detection and evolution support
  name: Schema Evolution
- description: Zeta execution engine with no external dependencies
  name: Distributed Execution
- description: Change Data Capture for real-time database synchronization
  name: CDC Support
- description: Built-in SQL and custom transform functions
  name: Transform Layer
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka source and sink connector for streaming pipelines
  name: Apache Kafka
- description: Run SeaTunnel jobs on Flink execution engine
  name: Apache Flink
- description: Run SeaTunnel jobs on Spark execution engine
  name: Apache Spark
- description: High-performance ClickHouse sink connector
  name: ClickHouse
- description: Apache Doris connector for analytical workloads
  name: Doris
jsonld:
- class_count: 10
  name: Apache Seatunnel Context
  property_count: 32
  slug: apache-seatunnel-context
layout: provider
modified: '2026-04-19'
name: Apache SeaTunnel
rules:
- name: Apache SeaTunnel API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-seatunnel-spectral-rules
skills: []
slug: apache-seatunnel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-seatunnel\nname: Apache SeaTunnel\ndescription: >-\n  Apache SeaTunnel is a high-performance, distributed data integration platform that supports real-time and batch data synchronization. It provides a connector API with support for over 100 data sources\n  and sinks.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Data Integration\n- ETL\n- ELT\n- Batch\n- Streaming\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-seatunnel:apache-seatunnel-rest-api\n  name: Apache SeaTunnel REST API\n  description: >-\n    SeaTunnel provides a REST API for job management and monitoring, a Connector API for building custom data sources and sinks, and a Transform API for data transformation, supporting over 100\
  \ built-in\n    connectors.\n  humanURL: https://seatunnel.apache.org/docs/\n  tags:\n  - Data Integration\n  - Job Management\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://seatunnel.apache.org/docs/\n  - type: OpenAPI\n    url: openapi/apache-seatunnel-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/seatunnel\n- type: Documentation\n  url: https://seatunnel.apache.org/\n- type: SpectralRules\n  url: rules/apache-seatunnel-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-seatunnel-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/seatunnel-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-seatunnel-context.jsonld\n- type: Features\n  data:\n  - name: 200+ Connectors\n    description: Over 200 built-in connectors for databases, warehouses, and file systems\n  - name: Batch and Streaming\n    description:\
  \ Unified API for both batch ETL and real-time streaming jobs\n  - name: Schema Evolution\n    description: Automatic schema detection and evolution support\n  - name: Distributed Execution\n    description: Zeta execution engine with no external dependencies\n  - name: CDC Support\n    description: Change Data Capture for real-time database synchronization\n  - name: Transform Layer\n    description: Built-in SQL and custom transform functions\n- type: UseCases\n  data:\n  - name: Database Migration\n    description: Migrate data between databases with schema mapping\n  - name: Data Warehouse Loading\n    description: Load and sync data into data warehouses\n  - name: Real-Time Synchronization\n    description: CDC-based real-time sync between source and target systems\n  - name: Data Lake Ingestion\n    description: Ingest data from multiple sources into a data lake\n- type: Integrations\n  data:\n  - name: Apache Kafka\n    description: Kafka source and sink connector for streaming\
  \ pipelines\n  - name: Apache Flink\n    description: Run SeaTunnel jobs on Flink execution engine\n  - name: Apache Spark\n    description: Run SeaTunnel jobs on Spark execution engine\n  - name: ClickHouse\n    description: High-performance ClickHouse sink connector\n  - name: Doris\n    description: Apache Doris connector for analytical workloads\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml
tags:
- Data Integration
- ETL
- ELT
- Batch
- Streaming
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml
use_cases:
- description: Migrate data between databases with schema mapping
  name: Database Migration
- description: Load and sync data into data warehouses
  name: Data Warehouse Loading
- description: CDC-based real-time sync between source and target systems
  name: Real-Time Synchronization
- description: Ingest data from multiple sources into a data lake
  name: Data Lake Ingestion
---
