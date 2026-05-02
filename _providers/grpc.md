---
api_count: 5
api_specs:
- filename: openapi.yml
  format: yaml
  label: gRPC-Web Proxy API
  slug: grpc-web-proxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/openapi.yml
- filename: asyncapi.yml
  format: yaml
  label: gRPC Health Checking Service
  slug: grpc-health-checking
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/asyncapi.yml
- filename: asyncapi.yml
  format: yaml
  label: gRPC Server Reflection
  slug: grpc-server-reflection
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/asyncapi.yml
apis:
- description: OpenAPI specification for gRPC-Web proxy endpoints covering health checking, server reflection, and channelz introspection services exposed over HTTP for browser-based and REST clients.
  name: gRPC-Web Proxy API
  slug: grpc-web-proxy-api
- description: The gRPC core framework defines the RPC protocol, service definition format using Protocol Buffers, and the fundamental call lifecycle including unary, server-streaming, client-streaming, and bidirect
  name: gRPC Core Framework
  slug: grpc-core
- description: JSON Schema for Protocol Buffers service definition format (.proto files). Describes the structure of gRPC service declarations, RPC methods, message types, enums, oneofs, maps, and file-level options
  name: Protocol Buffers Service Definition Schema
  slug: protobuf-service-definition
- description: The gRPC Health Checking Protocol defines a standard service that gRPC servers implement to expose health status information to clients and load balancers. Servers implement the Health service proto t
  name: gRPC Health Checking Service
  slug: grpc-health-checking
- description: The gRPC Server Reflection Protocol allows gRPC servers to declare the protobuf-defined APIs they export over a standardized RPC service, including all types referenced by request and response message
  name: gRPC Server Reflection
  slug: grpc-server-reflection
common:
- title: ''
  type: Website
  url: https://grpc.io/
- title: ''
  type: Documentation
  url: https://grpc.io/docs/
- title: ''
  type: Getting Started
  url: https://grpc.io/docs/languages/
- title: ''
  type: GitHub Organization
  url: https://github.com/grpc
- title: ''
  type: Blog
  url: https://grpc.io/blog/
- title: ''
  type: Community
  url: https://grpc.io/community/
- title: ''
  type: FAQ
  url: https://grpc.io/docs/what-is-grpc/faq/
- title: ''
  type: SDKs
  url: https://grpc.io/docs/languages/
- title: ''
  type: Change Log
  url: https://github.com/grpc/grpc/releases
- title: ''
  type: JSONSchema
  url: json-schema.yml
- title: ''
  type: JSONSchema
  url: service-config-schema.json
- title: ''
  type: AsyncAPI
  url: asyncapi.yml
- title: ''
  type: JSON-LD
  url: context.jsonld
created: '2025'
description: gRPC is a high-performance, open-source universal RPC framework that uses HTTP/2 for transport, Protocol Buffers as the interface description language, and provides features such as authentication, bidirectional streaming and flow control, blocking or nonblocking bindings, and cancellation and timeouts. Originally developed at Google, it is now a CNCF project.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: gRPC
skills: []
slug: grpc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: grpc\nname: gRPC\ndescription: >-\n  gRPC is a high-performance, open-source universal RPC framework that uses\n  HTTP/2 for transport, Protocol Buffers as the interface description language,\n  and provides features such as authentication, bidirectional streaming and flow\n  control, blocking or nonblocking bindings, and cancellation and timeouts.\n  Originally developed at Google, it is now a CNCF project.\nurl: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CNCF\n  - HTTP/2\n  - Microservices\n  - Protocol Buffers\n  - RPC\ncreated: '2025'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: grpc:grpc-web-proxy-api\n    name: gRPC-Web Proxy API\n    description: >-\n      OpenAPI specification for gRPC-Web proxy endpoints covering health\n      checking, server reflection, and channelz introspection services\n \
  \     exposed over HTTP for browser-based and REST clients.\n    humanURL: https://grpc.io/docs/platforms/web/\n    tags:\n      - Channelz\n      - gRPC-Web\n      - Health Checking\n      - Reflection\n    properties:\n      - type: OpenAPI\n        url: openapi.yml\n      - type: Documentation\n        url: https://grpc.io/docs/platforms/web/\n      - type: Reference\n        url: https://grpc.io/docs/platforms/web/basics/\n      - type: JSONSchema\n        url: json-schema.yml\n  - aid: grpc:grpc-core\n    name: gRPC Core Framework\n    description: >-\n      The gRPC core framework defines the RPC protocol, service definition\n      format using Protocol Buffers, and the fundamental call lifecycle\n      including unary, server-streaming, client-streaming, and bidirectional\n      streaming patterns over HTTP/2. It is the foundational specification\n      implemented by all language-specific gRPC SDKs.\n    humanURL: https://grpc.io/docs/what-is-grpc/introduction/\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    properties:\n      - type: Documentation\n        url: https://grpc.io/docs/what-is-grpc/introduction/\n      - type: Reference\n        url: https://grpc.io/docs/what-is-grpc/core-concepts/\n      - type: Authentication\n        url: https://grpc.io/docs/guides/auth/\n      - type: GitHubRepository\n        url: https://github.com/grpc/grpc\n      - type: JSONSchema\n        url: service-config-schema.json\n      - type: JSONSchema\n        url: json-schema.yml\n      - type: JSON-LD\n        url: context.jsonld\n    tags:\n      - HTTP/2\n      - Protocol Buffers\n      - RPC\n      - Streaming\n  - aid: grpc:protobuf-service-definition\n    name: Protocol Buffers Service Definition Schema\n    description: >-\n      JSON Schema for Protocol Buffers service definition format (.proto files).\n      Describes the structure of gRPC service declarations, RPC methods,\n      message types, enums, oneofs, maps, and file-level options used to\n      define gRPC APIs.\n    humanURL: https://protobuf.dev/programming-guides/proto3/\n\
  \    tags:\n      - IDL\n      - Protocol Buffers\n      - Schema\n      - Service Definition\n    properties:\n      - type: Documentation\n        url: https://protobuf.dev/programming-guides/proto3/\n      - type: JSONSchema\n        url: json-schema/protobuf-service-definition.yml\n  - aid: grpc:grpc-health-checking\n    name: gRPC Health Checking Service\n    description: >-\n      The gRPC Health Checking Protocol defines a standard service that gRPC\n      servers implement to expose health status information to clients and load\n      balancers. Servers implement the Health service proto to report per-service\n      readiness, and clients can configure automatic health-check-based connection\n      management.\n    humanURL: https://grpc.io/docs/guides/health-checking/\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://grpc.io/docs/guides/health-checking/\n      - type: Reference\n\
  \        url: https://github.com/grpc/grpc-proto/blob/master/grpc/health/v1/health.proto\n      - type: GitHubRepository\n        url: https://github.com/grpc/grpc-proto\n      - type: AsyncAPI\n        url: asyncapi.yml\n    tags:\n      - Health Checking\n      - Load Balancing\n      - Observability\n  - aid: grpc:grpc-server-reflection\n    name: gRPC Server Reflection\n    description: >-\n      The gRPC Server Reflection Protocol allows gRPC servers to declare the\n      protobuf-defined APIs they export over a standardized RPC service, including\n      all types referenced by request and response messages. This enables command-line\n      debugging tools and clients to dynamically discover and invoke gRPC services\n      without pre-compiled stubs.\n    humanURL: https://grpc.io/docs/guides/reflection/\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://grpc.io/docs/guides/reflection/\n\
  \      - type: Reference\n        url: https://github.com/grpc/grpc/blob/master/doc/server-reflection.md\n      - type: AsyncAPI\n        url: asyncapi.yml\n    tags:\n      - Debugging\n      - Reflection\n      - Service Discovery\ncommon:\n  - type: Website\n    url: https://grpc.io/\n  - type: Documentation\n    url: https://grpc.io/docs/\n  - type: Getting Started\n    url: https://grpc.io/docs/languages/\n  - type: GitHub Organization\n    url: https://github.com/grpc\n  - type: Blog\n    url: https://grpc.io/blog/\n  - type: Community\n    url: https://grpc.io/community/\n  - type: FAQ\n    url: https://grpc.io/docs/what-is-grpc/faq/\n  - type: SDKs\n    url: https://grpc.io/docs/languages/\n  - type: Change Log\n    url: https://github.com/grpc/grpc/releases\n  - type: JSONSchema\n    url: json-schema.yml\n  - type: JSONSchema\n    url: service-config-schema.json\n  - type: AsyncAPI\n    url: asyncapi.yml\n  - type: JSON-LD\n    url: context.jsonld\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/apis.yml
tags:
- CNCF
- HTTP/2
- Microservices
- Protocol Buffers
- RPC
url: https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/apis.yml
use_cases: []
---
