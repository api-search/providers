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
