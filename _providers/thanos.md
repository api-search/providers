---
api_count: 6
api_specs:
- filename: thanos-query-api.yml
  format: yaml
  label: Thanos Query API
  slug: thanos-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-query-api.yml
- filename: thanos-store-gateway-openapi.yml
  format: yaml
  label: Thanos Store Gateway API
  slug: thanos-store-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-store-gateway-openapi.yml
- filename: thanos-sidecar-openapi.yml
  format: yaml
  label: Thanos Sidecar API
  slug: thanos-sidecar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-sidecar-openapi.yml
- filename: thanos-ruler-openapi.yml
  format: yaml
  label: Thanos Ruler API
  slug: thanos-ruler-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-ruler-openapi.yml
- filename: thanos-receive-openapi.yml
  format: yaml
  label: Thanos Receive API
  slug: thanos-receive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-receive-openapi.yml
- filename: thanos-compact-openapi.yml
  format: yaml
  label: Thanos Compact API
  slug: thanos-compact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-compact-openapi.yml
apis:
- description: Prometheus-compatible HTTP API for querying metrics across multiple Prometheus servers and long-term storage backends with global query view, deduplication, and partial response support.
  name: Thanos Query API
  slug: thanos-query-api
- description: gRPC-based Store API that serves metrics stored in object storage buckets, allowing Thanos Querier to access historical time series data from long-term storage backends such as S3, GCS, and Azure Blob
  name: Thanos Store Gateway API
  slug: thanos-store-gateway-api
- description: Component deployed alongside a Prometheus instance that implements the Thanos Store API on top of Prometheus remote-read API, enabling Queriers to access real-time Prometheus data and optionally uploa
  name: Thanos Sidecar API
  slug: thanos-sidecar-api
- description: Component that evaluates Prometheus recording and alerting rules against the Thanos Query API, exposes results as metrics via a Store API endpoint, and optionally uploads rule evaluation blocks to obj
  name: Thanos Ruler API
  slug: thanos-ruler-api
- description: Implements the Prometheus Remote Write API to accept metrics pushed from Prometheus instances, storing them in a local TSDB and optionally uploading blocks to object storage for long-term retention an
  name: Thanos Receive API
  slug: thanos-receive-api
- description: Singleton process that applies Prometheus compaction procedures to block data stored in object storage, performing downsampling and retention policy enforcement to reduce storage costs and improve que
  name: Thanos Compact API
  slug: thanos-compact-api
capabilities:
- description: Unified metrics and observability capability for SRE, platform engineers, and monitoring teams. Composes Thanos Query API to provide PromQL-based metric queries, long-term trend analysis, alert monito
  name: Thanos Metrics and Observability
  slug: metrics-observability
common:
- title: ''
  type: Website
  url: https://thanos.io/
- title: ''
  type: JSON-LD
  url: json-ld/thanos-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/query-response.json
- title: ''
  type: JSONSchema
  url: json-schema/store-info.json
- title: ''
  type: JSONStructure
  url: json-structure/thanos-query-structure.json
- title: ''
  type: SpectralRules
  url: rules/thanos-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/thanos-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/metrics-observability.yaml
- title: ''
  type: Getting Started
  url: https://thanos.io/tip/thanos/getting-started.md/
- title: ''
  type: Documentation
  url: https://thanos.io/tip/
- title: ''
  type: GitHubRepository
  url: https://github.com/thanos-io/thanos
- title: ''
  type: GitHub Organization
  url: https://github.com/thanos-io
- title: ''
  type: Community
  url: https://thanos.io/tip/contributing/community.md/
- title: ''
  type: Troubleshooting
  url: https://thanos.io/tip/operating/troubleshooting.md/
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2025'
description: Open-source, highly available Prometheus setup with long-term storage capabilities that provides a global query view across multiple Prometheus servers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Thanos Context
  property_count: 10
  slug: thanos-context
layout: provider
modified: '2026-05-03'
name: Thanos
rules:
- name: Thanos API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 7
  slug: thanos-rules
skills: []
slug: thanos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thanos\nname: Thanos\ndescription: >-\n  Open-source, highly available Prometheus setup with long-term storage\n  capabilities that provides a global query view across multiple Prometheus\n  servers.\nurl: https://thanos.io/\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Metrics\n  - Monitoring\n  - Observability\n  - Prometheus\n  - Time Series Database\ncreated: '2025'\nmodified: '2026-05-03'\ntype: Index\napis:\n  - aid: thanos:thanos-query-api\n    name: Thanos Query API\n    description: >-\n      Prometheus-compatible HTTP API for querying metrics across multiple\n      Prometheus servers and long-term storage backends with global query\n      view, deduplication, and partial response support.\n    humanURL: https://thanos.io/tip/components/query.md/\n    baseURL: http://localhost:9090\n    tags:\n      - Metrics\n      - Monitoring\n      - PromQL\n      - Query\n      - Time Series\n    properties:\n      - url: https://thanos.io/tip/components/query.md/\n\
  \        type: Documentation\n      - url: openapi/thanos-query-api.yml\n        type: OpenAPI\n      - url: json-schema/query-response.json\n        type: JSONSchema\n      - url: json-schema/store-info.json\n        type: JSONSchema\n      - url: json-ld/thanos-context.jsonld\n        type: JSONLD\n  - aid: thanos:thanos-store-gateway-api\n    name: Thanos Store Gateway API\n    description: >-\n      gRPC-based Store API that serves metrics stored in object storage buckets,\n      allowing Thanos Querier to access historical time series data from long-term\n      storage backends such as S3, GCS, and Azure Blob Storage.\n    humanURL: https://thanos.io/tip/components/store.md/\n    baseURL: http://localhost:10902\n    tags:\n      - Metrics\n      - Monitoring\n      - Object Storage\n      - Store\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://thanos.io/tip/components/store.md/\n      - type: OpenAPI\n        url: openapi/thanos-store-gateway-openapi.yml\n\
  \  - aid: thanos:thanos-sidecar-api\n    name: Thanos Sidecar API\n    description: >-\n      Component deployed alongside a Prometheus instance that implements the\n      Thanos Store API on top of Prometheus remote-read API, enabling Queriers\n      to access real-time Prometheus data and optionally uploading blocks to\n      object storage.\n    humanURL: https://thanos.io/tip/components/sidecar.md/\n    baseURL: http://localhost:10902\n    tags:\n      - Metrics\n      - Monitoring\n      - Prometheus\n      - Sidecar\n      - Store\n    properties:\n      - type: Documentation\n        url: https://thanos.io/tip/components/sidecar.md/\n      - type: OpenAPI\n        url: openapi/thanos-sidecar-openapi.yml\n  - aid: thanos:thanos-ruler-api\n    name: Thanos Ruler API\n    description: >-\n      Component that evaluates Prometheus recording and alerting rules against\n      the Thanos Query API, exposes results as metrics via a Store API endpoint,\n      and optionally uploads rule\
  \ evaluation blocks to object storage.\n    humanURL: https://thanos.io/tip/components/rule.md/\n    baseURL: http://localhost:10902\n    tags:\n      - Alerting\n      - Metrics\n      - Monitoring\n      - Prometheus\n      - Rules\n    properties:\n      - type: Documentation\n        url: https://thanos.io/tip/components/rule.md/\n      - type: OpenAPI\n        url: openapi/thanos-ruler-openapi.yml\n  - aid: thanos:thanos-receive-api\n    name: Thanos Receive API\n    description: >-\n      Implements the Prometheus Remote Write API to accept metrics pushed from\n      Prometheus instances, storing them in a local TSDB and optionally uploading\n      blocks to object storage for long-term retention and horizontal scalability.\n    humanURL: https://thanos.io/tip/components/receive.md/\n    baseURL: http://localhost:10902\n    tags:\n      - Metrics\n      - Monitoring\n      - Receive\n      - Remote Write\n      - Time Series\n    properties:\n      - type: Documentation\n       \
  \ url: https://thanos.io/tip/components/receive.md/\n      - type: OpenAPI\n        url: openapi/thanos-receive-openapi.yml\n  - aid: thanos:thanos-compact-api\n    name: Thanos Compact API\n    description: >-\n      Singleton process that applies Prometheus compaction procedures to block\n      data stored in object storage, performing downsampling and retention policy\n      enforcement to reduce storage costs and improve query performance over long\n      time ranges.\n    humanURL: https://thanos.io/tip/components/compact.md/\n    baseURL: http://localhost:10902\n    tags:\n      - Compaction\n      - Downsampling\n      - Monitoring\n      - Object Storage\n      - Retention\n    properties:\n      - type: Documentation\n        url: https://thanos.io/tip/components/compact.md/\n      - type: OpenAPI\n        url: openapi/thanos-compact-openapi.yml\ncommon:\n  - url: https://thanos.io/\n    type: Website\n  - url: json-ld/thanos-context.jsonld\n    type: JSON-LD\n  - url: json-schema/query-response.json\n\
  \    type: JSONSchema\n  - url: json-schema/store-info.json\n    type: JSONSchema\n  - url: json-structure/thanos-query-structure.json\n    type: JSONStructure\n  - url: rules/thanos-rules.yml\n    type: SpectralRules\n  - url: vocabulary/thanos-vocabulary.yml\n    type: Vocabulary\n  - url: capabilities/metrics-observability.yaml\n    type: NaftikoCapability\n  - url: https://thanos.io/tip/thanos/getting-started.md/\n    type: Getting Started\n  - url: https://thanos.io/tip/\n    type: Documentation\n  - url: https://github.com/thanos-io/thanos\n    type: GitHubRepository\n  - url: https://github.com/thanos-io\n    type: GitHub Organization\n  - url: https://thanos.io/tip/contributing/community.md/\n    type: Community\n  - url: https://thanos.io/tip/operating/troubleshooting.md/\n    type: Troubleshooting\n  - url: https://www.apache.org/licenses/LICENSE-2.0\n    type: License\nmaintainers:\n  - FN: Kin Lane\n    url: http://apievangelist.com\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/apis.yml
tags:
- Metrics
- Monitoring
- Observability
- Prometheus
- Time Series Database
url: https://thanos.io/
use_cases: []
---
