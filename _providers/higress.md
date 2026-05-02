---
api_count: 4
apis:
- description: Higress is a next-generation cloud-native API gateway that provides intelligent routing, traffic management, authentication, and observability capabilities for microservices architectures.
  name: Higress
  slug: higress
- description: The Higress Console API provides a RESTful management interface for configuring and administering a running Higress gateway instance. It supports management of ingress routes, service sources, TLS cer
  name: Higress Console API
  slug: higress-console-api
- description: Higress AI Gateway extends the core Higress gateway with AI-specific capabilities including LLM proxy routing, multi-provider support for OpenAI-compatible APIs, prompt templating, token-based rate li
  name: Higress AI Gateway
  slug: higress-ai-gateway
- description: The Higress Wasm Plugin API provides a WebAssembly-based extension interface for developing and deploying custom plugins on the Higress gateway. Plugins can be written in Go, Rust, C++, or any languag
  name: Higress Wasm Plugin API
  slug: higress-wasm-plugin-api
common:
- title: ''
  type: Website
  url: https://higress.io/en-us/
- title: ''
  type: Documentation
  url: https://higress.io/en-us/docs/
- title: ''
  type: Getting Started
  url: https://higress.io/en-us/docs/user/quickstart
- title: ''
  type: Blog
  url: https://higress.io/en-us/blog/
- title: ''
  type: Change Log
  url: https://github.com/alibaba/higress/releases
- title: ''
  type: GitHub Organization
  url: https://github.com/alibaba
- title: ''
  type: GitHubRepository
  url: https://github.com/alibaba/higress
- title: ''
  type: Issue Tracker
  url: https://github.com/alibaba/higress/issues
- title: ''
  type: Community
  url: https://discord.gg/higress
created: '2026-03-16'
description: Higress is a cloud-native API gateway built on Istio and Envoy, providing enterprise-grade API gateway capabilities including traffic management, security, observability, and AI plugin support. It is an open-source project under the CNCF ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Higress
skills: []
slug: higress
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: higress\nname: Higress\ndescription: >-\n  Higress is a cloud-native API gateway built on Istio and Envoy, providing\n  enterprise-grade API gateway capabilities including traffic management,\n  security, observability, and AI plugin support. It is an open-source\n  project under the CNCF ecosystem.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Cloud Native\n  - Istio\n  - Kubernetes\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/higress/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: higress:higress\n    name: Higress\n    description: >-\n      Higress is a next-generation cloud-native API gateway that provides\n      intelligent routing, traffic management, authentication, and observability\n      capabilities for microservices architectures.\n    humanURL: https://higress.io/en-us/\n    tags:\n      - API\
  \ Gateway\n      - Cloud Native\n    properties:\n      - type: Documentation\n        url: https://higress.io/en-us/docs/\n      - type: Getting Started\n        url: https://higress.io/en-us/docs/user/quickstart\n      - type: Reference\n        url: https://higress.io/en-us/docs/ops/config/\n      - type: Change Log\n        url: https://github.com/alibaba/higress/releases\n      - type: GitHubRepository\n        url: https://github.com/alibaba/higress\n  - aid: higress:higress-console-api\n    name: Higress Console API\n    description: >-\n      The Higress Console API provides a RESTful management interface for\n      configuring and administering a running Higress gateway instance. It\n      supports management of ingress routes, service sources, TLS certificates,\n      plugins, and gateway configuration through the built-in web console\n      backend.\n    humanURL: https://higress.io/en-us/docs/ops/api\n    tags:\n      - Admin\n      - Configuration\n      - Management\n   \
  \   - REST\n    properties:\n      - type: Documentation\n        url: https://higress.io/en-us/docs/ops/api\n      - type: GitHubRepository\n        url: https://github.com/alibaba/higress-console\n  - aid: higress:higress-ai-gateway\n    name: Higress AI Gateway\n    description: >-\n      Higress AI Gateway extends the core Higress gateway with AI-specific\n      capabilities including LLM proxy routing, multi-provider support for\n      OpenAI-compatible APIs, prompt templating, token-based rate limiting,\n      semantic caching, and AI observability. It enables teams to manage and\n      govern traffic to large language model services.\n    humanURL: https://higress.io/en-us/docs/plugins/ai/\n    tags:\n      - AI\n      - API Gateway\n      - Cloud Native\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://higress.io/en-us/docs/plugins/ai/\n      - type: Getting Started\n        url: https://higress.io/en-us/docs/user/ai-proxy/\n      - type: GitHubRepository\n\
  \        url: https://github.com/alibaba/higress\n  - aid: higress:higress-wasm-plugin-api\n    name: Higress Wasm Plugin API\n    description: >-\n      The Higress Wasm Plugin API provides a WebAssembly-based extension\n      interface for developing and deploying custom plugins on the Higress\n      gateway. Plugins can be written in Go, Rust, C++, or any language\n      that compiles to WebAssembly, and can intercept and transform HTTP\n      requests and responses at the gateway level.\n    humanURL: https://higress.io/en-us/docs/plugins/custom/\n    tags:\n      - Cloud Native\n      - Extensions\n      - Plugins\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://higress.io/en-us/docs/plugins/custom/\n      - type: Reference\n        url: https://higress.io/en-us/docs/plugins/custom/go-plugin/\n      - type: GitHubRepository\n        url: https://github.com/alibaba/higress\ncommon:\n  - type: Website\n    url: https://higress.io/en-us/\n  - type:\
  \ Documentation\n    url: https://higress.io/en-us/docs/\n  - type: Getting Started\n    url: https://higress.io/en-us/docs/user/quickstart\n  - type: Blog\n    url: https://higress.io/en-us/blog/\n  - type: Change Log\n    url: https://github.com/alibaba/higress/releases\n  - type: GitHub Organization\n    url: https://github.com/alibaba\n  - type: GitHubRepository\n    url: https://github.com/alibaba/higress\n  - type: Issue Tracker\n    url: https://github.com/alibaba/higress/issues\n  - type: Community\n    url: https://discord.gg/higress\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/higress/refs/heads/main/apis.yml
tags:
- API Gateway
- Cloud Native
- Istio
- Kubernetes
url: https://raw.githubusercontent.com/api-evangelist/higress/refs/heads/main/apis.yml
use_cases: []
---
