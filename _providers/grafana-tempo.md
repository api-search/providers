---
api_count: 1
api_specs:
- filename: tempo-http-api.yml
  format: yaml
  label: Grafana Tempo HTTP API
  slug: tempo-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grafana-tempo/refs/heads/main/openapi/tempo-http-api.yml
apis:
- description: Grafana Tempo HTTP API for querying traces, searching with TraceQL, retrieving tag names and values, and computing metrics summaries from distributed trace data.
  name: Grafana Tempo HTTP API
  slug: tempo-http-api
common:
- title: ''
  type: Website
  url: https://grafana.com/oss/tempo/
- title: ''
  type: Documentation
  url: https://grafana.com/docs/tempo/latest/
- title: ''
  type: Getting Started
  url: https://grafana.com/docs/tempo/latest/getting-started/
- title: ''
  type: GitHub
  url: https://github.com/grafana/tempo
- title: ''
  type: Blog
  url: https://grafana.com/blog/
- title: ''
  type: Pricing
  url: https://grafana.com/pricing/
created: '2026-03-26'
description: Grafana Tempo is an open-source, high-scale distributed tracing backend that requires only object storage to operate, making it cost-effective and easy to run. It integrates deeply with Grafana, Prometheus, and Loki for seamless observability across metrics, logs, and traces.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-26'
name: Grafana Tempo
skills: []
slug: grafana-tempo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: grafana-tempo\nname: Grafana Tempo\ndescription: >-\n  Grafana Tempo is an open-source, high-scale distributed tracing backend that\n  requires only object storage to operate, making it cost-effective and easy to\n  run. It integrates deeply with Grafana, Prometheus, and Loki for seamless\n  observability across metrics, logs, and traces.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Tracing\n  - Grafana\n  - Microservices\n  - Observability\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/grafana-tempo/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-03-26'\nspecificationVersion: '0.19'\napis:\n  - aid: grafana-tempo:tempo-http-api\n    name: Grafana Tempo HTTP API\n    description: >-\n      Grafana Tempo HTTP API for querying traces, searching with TraceQL,\n      retrieving tag names and values, and computing metrics summaries from\n      distributed\
  \ trace data.\n    humanURL: https://grafana.com/docs/tempo/latest/api_docs/\n    tags:\n      - Distributed Tracing\n      - Observability\n      - Search\n      - TraceQL\n      - Traces\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/tempo/latest/api_docs/\n      - type: OpenAPI\n        url: openapi/tempo-http-api.yml\n      - type: JSONSchema\n        url: json-schema/trace.yml\ncommon:\n  - type: Website\n    url: https://grafana.com/oss/tempo/\n  - type: Documentation\n    url: https://grafana.com/docs/tempo/latest/\n  - type: Getting Started\n    url: https://grafana.com/docs/tempo/latest/getting-started/\n  - type: GitHub\n    url: https://github.com/grafana/tempo\n  - type: Blog\n    url: https://grafana.com/blog/\n  - type: Pricing\n    url: https://grafana.com/pricing/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/grafana-tempo/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Grafana
- Microservices
- Observability
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/grafana-tempo/refs/heads/main/apis.yml
use_cases: []
---
