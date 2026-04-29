---
api_count: 2
apis:
- description: The Apache Beam SDK provides the programming model for constructing data processing pipelines. Available in Java, Python, and Go, it provides PCollections, PTransforms, and Runners for batch and strea
  name: Apache Beam SDK
  slug: apache-beam-sdk
- description: The Beam Job Service API provides a gRPC-based interface for submitting, managing, and monitoring Apache Beam pipeline jobs on supported runners. It is part of the Beam portability framework and enabl
  name: Apache Beam Job Service API
  slug: apache-beam-job-service
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/beam
- title: ''
  type: Documentation
  url: https://beam.apache.org/
- title: ''
  type: GettingStarted
  url: https://beam.apache.org/get-started/
- title: ''
  type: Tutorials
  url: https://beam.apache.org/get-started/wordcount-example/
- title: ''
  type: Support
  url: https://beam.apache.org/community/contact-us/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://beam.apache.org/blog/
- title: Python SDK (PyPI)
  type: SDK
  url: https://pypi.org/project/apache-beam/
- title: Java SDK (Maven)
  type: SDK
  url: https://search.maven.org/artifact/org.apache.beam/beam-sdks-java-core
- title: Go SDK
  type: SDK
  url: https://pkg.go.dev/github.com/apache/beam/sdks/v2/go/pkg/beam
created: '2026-03-16'
description: Apache Beam is a unified, open-source programming model developed by the Apache Software Foundation for defining both batch and streaming data processing pipelines. It provides a portable API layer that lets developers write pipeline logic once in Java, Python, or Go and deploy it to multiple execution engines (runners) including Apache Flink, Apache Spark, Google Cloud Dataflow, and the direct runner for local testing. The Beam portability framework enables cross-language pipelines and runner-agnostic execution.
features:
- description: Single programming model for both batch and streaming data processing with consistent semantics.
  name: Unified Batch and Streaming
- description: Write pipeline logic once and execute on Apache Flink, Spark, Google Dataflow, Samza, or the local direct runner.
  name: Runner Portability
- description: Native SDKs for Java, Python, and Go with cross-language transform support for mixing languages.
  name: Multi-Language Support
- description: Flexible windowing (fixed, sliding, session, global) and trigger strategies for streaming data processing.
  name: Windowing and Triggers
- description: Built-in connectors for BigQuery, Kafka, Pub/Sub, GCS, HDFS, databases, and many other sources and sinks.
  name: I/O Connectors
- description: SQL-based data processing on Beam PCollections using Apache Calcite for query planning.
  name: Beam SQL
- description: RunInference transform for integrating ML model inference into Beam pipelines with TensorFlow, PyTorch, and sklearn.
  name: ML Integration
- description: Schema inference and typed PCollections for structured data processing with automatic serialization.
  name: Schema-Aware Processing
- description: Call Java transforms from Python pipelines and vice versa via the Beam portability framework.
  name: Cross-Language Transforms
- description: Built-in metrics API and integration with runner-specific monitoring dashboards.
  name: Metrics and Monitoring
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Managed Apache Beam runner on Google Cloud with autoscaling and monitoring.
  name: Google Cloud Dataflow
- description: Apache Flink runner for stateful stream processing with exactly-once semantics.
  name: Apache Flink
- description: Apache Spark runner for batch and streaming processing on Spark clusters.
  name: Apache Spark
- description: Kafka I/O connector for reading and writing Kafka topics in Beam pipelines.
  name: Apache Kafka
- description: BigQuery I/O connector for reading and writing BigQuery tables in Beam pipelines.
  name: Google BigQuery
- description: HDFS I/O connector for reading and writing files on Hadoop HDFS.
  name: Apache Hadoop
- description: TFX uses Beam as the runtime for ML data validation and preprocessing components.
  name: TensorFlow Extended (TFX)
layout: provider
modified: '2026-04-19'
name: Apache Beam
skills: []
slug: apache-beam
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-beam\nname: Apache Beam\ndescription: >-\n  Apache Beam is a unified, open-source programming model developed by the Apache Software Foundation for defining both batch and streaming data processing pipelines. It provides a portable API layer that lets developers write pipeline logic once in Java, Python, or Go and deploy it to multiple execution engines (runners) including Apache Flink, Apache Spark, Google Cloud Dataflow, and the direct runner for local testing. The Beam portability framework enables cross-language pipelines and runner-agnostic execution.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Batch Processing\n  - Data Pipeline\n  - ETL\n  - Open Source\n  - Python\n  - Streaming\n  - Unified Model\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-beam/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-beam:apache-beam-sdk\n    name: Apache Beam SDK\n    description: >-\n      The Apache Beam SDK provides the programming model for constructing data processing pipelines. Available in Java, Python, and Go, it provides PCollections, PTransforms, and Runners for batch and streaming data processing.\n    humanURL: https://beam.apache.org/documentation/\n    tags:\n      - Batch\n      - Pipeline\n      - SDK\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://beam.apache.org/documentation/\n      - type: APIReference\n        url: https://beam.apache.org/releases/pydoc/current/\n      - type: GettingStarted\n        url: https://beam.apache.org/get-started/wordcount-example/\n  - aid: apache-beam:apache-beam-job-service\n    name: Apache Beam Job Service API\n    description: >-\n      The Beam Job Service API provides a gRPC-based interface for submitting, managing, and monitoring Apache Beam pipeline\
  \ jobs on supported runners. It is part of the Beam portability framework and enables cross-runner job management.\n    humanURL: https://beam.apache.org/documentation/runtime/environments/\n    tags:\n      - gRPC\n      - Job Management\n      - Portability\n    properties:\n      - type: Documentation\n        url: https://beam.apache.org/documentation/runtime/environments/\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/beam\n  - type: Documentation\n    url: https://beam.apache.org/\n  - type: GettingStarted\n    url: https://beam.apache.org/get-started/\n  - type: Tutorials\n    url: https://beam.apache.org/get-started/wordcount-example/\n  - type: Support\n    url: https://beam.apache.org/community/contact-us/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: ChangeLog\n    url: https://beam.apache.org/blog/\n  - type: SDK\n    url: https://pypi.org/project/apache-beam/\n\
  \    title: Python SDK (PyPI)\n  - type: SDK\n    url: https://search.maven.org/artifact/org.apache.beam/beam-sdks-java-core\n    title: Java SDK (Maven)\n  - type: SDK\n    url: https://pkg.go.dev/github.com/apache/beam/sdks/v2/go/pkg/beam\n    title: Go SDK\n  - type: Features\n    data:\n      - name: Unified Batch and Streaming\n        description: Single programming model for both batch and streaming data processing with consistent semantics.\n      - name: Runner Portability\n        description: Write pipeline logic once and execute on Apache Flink, Spark, Google Dataflow, Samza, or the local direct runner.\n      - name: Multi-Language Support\n        description: Native SDKs for Java, Python, and Go with cross-language transform support for mixing languages.\n      - name: Windowing and Triggers\n        description: Flexible windowing (fixed, sliding, session, global) and trigger strategies for streaming data processing.\n      - name: I/O Connectors\n        description: Built-in\
  \ connectors for BigQuery, Kafka, Pub/Sub, GCS, HDFS, databases, and many other sources and sinks.\n      - name: Beam SQL\n        description: SQL-based data processing on Beam PCollections using Apache Calcite for query planning.\n      - name: ML Integration\n        description: RunInference transform for integrating ML model inference into Beam pipelines with TensorFlow, PyTorch, and sklearn.\n      - name: Schema-Aware Processing\n        description: Schema inference and typed PCollections for structured data processing with automatic serialization.\n      - name: Cross-Language Transforms\n        description: Call Java transforms from Python pipelines and vice versa via the Beam portability framework.\n      - name: Metrics and Monitoring\n        description: Built-in metrics API and integration with runner-specific monitoring dashboards.\n  - type: UseCases\n    data:\n      - name: ETL Pipelines\n        description: Extract, transform, and load data between storage systems\
  \ using portable, reusable pipeline components.\n      - name: Real-Time Stream Processing\n        description: Process high-throughput event streams with low-latency windowing and triggering strategies.\n      - name: Batch Data Analytics\n        description: Compute aggregate statistics, joins, and group-by operations on large historical datasets.\n      - name: ML Model Inference at Scale\n        description: Run ML model inference in distributed pipelines using the RunInference transform.\n      - name: Log and Event Processing\n        description: Parse, filter, and enrich log events from Kafka or Pub/Sub for operational analytics.\n      - name: Data Migration\n        description: Migrate data between cloud providers and storage systems using Beam's portable I/O connectors.\n  - type: Integrations\n    data:\n      - name: Google Cloud Dataflow\n        description: Managed Apache Beam runner on Google Cloud with autoscaling and monitoring.\n      - name: Apache Flink\n    \
  \    description: Apache Flink runner for stateful stream processing with exactly-once semantics.\n      - name: Apache Spark\n        description: Apache Spark runner for batch and streaming processing on Spark clusters.\n      - name: Apache Kafka\n        description: Kafka I/O connector for reading and writing Kafka topics in Beam pipelines.\n      - name: Google BigQuery\n        description: BigQuery I/O connector for reading and writing BigQuery tables in Beam pipelines.\n      - name: Apache Hadoop\n        description: HDFS I/O connector for reading and writing files on Hadoop HDFS.\n      - name: TensorFlow Extended (TFX)\n        description: TFX uses Beam as the runtime for ML data validation and preprocessing components.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-beam/refs/heads/main/apis.yml
tags:
- Apache
- Batch Processing
- Data Pipeline
- ETL
- Open Source
- Python
- Streaming
- Unified Model
url: https://raw.githubusercontent.com/api-evangelist/apache-beam/refs/heads/main/apis.yml
use_cases:
- description: Extract, transform, and load data between storage systems using portable, reusable pipeline components.
  name: ETL Pipelines
- description: Process high-throughput event streams with low-latency windowing and triggering strategies.
  name: Real-Time Stream Processing
- description: Compute aggregate statistics, joins, and group-by operations on large historical datasets.
  name: Batch Data Analytics
- description: Run ML model inference in distributed pipelines using the RunInference transform.
  name: ML Model Inference at Scale
- description: Parse, filter, and enrich log events from Kafka or Pub/Sub for operational analytics.
  name: Log and Event Processing
- description: Migrate data between cloud providers and storage systems using Beam's portable I/O connectors.
  name: Data Migration
---
