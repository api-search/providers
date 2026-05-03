---
api_count: 1
api_specs:
- filename: zipkin-api-v2.yml
  format: yaml
  label: Zipkin API V2
  slug: zipkin-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/openapi/zipkin-api-v2.yml
apis:
- description: Zipkin's v2 HTTP API for querying and collecting distributed traces. Provides endpoints for submitting spans, querying traces, looking up services and span names, and retrieving dependency links betwe
  name: Zipkin API V2
  slug: zipkin-api-v2
capabilities:
- description: A workflow capability for an SRE investigating latency or errors in a distributed system. Combines Zipkin trace search, trace retrieval, and dependency analysis to surface root causes across microserv
  name: Distributed Tracing Investigation
  slug: distributed-tracing-investigation
common:
- title: ''
  type: Website
  url: https://zipkin.io
- title: ''
  type: Documentation
  url: https://zipkin.io/pages/quickstart.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/openzipkin
- title: ''
  type: SDK
  url: https://github.com/openzipkin/brave
- title: ''
  type: SDK
  url: https://github.com/openzipkin/zipkin-go
- title: ''
  type: SDK
  url: https://github.com/openzipkin/zipkin-js
- title: ''
  type: SDK
  url: https://github.com/openzipkin/zipkin-ruby
- title: ''
  type: JSONLD
  url: json-ld/zipkin-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/zipkin-spectral.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/distributed-tracing-investigation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/zipkin-vocabulary.yaml
created: '2026-03-25'
description: Zipkin is an open source distributed tracing system for gathering timing data to troubleshoot latency problems in microservice architectures. It was originally developed at Twitter based on the Google Dapper paper, and is now a CNCF-related project maintained by the OpenZipkin community. Zipkin provides a collector, storage, and query service with a UI for visualizing trace data across distributed services.
features:
- description: End-to-end tracing of requests across microservices.
  name: Distributed Tracing
- description: Ingestion of spans via HTTP, Kafka, and other transports.
  name: Span Collection
- description: Query traces by service, span name, tags, and time range.
  name: Trace Search
- description: Derived service-to-service dependency links from spans.
  name: Dependency Graph
- description: Web-based UI for exploring traces and dependency graphs.
  name: UI
- description: Pluggable backends including in-memory, MySQL, Cassandra, and Elasticsearch.
  name: Pluggable Storage
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Java instrumentation library for OpenZipkin.
  name: Brave
- description: OpenTelemetry can export traces to Zipkin.
  name: OpenTelemetry
- description: Spring framework integration emitting Zipkin traces.
  name: Spring Cloud Sleuth
- description: Span transport via Kafka for asynchronous ingestion.
  name: Kafka
- description: Storage backend for spans and traces at scale.
  name: Elasticsearch
jsonld:
- class_count: 4
  name: Zipkin Context
  property_count: 20
  slug: zipkin-context
layout: provider
modified: '2026-05-03'
name: Zipkin
rules:
- name: Zipkin API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: zipkin-spectral
skills: []
slug: zipkin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zipkin\nname: Zipkin\ndescription: >-\n  Zipkin is an open source distributed tracing system for gathering timing data\n  to troubleshoot latency problems in microservice architectures. It was originally\n  developed at Twitter based on the Google Dapper paper, and is now a CNCF-related\n  project maintained by the OpenZipkin community. Zipkin provides a collector,\n  storage, and query service with a UI for visualizing trace data across distributed\n  services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Tracing\n  - Observability\n  - Open Source\n  - Microservices\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zipkin:zipkin-api-v2\n    name: Zipkin API V2\n    description: >-\n      Zipkin's v2 HTTP API for querying and collecting distributed traces.\n  \
  \    Provides endpoints for submitting spans, querying traces, looking up\n      services and span names, and retrieving dependency links between services.\n    humanURL: https://zipkin.io/zipkin-api/\n    tags:\n      - Dependencies\n      - Distributed Tracing\n      - Observability\n      - Spans\n      - Traces\n    properties:\n      - type: Documentation\n        url: https://zipkin.io/zipkin-api/\n      - type: GitHubRepository\n        url: https://github.com/openzipkin/zipkin\n      - type: OpenAPI\n        url: openapi/zipkin-api-v2.yml\n      - type: JSONSchema\n        url: json-schema/zipkin-api-v2-span-schema.json\n      - type: JSONSchema\n        url: json-schema/zipkin-api-v2-endpoint-schema.json\n      - type: JSONSchema\n        url: json-schema/zipkin-api-v2-annotation-schema.json\n      - type: JSONSchema\n        url: json-schema/zipkin-api-v2-dependency-link-schema.json\n      - type: JSONStructure\n        url: json-structure/zipkin-api-v2-span-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/zipkin-api-v2-endpoint-structure.json\n      - type: JSONStructure\n        url: json-structure/zipkin-api-v2-annotation-structure.json\n      - type: JSONStructure\n        url: json-structure/zipkin-api-v2-dependency-link-structure.json\n      - type: Example\n        url: examples/zipkin-api-v2-get-services-example.json\n      - type: Example\n        url: examples/zipkin-api-v2-get-dependencies-example.json\n      - type: Example\n        url: examples/zipkin-api-v2-report-spans-example.json\n      - type: Example\n        url: examples/zipkin-api-v2-search-traces-example.json\ncommon:\n  - type: Website\n    url: https://zipkin.io\n  - type: Documentation\n    url: https://zipkin.io/pages/quickstart.html\n  - type: GitHubOrganization\n    url: https://github.com/openzipkin\n  - type: SDK\n    url: https://github.com/openzipkin/brave\n    name: Brave (Java)\n  - type: SDK\n    url: https://github.com/openzipkin/zipkin-go\n \
  \   name: zipkin-go (Go)\n  - type: SDK\n    url: https://github.com/openzipkin/zipkin-js\n    name: zipkin-js (JavaScript/Node.js)\n  - type: SDK\n    url: https://github.com/openzipkin/zipkin-ruby\n    name: zipkin-ruby (Ruby)\n  - type: JSONLD\n    url: json-ld/zipkin-context.jsonld\n  - type: SpectralRules\n    url: rules/zipkin-spectral.yaml\n  - type: NaftikoCapability\n    url: capabilities/distributed-tracing-investigation.yaml\n  - type: Vocabulary\n    url: vocabulary/zipkin-vocabulary.yaml\n  - data:\n      - name: Distributed Tracing\n        description: End-to-end tracing of requests across microservices.\n      - name: Span Collection\n        description: Ingestion of spans via HTTP, Kafka, and other transports.\n      - name: Trace Search\n        description: Query traces by service, span name, tags, and time range.\n      - name: Dependency Graph\n        description: Derived service-to-service dependency links from spans.\n      - name: UI\n        description: Web-based\
  \ UI for exploring traces and dependency graphs.\n      - name: Pluggable Storage\n        description: Pluggable backends including in-memory, MySQL, Cassandra, and Elasticsearch.\n    name: Features\n    type: Features\n  - data:\n      - name: Microservices Latency Debugging\n        description: Identify slow services and operations in a microservice architecture.\n      - name: Error Investigation\n        description: Trace failed requests across services to find error origin.\n      - name: Service Dependency Mapping\n        description: Visualize which services call which, with call counts.\n      - name: Performance Optimization\n        description: Identify hotspots and optimize critical-path operations.\n    name: UseCases\n    type: UseCases\n  - data:\n      - name: Brave\n        description: Java instrumentation library for OpenZipkin.\n      - name: OpenTelemetry\n        description: OpenTelemetry can export traces to Zipkin.\n      - name: Spring Cloud Sleuth\n    \
  \    description: Spring framework integration emitting Zipkin traces.\n      - name: Kafka\n        description: Span transport via Kafka for asynchronous ingestion.\n      - name: Elasticsearch\n        description: Storage backend for spans and traces at scale.\n    name: Integrations\n    type: Integrations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Observability
- Open Source
- Microservices
url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml
use_cases:
- description: Identify slow services and operations in a microservice architecture.
  name: Microservices Latency Debugging
- description: Trace failed requests across services to find error origin.
  name: Error Investigation
- description: Visualize which services call which, with call counts.
  name: Service Dependency Mapping
- description: Identify hotspots and optimize critical-path operations.
  name: Performance Optimization
---
