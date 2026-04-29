---
api_count: 5
api_specs:
- filename: cilium-api-openapi.yml
  format: yaml
  label: Cilium API
  slug: cilium-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/openapi/cilium-api-openapi.yml
- filename: cilium-hubble-asyncapi.yml
  format: yaml
  label: Hubble API
  slug: hubble-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/asyncapi/cilium-hubble-asyncapi.yml
apis:
- description: 'The Cilium REST API provides access to Cilium daemon and agent endpoints for managing Kubernetes network policy, security, and connectivity. The API is served by the cilium-agent process over a local '
  name: Cilium API
  slug: cilium-api
- description: The Hubble API is a gRPC-based observability API built on top of Cilium and eBPF that provides deep visibility into network flows, DNS queries, HTTP requests, and service communication within Kubernet
  name: Hubble API
  slug: hubble-api
- description: The Tetragon gRPC API provides access to eBPF-based security observability and runtime enforcement capabilities. It enables querying of kernel-level events including process execution, file access, an
  name: Tetragon API
  slug: tetragon-api
- description: The Cilium Operator API provides a REST interface for the Cilium operator component, which handles cluster-wide tasks such as garbage collection of Cilium endpoints and identities, node IPAM managemen
  name: Cilium Operator API
  slug: cilium-operator-api
- description: 'The Hubble Relay API is a gRPC service that aggregates and relays network flow data from multiple Hubble agents running across Kubernetes cluster nodes. It provides a single cluster-wide endpoint for '
  name: Hubble Relay API
  slug: hubble-relay-api
asyncapis:
- description: The Hubble event streaming API provides real-time observability into network flows, DNS queries, HTTP requests, and service-to-service communication within Kubernetes clusters. Hubble exposes gRPC-bas
  name: Cilium Hubble Events
  slug: cilium-hubble-asyncapi
common:
- title: ''
  type: Website
  url: https://cilium.io/
- title: ''
  type: Documentation
  url: https://docs.cilium.io/
- title: ''
  type: GettingStarted
  url: https://docs.cilium.io/en/stable/gettingstarted/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cilium
- title: ''
  type: GitHubRepository
  url: https://github.com/cilium/cilium
- title: ''
  type: Blog
  url: https://cilium.io/blog/
- title: ''
  type: Community
  url: https://cilium.io/get-involved/
- title: ''
  type: Support
  url: https://cilium.io/get-help/
- title: ''
  type: PrivacyPolicy
  url: https://cilium.io/privacy/
- title: ''
  type: Slack
  url: https://slack.cilium.io/
- title: ''
  type: ChangeLog
  url: https://github.com/cilium/cilium/releases
- title: ''
  type: YouTube
  url: https://www.youtube.com/@CiliumProject
- title: ''
  type: TermsOfService
  url: https://cilium.io/terms/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/cilium
- title: ''
  type: JSONLDContext
  url: json-ld/cilium-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cilium-endpoint-schema.json
- title: ''
  type: AsyncAPI
  url: asyncapi/cilium-hubble-asyncapi.yml
- title: ''
  type: OpenAPI
  url: openapi/cilium-api-openapi.yml
- title: ''
  type: Spectral
  url: spectral/cilium-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/cilium-capabilities.yml
created: '2026-03-16'
description: Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary kernel technology eBPF. Cilium provides network security, load balancing, and observability for Kubernetes clusters.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cilium Context
  property_count: 11
  slug: cilium-context
layout: provider
modified: '2026-04-23'
name: Cilium
skills: []
slug: cilium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cilium\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml\nname: Cilium\ntags:\n  - Cloud Native\n  - eBPF\n  - Kubernetes\n  - Networking\n  - Security\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Cilium is an open source, cloud native solution for providing, securing, and\n  observing network connectivity between workloads, fueled by the revolutionary\n  kernel technology eBPF. Cilium provides network security, load balancing,\n  and observability for Kubernetes clusters.\napis:\n  - aid: cilium:cilium-api\n    name: Cilium API\n    tags:\n      - eBPF\n      - Kubernetes\n      - Networking\n      - Security\n    humanURL: https://docs.cilium.io/en/stable/api/\n    baseURL: https://localhost/v1\n    properties:\n      - url: https://docs.cilium.io/en/stable/api/\n       \
  \ type: Documentation\n      - url: https://github.com/cilium/cilium/blob/main/api/v1/openapi.yaml\n        type: OpenAPI\n      - url: openapi/cilium-api-openapi.yml\n        type: OpenAPI\n      - url: https://docs.cilium.io/en/stable/gettingstarted/\n        type: Getting Started\n      - url: https://github.com/cilium/cilium/releases\n        type: Change Log\n    description: >-\n      The Cilium REST API provides access to Cilium daemon and agent endpoints\n      for managing Kubernetes network policy, security, and connectivity. The\n      API is served by the cilium-agent process over a local Unix domain socket\n      and HTTP interface, and covers endpoints, identities, cluster nodes, and\n      health status.\n  - aid: cilium:hubble-api\n    name: Hubble API\n    tags:\n      - eBPF\n      - Kubernetes\n      - Networking\n      - Observability\n    humanURL: https://docs.cilium.io/en/stable/observability/hubble/index.html\n    properties:\n      - url: https://docs.cilium.io/en/stable/observability/hubble/index.html\n\
  \        type: Documentation\n      - url: https://docs.cilium.io/en/stable/internals/hubble/\n        type: Reference\n      - url: asyncapi/cilium-hubble-asyncapi.yml\n        type: AsyncAPI\n      - url: https://github.com/cilium/hubble\n        type: GitHubRepository\n      - url: https://github.com/cilium/hubble/releases\n        type: Change Log\n    description: >-\n      The Hubble API is a gRPC-based observability API built on top of Cilium\n      and eBPF that provides deep visibility into network flows, DNS queries,\n      HTTP requests, and service communication within Kubernetes clusters. It\n      exposes Observer and Peer gRPC services for querying flows, nodes,\n      namespaces, and server status across single nodes or entire clusters via\n      Hubble Relay.\n  - aid: cilium:tetragon-api\n    name: Tetragon API\n    tags:\n      - eBPF\n      - Kubernetes\n      - Observability\n      - Security\n    humanURL: https://tetragon.io/docs/reference/grpc-api/\n    properties:\n\
  \      - url: https://tetragon.io/docs/reference/grpc-api/\n        type: Documentation\n      - url: https://tetragon.io/docs/\n        type: Reference\n      - url: https://github.com/cilium/tetragon\n        type: GitHubRepository\n      - url: https://tetragon.io/docs/getting-started/\n        type: Getting Started\n      - url: https://github.com/cilium/tetragon/releases\n        type: Change Log\n    description: >-\n      The Tetragon gRPC API provides access to eBPF-based security observability\n      and runtime enforcement capabilities. It enables querying of kernel-level\n      events including process execution, file access, and network activity,\n      and supports defining tracing policies via Kubernetes custom resources for\n      real-time enforcement and event streaming.\n  - aid: cilium:cilium-operator-api\n    name: Cilium Operator API\n    tags:\n      - eBPF\n      - Kubernetes\n      - Networking\n      - Operations\n    humanURL: https://docs.cilium.io/en/stable/internals/\n\
  \    baseURL: https://localhost/v1\n    properties:\n      - url: https://docs.cilium.io/en/stable/internals/\n        type: Documentation\n      - url: https://github.com/cilium/cilium/blob/main/api/v1/operator/openapi.yaml\n        type: OpenAPI\n      - url: https://github.com/cilium/cilium/releases\n        type: Change Log\n    description: >-\n      The Cilium Operator API provides a REST interface for the Cilium operator\n      component, which handles cluster-wide tasks such as garbage collection of\n      Cilium endpoints and identities, node IPAM management, and coordination\n      of cluster mesh operations. It exposes health and status endpoints for\n      operator lifecycle management in Kubernetes deployments.\n  - aid: cilium:hubble-relay-api\n    name: Hubble Relay API\n    tags:\n      - gRPC\n      - Kubernetes\n      - Networking\n      - Observability\n    humanURL: https://docs.cilium.io/en/stable/observability/hubble/index.html\n    properties:\n      - url: https://docs.cilium.io/en/stable/observability/hubble/index.html\n\
  \        type: Documentation\n      - url: https://github.com/cilium/cilium/tree/main/api/v1/relay\n        type: Reference\n      - url: https://github.com/cilium/cilium\n        type: GitHubRepository\n      - url: https://github.com/cilium/cilium/releases\n        type: Change Log\n    description: >-\n      The Hubble Relay API is a gRPC service that aggregates and relays network\n      flow data from multiple Hubble agents running across Kubernetes cluster\n      nodes. It provides a single cluster-wide endpoint for the Hubble Observer\n      service, enabling centralized queries of flow data, DNS events, and HTTP\n      metrics from all nodes through Hubble Relay without connecting to each\n      node individually.\ncommon:\n  - type: Website\n    url: https://cilium.io/\n  - type: Documentation\n    url: https://docs.cilium.io/\n  - type: GettingStarted\n    url: https://docs.cilium.io/en/stable/gettingstarted/\n  - type: GitHubOrganization\n    url: https://github.com/cilium\n\
  \  - type: GitHubRepository\n    url: https://github.com/cilium/cilium\n  - type: Blog\n    url: https://cilium.io/blog/\n  - type: Community\n    url: https://cilium.io/get-involved/\n  - type: Support\n    url: https://cilium.io/get-help/\n  - type: PrivacyPolicy\n    url: https://cilium.io/privacy/\n  - type: Slack\n    url: https://slack.cilium.io/\n  - type: ChangeLog\n    url: https://github.com/cilium/cilium/releases\n  - type: YouTube\n    url: https://www.youtube.com/@CiliumProject\n  - type: TermsOfService\n    url: https://cilium.io/terms/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/cilium\n  - type: JSONLDContext\n    url: json-ld/cilium-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cilium-endpoint-schema.json\n  - type: AsyncAPI\n    url: asyncapi/cilium-hubble-asyncapi.yml\n  - type: OpenAPI\n    url: openapi/cilium-api-openapi.yml\n  - type: Spectral\n    url: spectral/cilium-spectral.yml\n  - type: NaftikoCapabilities\n   \
  \ url: naftiko/cilium-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.20'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml
tags:
- Cloud Native
- eBPF
- Kubernetes
- Networking
- Security
url: https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml
use_cases: []
---
