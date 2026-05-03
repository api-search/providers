---
api_count: 4
api_specs:
- filename: traefik-api-openapi.yml
  format: yaml
  label: Traefik REST API
  slug: traefik-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/openapi/traefik-api-openapi.yml
apis:
- description: Traefik is a leading modern reverse proxy and load balancer that makes deploying microservices easy with native support for Kubernetes, Docker, and automatic TLS certificate provisioning.
  name: Traefik Proxy
  slug: traefik
- description: The Traefik REST API exposes runtime configuration and state for all routers, services, middlewares, and entry points in a running Traefik instance. It provides read-only HTTP endpoints for inspecting
  name: Traefik REST API
  slug: traefik-api
- description: The Traefik Ping API provides a simple health check endpoint at `/ping` that returns HTTP 200 with the body "OK" when the Traefik process is alive and ready. It is used for liveness probes in containe
  name: Traefik Ping API
  slug: traefik-ping
- description: The Traefik Dashboard is a built-in web UI that provides a real-time visual overview of all configured routers, services, middlewares, and entry points. It is served from the same API handler as the R
  name: Traefik Dashboard
  slug: traefik-dashboard
common:
- title: ''
  type: Website
  url: https://traefik.io/
- title: ''
  type: Documentation
  url: https://doc.traefik.io/traefik/
- title: ''
  type: Getting Started
  url: https://doc.traefik.io/traefik/getting-started/quick-start/
- title: ''
  type: Blog
  url: https://traefik.io/blog/
- title: ''
  type: Change Log
  url: https://github.com/traefik/traefik/blob/master/CHANGELOG.md
- title: ''
  type: GitHub Organization
  url: https://github.com/traefik
- title: ''
  type: GitHubRepository
  url: https://github.com/traefik/traefik
- title: ''
  type: Issue Tracker
  url: https://github.com/traefik/traefik/issues
- title: ''
  type: JSON-LD
  url: json-ld/traefik-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/traefik-router-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/traefik-service-schema.json
- title: ''
  type: Community
  url: https://community.traefik.io/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/traefik
created: '2026-03-18'
description: Traefik is a modern open-source HTTP reverse proxy and load balancer that makes deploying microservices and API gateways easy with automatic service discovery, Let's Encrypt integration, and a rich middleware ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Traefik Context
  property_count: 9
  slug: traefik-context
layout: provider
modified: '2026-03-26'
name: Traefik
skills: []
slug: traefik
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: traefik\nname: Traefik\ndescription: >-\n  Traefik is a modern open-source HTTP reverse proxy and load balancer that\n  makes deploying microservices and API gateways easy with automatic service\n  discovery, Let's Encrypt integration, and a rich middleware ecosystem.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Kubernetes\n  - Load Balancer\n  - Open Source\n  - Reverse Proxy\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-03-26'\nspecificationVersion: '0.19'\napis:\n  - aid: traefik:traefik\n    name: Traefik Proxy\n    description: >-\n      Traefik is a leading modern reverse proxy and load balancer that makes\n      deploying microservices easy with native support for Kubernetes, Docker,\n      and automatic TLS certificate provisioning.\n    humanURL: https://traefik.io/traefik/\n    tags:\n      - API\
  \ Gateway\n      - Kubernetes\n      - Reverse Proxy\n    properties:\n      - type: Documentation\n        url: https://doc.traefik.io/traefik/\n      - type: Getting Started\n        url: https://doc.traefik.io/traefik/getting-started/quick-start/\n      - type: Reference\n        url: https://doc.traefik.io/traefik/reference/static-configuration/cli/\n      - type: Change Log\n        url: https://github.com/traefik/traefik/blob/master/CHANGELOG.md\n      - type: GitHubRepository\n        url: https://github.com/traefik/traefik\n  - aid: traefik:traefik-api\n    name: Traefik REST API\n    description: >-\n      The Traefik REST API exposes runtime configuration and state for all\n      routers, services, middlewares, and entry points in a running Traefik\n      instance. It provides read-only HTTP endpoints for inspecting HTTP, TCP,\n      and UDP routing configuration, as well as version and overview statistics.\n      The API must be enabled in static configuration and should be\
  \ secured\n      before use in production.\n    humanURL: https://doc.traefik.io/traefik/operations/api/\n    tags:\n      - Configuration\n      - Management\n      - Observability\n      - REST\n    properties:\n      - type: Documentation\n        url: https://doc.traefik.io/traefik/operations/api/\n      - type: Reference\n        url: https://doc.traefik.io/traefik/operations/api/#endpoints\n      - type: OpenAPI\n        url: openapi/traefik-api-openapi.yml\n  - aid: traefik:traefik-ping\n    name: Traefik Ping API\n    description: >-\n      The Traefik Ping API provides a simple health check endpoint at `/ping`\n      that returns HTTP 200 with the body \"OK\" when the Traefik process is\n      alive and ready. It is used for liveness probes in container orchestration\n      environments and can be configured on a dedicated entry point.\n    humanURL: https://doc.traefik.io/traefik/operations/ping/\n    tags:\n      - Health Check\n      - Liveness\n      - Monitoring\n      -\
  \ Operations\n    properties:\n      - type: Documentation\n        url: https://doc.traefik.io/traefik/operations/ping/\n  - aid: traefik:traefik-dashboard\n    name: Traefik Dashboard\n    description: >-\n      The Traefik Dashboard is a built-in web UI that provides a real-time\n      visual overview of all configured routers, services, middlewares, and\n      entry points. It is served from the same API handler as the REST API\n      and can be accessed via the Traefik entry point or a custom route.\n    humanURL: https://doc.traefik.io/traefik/operations/dashboard/\n    tags:\n      - Dashboard\n      - Management\n      - Observability\n      - UI\n    properties:\n      - type: Documentation\n        url: https://doc.traefik.io/traefik/operations/dashboard/\ncommon:\n  - type: Website\n    url: https://traefik.io/\n  - type: Documentation\n    url: https://doc.traefik.io/traefik/\n  - type: Getting Started\n    url: https://doc.traefik.io/traefik/getting-started/quick-start/\n\
  \  - type: Blog\n    url: https://traefik.io/blog/\n  - type: Change Log\n    url: https://github.com/traefik/traefik/blob/master/CHANGELOG.md\n  - type: GitHub Organization\n    url: https://github.com/traefik\n  - type: GitHubRepository\n    url: https://github.com/traefik/traefik\n  - type: Issue Tracker\n    url: https://github.com/traefik/traefik/issues\n  - type: JSON-LD\n    url: json-ld/traefik-context.jsonld\n  - type: JSONSchema\n    url: json-schema/traefik-router-schema.json\n  - type: JSONSchema\n    url: json-schema/traefik-service-schema.json\n  - type: Community\n    url: https://community.traefik.io/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/traefik\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/apis.yml
tags:
- API Gateway
- Kubernetes
- Load Balancer
- Open Source
- Reverse Proxy
url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/apis.yml
use_cases: []
---
