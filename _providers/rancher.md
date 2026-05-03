---
api_count: 1
api_specs:
- filename: rancher-management-api-openapi.yml
  format: yaml
  label: Rancher Management API
  slug: rancher-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/openapi/rancher-management-api-openapi.yml
apis:
- description: The Rancher Management API exposes Rancher's multi-cluster Kubernetes management capabilities as Kubernetes-style REST resources. It supports automation of cluster lifecycle, project and namespace man
  name: Rancher Management API
  slug: rancher-management-api
capabilities:
- description: Workflow capability for managing users, roles, tokens, and access policies in Rancher. Enables platform administrators to provision users, assign role templates, manage API tokens, and enforce RBAC ac
  name: Rancher Access Control
  slug: access-control
- description: 'Workflow capability for managing the full lifecycle of Kubernetes clusters through Rancher: provisioning new clusters, inspecting cluster health and node status, managing projects and namespaces, and '
  name: Rancher Cluster Lifecycle Management
  slug: cluster-lifecycle
common:
- title: ''
  type: Website
  url: https://www.rancher.com/
- title: ''
  type: Documentation
  url: https://ranchermanager.docs.rancher.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/rancher
- title: ''
  type: GitHub Repository
  url: https://github.com/rancher/rancher
- title: ''
  type: Blog
  url: https://www.suse.com/c/rancher/
- title: ''
  type: Pricing
  url: https://www.rancher.com/pricing
- title: ''
  type: Sign Up
  url: https://www.rancher.com/quick-start
- title: ''
  type: Support
  url: https://www.rancher.com/support-maintenance-terms
- title: ''
  type: Vocabulary
  url: vocabulary/rancher-vocabulary.yml
created: '2026-03-26'
description: Rancher is an open source container management platform built by SUSE that provides a complete software stack for teams adopting containers. It simplifies Kubernetes cluster deployment and management across any infrastructure, providing unified security, policy, and user management across all clusters. The Rancher Management API exposes these capabilities as Kubernetes-style REST resources for automation and platform engineering.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Rancher Context
  property_count: 1
  slug: rancher-context
layout: provider
modified: '2026-05-02'
name: Rancher
rules:
- name: Rancher API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 2
    info: 0
    warn: 4
  slug: rancher-rules
skills: []
slug: rancher
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rancher\nname: Rancher\ndescription: >-\n  Rancher is an open source container management platform built by SUSE that\n  provides a complete software stack for teams adopting containers. It\n  simplifies Kubernetes cluster deployment and management across any\n  infrastructure, providing unified security, policy, and user management\n  across all clusters. The Rancher Management API exposes these capabilities\n  as Kubernetes-style REST resources for automation and platform engineering.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cluster Management\n  - Containers\n  - Kubernetes\n  - Multi-Cluster\n  - Open Source\n  - SUSE\n  - Platform Engineering\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rancher:rancher-management-api\n    name: Rancher Management API\n    description:\
  \ >-\n      The Rancher Management API exposes Rancher's multi-cluster Kubernetes\n      management capabilities as Kubernetes-style REST resources. It supports\n      automation of cluster lifecycle, project and namespace management, user\n      and access control, catalog and app management, and integration of\n      Rancher into CI/CD and platform engineering workflows. Authentication is\n      via bearer tokens generated from the Rancher UI or via the login\n      endpoint, and the API is reached through the Rancher server URL.\n    humanURL: https://ranchermanager.docs.rancher.com/api/quickstart\n    baseURL: https://{rancher_host}/v3\n    tags:\n      - Cluster Management\n      - Containers\n      - Kubernetes\n      - Multi-Cluster\n      - Open Source\n      - SUSE\n    properties:\n      - type: Documentation\n        url: https://ranchermanager.docs.rancher.com/\n      - type: Getting Started\n        url: https://ranchermanager.docs.rancher.com/getting-started/overview\n  \
  \    - type: API Quick Start\n        url: https://ranchermanager.docs.rancher.com/api/quickstart\n      - type: OpenAPI\n        url: openapi/rancher-management-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/rancher-cluster.json\n      - type: JSONSchema\n        url: json-schema/rancher-project.json\n      - type: JSONSchema\n        url: json-schema/rancher-node.json\n      - type: JSONLD\n        url: json-ld/rancher-context.jsonld\n      - type: JSONStructure\n        url: json-structure/rancher-cluster-structure.json\n      - type: JSONStructure\n        url: json-structure/rancher-project-structure.json\n      - type: JSONStructure\n        url: json-structure/rancher-node-structure.json\n      - type: Example\n        url: examples/rancher-list-clusters-example.json\n      - type: Example\n        url: examples/rancher-create-cluster-example.json\n      - type: Example\n        url: examples/rancher-list-projects-example.json\n      - type: SpectralRules\n\
  \        url: rules/rancher-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/cluster-lifecycle.yaml\n      - type: NaftikoCapabilities\n        url: capabilities/access-control.yaml\ncommon:\n  - type: Website\n    url: https://www.rancher.com/\n  - type: Documentation\n    url: https://ranchermanager.docs.rancher.com/\n  - type: GitHub Organization\n    url: https://github.com/rancher\n  - type: GitHub Repository\n    url: https://github.com/rancher/rancher\n  - type: Blog\n    url: https://www.suse.com/c/rancher/\n  - type: Pricing\n    url: https://www.rancher.com/pricing\n  - type: Sign Up\n    url: https://www.rancher.com/quick-start\n  - type: Support\n    url: https://www.rancher.com/support-maintenance-terms\n  - type: Vocabulary\n    url: vocabulary/rancher-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml
tags:
- Cluster Management
- Containers
- Kubernetes
- Multi-Cluster
- Open Source
- SUSE
- Platform Engineering
url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml
use_cases: []
---
