---
api_count: 3
apis:
- description: The Dubbo Admin REST API provides service governance operations for managing services, instances, traffic rules, load balancing, route policies, and dynamic configuration in a Dubbo microservices clus
  name: Apache Dubbo Admin API
  slug: apache-dubbo-admin
- description: The core Apache Dubbo Java framework providing RPC service definition, publishing, invocation, and service governance APIs for building enterprise microservices in Java and Spring Boot.
  name: Apache Dubbo Java SDK
  slug: apache-dubbo-java
- description: The Go implementation of Apache Dubbo, providing the same RPC framework capabilities including service discovery, traffic management, and Triple protocol support for Go-based microservices.
  name: Apache Dubbo Go SDK
  slug: apache-dubbo-go
capabilities:
- description: 'Unified capability for governing Apache Dubbo microservices — managing services, applications, traffic rules, routing policies, and monitoring cluster health. Designed for platform engineers and SREs '
  name: Apache Dubbo Service Governance
  slug: dubbo-service-governance
common:
- title: Apache GitHub Organization
  type: GitHubOrganization
  url: https://github.com/apache
- title: Apache Dubbo Java (Main Repo)
  type: GitHubRepository
  url: https://github.com/apache/dubbo
- title: Apache Dubbo Go
  type: GitHubRepository
  url: https://github.com/apache/dubbo-go
- title: Apache Dubbo Admin
  type: GitHubRepository
  url: https://github.com/apache/dubbo-admin
- title: Apache Dubbo Kubernetes
  type: GitHubRepository
  url: https://github.com/apache/dubbo-kubernetes
- title: ''
  type: Documentation
  url: https://dubbo.apache.org/en/overview/
- title: ''
  type: GettingStarted
  url: https://dubbo.apache.org/en/overview/quickstart/
- title: ''
  type: Blog
  url: https://dubbo.apache.org/en/blog/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/dubbo/releases
- title: ''
  type: SpectralRules
  url: rules/apache-dubbo-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-dubbo-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/dubbo-service-governance.yaml
created: '2026-03-16'
description: Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for Java, Go, Node.js, Python, Rust, and Erlang.
features:
- description: HTTP/2-based RPC protocol fully compatible with gRPC, supporting streaming communication and cross-language interoperability.
  name: Triple Protocol (gRPC Compatible)
- description: High-performance application-level service discovery supporting Nacos, Zookeeper, Kubernetes, Consul, Etcd, and Redis registries.
  name: Service Discovery
- description: Advanced traffic control with conditional routing, tag routing, gray releases, and percentage-based traffic splitting.
  name: Traffic Management
- description: Multiple load balancing strategies including weighted random, round-robin, least active, and consistent hashing.
  name: Load Balancing
- description: Built-in rate limiting, circuit breaker, and service degradation capabilities for resilient microservices.
  name: Rate Limiting and Circuit Breaking
- description: Full-link tracing via OpenTelemetry, Prometheus metrics, Grafana dashboards, Zipkin, and SkyWalking integration.
  name: Observability
- description: Official SDKs for Java, Go, Node.js, Python, Rust, and Erlang enabling polyglot microservices architectures.
  name: Multi-Language SDK Support
- description: Native Istio integration with xDS protocol support for deploying Dubbo services in service mesh environments.
  name: Service Mesh Integration
- description: Visual cluster management UI for service governance, traffic rules, configuration, and monitoring.
  name: Dubbo Admin Console
- description: HTTP/gRPC gateway (Pixiu) enabling REST HTTP clients to access Dubbo backend services.
  name: Pixiu Gateway
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Service registry and configuration center integration for service discovery and dynamic configuration.
  name: Nacos
- description: Apache Zookeeper integration for service registry and coordination.
  name: Zookeeper
- description: Native Kubernetes service discovery and deployment orchestration support.
  name: Kubernetes
- description: Service mesh integration with Istio using xDS protocol for traffic management.
  name: Istio
- description: Metrics export to Prometheus for monitoring Dubbo service performance.
  name: Prometheus
- description: Pre-built Grafana dashboards for visualizing Dubbo service metrics.
  name: Grafana
- description: Distributed tracing via OpenTelemetry standard for end-to-end request tracking.
  name: OpenTelemetry
- description: Distributed tracing integration with Zipkin for request flow visualization.
  name: Zipkin
- description: Apache SkyWalking APM integration for distributed tracing and service performance monitoring.
  name: SkyWalking
- description: Apache Seata integration for distributed transaction management across Dubbo services.
  name: Seata
jsonld:
- class_count: 35
  name: Apache Dubbo Admin Context
  property_count: 88
  slug: apache-dubbo-admin-context
layout: provider
modified: '2026-04-19'
name: Apache Dubbo
rules:
- name: Apache Dubbo API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 9
  slug: apache-dubbo-spectral-rules
skills: []
slug: apache-dubbo
solutions: []
tags:
- Apache
- Go
- Java
- Microservices
- Open Source
- RPC
- Service Discovery
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml
use_cases:
- description: Build high-performance Java or Go microservices with RPC communication, service discovery, and traffic governance.
  name: Enterprise Microservices
- description: Adopt the Triple protocol as a drop-in gRPC-compatible alternative with richer governance capabilities.
  name: gRPC Migration
- description: Enable polyglot microservices with Java, Go, Node.js, Python, Rust, and Erlang services communicating via Dubbo protocols.
  name: Cross-Language Service Communication
- description: Run Dubbo services in Istio-managed service meshes using xDS protocol for sidecar-free or sidecar-based deployments.
  name: Service Mesh Deployment
- description: Deploy and manage Dubbo services on Kubernetes using the Dubbo Kubernetes operator and control plane.
  name: Cloud-Native Kubernetes Deployment
- description: Expose internal Dubbo RPC services as REST HTTP endpoints through the Pixiu API gateway.
  name: API Gateway Integration
---
