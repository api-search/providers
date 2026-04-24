---
api_count: 1
apis:
- description: The BFE Management API provides internal monitoring metrics, configuration reload, and Go pprof profiling endpoints. This API should only be exposed on internal networks.
  name: BFE Management API
  slug: bfe-management-api
capabilities:
- description: Workflow capability for managing BFE load balancer operations including runtime metrics collection, configuration hot reload, and observability for infrastructure and platform engineering teams.
  name: BFE Load Balancer Management
  slug: load-balancer-management
common:
- title: ''
  type: Portal
  url: https://www.bfe-networks.net/en_us/
- title: ''
  type: Documentation
  url: https://www.bfe-networks.net/en_us/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bfenetworks
- title: ''
  type: GitHubRepository
  url: https://github.com/bfenetworks/bfe
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/vocabulary/bfe-vocabulary.yaml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/rules/bfe-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/capabilities/load-balancer-management.yaml
created: '2025-01-01'
description: BFE (Beyond Front End) is an open-source layer 7 load balancer developed by Baidu, providing advanced traffic routing, forwarding, and load balancing capabilities with support for HTTP, HTTPS, HTTP/2, WebSocket, TLS, and gRPC. BFE is a CNCF sandbox project licensed under Apache 2.0.
features:
- description: Advanced HTTP/HTTPS/HTTP2 load balancing with pluggable algorithms.
  name: Layer 7 Load Balancing
- description: Extensible plugin system enabling custom traffic management logic.
  name: Plugin Framework
- description: Isolated configuration and routing per tenant.
  name: Multi-tenancy
- description: DSL-based routing rules for fine-grained traffic control.
  name: Advanced Routing
- description: HTTP, HTTPS, SPDY, HTTP/2, gRPC, WebSocket, TLS, FastCGI protocols.
  name: Protocol Support
- description: Built-in metrics, logging, and distributed tracing integration.
  name: Observability
- description: Hot reload of routing and load balancing configuration without restart.
  name: Dynamic Configuration
- description: Hosted as a CNCF sandbox project with active community governance.
  name: CNCF Sandbox
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Export metrics to Prometheus for monitoring and alerting.
  name: Prometheus
- description: Deploy BFE as an ingress controller in Kubernetes clusters.
  name: Kubernetes
- description: Run BFE in Docker containers for containerized deployments.
  name: Docker
- description: Visualize BFE metrics in Grafana dashboards.
  name: Grafana
jsonld:
- class_count: 5
  name: Bfe Context
  property_count: 7
  slug: bfe-context
layout: provider
modified: '2026-04-19'
name: BFE
rules:
- name: BFE API Rules
  rule_count: 22
  severity_counts:
    error: 13
    hint: 0
    info: 1
    warn: 8
  slug: bfe-spectral-rules
skills: []
slug: bfe
solutions: []
tags:
- Load Balancer
- Networking
- Open Source
- Traffic Management
- CNCF
- Baidu
url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/apis.yml
use_cases:
- description: Route and load balance API traffic with per-tenant isolation.
  name: Enterprise API Gateway
- description: Manage east-west and north-south traffic in microservices architectures.
  name: Microservices Traffic Management
- description: Terminate TLS/HTTPS at the edge and forward to backend HTTP services.
  name: TLS Termination
- description: Route fractions of traffic to canary deployments using routing rules.
  name: A/B Testing
- description: Use traffic management plugins to detect and mitigate DDoS attacks.
  name: DDoS Mitigation
---
