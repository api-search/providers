---
api_count: 5
apis:
- description: 'The Tetrate Service Bridge (TSB) Platform API provides programmatic management of the TSB control plane, including organizations, tenants, workspaces, and cluster onboarding. It exposes REST and gRPC '
  name: Tetrate Service Bridge Platform API
  slug: tsb-platform-api
- description: The TSB Gateway API manages ingress and egress gateway configuration for services in a Tetrate Service Bridge environment. It provides resources for defining gateway groups, IngressGateway, EgressGate
  name: Tetrate Service Bridge Gateway API
  slug: tsb-gateway-api
- description: The TSB Traffic API provides configuration resources for managing service-to-service traffic within a Tetrate Service Bridge workspace. It supports traffic groups, TrafficSetting, and ServiceRoute obj
  name: Tetrate Service Bridge Traffic API
  slug: tsb-traffic-api
- description: 'The TSB Security API provides configuration resources for enforcing security policies in a Tetrate Service Bridge environment. It includes security groups, SecuritySetting, and ServiceSecuritySetting '
  name: Tetrate Service Bridge Security API
  slug: tsb-security-api
- description: The TSB Observability API exposes metrics, topology, and service observability data for workloads managed by Tetrate Service Bridge. It provides access to service-level metrics, traffic telemetry, and
  name: Tetrate Service Bridge Observability API
  slug: tsb-observability-api
common:
- title: ''
  type: Website
  url: https://tetrate.io/
- title: ''
  type: Documentation
  url: https://docs.tetrate.io/
- title: ''
  type: Getting Started
  url: https://docs.tetrate.io/service-bridge/latest/quickstart/
- title: ''
  type: Blog
  url: https://tetrate.io/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/tetrateio
- title: ''
  type: GitHubRepository
  url: https://github.com/tetrateio/tetrate
- title: ''
  type: Change Log
  url: https://docs.tetrate.io/service-bridge/latest/release-notes/
- title: ''
  type: Support
  url: https://tetrate.io/contact/
- title: ''
  type: Pricing
  url: https://tetrate.io/tetrate-service-bridge/
- title: ''
  type: Community
  url: https://tetrate.io/community/
created: '2026-03-16'
description: Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, and observability across distributed microservice environments, as well as Tetrate Istio Distro, a vetted upstream Istio distribution with FIPS-verified builds.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-18'
name: Tetrate
skills: []
slug: tetrate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tetrate\nname: Tetrate\ndescription: >-\n  Tetrate is an enterprise service mesh company that provides Tetrate Service\n  Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform\n  built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic,\n  security, and observability across distributed microservice environments, as\n  well as Tetrate Istio Distro, a vetted upstream Istio distribution with\n  FIPS-verified builds.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise\n  - Envoy\n  - Istio\n  - Kubernetes\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: tetrate:tsb-platform-api\n    name: Tetrate Service Bridge Platform API\n    description: >-\n      The Tetrate Service Bridge (TSB) Platform API provides programmatic\n\
  \      management of the TSB control plane, including organizations, tenants,\n      workspaces, and cluster onboarding. It exposes REST and gRPC endpoints\n      for configuring the global service mesh management plane across\n      multi-cluster and multi-cloud environments.\n    humanURL: https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/\n    baseURL: https://docs.tetrate.io/\n    tags:\n      - Management Plane\n      - Multi-Cluster\n      - REST\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/\n      - type: Reference\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/v2/\n  - aid: tetrate:tsb-gateway-api\n    name: Tetrate Service Bridge Gateway API\n    description: >-\n      The TSB Gateway API manages ingress and egress gateway configuration for\n      services in a Tetrate Service Bridge environment. It provides resources\n      for defining gateway groups,\
  \ IngressGateway, EgressGateway, and\n      Tier1Gateway objects that control traffic entering and leaving the mesh\n      across clusters.\n    humanURL: https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/\n    baseURL: https://docs.tetrate.io/\n    tags:\n      - Egress\n      - Gateway\n      - Ingress\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/\n      - type: Reference\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/gateway/v2/\n  - aid: tetrate:tsb-traffic-api\n    name: Tetrate Service Bridge Traffic API\n    description: >-\n      The TSB Traffic API provides configuration resources for managing\n      service-to-service traffic within a Tetrate Service Bridge workspace.\n      It supports traffic groups, TrafficSetting, and ServiceRoute objects\n      that control load balancing, failover, retries, and routing rules for\n      workloads\
  \ in the mesh.\n    humanURL: https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/\n    baseURL: https://docs.tetrate.io/\n    tags:\n      - Load Balancing\n      - Routing\n      - Service Mesh\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/\n      - type: Reference\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/traffic/v2/\n  - aid: tetrate:tsb-security-api\n    name: Tetrate Service Bridge Security API\n    description: >-\n      The TSB Security API provides configuration resources for enforcing\n      security policies in a Tetrate Service Bridge environment. It includes\n      security groups, SecuritySetting, and ServiceSecuritySetting objects\n      for controlling mutual TLS, authorization policies, and access control\n      between workloads across the mesh.\n    humanURL: https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/\n\
  \    baseURL: https://docs.tetrate.io/\n    tags:\n      - Authorization\n      - mTLS\n      - Security\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/\n      - type: Reference\n        url: https://docs.tetrate.io/service-bridge/latest/refs/tsb/security/v2/\n  - aid: tetrate:tsb-observability-api\n    name: Tetrate Service Bridge Observability API\n    description: >-\n      The TSB Observability API exposes metrics, topology, and service\n      observability data for workloads managed by Tetrate Service Bridge.\n      It provides access to service-level metrics, traffic telemetry, and\n      distributed tracing information collected across mesh clusters, enabling\n      monitoring and troubleshooting of distributed applications.\n    humanURL: https://docs.tetrate.io/service-bridge/latest/refs/\n    baseURL: https://docs.tetrate.io/\n    tags:\n      - Metrics\n      - Observability\n\
  \      - Telemetry\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://docs.tetrate.io/service-bridge/latest/refs/\ncommon:\n  - type: Website\n    url: https://tetrate.io/\n  - type: Documentation\n    url: https://docs.tetrate.io/\n  - type: Getting Started\n    url: https://docs.tetrate.io/service-bridge/latest/quickstart/\n  - type: Blog\n    url: https://tetrate.io/blog/\n  - type: GitHub Organization\n    url: https://github.com/tetrateio\n  - type: GitHubRepository\n    url: https://github.com/tetrateio/tetrate\n  - type: Change Log\n    url: https://docs.tetrate.io/service-bridge/latest/release-notes/\n  - type: Support\n    url: https://tetrate.io/contact/\n  - type: Pricing\n    url: https://tetrate.io/tetrate-service-bridge/\n  - type: Community\n    url: https://tetrate.io/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/apis.yml
tags:
- Enterprise
- Envoy
- Istio
- Kubernetes
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/tetrate/refs/heads/main/apis.yml
use_cases: []
---
