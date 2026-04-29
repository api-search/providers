---
api_count: 3
api_specs:
- filename: cri-o-status-openapi.yml
  format: yaml
  label: CRI-O Status API
  slug: cri-o-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cri-o/refs/heads/main/openapi/cri-o-status-openapi.yml
- filename: cri-o-metrics-openapi.yml
  format: yaml
  label: CRI-O Metrics API
  slug: cri-o-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cri-o/refs/heads/main/openapi/cri-o-metrics-openapi.yml
apis:
- description: CRI-O implements the Kubernetes Container Runtime Interface (CRI) gRPC API that the kubelet uses to manage pod sandboxes, containers, image lifecycle, and runtime status. The CRI gRPC API is served ov
  name: CRI-O CRI gRPC API
  slug: cri-o-cri-grpc-api
- description: The CRI-O Status API is an HTTP server exposed by the cri-o daemon for runtime introspection, container inspection, and lifecycle control. It provides /info and /config endpoints for daemon configurat
  name: CRI-O Status API
  slug: cri-o-status-api
- description: The CRI-O metrics endpoint exposes Prometheus-compatible metrics for operation counts, container lifecycle, image pulls, and errors. It is enabled with the --enable-metrics flag and served on the conf
  name: CRI-O Metrics API
  slug: cri-o-metrics-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://cri-o.io/
- title: ''
  type: Documentation
  url: https://github.com/cri-o/cri-o/tree/main/docs
- title: ''
  type: GettingStarted
  url: https://github.com/cri-o/cri-o/blob/main/install.md
- title: ''
  type: GitHubOrganization
  url: https://github.com/cri-o
- title: ''
  type: GitHubRepository
  url: https://github.com/cri-o/cri-o
- title: ''
  type: Blog
  url: https://cri-o.io/#blog
- title: ''
  type: ChangeLog
  url: https://github.com/cri-o/cri-o/releases
- title: ''
  type: Community
  url: https://github.com/cri-o/cri-o#getting-started
- title: ''
  type: License
  url: https://github.com/cri-o/cri-o/blob/main/LICENSE
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/cri-o/
created: '2025-01-01'
description: CRI-O is a CNCF graduated, lightweight container runtime built specifically for Kubernetes. It implements the Kubernetes Container Runtime Interface (CRI) gRPC API and uses any Open Container Initiative (OCI) compatible runtime, including runc and crun, as the underlying container executor. CRI-O integrates with the containers/image and containers/storage libraries, the conmon container monitor, and CNI plugins to deliver a minimal kubelet-facing runtime surface, while also exposing an HTTP status API and Prometheus metrics endpoint for operations and observability.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: CRI-O
rules:
- name: CRI-O API Rules
  rule_count: 7
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 1
  slug: cri-o-metrics-rules
- name: CRI-O API Rules
  rule_count: 6
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 1
  slug: cri-o-status-rules
skills: []
slug: cri-o
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cri-o\nname: CRI-O\nx-type: opensource\ndescription: >-\n  CRI-O is a CNCF graduated, lightweight container runtime built specifically\n  for Kubernetes. It implements the Kubernetes Container Runtime Interface\n  (CRI) gRPC API and uses any Open Container Initiative (OCI) compatible\n  runtime, including runc and crun, as the underlying container executor.\n  CRI-O integrates with the containers/image and containers/storage\n  libraries, the conmon container monitor, and CNI plugins to deliver a\n  minimal kubelet-facing runtime surface, while also exposing an HTTP\n  status API and Prometheus metrics endpoint for operations and\n  observability.\nurl: https://raw.githubusercontent.com/api-evangelist/cri-o/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache 2.0\n  - CNCF\n  - Cloud Native\n  - conmon\n  - Container Runtime\n  - Containers\n  - CRI\n  - Go\n  - Graduated\n  - Kubernetes\n  - OCI\n\
  \  - Open Source\n  - Prometheus\n  - runc\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Index\naccess: Public\nposition: Provider\napis:\n  - aid: cri-o:cri-o-cri-grpc-api\n    name: CRI-O CRI gRPC API\n    description: >-\n      CRI-O implements the Kubernetes Container Runtime Interface (CRI) gRPC\n      API that the kubelet uses to manage pod sandboxes, containers, image\n      lifecycle, and runtime status. The CRI gRPC API is served over a Unix\n      domain socket (default /var/run/crio/crio.sock) and includes services\n      for RuntimeService and ImageService as defined by the upstream CRI\n      protobuf specification.\n    humanURL: https://kubernetes.io/docs/concepts/architecture/cri/\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/architecture/cri/\n      - type: Specification\n        url: https://github.com/kubernetes/cri-api\n      - type: GitHubRepository\n        url: https://github.com/cri-o/cri-o\n\
  \    tags:\n      - CRI\n      - gRPC\n      - Kubelet\n      - Kubernetes\n  - aid: cri-o:cri-o-status-api\n    name: CRI-O Status API\n    description: >-\n      The CRI-O Status API is an HTTP server exposed by the cri-o daemon for\n      runtime introspection, container inspection, and lifecycle control.\n      It provides /info and /config endpoints for daemon configuration,\n      /containers/{id} for live container inspection, /pause/{id} and\n      /unpause/{id} to control container execution, and /debug endpoints\n      for golang debugging. As noted upstream, this API is not considered\n      stable for production use.\n    humanURL: https://github.com/cri-o/cri-o\n    baseURL: http://localhost\n    properties:\n      - type: Documentation\n        url: https://github.com/cri-o/cri-o\n      - type: OpenAPI\n        url: openapi/cri-o-status-openapi.yml\n      - type: Rules\n        url: rules/cri-o-status-rules.yml\n      - type: Capabilities\n        url: capabilities/cri-o-status-capabilities.yml\n\
  \    tags:\n      - Debugging\n      - HTTP\n      - Lifecycle\n      - Status\n  - aid: cri-o:cri-o-metrics-api\n    name: CRI-O Metrics API\n    description: >-\n      The CRI-O metrics endpoint exposes Prometheus-compatible metrics for\n      operation counts, container lifecycle, image pulls, and errors. It is\n      enabled with the --enable-metrics flag and served on the configured\n      port (default 9090) at the /metrics path. The endpoint can also be\n      served over a Unix socket and secured with TLS for cluster-grade\n      observability.\n    humanURL: https://github.com/cri-o/cri-o/blob/main/docs/metrics.md\n    baseURL: http://localhost:9090\n    properties:\n      - type: Documentation\n        url: https://github.com/cri-o/cri-o/blob/main/docs/metrics.md\n      - type: OpenAPI\n        url: openapi/cri-o-metrics-openapi.yml\n      - type: Rules\n        url: rules/cri-o-metrics-rules.yml\n      - type: Capabilities\n        url: capabilities/cri-o-metrics-capabilities.yml\n\
  \    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n      - Prometheus\ncommon:\n  - type: Website\n    url: https://cri-o.io/\n  - type: Documentation\n    url: https://github.com/cri-o/cri-o/tree/main/docs\n  - type: GettingStarted\n    url: https://github.com/cri-o/cri-o/blob/main/install.md\n  - type: GitHubOrganization\n    url: https://github.com/cri-o\n  - type: GitHubRepository\n    url: https://github.com/cri-o/cri-o\n  - type: Blog\n    url: https://cri-o.io/#blog\n  - type: ChangeLog\n    url: https://github.com/cri-o/cri-o/releases\n  - type: Community\n    url: https://github.com/cri-o/cri-o#getting-started\n  - type: License\n    url: https://github.com/cri-o/cri-o/blob/main/LICENSE\n  - type: CNCF\n    url: https://www.cncf.io/projects/cri-o/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cri-o/refs/heads/main/apis.yml
tags:
- Apache 2.0
- CNCF
- Cloud Native
- conmon
- Container Runtime
- Containers
- CRI
- Go
- Graduated
- Kubernetes
- OCI
- Open Source
- Prometheus
- runc
url: https://raw.githubusercontent.com/api-evangelist/cri-o/refs/heads/main/apis.yml
use_cases: []
---
