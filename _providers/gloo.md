---
api_count: 4
apis:
- description: Gloo Edge is a feature-rich, Kubernetes-native ingress controller and API gateway built on Envoy Proxy, supporting advanced routing, security policies, and observability for cloud-native workloads. It
  name: Gloo Edge
  slug: gloo-edge
- description: Gloo Gateway is the next-generation API gateway from Solo.io built on Envoy Proxy and implementing the Kubernetes Gateway API specification. It provides advanced traffic management, security, and exte
  name: Gloo Gateway
  slug: gloo-gateway
- description: Gloo Mesh is an enterprise service mesh management platform from Solo.io built on Istio, providing multi-cluster and multi-mesh traffic management, security policy enforcement, and observability acros
  name: Gloo Mesh
  slug: gloo-mesh
- description: Gloo Portal is a developer portal product from Solo.io that enables organizations to expose, document, and manage API products for internal and external consumers. It integrates with Gloo Gateway to p
  name: Gloo Portal
  slug: gloo-portal
common:
- title: ''
  type: Website
  url: https://www.solo.io/
- title: ''
  type: Portal
  url: https://www.solo.io/products/
- title: ''
  type: Documentation
  url: https://docs.solo.io/
- title: ''
  type: Getting Started
  url: https://docs.solo.io/gloo-edge/latest/getting_started/
- title: ''
  type: Blog
  url: https://www.solo.io/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/solo-io
- title: ''
  type: GitHubRepository
  url: https://github.com/solo-io/gloo
- title: ''
  type: Change Log
  url: https://github.com/solo-io/gloo/releases
- title: ''
  type: Community
  url: https://slack.solo.io/
- title: ''
  type: Support
  url: https://www.solo.io/company/contact/
- title: ''
  type: Terms of Service
  url: https://www.solo.io/legal/terms-of-service/
- title: ''
  type: Privacy Policy
  url: https://www.solo.io/legal/privacy-policy/
created: '2026-03-18'
description: Gloo is a suite of open-source and enterprise API gateway and service mesh products from Solo.io built on Envoy Proxy, offering advanced traffic management, security, observability, and developer portal capabilities for Kubernetes and cloud-native environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Gloo
skills: []
slug: gloo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gloo\nname: Gloo\ndescription: >-\n  Gloo is a suite of open-source and enterprise API gateway and service mesh\n  products from Solo.io built on Envoy Proxy, offering advanced traffic\n  management, security, observability, and developer portal capabilities for\n  Kubernetes and cloud-native environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - API Gateway\n  - Envoy\n  - Kubernetes\n  - Open Source\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gloo/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: gloo:gloo-edge\n    name: Gloo Edge\n    description: >-\n      Gloo Edge is a feature-rich, Kubernetes-native ingress controller and\n      API gateway built on Envoy Proxy, supporting advanced routing,\n      security policies, and observability for cloud-native workloads.\n\
  \      It provides traffic management features such as rate limiting,\n      transformation, and WebAssembly-based extensibility.\n    humanURL: https://www.solo.io/products/gloo-gateway/\n    baseURL: https://docs.solo.io/gloo-edge/latest/\n    tags:\n      - API Gateway\n      - Envoy\n      - Kubernetes\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/gloo-edge/latest/\n      - type: Getting Started\n        url: https://docs.solo.io/gloo-edge/latest/getting_started/\n      - type: Reference\n        url: https://docs.solo.io/gloo-edge/latest/reference/\n      - type: Change Log\n        url: https://docs.solo.io/gloo-edge/latest/changelog/\n      - type: GitHubRepository\n        url: https://github.com/solo-io/gloo\n  - aid: gloo:gloo-gateway\n    name: Gloo Gateway\n    description: >-\n      Gloo Gateway is the next-generation API gateway from Solo.io built on\n      Envoy Proxy and implementing the Kubernetes Gateway API specification.\n\
  \      It provides advanced traffic management, security, and extensibility for\n      modern cloud-native applications with first-class support for AI and LLM\n      traffic routing.\n    humanURL: https://www.solo.io/products/gloo-gateway/\n    baseURL: https://docs.solo.io/gateway/latest/\n    tags:\n      - API Gateway\n      - Cloud Native\n      - Envoy\n      - Kubernetes Gateway API\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/gateway/latest/\n      - type: Getting Started\n        url: https://docs.solo.io/gateway/latest/quickstart/\n      - type: Reference\n        url: https://docs.solo.io/gateway/latest/reference/\n      - type: Change Log\n        url: https://docs.solo.io/gateway/latest/changelog/\n      - type: GitHubRepository\n        url: https://github.com/solo-io/gloo\n  - aid: gloo:gloo-mesh\n    name: Gloo Mesh\n    description: >-\n      Gloo Mesh is an enterprise service mesh management platform from Solo.io\n      built on Istio,\
  \ providing multi-cluster and multi-mesh traffic management,\n      security policy enforcement, and observability across hybrid cloud\n      environments. It simplifies service mesh operations with a unified control\n      plane and policy management interface.\n    humanURL: https://www.solo.io/products/gloo-mesh/\n    baseURL: https://docs.solo.io/gloo-mesh-enterprise/latest/\n    tags:\n      - Istio\n      - Kubernetes\n      - Multi-Cluster\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/gloo-mesh-enterprise/latest/\n      - type: Getting Started\n        url: https://docs.solo.io/gloo-mesh-enterprise/latest/getting_started/\n      - type: Reference\n        url: https://docs.solo.io/gloo-mesh-enterprise/latest/reference/\n      - type: Change Log\n        url: https://docs.solo.io/gloo-mesh-enterprise/latest/changelog/\n  - aid: gloo:gloo-portal\n    name: Gloo Portal\n    description: >-\n      Gloo Portal is a developer portal\
  \ product from Solo.io that enables\n      organizations to expose, document, and manage API products for internal\n      and external consumers. It integrates with Gloo Gateway to provide\n      self-service API discovery, subscription management, and usage analytics\n      for API consumers.\n    humanURL: https://www.solo.io/products/gloo-portal/\n    baseURL: https://docs.solo.io/portal/latest/\n    tags:\n      - API Discovery\n      - API Management\n      - Developer Portal\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/portal/latest/\n      - type: Getting Started\n        url: https://docs.solo.io/portal/latest/getting_started/\n      - type: Reference\n        url: https://docs.solo.io/portal/latest/reference/\ncommon:\n  - type: Website\n    url: https://www.solo.io/\n  - type: Portal\n    url: https://www.solo.io/products/\n  - type: Documentation\n    url: https://docs.solo.io/\n  - type: Getting Started\n    url: https://docs.solo.io/gloo-edge/latest/getting_started/\n\
  \  - type: Blog\n    url: https://www.solo.io/blog/\n  - type: GitHub Organization\n    url: https://github.com/solo-io\n  - type: GitHubRepository\n    url: https://github.com/solo-io/gloo\n  - type: Change Log\n    url: https://github.com/solo-io/gloo/releases\n  - type: Community\n    url: https://slack.solo.io/\n  - type: Support\n    url: https://www.solo.io/company/contact/\n  - type: Terms of Service\n    url: https://www.solo.io/legal/terms-of-service/\n  - type: Privacy Policy\n    url: https://www.solo.io/legal/privacy-policy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gloo/refs/heads/main/apis.yml
tags:
- API Gateway
- Envoy
- Kubernetes
- Open Source
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/gloo/refs/heads/main/apis.yml
use_cases: []
---
