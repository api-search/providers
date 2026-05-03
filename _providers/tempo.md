---
api_count: 2
api_specs:
- filename: tempo-openapi.yml
  format: yaml
  label: Tempo HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/openapi/tempo-openapi.yml
apis:
- description: Tempo exposes an HTTP API for querying traces, searching spans, discovering tag keys and values, and generating metrics from trace data. The API is compatible with Jaeger and Zipkin query protocols in
  name: Tempo HTTP API
  slug: ''
- description: TraceQL is a query language developed for Grafana Tempo that allows filtering and selecting spans within traces. The TraceQL search API endpoint enables rich span-level filtering using a pipeline synt
  name: Tempo TraceQL API
  slug: ''
capabilities:
- description: Distributed tracing workflow using the Grafana Tempo API for trace retrieval, TraceQL search, tag discovery, and trace-based metrics generation. Used by SREs, platform engineers, and developers to inv
  name: Grafana Tempo Distributed Tracing
  slug: distributed-tracing
common:
- title: ''
  type: Website
  url: https://grafana.com/oss/tempo/
- title: ''
  type: Documentation
  url: https://grafana.com/docs/tempo/latest/
- title: ''
  type: GitHub Repository
  url: https://github.com/grafana/tempo
- title: ''
  type: GitHub Organization
  url: https://github.com/grafana
- title: ''
  type: Helm Chart
  url: https://grafana.github.io/helm-charts
- title: ''
  type: Docker Hub
  url: https://hub.docker.com/r/grafana/tempo
- title: ''
  type: Release Notes
  url: https://github.com/grafana/tempo/releases
- title: ''
  type: Community
  url: https://community.grafana.com/c/grafana-tempo/
- title: ''
  type: Slack
  url: https://grafana.slack.com/archives/C01BULREPHA
- title: ''
  type: Blog
  url: https://grafana.com/blog/tag/traces/
- title: ''
  type: Getting Started
  url: https://grafana.com/docs/tempo/latest/getting-started/
- title: ''
  type: OpenAPI
  url: openapi/tempo-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/tempo-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tempo-trace-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/tempo-trace-structure.json
- title: ''
  type: SpectralRules
  url: rules/tempo-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/distributed-tracing.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tempo-vocabulary.yml
created: '2026-03-25'
description: Tempo is an open source, high-scale distributed tracing backend from Grafana Labs. Designed for cost-efficient, object storage-backed trace storage with minimal operational overhead. Integrates with popular open telemetry standards including OpenTelemetry, Jaeger, Zipkin, and W3C Trace Context. Provides HTTP query APIs for trace retrieval, search, tag discovery, and metrics generation.
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Tempo Context
  property_count: 14
  slug: tempo-context
layout: provider
modified: '2026-05-03'
name: Tempo
rules:
- name: Tempo API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: tempo-rules
skills: []
slug: tempo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tempo\ndescription: >-\n  Tempo is an open source, high-scale distributed tracing backend from Grafana Labs.\n  Designed for cost-efficient, object storage-backed trace storage with minimal operational\n  overhead. Integrates with popular open telemetry standards including OpenTelemetry,\n  Jaeger, Zipkin, and W3C Trace Context. Provides HTTP query APIs for trace retrieval,\n  search, tag discovery, and metrics generation.\nurl: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Distributed Tracing\n  - Observability\n  - OpenTelemetry\n  - Grafana\n  - Monitoring\n\napis:\n  - name: Tempo HTTP API\n    description: >-\n      Tempo exposes an HTTP API for querying traces, searching spans, discovering\n      tag keys and values, and generating metrics from trace data. The API is compatible\n      with Jaeger and Zipkin query protocols in addition to the\
  \ native Tempo protocol.\n      Used by Grafana dashboards, the Tempo CLI, and external integrations.\n    humanURL: https://grafana.com/docs/tempo/latest/api_docs/\n    baseURL: http://localhost:3200\n    tags:\n      - Distributed Tracing\n      - Observability\n      - Trace Querying\n      - OpenTelemetry\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/tempo/latest/api_docs/\n      - type: GitHub Repository\n        url: https://github.com/grafana/tempo\n      - type: OpenAPI\n        url: openapi/tempo-openapi.yml\n\n  - name: Tempo TraceQL API\n    description: >-\n      TraceQL is a query language developed for Grafana Tempo that allows filtering\n      and selecting spans within traces. The TraceQL search API endpoint enables\n      rich span-level filtering using a pipeline syntax with attribute matchers,\n      duration filters, and structural operators.\n    humanURL: https://grafana.com/docs/tempo/latest/traceql/\n    baseURL: http://localhost:3200\n\
  \    tags:\n      - Distributed Tracing\n      - Query Language\n      - TraceQL\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/tempo/latest/traceql/\n      - type: Reference\n        url: https://grafana.com/docs/tempo/latest/traceql/query-editor/\n\ncommon:\n  - type: Website\n    url: https://grafana.com/oss/tempo/\n  - type: Documentation\n    url: https://grafana.com/docs/tempo/latest/\n  - type: GitHub Repository\n    url: https://github.com/grafana/tempo\n  - type: GitHub Organization\n    url: https://github.com/grafana\n  - type: Helm Chart\n    url: https://grafana.github.io/helm-charts\n  - type: Docker Hub\n    url: https://hub.docker.com/r/grafana/tempo\n  - type: Release Notes\n    url: https://github.com/grafana/tempo/releases\n  - type: Community\n    url: https://community.grafana.com/c/grafana-tempo/\n  - type: Slack\n    url: https://grafana.slack.com/archives/C01BULREPHA\n  - type: Blog\n    url: https://grafana.com/blog/tag/traces/\n\
  \  - type: Getting Started\n    url: https://grafana.com/docs/tempo/latest/getting-started/\n  - type: OpenAPI\n    url: openapi/tempo-openapi.yml\n  - type: JSON-LD\n    url: json-ld/tempo-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tempo-trace-schema.json\n  - type: JSONStructure\n    url: json-structure/tempo-trace-structure.json\n  - type: SpectralRules\n    url: rules/tempo-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/distributed-tracing.yaml\n  - type: Vocabulary\n    url: vocabulary/tempo-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Observability
- OpenTelemetry
- Grafana
- Monitoring
url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/apis.yml
use_cases: []
---
