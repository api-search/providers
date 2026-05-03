---
api_count: 3
api_specs:
- filename: pixie-openapi.yml
  format: yaml
  label: Pixie API
  slug: pixie
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/openapi/pixie-openapi.yml
apis:
- description: Kubernetes observability platform using eBPF for automatic telemetry collection without manual instrumentation.
  name: Pixie API
  slug: pixie
- description: Python-dialect domain-specific language and API for querying and analyzing telemetry data collected by Pixie within a Kubernetes cluster. PxL scripts allow developers to filter, aggregate, and visuali
  name: Pixie PxL Script API
  slug: pixie-pxl-api
- description: Plugin API that allows configuring PxL scripts to export observability data from Pixie at regularly scheduled intervals to external systems. Supports integrations including a Grafana datasource plugin
  name: Pixie Plugin System API
  slug: pixie-plugin-api
common:
- title: ''
  type: Website
  url: https://px.dev/
- title: ''
  type: JSON-LD
  url: json-ld/pixie-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/pixie-pxl-script-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/pixie-plugin-schema.json
- title: ''
  type: Documentation
  url: https://docs.px.dev/
- title: ''
  type: Getting Started
  url: https://docs.px.dev/installing-pixie/
- title: ''
  type: GitHub Organization
  url: https://github.com/pixie-io
- title: ''
  type: GitHubRepository
  url: https://github.com/pixie-io/pixie
- title: ''
  type: Blog
  url: https://blog.px.dev/
- title: ''
  type: Community
  url: https://px.dev/community/
- title: ''
  type: Slack
  url: https://slackin.px.dev/
created: '2026-03-16'
description: Pixie is a Kubernetes observability platform that uses eBPF to automatically collect telemetry data including full-body application requests, resource and network metrics, and application profiles without manual instrumentation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Pixie Context
  property_count: 7
  slug: pixie-context
layout: provider
modified: '2026-03-18'
name: Pixie
skills: []
slug: pixie
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pixie\nname: Pixie\ndescription: >-\n  Pixie is a Kubernetes observability platform that uses eBPF to automatically\n  collect telemetry data including full-body application requests, resource and\n  network metrics, and application profiles without manual instrumentation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - eBPF\n  - Kubernetes\n  - Monitoring\n  - Observability\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: pixie:pixie\n    name: Pixie API\n    description: >-\n      Kubernetes observability platform using eBPF for automatic telemetry\n      collection without manual instrumentation.\n    humanURL: https://docs.px.dev/\n    tags:\n      - Kubernetes\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://docs.px.dev/\n      -\
  \ type: Getting Started\n        url: https://docs.px.dev/installing-pixie/\n      - type: Reference\n        url: https://docs.px.dev/reference/api/overview/\n      - type: Client Libraries\n        url: https://docs.px.dev/reference/api/\n      - type: OpenAPI\n        url: openapi/pixie-openapi.yml\n  - aid: pixie:pixie-pxl-api\n    name: Pixie PxL Script API\n    description: >-\n      Python-dialect domain-specific language and API for querying and analyzing\n      telemetry data collected by Pixie within a Kubernetes cluster. PxL scripts\n      allow developers to filter, aggregate, and visualize metrics, traces, and\n      full-body request data collected via eBPF.\n    humanURL: https://docs.px.dev/reference/pxl/\n    tags:\n      - eBPF\n      - Kubernetes\n      - Metrics\n      - Observability\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.px.dev/reference/pxl/\n      - type: Reference\n        url: https://docs.px.dev/reference/pxl/\n\
  \      - type: JSONSchema\n        url: json-schema/pixie-pxl-script-schema.json\n  - aid: pixie:pixie-plugin-api\n    name: Pixie Plugin System API\n    description: >-\n      Plugin API that allows configuring PxL scripts to export observability data\n      from Pixie at regularly scheduled intervals to external systems. Supports\n      integrations including a Grafana datasource plugin for visualizing Pixie\n      data in Grafana dashboards.\n    humanURL: https://docs.px.dev/reference/plugins/plugin-system/\n    tags:\n      - Grafana\n      - Integrations\n      - Kubernetes\n      - Observability\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://docs.px.dev/reference/plugins/plugin-system/\n      - type: Reference\n        url: https://docs.px.dev/reference/plugins/grafana/\n      - type: JSONSchema\n        url: json-schema/pixie-plugin-schema.json\ncommon:\n  - type: Website\n    url: https://px.dev/\n  - type: JSON-LD\n    url: json-ld/pixie-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/pixie-pxl-script-schema.json\n  - type: JSONSchema\n    url: json-schema/pixie-plugin-schema.json\n  - type: Documentation\n    url: https://docs.px.dev/\n  - type: Getting Started\n    url: https://docs.px.dev/installing-pixie/\n  - type: GitHub Organization\n    url: https://github.com/pixie-io\n  - type: GitHubRepository\n    url: https://github.com/pixie-io/pixie\n  - type: Blog\n    url: https://blog.px.dev/\n  - type: Community\n    url: https://px.dev/community/\n  - type: Slack\n    url: https://slackin.px.dev/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/apis.yml
tags:
- eBPF
- Kubernetes
- Monitoring
- Observability
url: https://raw.githubusercontent.com/api-evangelist/pixie/refs/heads/main/apis.yml
use_cases: []
---
