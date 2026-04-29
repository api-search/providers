---
api_count: 1
api_specs:
- filename: consul-http-api.yml
  format: yaml
  label: Consul HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/openapi/consul-http-api.yml
apis:
- description: The main HTTP API for interacting with Consul agents and servers. Endpoints are grouped under /agent (local agent state and registration), /catalog (cluster-wide service and node catalog), /health (he
  name: Consul HTTP API
  slug: http-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.consul.io
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/consul
- title: ''
  type: Getting Started
  url: https://developer.hashicorp.com/consul/tutorials/get-started-vms
- title: ''
  type: Tutorials
  url: https://developer.hashicorp.com/consul/tutorials
- title: ''
  type: GitHub Organization
  url: https://github.com/hashicorp
- title: ''
  type: GitHub Repository
  url: https://github.com/hashicorp/consul
- title: ''
  type: Change Log
  url: https://github.com/hashicorp/consul/releases
- title: ''
  type: Blog
  url: https://www.hashicorp.com/blog/products/consul
- title: ''
  type: Community
  url: https://discuss.hashicorp.com/c/consul
- title: ''
  type: Twitter
  url: https://twitter.com/HashiCorp
- title: ''
  type: Terms of Service
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: JSON-LD
  url: json-ld/consul-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/consul-service-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/consul-kv-schema.json
- title: ''
  type: Spectral
  url: rules/consul-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/consul-capabilities.yml
created: '2024-01-01'
description: HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by every Consul agent and server at /v1, gated by the X-Consul-Token header (apiKey) and ACL policies, supporting blocking queries via X-Consul-Index for streaming-style change detection.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Consul Context
  property_count: 6
  slug: consul-context
layout: provider
modified: '2026-04-29'
name: HashiCorp Consul
rules:
- name: HashiCorp Consul API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 3
  slug: consul-rules
skills: []
slug: consul
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consul\nname: HashiCorp Consul\nurl: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml\ndescription: >-\n  HashiCorp Consul is a distributed, highly available service-networking\n  control plane that automates network configuration, discovers services,\n  enables secure service-to-service communication, and exposes a strongly\n  consistent key/value store. The Consul HTTP API is a REST + JSON service\n  exposed by every Consul agent and server at /v1, gated by the\n  X-Consul-Token header (apiKey) and ACL policies, supporting blocking\n  queries via X-Consul-Index for streaming-style change detection.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ntags:\n  - ACL\n  - Configuration\n  - Health Checking\n  - Key/Value Store\n  - Multi-Datacenter\n  - Open Source\n  - Service Discovery\n  - Service Mesh\ncreated: '2024-01-01'\nmodified: '2026-04-29'\nposition: Provider\nspecificationVersion:\
  \ '0.19'\nx-type: opensource\napis:\n  - aid: consul:http-api\n    name: Consul HTTP API\n    description: >-\n      The main HTTP API for interacting with Consul agents and servers.\n      Endpoints are grouped under /agent (local agent state and\n      registration), /catalog (cluster-wide service and node catalog),\n      /health (health-checked service queries), /kv (key/value store),\n      /acl (token, policy, and role management), /connect (service\n      mesh CA, intentions), /config (central configuration entries),\n      /event (user events), /session (locks and leadership), and\n      /operator (Raft, autopilot, license).\n    image: https://www.consul.io/img/logo-hashicorp.svg\n    humanURL: https://developer.hashicorp.com/consul/api-docs\n    baseURL: http://localhost:8500/v1\n    tags:\n      - ACL\n      - Catalog\n      - Connect\n      - Health\n      - Key/Value\n      - Service Discovery\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url:\
  \ https://developer.hashicorp.com/consul/api-docs\n      - type: OpenAPI\n        url: openapi/consul-http-api.yml\n      - type: Authentication\n        url: https://developer.hashicorp.com/consul/api-docs/api-structure\n      - type: ACL Documentation\n        url: https://developer.hashicorp.com/consul/docs/security/acl\n      - type: GitHub Repository\n        url: https://github.com/hashicorp/consul\ncommon:\n  - type: Website\n    url: https://www.consul.io\n  - type: Documentation\n    url: https://developer.hashicorp.com/consul\n  - type: Getting Started\n    url: https://developer.hashicorp.com/consul/tutorials/get-started-vms\n  - type: Tutorials\n    url: https://developer.hashicorp.com/consul/tutorials\n  - type: GitHub Organization\n    url: https://github.com/hashicorp\n  - type: GitHub Repository\n    url: https://github.com/hashicorp/consul\n  - type: Change Log\n    url: https://github.com/hashicorp/consul/releases\n  - type: Blog\n    url: https://www.hashicorp.com/blog/products/consul\n\
  \  - type: Community\n    url: https://discuss.hashicorp.com/c/consul\n  - type: Twitter\n    url: https://twitter.com/HashiCorp\n  - type: Terms of Service\n    url: https://www.hashicorp.com/terms-of-service\n  - type: Privacy Policy\n    url: https://www.hashicorp.com/privacy\n  - type: JSON-LD\n    url: json-ld/consul-context.jsonld\n  - type: JSONSchema\n    url: json-schema/consul-service-schema.json\n  - type: JSONSchema\n    url: json-schema/consul-kv-schema.json\n  - type: Spectral\n    url: rules/consul-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/consul-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml
tags:
- ACL
- Configuration
- Health Checking
- Key/Value Store
- Multi-Datacenter
- Open Source
- Service Discovery
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml
use_cases: []
---
