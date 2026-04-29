---
api_count: 5
api_specs:
- filename: contour-httpproxy-openapi.yml
  format: yaml
  label: Contour HTTPProxy API
  slug: contour-httpproxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/openapi/contour-httpproxy-openapi.yml
- filename: contour-gateway-openapi.yml
  format: yaml
  label: Contour Gateway API
  slug: contour-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/openapi/contour-gateway-openapi.yml
apis:
- description: Kubernetes Custom Resource Definition that extends the standard Ingress API with advanced routing, multi-team support, TLS delegation, and weighted load balancing across multiple backend services. HTT
  name: Contour HTTPProxy API
  slug: contour-httpproxy-api
- description: Contour's implementation of the Kubernetes Gateway API, supporting HTTPRoute and TLSRoute resources for defining ingress traffic routing rules. Gateway API is the next-generation Kubernetes ingress st
  name: Contour Gateway API
  slug: contour-gateway-api
- description: 'Contour''s support for the standard Kubernetes Ingress v1 resource, enabling basic ingress use cases such as host-based and path-based routing to backend services. Contour watches Ingress v1 resources '
  name: Contour Kubernetes Ingress API
  slug: contour-kubernetes-ingress-api
- description: Kubernetes Custom Resource Definition for binding gRPC-based extension services to the Contour API. ExtensionService resources allow external components to implement Contour API features such as exter
  name: Contour ExtensionService API
  slug: contour-extensionservice-api
- description: Contour's ContourConfiguration Custom Resource Definition (v1alpha1) that provides cluster-scoped configuration of a Contour instance, including ingress settings, TLS defaults, timeouts, and feature g
  name: Contour Configuration API
  slug: contour-configuration-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://projectcontour.io/
- title: ''
  type: JSON-LD
  url: json-ld/contour-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/contour-httpproxy-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/contour-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/contour-httpproxy-rules.yml
- title: ''
  type: SpectralRules
  url: rules/contour-gateway-rules.yml
- title: ''
  type: Capability
  url: capabilities/manage-httpproxy-routing.yml
- title: ''
  type: Capability
  url: capabilities/configure-gateway-api-routing.yml
- title: ''
  type: Getting Started
  url: https://projectcontour.io/getting-started/
- title: ''
  type: Documentation
  url: https://projectcontour.io/docs/main/
- title: ''
  type: GitHub Organization
  url: https://github.com/projectcontour
- title: ''
  type: GitHubRepository
  url: https://github.com/projectcontour/contour
- title: ''
  type: Support
  url: https://projectcontour.io/resources/support/
- title: ''
  type: Community
  url: https://projectcontour.io/community/
- title: ''
  type: Resources
  url: https://projectcontour.io/resources/
- title: ''
  type: Change Log
  url: https://github.com/projectcontour/contour/releases
- title: ''
  type: Issue Tracker
  url: https://github.com/projectcontour/contour/issues
- title: ''
  type: Upgrading
  url: https://projectcontour.io/resources/upgrading/
created: '2025-01-01'
description: A Kubernetes ingress controller using Envoy proxy that provides dynamic configuration updates and advanced routing capabilities for managing external access to services in a cluster.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Contour Context
  property_count: 12
  slug: contour-context
layout: provider
modified: '2026-04-28'
name: Contour
rules:
- name: Contour API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 1
  slug: contour-gateway-rules
- name: Contour API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: contour-httpproxy-rules
skills: []
slug: contour
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Contour\ndescription: A Kubernetes ingress controller using Envoy proxy that provides dynamic configuration updates and advanced routing capabilities for managing external access to services in a cluster.\nurl: https://projectcontour.io/\ntags:\n  - Envoy\n  - Ingress Controller\n  - Kubernetes\n  - Networking\n  - Proxy\ncreated: '2025-01-01'\nmodified: '2026-04-28'\napis:\n  - aid: contour:contour-httpproxy-api\n    name: Contour HTTPProxy API\n    description: >-\n      Kubernetes Custom Resource Definition that extends the standard Ingress API\n      with advanced routing, multi-team support, TLS delegation, and weighted load\n      balancing across multiple backend services. HTTPProxy is Contour's primary\n      ingress configuration resource and supports inclusion of routing configuration\n      across namespaces.\n    humanURL: https://projectcontour.io/docs/main/config/api/\n    baseURL: https://projectcontour.io\n    tags:\n      - Custom Resource\n      - HTTPProxy\n\
  \      - Ingress\n      - Kubernetes\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://projectcontour.io/docs/main/config/api/\n      - type: Reference\n        url: https://projectcontour.io/docs/main/config/api-reference.html\n      - type: OpenAPI\n        url: openapi/contour-httpproxy-openapi.yml\n      - type: JSONSchema\n        url: json-schema/contour-httpproxy-schema.json\n  - aid: contour:contour-gateway-api\n    name: Contour Gateway API\n    description: >-\n      Contour's implementation of the Kubernetes Gateway API, supporting HTTPRoute\n      and TLSRoute resources for defining ingress traffic routing rules. Gateway API\n      is the next-generation Kubernetes ingress standard and Contour provides support\n      for GatewayClass, Gateway, HTTPRoute, and related resources.\n    humanURL: https://projectcontour.io/docs/1.30/config/gateway-api/\n    baseURL: https://projectcontour.io\n    tags:\n      - Gateway API\n      - Ingress\n   \
  \   - Kubernetes\n      - Networking\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://projectcontour.io/docs/1.30/config/gateway-api/\n      - type: Reference\n        url: https://projectcontour.io/docs/main/config/api-reference.html\n      - type: OpenAPI\n        url: openapi/contour-gateway-openapi.yml\n  - aid: contour:contour-kubernetes-ingress-api\n    name: Contour Kubernetes Ingress API\n    description: >-\n      Contour's support for the standard Kubernetes Ingress v1 resource, enabling\n      basic ingress use cases such as host-based and path-based routing to backend\n      services. Contour watches Ingress v1 resources and translates them into Envoy\n      proxy configuration, with support for IngressClass selection and Contour-specific\n      annotations for extended configuration.\n    humanURL: https://projectcontour.io/docs/main/config/ingress/\n    baseURL: https://projectcontour.io\n    tags:\n      - Ingress\n      - Kubernetes\n\
  \      - Networking\n      - Routing\n      - Standard API\n    properties:\n      - type: Documentation\n        url: https://projectcontour.io/docs/main/config/ingress/\n      - type: Reference\n        url: https://projectcontour.io/docs/main/config/annotations/\n  - aid: contour:contour-extensionservice-api\n    name: Contour ExtensionService API\n    description: >-\n      Kubernetes Custom Resource Definition for binding gRPC-based extension services\n      to the Contour API. ExtensionService resources allow external components to\n      implement Contour API features such as external authorization and rate limiting\n      by registering a network service that Contour will route to via Envoy's gRPC\n      extension protocol (v3).\n    humanURL: https://projectcontour.io/docs/main/config/api/\n    baseURL: https://projectcontour.io\n    tags:\n      - Authorization\n      - Custom Resource\n      - Extension Service\n      - gRPC\n      - Kubernetes\n    properties:\n      - type:\
  \ Documentation\n        url: https://projectcontour.io/docs/main/config/api/\n      - type: Reference\n        url: https://projectcontour.io/docs/main/config/api-reference.html\n  - aid: contour:contour-configuration-api\n    name: Contour Configuration API\n    description: >-\n      Contour's ContourConfiguration Custom Resource Definition (v1alpha1) that\n      provides cluster-scoped configuration of a Contour instance, including ingress\n      settings, TLS defaults, timeouts, and feature gates. This API allows operators\n      to declaratively manage Contour's runtime behavior through Kubernetes resources\n      instead of command-line flags or static config files.\n    humanURL: https://projectcontour.io/docs/main/config/api/\n    baseURL: https://projectcontour.io\n    tags:\n      - Configuration\n      - Custom Resource\n      - Kubernetes\n      - Networking\n      - Operator\n    properties:\n      - type: Documentation\n        url: https://projectcontour.io/docs/main/config/api/\n\
  \      - type: Reference\n        url: https://projectcontour.io/docs/main/config/api-reference.html\ncommon:\n  - type: Website\n    url: https://projectcontour.io/\n  - type: JSON-LD\n    url: json-ld/contour-context.jsonld\n  - type: JSONSchema\n    url: json-schema/contour-httpproxy-schema.json\n  - type: Vocabulary\n    url: vocabulary/contour-vocabulary.yml\n  - type: SpectralRules\n    url: rules/contour-httpproxy-rules.yml\n  - type: SpectralRules\n    url: rules/contour-gateway-rules.yml\n  - type: Capability\n    url: capabilities/manage-httpproxy-routing.yml\n  - type: Capability\n    url: capabilities/configure-gateway-api-routing.yml\n  - type: Getting Started\n    url: https://projectcontour.io/getting-started/\n  - type: Documentation\n    url: https://projectcontour.io/docs/main/\n  - type: GitHub Organization\n    url: https://github.com/projectcontour\n  - type: GitHubRepository\n    url: https://github.com/projectcontour/contour\n  - type: Support\n    url: https://projectcontour.io/resources/support/\n\
  \  - type: Community\n    url: https://projectcontour.io/community/\n  - type: Resources\n    url: https://projectcontour.io/resources/\n  - type: Change Log\n    url: https://github.com/projectcontour/contour/releases\n  - type: Issue Tracker\n    url: https://github.com/projectcontour/contour/issues\n  - type: Upgrading\n    url: https://projectcontour.io/resources/upgrading/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/apis.yml
tags:
- Envoy
- Ingress Controller
- Kubernetes
- Networking
- Proxy
url: https://projectcontour.io/
use_cases: []
---
