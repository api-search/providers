---
api_count: 1
api_specs:
- filename: uptrace-openapi.yml
  format: yaml
  label: Uptrace API
  slug: uptrace
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/openapi/uptrace-openapi.yml
apis:
- description: The Uptrace REST API provides programmatic management of projects, chart annotations for deployment tracking, alert rules using PromQL, dashboard management, and Prometheus Remote Write for metrics in
  name: Uptrace API
  slug: uptrace
capabilities:
- description: Workflow capability for Uptrace APM observability and monitoring workflows, combining annotations for deployment tracking, alert rule management, dashboard operations, and project management. Designed
  name: Uptrace Observability and Monitoring
  slug: observability-and-monitoring
common:
- title: ''
  type: Website
  url: https://uptrace.dev
- title: ''
  type: Documentation
  url: https://uptrace.dev/get/get-started.html
- title: ''
  type: GitHub Organization
  url: https://github.com/uptrace/uptrace
- title: ''
  type: Docker Hub
  url: https://hub.docker.com/r/uptrace/uptrace
created: '2026-03-25'
description: Uptrace is an open source APM and distributed tracing platform powered by OpenTelemetry for monitoring application traces, metrics, and logs. The Uptrace API provides programmatic access to annotations, Prometheus metrics ingestion, PromQL querying, alert rules, project management, and dashboards.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Uptrace Context
  property_count: 19
  slug: uptrace-context
layout: provider
modified: '2026-05-03'
name: Uptrace
rules:
- name: Uptrace API Rules
  rule_count: 7
  severity_counts:
    error: 0
    hint: 0
    info: 3
    warn: 4
  slug: uptrace-rules
skills: []
slug: uptrace
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uptrace\nname: Uptrace\ndescription: >-\n  Uptrace is an open source APM and distributed tracing platform powered by\n  OpenTelemetry for monitoring application traces, metrics, and logs. The\n  Uptrace API provides programmatic access to annotations, Prometheus metrics\n  ingestion, PromQL querying, alert rules, project management, and dashboards.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - APM\n  - Observability\n  - OpenTelemetry\n  - Distributed Tracing\n  - Monitoring\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: uptrace:uptrace\n    name: Uptrace API\n    description: >-\n      The Uptrace REST API provides programmatic management of projects,\n      chart annotations for deployment tracking, alert rules using PromQL,\n      dashboard management, and Prometheus\
  \ Remote Write for metrics ingestion.\n      Uptrace accepts OpenTelemetry data via OTLP/gRPC and OTLP/HTTP.\n    humanURL: https://uptrace.dev\n    baseURL: https://api.uptrace.dev\n    tags:\n      - APM\n      - Observability\n      - OpenTelemetry\n      - Distributed Tracing\n      - Alerting\n    properties:\n      - type: Documentation\n        url: https://uptrace.dev/get/get-started.html\n      - type: GitHub Repository\n        url: https://github.com/uptrace/uptrace\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/openapi/uptrace-openapi.yml\ncommon:\n  - type: Website\n    url: https://uptrace.dev\n  - type: Documentation\n    url: https://uptrace.dev/get/get-started.html\n  - type: GitHub Organization\n    url: https://github.com/uptrace/uptrace\n  - type: Docker Hub\n    url: https://hub.docker.com/r/uptrace/uptrace\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/apis.yml
tags:
- APM
- Observability
- OpenTelemetry
- Distributed Tracing
- Monitoring
url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/apis.yml
use_cases: []
---
