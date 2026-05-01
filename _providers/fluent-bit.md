---
api_count: 1
api_specs:
- filename: fluent-bit-monitoring-openapi.yml
  format: yaml
  label: Fluent Bit Monitoring HTTP API
  slug: fluent-bit-monitoring-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/openapi/fluent-bit-monitoring-openapi.yml
apis:
- description: Fluent Bit's embedded HTTP server (default port 2020) exposes endpoints for build information, uptime, internal plugin metrics in JSON, Prometheus, and cmetrics formats, storage layer statistics, heal
  name: Fluent Bit Monitoring HTTP API
  slug: fluent-bit-monitoring-http-api
common:
- title: ''
  type: Website
  url: https://fluentbit.io
- title: ''
  type: Documentation
  url: https://docs.fluentbit.io
- title: ''
  type: GitHub Repository
  url: https://github.com/fluent/fluent-bit
- title: ''
  type: Slack
  url: https://launchpass.com/fluent-all
- title: ''
  type: Community
  url: https://fluentbit.io/community/
created: '2026-03-25'
description: Fluent Bit is an open source lightweight log processor and forwarder for collecting, parsing, and routing logs and metrics at scale. It exposes an embedded HTTP monitoring server with v1 and v2 endpoints for build info, uptime, internal metrics (JSON, Prometheus, cmetrics), storage stats, health checks, and hot reload.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Fluent Bit
skills: []
slug: fluent-bit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fluent-bit\nname: Fluent Bit\ndescription: >-\n  Fluent Bit is an open source lightweight log processor and forwarder for\n  collecting, parsing, and routing logs and metrics at scale. It exposes an\n  embedded HTTP monitoring server with v1 and v2 endpoints for build info,\n  uptime, internal metrics (JSON, Prometheus, cmetrics), storage stats,\n  health checks, and hot reload.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Logging\n  - Observability\n  - Metrics\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: fluent-bit:fluent-bit-monitoring-http-api\n    name: Fluent Bit Monitoring HTTP API\n    description: >-\n      Fluent Bit's embedded HTTP server (default port 2020) exposes endpoints\n      for build information, uptime, internal plugin metrics\
  \ in JSON,\n      Prometheus, and cmetrics formats, storage layer statistics, health\n      checks, and hot reload.\n    humanURL: https://docs.fluentbit.io/manual/administration/monitoring\n    baseURL: http://127.0.0.1:2020\n    tags:\n      - Logging\n      - Observability\n      - Metrics\n      - Health Check\n      - Prometheus\n    properties:\n      - type: Documentation\n        url: https://docs.fluentbit.io/manual/administration/monitoring\n      - type: OpenAPI\n        url: openapi/fluent-bit-monitoring-openapi.yml\ncommon:\n  - type: Website\n    url: https://fluentbit.io\n  - type: Documentation\n    url: https://docs.fluentbit.io\n  - type: GitHub Repository\n    url: https://github.com/fluent/fluent-bit\n  - type: Slack\n    url: https://launchpass.com/fluent-all\n  - type: Community\n    url: https://fluentbit.io/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml
tags:
- Logging
- Observability
- Metrics
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml
use_cases: []
---
