---
api_count: 1
api_specs:
- filename: apache-samza-rest-api.yaml
  format: yaml
  label: Apache Samza
  slug: apache-samza
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/openapi/apache-samza-rest-api.yaml
apis:
- description: Samza provides a high-level Streams API and low-level Task API in Java/Scala for stateful stream processing, with a REST API for job management and integration with Kafka, HDFS, and other data systems
  name: Apache Samza
  slug: apache-samza
capabilities:
- description: ''
  name: Samza Workflow
  slug: samza-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/samza
- title: ''
  type: Documentation
  url: https://samza.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-samza-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-samza-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/samza-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-samza-context.jsonld
created: '2026-03-16'
description: Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both stream and batch processing.
features:
- description: Native Apache Kafka consumer/producer for stream processing
  name: Kafka Integration
- description: Runs on Apache YARN for resource management and fault tolerance
  name: YARN Execution
- description: Local state stores with RocksDB for low-latency stateful computations
  name: Stateful Processing
- description: Transactional state stores for exactly-once semantics
  name: Exactly-Once Processing
- description: Run on YARN, Kubernetes, or standalone
  name: Flexible Deployment
- description: Fluent API and SQL support for stream transformations
  name: High Level API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary messaging system for Samza input and output streams
  name: Apache Kafka
- description: Resource management and job scheduling on Hadoop
  name: Apache YARN
- description: HDFS integration for checkpoint storage
  name: Apache Hadoop
- description: Embedded state store for local stateful processing
  name: RocksDB
jsonld:
- class_count: 8
  name: Apache Samza Context
  property_count: 17
  slug: apache-samza-context
layout: provider
modified: '2026-04-19'
name: Apache Samza
rules:
- name: Apache Samza API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-samza-spectral-rules
skills: []
slug: apache-samza
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-samza\nname: Apache Samza\ndescription: >-\n  Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both\n  stream and batch processing.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Big Data\n- Hadoop\n- Kafka\n- Stream Processing\n- Streaming\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-samza:apache-samza\n  name: Apache Samza\n  description: >-\n    Samza provides a high-level Streams API and low-level Task API in Java/Scala for stateful stream processing, with a REST API for job management and integration with Kafka, HDFS, and other data systems.\n\
  \  humanURL: https://samza.apache.org/learn/documentation/latest/\n  tags:\n  - Job Management\n  - REST\n  - Stream Processing\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://samza.apache.org/learn/documentation/latest/\n  - type: Documentation\n    url: https://samza.apache.org/learn/documentation/\n  - type: OpenAPI\n    url: openapi/apache-samza-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/samza\n- type: Documentation\n  url: https://samza.apache.org/\n- type: SpectralRules\n  url: rules/apache-samza-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-samza-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/samza-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-samza-context.jsonld\n- type: Features\n  data:\n  - name: Kafka Integration\n    description: Native Apache Kafka consumer/producer for stream processing\n\
  \  - name: YARN Execution\n    description: Runs on Apache YARN for resource management and fault tolerance\n  - name: Stateful Processing\n    description: Local state stores with RocksDB for low-latency stateful computations\n  - name: Exactly-Once Processing\n    description: Transactional state stores for exactly-once semantics\n  - name: Flexible Deployment\n    description: Run on YARN, Kubernetes, or standalone\n  - name: High Level API\n    description: Fluent API and SQL support for stream transformations\n- type: UseCases\n  data:\n  - name: Event Stream Processing\n    description: Real-time processing of Kafka event streams\n  - name: Stateful Aggregations\n    description: Windowed aggregations over streaming data\n  - name: Stream Joins\n    description: Join multiple Kafka streams for enrichment\n  - name: Change Data Capture\n    description: Process CDC events from databases in real time\n- type: Integrations\n  data:\n  - name: Apache Kafka\n    description: Primary messaging\
  \ system for Samza input and output streams\n  - name: Apache YARN\n    description: Resource management and job scheduling on Hadoop\n  - name: Apache Hadoop\n    description: HDFS integration for checkpoint storage\n  - name: RocksDB\n    description: Embedded state store for local stateful processing\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/apis.yml
tags:
- Big Data
- Hadoop
- Kafka
- Stream Processing
- Streaming
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/apis.yml
use_cases:
- description: Real-time processing of Kafka event streams
  name: Event Stream Processing
- description: Windowed aggregations over streaming data
  name: Stateful Aggregations
- description: Join multiple Kafka streams for enrichment
  name: Stream Joins
- description: Process CDC events from databases in real time
  name: Change Data Capture
---
