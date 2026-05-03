---
api_count: 5
apis:
- description: Resurface captures complete API request and response data in real time, providing full-payload API call logging with no sampling. Security teams use it to detect threats, identify data leaks, and ensu
  name: Resurface Platform
  slug: resurface-platform
- description: Open-source Go library for logging API requests and responses to the Resurface database. Integrates with gorilla/mux and other Go HTTP frameworks.
  name: Resurface Logger for Go
  slug: resurface-logger-go
- description: eBPF-based kernel-level API call logger that captures HTTP traffic without application code changes for zero-instrumentation observability.
  name: Resurface Logger for eBPF
  slug: resurface-logger-ebpf
- description: Official Helm charts and container images for deploying the Resurface API security database on Kubernetes.
  name: Resurface Containers
  slug: resurface-containers
- description: Connector for querying Resurface API call data via Trino distributed SQL query engine.
  name: Resurface Trino Connector
  slug: resurface-trino-connector
common:
- title: ''
  type: Website
  url: https://resurface.io
- title: ''
  type: Documentation
  url: https://resurface.io/docs
- title: ''
  type: Blog
  url: https://resurface.io/blog
- title: ''
  type: GitHub
  url: https://github.com/resurfaceio
- title: ''
  type: Pricing
  url: https://resurface.io/pricing
- title: ''
  type: Support
  url: https://resurface.io/support
- title: ''
  type: Login
  url: https://resurface.io/login
- title: ''
  type: Twitter
  url: https://twitter.com/resabordeio
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/resurfacelabs
- title: ''
  type: HelmChart
  url: https://artifacthub.io/packages/helm/resurfaceio/resurface
- title: ''
  type: AcquiredBy
  url: https://graylog.org
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/vocabulary/resurface-vocabulary.yml
created: '2026-03-26'
description: Resurface (now Graylog API Security) is an API runtime security and observability platform that captures and analyzes complete API request and response payloads in real time. It provides full API call logging, threat detection, data leak prevention, and compliance auditing for API traffic without sampling or aggregation. Acquired by Graylog and integrated into the Graylog SIEM platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Resurface Context
  property_count: 10
  slug: resurface-context
layout: provider
modified: '2026-05-02'
name: Resurface
skills: []
slug: resurface
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: resurface\nname: Resurface\ndescription: >-\n  Resurface (now Graylog API Security) is an API runtime security and observability\n  platform that captures and analyzes complete API request and response payloads\n  in real time. It provides full API call logging, threat detection, data leak\n  prevention, and compliance auditing for API traffic without sampling or aggregation.\n  Acquired by Graylog and integrated into the Graylog SIEM platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Analytics\n  - API Compliance\n  - API Logging\n  - API Observability\n  - API Security\n  - Data Leak Prevention\n  - Runtime Security\n  - SIEM\n  - Threat Detection\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: resurface:resurface-platform\n    name: Resurface Platform\n    description:\
  \ >-\n      Resurface captures complete API request and response data in real time,\n      providing full-payload API call logging with no sampling. Security teams\n      use it to detect threats, identify data leaks, and ensure compliance\n      across all API traffic using a custom columnar database and SQL query interface.\n    humanURL: https://resurface.io\n    tags:\n      - API Compliance\n      - API Logging\n      - API Observability\n      - API Security\n      - Runtime Security\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://resurface.io/docs\n      - type: GettingStarted\n        url: https://resurface.io/docs/getting-started\n      - type: HelmChart\n        url: https://artifacthub.io/packages/helm/resurfaceio/resurface\n      - type: GitHub\n        url: https://github.com/resurfaceio\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/json-schema/resurface-api-call-log-schema.json\n\
  \  - aid: resurface:resurface-logger-go\n    name: Resurface Logger for Go\n    description: >-\n      Open-source Go library for logging API requests and responses to the\n      Resurface database. Integrates with gorilla/mux and other Go HTTP frameworks.\n    humanURL: https://github.com/resurfaceio/logger-go\n    tags:\n      - Go\n      - Integration\n      - Logger\n      - SDK\n    properties:\n      - type: GitHub\n        url: https://github.com/resurfaceio/logger-go\n  - aid: resurface:resurface-logger-ebpf\n    name: Resurface Logger for eBPF\n    description: >-\n      eBPF-based kernel-level API call logger that captures HTTP traffic\n      without application code changes for zero-instrumentation observability.\n    humanURL: https://github.com/resurfaceio/logger-ebpf\n    tags:\n      - eBPF\n      - Integration\n      - Kubernetes\n      - Logger\n    properties:\n      - type: GitHub\n        url: https://github.com/resurfaceio/logger-ebpf\n  - aid: resurface:resurface-containers\n\
  \    name: Resurface Containers\n    description: >-\n      Official Helm charts and container images for deploying the Resurface\n      API security database on Kubernetes.\n    humanURL: https://resurfaceio.github.io/containers/\n    tags:\n      - Containers\n      - Docker\n      - Helm\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://resurfaceio.github.io/containers/\n      - type: HelmChart\n        url: https://artifacthub.io/packages/helm/resurfaceio/resurface\n      - type: GitHub\n        url: https://github.com/resurfaceio/containers\n  - aid: resurface:resurface-trino-connector\n    name: Resurface Trino Connector\n    description: >-\n      Connector for querying Resurface API call data via Trino distributed\n      SQL query engine.\n    humanURL: https://github.com/resurfaceio/trino-connector\n    tags:\n      - Analytics\n      - Integration\n      - SQL\n      - Trino\n    properties:\n      - type: GitHub\n        url: https://github.com/resurfaceio/trino-connector\n\
  common:\n  - type: Website\n    url: https://resurface.io\n  - type: Documentation\n    url: https://resurface.io/docs\n  - type: Blog\n    url: https://resurface.io/blog\n  - type: GitHub\n    url: https://github.com/resurfaceio\n  - type: Pricing\n    url: https://resurface.io/pricing\n  - type: Support\n    url: https://resurface.io/support\n  - type: Login\n    url: https://resurface.io/login\n  - type: Twitter\n    url: https://twitter.com/resabordeio\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/resurfacelabs\n  - type: HelmChart\n    url: https://artifacthub.io/packages/helm/resurfaceio/resurface\n  - type: AcquiredBy\n    url: https://graylog.org\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/vocabulary/resurface-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/apis.yml
tags:
- API Analytics
- API Compliance
- API Logging
- API Observability
- API Security
- Data Leak Prevention
- Runtime Security
- SIEM
- Threat Detection
url: https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/apis.yml
use_cases: []
---
