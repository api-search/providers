---
api_count: 3
apis:
- description: Apache APISIX provides rich traffic management features including load balancing, dynamic upstream configuration, canary releases, circuit breaking, authentication, observability plugins, and more. It
  name: Apache APISIX Gateway
  slug: apache-apisix-gateway
- description: The Apache APISIX Admin API provides a RESTful interface to dynamically control and configure a running APISIX instance. It supports management of routes, services, upstreams, consumers, SSL certifica
  name: Apache APISIX Admin API
  slug: apache-apisix-admin-api
- description: The Apache APISIX Control API provides internal status and health check endpoints for monitoring and introspecting a running APISIX instance. It listens by default on port 9090, is accessible only fro
  name: Apache APISIX Control API
  slug: apache-apisix-control-api
capabilities:
- description: Unified capability for configuring and managing Apache APISIX API gateway resources including routes, upstreams, services, consumers, and SSL certificates. Used by platform engineers and API gateway a
  name: Apache APISIX Gateway Configuration
  slug: apisix-gateway-config
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/apisix
- title: ''
  type: Documentation
  url: https://apisix.apache.org/docs/
- title: ''
  type: GettingStarted
  url: https://apisix.apache.org/docs/apisix/getting-started/
- title: ''
  type: Blog
  url: https://apisix.apache.org/blog/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/apisix/releases
- title: ''
  type: Support
  url: https://apisix.apache.org/docs/general/community/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-apisix
- title: ''
  type: JSONSchema
  url: json-schema/route.json
- title: ''
  type: JSONSchema
  url: json-schema/upstream.json
- title: ''
  type: JSONSchema
  url: json-schema/service.json
- title: ''
  type: JSONSchema
  url: json-schema/consumer.json
- title: ''
  type: JSONSchema
  url: json-schema/ssl.json
- title: ''
  type: JSONSchema
  url: json-schema/global-rule.json
- title: ''
  type: JSONSchema
  url: json-schema/plugin-config.json
- title: ''
  type: JSONSchema
  url: json-schema/consumer-group.json
- title: ''
  type: JSONSchema
  url: json-schema/stream-route.json
- title: ''
  type: JSONSchema
  url: json-schema/secret.json
- title: ''
  type: JSONLD
  url: json-ld/apache-apisix-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/apache-apisix-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-apisix-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/apisix-gateway-config.yaml
created: '2026-03-18'
description: Apache APISIX is a dynamic, real-time, high-performance cloud-native API gateway built on NGINX and etcd, developed by the Apache Software Foundation. It supports Lua and multi-language plugins for traffic management, authentication, observability, and security. APISIX provides a RESTful Admin API for dynamic configuration of routes, upstreams, services, consumers, SSL certificates, and plugins, and a Control API for health monitoring and schema introspection.
features:
- description: Dynamically add, update, and delete routes without restarting via the Admin API and etcd-backed config.
  name: Dynamic Route Configuration
- description: Supports HTTP, HTTPS, HTTP/2, gRPC, TCP, UDP, and WebSocket protocols for diverse API types.
  name: Multi-Protocol Support
- description: Rich plugin ecosystem for authentication (JWT, key-auth, OAuth2), rate limiting, transformations, and observability.
  name: Plugin Ecosystem
- description: Plugins can be written in Lua, Go, Python, Java, and Node.js via the Plugin Runner architecture.
  name: Multi-Language Plugin Support
- description: Supports round-robin, consistent hashing, EWMA, and least connections load balancing strategies.
  name: Load Balancing
- description: Traffic splitting for canary deployments and A/B testing with percentage-based routing.
  name: Canary Releases
- description: Built-in circuit breaker plugin for resilience and fault tolerance in upstream communication.
  name: Circuit Breaking
- description: Native Kubernetes ingress controller (APISIX Ingress) for Kubernetes-native API gateway deployments.
  name: Kubernetes Integration
- description: Native integrations with Prometheus, Zipkin, SkyWalking, Datadog, and OpenTelemetry for metrics and tracing.
  name: Observability
- description: Dynamic service discovery via Kubernetes, Nacos, Consul, Eureka, and DNS for upstream resolution.
  name: Service Discovery
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Kubernetes Ingress controller (APISIX Ingress Controller) for cloud-native deployments.
  name: Kubernetes
- description: Native Prometheus metrics exporter for monitoring route, consumer, and upstream metrics.
  name: Prometheus
- description: Distributed tracing integration for request flow analysis across microservices.
  name: Zipkin and Jaeger
- description: OpenTelemetry plugin for standardized telemetry data export.
  name: OpenTelemetry
- description: etcd backend for distributed configuration storage and cluster synchronization.
  name: etcd
- description: Dynamic service discovery integrations for automatic upstream resolution.
  name: Nacos and Consul
- description: Secret management integration for storing API credentials and TLS certificates.
  name: HashiCorp Vault
jsonld:
- class_count: 0
  name: Apache Apisix Context
  property_count: 10
  slug: apache-apisix-context
layout: provider
modified: '2026-04-19'
name: Apache APISIX
rules:
- name: Apache APISIX API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 9
  slug: apache-apisix-spectral-rules
skills: []
slug: apache-apisix
solutions: []
tags:
- Apache
- API Gateway
- Cloud Native
- Kubernetes
- Lua
- NGINX
- Open Source
- Traffic Management
url: https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/apis.yml
use_cases:
- description: Route and manage traffic to microservices with dynamic configuration and plugin-based policies.
  name: API Gateway for Microservices
- description: Apply JWT, key-auth, LDAP, OIDC, and OAuth2 plugins to protect APIs without changing upstream services.
  name: Authentication and Authorization
- description: Apply global or per-consumer rate limits to protect upstream services from traffic spikes.
  name: Rate Limiting and Throttling
- description: Use traffic splitting to gradually roll out new API versions with percentage-based routing.
  name: Canary and Blue-Green Deployments
- description: Replace traditional ingress controllers with APISIX for rich API gateway features in Kubernetes.
  name: Kubernetes Ingress Controller
- description: Collect metrics, traces, and logs via native integrations with Prometheus, Zipkin, and SkyWalking.
  name: API Observability
---
