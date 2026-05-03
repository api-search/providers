---
api_count: 3
api_specs:
- filename: vector-observability-api-openapi.yml
  format: yaml
  label: Vector Observability API
  slug: vector-observability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/openapi/vector-observability-api-openapi.yml
apis:
- description: 'The Vector Observability API provides HTTP endpoints for health monitoring of running Vector instances and gRPC endpoints for component inspection and event streaming. Enable via api.enabled: true in '
  name: Vector Observability API
  slug: vector-observability-api
- description: Vector Remap Language (VRL) is a purpose-built expression language for transforming observability data in Vector. Provides 100+ built-in functions for parsing, filtering, enriching, and transforming l
  name: Vector Remap Language (VRL)
  slug: vector-vrl
- description: Official Helm charts for deploying Vector on Kubernetes as a DaemonSet (agent mode) or Deployment (aggregator mode).
  name: Vector Helm Charts
  slug: vector-helm
capabilities:
- description: Workflow capability for DevOps engineers monitoring Vector observability pipeline health. Provides health check access for integration with load balancers, Kubernetes probes, and monitoring systems.
  name: Vector Pipeline Monitoring
  slug: pipeline-monitoring
common:
- title: ''
  type: Website
  url: https://vector.dev
- title: ''
  type: Documentation
  url: https://vector.dev/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/vectordotdev
- title: ''
  type: GitHubRepository
  url: https://github.com/vectordotdev/vector
- title: ''
  type: ReleaseNotes
  url: https://vector.dev/releases/
- title: ''
  type: Blog
  url: https://vector.dev/blog/
- title: ''
  type: Forum
  url: https://discord.com/invite/n2yjjZR
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/vector-dev
- title: ''
  type: SpectralRules
  url: rules/vector-spectral-rules.yml
- title: Pipeline Monitoring
  type: NaftikoCapability
  url: capabilities/pipeline-monitoring.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/vector-vocabulary.yaml
created: '2026-03-25'
description: Vector is an open source high-performance observability data pipeline from Datadog for collecting, transforming, and routing logs, metrics, and traces. Built in Rust for performance and reliability, Vector supports 50+ sources, 20+ transforms, and 80+ sinks. It provides a built-in API for health monitoring and component inspection, plus Vector Remap Language (VRL) for powerful data transformation.
features:
- description: Built in Rust with benchmarks showing 86+ MiB/s throughput for log pipeline workloads.
  name: High-Performance Pipeline
- description: Single binary handles logs, metrics, and traces from collection through routing.
  name: Unified Data Plane
- description: Native integrations for files, Kafka, Kubernetes, AWS S3/CloudWatch, Splunk, and more.
  name: 50+ Sources
- description: Route data to Elasticsearch, Datadog, S3, BigQuery, Splunk, Loki, and many more destinations.
  name: 80+ Sinks
- description: Purpose-built expression language with 100+ functions for transforming observability data.
  name: Vector Remap Language (VRL)
- description: Built-in HTTP/gRPC API for health checks and component inspection (must be explicitly enabled).
  name: Observability API
- description: Deploy as DaemonSet (agent) or Deployment (aggregator) with official Helm charts.
  name: Kubernetes Native
- description: Run as a lightweight agent on each node or as a centralized aggregator for fan-in routing.
  name: Agent and Aggregator Modes
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Datadog logs and metrics sink; Vector was created and is maintained by Datadog.
  name: Datadog
- description: Elasticsearch sink for forwarding logs and metrics to Elasticsearch clusters.
  name: Elasticsearch
- description: Splunk HTTP Event Collector sink for sending data to Splunk Enterprise and Cloud.
  name: Splunk HEC
- description: Kafka source and sink for consuming and producing observability data streams.
  name: Kafka
- description: S3 sink for archiving logs and metrics to Amazon S3 for long-term storage.
  name: AWS S3
- description: Loki sink for forwarding logs to Grafana's log aggregation system.
  name: Grafana Loki
- description: Prometheus remote write sink and scrape source for metrics pipelines.
  name: Prometheus
- description: Kubernetes source for collecting container logs, pod metadata, and events.
  name: Kubernetes
jsonld:
- class_count: 1
  name: Vector Observability Api Context
  property_count: 1
  slug: vector-observability-api-context
layout: provider
modified: '2026-05-03'
name: Vector
rules:
- name: Vector API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: vector-spectral-rules
skills: []
slug: vector
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vector\nname: Vector\ndescription: >-\n  Vector is an open source high-performance observability data pipeline from Datadog\n  for collecting, transforming, and routing logs, metrics, and traces. Built in Rust\n  for performance and reliability, Vector supports 50+ sources, 20+ transforms, and\n  80+ sinks. It provides a built-in API for health monitoring and component inspection,\n  plus Vector Remap Language (VRL) for powerful data transformation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Pipeline\n  - Logs\n  - Metrics\n  - Observability\n  - Open Source\n  - Rust\n  - Traces\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vector:vector-observability-api\n    name: Vector Observability API\n    description: >-\n      The Vector Observability API provides HTTP endpoints\
  \ for health monitoring\n      of running Vector instances and gRPC endpoints for component inspection and\n      event streaming. Enable via api.enabled: true in Vector configuration.\n      Binds to 127.0.0.1:8686 by default. Note: the API does not support\n      authentication and should only be used in isolated environments.\n    humanURL: https://vector.dev/docs/reference/api/\n    baseURL: http://127.0.0.1:8686\n    tags:\n      - Health Monitoring\n      - Observability\n      - Pipeline Management\n    properties:\n      - type: Documentation\n        url: https://vector.dev/docs/reference/api/\n      - type: OpenAPI\n        url: openapi/vector-observability-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vector-observability-api-health-response-schema.json\n        title: Health Response Schema\n      - type: JSONStructure\n        url: json-structure/vector-observability-api-health-response-structure.json\n        title: Health Response Structure\n      -\
  \ type: Example\n        url: examples/vector-observability-api-health-response-example.json\n        title: Health Response Example\n      - type: JSON-LD\n        url: json-ld/vector-observability-api-context.jsonld\n  - aid: vector:vector-vrl\n    name: Vector Remap Language (VRL)\n    description: >-\n      Vector Remap Language (VRL) is a purpose-built expression language for\n      transforming observability data in Vector. Provides 100+ built-in functions\n      for parsing, filtering, enriching, and transforming logs, metrics, and\n      traces without leaving the Vector pipeline.\n    humanURL: https://vector.dev/docs/reference/vrl/\n    tags:\n      - Data Transformation\n      - Expression Language\n      - VRL\n    properties:\n      - type: Documentation\n        url: https://vector.dev/docs/reference/vrl/\n      - type: GitHub Repository\n        url: https://github.com/vectordotdev/vrl\n  - aid: vector:vector-helm\n    name: Vector Helm Charts\n    description: >-\n    \
  \  Official Helm charts for deploying Vector on Kubernetes as a DaemonSet\n      (agent mode) or Deployment (aggregator mode).\n    humanURL: https://vector.dev/docs/setup/installation/package-managers/helm/\n    tags:\n      - Helm\n      - Kubernetes\n      - Deployment\n    properties:\n      - type: Documentation\n        url: https://vector.dev/docs/setup/installation/package-managers/helm/\n      - type: GitHub Repository\n        url: https://github.com/vectordotdev/helm-charts\ncommon:\n  - type: Website\n    url: https://vector.dev\n  - type: Documentation\n    url: https://vector.dev/docs/\n  - type: GitHubOrganization\n    url: https://github.com/vectordotdev\n  - type: GitHubRepository\n    url: https://github.com/vectordotdev/vector\n  - type: ReleaseNotes\n    url: https://vector.dev/releases/\n  - type: Blog\n    url: https://vector.dev/blog/\n  - type: Forum\n    url: https://discord.com/invite/n2yjjZR\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/vector-dev\n\
  \  - type: SpectralRules\n    url: rules/vector-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/pipeline-monitoring.yaml\n    title: Pipeline Monitoring\n  - type: Vocabulary\n    url: vocabulary/vector-vocabulary.yaml\n  - type: Features\n    data:\n      - name: High-Performance Pipeline\n        description: Built in Rust with benchmarks showing 86+ MiB/s throughput for log pipeline workloads.\n      - name: Unified Data Plane\n        description: Single binary handles logs, metrics, and traces from collection through routing.\n      - name: 50+ Sources\n        description: Native integrations for files, Kafka, Kubernetes, AWS S3/CloudWatch, Splunk, and more.\n      - name: 80+ Sinks\n        description: Route data to Elasticsearch, Datadog, S3, BigQuery, Splunk, Loki, and many more destinations.\n      - name: Vector Remap Language (VRL)\n        description: Purpose-built expression language with 100+ functions for transforming observability data.\n     \
  \ - name: Observability API\n        description: Built-in HTTP/gRPC API for health checks and component inspection (must be explicitly enabled).\n      - name: Kubernetes Native\n        description: Deploy as DaemonSet (agent) or Deployment (aggregator) with official Helm charts.\n      - name: Agent and Aggregator Modes\n        description: Run as a lightweight agent on each node or as a centralized aggregator for fan-in routing.\n  - type: UseCases\n    data:\n      - name: Log Pipeline Unification\n        description: Replace multiple log shippers with a single Vector pipeline for all log collection and routing.\n      - name: Observability Cost Reduction\n        description: Filter, sample, and transform data before sending to expensive SaaS observability platforms.\n      - name: Vendor Switching\n        description: Route observability data to multiple backends simultaneously to facilitate migration.\n      - name: Kubernetes Log Collection\n        description: Deploy Vector\
  \ as a DaemonSet to collect container logs from all Kubernetes nodes.\n      - name: Log Enrichment\n        description: Parse, enrich, and normalize log events using VRL before routing to downstream systems.\n      - name: Metrics Collection\n        description: Collect host and service metrics using Vector's built-in sources and forward to Prometheus or DataDog.\n      - name: Splunk Cost Reduction\n        description: Use Vector to filter and route Splunk data to reduce indexing volume and licensing costs.\n  - type: Integrations\n    data:\n      - name: Datadog\n        description: Native Datadog logs and metrics sink; Vector was created and is maintained by Datadog.\n      - name: Elasticsearch\n        description: Elasticsearch sink for forwarding logs and metrics to Elasticsearch clusters.\n      - name: Splunk HEC\n        description: Splunk HTTP Event Collector sink for sending data to Splunk Enterprise and Cloud.\n      - name: Kafka\n        description: Kafka source\
  \ and sink for consuming and producing observability data streams.\n      - name: AWS S3\n        description: S3 sink for archiving logs and metrics to Amazon S3 for long-term storage.\n      - name: Grafana Loki\n        description: Loki sink for forwarding logs to Grafana's log aggregation system.\n      - name: Prometheus\n        description: Prometheus remote write sink and scrape source for metrics pipelines.\n      - name: Kubernetes\n        description: Kubernetes source for collecting container logs, pod metadata, and events.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/apis.yml
tags:
- Data Pipeline
- Logs
- Metrics
- Observability
- Open Source
- Rust
- Traces
url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/apis.yml
use_cases:
- description: Replace multiple log shippers with a single Vector pipeline for all log collection and routing.
  name: Log Pipeline Unification
- description: Filter, sample, and transform data before sending to expensive SaaS observability platforms.
  name: Observability Cost Reduction
- description: Route observability data to multiple backends simultaneously to facilitate migration.
  name: Vendor Switching
- description: Deploy Vector as a DaemonSet to collect container logs from all Kubernetes nodes.
  name: Kubernetes Log Collection
- description: Parse, enrich, and normalize log events using VRL before routing to downstream systems.
  name: Log Enrichment
- description: Collect host and service metrics using Vector's built-in sources and forward to Prometheus or DataDog.
  name: Metrics Collection
- description: Use Vector to filter and route Splunk data to reduce indexing volume and licensing costs.
  name: Splunk Cost Reduction
---
