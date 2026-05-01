---
api_count: 9
api_specs:
- filename: envoy-proxy-admin-api-openapi.yml
  format: yaml
  label: Envoy Proxy Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/openapi/envoy-proxy-admin-api-openapi.yml
- filename: envoy-proxy-xds-discovery-api-openapi.yml
  format: yaml
  label: Envoy Proxy xDS Discovery API
  slug: xds-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/openapi/envoy-proxy-xds-discovery-api-openapi.yml
apis:
- description: 'The Envoy Proxy Administration Interface provides a local HTTP-based management API for querying and modifying various aspects of the Envoy server at runtime. It serves as a critical operational tool '
  name: Envoy Proxy Admin API
  slug: admin-api
- description: The Envoy xDS (x Discovery Service) REST API provides endpoints for dynamically discovering and configuring Envoy proxy resources including clusters (CDS), listeners (LDS), routes (RDS), endpoints (ED
  name: Envoy Proxy xDS Discovery API
  slug: xds-discovery-api
- description: The Envoy Rate Limit Service (RLS) is a gRPC-based API that allows Envoy to delegate rate limiting decisions to an external service. When a request matches a configured rate limit rule, Envoy calls th
  name: Envoy Proxy Rate Limit Service API
  slug: rate-limit-service-api
- description: The Envoy Health Discovery Service (HDS) is a gRPC-based API that enables a management server to instruct Envoy to perform health checks on behalf of the control plane and report results back. This al
  name: Envoy Proxy Health Discovery Service API
  slug: health-discovery-service-api
- description: The Envoy gRPC Access Log Service (ALS) API provides a streaming gRPC interface for receiving access log entries from Envoy instances in real time. It enables centralized log aggregation by allowing E
  name: Envoy Proxy gRPC Access Log Service API
  slug: access-log-service-api
- description: The Envoy External Processing API is a gRPC-based service that enables an external server to inspect and modify HTTP requests and responses as they pass through Envoy. This extensibility mechanism sup
  name: Envoy Proxy External Processing API
  slug: external-processing-api
- description: The Envoy External Authorization API provides a gRPC or HTTP interface for delegating authorization decisions to an external service. When a request arrives, Envoy calls the ext_authz service, which c
  name: Envoy Proxy External Authorization API
  slug: external-authorization-api
- description: The Envoy Metrics Service API is a gRPC-based interface for streaming Envoy's statistics and metrics to a remote metrics collection service. It allows operators to centralize telemetry data from multi
  name: Envoy Proxy Metrics Service API
  slug: metrics-service-api
- description: The Envoy Tap Service API provides a mechanism for intercepting and recording HTTP and TCP traffic passing through Envoy. The tap filter matches requests and responses based on configurable conditions
  name: Envoy Proxy Tap Service API
  slug: tap-service-api
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
  type: Security
  url: https://github.com/envoyproxy/envoy/blob/main/SECURITY.md
- title: ''
  type: JSON-LD
  url: json-ld/envoy-proxy-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/envoy-proxy-cluster.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-proxy-listener.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-proxy-route.json
- title: ''
  type: JSONSchema
  url: json-schema/envoy-proxy-endpoint.json
- title: ''
  type: Issue Tracker
  url: https://github.com/envoyproxy/envoy/issues
- title: ''
  type: Community
  url: https://envoyslack.cncf.io/
- title: ''
  type: Community
  url: https://www.cncf.io/projects/envoy/
- title: ''
  type: Reference
  url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/api
created: '2026-01-02'
description: Envoy Proxy is an open-source edge and service proxy that is designed for cloud-native applications. It acts as a gateway for all incoming and outgoing traffic within a microservices architecture, providing functionalities such as load balancing, service discovery, encryption, authentication, and observability. Envoy Proxy is known for its high performance and low latency, making it a popular choice for companies seeking to optimize their network traffic and improve overall system efficiency.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Envoy Proxy Context
  property_count: 10
  slug: envoy-proxy-context
layout: provider
modified: '2026-04-28'
name: Envoy Proxy
skills: []
slug: envoy-proxy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: envoy-proxy\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/apis.yml\napis:\n  - aid: envoy-proxy:admin-api\n    name: Envoy Proxy Admin API\n    tags:\n      - Gateways\n      - Proxies\n      - Service Mesh\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n    properties:\n      - url: openapi/envoy-proxy-admin-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n        type: Documentation\n      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n      - url: https://github.com/envoyproxy/envoy/releases\n        type: Change Log\n    description: >-\n      The Envoy Proxy Administration Interface provides a local HTTP-based\n      management API for querying and modifying various aspects of the Envoy\n      server at runtime. It serves as a critical operational tool for\n      monitoring, debugging, and managing Envoy\
  \ proxy instances including\n      statistics, clusters, listeners, certificates, runtime settings, logging,\n      and health checks.\n  - aid: envoy-proxy:xds-discovery-api\n    name: Envoy Proxy xDS Discovery API\n    tags:\n      - Discovery\n      - Gateways\n      - Proxies\n      - Service Mesh\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol\n    properties:\n      - url: openapi/envoy-proxy-xds-discovery-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/xds_api\n        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n    description: >-\n      The Envoy xDS (x Discovery Service) REST API provides endpoints for\n      dynamically discovering and configuring Envoy proxy resources including\n      clusters (CDS), listeners\
  \ (LDS), routes (RDS), endpoints (EDS), secrets\n      (SDS), and runtime configuration (RTDS). The xDS protocol is the\n      foundation of Envoy's dynamic configuration model, enabling control\n      planes to push configuration updates to Envoy instances without\n      requiring restarts.\n  - aid: envoy-proxy:rate-limit-service-api\n    name: Envoy Proxy Rate Limit Service API\n    tags:\n      - gRPC\n      - Proxies\n      - Rate Limiting\n      - Service Mesh\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/rate_limit_filter\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/rate_limit_filter\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/ratelimit/v3/rls.proto\n        type: Reference\n      - url: https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/other_features/global_rate_limiting\n        type: Documentation\n\
  \      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n    description: >-\n      The Envoy Rate Limit Service (RLS) is a gRPC-based API that allows Envoy\n      to delegate rate limiting decisions to an external service. When a request\n      matches a configured rate limit rule, Envoy calls the RLS to check whether\n      the request should be allowed or throttled based on descriptors extracted\n      from the request context.\n  - aid: envoy-proxy:health-discovery-service-api\n    name: Envoy Proxy Health Discovery Service API\n    tags:\n      - Discovery\n      - gRPC\n      - Health\n      - Proxies\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/health/v3/hds.proto\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/health/v3/hds.proto\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service\n        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n\
  \        type: GitHubRepository\n    description: >-\n      The Envoy Health Discovery Service (HDS) is a gRPC-based API that enables\n      a management server to instruct Envoy to perform health checks on behalf of\n      the control plane and report results back. This allows centralized health\n      state management across a fleet of Envoy instances without requiring the\n      control plane to perform health checks directly.\n  - aid: envoy-proxy:access-log-service-api\n    name: Envoy Proxy gRPC Access Log Service API\n    tags:\n      - Access Logs\n      - gRPC\n      - Observability\n      - Proxies\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/accesslog/v3/als.proto\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/accesslog/v3/als.proto\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service\n        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n\
  \        type: GitHubRepository\n    description: >-\n      The Envoy gRPC Access Log Service (ALS) API provides a streaming gRPC\n      interface for receiving access log entries from Envoy instances in real\n      time. It enables centralized log aggregation by allowing Envoy to stream\n      HTTP and TCP access logs to a remote endpoint rather than writing them\n      locally.\n  - aid: envoy-proxy:external-processing-api\n    name: Envoy Proxy External Processing API\n    tags:\n      - Extensibility\n      - gRPC\n      - Proxies\n      - Request Processing\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_proc_filter\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_proc_filter\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/ext_proc/v3/external_processor.proto\n        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n\
  \        type: GitHubRepository\n    description: >-\n      The Envoy External Processing API is a gRPC-based service that enables an\n      external server to inspect and modify HTTP requests and responses as they\n      pass through Envoy. This extensibility mechanism supports use cases such\n      as custom authentication, header manipulation, body transformation, and\n      dynamic routing decisions without requiring Envoy filter plugins.\n  - aid: envoy-proxy:external-authorization-api\n    name: Envoy Proxy External Authorization API\n    tags:\n      - Authorization\n      - gRPC\n      - Proxies\n      - Security\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/extensions/filters/http/ext_authz/v3/ext_authz.proto\n\
  \        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n    description: >-\n      The Envoy External Authorization API provides a gRPC or HTTP interface for\n      delegating authorization decisions to an external service. When a request\n      arrives, Envoy calls the ext_authz service, which can approve, deny, or\n      modify the request before it is forwarded to the upstream. This enables\n      policy-based access control enforced at the proxy layer.\n  - aid: envoy-proxy:metrics-service-api\n    name: Envoy Proxy Metrics Service API\n    tags:\n      - gRPC\n      - Metrics\n      - Observability\n      - Proxies\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/metrics/v3/metrics_service.proto\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/metrics/v3/metrics_service.proto\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service\n\
  \        type: Reference\n      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n    description: >-\n      The Envoy Metrics Service API is a gRPC-based interface for streaming\n      Envoy's statistics and metrics to a remote metrics collection service.\n      It allows operators to centralize telemetry data from multiple Envoy\n      instances, supporting integration with observability platforms for\n      monitoring proxy performance and traffic patterns.\n  - aid: envoy-proxy:tap-service-api\n    name: Envoy Proxy Tap Service API\n    tags:\n      - Debugging\n      - gRPC\n      - Proxies\n      - Traffic Capture\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/tap_filter\n    properties:\n      - url: https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/tap_filter\n        type: Documentation\n      - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/tap/v3/tap.proto\n     \
  \   type: Reference\n      - url: https://github.com/envoyproxy/envoy\n        type: GitHubRepository\n    description: >-\n      The Envoy Tap Service API provides a mechanism for intercepting and\n      recording HTTP and TCP traffic passing through Envoy. The tap filter\n      matches requests and responses based on configurable conditions and\n      streams the captured data to a sink such as a gRPC service or local file,\n      enabling debugging, auditing, and traffic analysis use cases.\nname: Envoy Proxy\ntags:\n  - Gateways\n  - Proxies\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.envoyproxy.io/\n    name: Website | Envoy Proxy\n    type: Website\n  - url: https://www.envoyproxy.io/docs/envoy/latest/\n    name: Documentation | Envoy Proxy\n    type: Documentation\n  - url: https://www.envoyproxy.io/docs/envoy/latest/start/start\n    name: Getting Started | Envoy Proxy\n    type:\
  \ Getting Started\n  - url: https://blog.envoyproxy.io/\n    name: Blog | Envoy Proxy\n    type: Blog\n  - url: https://github.com/envoyproxy/envoy/releases\n    name: Change Log | Envoy Proxy\n    type: Change Log\n  - url: https://github.com/envoyproxy\n    name: GitHub Organization | Envoy Proxy\n    type: GitHub Organization\n  - url: https://github.com/envoyproxy/envoy\n    name: GitHub Repository | Envoy Proxy\n    type: GitHubRepository\n  - url: https://www.envoyproxy.io/community\n    name: Community | Envoy Proxy\n    type: Community\n  - url: https://github.com/envoyproxy/envoy/blob/main/SECURITY.md\n    name: Security Policy | Envoy Proxy\n    type: Security\n  - url: json-ld/envoy-proxy-context.jsonld\n    name: JSON-LD Context | Envoy Proxy\n    type: JSON-LD\n  - url: json-schema/envoy-proxy-cluster.json\n    name: Cluster JSON Schema\n    type: JSONSchema\n  - url: json-schema/envoy-proxy-listener.json\n    name: Listener JSON Schema\n    type: JSONSchema\n  - url: json-schema/envoy-proxy-route.json\n\
  \    name: Route Configuration JSON Schema\n    type: JSONSchema\n  - url: json-schema/envoy-proxy-endpoint.json\n    name: Endpoint JSON Schema\n    type: JSONSchema\n  - url: https://github.com/envoyproxy/envoy/issues\n    name: Issue Tracker | Envoy Proxy\n    type: Issue Tracker\n  - url: https://envoyslack.cncf.io/\n    name: Slack Community | Envoy Proxy\n    type: Community\n  - url: https://www.cncf.io/projects/envoy/\n    name: CNCF Project | Envoy Proxy\n    type: Community\n  - url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/api\n    name: v3 API Reference | Envoy Proxy\n    type: Reference\ncreated: '2026-01-02'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Envoy Proxy is an open-source edge and service proxy that is designed for cloud-native\n  applications. It acts as a gateway for all incoming and outgoing traffic within\n  a microservices architecture, providing functionalities such as load balancing,\n  service discovery, encryption, authentication,\
  \ and observability. Envoy Proxy is\n  known for its high performance and low latency, making it a popular choice for companies\n  seeking to optimize their network traffic and improve overall system efficiency.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/apis.yml
tags:
- Gateways
- Proxies
url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/apis.yml
use_cases: []
---
