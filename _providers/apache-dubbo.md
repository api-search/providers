---
api_count: 3
api_specs:
- filename: apache-dubbo-admin-openapi-original.json
  format: json
  label: Apache Dubbo Admin API
  slug: apache-dubbo-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/openapi/apache-dubbo-admin-openapi-original.json
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-dubbo\nname: Apache Dubbo\ndescription: >-\n  Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for Java, Go, Node.js, Python, Rust, and Erlang.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Go\n  - Java\n  - Microservices\n  - Open Source\n  - RPC\n  - Service Discovery\n  - Service Mesh\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-dubbo:apache-dubbo-admin\n    name: Apache Dubbo Admin API\n    description: >-\n      The Dubbo Admin REST API provides service\
  \ governance operations for managing services, instances, traffic rules, load balancing, route policies, and dynamic configuration in a Dubbo microservices cluster.\n    humanURL: https://github.com/apache/dubbo-admin\n    tags:\n      - Admin\n      - Governance\n      - REST\n      - Service Management\n    properties:\n      - type: Documentation\n        url: https://dubbo.apache.org/en/overview/reference/admin/\n      - type: OpenAPI\n        url: openapi/apache-dubbo-admin-openapi-original.json\n      - type: GitHubRepository\n        url: https://github.com/apache/dubbo-admin\n\n  - aid: apache-dubbo:apache-dubbo-java\n    name: Apache Dubbo Java SDK\n    description: >-\n      The core Apache Dubbo Java framework providing RPC service definition, publishing, invocation, and service governance APIs for building enterprise microservices in Java and Spring Boot.\n    humanURL: https://dubbo.apache.org/en/overview/mannual/java-sdk/\n    tags:\n      - Java\n      - RPC\n      - SDK\n\
  \      - Spring Boot\n    properties:\n      - type: Documentation\n        url: https://dubbo.apache.org/en/overview/mannual/java-sdk/\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.dubbo/dubbo\n        title: Java SDK (Maven Central)\n      - type: GitHubRepository\n        url: https://github.com/apache/dubbo\n\n  - aid: apache-dubbo:apache-dubbo-go\n    name: Apache Dubbo Go SDK\n    description: >-\n      The Go implementation of Apache Dubbo, providing the same RPC framework capabilities including service discovery, traffic management, and Triple protocol support for Go-based microservices.\n    humanURL: https://dubbo.apache.org/en/overview/mannual/golang-sdk/\n    tags:\n      - Go\n      - Golang\n      - RPC\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://dubbo.apache.org/en/overview/mannual/golang-sdk/\n      - type: GitHubRepository\n        url: https://github.com/apache/dubbo-go\n\ncommon:\n  - type: GitHubOrganization\n\
  \    url: https://github.com/apache\n    title: Apache GitHub Organization\n  - type: GitHubRepository\n    url: https://github.com/apache/dubbo\n    title: Apache Dubbo Java (Main Repo)\n  - type: GitHubRepository\n    url: https://github.com/apache/dubbo-go\n    title: Apache Dubbo Go\n  - type: GitHubRepository\n    url: https://github.com/apache/dubbo-admin\n    title: Apache Dubbo Admin\n  - type: GitHubRepository\n    url: https://github.com/apache/dubbo-kubernetes\n    title: Apache Dubbo Kubernetes\n  - type: Documentation\n    url: https://dubbo.apache.org/en/overview/\n  - type: GettingStarted\n    url: https://dubbo.apache.org/en/overview/quickstart/\n  - type: Blog\n    url: https://dubbo.apache.org/en/blog/\n  - type: ReleaseNotes\n    url: https://github.com/apache/dubbo/releases\n  - type: SpectralRules\n    url: rules/apache-dubbo-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-dubbo-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/dubbo-service-governance.yaml\n\
  \  - type: Features\n    data:\n      - name: Triple Protocol (gRPC Compatible)\n        description: HTTP/2-based RPC protocol fully compatible with gRPC, supporting streaming communication and cross-language interoperability.\n      - name: Service Discovery\n        description: High-performance application-level service discovery supporting Nacos, Zookeeper, Kubernetes, Consul, Etcd, and Redis registries.\n      - name: Traffic Management\n        description: Advanced traffic control with conditional routing, tag routing, gray releases, and percentage-based traffic splitting.\n      - name: Load Balancing\n        description: Multiple load balancing strategies including weighted random, round-robin, least active, and consistent hashing.\n      - name: Rate Limiting and Circuit Breaking\n        description: Built-in rate limiting, circuit breaker, and service degradation capabilities for resilient microservices.\n      - name: Observability\n        description: Full-link tracing\
  \ via OpenTelemetry, Prometheus metrics, Grafana dashboards, Zipkin, and SkyWalking integration.\n      - name: Multi-Language SDK Support\n        description: Official SDKs for Java, Go, Node.js, Python, Rust, and Erlang enabling polyglot microservices architectures.\n      - name: Service Mesh Integration\n        description: Native Istio integration with xDS protocol support for deploying Dubbo services in service mesh environments.\n      - name: Dubbo Admin Console\n        description: Visual cluster management UI for service governance, traffic rules, configuration, and monitoring.\n      - name: Pixiu Gateway\n        description: HTTP/gRPC gateway (Pixiu) enabling REST HTTP clients to access Dubbo backend services.\n  - type: UseCases\n    data:\n      - name: Enterprise Microservices\n        description: Build high-performance Java or Go microservices with RPC communication, service discovery, and traffic governance.\n      - name: gRPC Migration\n        description: Adopt\
  \ the Triple protocol as a drop-in gRPC-compatible alternative with richer governance capabilities.\n      - name: Cross-Language Service Communication\n        description: Enable polyglot microservices with Java, Go, Node.js, Python, Rust, and Erlang services communicating via Dubbo protocols.\n      - name: Service Mesh Deployment\n        description: Run Dubbo services in Istio-managed service meshes using xDS protocol for sidecar-free or sidecar-based deployments.\n      - name: Cloud-Native Kubernetes Deployment\n        description: Deploy and manage Dubbo services on Kubernetes using the Dubbo Kubernetes operator and control plane.\n      - name: API Gateway Integration\n        description: Expose internal Dubbo RPC services as REST HTTP endpoints through the Pixiu API gateway.\n  - type: Integrations\n    data:\n      - name: Nacos\n        description: Service registry and configuration center integration for service discovery and dynamic configuration.\n      - name: Zookeeper\n\
  \        description: Apache Zookeeper integration for service registry and coordination.\n      - name: Kubernetes\n        description: Native Kubernetes service discovery and deployment orchestration support.\n      - name: Istio\n        description: Service mesh integration with Istio using xDS protocol for traffic management.\n      - name: Prometheus\n        description: Metrics export to Prometheus for monitoring Dubbo service performance.\n      - name: Grafana\n        description: Pre-built Grafana dashboards for visualizing Dubbo service metrics.\n      - name: OpenTelemetry\n        description: Distributed tracing via OpenTelemetry standard for end-to-end request tracking.\n      - name: Zipkin\n        description: Distributed tracing integration with Zipkin for request flow visualization.\n      - name: SkyWalking\n        description: Apache SkyWalking APM integration for distributed tracing and service performance monitoring.\n      - name: Seata\n        description:\
  \ Apache Seata integration for distributed transaction management across Dubbo services.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml
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
