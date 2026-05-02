---
api_count: 3
api_specs:
- filename: kuma-api-openapi.yml
  format: yaml
  label: Kuma API
  slug: kuma-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/openapi/kuma-api-openapi.yml
apis:
- description: Kuma's control plane REST API for managing service mesh policies, dataplanes, zones, and configurations. It provides endpoints for inspecting and managing all mesh resources including traffic policies
  name: Kuma API
  slug: kuma-api
- description: Kuma extends the Kubernetes API server with Custom Resource Definitions (CRDs) for defining and managing service mesh policies. These resources include MeshTrafficPermission, MeshRetry, MeshTimeout, M
  name: Kuma Kubernetes Policy API
  slug: kuma-kubernetes-policy-api
- description: Kuma's Multizone deployment API enables managing service meshes across multiple Kubernetes clusters and Universal zones from a single global control plane. It provides resources for zone management, c
  name: Kuma Multizone API
  slug: kuma-multizone-api
common:
- title: ''
  type: Website
  url: https://kuma.io/
- title: ''
  type: Documentation
  url: https://kuma.io/docs/
- title: ''
  type: Getting Started
  url: https://kuma.io/docs/latest/installation/
- title: ''
  type: GitHub Organization
  url: https://github.com/kumahq
- title: ''
  type: GitHubRepository
  url: https://github.com/kumahq/kuma
- title: ''
  type: Community
  url: https://kuma.io/community/
- title: ''
  type: Blog
  url: https://kuma.io/blog/
- title: ''
  type: Slack
  url: https://kuma-mesh.slack.com/
- title: ''
  type: Change Log
  url: https://github.com/kumahq/kuma/releases
- title: ''
  type: Support
  url: https://kuma.io/community/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/kuma
- title: ''
  type: Security
  url: https://github.com/kumahq/kuma/blob/master/SECURITY.md
- title: ''
  type: YouTube
  url: https://www.youtube.com/@KumaMesh
- title: ''
  type: JSONSchema
  url: json-schema/kuma-mesh-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/kuma-context.jsonld
created: '2026-03-16'
description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Kuma Context
  property_count: 0
  slug: kuma-context
layout: provider
modified: '2026-04-28'
name: Kuma
skills: []
slug: kuma
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kuma\nname: Kuma\ndescription: >-\n  Kuma is a platform-agnostic open-source service mesh built on top of Envoy\n  proxy. It provides universal connectivity, security, and observability for\n  services and microservices running on any infrastructure including Kubernetes\n  and VMs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Envoy\n  - Kubernetes\n  - Microservices\n  - Security\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kuma:kuma-api\n    name: Kuma API\n    description: >-\n      Kuma's control plane REST API for managing service mesh policies,\n      dataplanes, zones, and configurations. It provides endpoints for\n      inspecting and managing all mesh resources including traffic policies,\n      service discovery, and health checks across Universal\
  \ and Kubernetes\n      deployments.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://kuma.io/docs/latest/reference/http-api/\n    baseURL: https://localhost:5681\n    tags:\n      - Control Plane\n      - Management\n      - REST API\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://kuma.io/docs/latest/reference/http-api/\n      - type: Getting Started\n        url: https://kuma.io/docs/latest/installation/\n      - type: Reference\n        url: https://kuma.io/docs/latest/reference/http-api/\n      - type: OpenAPI\n        url: openapi/kuma-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/kuma-mesh-schema.json\n  - aid: kuma:kuma-kubernetes-policy-api\n    name: Kuma Kubernetes Policy API\n    description: >-\n      Kuma extends the Kubernetes API server with Custom Resource Definitions\n      (CRDs) for defining and managing service mesh policies. These resources\n\
  \      include MeshTrafficPermission, MeshRetry, MeshTimeout, MeshCircuitBreaker,\n      MeshHealthCheck, MeshFaultInjection, and MeshRateLimit, enabling\n      fine-grained traffic management, security, and resilience policies for\n      meshed workloads.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://kuma.io/docs/latest/policies/\n    tags:\n      - CRD\n      - Kubernetes\n      - Policy\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://kuma.io/docs/latest/policies/\n      - type: Reference\n        url: https://kuma.io/docs/latest/reference/kubernetes-annotations/\n  - aid: kuma:kuma-multizone-api\n    name: Kuma Multizone API\n    description: >-\n      Kuma's Multizone deployment API enables managing service meshes across\n      multiple Kubernetes clusters and Universal zones from a single global\n      control plane. It provides resources for zone management, cross-zone\n\
  \      traffic routing, and zone egress and ingress configuration.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://kuma.io/docs/latest/production/deployment/multi-zone/\n    tags:\n      - Control Plane\n      - Federation\n      - Multi-Cluster\n      - Multizone\n    properties:\n      - type: Documentation\n        url: https://kuma.io/docs/latest/production/deployment/multi-zone/\n      - type: Reference\n        url: https://kuma.io/docs/latest/reference/http-api/\ncommon:\n  - type: Website\n    url: https://kuma.io/\n  - type: Documentation\n    url: https://kuma.io/docs/\n  - type: Getting Started\n    url: https://kuma.io/docs/latest/installation/\n  - type: GitHub Organization\n    url: https://github.com/kumahq\n  - type: GitHubRepository\n    url: https://github.com/kumahq/kuma\n  - type: Community\n    url: https://kuma.io/community/\n  - type: Blog\n    url: https://kuma.io/blog/\n  - type: Slack\n    url: https://kuma-mesh.slack.com/\n\
  \  - type: Change Log\n    url: https://github.com/kumahq/kuma/releases\n  - type: Support\n    url: https://kuma.io/community/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/kuma\n  - type: Security\n    url: https://github.com/kumahq/kuma/blob/master/SECURITY.md\n  - type: YouTube\n    url: https://www.youtube.com/@KumaMesh\n  - type: JSONSchema\n    url: json-schema/kuma-mesh-schema.json\n  - type: JSON-LD\n    url: json-ld/kuma-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/apis.yml
tags:
- Envoy
- Kubernetes
- Microservices
- Security
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/apis.yml
use_cases: []
---
