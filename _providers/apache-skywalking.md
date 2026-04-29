---
api_count: 3
apis:
- description: The SkyWalking GraphQL Query API provides a comprehensive query interface for retrieving observability data including traces, metrics, logs, alarms, topology maps, and profiling results. It supports m
  name: Apache SkyWalking GraphQL Query API
  slug: apache-skywalking-graphql-query-api
- description: 'The SkyWalking HTTP REST API exposes endpoints on port 12800 for health checks, PromQL-compatible metrics queries (Prometheus Query Language), LogQL log queries, and dynamic configuration management. '
  name: Apache SkyWalking REST API
  slug: apache-skywalking-rest-api
- description: The SkyWalking data collection protocol defines gRPC service definitions for telemetry data ingestion from language agents and service mesh proxies. It covers trace data (v3), JVM metrics, meter proto
  name: Apache SkyWalking gRPC Data Collect Protocol
  slug: apache-skywalking-grpc-data-collect-protocol
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache?q=skywalking
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/skywalking
- title: ''
  type: Documentation
  url: https://skywalking.apache.org/docs/
- title: ''
  type: Portal
  url: https://skywalking.apache.org/
- title: ''
  type: Blog
  url: https://skywalking.apache.org/blog/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/skywalking/releases
- title: ''
  type: Support
  url: https://skywalking.apache.org/community/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: Java Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-java
- title: Python Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-python
- title: Go Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-go
- title: Node.js Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-nodejs
- title: PHP Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-php
- title: Ruby Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-ruby
- title: Rust Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-rust
- title: JavaScript Browser Agent SDK
  type: SDK
  url: https://github.com/apache/skywalking-client-js
created: '2026-03-16'
description: Apache SkyWalking is an open-source APM (Application Performance Monitoring) system that provides monitoring, tracing, and diagnosing capabilities for distributed systems in cloud native architectures. It supports auto-instrumentation for Java, .NET, Python, Go, Node.js, PHP, and Ruby, offering distributed tracing, metrics collection, log aggregation, and continuous profiling through a unified observability platform governed by the Apache Software Foundation.
features:
- description: Auto-instrumented distributed tracing across 10+ languages with trace correlation and cross-service propagation.
  name: Distributed Tracing
- description: Service, instance, and endpoint metrics with SkyWalking Metrics Query Expression (MQE) engine.
  name: Metrics Collection
- description: Centralized log collection and search with LAL (Log Analysis Language) rules.
  name: Log Aggregation
- description: Automatic service dependency mapping and topology visualization.
  name: Service Topology
- description: Rule-based alerting on metrics thresholds with webhook and notification integrations.
  name: Alarm System
- description: CPU, memory, and network profiling via async-profiler, pprof, and eBPF.
  name: Continuous Profiling
- description: Out-of-process network performance profiling using eBPF without code instrumentation.
  name: eBPF Network Profiling
- description: Prometheus Query Language API for Grafana and other Prometheus-compatible tools.
  name: PromQL Compatibility
- description: Native observability database optimized for time-series and trace data storage.
  name: BanyanDB Storage
- description: Hierarchical service model supporting mesh, Kubernetes, APISIX gateway, and custom layers.
  name: Multi-Layer Service Model
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Kubernetes monitoring via skywalking-kubernetes Helm charts and event integration.
  name: Kubernetes
- description: PromQL-compatible metrics API enables native Grafana dashboard integration.
  name: Grafana
- description: Service mesh telemetry collection from Istio-managed service traffic.
  name: Istio
- description: API Gateway integration for monitoring API traffic through Apache APISIX.
  name: APISIX
- description: Elasticsearch and OpenSearch backend storage for trace and log data.
  name: Elasticsearch
- description: Native high-performance observability database built for SkyWalking.
  name: BanyanDB
- description: Kafka-based data pipeline for high-throughput telemetry ingestion.
  name: Kafka
- description: OpenTelemetry receiver for ingesting OTLP traces, metrics, and logs.
  name: OpenTelemetry
layout: provider
modified: '2026-04-19'
name: Apache SkyWalking
skills: []
slug: apache-skywalking
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-skywalking\nname: Apache SkyWalking\ndescription: >-\n  Apache SkyWalking is an open-source APM (Application Performance Monitoring) system that\n  provides monitoring, tracing, and diagnosing capabilities for distributed systems in cloud\n  native architectures. It supports auto-instrumentation for Java, .NET, Python, Go, Node.js,\n  PHP, and Ruby, offering distributed tracing, metrics collection, log aggregation, and\n  continuous profiling through a unified observability platform governed by the Apache Software\n  Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - APM\n  - Application Performance Monitoring\n  - Cloud Native\n  - Distributed Tracing\n  - Monitoring\n  - Observability\n  - Open Source\n  - Tracing\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-skywalking/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-skywalking:apache-skywalking-graphql-query-api\n    name: Apache SkyWalking GraphQL Query API\n    description: >-\n      The SkyWalking GraphQL Query API provides a comprehensive query interface for retrieving\n      observability data including traces, metrics, logs, alarms, topology maps, and profiling\n      results. It supports metadata queries (services, instances, endpoints), topology queries,\n      metrics via SkyWalking Metrics Query Expression (MQE), log queries, trace queries,\n      alarm queries, and profiling queries. The API is served on port 12800 and consumed by\n      the native UI and CLI tools.\n    humanURL: https://github.com/apache/skywalking-query-protocol\n    tags:\n      - GraphQL\n      - Metrics\n      - Observability\n      - Tracing\n      - Logs\n      - Alarms\n      - Profiling\n    properties:\n      - type: Documentation\n        url: https://skywalking.apache.org/docs/main/next/en/api/query-protocol/\n\
  \      - type: GitHubRepository\n        url: https://github.com/apache/skywalking-query-protocol\n\n  - aid: apache-skywalking:apache-skywalking-rest-api\n    name: Apache SkyWalking REST API\n    description: >-\n      The SkyWalking HTTP REST API exposes endpoints on port 12800 for health checks,\n      PromQL-compatible metrics queries (Prometheus Query Language), LogQL log queries,\n      and dynamic configuration management. PromQL support enables integration with\n      Grafana and other Prometheus-compatible visualization tools. LogQL support enables\n      integration with Grafana Loki-compatible tooling.\n    humanURL: https://skywalking.apache.org/docs/main/next/en/api/promql-service/\n    tags:\n      - REST\n      - HTTP\n      - PromQL\n      - LogQL\n      - Health Check\n      - Metrics\n    properties:\n      - type: Documentation\n        url: https://skywalking.apache.org/docs/main/next/en/api/promql-service/\n      - type: Documentation\n        url: https://skywalking.apache.org/docs/main/next/en/api/logql-service/\n\
  \n  - aid: apache-skywalking:apache-skywalking-grpc-data-collect-protocol\n    name: Apache SkyWalking gRPC Data Collect Protocol\n    description: >-\n      The SkyWalking data collection protocol defines gRPC service definitions for telemetry\n      data ingestion from language agents and service mesh proxies. It covers trace data\n      (v3), JVM metrics, meter protocol, event reporting, browser performance data,\n      instance properties, continuous profiling, eBPF profiling, and log data protocols.\n      Agents report data to OAP server on port 11800.\n    humanURL: https://github.com/apache/skywalking-data-collect-protocol\n    tags:\n      - gRPC\n      - Protocol Buffers\n      - Telemetry\n      - Agents\n      - Tracing\n      - Metrics\n    properties:\n      - type: Documentation\n        url: https://skywalking.apache.org/docs/main/next/en/api/trace-data-protocol-v3/\n      - type: GitHubRepository\n        url: https://github.com/apache/skywalking-data-collect-protocol\n\
  \ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache?q=skywalking\n  - type: GitHubRepository\n    url: https://github.com/apache/skywalking\n  - type: Documentation\n    url: https://skywalking.apache.org/docs/\n  - type: Portal\n    url: https://skywalking.apache.org/\n  - type: Blog\n    url: https://skywalking.apache.org/blog/\n  - type: ReleaseNotes\n    url: https://github.com/apache/skywalking/releases\n  - type: Support\n    url: https://skywalking.apache.org/community/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://github.com/apache/skywalking-java\n    title: Java Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-python\n    title: Python Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-go\n    title: Go Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-nodejs\n    title: Node.js Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-php\n\
  \    title: PHP Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-ruby\n    title: Ruby Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-rust\n    title: Rust Agent SDK\n  - type: SDK\n    url: https://github.com/apache/skywalking-client-js\n    title: JavaScript Browser Agent SDK\n  - type: Features\n    data:\n      - name: Distributed Tracing\n        description: Auto-instrumented distributed tracing across 10+ languages with trace correlation and cross-service propagation.\n      - name: Metrics Collection\n        description: Service, instance, and endpoint metrics with SkyWalking Metrics Query Expression (MQE) engine.\n      - name: Log Aggregation\n        description: Centralized log collection and search with LAL (Log Analysis Language) rules.\n      - name: Service Topology\n        description: Automatic service dependency mapping and topology visualization.\n      - name: Alarm System\n        description: Rule-based alerting on\
  \ metrics thresholds with webhook and notification integrations.\n      - name: Continuous Profiling\n        description: CPU, memory, and network profiling via async-profiler, pprof, and eBPF.\n      - name: eBPF Network Profiling\n        description: Out-of-process network performance profiling using eBPF without code instrumentation.\n      - name: PromQL Compatibility\n        description: Prometheus Query Language API for Grafana and other Prometheus-compatible tools.\n      - name: BanyanDB Storage\n        description: Native observability database optimized for time-series and trace data storage.\n      - name: Multi-Layer Service Model\n        description: Hierarchical service model supporting mesh, Kubernetes, APISIX gateway, and custom layers.\n  - type: UseCases\n    data:\n      - name: Microservices Observability\n        description: End-to-end monitoring and tracing for microservices architectures in Kubernetes.\n      - name: Service Mesh Monitoring\n        description:\
  \ Integration with Istio and other service meshes for traffic and performance monitoring.\n      - name: Root Cause Analysis\n        description: Trace-based root cause analysis for distributed system failures and latency issues.\n      - name: SLA Monitoring\n        description: Service level agreement monitoring with metrics dashboards and alerting.\n      - name: Continuous Profiling\n        description: Always-on profiling for performance optimization without overhead in production.\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: Native Kubernetes monitoring via skywalking-kubernetes Helm charts and event integration.\n      - name: Grafana\n        description: PromQL-compatible metrics API enables native Grafana dashboard integration.\n      - name: Istio\n        description: Service mesh telemetry collection from Istio-managed service traffic.\n      - name: APISIX\n        description: API Gateway integration for monitoring API traffic through\
  \ Apache APISIX.\n      - name: Elasticsearch\n        description: Elasticsearch and OpenSearch backend storage for trace and log data.\n      - name: BanyanDB\n        description: Native high-performance observability database built for SkyWalking.\n      - name: Kafka\n        description: Kafka-based data pipeline for high-throughput telemetry ingestion.\n      - name: OpenTelemetry\n        description: OpenTelemetry receiver for ingesting OTLP traces, metrics, and logs.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-skywalking/refs/heads/main/apis.yml
tags:
- APM
- Application Performance Monitoring
- Cloud Native
- Distributed Tracing
- Monitoring
- Observability
- Open Source
- Tracing
url: https://raw.githubusercontent.com/api-evangelist/apache-skywalking/refs/heads/main/apis.yml
use_cases:
- description: End-to-end monitoring and tracing for microservices architectures in Kubernetes.
  name: Microservices Observability
- description: Integration with Istio and other service meshes for traffic and performance monitoring.
  name: Service Mesh Monitoring
- description: Trace-based root cause analysis for distributed system failures and latency issues.
  name: Root Cause Analysis
- description: Service level agreement monitoring with metrics dashboards and alerting.
  name: SLA Monitoring
- description: Always-on profiling for performance optimization without overhead in production.
  name: Continuous Profiling
---
