---
api_count: 6
api_specs:
- filename: kubernetes-operators-watch-asyncapi.yml
  format: yaml
  label: Kubernetes Operators
  slug: kubernetes-operators
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/asyncapi/kubernetes-operators-watch-asyncapi.yml
- filename: kubernetes-crd-openapi.yml
  format: yaml
  label: Kubernetes Custom Resource Definitions
  slug: custom-resource-definitions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/openapi/kubernetes-crd-openapi.yml
- filename: kubernetes-olm-openapi.yml
  format: yaml
  label: Operator Lifecycle Manager
  slug: operator-lifecycle-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/openapi/kubernetes-olm-openapi.yml
apis:
- description: 'Kubernetes Operators extend the Kubernetes API for managing complex stateful applications using custom resources and controllers. An Operator encodes the operational knowledge of a domain expert into '
  name: Kubernetes Operators
  slug: kubernetes-operators
- description: 'The CustomResourceDefinition (CRD) API lets you extend the Kubernetes API by defining new resource types with custom schemas. When a CRD is created, the Kubernetes API server automatically serves and '
  name: Kubernetes Custom Resource Definitions
  slug: custom-resource-definitions
- description: The Operator SDK is a framework for building Kubernetes Operators in Go, Ansible, or Helm. It provides high-level APIs, abstractions, scaffolding tools, and CLI commands that simplify writing operator
  name: Operator SDK
  slug: operator-sdk
- description: The Operator Lifecycle Manager (OLM) extends Kubernetes with a declarative API for installing, upgrading, and managing the lifecycle of Operators and their dependencies in a cluster. OLM provides clus
  name: Operator Lifecycle Manager
  slug: operator-lifecycle-manager
- description: OperatorHub.io is a community registry of Kubernetes Operators that can be discovered and installed via the Operator Lifecycle Manager. It provides a catalog of operators across categories including d
  name: OperatorHub
  slug: operatorhub
- description: controller-runtime is a set of Go libraries for building Kubernetes controllers and operators. It is used by both Kubebuilder and Operator SDK and provides core abstractions including Manager, Client,
  name: Controller-Runtime
  slug: controller-runtime
asyncapis:
- description: The Kubernetes Operators watch API provides streaming event notifications for operator-related resources including CustomResourceDefinitions, OLM resources (CatalogSources, Subscriptions, InstallPlans
  name: Kubernetes Operators Watch Events
  slug: kubernetes-operators-watch-asyncapi
common:
- title: ''
  type: Website
  url: https://kubernetes.io
- title: ''
  type: Documentation
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/
- title: ''
  type: Getting Started
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- title: ''
  type: GitHub Organization
  url: https://github.com/operator-framework
- title: ''
  type: GitHubRepository
  url: https://github.com/operator-framework/operator-sdk
- title: ''
  type: Blog
  url: https://kubernetes.io/blog/
- title: ''
  type: Community
  url: https://kubernetes.io/community/
- title: ''
  type: Change Log
  url: https://kubernetes.io/releases/
- title: ''
  type: JSONSchema
  url: json-schema/kubernetes-operator-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/kubernetes-operators-context.jsonld
created: '2025-01-01'
description: Kubernetes Operators are a method of packaging, deploying, and managing Kubernetes applications that extend the Kubernetes API to create, configure, and manage instances of complex applications on behalf of a Kubernetes user.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kubernetes Operators Context
  property_count: 20
  slug: kubernetes-operators-context
layout: provider
modified: '2026-04-28'
name: Kubernetes Operators
skills: []
slug: kubernetes-operators
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubernetes-operators\nname: Kubernetes Operators\ndescription: >-\n  Kubernetes Operators are a method of packaging, deploying, and managing\n  Kubernetes applications that extend the Kubernetes API to create, configure,\n  and manage instances of complex applications on behalf of a Kubernetes user.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Cloud Native\n  - DevOps\n  - Infrastructure\n  - Kubernetes\nurl: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kubernetes-operators:kubernetes-operators\n    name: Kubernetes Operators\n    description: >-\n      Kubernetes Operators extend the Kubernetes API for managing complex\n      stateful applications using custom resources and controllers. An Operator\n      encodes the operational knowledge of a domain\
  \ expert into software that\n      automates the deployment, scaling, and management of Kubernetes\n      applications.\n    humanURL: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/\n    tags:\n      - Automation\n      - Cloud Native\n      - Custom Resources\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/\n      - type: AsyncAPI\n        url: asyncapi/kubernetes-operators-watch-asyncapi.yml\n  - aid: kubernetes-operators:custom-resource-definitions\n    name: Kubernetes Custom Resource Definitions\n    description: >-\n      The CustomResourceDefinition (CRD) API lets you extend the Kubernetes API\n      by defining new resource types with custom schemas. When a CRD is created,\n      the Kubernetes API server automatically serves and handles storage for the\n     \
  \ new custom resource, enabling operators and other controllers to manage\n      domain-specific objects.\n    humanURL: https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/\n    tags:\n      - API Extension\n      - Cloud Native\n      - Custom Resources\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/custom-resource-definition-v1/\n      - type: Getting Started\n        url: https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/\n      - type: OpenAPI\n        url: openapi/kubernetes-crd-openapi.yml\n      - type: JSONSchema\n        url: json-schema/kubernetes-operator-schema.json\n  - aid: kubernetes-operators:operator-sdk\n    name: Operator SDK\n    description: >-\n      The Operator\
  \ SDK is a framework for building Kubernetes Operators in Go,\n      Ansible, or Helm. It provides high-level APIs, abstractions, scaffolding\n      tools, and CLI commands that simplify writing operator logic and\n      integrating with the Operator Lifecycle Manager (OLM) for packaging and\n      distribution.\n    humanURL: https://sdk.operatorframework.io/\n    tags:\n      - Go\n      - Kubernetes\n      - Operators\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://sdk.operatorframework.io/docs/overview/\n      - type: Getting Started\n        url: https://sdk.operatorframework.io/docs/building-operators/golang/tutorial/\n      - type: GitHubRepository\n        url: https://github.com/operator-framework/operator-sdk\n  - aid: kubernetes-operators:operator-lifecycle-manager\n    name: Operator Lifecycle Manager\n    description: >-\n      The Operator Lifecycle Manager (OLM) extends Kubernetes with a declarative\n      API for installing, upgrading, and\
  \ managing the lifecycle of Operators and\n      their dependencies in a cluster. OLM provides cluster administrators with\n      fine-grained control over what operators are available and which namespaces\n      they can operate in.\n    humanURL: https://olm.operatorframework.io/\n    tags:\n      - Cloud Native\n      - Kubernetes\n      - Lifecycle Management\n      - Operators\n    properties:\n      - type: Documentation\n        url: https://olm.operatorframework.io/docs/\n      - type: GitHubRepository\n        url: https://github.com/operator-framework/operator-lifecycle-manager\n      - type: Change Log\n        url: https://github.com/operator-framework/operator-lifecycle-manager/releases\n      - type: OpenAPI\n        url: openapi/kubernetes-olm-openapi.yml\n  - aid: kubernetes-operators:operatorhub\n    name: OperatorHub\n    description: >-\n      OperatorHub.io is a community registry of Kubernetes Operators that can\n      be discovered and installed via the Operator Lifecycle\
  \ Manager. It\n      provides a catalog of operators across categories including databases,\n      monitoring, security, and networking for use in Kubernetes clusters.\n    humanURL: https://operatorhub.io/\n    tags:\n      - Community\n      - Kubernetes\n      - Operators\n      - Registry\n    properties:\n      - type: Documentation\n        url: https://operatorhub.io/\n  - aid: kubernetes-operators:controller-runtime\n    name: Controller-Runtime\n    description: >-\n      controller-runtime is a set of Go libraries for building Kubernetes\n      controllers and operators. It is used by both Kubebuilder and Operator SDK\n      and provides core abstractions including Manager, Client, Cache, and\n      Reconciler interfaces for building controllers that interact with the\n      Kubernetes API.\n    humanURL: https://github.com/kubernetes-sigs/controller-runtime\n    tags:\n      - Controllers\n      - Go\n      - Kubernetes\n      - SDK\n    properties:\n      - type: Documentation\n\
  \        url: https://pkg.go.dev/sigs.k8s.io/controller-runtime\n      - type: GitHubRepository\n        url: https://github.com/kubernetes-sigs/controller-runtime\ncommon:\n  - type: Website\n    url: https://kubernetes.io\n  - type: Documentation\n    url: https://kubernetes.io/docs/concepts/extend-kubernetes/\n  - type: Getting Started\n    url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/\n  - type: GitHub Organization\n    url: https://github.com/operator-framework\n  - type: GitHubRepository\n    url: https://github.com/operator-framework/operator-sdk\n  - type: Blog\n    url: https://kubernetes.io/blog/\n  - type: Community\n    url: https://kubernetes.io/community/\n  - type: Change Log\n    url: https://kubernetes.io/releases/\n  - type: JSONSchema\n    url: json-schema/kubernetes-operator-schema.json\n  - type: JSON-LD\n    url: json-ld/kubernetes-operators-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml
tags:
- Automation
- Cloud Native
- DevOps
- Infrastructure
- Kubernetes
url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml
use_cases: []
---
