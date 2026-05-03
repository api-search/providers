---
api_count: 1
api_specs:
- filename: restate-admin-api.yml
  format: yaml
  label: Restate Admin API
  slug: restate-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/openapi/restate-admin-api.yml
apis:
- description: The Restate Admin API provides endpoints for managing service deployments, inspecting service metadata, managing in-flight invocations, and monitoring the health of the Restate server. It enables oper
  name: Restate Admin API
  slug: restate-admin
capabilities:
- description: Unified capability for managing the full lifecycle of Restate services and deployments. Covers registering service deployments, inspecting service metadata and handlers, managing in-flight invocations
  name: Restate Service Operations
  slug: service-operations
common:
- title: ''
  type: Website
  url: https://restate.dev/
- title: ''
  type: Documentation
  url: https://docs.restate.dev/
- title: ''
  type: GitHub Organization
  url: https://github.com/restatedev
- title: ''
  type: TypeScript SDK
  url: https://github.com/restatedev/sdk-typescript
- title: ''
  type: Python SDK
  url: https://github.com/restatedev/sdk-python
- title: ''
  type: Java SDK
  url: https://github.com/restatedev/sdk-java
- title: ''
  type: Go SDK
  url: https://github.com/restatedev/sdk-go
- title: ''
  type: Rust SDK
  url: https://github.com/restatedev/sdk-rust
- title: ''
  type: Examples
  url: https://github.com/restatedev/examples
- title: ''
  type: Web UI
  url: https://github.com/restatedev/restate-web-ui
- title: ''
  type: Discord
  url: https://discord.gg/skW3AZ6uGd
- title: ''
  type: Blog
  url: https://restate.dev/blog/
created: '2026-03-26'
description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices with exactly-once semantics, automatic retries, and built-in state management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Restate Context
  property_count: 0
  slug: restate-context
layout: provider
modified: '2026-05-02'
name: Restate
rules:
- name: Restate API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 6
  slug: restate-rules
skills: []
slug: restate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: restate\nname: Restate\ndescription: >-\n  Restate is a low-latency durable execution engine for building resilient\n  applications that tolerate all infrastructure faults. It provides durable\n  execution for workflows, event-driven handlers, and stateful orchestration of\n  microservices with exactly-once semantics, automatic retries, and built-in\n  state management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Durable Execution\n  - Workflows\n  - Microservices\n  - Orchestration\n  - Distributed Systems\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: restate:restate-admin\n    name: Restate Admin API\n    description: >-\n      The Restate Admin API provides endpoints for managing service deployments,\n      inspecting service metadata, managing in-flight invocations,\
  \ and\n      monitoring the health of the Restate server. It enables operators to\n      register service deployments, purge completed invocations, and configure\n      services programmatically.\n    humanURL: https://restate.dev/\n    baseURL: http://localhost:9070\n    tags:\n      - Deployments\n      - Services\n      - Invocations\n      - Administration\n    properties:\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/openapi/restate-admin-api.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/json-schema/restate-deployment-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/json-schema/restate-invocation-schema.json\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/vocabulary/restate-vocabulary.yml\n      - type: Documentation\n\
  \        url: https://docs.restate.dev/\n      - type: GitHub Repository\n        url: https://github.com/restatedev/restate\n      - type: KubernetesCRD\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/crd/restateclusters.yaml\n      - type: KubernetesCRD\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/crd/restatedeployments.yaml\n      - type: KubernetesCRD\n        url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/crd/restatecloudenvironments.yaml\ncommon:\n  - type: Website\n    url: https://restate.dev/\n  - type: Documentation\n    url: https://docs.restate.dev/\n  - type: GitHub Organization\n    url: https://github.com/restatedev\n  - type: TypeScript SDK\n    url: https://github.com/restatedev/sdk-typescript\n  - type: Python SDK\n    url: https://github.com/restatedev/sdk-python\n  - type: Java SDK\n    url: https://github.com/restatedev/sdk-java\n  - type: Go SDK\n    url:\
  \ https://github.com/restatedev/sdk-go\n  - type: Rust SDK\n    url: https://github.com/restatedev/sdk-rust\n  - type: Examples\n    url: https://github.com/restatedev/examples\n  - type: Web UI\n    url: https://github.com/restatedev/restate-web-ui\n  - type: Discord\n    url: https://discord.gg/skW3AZ6uGd\n  - type: Blog\n    url: https://restate.dev/blog/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/apis.yml
tags:
- Durable Execution
- Workflows
- Microservices
- Orchestration
- Distributed Systems
url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/apis.yml
use_cases: []
---
