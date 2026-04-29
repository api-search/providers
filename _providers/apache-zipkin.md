---
api_count: 1
apis:
- description: The Zipkin REST API v2 provides endpoints for querying trace data, service names, span names, and dependencies. Key endpoints include GET /api/v2/services (list services), GET /api/v2/spans (list span
  name: Apache Zipkin REST API
  slug: apache-zipkin-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/openzipkin/zipkin
- title: ''
  type: Documentation
  url: https://zipkin.io/pages/documentation.html
- title: ''
  type: Portal
  url: https://zipkin.io/
- title: ''
  type: GettingStarted
  url: https://zipkin.io/pages/quickstart.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/openzipkin/zipkin/releases
- title: ''
  type: Support
  url: https://gitter.im/openzipkin/zipkin
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/py_zipkin/
- title: Java SDK
  type: SDK
  url: https://search.maven.org/search?q=io.zipkin
created: '2026-03-16'
description: Apache Zipkin is a distributed tracing system that helps gather timing data needed to troubleshoot latency problems in service architectures. It manages both the collection and lookup of tracing data through a collector and query service. Zipkin provides a REST API, web UI, and multiple storage backends (Cassandra, Elasticsearch, MySQL). It supports the B3 propagation format and is compatible with OpenZipkin instrumentation libraries. Originally created at Twitter, it is now maintained as an open-source project.
features:
- description: Collect timing and metadata for distributed service calls with B3 propagation headers.
  name: Distributed Trace Collection
- description: Web UI and REST API for searching and visualizing distributed traces with latency analysis.
  name: Trace Query and Visualization
- description: Automatic service call graph generation from collected trace data.
  name: Service Dependency Graph
- description: Cassandra, Elasticsearch, and MySQL storage backends for different scale requirements.
  name: Multiple Storage Backends
- description: Accepts OTLP/Zipkin spans from OpenTelemetry instrumented services.
  name: OpenTelemetry Compatible
- description: Standard B3 trace propagation headers for distributed context passing across services.
  name: B3 Propagation
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spring Boot auto-instrumentation for trace propagation and Zipkin reporting.
  name: Spring Cloud Sleuth
- description: Java instrumentation library (Brave) for adding Zipkin tracing to Java applications.
  name: Brave
- description: Elasticsearch storage backend for scalable trace data storage and search.
  name: Elasticsearch
- description: Cassandra storage backend for high-volume trace data.
  name: Apache Cassandra
- description: OpenTelemetry Zipkin exporter for reporting OTLP traces to Zipkin.
  name: OpenTelemetry
- description: Kafka collector for ingesting spans from high-throughput microservice architectures.
  name: Kafka
layout: provider
modified: '2026-04-19'
name: Apache Zipkin
skills: []
slug: apache-zipkin
solutions: []
source_yaml: "aid: apache-zipkin\nname: Apache Zipkin\ndescription: >-\n  Apache Zipkin is a distributed tracing system that helps gather timing data needed to\n  troubleshoot latency problems in service architectures. It manages both the collection\n  and lookup of tracing data through a collector and query service. Zipkin provides a REST\n  API, web UI, and multiple storage backends (Cassandra, Elasticsearch, MySQL). It supports\n  the B3 propagation format and is compatible with OpenZipkin instrumentation libraries.\n  Originally created at Twitter, it is now maintained as an open-source project.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Tracing\n  - Microservices\n  - Monitoring\n  - Observability\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-zipkin/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: apache-zipkin:apache-zipkin-api\n    name: Apache Zipkin REST API\n    description: >-\n      The Zipkin REST API v2 provides endpoints for querying trace data, service names, span names,\n      and dependencies. Key endpoints include GET /api/v2/services (list services), GET /api/v2/spans\n      (list span names for a service), GET /api/v2/traces (search traces by service, span, tags, duration),\n      GET /api/v2/trace/{traceId} (get a specific trace), and GET /api/v2/dependencies (service dependency graph).\n      Span reporting uses POST /api/v2/spans for JSON format or POST /api/v2/spans for Thrift format.\n    humanURL: https://zipkin.io/zipkin-api/\n    tags:\n      - REST\n      - Distributed Tracing\n      - Monitoring\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://zipkin.io/zipkin-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/openzipkin/zipkin-api/master/zipkin2-api.yaml\ncommon:\n\
  \  - type: GitHubRepository\n    url: https://github.com/openzipkin/zipkin\n  - type: Documentation\n    url: https://zipkin.io/pages/documentation.html\n  - type: Portal\n    url: https://zipkin.io/\n  - type: GettingStarted\n    url: https://zipkin.io/pages/quickstart.html\n  - type: ReleaseNotes\n    url: https://github.com/openzipkin/zipkin/releases\n  - type: Support\n    url: https://gitter.im/openzipkin/zipkin\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://pypi.org/project/py_zipkin/\n    title: Python SDK\n  - type: SDK\n    url: https://search.maven.org/search?q=io.zipkin\n    title: Java SDK\n  - type: Features\n    data:\n      - name: Distributed Trace Collection\n        description: Collect timing and metadata for distributed service calls with B3 propagation headers.\n      - name: Trace Query and Visualization\n        description: Web UI and REST API for searching and visualizing distributed traces with latency analysis.\n\
  \      - name: Service Dependency Graph\n        description: Automatic service call graph generation from collected trace data.\n      - name: Multiple Storage Backends\n        description: Cassandra, Elasticsearch, and MySQL storage backends for different scale requirements.\n      - name: OpenTelemetry Compatible\n        description: Accepts OTLP/Zipkin spans from OpenTelemetry instrumented services.\n      - name: B3 Propagation\n        description: Standard B3 trace propagation headers for distributed context passing across services.\n  - type: UseCases\n    data:\n      - name: Microservices Latency Troubleshooting\n        description: Identify bottlenecks and slow service calls in distributed architectures.\n      - name: Service Dependency Mapping\n        description: Automatically discover and visualize service-to-service call graphs.\n      - name: Performance Regression Detection\n        description: Compare trace data before and after deployments to detect performance\
  \ regressions.\n      - name: Root Cause Analysis\n        description: Follow distributed call chains to identify the root cause of errors and failures.\n  - type: Integrations\n    data:\n      - name: Spring Cloud Sleuth\n        description: Spring Boot auto-instrumentation for trace propagation and Zipkin reporting.\n      - name: Brave\n        description: Java instrumentation library (Brave) for adding Zipkin tracing to Java applications.\n      - name: Elasticsearch\n        description: Elasticsearch storage backend for scalable trace data storage and search.\n      - name: Apache Cassandra\n        description: Cassandra storage backend for high-volume trace data.\n      - name: OpenTelemetry\n        description: OpenTelemetry Zipkin exporter for reporting OTLP traces to Zipkin.\n      - name: Kafka\n        description: Kafka collector for ingesting spans from high-throughput microservice architectures.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-zipkin/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Microservices
- Monitoring
- Observability
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-zipkin/refs/heads/main/apis.yml
use_cases:
- description: Identify bottlenecks and slow service calls in distributed architectures.
  name: Microservices Latency Troubleshooting
- description: Automatically discover and visualize service-to-service call graphs.
  name: Service Dependency Mapping
- description: Compare trace data before and after deployments to detect performance regressions.
  name: Performance Regression Detection
- description: Follow distributed call chains to identify the root cause of errors and failures.
  name: Root Cause Analysis
---
