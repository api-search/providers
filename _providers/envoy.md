---
api_count: 5
api_specs:
- filename: envoy-admin-api-openapi.yml
  format: yaml
  label: Envoy Admin API
  slug: envoy-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/openapi/envoy-admin-api-openapi.yml
- filename: envoy-ai-gateway-openapi.yml
  format: yaml
  label: Envoy AI Gateway API
  slug: envoy-ai-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/openapi/envoy-ai-gateway-openapi.yml
apis:
- description: The Envoy Admin API provides local administrative access to a running Envoy proxy instance, exposing endpoints for inspecting clusters, listeners, configuration, statistics, health status, and runtime
  name: Envoy Admin API
  slug: envoy-admin-api
- description: 'The xDS (x Discovery Service) APIs provide dynamic configuration for Envoy proxies via a management server, including LDS, RDS, CDS, EDS, SDS, and ADS. xDS APIs are served over gRPC or REST and allow '
  name: Envoy xDS APIs
  slug: envoy-xds-api
- description: The Envoy API v3 is the current stable protobuf-based configuration and extension API for Envoy proxy. It defines the configuration types for all Envoy subsystems including listeners, clusters, routes
  name: Envoy API V3
  slug: envoy-api-v3
- description: Envoy Gateway manages Envoy Proxy as a standalone or Kubernetes-based application gateway, implementing and extending the Kubernetes Gateway API. It provides Gateway API extensions including BackendTr
  name: Envoy Gateway API
  slug: envoy-gateway-api
- description: The Envoy AI Gateway manages unified access to Generative AI services built on Envoy Gateway. It provides OpenAI-compatible and Anthropic-compatible API endpoints for routing LLM traffic across multip
  name: Envoy AI Gateway API
  slug: envoy-ai-gateway-api
common:
- title: ''
  type: Website
  url: https://www.envoyproxy.io/
- title: ''
  type: Documentation
  url: https://www.envoyproxy.io/docs/envoy/latest/
- title: ''
  type: Getting Started
  url: https://www.envoyproxy.io/docs/envoy/latest/start/start
- title: ''
  type: Blog
  url: https://blog.envoyproxy.io/
- title: ''
  type: Change Log
  url: https://github.com/envoyproxy/envoy/releases
- title: ''
  type: GitHub Organization
  url: https://github.com/envoyproxy
- title: ''
  type: GitHubRepository
  url: https://github.com/envoyproxy/envoy
- title: ''
  type: Community
  url: https://www.envoyproxy.io/community
- title: ''
  type: JSONSchema
  url: json-schema/envoy-bootstrap.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-cluster.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-listener.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-route-configuration.json
- title: ''
  type: JSON-LD
  url: json-ld/envoy-context.jsonld
created: '2025-01-01'
description: Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the data plane for many service mesh implementations including Istio.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Envoy Context
  property_count: 10
  slug: envoy-context
layout: provider
modified: '2026-04-28'
name: Envoy
skills: []
slug: envoy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: envoy\nname: Envoy\ndescription: >-\n  Envoy is a high-performance, open-source edge and service proxy designed for\n  cloud-native applications and microservice architectures. It provides advanced\n  load balancing, observability, and traffic management features, and serves as\n  the data plane for many service mesh implementations including Istio.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Load Balancing\n  - Proxy\n  - Service Mesh\nurl: https://www.envoyproxy.io/\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: envoy:envoy-admin-api\n    name: Envoy Admin API\n    description: >-\n      The Envoy Admin API provides local administrative access to a running\n      Envoy proxy instance, exposing endpoints for inspecting clusters, listeners,\n      configuration, statistics, health status, and runtime settings.\n\
  \    humanURL: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n    tags:\n      - Admin\n      - Management\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n      - type: OpenAPI\n        url: openapi/envoy-admin-api-openapi.yml\n  - aid: envoy:envoy-xds-api\n    name: Envoy xDS APIs\n    description: >-\n      The xDS (x Discovery Service) APIs provide dynamic configuration for Envoy\n      proxies via a management server, including LDS, RDS, CDS, EDS, SDS, and ADS.\n      xDS APIs are served over gRPC or REST and allow management servers to push\n      Listener, Route, Cluster, Endpoint, and Secret configurations to Envoy\n      proxies at runtime without restarts.\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol\n    tags:\n      - Discovery Service\n      - Dynamic Configuration\n      - gRPC\n      - xDS\n    properties:\n      - type: Documentation\n\
  \        url: https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol\n      - type: Reference\n        url: https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/xds_api\n      - type: GitHubRepository\n        url: https://github.com/envoyproxy/envoy\n  - aid: envoy:envoy-api-v3\n    name: Envoy API V3\n    description: >-\n      The Envoy API v3 is the current stable protobuf-based configuration and\n      extension API for Envoy proxy. It defines the configuration types for all\n      Envoy subsystems including listeners, clusters, routes, endpoints, HTTP\n      filters, network filters, transport sockets, and access logging. The API\n      is defined using Protocol Buffers and published in the envoy-api repository.\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api/api\n    tags:\n      - Configuration\n      - Extensions\n      - Filters\n      - Protobuf\n    properties:\n      - type: Documentation\n        url: https://www.envoyproxy.io/docs/envoy/latest/api/api\n\
  \      - type: GitHubRepository\n        url: https://github.com/envoyproxy/envoy\n      - type: JSONSchema\n        url: json-schema/envoy-cluster.json\n      - type: JSONSchema\n        url: json-schema/envoy-listener.json\n      - type: JSONSchema\n        url: json-schema/envoy-route-configuration.json\n  - aid: envoy:envoy-gateway-api\n    name: Envoy Gateway API\n    description: >-\n      Envoy Gateway manages Envoy Proxy as a standalone or Kubernetes-based\n      application gateway, implementing and extending the Kubernetes Gateway API.\n      It provides Gateway API extensions including BackendTrafficPolicy,\n      ClientTrafficPolicy, SecurityPolicy, and EnvoyPatchPolicy for advanced\n      traffic management without requiring direct Envoy configuration knowledge.\n    humanURL: https://gateway.envoyproxy.io/\n    tags:\n      - Cloud Native\n      - Gateway\n      - Kubernetes\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://gateway.envoyproxy.io/docs/\n\
  \      - type: Reference\n        url: https://gateway.envoyproxy.io/docs/concepts/gateway-api/\n      - type: Getting Started\n        url: https://gateway.envoyproxy.io/docs/\n      - type: GitHubRepository\n        url: https://github.com/envoyproxy/gateway\n  - aid: envoy:envoy-ai-gateway-api\n    name: Envoy AI Gateway API\n    description: >-\n      The Envoy AI Gateway manages unified access to Generative AI services\n      built on Envoy Gateway. It provides OpenAI-compatible and\n      Anthropic-compatible API endpoints for routing LLM traffic across multiple\n      AI backends with backend rate limiting, policy control, and security\n      configuration via Kubernetes custom resources.\n    humanURL: https://aigateway.envoyproxy.io/\n    tags:\n      - AI\n      - Cloud Native\n      - Gateway\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://aigateway.envoyproxy.io/docs/\n      - type: Reference\n        url: https://aigateway.envoyproxy.io/docs/api/\n\
  \      - type: Getting Started\n        url: https://aigateway.envoyproxy.io/docs/getting-started/basic-usage/\n      - type: GitHubRepository\n        url: https://github.com/envoyproxy/ai-gateway\n      - type: Change Log\n        url: https://aigateway.envoyproxy.io/release-notes/\n      - type: OpenAPI\n        url: openapi/envoy-ai-gateway-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.envoyproxy.io/\n  - type: Documentation\n    url: https://www.envoyproxy.io/docs/envoy/latest/\n  - type: Getting Started\n    url: https://www.envoyproxy.io/docs/envoy/latest/start/start\n  - type: Blog\n    url: https://blog.envoyproxy.io/\n  - type: Change Log\n    url: https://github.com/envoyproxy/envoy/releases\n  - type: GitHub Organization\n    url: https://github.com/envoyproxy\n  - type: GitHubRepository\n    url: https://github.com/envoyproxy/envoy\n  - type: Community\n    url: https://www.envoyproxy.io/community\n  - type: JSONSchema\n    url: json-schema/envoy-bootstrap.json\n\
  \  - type: JSONSchema\n    url: json-schema/envoy-cluster.json\n  - type: JSONSchema\n    url: json-schema/envoy-listener.json\n  - type: JSONSchema\n    url: json-schema/envoy-route-configuration.json\n  - type: JSON-LD\n    url: json-ld/envoy-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/apis.yml
tags:
- Cloud Native
- Load Balancing
- Proxy
- Service Mesh
url: https://www.envoyproxy.io/
use_cases: []
---
