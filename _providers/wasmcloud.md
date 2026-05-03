---
api_count: 5
api_specs:
- filename: wasmcloud-control-asyncapi.yml
  format: yaml
  label: wasmCloud Control Interface API
  slug: wasmcloud-control-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/asyncapi/wasmcloud-control-asyncapi.yml
- filename: wasmcloud-wadm-asyncapi.yml
  format: yaml
  label: wasmCloud Application Deployment Manager (wadm) API
  slug: wasmcloud-wadm-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/asyncapi/wasmcloud-wadm-asyncapi.yml
apis:
- description: The wasmCloud control interface provides a NATS-based API for managing the wasmCloud lattice. It supports operations for starting and stopping actors and providers, establishing links between componen
  name: wasmCloud Control Interface API
  slug: wasmcloud-control-api
- description: 'wadm provides a declarative application deployment API for wasmCloud. Applications are defined as YAML manifests specifying components, capability providers, and their links. wadm manages the desired '
  name: wasmCloud Application Deployment Manager (wadm) API
  slug: wasmcloud-wadm-api
- description: wash (WAsmcloud SHell) is the comprehensive command-line tool for developing, building, deploying, and managing wasmCloud applications and WebAssembly components. It bundles a wasmCloud host, NATS ser
  name: wasmCloud wash CLI
  slug: wasmcloud-wash-cli
- description: 'wasmCloud interfaces are defined using WebAssembly Interface Type (WIT), the open standard interface description language maintained as part of the W3C WebAssembly Component Model. wasmCloud supports '
  name: wasmCloud WIT Interfaces
  slug: wasmcloud-interfaces
- description: 'The wasmCloud Kubernetes Operator enables running wasmCloud infrastructure natively on Kubernetes clusters. It deploys wasmCloud hosts as Kubernetes workloads and bridges the Kubernetes control plane '
  name: wasmCloud Kubernetes Operator
  slug: wasmcloud-kubernetes-operator
asyncapis:
- description: AsyncAPI specification for the wasmCloud Control Interface, a NATS-based API for managing the wasmCloud lattice. Operators and tooling (wash CLI, wasmCloud dashboard, wadm) interact with wasmCloud hos
  name: wasmCloud Control Interface API
  slug: wasmcloud-control-asyncapi
- description: The wasmCloud lattice event system publishes CloudEvents-format messages to NATS subjects describing the lifecycle of components, capability providers, links, and hosts within a wasmCloud lattice. All
  name: wasmCloud Lattice Events
  slug: wasmcloud-lattice-events-asyncapi
- description: The wasmCloud Application Deployment Manager (wadm) API is exposed entirely as a NATS service using a subject-per-operation model. All API requests and responses are JSON-encoded and published on subj
  name: wasmCloud wadm Application Deployment Manager API
  slug: wasmcloud-wadm-asyncapi
common:
- title: ''
  type: Website
  url: https://wasmcloud.com
- title: ''
  type: Documentation
  url: https://wasmcloud.com/docs/
- title: ''
  type: Getting Started
  url: https://wasmcloud.com/docs/getting-started/
- title: ''
  type: Blog
  url: https://wasmcloud.com/blog/
- title: ''
  type: Community
  url: https://wasmcloud.com/community/
- title: ''
  type: GitHubOrganization
  url: https://github.com/wasmCloud
- title: ''
  type: GitHubRepository
  url: https://github.com/wasmCloud/wasmCloud
- title: ''
  type: Change Log
  url: https://github.com/wasmcloud/wasmcloud/releases
- title: ''
  type: Slack
  url: https://slack.wasmcloud.com/
- title: ''
  type: AsyncAPI
  url: asyncapi/wasmcloud-control-asyncapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/wasmcloud-wadm-asyncapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/wasmcloud-lattice-events-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/wasmcloud-manifest-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/wasmcloud-oam-manifest-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/wasmcloud-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/wasmcloud-oam-manifest-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/wasmcloud-vocabulary.yml
- title: ''
  type: KubernetesCRD
  url: crd/runtime.wasmcloud.dev_hosts.yaml
- title: ''
  type: KubernetesCRD
  url: crd/runtime.wasmcloud.dev_artifacts.yaml
- title: ''
  type: KubernetesCRD
  url: crd/runtime.wasmcloud.dev_workloads.yaml
- title: ''
  type: KubernetesCRD
  url: crd/runtime.wasmcloud.dev_workloaddeployments.yaml
- title: ''
  type: KubernetesCRD
  url: crd/runtime.wasmcloud.dev_workloadreplicasets.yaml
created: '2026-03-16'
description: wasmCloud is a CNCF incubating platform for building, managing, and scaling distributed applications using WebAssembly components. It provides a runtime that manages the lifecycle of WebAssembly actors and capability providers, enabling developers to write portable business logic that connects to infrastructure capabilities like HTTP servers, messaging, key-value stores, and databases through a declarative linking model based on WebAssembly Interface Types (WIT).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Wasmcloud Context
  property_count: 35
  slug: wasmcloud-context
layout: provider
modified: '2026-05-03'
name: wasmCloud
skills: []
slug: wasmcloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wasmcloud\nname: wasmCloud\ndescription: >-\n  wasmCloud is a CNCF incubating platform for building, managing, and scaling\n  distributed applications using WebAssembly components. It provides a runtime\n  that manages the lifecycle of WebAssembly actors and capability providers,\n  enabling developers to write portable business logic that connects to\n  infrastructure capabilities like HTTP servers, messaging, key-value stores,\n  and databases through a declarative linking model based on WebAssembly\n  Interface Types (WIT).\nurl: https://wasmcloud.com\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - CNCF\n  - Distributed Systems\n  - Incubating\n  - Runtime\n  - Wasm\n  - WebAssembly\n  - WIT\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: wasmcloud:wasmcloud-control-api\n    name: wasmCloud Control Interface API\n    description: >-\n      The\
  \ wasmCloud control interface provides a NATS-based API for managing\n      the wasmCloud lattice. It supports operations for starting and stopping\n      actors and providers, establishing links between components, querying\n      host inventories, and managing application deployments. The wash CLI\n      and wasmCloud dashboard interact with hosts through this interface.\n    humanURL: https://wasmcloud.com/docs/hosts/lattice-protocols/control-interface/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmcloud.com/docs/hosts/lattice-protocols/control-interface/\n      - type: Reference\n        url: https://wasmcloud.com/docs/concepts/\n      - type: AsyncAPI\n        url: asyncapi/wasmcloud-control-asyncapi.yml\n      - type: AsyncAPI\n        url: asyncapi/wasmcloud-lattice-events-asyncapi.yml\n    tags:\n      - Control API\n      - Lattice Management\n      - NATS\n  - aid:\
  \ wasmcloud:wasmcloud-wadm-api\n    name: wasmCloud Application Deployment Manager (wadm) API\n    description: >-\n      wadm provides a declarative application deployment API for wasmCloud.\n      Applications are defined as YAML manifests specifying components,\n      capability providers, and their links. wadm manages the desired state\n      of applications across the lattice, handling scaling, updates, and\n      self-healing through reconciliation loops using the Open Application Model format.\n    humanURL: https://wasmcloud.com/docs/ecosystem/wadm/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmcloud.com/docs/ecosystem/wadm/\n      - type: Reference\n        url: https://wasmcloud.com/docs/ecosystem/wadm/api/\n      - type: GitHubRepository\n        url: https://github.com/wasmCloud/wadm\n      - type: JSONSchema\n        url: json-schema/wasmcloud-manifest-schema.json\n\
  \      - type: AsyncAPI\n        url: asyncapi/wasmcloud-wadm-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/wasmcloud-oam-manifest-schema.json\n    tags:\n      - Application Management\n      - Declarative\n      - Deployment\n      - OAM\n  - aid: wasmcloud:wasmcloud-wash-cli\n    name: wasmCloud wash CLI\n    description: >-\n      wash (WAsmcloud SHell) is the comprehensive command-line tool for\n      developing, building, deploying, and managing wasmCloud applications and\n      WebAssembly components. It bundles a wasmCloud host, NATS server, and wadm\n      for local development, and supports publishing components to OCI registries\n      and managing remote lattices.\n    humanURL: https://wasmcloud.com/docs/cli/wash/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmcloud.com/docs/cli/wash/\n      - type: Getting Started\n        url: https://wasmcloud.com/docs/getting-started/\n\
  \      - type: GitHubRepository\n        url: https://github.com/wasmCloud/wash\n      - type: Change Log\n        url: https://github.com/wasmCloud/wash/releases\n    tags:\n      - CLI\n      - Developer Tools\n      - WebAssembly\n  - aid: wasmcloud:wasmcloud-interfaces\n    name: wasmCloud WIT Interfaces\n    description: >-\n      wasmCloud interfaces are defined using WebAssembly Interface Type (WIT),\n      the open standard interface description language maintained as part of the\n      W3C WebAssembly Component Model. wasmCloud supports WASI 0.2 interfaces\n      as well as wasmCloud-specific interfaces for capability providers covering\n      HTTP, messaging, key-value, blobstore, and other infrastructure concerns.\n    humanURL: https://wasmcloud.com/docs/concepts/interfaces/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmcloud.com/docs/concepts/interfaces/\n     \
  \ - type: Reference\n        url: https://wasmcloud.com/docs/reference/wasi/support/\n      - type: GitHubRepository\n        url: https://github.com/wasmCloud/wasmCloud\n    tags:\n      - Interfaces\n      - WASI\n      - WebAssembly\n      - WIT\n  - aid: wasmcloud:wasmcloud-kubernetes-operator\n    name: wasmCloud Kubernetes Operator\n    description: >-\n      The wasmCloud Kubernetes Operator enables running wasmCloud infrastructure\n      natively on Kubernetes clusters. It deploys wasmCloud hosts as Kubernetes\n      workloads and bridges the Kubernetes control plane with the wasmCloud\n      lattice, enabling seamless integration with existing Kubernetes tooling\n      and GitOps workflows. Defines CRDs for Hosts, Artifacts, Workloads,\n      WorkloadDeploments, and WorkloadReplicaSets under the runtime.wasmcloud.dev group.\n    humanURL: https://wasmcloud.com/docs/deployment/k8s/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n\
  \      - type: Documentation\n        url: https://wasmcloud.com/docs/deployment/k8s/\n      - type: GitHubRepository\n        url: https://github.com/wasmCloud/wasmcloud-operator\n      - type: KubernetesCRD\n        url: crd/runtime.wasmcloud.dev_hosts.yaml\n      - type: KubernetesCRD\n        url: crd/runtime.wasmcloud.dev_artifacts.yaml\n      - type: KubernetesCRD\n        url: crd/runtime.wasmcloud.dev_workloads.yaml\n      - type: KubernetesCRD\n        url: crd/runtime.wasmcloud.dev_workloaddeployments.yaml\n      - type: KubernetesCRD\n        url: crd/runtime.wasmcloud.dev_workloadreplicasets.yaml\n    tags:\n      - Kubernetes\n      - Operator\n      - Deployment\ncommon:\n  - type: Website\n    url: https://wasmcloud.com\n  - type: Documentation\n    url: https://wasmcloud.com/docs/\n  - type: Getting Started\n    url: https://wasmcloud.com/docs/getting-started/\n  - type: Blog\n    url: https://wasmcloud.com/blog/\n  - type: Community\n    url: https://wasmcloud.com/community/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/wasmCloud\n  - type: GitHubRepository\n    url: https://github.com/wasmCloud/wasmCloud\n  - type: Change Log\n    url: https://github.com/wasmcloud/wasmcloud/releases\n  - type: Slack\n    url: https://slack.wasmcloud.com/\n  - type: AsyncAPI\n    url: asyncapi/wasmcloud-control-asyncapi.yml\n  - type: AsyncAPI\n    url: asyncapi/wasmcloud-wadm-asyncapi.yml\n  - type: AsyncAPI\n    url: asyncapi/wasmcloud-lattice-events-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/wasmcloud-manifest-schema.json\n  - type: JSONSchema\n    url: json-schema/wasmcloud-oam-manifest-schema.json\n  - type: JSON-LD\n    url: json-ld/wasmcloud-context.jsonld\n  - type: JSONStructure\n    url: json-structure/wasmcloud-oam-manifest-structure.json\n  - type: Vocabulary\n    url: vocabulary/wasmcloud-vocabulary.yml\n  - type: KubernetesCRD\n    url: crd/runtime.wasmcloud.dev_hosts.yaml\n  - type: KubernetesCRD\n    url: crd/runtime.wasmcloud.dev_artifacts.yaml\n\
  \  - type: KubernetesCRD\n    url: crd/runtime.wasmcloud.dev_workloads.yaml\n  - type: KubernetesCRD\n    url: crd/runtime.wasmcloud.dev_workloaddeployments.yaml\n  - type: KubernetesCRD\n    url: crd/runtime.wasmcloud.dev_workloadreplicasets.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wasmcloud/refs/heads/main/apis.yml
tags:
- Cloud Native
- CNCF
- Distributed Systems
- Incubating
- Runtime
- Wasm
- WebAssembly
- WIT
url: https://wasmcloud.com
use_cases: []
---
