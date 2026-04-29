---
api_count: 1
api_specs:
- filename: crossplane-kubernetes-api-openapi.yml
  format: yaml
  label: Crossplane Kubernetes API
  slug: crossplane-kubernetes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/openapi/crossplane-kubernetes-api-openapi.yml
apis:
- description: 'The Crossplane Kubernetes API extends the Kubernetes API server with custom resources for managing cloud infrastructure declaratively. Resources are organized into two main API groups: apiextensions.c'
  name: Crossplane Kubernetes API
  slug: crossplane-kubernetes-api
capabilities: []
common:
- title: ''
  type: JSONSchema
  url: json-schema/crossplane-composition-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/crossplane-xrd-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/crossplane-provider-schema.json
- title: ''
  type: JSONLD
  url: json-ld/crossplane-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/crossplane-vocabulary.yml
- title: ''
  type: Website
  url: https://www.crossplane.io/
- title: ''
  type: Documentation
  url: https://docs.crossplane.io/latest/
- title: ''
  type: GettingStarted
  url: https://docs.crossplane.io/latest/get-started/get-started-with-composition/
- title: ''
  type: Reference
  url: https://docs.crossplane.io/latest/api/
- title: ''
  type: Blog
  url: https://blog.crossplane.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/crossplane
- title: ''
  type: GitHubRepository
  url: https://github.com/crossplane/crossplane
- title: ''
  type: ChangeLog
  url: https://github.com/crossplane/crossplane/releases
- title: ''
  type: Community
  url: https://docs.crossplane.io/latest/learn/
- title: ''
  type: Contributing
  url: https://docs.crossplane.io/contribute/contribute/
- title: ''
  type: License
  url: https://github.com/crossplane/crossplane/blob/main/LICENSE
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/crossplane/
created: '2025-01-01'
description: Crossplane is a graduated CNCF open-source Kubernetes add-on that transforms a cluster into a universal control plane for cloud infrastructure, services, and applications. Crossplane introduces custom resources including CompositeResourceDefinitions (XRDs), Compositions, Claims, Providers, ProviderConfigs, Configurations, Functions, and EnvironmentConfigs, allowing platform teams to author self-service platform APIs that compose managed resources across AWS, GCP, Azure, and other providers using Kubernetes-style declarative configuration.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Crossplane Context
  property_count: 17
  slug: crossplane-context
layout: provider
modified: '2026-04-28'
name: Crossplane
rules:
- name: Crossplane API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 2
  slug: crossplane-kubernetes-api-rules
skills: []
slug: crossplane
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: crossplane\nname: Crossplane\nx-type: opensource\ndescription: >-\n  Crossplane is a graduated CNCF open-source Kubernetes add-on that\n  transforms a cluster into a universal control plane for cloud\n  infrastructure, services, and applications. Crossplane introduces\n  custom resources including CompositeResourceDefinitions (XRDs),\n  Compositions, Claims, Providers, ProviderConfigs, Configurations,\n  Functions, and EnvironmentConfigs, allowing platform teams to author\n  self-service platform APIs that compose managed resources across AWS,\n  GCP, Azure, and other providers using Kubernetes-style declarative\n  configuration.\nurl: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache 2.0\n  - CNCF\n  - Cloud Native\n  - Composition\n  - Control Plane\n  - Custom Resource Definitions\n  - Graduated\n  - Infrastructure as Code\n  - Kubernetes\n\
  \  - Multi-Cloud\n  - Open Source\n  - Platform Engineering\n  - Providers\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Index\naccess: Public\nposition: Provider\napis:\n  - aid: crossplane:crossplane-kubernetes-api\n    name: Crossplane Kubernetes API\n    description: >-\n      The Crossplane Kubernetes API extends the Kubernetes API server with\n      custom resources for managing cloud infrastructure declaratively.\n      Resources are organized into two main API groups:\n      apiextensions.crossplane.io for composition primitives\n      (Compositions, CompositeResourceDefinitions, EnvironmentConfigs,\n      DeploymentRuntimeConfigs) and pkg.crossplane.io for package\n      management (Providers, Functions, Configurations and their\n      revisions). All operations use standard Kubernetes REST conventions\n      and are authenticated through the Kubernetes API server's\n      authentication mechanisms.\n    humanURL: https://docs.crossplane.io/latest/api/\n\
  \    baseURL: https://kubernetes.default.svc\n    properties:\n      - type: Documentation\n        url: https://docs.crossplane.io/latest/\n      - type: Reference\n        url: https://docs.crossplane.io/latest/api/\n      - type: GettingStarted\n        url: https://docs.crossplane.io/latest/get-started/get-started-with-composition/\n      - type: OpenAPI\n        url: openapi/crossplane-kubernetes-api-openapi.yml\n      - type: Rules\n        url: rules/crossplane-kubernetes-api-rules.yml\n      - type: Capabilities\n        url: capabilities/crossplane-kubernetes-api-capabilities.yml\n      - type: JSONSchema\n        url: json-schema/crossplane-composition-schema.json\n      - type: JSONSchema\n        url: json-schema/crossplane-xrd-schema.json\n      - type: JSONSchema\n        url: json-schema/crossplane-provider-schema.json\n      - type: JSONLD\n        url: json-ld/crossplane-context.jsonld\n      - type: ChangeLog\n        url: https://github.com/crossplane/crossplane/releases\n\
  \    tags:\n      - Composition\n      - Control Plane\n      - Custom Resources\n      - Infrastructure as Code\n      - Kubernetes\n      - Multi-Cloud\n      - Platform Engineering\ncommon:\n  - type: JSONSchema\n    url: json-schema/crossplane-composition-schema.json\n  - type: JSONSchema\n    url: json-schema/crossplane-xrd-schema.json\n  - type: JSONSchema\n    url: json-schema/crossplane-provider-schema.json\n  - type: JSONLD\n    url: json-ld/crossplane-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/crossplane-vocabulary.yml\n  - type: Website\n    url: https://www.crossplane.io/\n  - type: Documentation\n    url: https://docs.crossplane.io/latest/\n  - type: GettingStarted\n    url: https://docs.crossplane.io/latest/get-started/get-started-with-composition/\n  - type: Reference\n    url: https://docs.crossplane.io/latest/api/\n  - type: Blog\n    url: https://blog.crossplane.io/\n  - type: GitHubOrganization\n    url: https://github.com/crossplane\n  - type: GitHubRepository\n\
  \    url: https://github.com/crossplane/crossplane\n  - type: ChangeLog\n    url: https://github.com/crossplane/crossplane/releases\n  - type: Community\n    url: https://docs.crossplane.io/latest/learn/\n  - type: Contributing\n    url: https://docs.crossplane.io/contribute/contribute/\n  - type: License\n    url: https://github.com/crossplane/crossplane/blob/main/LICENSE\n  - type: CNCF\n    url: https://www.cncf.io/projects/crossplane/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/apis.yml
tags:
- Apache 2.0
- CNCF
- Cloud Native
- Composition
- Control Plane
- Custom Resource Definitions
- Graduated
- Infrastructure as Code
- Kubernetes
- Multi-Cloud
- Open Source
- Platform Engineering
- Providers
url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/apis.yml
use_cases: []
---
