---
api_count: 1
api_specs:
- filename: timoni-openapi.yml
  format: yaml
  label: Timoni Module Registry API
  slug: timoni
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml
apis:
- description: Timoni modules are distributed as OCI artifacts in container registries. The registry API provides operations for listing module tags, retrieving OCI manifests, and downloading module blobs containing
  name: Timoni Module Registry API
  slug: timoni
common:
- title: ''
  type: Website
  url: https://timoni.sh/
- title: ''
  type: Documentation
  url: https://timoni.sh/
- title: ''
  type: GitHub Organization
  url: https://github.com/stefanprodan/timoni
- title: ''
  type: Getting Started
  url: https://timoni.sh/quickstart/
- title: ''
  type: Concepts
  url: https://timoni.sh/concepts/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-schema/timoni-module-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/vocabulary/timoni-vocabulary.yml
created: '2026-03-26'
description: Timoni is a package manager for Kubernetes powered by CUE that provides a type-safe alternative to Helm charts. It enables software vendors to define complex application deployments packaged as Modules using CUE definitions, distributed as OCI artifacts in container registries with semantic versioning and cryptographic signing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 33
  name: Timoni Context
  property_count: 1
  slug: timoni-context
layout: provider
modified: '2026-05-03'
name: Timoni
skills: []
slug: timoni
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: timoni\nname: Timoni\ndescription: >-\n  Timoni is a package manager for Kubernetes powered by CUE that provides a type-safe\n  alternative to Helm charts. It enables software vendors to define complex application\n  deployments packaged as Modules using CUE definitions, distributed as OCI artifacts\n  in container registries with semantic versioning and cryptographic signing.\ntype: Index\nposition: Consumer\naccess: Open Source\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Containers\n  - Kubernetes\n  - Package Manager\n  - CUE\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: timoni:timoni\n    name: Timoni Module Registry API\n    description: >-\n      Timoni modules are distributed as OCI artifacts in container registries.\n      The registry API provides operations for listing module tags,\
  \ retrieving\n      OCI manifests, and downloading module blobs containing CUE definitions\n      and Kubernetes configurations.\n    humanURL: https://timoni.sh/\n    baseURL: https://ghcr.io\n    tags:\n      - Containers\n      - Kubernetes\n      - Package Manager\n      - OCI Registry\n    properties:\n      - type: Documentation\n        url: https://timoni.sh/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml\n      - type: GitHub Repository\n        url: https://github.com/stefanprodan/timoni\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-schema/timoni-module-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-structure/timoni-module-structure.json\n      - type: JSONLDContext\n        url: >-\n         \
  \ https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld\nfeatures:\n  - Type-safe Kubernetes configuration via CUE\n  - OCI artifact distribution and signing\n  - Semantic versioning for modules\n  - Bundle-based multi-instance management\n  - Kubernetes CRD lifecycle management\n  - Drift detection and correction\n  - Bundle Runtime API for dynamic configuration\n  - Cryptographic signing and verification\nuseCases:\n  - Kubernetes application packaging and distribution\n  - Type-safe alternative to Helm charts\n  - Multi-service deployment orchestration\n  - GitOps-compatible application delivery\n  - Kubernetes module versioning and rollback\nintegrations:\n  - GitHub Container Registry (ghcr.io)\n  - Docker Hub\n  - Any OCI-compatible container registry\n  - Kubernetes clusters\n  - Flux CD\nsolutions:\n  - Cloud-native application delivery\n  - Kubernetes package management\n  - Infrastructure as code\n  - CUE-based configuration management\n\
  common:\n  - type: Website\n    url: https://timoni.sh/\n  - type: Documentation\n    url: https://timoni.sh/\n  - type: GitHub Organization\n    url: https://github.com/stefanprodan/timoni\n  - type: Getting Started\n    url: https://timoni.sh/quickstart/\n  - type: Concepts\n    url: https://timoni.sh/concepts/\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-schema/timoni-module-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/vocabulary/timoni-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/apis.yml
tags:
- Containers
- Kubernetes
- Package Manager
- CUE
url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/apis.yml
use_cases: []
---
