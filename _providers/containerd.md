---
api_count: 4
api_specs:
- filename: containerd-metrics-openapi.yml
  format: yaml
  label: Containerd Metrics API
  slug: containerd-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/containerd/refs/heads/main/openapi/containerd-metrics-openapi.yml
apis:
- description: Core gRPC API for managing the full container lifecycle including containers, images, content, snapshots, namespaces, tasks, leases, events, and plugins. Provides low-level access to all containerd fu
  name: Containerd gRPC API
  slug: containerd-grpc-api
- description: Container Runtime Interface (CRI) implementation that enables Kubernetes to use containerd as its container runtime. Supports pod sandbox management, container lifecycle operations, image pulling, and
  name: Containerd CRI API
  slug: containerd-cri-api
- description: The containerd metrics plugin exposes a Prometheus-compatible HTTP endpoint for scraping runtime metrics. When enabled via the metrics.address configuration option in config.toml, it serves Prometheus
  name: Containerd Metrics API
  slug: containerd-metrics-api
- description: The Node Resource Interface (NRI) is a framework for plugging extensions into OCI-compatible container runtimes. NRI plugins receive lifecycle event notifications and can make controlled modifications
  name: Containerd NRI API
  slug: containerd-nri-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://containerd.io/
- title: ''
  type: Documentation
  url: https://containerd.io/docs/
- title: ''
  type: Getting Started
  url: https://containerd.io/docs/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/containerd
- title: ''
  type: GitHubRepository
  url: https://github.com/containerd/containerd
- title: ''
  type: Change Log
  url: https://github.com/containerd/containerd/releases
- title: ''
  type: Community
  url: https://cloud-native.slack.com/
- title: ''
  type: CNCF Project
  url: https://www.cncf.io/projects/containerd/
- title: ''
  type: License
  url: https://github.com/containerd/containerd/blob/main/LICENSE
- title: ''
  type: JSON-LD
  url: json-ld/containerd-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/containerd-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/containerd-oci-runtime-spec-schema.json
- title: ''
  type: Spectral
  url: rules/containerd-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/containerd-capabilities.yml
created: '2025-01-01'
description: An industry-standard container runtime with an emphasis on simplicity, robustness and portability.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Containerd Context
  property_count: 12
  slug: containerd-context
layout: provider
modified: '2026-03-18'
name: Containerd
rules:
- name: Containerd API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 2
  slug: containerd-rules
skills: []
slug: containerd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: containerd\nname: Containerd\ndescription: >-\n  An industry-standard container runtime with an emphasis on simplicity, robustness\n  and portability.\nurl: https://containerd.io/\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Container Runtime\n  - CRI\n  - Docker\n  - gRPC\n  - Kubernetes\n  - OCI\ncreated: '2025-01-01'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: containerd:containerd-grpc-api\n    name: Containerd gRPC API\n    description: >-\n      Core gRPC API for managing the full container lifecycle including\n      containers, images, content, snapshots, namespaces, tasks, leases,\n      events, and plugins. Provides low-level access to all containerd\n      functionality through Protocol Buffers service definitions.\n    humanURL: https://github.com/containerd/containerd/tree/main/api\n    properties:\n      - type: Documentation\n        url: https://containerd.io/docs/\n\
  \      - type: Reference\n        url: https://github.com/containerd/containerd/tree/main/api\n      - type: JSONSchema\n        url: json-schema/containerd-config-schema.json\n      - type: JSONSchema\n        url: json-schema/containerd-oci-runtime-spec-schema.json\n    tags:\n      - Container Runtime\n      - gRPC\n      - Lifecycle Management\n  - aid: containerd:containerd-cri-api\n    name: Containerd CRI API\n    description: >-\n      Container Runtime Interface (CRI) implementation that enables\n      Kubernetes to use containerd as its container runtime. Supports\n      pod sandbox management, container lifecycle operations, image\n      pulling, and streaming APIs for exec, attach, and port-forward.\n    humanURL: https://github.com/containerd/containerd/tree/main/pkg/cri\n    properties:\n      - type: Documentation\n        url: https://containerd.io/docs/\n      - type: Reference\n        url: https://github.com/containerd/containerd/tree/main/pkg/cri\n      - type: JSONSchema\n\
  \        url: json-schema/containerd-config-schema.json\n    tags:\n      - Container Runtime\n      - CRI\n      - Kubernetes\n  - aid: containerd:containerd-metrics-api\n    name: Containerd Metrics API\n    description: >-\n      The containerd metrics plugin exposes a Prometheus-compatible HTTP endpoint\n      for scraping runtime metrics. When enabled via the metrics.address\n      configuration option in config.toml, it serves Prometheus text format\n      metrics covering gRPC request counts, latency histograms, snapshot usage,\n      content store statistics, and task lifecycle events.\n    humanURL: https://containerd.io/docs/\n    properties:\n      - type: Documentation\n        url: https://containerd.io/docs/\n      - type: OpenAPI\n        url: openapi/containerd-metrics-openapi.yml\n    tags:\n      - Metrics\n      - Observability\n      - Prometheus\n  - aid: containerd:containerd-nri-api\n    name: Containerd NRI API\n    description: >-\n      The Node Resource Interface\
  \ (NRI) is a framework for plugging extensions\n      into OCI-compatible container runtimes. NRI plugins receive lifecycle\n      event notifications and can make controlled modifications to container\n      configurations before creation, enabling domain-specific resource\n      management without modifying the runtime itself.\n    humanURL: https://github.com/containerd/nri\n    properties:\n      - type: Documentation\n        url: https://github.com/containerd/containerd/blob/main/docs/NRI.md\n      - type: GitHubRepository\n        url: https://github.com/containerd/nri\n    tags:\n      - Extensibility\n      - Kubernetes\n      - NRI\n      - Plugins\ncommon:\n  - type: Website\n    url: https://containerd.io/\n  - type: Documentation\n    url: https://containerd.io/docs/\n  - type: Getting Started\n    url: https://containerd.io/docs/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/containerd\n  - type: GitHubRepository\n    url: https://github.com/containerd/containerd\n\
  \  - type: Change Log\n    url: https://github.com/containerd/containerd/releases\n  - type: Community\n    url: https://cloud-native.slack.com/\n  - type: CNCF Project\n    url: https://www.cncf.io/projects/containerd/\n  - type: License\n    url: https://github.com/containerd/containerd/blob/main/LICENSE\n  - type: JSON-LD\n    url: json-ld/containerd-context.jsonld\n  - type: JSONSchema\n    url: json-schema/containerd-config-schema.json\n  - type: JSONSchema\n    url: json-schema/containerd-oci-runtime-spec-schema.json\n  - type: Spectral\n    url: rules/containerd-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/containerd-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nx-type: opensource\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/containerd/refs/heads/main/apis.yml
tags:
- Cloud Native
- Container Runtime
- CRI
- Docker
- gRPC
- Kubernetes
- OCI
url: https://containerd.io/
use_cases: []
---
