---
api_count: 2
api_specs:
- filename: emissary-ingress-openapi.yml
  format: yaml
  label: Emissary-Ingress Configuration API
  slug: emissary-ingress-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/openapi/emissary-ingress-openapi.yml
apis:
- description: Emissary-Ingress is configured through Kubernetes custom resources including Mapping for routing rules, Host for domain configuration, TLSContext for TLS termination, RateLimitService for rate limitin
  name: Emissary-Ingress Configuration API
  slug: emissary-ingress-api
- description: Emissary-Ingress supports a subset of the Kubernetes Gateway API standard, including GatewayClass, Gateway, and HTTPRoute resources. This enables teams to use the next-generation Kubernetes ingress st
  name: Emissary-Ingress Gateway API
  slug: emissary-ingress-gateway-api
common:
- title: ''
  type: Website
  url: https://www.getambassador.io/products/api-gateway
- title: ''
  type: Documentation
  url: https://www.getambassador.io/docs/emissary/
- title: ''
  type: Getting Started
  url: https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install
- title: ''
  type: GitHub Organization
  url: https://github.com/emissary-ingress
- title: ''
  type: GitHubRepository
  url: https://github.com/emissary-ingress/emissary
- title: ''
  type: Support
  url: https://www.getambassador.io/docs/emissary/latest/about/support
- title: ''
  type: Community
  url: https://emissary-ingress.dev/docs/4.0/community/
- title: ''
  type: Issue Tracker
  url: https://github.com/emissary-ingress/emissary/issues
- title: ''
  type: Blog
  url: https://blog.getambassador.io/
- title: ''
  type: Change Log
  url: https://archive.getambassador.io/docs/emissary/3.1/release-notes/
- title: ''
  type: JSON-LD
  url: json-ld/emissary-ingress-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/emissary-ingress-mapping-schema.json
created: '2026-03-16'
description: Emissary-Ingress is a CNCF incubating Kubernetes-native API gateway built on the Envoy proxy. It provides ingress control, load balancing, authentication, rate limiting, and traffic management for microservices. Emissary-Ingress is configured through Kubernetes custom resources and supports canary releases, circuit breaking, and automatic retries.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Emissary Ingress Context
  property_count: 10
  slug: emissary-ingress-context
layout: provider
modified: '2026-04-28'
name: Emissary-Ingress
skills: []
slug: emissary-ingress
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: emissary-ingress\nname: Emissary-Ingress\ndescription: >-\n  Emissary-Ingress is a CNCF incubating Kubernetes-native API gateway\n  built on the Envoy proxy. It provides ingress control, load balancing,\n  authentication, rate limiting, and traffic management for microservices.\n  Emissary-Ingress is configured through Kubernetes custom resources and\n  supports canary releases, circuit breaking, and automatic retries.\nurl: https://www.getambassador.io/products/api-gateway\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Cloud Native\n  - Envoy\n  - Incubating\n  - Ingress\n  - Kubernetes\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: emissary-ingress:emissary-ingress-api\n    name: Emissary-Ingress Configuration API\n    description: >-\n      Emissary-Ingress is configured through Kubernetes custom resources\n      including Mapping for routing\
  \ rules, Host for domain configuration,\n      TLSContext for TLS termination, RateLimitService for rate limiting,\n      and AuthService for external authentication. These CRDs provide\n      declarative API gateway configuration within the Kubernetes ecosystem.\n    humanURL: https://www.getambassador.io/docs/emissary/\n    properties:\n      - type: Documentation\n        url: https://www.getambassador.io/docs/emissary/\n      - type: Getting Started\n        url: https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install\n      - type: Reference\n        url: https://www.getambassador.io/docs/emissary/latest/topics/running/\n      - type: Change Log\n        url: https://archive.getambassador.io/docs/emissary/3.1/release-notes/\n      - type: OpenAPI\n        url: openapi/emissary-ingress-openapi.yml\n      - type: JSONSchema\n        url: json-schema/emissary-ingress-mapping-schema.json\n      - type: Authentication\n        url: https://www.getambassador.io/docs/emissary/latest/topics/running/services/auth-service\n\
  \      - type: Quotas\n        url: https://www.getambassador.io/docs/emissary/latest/topics/running/services/rate-limit-service\n    tags:\n      - API Gateway\n      - Configuration\n      - Routing\n  - aid: emissary-ingress:emissary-ingress-gateway-api\n    name: Emissary-Ingress Gateway API\n    description: >-\n      Emissary-Ingress supports a subset of the Kubernetes Gateway API standard,\n      including GatewayClass, Gateway, and HTTPRoute resources. This enables\n      teams to use the next-generation Kubernetes ingress standard for defining\n      routing rules, with support for path matching, header matching, and\n      weighted load balancing across backend services.\n    humanURL: https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/\n    properties:\n      - type: Documentation\n        url: https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/\n    tags:\n      - Gateway API\n      - HTTPRoute\n      - Kubernetes\n      - Routing\ncommon:\n  - type:\
  \ Website\n    url: https://www.getambassador.io/products/api-gateway\n  - type: Documentation\n    url: https://www.getambassador.io/docs/emissary/\n  - type: Getting Started\n    url: https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install\n  - type: GitHub Organization\n    url: https://github.com/emissary-ingress\n  - type: GitHubRepository\n    url: https://github.com/emissary-ingress/emissary\n  - type: Support\n    url: https://www.getambassador.io/docs/emissary/latest/about/support\n  - type: Community\n    url: https://emissary-ingress.dev/docs/4.0/community/\n  - type: Issue Tracker\n    url: https://github.com/emissary-ingress/emissary/issues\n  - type: Blog\n    url: https://blog.getambassador.io/\n  - type: Change Log\n    url: https://archive.getambassador.io/docs/emissary/3.1/release-notes/\n  - type: JSON-LD\n    url: json-ld/emissary-ingress-context.jsonld\n  - type: JSONSchema\n    url: json-schema/emissary-ingress-mapping-schema.json\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/apis.yml
tags:
- API Gateway
- Cloud Native
- Envoy
- Incubating
- Ingress
- Kubernetes
url: https://www.getambassador.io/products/api-gateway
use_cases: []
---
