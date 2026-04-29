---
api_count: 3
api_specs:
- filename: consul-connect-openapi.yml
  format: yaml
  label: Consul Connect HTTP API
  slug: consul-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/openapi/consul-connect-openapi.yml
apis:
- description: The HTTP API exposed by Consul agents under /v1/connect for managing intentions, the Connect certificate authority, and related mesh operations. Connect-related endpoints also exist in the Agent and C
  name: Consul Connect HTTP API
  slug: consul-connect-api
- description: Consul Connect configuration entries (service-defaults, service-resolver, service-router, service-splitter, service-intentions, mesh, proxy-defaults) that declaratively configure mesh behavior. Config
  name: Consul Connect Configuration Entries
  slug: consul-connect-config-entries
- description: 'Consul Connect supports four gateway types for traffic flowing into and out of the mesh: mesh gateways for cross-datacenter and cross-partition traffic, ingress gateways for North-South entry, termina'
  name: Consul Connect Gateways
  slug: consul-connect-gateways
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.consul.io/
- title: ''
  type: JSON-LD
  url: json-ld/consul-connect-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/consul-connect-intention-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/consul-connect-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/consul-connect-rules.yml
- title: ''
  type: Capability
  url: capabilities/manage-service-intentions.yml
- title: ''
  type: Capability
  url: capabilities/rotate-mesh-ca.yml
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/consul/docs/connect
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/consul/api-docs/connect
- title: ''
  type: GitHubRepository
  url: https://github.com/hashicorp/consul
- title: ''
  type: GitHub Organization
  url: https://github.com/hashicorp
- title: ''
  type: Issue Tracker
  url: https://github.com/hashicorp/consul/issues
- title: ''
  type: Change Log
  url: https://github.com/hashicorp/consul/releases
- title: ''
  type: License
  url: https://github.com/hashicorp/consul/blob/main/LICENSE
created: '2025-01-01'
description: Consul Connect is the service mesh subsystem of HashiCorp Consul. Connect provides service identity, mTLS, traffic authorization via intentions, and L7 traffic management through Envoy sidecar proxies. Consul Connect ships with a built-in certificate authority that can also be backed by Vault or external PKI, supports mesh, terminating, ingress, and API gateways, and spans virtual machines, Kubernetes, AWS ECS, AWS Lambda, and Nomad runtimes. Operators interact with Connect through the consul CLI, the HTTP API, configuration entries, and Kubernetes Custom Resource Definitions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Consul Connect Context
  property_count: 4
  slug: consul-connect-context
layout: provider
modified: '2026-04-28'
name: Consul Connect
rules:
- name: Consul Connect API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: consul-connect-rules
skills: []
slug: consul-connect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consul-connect\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/apis.yml\nname: Consul Connect\nx-type: opensource\ndescription: >-\n  Consul Connect is the service mesh subsystem of HashiCorp Consul. Connect\n  provides service identity, mTLS, traffic authorization via intentions, and\n  L7 traffic management through Envoy sidecar proxies. Consul Connect ships\n  with a built-in certificate authority that can also be backed by Vault or\n  external PKI, supports mesh, terminating, ingress, and API gateways, and\n  spans virtual machines, Kubernetes, AWS ECS, AWS Lambda, and Nomad\n  runtimes. Operators interact with Connect through the consul CLI, the\n  HTTP API, configuration entries, and Kubernetes Custom Resource\n  Definitions.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Consul\n  - Envoy\n  - HashiCorp\n  - Intentions\n  - Kubernetes\n  - mTLS\n  - Service Mesh\n  - Sidecar\n\
  \  - Zero Trust\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: consul-connect:consul-connect-api\n    name: Consul Connect HTTP API\n    description: >-\n      The HTTP API exposed by Consul agents under /v1/connect for managing\n      intentions, the Connect certificate authority, and related mesh\n      operations. Connect-related endpoints also exist in the Agent and\n      Catalog APIs for sidecar proxy registration and CA leaf signing.\n    humanURL: https://developer.hashicorp.com/consul/api-docs/connect\n    baseURL: http://localhost:8500/v1\n    tags:\n      - HTTP API\n      - Intentions\n      - mTLS\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/api-docs/connect\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/api-docs/connect/intentions\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/api-docs/connect/ca\n\
  \      - type: OpenAPI\n        url: openapi/consul-connect-openapi.yml\n      - type: JSONSchema\n        url: json-schema/consul-connect-intention-schema.json\n    x-features:\n      - Manage intentions by source/destination or UUID (legacy)\n      - Authorize connections via /connect/intentions/check\n      - Match intentions for a given service via /connect/intentions/match\n      - List and configure the Connect certificate authority\n      - Pluggable CA providers (Consul, Vault, AWS PCA, external)\n      - ACL token enforcement via X-Consul-Token header\n    x-useCases:\n      - GitOps-managed authorization across heterogeneous services\n      - Automating CA rotation and provider migrations\n      - Building admin dashboards over service mesh policy\n      - Integrating Consul Connect with CI/CD release gates\n  - aid: consul-connect:consul-connect-config-entries\n    name: Consul Connect Configuration Entries\n    description: >-\n      Consul Connect configuration entries (service-defaults,\n\
  \      service-resolver, service-router, service-splitter, service-intentions,\n      mesh, proxy-defaults) that declaratively configure mesh behavior.\n      Configuration entries are managed via the /v1/config API and via\n      Kubernetes Custom Resource Definitions when running on Kubernetes.\n    humanURL: https://developer.hashicorp.com/consul/docs/connect/config-entries\n    baseURL: https://developer.hashicorp.com\n    tags:\n      - Configuration Entries\n      - CRD\n      - Kubernetes\n      - L7 Routing\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/docs/connect/config-entries\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/config-entries/service-defaults\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/config-entries/service-router\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/config-entries/service-splitter\n\
  \    x-features:\n      - service-defaults to set protocol and timeouts\n      - service-router for L7 path/header/method routing\n      - service-splitter for canary and blue/green rollouts\n      - service-resolver for failover and subsets\n      - mesh-wide configuration via the mesh entry\n      - Kubernetes CRDs for declarative mesh management\n    x-useCases:\n      - Implementing canary deployments via service-splitter\n      - Routing traffic by header for tenant isolation\n      - Centralizing TLS and protocol defaults\n  - aid: consul-connect:consul-connect-gateways\n    name: Consul Connect Gateways\n    description: >-\n      Consul Connect supports four gateway types for traffic flowing into\n      and out of the mesh: mesh gateways for cross-datacenter and\n      cross-partition traffic, ingress gateways for North-South entry,\n      terminating gateways for access to non-mesh services, and the\n      Consul API Gateway implementing the Kubernetes Gateway API.\n    humanURL:\
  \ https://developer.hashicorp.com/consul/docs/connect/gateways\n    baseURL: https://developer.hashicorp.com\n    tags:\n      - API Gateway\n      - Gateways\n      - Ingress\n      - Mesh Gateway\n      - Terminating Gateway\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/docs/connect/gateways\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/gateways/mesh-gateway\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/gateways/ingress-gateway\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/connect/gateways/terminating-gateway\n      - type: Reference\n        url: https://developer.hashicorp.com/consul/docs/api-gateway\n    x-features:\n      - Mesh gateways for WAN federation and partition crossing\n      - Ingress gateways for L4/L7 ingress with TLS\n      - Terminating gateways for non-mesh service access\n      - API Gateway\
  \ implementing the Kubernetes Gateway API\n    x-useCases:\n      - Federate Consul across datacenters securely\n      - Expose mesh services to external clients with TLS\n      - Allow mesh services to call legacy non-mesh endpoints\ncommon:\n  - type: Website\n    url: https://www.consul.io/\n  - type: JSON-LD\n    url: json-ld/consul-connect-context.jsonld\n  - type: JSONSchema\n    url: json-schema/consul-connect-intention-schema.json\n  - type: Vocabulary\n    url: vocabulary/consul-connect-vocabulary.yml\n  - type: SpectralRules\n    url: rules/consul-connect-rules.yml\n  - type: Capability\n    url: capabilities/manage-service-intentions.yml\n  - type: Capability\n    url: capabilities/rotate-mesh-ca.yml\n  - type: Documentation\n    url: https://developer.hashicorp.com/consul/docs/connect\n  - type: Documentation\n    url: https://developer.hashicorp.com/consul/api-docs/connect\n  - type: GitHubRepository\n    url: https://github.com/hashicorp/consul\n  - type: GitHub Organization\n\
  \    url: https://github.com/hashicorp\n  - type: Issue Tracker\n    url: https://github.com/hashicorp/consul/issues\n  - type: Change Log\n    url: https://github.com/hashicorp/consul/releases\n  - type: License\n    url: https://github.com/hashicorp/consul/blob/main/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/apis.yml
tags:
- Consul
- Envoy
- HashiCorp
- Intentions
- Kubernetes
- mTLS
- Service Mesh
- Sidecar
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/consul-connect/refs/heads/main/apis.yml
use_cases: []
---
