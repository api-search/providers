---
api_count: 5
apis:
- description: Kong Gateway is an open-source, lightweight API gateway optimized for microservices, delivering unparalleled latency performance and scalability through a rich plugin ecosystem.
  name: Kong Gateway
  slug: kong
- description: The Kong Gateway Admin API provides a RESTful interface for configuring and managing Kong Gateway instances, including services, routes, plugins, consumers, and certificates. It is used by operators t
  name: Kong Gateway Admin API
  slug: kong-admin-api
- description: The Kong Konnect API provides a programmatic interface for managing the Konnect cloud platform, including control planes, API products, teams, system accounts, and developer portal configuration. It i
  name: Kong Konnect API
  slug: kong-konnect-api
- description: Kong Mesh is an enterprise-grade service mesh built on top of Kuma and Envoy, providing universal service mesh capabilities across Kubernetes and virtual machine environments. It supports mTLS, traffi
  name: Kong Mesh
  slug: kong-mesh
- description: Kong Insomnia is an open-source API development platform for designing, debugging, and testing APIs. It supports REST, GraphQL, gRPC, and WebSocket protocols and provides collections, environments, mo
  name: Kong Insomnia
  slug: kong-insomnia
capabilities:
- description: API gateway management workflow for platform engineers to configure services, routes, plugins, consumers, upstreams, and TLS certificates on Kong Gateway instances.
  name: Kong API Gateway Management
  slug: api-gateway-management
common:
- title: ''
  type: Documentation
  url: https://developer.konghq.com/
- title: ''
  type: GettingStarted
  url: https://docs.konghq.com/gateway/latest/get-started/
- title: ''
  type: Blog
  url: https://konghq.com/blog
- title: ''
  type: ChangeLog
  url: https://developer.konghq.com/gateway/changelog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Kong
- title: ''
  type: GitHubRepository
  url: https://github.com/Kong/kong
- title: ''
  type: SDK
  url: https://github.com/Kong/sdk-konnect-go
- title: ''
  type: CLI
  url: https://github.com/Kong/kongctl
- title: ''
  type: Support
  url: https://discuss.konghq.com/
- title: ''
  type: JSONSchema
  url: json-schema/kong-service-schema.json
- title: ''
  type: JSONLD
  url: json-ld/kong-context.jsonld
created: '2026-03-18'
description: Kong Gateway is the world's most popular open-source API gateway, built on NGINX and Lua, offering a plugin ecosystem for authentication, rate limiting, observability, and traffic management at any scale.
features:
- description: Extensible plugin architecture for authentication, rate limiting, logging, transformations, and custom business logic.
  name: Plugin Ecosystem
- description: Define upstream services and routing rules to direct client requests to the correct backend services.
  name: Service and Route Management
- description: Create and manage API consumers with per-consumer authentication credentials and plugin configurations.
  name: Consumer Management
- description: Built-in upstream load balancing with health checks, circuit breaking, and weighted target distribution.
  name: Load Balancing
- description: Manage TLS certificates and SNI mappings for secure HTTPS traffic termination at the gateway.
  name: TLS Certificate Management
- description: Configure Kong Gateway declaratively using decK or the Admin API for infrastructure-as-code workflows.
  name: Declarative Configuration
- description: Centralized cloud control plane for managing multiple Kong Gateway instances, teams, and API products.
  name: Kong Konnect Cloud Platform
- description: Enterprise service mesh built on Kuma and Envoy for mTLS, traffic policies, and multi-zone deployments.
  name: Service Mesh with Kong Mesh
image: /assets/icons/kong.png
integrations:
- description: Deploy Kong Gateway as a Kubernetes Ingress Controller with CRD-based configuration for cloud-native environments.
  name: Kubernetes
- description: Export gateway metrics to Prometheus and visualize API performance and health in Grafana dashboards.
  name: Prometheus and Grafana
- description: Distributed tracing integration with OpenTelemetry for end-to-end request visibility across services.
  name: OpenTelemetry
- description: Secrets management integration for storing and retrieving API keys, certificates, and credentials.
  name: HashiCorp Vault
- description: Send gateway logs, metrics, and traces to Datadog for comprehensive API monitoring and alerting.
  name: Datadog
jsonld:
- class_count: 2
  name: Kong Context
  property_count: 7
  slug: kong-context
- class_count: 0
  name: Kong Gateway Admin Context
  property_count: 0
  slug: kong-gateway-admin-context
layout: provider
modified: '2026-04-18'
name: Kong
rules:
- name: Kong API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: kong-spectral-rules
skills: []
slug: kong
solutions: []
source_yaml: "aid: kong\nname: Kong\ndescription: >-\n  Kong Gateway is the world's most popular open-source API gateway, built on\n  NGINX and Lua, offering a plugin ecosystem for authentication, rate limiting,\n  observability, and traffic management at any scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Lua\n  - NGINX\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: kong:kong\n    name: Kong Gateway\n    description: >-\n      Kong Gateway is an open-source, lightweight API gateway optimized for\n      microservices, delivering unparalleled latency performance and scalability\n      through a rich plugin ecosystem.\n    humanURL: https://konghq.com/products/kong-gateway\n    tags:\n      - API Gateway\n      - Open Source\n    properties:\n      - type:\
  \ Documentation\n        url: https://developer.konghq.com/gateway/\n      - type: GettingStarted\n        url: https://docs.konghq.com/gateway/latest/get-started/\n      - type: ChangeLog\n        url: https://developer.konghq.com/gateway/changelog/\n      - type: GitHubRepository\n        url: https://github.com/Kong/kong\n  - aid: kong:kong-admin-api\n    name: Kong Gateway Admin API\n    description: >-\n      The Kong Gateway Admin API provides a RESTful interface for configuring\n      and managing Kong Gateway instances, including services, routes, plugins,\n      consumers, and certificates. It is used by operators to configure the\n      gateway programmatically or via decK declarative configuration.\n    humanURL: https://developer.konghq.com/admin-api/\n    baseURL: https://konghq.com/\n    tags:\n      - Admin API\n      - Configuration\n      - Gateway\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developer.konghq.com/admin-api/\n  \
  \    - type: OpenAPI\n        url: openapi/kong-gateway-admin-api.yml\n      - type: JSONSchema\n        url: json-schema/kong-service-schema.json\n      - type: JSONLD\n        url: json-ld/kong-context.jsonld\n      - type: GitHubRepository\n        url: https://github.com/Kong/kong\n  - aid: kong:kong-konnect-api\n    name: Kong Konnect API\n    description: >-\n      The Kong Konnect API provides a programmatic interface for managing the\n      Konnect cloud platform, including control planes, API products, teams,\n      system accounts, and developer portal configuration. It is used to\n      automate Konnect operations and integrate with CI/CD pipelines.\n    humanURL: https://developer.konghq.com/konnect-api/\n    baseURL: https://konghq.com/\n    tags:\n      - Cloud\n      - Konnect\n      - Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developer.konghq.com/konnect-api/\n      - type: APIReference\n        url: https://developer.konghq.com/api/\n\
  \      - type: Authentication\n        url: https://developer.konghq.com/konnect-api/\n      - type: GitHubRepository\n        url: https://github.com/Kong/kong\n  - aid: kong:kong-mesh\n    name: Kong Mesh\n    description: >-\n      Kong Mesh is an enterprise-grade service mesh built on top of Kuma and\n      Envoy, providing universal service mesh capabilities across Kubernetes and\n      virtual machine environments. It supports mTLS, traffic policies, service\n      discovery, observability, and multi-zone deployments.\n    humanURL: https://developer.konghq.com/mesh/\n    baseURL: https://konghq.com/\n    tags:\n      - Envoy\n      - Kubernetes\n      - mTLS\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://developer.konghq.com/mesh/\n      - type: ChangeLog\n        url: https://developer.konghq.com/mesh/changelog/\n      - type: GettingStarted\n        url: https://developer.konghq.com/mesh/\n  - aid: kong:kong-insomnia\n    name: Kong Insomnia\n\
  \    description: >-\n      Kong Insomnia is an open-source API development platform for designing,\n      debugging, and testing APIs. It supports REST, GraphQL, gRPC, and\n      WebSocket protocols and provides collections, environments, mock servers,\n      and OpenAPI spec editing for developers.\n    humanURL: https://developer.konghq.com/insomnia/\n    baseURL: https://konghq.com/\n    tags:\n      - API Client\n      - Developer Tools\n      - Open Source\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://developer.konghq.com/insomnia/\n      - type: GitHubRepository\n        url: https://github.com/Kong/insomnia\ncommon:\n  - type: Documentation\n    url: https://developer.konghq.com/\n  - type: GettingStarted\n    url: https://docs.konghq.com/gateway/latest/get-started/\n  - type: Blog\n    url: https://konghq.com/blog\n  - type: ChangeLog\n    url: https://developer.konghq.com/gateway/changelog/\n  - type: GitHubOrganization\n    url: https://github.com/Kong\n\
  \  - type: GitHubRepository\n    url: https://github.com/Kong/kong\n  - type: SDK\n    url: https://github.com/Kong/sdk-konnect-go\n    name: Kong Konnect Go SDK\n  - type: CLI\n    url: https://github.com/Kong/kongctl\n    name: Kong Developer CLI\n  - type: Support\n    url: https://discuss.konghq.com/\n  - type: JSONSchema\n    url: json-schema/kong-service-schema.json\n  - type: JSONLD\n    url: json-ld/kong-context.jsonld\n  - type: Features\n    data:\n      - name: Plugin Ecosystem\n        description: Extensible plugin architecture for authentication, rate limiting, logging, transformations, and custom business logic.\n      - name: Service and Route Management\n        description: Define upstream services and routing rules to direct client requests to the correct backend services.\n      - name: Consumer Management\n        description: Create and manage API consumers with per-consumer authentication credentials and plugin configurations.\n      - name: Load Balancing\n    \
  \    description: Built-in upstream load balancing with health checks, circuit breaking, and weighted target distribution.\n      - name: TLS Certificate Management\n        description: Manage TLS certificates and SNI mappings for secure HTTPS traffic termination at the gateway.\n      - name: Declarative Configuration\n        description: Configure Kong Gateway declaratively using decK or the Admin API for infrastructure-as-code workflows.\n      - name: Kong Konnect Cloud Platform\n        description: Centralized cloud control plane for managing multiple Kong Gateway instances, teams, and API products.\n      - name: Service Mesh with Kong Mesh\n        description: Enterprise service mesh built on Kuma and Envoy for mTLS, traffic policies, and multi-zone deployments.\n  - type: UseCases\n    data:\n      - name: API Gateway for Microservices\n        description: Route, secure, and observe traffic to microservices with authentication, rate limiting, and request transformations.\n\
  \      - name: Multi-Cloud API Management\n        description: Manage APIs across hybrid and multi-cloud environments with centralized control through Kong Konnect.\n      - name: Zero-Trust Security\n        description: Implement zero-trust security with mTLS, OAuth2, JWT validation, and API key authentication at the gateway layer.\n      - name: API Lifecycle Management\n        description: Manage the full API lifecycle from design with Insomnia to deployment and monitoring with Kong Gateway.\n      - name: Rate Limiting and Traffic Control\n        description: Protect backend services with configurable rate limiting, request size limits, and traffic shaping policies.\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: Deploy Kong Gateway as a Kubernetes Ingress Controller with CRD-based configuration for cloud-native environments.\n      - name: Prometheus and Grafana\n        description: Export gateway metrics to Prometheus and visualize API performance\
  \ and health in Grafana dashboards.\n      - name: OpenTelemetry\n        description: Distributed tracing integration with OpenTelemetry for end-to-end request visibility across services.\n      - name: HashiCorp Vault\n        description: Secrets management integration for storing and retrieving API keys, certificates, and credentials.\n      - name: Datadog\n        description: Send gateway logs, metrics, and traces to Datadog for comprehensive API monitoring and alerting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml
tags:
- API Gateway
- Lua
- NGINX
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml
use_cases:
- description: Route, secure, and observe traffic to microservices with authentication, rate limiting, and request transformations.
  name: API Gateway for Microservices
- description: Manage APIs across hybrid and multi-cloud environments with centralized control through Kong Konnect.
  name: Multi-Cloud API Management
- description: Implement zero-trust security with mTLS, OAuth2, JWT validation, and API key authentication at the gateway layer.
  name: Zero-Trust Security
- description: Manage the full API lifecycle from design with Insomnia to deployment and monitoring with Kong Gateway.
  name: API Lifecycle Management
- description: Protect backend services with configurable rate limiting, request size limits, and traffic shaping policies.
  name: Rate Limiting and Traffic Control
---
