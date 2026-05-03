---
api_count: 3
api_specs:
- filename: porter-bundle-openapi.yml
  format: yaml
  label: Porter Bundle API
  slug: porter-bundle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/openapi/porter-bundle-openapi.yml
apis:
- description: 'Core API for authoring, building, distributing, and installing Cloud Native Application Bundles (CNAB) using Porter. Bundles package application artifacts, client tools, configuration, and deployment '
  name: Porter Bundle API
  slug: porter-bundle-api
- description: Extension interface for building and using mixins, which are the building blocks for authoring Porter bundles. Mixins provide pre-built integrations for interacting with tools and services such as Kub
  name: Porter Mixins API
  slug: porter-mixins-api
- description: Plugin interface that allows extending Porter's core functionality, such as storing installation data, credential sets, and parameter sets in external systems like cloud storage instead of the local f
  name: Porter Plugins API
  slug: porter-plugins-api
common:
- title: ''
  type: Website
  url: https://porter.sh/
- title: ''
  type: JSON-LD
  url: json-ld/porter-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/porter-manifest-schema.json
- title: ''
  type: Documentation
  url: https://porter.sh/docs/
- title: ''
  type: Getting Started
  url: https://porter.sh/docs/learn/
- title: ''
  type: GitHub Organization
  url: https://github.com/getporter
- title: ''
  type: GitHubRepository
  url: https://github.com/getporter/porter
- title: ''
  type: Community
  url: https://porter.sh/community/
created: '2025'
description: A package manager for Kubernetes that uses Cloud Native Application Bundles (CNAB) to package and deploy applications along with their dependencies and configuration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Porter Context
  property_count: 9
  slug: porter-context
layout: provider
modified: '2026-04-28'
name: Porter
skills: []
slug: porter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: porter\nname: Porter\ndescription: A package manager for Kubernetes that uses Cloud Native Application Bundles (CNAB) to package and deploy applications along with their dependencies and configuration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - CNAB\n  - DevOps\n  - Kubernetes\n  - Package Manager\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/apis.yml\ncreated: '2025'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: porter:porter-bundle-api\n    name: Porter Bundle API\n    description: >-\n      Core API for authoring, building, distributing, and installing Cloud Native\n      Application Bundles (CNAB) using Porter. Bundles package application artifacts,\n      client tools, configuration, and deployment logic into a single distributable\n      installer that can be run with a single command.\n    humanURL: https://porter.sh/docs/\n\
  \    baseURL: https://porter.sh\n    tags:\n      - Cloud Native\n      - CNAB\n      - DevOps\n      - Kubernetes\n      - Package Manager\n    properties:\n      - type: Documentation\n        url: https://porter.sh/docs/\n      - type: Getting Started\n        url: https://porter.sh/docs/learn/\n      - type: OpenAPI\n        url: openapi/porter-bundle-openapi.yml\n      - type: JSONSchema\n        url: json-schema/porter-manifest-schema.json\n  - aid: porter:porter-mixins-api\n    name: Porter Mixins API\n    description: >-\n      Extension interface for building and using mixins, which are the building\n      blocks for authoring Porter bundles. Mixins provide pre-built integrations\n      for interacting with tools and services such as Kubernetes, Helm, Terraform,\n      and Docker Compose from within a bundle action.\n    humanURL: https://porter.sh/mixins/\n    baseURL: https://porter.sh\n    tags:\n      - CNAB\n      - DevOps\n      - Extensions\n      - Mixins\n      - Plugins\n\
  \    properties:\n      - type: Documentation\n        url: https://porter.sh/mixins/\n      - type: Reference\n        url: https://porter.sh/docs/development/dev-a-mixin/\n  - aid: porter:porter-plugins-api\n    name: Porter Plugins API\n    description: >-\n      Plugin interface that allows extending Porter's core functionality, such as\n      storing installation data, credential sets, and parameter sets in external\n      systems like cloud storage instead of the local filesystem. Plugins reimplement\n      Porter's default behavior to integrate with enterprise or cloud infrastructure.\n    humanURL: https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/\n    baseURL: https://porter.sh\n    tags:\n      - Cloud Native\n      - CNAB\n      - DevOps\n      - Extensions\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/\ncommon:\n  - type: Website\n    url:\
  \ https://porter.sh/\n  - type: JSON-LD\n    url: json-ld/porter-context.jsonld\n  - type: JSONSchema\n    url: json-schema/porter-manifest-schema.json\n  - type: Documentation\n    url: https://porter.sh/docs/\n  - type: Getting Started\n    url: https://porter.sh/docs/learn/\n  - type: GitHub Organization\n    url: https://github.com/getporter\n  - type: GitHubRepository\n    url: https://github.com/getporter/porter\n  - type: Community\n    url: https://porter.sh/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/apis.yml
tags:
- Cloud Native
- CNAB
- DevOps
- Kubernetes
- Package Manager
url: https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/apis.yml
use_cases: []
---
