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
