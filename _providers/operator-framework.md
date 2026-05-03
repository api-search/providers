---
api_count: 2
apis:
- description: OLM extends Kubernetes with CRDs for operator lifecycle management including ClusterServiceVersion for describing operator capabilities and requirements, Subscription for tracking update channels, Ins
  name: Operator Lifecycle Manager API
  slug: olm-api
- description: The Operator SDK provides tools for building Kubernetes operators. It includes scaffolding commands, code generation for CRD types and controllers, integration testing harness, scorecard for validatin
  name: Operator SDK
  slug: operator-sdk
common:
- title: ''
  type: Documentation
  url: https://operatorframework.io/
- title: ''
  type: GitHubOrg
  url: https://github.com/operator-framework
created: '2026-03-16'
description: The Operator Framework is a CNCF incubating toolkit for building and managing Kubernetes Operators. It includes the Operator SDK for scaffolding and building operators using Go, Ansible, or Helm, the Operator Lifecycle Manager (OLM) for installing and managing operators on clusters, and OperatorHub for discovering and sharing operators. The framework codifies operational knowledge into software.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Operator Framework
skills: []
slug: operator-framework
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: operator-framework\nname: Operator Framework\ndescription: >-\n  The Operator Framework is a CNCF incubating toolkit for building and\n  managing Kubernetes Operators. It includes the Operator SDK for scaffolding\n  and building operators using Go, Ansible, or Helm, the Operator Lifecycle\n  Manager (OLM) for installing and managing operators on clusters, and\n  OperatorHub for discovering and sharing operators. The framework codifies\n  operational knowledge into software.\nurl: https://operatorframework.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Cloud Native\n  - Incubating\n  - Kubernetes\n  - Lifecycle Management\n  - Operators\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: operator-framework:olm-api\n    name: Operator Lifecycle Manager API\n    description: >-\n      OLM extends Kubernetes with CRDs for operator lifecycle management\n\
  \      including ClusterServiceVersion for describing operator capabilities\n      and requirements, Subscription for tracking update channels,\n      InstallPlan for managing operator installation, CatalogSource for\n      defining operator repositories, and OperatorGroup for multi-tenant\n      operator deployment scoping.\n    humanURL: https://olm.operatorframework.io/docs/\n    properties:\n      - type: Documentation\n        url: https://olm.operatorframework.io/docs/\n    tags:\n      - Installation\n      - Lifecycle Management\n      - Updates\n  - aid: operator-framework:operator-sdk\n    name: Operator SDK\n    description: >-\n      The Operator SDK provides tools for building Kubernetes operators.\n      It includes scaffolding commands, code generation for CRD types and\n      controllers, integration testing harness, scorecard for validating\n      operator quality, and bundle commands for packaging operators for\n      distribution through OLM catalogs.\n    humanURL:\
  \ https://sdk.operatorframework.io/docs/\n    properties:\n      - type: Documentation\n        url: https://sdk.operatorframework.io/docs/\n    tags:\n      - Code Generation\n      - Scaffolding\n      - SDK\ncommon:\n  - type: Documentation\n    name: Operator Framework Documentation\n    description: Official Operator Framework documentation.\n    url: https://operatorframework.io/\n  - type: GitHubOrg\n    name: Operator Framework GitHub\n    description: Source code repositories.\n    url: https://github.com/operator-framework\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/operator-framework/refs/heads/main/apis.yml
tags:
- Automation
- Cloud Native
- Incubating
- Kubernetes
- Lifecycle Management
- Operators
url: https://operatorframework.io
use_cases: []
---
