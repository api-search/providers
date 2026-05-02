---
api_count: 4
api_specs:
- filename: jaeger-query-api.yml
  format: yaml
  label: Jaeger Query API
  slug: jaeger-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jaeger/refs/heads/main/openapi/jaeger-query-api.yml
apis:
- description: The Jaeger Query API is an HTTP/JSON API exposed by the Jaeger Query service for retrieving distributed traces, listing services and operations, querying service dependency graphs, and accessing perfo
  name: Jaeger Query API
  slug: jaeger-query-api
- description: The Jaeger Collector API receives trace spans from instrumented applications and SDKs. Since Jaeger v1.11 the primary protocol is the jaeger.api_v2.CollectorService gRPC endpoint; the collector also a
  name: Jaeger Collector API
  slug: jaeger-collector-api
- description: The Jaeger Remote Storage API is a gRPC-based interface that allows extending Jaeger with custom storage backends. Any backend implementing this API can be deployed as a remote gRPC server and plugged
  name: Jaeger Remote Storage API
  slug: jaeger-remote-storage-api
- description: The Jaeger Remote Sampling API provides HTTP and gRPC endpoints that SDKs use to retrieve sampling strategies for distributed trace collection. It is implemented by the jaeger-collector and defined in
  name: Jaeger Remote Sampling API
  slug: jaeger-remote-sampling-api
common:
- title: ''
  type: Website
  url: https://www.jaegertracing.io/
- title: ''
  type: Documentation
  url: https://www.jaegertracing.io/docs/
- title: ''
  type: Getting Started
  url: https://www.jaegertracing.io/docs/latest/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/jaegertracing
- title: ''
  type: GitHubRepository
  url: https://github.com/jaegertracing/jaeger
- title: ''
  type: Blog
  url: https://www.jaegertracing.io/news/
- title: ''
  type: Community
  url: https://www.jaegertracing.io/get-involved/
- title: ''
  type: Support
  url: https://www.jaegertracing.io/get-in-touch/
- title: ''
  type: Change Log
  url: https://github.com/jaegertracing/jaeger/blob/main/CHANGELOG.md
- title: ''
  type: JSON-LD
  url: json-ld/jaeger-trace.yml
- title: ''
  type: JSONSchema
  url: json-schema/jaeger-trace.yml
created: '2025-01-01'
description: Jaeger is an open source, end-to-end distributed tracing system for monitoring and troubleshooting microservices-based architectures. Jaeger provides visibility into distributed system behavior through trace collection, storage, and visualization.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Jaeger
skills: []
slug: jaeger
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jaeger\nname: Jaeger\ndescription: >-\n  Jaeger is an open source, end-to-end distributed tracing system for\n  monitoring and troubleshooting microservices-based architectures. Jaeger\n  provides visibility into distributed system behavior through trace collection,\n  storage, and visualization.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Tracing\n  - Microservices\n  - Monitoring\n  - Observability\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/jaeger/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jaeger:jaeger-query-api\n    name: Jaeger Query API\n    description: >-\n      The Jaeger Query API is an HTTP/JSON API exposed by the Jaeger Query\n      service for retrieving distributed traces, listing services and operations,\n      querying service dependency graphs, and accessing performance metrics\n      including\
  \ latency, call rates, and error rates. A gRPC version of the\n      Query API is also available defined in the jaeger-idl query.proto IDL.\n    humanURL: https://www.jaegertracing.io/docs/latest/apis/\n    tags:\n      - Distributed Tracing\n      - Observability\n      - Query\n      - Traces\n    properties:\n      - type: Documentation\n        url: https://www.jaegertracing.io/docs/latest/apis/\n      - type: OpenAPI\n        url: openapi/jaeger-query-api.yml\n      - type: GitHubRepository\n        url: https://github.com/jaegertracing/jaeger\n      - type: Change Log\n        url: https://github.com/jaegertracing/jaeger/blob/main/CHANGELOG.md\n  - aid: jaeger:jaeger-collector-api\n    name: Jaeger Collector API\n    description: >-\n      The Jaeger Collector API receives trace spans from instrumented\n      applications and SDKs. Since Jaeger v1.11 the primary protocol is the\n      jaeger.api_v2.CollectorService gRPC endpoint; the collector also accepts\n      OTLP traces (binary\
  \ gRPC, Protobuf over HTTP, JSON over HTTP) since\n      v1.35, as well as legacy Thrift over UDP and HTTP formats.\n    humanURL: https://www.jaegertracing.io/docs/latest/apis/\n    tags:\n      - Collector\n      - Distributed Tracing\n      - gRPC\n      - OTLP\n    properties:\n      - type: Documentation\n        url: https://www.jaegertracing.io/docs/latest/apis/\n      - type: Reference\n        url: https://github.com/jaegertracing/jaeger-idl/blob/main/proto/api_v2/collector.proto\n      - type: GitHubRepository\n        url: https://github.com/jaegertracing/jaeger\n  - aid: jaeger:jaeger-remote-storage-api\n    name: Jaeger Remote Storage API\n    description: >-\n      The Jaeger Remote Storage API is a gRPC-based interface that allows\n      extending Jaeger with custom storage backends. Any backend implementing\n      this API can be deployed as a remote gRPC server and plugged into Jaeger\n      components in place of built-in storage engines (available since v1.30).\n   \
  \ humanURL: https://www.jaegertracing.io/docs/latest/apis/\n    tags:\n      - Distributed Tracing\n      - Extensions\n      - gRPC\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://www.jaegertracing.io/docs/latest/apis/\n      - type: Reference\n        url: https://github.com/jaegertracing/jaeger-idl/blob/main/proto/api_v2/query.proto\n      - type: GitHubRepository\n        url: https://github.com/jaegertracing/jaeger\n  - aid: jaeger:jaeger-remote-sampling-api\n    name: Jaeger Remote Sampling API\n    description: >-\n      The Jaeger Remote Sampling API provides HTTP and gRPC endpoints that\n      SDKs use to retrieve sampling strategies for distributed trace collection.\n      It is implemented by the jaeger-collector and defined in the sampling.proto\n      IDL, supporting both static file-based and adaptive sampling strategies.\n    humanURL: https://www.jaegertracing.io/docs/latest/apis/\n    tags:\n      - Configuration\n      - Distributed\
  \ Tracing\n      - gRPC\n      - Sampling\n    properties:\n      - type: Documentation\n        url: https://www.jaegertracing.io/docs/latest/apis/\n      - type: Reference\n        url: https://github.com/jaegertracing/jaeger-idl/blob/main/proto/api_v2/sampling.proto\n      - type: GitHubRepository\n        url: https://github.com/jaegertracing/jaeger\ncommon:\n  - type: Website\n    url: https://www.jaegertracing.io/\n  - type: Documentation\n    url: https://www.jaegertracing.io/docs/\n  - type: Getting Started\n    url: https://www.jaegertracing.io/docs/latest/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/jaegertracing\n  - type: GitHubRepository\n    url: https://github.com/jaegertracing/jaeger\n  - type: Blog\n    url: https://www.jaegertracing.io/news/\n  - type: Community\n    url: https://www.jaegertracing.io/get-involved/\n  - type: Support\n    url: https://www.jaegertracing.io/get-in-touch/\n  - type: Change Log\n    url: https://github.com/jaegertracing/jaeger/blob/main/CHANGELOG.md\n\
  \  - type: JSON-LD\n    url: json-ld/jaeger-trace.yml\n  - type: JSONSchema\n    url: json-schema/jaeger-trace.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jaeger/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Microservices
- Monitoring
- Observability
url: https://raw.githubusercontent.com/api-evangelist/jaeger/refs/heads/main/apis.yml
use_cases: []
---
