---
api_count: 1
api_specs:
- filename: signoz-openapi.yml
  format: yaml
  label: SigNoz
  slug: signoz
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/openapi/signoz-openapi.yml
apis:
- description: The SigNoz REST API provides programmatic access to the SigNoz observability platform. The API enables management of alerts, dashboards, notification channels, cloud integrations, users, organizations
  name: SigNoz
  slug: signoz
capabilities:
- description: Unified observability monitoring capability combining SigNoz's alerts, dashboards, metrics, traces, logs, and infrastructure monitoring APIs into a single workflow. Designed for DevOps engineers, SREs
  name: SigNoz Observability Monitoring
  slug: observability-monitoring
common:
- title: ''
  type: Website
  url: https://signoz.io
- title: ''
  type: Documentation
  url: https://signoz.io/docs/
- title: ''
  type: API Reference
  url: https://signoz.io/api-reference/
- title: ''
  type: GitHub Organization
  url: https://github.com/SigNoz
- title: ''
  type: Blog
  url: https://signoz.io/blog/
- title: ''
  type: Pricing
  url: https://signoz.io/pricing/
- title: ''
  type: Support
  url: https://signoz.io/support/
- title: ''
  type: Community
  url: https://signoz.io/slack/
- title: ''
  type: Enterprise
  url: https://signoz.io/enterprise/
- title: ''
  type: Changelog
  url: https://signoz.io/changelog/
- title: ''
  type: Status
  url: https://status.signoz.io/
created: '2026-03-25'
description: SigNoz is an open source observability platform with logs, traces, and metrics in a single pane, built natively on OpenTelemetry. It is a full-stack open-source APM and observability tool that serves as an open-source alternative to DataDog, NewRelic, and other proprietary monitoring solutions. SigNoz provides distributed tracing, log management, infrastructure monitoring, and alerting capabilities unified under a single interface.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Signoz Context
  property_count: 3
  slug: signoz-context
layout: provider
modified: '2026-05-02'
name: SigNoz
rules:
- name: SigNoz API Rules
  rule_count: 8
  severity_counts:
    error: 0
    hint: 0
    info: 2
    warn: 6
  slug: signoz-rules
skills: []
slug: signoz
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: signoz\nname: SigNoz\ndescription: >-\n  SigNoz is an open source observability platform with logs, traces, and metrics\n  in a single pane, built natively on OpenTelemetry. It is a full-stack\n  open-source APM and observability tool that serves as an open-source alternative\n  to DataDog, NewRelic, and other proprietary monitoring solutions. SigNoz provides\n  distributed tracing, log management, infrastructure monitoring, and alerting\n  capabilities unified under a single interface.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - APM\n  - Alerting\n  - Cloud Monitoring\n  - Dashboards\n  - Distributed Tracing\n  - Infrastructure Monitoring\n  - Logs\n  - Metrics\n  - Observability\n  - OpenTelemetry\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: signoz:signoz\n\
  \    name: SigNoz\n    description: >-\n      The SigNoz REST API provides programmatic access to the SigNoz observability\n      platform. The API enables management of alerts, dashboards, notification channels,\n      cloud integrations, users, organizations, service accounts, and ingestion keys.\n      It also exposes query endpoints for traces, logs, metrics, and infrastructure\n      monitoring data. The API uses API key authentication via the SigNoz-Api-Key header.\n    humanURL: https://signoz.io\n    baseURL: https://{host}:{port}\n    tags:\n      - APM\n      - Alerting\n      - Dashboards\n      - Distributed Tracing\n      - Logs\n      - Metrics\n      - Observability\n      - OpenTelemetry\n    properties:\n      - type: Documentation\n        url: https://signoz.io/docs/\n      - type: API Reference\n        url: https://signoz.io/api-reference/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/openapi/signoz-openapi.yml\n\
  \      - type: GitHub Repository\n        url: https://github.com/SigNoz/signoz\n      - type: Pricing\n        url: https://signoz.io/pricing/\n      - type: Getting Started\n        url: https://signoz.io/docs/introduction/\n      - type: Changelog\n        url: https://signoz.io/changelog/\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/rules/signoz-rules.yml\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/vocabulary/signoz-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://signoz.io\n  - type: Documentation\n    url: https://signoz.io/docs/\n  - type: API Reference\n    url: https://signoz.io/api-reference/\n  - type: GitHub Organization\n    url: https://github.com/SigNoz\n  - type: Blog\n    url: https://signoz.io/blog/\n  - type: Pricing\n    url: https://signoz.io/pricing/\n  - type: Support\n    url: https://signoz.io/support/\n  - type: Community\n\
  \    url: https://signoz.io/slack/\n  - type: Enterprise\n    url: https://signoz.io/enterprise/\n  - type: Changelog\n    url: https://signoz.io/changelog/\n  - type: Status\n    url: https://status.signoz.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/apis.yml
tags:
- APM
- Alerting
- Cloud Monitoring
- Dashboards
- Distributed Tracing
- Infrastructure Monitoring
- Logs
- Metrics
- Observability
- OpenTelemetry
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/apis.yml
use_cases: []
---
