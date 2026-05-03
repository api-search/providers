---
api_count: 1
api_specs:
- filename: zipkin-api-v2.yml
  format: yaml
  label: Zipkin API V2
  slug: zipkin-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/openapi/zipkin-api-v2.yml
apis:
- description: Zipkin's v2 HTTP API for querying and collecting distributed traces. Provides endpoints for submitting spans, querying traces, looking up services and span names, and retrieving dependency links betwe
  name: Zipkin API V2
  slug: zipkin-api-v2
common:
- title: ''
  type: Website
  url: https://zipkin.io
- title: ''
  type: Documentation
  url: https://zipkin.io/pages/quickstart.html
- title: ''
  type: GitHub Organization
  url: https://github.com/openzipkin/zipkin
created: '2026-03-25'
description: Zipkin is an open source distributed tracing system for gathering timing data to troubleshoot latency problems in microservice architectures.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-26'
name: Zipkin
skills: []
slug: zipkin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zipkin\nname: Zipkin\ndescription: >-\n  Zipkin is an open source distributed tracing system for gathering timing data to troubleshoot latency problems in microservice architectures.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Tracing\n  - Observability\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-03-26'\nspecificationVersion: '0.19'\napis:\n  - aid: zipkin:zipkin-api-v2\n    name: Zipkin API V2\n    description: >-\n      Zipkin's v2 HTTP API for querying and collecting distributed traces.\n      Provides endpoints for submitting spans, querying traces, looking up\n      services and span names, and retrieving dependency links between services.\n    humanURL: https://zipkin.io/zipkin-api/\n    tags:\n      - Dependencies\n      - Distributed Tracing\n      - Observability\n      - Spans\n      - Traces\n   \
  \ properties:\n      - type: Documentation\n        url: https://zipkin.io/zipkin-api/\n      - type: GitHub Repository\n        url: https://github.com/openzipkin/zipkin\n      - type: OpenAPI\n        url: openapi/zipkin-api-v2.yml\n      - type: JSONSchema\n        url: json-schema/span.yml\ncommon:\n  - type: Website\n    url: https://zipkin.io\n  - type: Documentation\n    url: https://zipkin.io/pages/quickstart.html\n  - type: GitHub Organization\n    url: https://github.com/openzipkin/zipkin\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml
tags:
- Distributed Tracing
- Observability
url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml
use_cases: []
---
