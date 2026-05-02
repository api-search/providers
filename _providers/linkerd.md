---
api_count: 5
api_specs:
- filename: linkerd-proxy-admin-openapi.yml
  format: yaml
  label: Linkerd Proxy Admin API
  slug: proxy-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-proxy-admin-openapi.yml
- filename: linkerd-viz-metrics-openapi.yml
  format: yaml
  label: Linkerd Viz Metrics API
  slug: viz-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-viz-metrics-openapi.yml
- filename: linkerd-tap-openapi.yml
  format: yaml
  label: Linkerd Tap API
  slug: tap-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-tap-openapi.yml
apis:
- description: The Linkerd proxy exposes an admin HTTP server on each meshed pod, providing health check endpoints, readiness probes, Prometheus-compatible metrics, and runtime diagnostic information. By default thi
  name: Linkerd Proxy Admin API
  slug: proxy-admin-api
- description: The Linkerd Viz extension provides a metrics API that powers the linkerd viz CLI commands and the Linkerd dashboard. It queries Prometheus for golden metrics including request volume, success rate, an
  name: Linkerd Viz Metrics API
  slug: viz-metrics-api
- description: The Linkerd Tap API is a Kubernetes aggregated API server that provides real-time streaming access to requests flowing through the Linkerd service mesh. It allows live inspection of HTTP and gRPC traf
  name: Linkerd Tap API
  slug: tap-api
- description: The Linkerd Proxy Control Plane gRPC API defines the protobuf service contracts used by the data-plane proxy to communicate with the control plane. It includes the Destination API for service discover
  name: Linkerd Proxy Control Plane API
  slug: proxy-control-plane-api
- description: 'The Linkerd Multicluster extension provides Kubernetes CRDs and a gateway component that enables transparent, secure cross-cluster service communication. It uses mTLS to authenticate workloads across '
  name: Linkerd Multicluster API
  slug: multicluster-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/linkerd-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/service-profile.json
- title: ''
  type: Website
  url: https://linkerd.io/
- title: ''
  type: Documentation
  url: https://linkerd.io/2.19/reference/
- title: ''
  type: Getting Started
  url: https://linkerd.io/2.19/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/linkerd
- title: ''
  type: GitHubRepository
  url: https://github.com/linkerd/linkerd2
- title: ''
  type: Blog
  url: https://linkerd.io/blog/
- title: ''
  type: Change Log
  url: https://github.com/linkerd/linkerd2/blob/main/CHANGES.md
- title: ''
  type: Community
  url: https://linkerd.io/community/get-involved/
- title: ''
  type: Slack
  url: https://slack.linkerd.io/
- title: ''
  type: Support
  url: https://linkerd.buoyant.io/
- title: ''
  type: Releases
  url: https://github.com/linkerd/linkerd2/releases
- title: ''
  type: Security
  url: https://github.com/linkerd/linkerd2/blob/main/SECURITY.md
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/linkerd
- title: ''
  type: YouTube
  url: https://www.youtube.com/@Linkerd
- title: ''
  type: Privacy Policy
  url: https://buoyant.io/privacy-policy
- title: ''
  type: Terms of Service
  url: https://buoyant.io/terms-of-service
created: '2025-08-19'
description: Service mesh without the mess. Linkerd adds security, observability, and reliability to any Kubernetes cluster without the complexity of bloat of other meshes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Linkerd Context
  property_count: 6
  slug: linkerd-context
layout: provider
modified: '2026-04-28'
name: Linkerd
skills: []
slug: linkerd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linkerd\nname: Linkerd\ndescription: >-\n  Service mesh without the mess. Linkerd adds security, observability, and\n  reliability to any Kubernetes cluster without the complexity of bloat of other\n  meshes.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Kubernetes\n  - mTLS\n  - Observability\n  - Security\n  - Service Mesh\ncreated: '2025-08-19'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: linkerd:proxy-admin-api\n    name: Linkerd Proxy Admin API\n    description: >-\n      The Linkerd proxy exposes an admin HTTP server on each meshed pod,\n      providing health check endpoints, readiness probes, Prometheus-compatible\n      metrics, and runtime diagnostic information. By default this server\n      listens on port 4191.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://linkerd.io/2-edge/reference/proxy-configuration/\n    baseURL: http://localhost:4191\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2-edge/reference/proxy-configuration/\n      - type: Reference\n        url: https://linkerd.io/2-edge/reference/proxy-metrics/\n      - type: OpenAPI\n        url: openapi/linkerd-proxy-admin-openapi.yml\n    tags:\n      - Health Check\n      - Metrics\n      - Prometheus\n      - Proxy\n  - aid: linkerd:viz-metrics-api\n    name: Linkerd Viz Metrics API\n    description: >-\n      The Linkerd Viz extension provides a metrics API that powers the\n      linkerd viz CLI commands and the Linkerd dashboard. It queries\n      Prometheus for golden metrics including request volume, success\n      rate, and latency distributions for HTTP, HTTP/2, and gRPC traffic\n      across meshed workloads.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://linkerd.io/2-edge/reference/cli/viz/\n\
  \    properties:\n      - type: Documentation\n        url: https://linkerd.io/2-edge/reference/cli/viz/\n      - type: OpenAPI\n        url: openapi/linkerd-viz-metrics-openapi.yml\n      - type: JSONSchema\n        url: json-schema/stat-summary.json\n      - type: JSONSchema\n        url: json-schema/edge.json\n      - type: JSONSchema\n        url: json-schema/gateway.json\n      - type: JSONLD\n        url: json-ld/linkerd-context.jsonld\n    tags:\n      - Dashboard\n      - Metrics\n      - Observability\n      - Statistics\n  - aid: linkerd:tap-api\n    name: Linkerd Tap API\n    description: >-\n      The Linkerd Tap API is a Kubernetes aggregated API server that\n      provides real-time streaming access to requests flowing through\n      the Linkerd service mesh. It allows live inspection of HTTP and\n      gRPC traffic including headers, paths, response codes, and\n      latency. Access is controlled via Kubernetes RBAC.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://linkerd.io/2-edge/reference/cli/viz/\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2-edge/reference/cli/viz/\n      - type: OpenAPI\n        url: openapi/linkerd-tap-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tap-event.json\n      - type: JSONLD\n        url: json-ld/linkerd-context.jsonld\n    tags:\n      - Debugging\n      - Real-Time\n      - Tap\n      - Traffic Inspection\n  - aid: linkerd:proxy-control-plane-api\n    name: Linkerd Proxy Control Plane API\n    description: >-\n      The Linkerd Proxy Control Plane gRPC API defines the protobuf service\n      contracts used by the data-plane proxy to communicate with the control\n      plane. It includes the Destination API for service discovery and traffic\n      policy, the Identity API for issuing mTLS certificates, and the Inbound\n      API for per-port authorization and rate-limiting policies.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://github.com/linkerd/linkerd2-proxy-api\n    tags:\n      - Control Plane\n      - gRPC\n      - mTLS\n      - Policy\n    properties:\n      - type: Documentation\n        url: https://github.com/linkerd/linkerd2-proxy-api\n      - type: Reference\n        url: https://linkerd.io/2-edge/reference/authorization-policy/\n      - type: GitHubRepository\n        url: https://github.com/linkerd/linkerd2-proxy-api\n      - type: JSONSchema\n        url: json-schema/service-profile.json\n  - aid: linkerd:multicluster-api\n    name: Linkerd Multicluster API\n    description: >-\n      The Linkerd Multicluster extension provides Kubernetes CRDs and a\n      gateway component that enables transparent, secure cross-cluster service\n      communication. It uses mTLS to authenticate workloads across cluster\n      boundaries within a unified trust domain, allowing services in different\n      clusters to communicate as if they were local.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://linkerd.io/2-edge/features/multicluster/\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2-edge/features/multicluster/\n      - type: Reference\n        url: https://linkerd.io/2-edge/reference/multicluster/\n    tags:\n      - Federation\n      - Kubernetes\n      - mTLS\n      - Multicluster\ncommon:\n  - type: JSON-LD\n    url: json-ld/linkerd-context.jsonld\n  - type: JSONSchema\n    url: json-schema/service-profile.json\n  - type: Website\n    url: https://linkerd.io/\n  - type: Documentation\n    url: https://linkerd.io/2.19/reference/\n  - type: Getting Started\n    url: https://linkerd.io/2.19/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/linkerd\n  - type: GitHubRepository\n    url: https://github.com/linkerd/linkerd2\n  - type: Blog\n    url: https://linkerd.io/blog/\n  - type: Change Log\n    url: https://github.com/linkerd/linkerd2/blob/main/CHANGES.md\n  - type: Community\n    url: https://linkerd.io/community/get-involved/\n\
  \  - type: Slack\n    url: https://slack.linkerd.io/\n  - type: Support\n    url: https://linkerd.buoyant.io/\n  - type: Releases\n    url: https://github.com/linkerd/linkerd2/releases\n  - type: Security\n    url: https://github.com/linkerd/linkerd2/blob/main/SECURITY.md\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/linkerd\n  - type: YouTube\n    url: https://www.youtube.com/@Linkerd\n  - type: Privacy Policy\n    url: https://buoyant.io/privacy-policy\n  - type: Terms of Service\n    url: https://buoyant.io/terms-of-service\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/apis.yml
tags:
- Kubernetes
- mTLS
- Observability
- Security
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/apis.yml
use_cases: []
---
