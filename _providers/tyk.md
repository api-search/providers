---
api_count: 4
api_specs:
- filename: tyk-gateway-api-openapi.yml
  format: yaml
  label: Tyk Gateway API
  slug: tyk-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/openapi/tyk-gateway-api-openapi.yml
- filename: tyk-dashboard-api-openapi.yml
  format: yaml
  label: Tyk Dashboard API
  slug: tyk-dashboard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/openapi/tyk-dashboard-api-openapi.yml
- filename: tyk-dashboard-admin-api-openapi.yml
  format: yaml
  label: Tyk Dashboard Admin API
  slug: tyk-dashboard-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/openapi/tyk-dashboard-admin-api-openapi.yml
- filename: tyk-mdcb-api-openapi.yml
  format: yaml
  label: Tyk MDCB API
  slug: tyk-mdcb-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/openapi/tyk-mdcb-api-openapi.yml
apis:
- description: The Tyk Gateway API provides a RESTful interface for managing API definitions, keys, certificates, and health checks directly on a Tyk Gateway node. It is used to configure and operate the gateway pro
  name: Tyk Gateway API
  slug: tyk-gateway-api
- description: The Tyk Dashboard API is a superset of the Gateway API providing programmatic access to a centralized database of API definitions, keys, policies, users, and organizations. It is the primary integrati
  name: Tyk Dashboard API
  slug: tyk-dashboard-api
- description: The Tyk Dashboard Admin API provides super-administrative access to the Tyk Dashboard, enabling management of organizations and system-level configuration. It is used for bootstrapping and managing mu
  name: Tyk Dashboard Admin API
  slug: tyk-dashboard-admin-api
- description: The Tyk Multi Data Centre Bridge (MDCB) API enables synchronization of API configurations, keys, and policies across geographically distributed Tyk Gateway clusters. It provides a control plane for ma
  name: Tyk MDCB API
  slug: tyk-mdcb-api
capabilities:
- description: Unified API management workflow combining Gateway and Dashboard APIs for API developers and platform engineers to manage API definitions, keys, policies, and portal configurations.
  name: Tyk API Management
  slug: api-management
- description: Platform administration workflow combining Dashboard Admin and MDCB APIs for platform administrators to manage organizations, multi-data center deployments, and system diagnostics.
  name: Tyk Platform Administration
  slug: platform-administration
common:
- title: ''
  type: Portal
  url: https://tyk.io/
- title: ''
  type: Documentation
  url: https://tyk.io/docs/
- title: ''
  type: GettingStarted
  url: https://tyk.io/docs/getting-started/
- title: ''
  type: Authentication
  url: https://tyk.io/docs/basic-config-and-security/security/authentication-authorization/
- title: ''
  type: Blog
  url: https://tyk.io/blog/
- title: ''
  type: ChangeLog
  url: https://tyk.io/docs/developer-support/release-notes/dashboard
- title: ''
  type: GitHubOrganization
  url: https://github.com/TykTechnologies
- title: ''
  type: GitHubRepository
  url: https://github.com/TykTechnologies/tyk
- title: ''
  type: Support
  url: https://community.tyk.io/
- title: ''
  type: FAQ
  url: https://tyk.io/docs/frequently-asked-questions/
- title: ''
  type: Pricing
  url: https://tyk.io/price-comparison/
- title: ''
  type: CLI
  url: https://github.com/TykTechnologies/tyk-cli
- title: Go Gateway SDK
  type: SDK
  url: https://github.com/TykTechnologies/tyk
- title: ''
  type: SpectralRules
  url: rules/tyk-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tyk-vocabulary.yaml
created: '2026-03-18'
description: Tyk is an open-source API gateway and management platform supporting REST, GraphQL, gRPC, and Async APIs with a developer portal, analytics, and flexible deployment across cloud, on-premise, and hybrid environments.
features:
- description: High-performance, open-source API gateway supporting REST, GraphQL, gRPC, TCP, and async APIs with low-latency request proxying.
  name: API Gateway
- description: Configurable rate limiting and throttling policies to protect backend services from traffic spikes and abuse.
  name: Rate Limiting
- description: Multiple authentication methods including API keys, JWT, OAuth 2.0, mutual TLS, OpenID Connect, and basic auth.
  name: Authentication
- description: Real-time API analytics, traffic monitoring, and detailed logging with export to multiple backend stores.
  name: Analytics and Monitoring
- description: Customizable developer portal for API documentation, key management, and developer onboarding.
  name: Developer Portal
- description: Native GraphQL proxy and Universal Data Graph for federating REST and GraphQL APIs into a single graph endpoint.
  name: GraphQL Support
- description: Built-in support for API versioning with URL, header, and query parameter-based version routing.
  name: API Versioning
- description: Centralized access control policies for managing rate limits, quotas, and access rights across multiple APIs.
  name: Policy Management
- description: MDCB enables synchronization of API configurations and keys across geographically distributed gateway clusters.
  name: Multi Data Center
- description: Extensible middleware plugin system supporting Go, Python, JavaScript, Lua, and gRPC-based custom plugins.
  name: Plugin System
- description: Tyk AI Studio provides an AI gateway for managing, governing, and interacting with AI models across your organization.
  name: AI Gateway
image: /assets/icons/tyk.png
integrations:
- description: Tyk Operator provides native Kubernetes integration for managing API definitions and policies as custom resources.
  name: Kubernetes
- description: Infrastructure-as-code provider for managing Tyk configurations through Terraform.
  name: Terraform
- description: Integration with Keycloak for OAuth 2.0 and OpenID Connect authentication flows.
  name: Keycloak
- description: Support for Auth0 as an identity provider for JWT validation and OAuth 2.0 token management.
  name: Auth0
- description: Export gateway metrics to Prometheus for monitoring and alerting with Grafana dashboards.
  name: Prometheus
- description: Distributed tracing integration with OpenTelemetry for end-to-end request visibility.
  name: OpenTelemetry
- description: Backstage plugin for viewing and managing Tyk API definitions from within the Backstage developer portal.
  name: Backstage
- description: CI/CD integration for automated API deployment and configuration updates through Jenkins pipelines.
  name: Jenkins
- description: Ansible playbooks for automated Tyk gateway and dashboard provisioning and configuration.
  name: Ansible
- description: Official Helm charts for deploying Tyk components on Kubernetes clusters.
  name: Helm Charts
jsonld:
- class_count: 0
  name: Tyk Gateway Context
  property_count: 0
  slug: tyk-gateway-context
- class_count: 0
  name: Tyk Mdcb Context
  property_count: 0
  slug: tyk-mdcb-context
layout: provider
modified: '2026-04-19'
name: Tyk
rules:
- name: Tyk API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: tyk-spectral-rules
skills: []
slug: tyk
solutions: []
source_filename: apis.yml
source_yaml: "aid: tyk\nname: Tyk\ndescription: >-\n  Tyk is an open-source API gateway and management platform supporting REST,\n  GraphQL, gRPC, and Async APIs with a developer portal, analytics, and\n  flexible deployment across cloud, on-premise, and hybrid environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - GraphQL\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/apis.yml\nhumanURL: https://tyk.io/\ncreated: '2026-03-18'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\naccess: 3rd-Party\nposition: Consuming\napis:\n  - aid: tyk:tyk-gateway-api\n    name: Tyk Gateway API\n    description: >-\n      The Tyk Gateway API provides a RESTful interface for managing API\n      definitions, keys, certificates, and health checks directly on a Tyk\n      Gateway node. It is used to configure and operate the gateway\n      programmatically\
  \ in self-managed and open-source deployments.\n    humanURL: https://tyk.io/docs/tyk-apis/\n    baseURL: https://tyk.io/\n    tags:\n      - Administration\n      - Gateway\n      - Open Source\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://tyk.io/docs/tyk-apis/\n      - type: OpenAPI\n        url: openapi/tyk-gateway-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tyk-gateway-access-definition-schema.json\n      - type: JSONLD\n        url: json-ld/tyk-gateway-context.jsonld\n      - type: GitHubRepository\n        url: https://github.com/TykTechnologies/tyk\n  - aid: tyk:tyk-dashboard-api\n    name: Tyk Dashboard API\n    description: >-\n      The Tyk Dashboard API is a superset of the Gateway API providing\n      programmatic access to a centralized database of API definitions, keys,\n      policies, users, and organizations. It is the primary integration point\n      for managing multi-team Tyk deployments and is authenticated\
  \ via an\n      access credentials header.\n    humanURL: https://tyk.io/docs/tyk-dashboard-api\n    baseURL: https://tyk.io/\n    tags:\n      - Administration\n      - Dashboard\n      - Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://tyk.io/docs/tyk-dashboard-api\n      - type: OpenAPI\n        url: openapi/tyk-dashboard-api-openapi.yml\n      - type: ChangeLog\n        url: https://tyk.io/docs/developer-support/release-notes/dashboard\n      - type: GitHubRepository\n        url: https://github.com/TykTechnologies/tyk-analytics\n  - aid: tyk:tyk-dashboard-admin-api\n    name: Tyk Dashboard Admin API\n    description: >-\n      The Tyk Dashboard Admin API provides super-administrative access to the\n      Tyk Dashboard, enabling management of organizations and system-level\n      configuration. It is used for bootstrapping and managing multi-organization\n      Tyk deployments.\n    humanURL: https://tyk.io/docs/tyk-dashboard-api\n  \
  \  baseURL: https://tyk.io/\n    tags:\n      - Admin\n      - Dashboard\n      - Multi-Tenant\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://tyk.io/docs/tyk-dashboard-api\n      - type: OpenAPI\n        url: openapi/tyk-dashboard-admin-api-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/TykTechnologies/tyk-analytics\n  - aid: tyk:tyk-mdcb-api\n    name: Tyk MDCB API\n    description: >-\n      The Tyk Multi Data Centre Bridge (MDCB) API enables synchronization of\n      API configurations, keys, and policies across geographically distributed\n      Tyk Gateway clusters. It provides a control plane for managing multiple\n      data center deployments from a single Tyk Dashboard.\n    humanURL: https://tyk.io/docs/\n    baseURL: https://tyk.io/\n    tags:\n      - MDCB\n      - Multi-Data Center\n      - REST API\n      - Synchronization\n    properties:\n      - type: Documentation\n        url: https://tyk.io/docs/\n\
  \      - type: OpenAPI\n        url: openapi/tyk-mdcb-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tyk-mdcb-data-plane-config-schema.json\n      - type: JSONLD\n        url: json-ld/tyk-mdcb-context.jsonld\n      - type: GitHubRepository\n        url: https://github.com/TykTechnologies/tyk-sink\ncommon:\n  - type: Portal\n    url: https://tyk.io/\n  - type: Documentation\n    url: https://tyk.io/docs/\n  - type: GettingStarted\n    url: https://tyk.io/docs/getting-started/\n  - type: Authentication\n    url: https://tyk.io/docs/basic-config-and-security/security/authentication-authorization/\n  - type: Blog\n    url: https://tyk.io/blog/\n  - type: ChangeLog\n    url: https://tyk.io/docs/developer-support/release-notes/dashboard\n  - type: GitHubOrganization\n    url: https://github.com/TykTechnologies\n  - type: GitHubRepository\n    url: https://github.com/TykTechnologies/tyk\n  - type: Support\n    url: https://community.tyk.io/\n  - type: FAQ\n    url: https://tyk.io/docs/frequently-asked-questions/\n\
  \  - type: Pricing\n    url: https://tyk.io/price-comparison/\n  - type: CLI\n    url: https://github.com/TykTechnologies/tyk-cli\n  - type: SDK\n    url: https://github.com/TykTechnologies/tyk\n    title: Go Gateway SDK\n  - type: SpectralRules\n    url: rules/tyk-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/tyk-vocabulary.yaml\n  - type: Features\n    data:\n      - name: API Gateway\n        description: >-\n          High-performance, open-source API gateway supporting REST, GraphQL,\n          gRPC, TCP, and async APIs with low-latency request proxying.\n      - name: Rate Limiting\n        description: >-\n          Configurable rate limiting and throttling policies to protect backend\n          services from traffic spikes and abuse.\n      - name: Authentication\n        description: >-\n          Multiple authentication methods including API keys, JWT, OAuth 2.0,\n          mutual TLS, OpenID Connect, and basic auth.\n      - name: Analytics and Monitoring\n \
  \       description: >-\n          Real-time API analytics, traffic monitoring, and detailed logging\n          with export to multiple backend stores.\n      - name: Developer Portal\n        description: >-\n          Customizable developer portal for API documentation, key management,\n          and developer onboarding.\n      - name: GraphQL Support\n        description: >-\n          Native GraphQL proxy and Universal Data Graph for federating REST and\n          GraphQL APIs into a single graph endpoint.\n      - name: API Versioning\n        description: >-\n          Built-in support for API versioning with URL, header, and query\n          parameter-based version routing.\n      - name: Policy Management\n        description: >-\n          Centralized access control policies for managing rate limits, quotas,\n          and access rights across multiple APIs.\n      - name: Multi Data Center\n        description: >-\n          MDCB enables synchronization of API configurations\
  \ and keys across\n          geographically distributed gateway clusters.\n      - name: Plugin System\n        description: >-\n          Extensible middleware plugin system supporting Go, Python, JavaScript,\n          Lua, and gRPC-based custom plugins.\n      - name: AI Gateway\n        description: >-\n          Tyk AI Studio provides an AI gateway for managing, governing, and\n          interacting with AI models across your organization.\n  - type: UseCases\n    data:\n      - name: API Monetization\n        description: >-\n          Enable API-as-a-product strategies with tiered plans, usage tracking,\n          and developer self-service through the portal.\n      - name: Microservices Gateway\n        description: >-\n          Centralize traffic management, authentication, and observability for\n          microservices architectures.\n      - name: Multi-Cloud API Management\n        description: >-\n          Deploy gateways across cloud, on-premise, and hybrid environments\n\
  \          with centralized management.\n      - name: Legacy API Modernization\n        description: >-\n          Wrap legacy SOAP and XML APIs with modern REST or GraphQL interfaces\n          using Tyk's transformation middleware.\n      - name: Partner API Program\n        description: >-\n          Manage third-party developer access with fine-grained policies,\n          quota management, and analytics per consumer.\n      - name: AI API Management\n        description: >-\n          Govern and manage AI model APIs with rate limiting, access control,\n          and usage analytics through Tyk AI Studio.\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: >-\n          Tyk Operator provides native Kubernetes integration for managing API\n          definitions and policies as custom resources.\n      - name: Terraform\n        description: >-\n          Infrastructure-as-code provider for managing Tyk configurations\n          through Terraform.\n  \
  \    - name: Keycloak\n        description: >-\n          Integration with Keycloak for OAuth 2.0 and OpenID Connect\n          authentication flows.\n      - name: Auth0\n        description: >-\n          Support for Auth0 as an identity provider for JWT validation and\n          OAuth 2.0 token management.\n      - name: Prometheus\n        description: >-\n          Export gateway metrics to Prometheus for monitoring and alerting\n          with Grafana dashboards.\n      - name: OpenTelemetry\n        description: >-\n          Distributed tracing integration with OpenTelemetry for end-to-end\n          request visibility.\n      - name: Backstage\n        description: >-\n          Backstage plugin for viewing and managing Tyk API definitions from\n          within the Backstage developer portal.\n      - name: Jenkins\n        description: >-\n          CI/CD integration for automated API deployment and configuration\n          updates through Jenkins pipelines.\n      - name: Ansible\n\
  \        description: >-\n          Ansible playbooks for automated Tyk gateway and dashboard\n          provisioning and configuration.\n      - name: Helm Charts\n        description: >-\n          Official Helm charts for deploying Tyk components on Kubernetes\n          clusters.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- GraphQL
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/tyk/refs/heads/main/apis.yml
use_cases:
- description: Enable API-as-a-product strategies with tiered plans, usage tracking, and developer self-service through the portal.
  name: API Monetization
- description: Centralize traffic management, authentication, and observability for microservices architectures.
  name: Microservices Gateway
- description: Deploy gateways across cloud, on-premise, and hybrid environments with centralized management.
  name: Multi-Cloud API Management
- description: Wrap legacy SOAP and XML APIs with modern REST or GraphQL interfaces using Tyk's transformation middleware.
  name: Legacy API Modernization
- description: Manage third-party developer access with fine-grained policies, quota management, and analytics per consumer.
  name: Partner API Program
- description: Govern and manage AI model APIs with rate limiting, access control, and usage analytics through Tyk AI Studio.
  name: AI API Management
---
