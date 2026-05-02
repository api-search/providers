---
api_count: 8
api_specs:
- filename: helm-chart-repository-openapi.yml
  format: yaml
  label: Helm Chart Repository API
  slug: chart-repository-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/helm/refs/heads/main/openapi/helm-chart-repository-openapi.yml
apis:
- description: The Helm Chart Repository API defines the HTTP endpoints used by Helm clients to discover and download charts from a repository server. This includes the index.yaml endpoint for chart discovery and ch
  name: Helm Chart Repository API
  slug: chart-repository-api
- description: JSON Schema defining the structure and validation rules for Chart.yaml, the metadata file required in every Helm chart. Describes chart name, version, dependencies, maintainers, and other metadata fie
  name: Helm Chart.yaml Schema
  slug: chart-yaml-schema
- description: JSON Schema describing common conventional patterns for values.yaml files in Helm charts. Values.yaml provides default configuration values including container image settings, service configuration, i
  name: Helm Values YAML Schema
  slug: values-yaml-schema
- description: JSON Schema for the index.yaml file served by Helm chart repositories. The index is the primary discovery mechanism listing all available charts and versions with download URLs and integrity digests.
  name: Helm Repository Index Schema
  slug: repository-index-schema
- description: JSON-LD context document mapping Helm concepts to linked data vocabularies including Schema.org, Dublin Core, SPDX, FOAF, and W3C PROV. Enables semantic interoperability of Helm chart metadata.
  name: Helm JSON-LD Context
  slug: json-ld-context
- description: The Helm Go SDK provides Go packages for programmatically performing Helm actions such as install, upgrade, list, and rollback without using the CLI. The SDK is published as helm.sh/helm/v3 and provid
  name: Helm Go SDK
  slug: go-sdk
- description: The Helm Plugins API defines the interface for extending the Helm CLI with additional subcommands. Plugins live in a single directory with a plugin.yaml descriptor and can be implemented as shell scri
  name: Helm Plugins
  slug: plugins
- description: The Helm Chart Template API defines the Go template language extensions, built-in objects, and Sprig function library available for authoring Helm chart templates. Templates render Kubernetes manifest
  name: Helm Chart Template API
  slug: chart-template-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/helm-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/helm-plugin-schema.json
- title: ''
  type: Website
  url: https://helm.sh/
- title: ''
  type: Documentation
  url: https://helm.sh/docs/
- title: ''
  type: Getting Started
  url: https://helm.sh/docs/intro/quickstart/
- title: ''
  type: GitHub Organization
  url: https://github.com/helm
- title: ''
  type: GitHubRepository
  url: https://github.com/helm/helm
- title: ''
  type: Blog
  url: https://helm.sh/blog/
- title: ''
  type: Change Log
  url: https://helm.sh/docs/changelog/
- title: ''
  type: Community
  url: https://helm.sh/community/
- title: ''
  type: Slack
  url: https://kubernetes.slack.com/messages/helm-users
- title: ''
  type: Security
  url: https://helm.sh/community/SECURITY
- title: ''
  type: ArtifactHub
  url: https://artifacthub.io/
created: '2025'
description: Package manager for Kubernetes that helps you define, install, and upgrade complex Kubernetes applications using charts. Helm uses a packaging format called charts, which are collections of files that describe a related set of Kubernetes resources. A chart repository is an HTTP server that houses an index.yaml file and packaged chart archives.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Helm Context
  property_count: 11
  slug: helm-context
layout: provider
modified: '2026-04-28'
name: Helm
skills: []
slug: helm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: helm\nname: Helm\ndescription: >-\n  Package manager for Kubernetes that helps you define, install, and upgrade\n  complex Kubernetes applications using charts. Helm uses a packaging format\n  called charts, which are collections of files that describe a related set\n  of Kubernetes resources. A chart repository is an HTTP server that houses\n  an index.yaml file and packaged chart archives.\nurl: https://helm.sh\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Charts\n  - Cloud Native\n  - Container Orchestration\n  - DevOps\n  - Kubernetes\n  - Package Manager\ncreated: '2025'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: helm:chart-repository-api\n    name: Helm Chart Repository API\n    description: >-\n      The Helm Chart Repository API defines the HTTP endpoints used by Helm\n      clients to discover and download charts from a repository server. This\n      includes the index.yaml\
  \ endpoint for chart discovery and chart package\n      download endpoints. ChartMuseum extends this with a JSON-based management\n      API for listing, uploading, and deleting charts.\n    humanURL: https://helm.sh/docs/topics/chart_repository/\n    properties:\n      - type: OpenAPI\n        url: openapi/helm-chart-repository-openapi.yml\n      - type: Documentation\n        url: https://helm.sh/docs/topics/chart_repository/\n      - type: JSONSchema\n        url: json-schema/helm-repository-index-schema.json\n    tags:\n      - Charts\n      - Package Registry\n      - Repository\n  - aid: helm:chart-yaml-schema\n    name: Helm Chart.yaml Schema\n    description: >-\n      JSON Schema defining the structure and validation rules for Chart.yaml,\n      the metadata file required in every Helm chart. Describes chart name,\n      version, dependencies, maintainers, and other metadata fields.\n    humanURL: https://helm.sh/docs/topics/charts/#the-chartyaml-file\n    properties:\n      -\
  \ type: JSONSchema\n        url: json-schema/helm-chart-yaml-schema.json\n      - type: Documentation\n        url: https://helm.sh/docs/topics/charts/#the-chartyaml-file\n    tags:\n      - Chart Metadata\n      - Schema\n      - Validation\n  - aid: helm:values-yaml-schema\n    name: Helm Values YAML Schema\n    description: >-\n      JSON Schema describing common conventional patterns for values.yaml\n      files in Helm charts. Values.yaml provides default configuration values\n      including container image settings, service configuration, ingress rules,\n      resource limits, and scheduling constraints.\n    humanURL: https://helm.sh/docs/chart_template_guide/values_files/\n    properties:\n      - type: JSONSchema\n        url: json-schema/helm-values-yaml-schema.json\n      - type: Documentation\n        url: https://helm.sh/docs/chart_template_guide/values_files/\n    tags:\n      - Configuration\n      - Schema\n      - Values\n  - aid: helm:repository-index-schema\n    name:\
  \ Helm Repository Index Schema\n    description: >-\n      JSON Schema for the index.yaml file served by Helm chart repositories.\n      The index is the primary discovery mechanism listing all available charts\n      and versions with download URLs and integrity digests.\n    humanURL: https://helm.sh/docs/topics/chart_repository/#the-index-file\n    properties:\n      - type: JSONSchema\n        url: json-schema/helm-repository-index-schema.json\n      - type: Documentation\n        url: https://helm.sh/docs/topics/chart_repository/#the-index-file\n    tags:\n      - Discovery\n      - Repository Index\n      - Schema\n  - aid: helm:json-ld-context\n    name: Helm JSON-LD Context\n    description: >-\n      JSON-LD context document mapping Helm concepts to linked data\n      vocabularies including Schema.org, Dublin Core, SPDX, FOAF, and\n      W3C PROV. Enables semantic interoperability of Helm chart metadata.\n    humanURL: https://helm.sh/docs/\n    properties:\n      - type: JSON-LD\n\
  \        url: json-ld/helm-context.jsonld\n    tags:\n      - JSON-LD\n      - Linked Data\n      - Semantics\n  - aid: helm:go-sdk\n    name: Helm Go SDK\n    description: >-\n      The Helm Go SDK provides Go packages for programmatically performing Helm\n      actions such as install, upgrade, list, and rollback without using the\n      CLI. The SDK is published as helm.sh/helm/v3 and provides a stable API\n      surface for tooling that embeds Helm functionality.\n    humanURL: https://helm.sh/docs/v3/sdk/gosdk/\n    tags:\n      - Go\n      - Kubernetes\n      - Package Manager\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://helm.sh/docs/v3/sdk/gosdk/\n      - type: Reference\n        url: https://pkg.go.dev/helm.sh/helm/v3\n      - type: GitHubRepository\n        url: https://github.com/helm/helm\n  - aid: helm:plugins\n    name: Helm Plugins\n    description: >-\n      The Helm Plugins API defines the interface for extending the Helm CLI\n      with\
  \ additional subcommands. Plugins live in a single directory with a\n      plugin.yaml descriptor and can be implemented as shell scripts, binaries,\n      or WebAssembly modules introduced in Helm 4.\n    humanURL: https://helm.sh/docs/topics/plugins/\n    tags:\n      - CLI\n      - Extensions\n      - Kubernetes\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://helm.sh/docs/topics/plugins/\n      - type: Reference\n        url: https://helm.sh/docs/plugins/developer/\n      - type: JSONSchema\n        url: json-schema/helm-plugin-schema.json\n  - aid: helm:chart-template-api\n    name: Helm Chart Template API\n    description: >-\n      The Helm Chart Template API defines the Go template language extensions,\n      built-in objects, and Sprig function library available for authoring\n      Helm chart templates. Templates render Kubernetes manifests from\n      parameterized values and support flow control, named templates, and\n      over 60 template\
  \ functions.\n    humanURL: https://helm.sh/docs/chart_template_guide/\n    tags:\n      - Charts\n      - Go Templates\n      - Kubernetes\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://helm.sh/docs/chart_template_guide/\n      - type: Reference\n        url: https://helm.sh/docs/chart_template_guide/function_list/\ncommon:\n  - type: JSON-LD\n    url: json-ld/helm-context.jsonld\n  - type: JSONSchema\n    url: json-schema/helm-plugin-schema.json\n  - type: Website\n    name: Helm Website\n    description: Official Helm website.\n    url: https://helm.sh/\n  - type: Documentation\n    name: Helm Documentation\n    description: Official Helm documentation covering installation, chart development, and best practices.\n    url: https://helm.sh/docs/\n  - type: Getting Started\n    name: Helm Quickstart Guide\n    description: Step-by-step guide to installing Helm and deploying your first chart.\n    url: https://helm.sh/docs/intro/quickstart/\n  -\
  \ type: GitHub Organization\n    name: Helm GitHub Organization\n    description: Source code repositories for Helm and related projects.\n    url: https://github.com/helm\n  - type: GitHubRepository\n    name: Helm GitHub Repository\n    description: Main Helm source code repository.\n    url: https://github.com/helm/helm\n  - type: Blog\n    name: Helm Blog\n    description: Official blog with announcements, releases, and community updates.\n    url: https://helm.sh/blog/\n  - type: Change Log\n    name: Helm Changelog\n    description: Full changelog and release history for Helm.\n    url: https://helm.sh/docs/changelog/\n  - type: Community\n    name: Helm Community\n    description: Community resources including developer calls and contribution guides.\n    url: https://helm.sh/community/\n  - type: Slack\n    name: Helm Slack\n    description: Kubernetes Slack workspace with Helm channels for community support.\n    url: https://kubernetes.slack.com/messages/helm-users\n  - type:\
  \ Security\n    name: Helm Security Policy\n    description: Security process and policy for reporting vulnerabilities in Helm.\n    url: https://helm.sh/community/SECURITY\n  - type: ArtifactHub\n    name: Artifact Hub\n    description: Public chart repository search engine for discovering Helm charts.\n    url: https://artifacthub.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/helm/refs/heads/main/apis.yml
tags:
- Charts
- Cloud Native
- Container Orchestration
- DevOps
- Kubernetes
- Package Manager
url: https://helm.sh
use_cases: []
---
