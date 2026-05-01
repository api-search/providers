---
api_count: 5
api_specs:
- filename: etcd-http-gateway-openapi.yml
  format: yaml
  label: etcd HTTP Gateway API
  slug: etcd-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/etcd/refs/heads/main/openapi/etcd-http-gateway-openapi.yml
apis:
- description: The etcd v3 API is a gRPC-based interface providing key-value operations (put, get, delete, range), watch streams for change notifications, lease management for TTL-based keys, cluster membership mana
  name: etcd gRPC API
  slug: etcd-grpc-api
- description: 'etcd provides an HTTP/JSON gateway that translates HTTP requests into gRPC calls, allowing clients without gRPC support to interact with etcd. The gateway supports the same operations as the gRPC API '
  name: etcd HTTP Gateway API
  slug: etcd-http-api
- description: The etcd concurrency API provides distributed primitives built on top of the core key-value store, including distributed mutexes (locks), leader election, and software transactional memory (STM). Thes
  name: etcd Concurrency API
  slug: etcd-concurrency-api
- description: etcd exposes a Prometheus-compatible metrics endpoint that provides operational insights into the etcd cluster, including request rates, latency histograms, disk I/O statistics, Raft state, and cluste
  name: etcd Metrics API
  slug: etcd-metrics-api
- description: The original etcd v2 API exposed a RESTful HTTP interface for key-value operations using a hierarchical directory structure. This API has been deprecated in favor of the v3 gRPC API and was removed fr
  name: etcd v2 HTTP API
  slug: etcd-v2-api
common:
- title: ''
  type: JSONSchema
  url: json-schema/etcd-key-value-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/etcd-context.jsonld
- title: ''
  type: Website
  url: https://etcd.io
- title: ''
  type: Documentation
  url: https://etcd.io/docs/
- title: ''
  type: Getting Started
  url: https://etcd.io/docs/v3.5/quickstart/
- title: ''
  type: GitHub Organization
  url: https://github.com/etcd-io
- title: ''
  type: GitHubRepository
  url: https://github.com/etcd-io/etcd
- title: ''
  type: Blog
  url: https://etcd.io/blog/
- title: ''
  type: Community
  url: https://etcd.io/community/
- title: ''
  type: Change Log
  url: https://github.com/etcd-io/etcd/blob/main/CHANGELOG/
- title: ''
  type: Security
  url: https://github.com/etcd-io/etcd/blob/main/security/SECURITY.md
- title: ''
  type: Support
  url: https://etcd.io/community/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/etcd
created: '2026-03-16'
description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-based TTLs, and atomic compare-and-swap transactions. etcd is designed for high availability and stores critical configuration data for distributed systems.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Etcd Context
  property_count: 9
  slug: etcd-context
layout: provider
modified: '2026-04-28'
name: Etcd
skills: []
slug: etcd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: etcd\nname: Etcd\ndescription: >-\n  etcd is a CNCF graduated distributed, reliable key-value store used as\n  the backing store for all Kubernetes cluster data. It provides strong\n  consistency guarantees using the Raft consensus algorithm, supporting\n  watch operations, lease-based TTLs, and atomic compare-and-swap\n  transactions. etcd is designed for high availability and stores critical\n  configuration data for distributed systems.\nurl: https://etcd.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Consensus\n  - Distributed Systems\n  - Graduated\n  - Key-Value Store\n  - Kubernetes\ncreated: '2026-03-16'\nmodified: '2026-04-28'\n\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: etcd:etcd-grpc-api\n    name: etcd gRPC API\n    description: >-\n      The etcd v3 API is a gRPC-based interface providing key-value operations\n      (put, get, delete, range), watch streams for change notifications,\n\
  \      lease management for TTL-based keys, cluster membership management,\n      maintenance operations including snapshots and defragmentation, and\n      authentication and authorization controls.\n    humanURL: https://etcd.io/docs/v3.5/learning/api/\n    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/v3.5/learning/api/\n      - type: Reference\n        url: https://etcd.io/docs/v3.5/learning/api_guarantees/\n      - type: Authentication\n        url: https://etcd.io/docs/v3.5/op-guide/authentication/\n      - type: Getting Started\n        url: https://etcd.io/docs/v3.5/dev-guide/interacting_v3/\n      - type: Client Libraries\n        url: https://etcd.io/docs/v3.5/integrations/\n    tags:\n      - Cluster Management\n      - gRPC\n      - Key-Value\n      - Lease\n      - Watch\n  - aid: etcd:etcd-http-api\n    name: etcd HTTP Gateway API\n    description: >-\n      etcd provides an HTTP/JSON gateway that translates HTTP requests into\n      gRPC calls,\
  \ allowing clients without gRPC support to interact with etcd.\n      The gateway supports the same operations as the gRPC API including\n      key-value operations, watches, and cluster management through a RESTful\n      interface.\n    humanURL: https://etcd.io/docs/v3.5/dev-guide/api_grpc_gateway/\n    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/v3.5/dev-guide/api_grpc_gateway/\n      - type: Reference\n        url: https://etcd.io/docs/v3.5/dev-guide/api_grpc_gateway/\n      - type: OpenAPI\n        url: openapi/etcd-http-gateway-openapi.yml\n    tags:\n      - Gateway\n      - gRPC\n      - HTTP\n      - REST\n  - aid: etcd:etcd-concurrency-api\n    name: etcd Concurrency API\n    description: >-\n      The etcd concurrency API provides distributed primitives built on top of\n      the core key-value store, including distributed mutexes (locks), leader\n      election, and software transactional memory (STM). These primitives are\n      used to coordinate\
  \ between distributed processes and implement consensus\n      patterns in clustered applications.\n    humanURL: https://etcd.io/docs/v3.5/dev-guide/api_concurrency_reference_v3/\n    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/v3.5/dev-guide/api_concurrency_reference_v3/\n      - type: Reference\n        url: https://etcd.io/docs/v3.5/dev-guide/api_concurrency_reference_v3/\n    tags:\n      - Concurrency\n      - Coordination\n      - Distributed Locking\n      - Leader Election\n  - aid: etcd:etcd-metrics-api\n    name: etcd Metrics API\n    description: >-\n      etcd exposes a Prometheus-compatible metrics endpoint that provides\n      operational insights into the etcd cluster, including request rates,\n      latency histograms, disk I/O statistics, Raft state, and cluster health\n      indicators. This endpoint is used for monitoring and alerting in\n      production etcd deployments.\n    humanURL: https://etcd.io/docs/v3.5/op-guide/monitoring/\n\
  \    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/v3.5/op-guide/monitoring/\n      - type: Reference\n        url: https://etcd.io/docs/v3.5/metrics/\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n      - Prometheus\n  - aid: etcd:etcd-v2-api\n    name: etcd v2 HTTP API\n    description: >-\n      The original etcd v2 API exposed a RESTful HTTP interface for key-value\n      operations using a hierarchical directory structure. This API has been\n      deprecated in favor of the v3 gRPC API and was removed from the default\n      etcd build in later versions. Existing users should migrate to the v3 API.\n    humanURL: https://etcd.io/docs/v2.3/api/\n    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/v2.3/api/\n      - type: Deprecation Notice\n        url: https://etcd.io/docs/v3.5/op-guide/v2-migration/\n      - type: Migration Guide\n        url: https://etcd.io/docs/v3.5/op-guide/v2-migration/\n    tags:\n\
  \      - Deprecated\n      - HTTP\n      - Key-Value\n      - REST\ncommon:\n  - type: JSONSchema\n    url: json-schema/etcd-key-value-schema.json\n  - type: JSON-LD\n    url: json-ld/etcd-context.jsonld\n  - type: Website\n    name: etcd Website\n    description: Official etcd project website.\n    url: https://etcd.io\n  - type: Documentation\n    name: etcd Documentation\n    description: Official etcd documentation.\n    url: https://etcd.io/docs/\n  - type: Getting Started\n    name: etcd Getting Started\n    description: Guide to installing and using etcd for the first time.\n    url: https://etcd.io/docs/v3.5/quickstart/\n  - type: GitHub Organization\n    name: etcd GitHub Organization\n    description: Source code and related repositories for the etcd project.\n    url: https://github.com/etcd-io\n  - type: GitHubRepository\n    name: etcd GitHub Repository\n    description: Main etcd source code repository.\n    url: https://github.com/etcd-io/etcd\n  - type: Blog\n    name:\
  \ etcd Blog\n    description: Project blog and announcements.\n    url: https://etcd.io/blog/\n  - type: Community\n    name: etcd Community\n    description: Community resources and contribution guidelines for the etcd project.\n    url: https://etcd.io/community/\n  - type: Change Log\n    name: etcd Changelog\n    description: Release notes and version history for etcd.\n    url: https://github.com/etcd-io/etcd/blob/main/CHANGELOG/\n  - type: Security\n    name: etcd Security\n    description: Security disclosure policy and advisories for etcd.\n    url: https://github.com/etcd-io/etcd/blob/main/security/SECURITY.md\n  - type: Support\n    name: etcd Support\n    description: Community support channels including mailing lists and Slack.\n    url: https://etcd.io/community/\n  - type: Stack Overflow\n    name: etcd Stack Overflow\n    description: etcd-tagged questions and answers on Stack Overflow.\n    url: https://stackoverflow.com/questions/tagged/etcd\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/etcd/refs/heads/main/apis.yml
tags:
- Cloud Native
- Consensus
- Distributed Systems
- Graduated
- Key-Value Store
- Kubernetes
url: https://etcd.io
use_cases: []
---
