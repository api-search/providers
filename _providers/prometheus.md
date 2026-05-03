---
api_count: 6
api_specs:
- filename: prometheus-http-api-openapi.yml
  format: yaml
  label: Prometheus HTTP API
  slug: prometheus-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-http-api-openapi.yml
- filename: prometheus-management-api-openapi.yml
  format: yaml
  label: Prometheus Management API
  slug: prometheus-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-management-api-openapi.yml
- filename: prometheus-pushgateway-api-openapi.yml
  format: yaml
  label: Prometheus Pushgateway API
  slug: prometheus-pushgateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-pushgateway-api-openapi.yml
- filename: prometheus-alertmanager-api-openapi.yml
  format: yaml
  label: Prometheus Alertmanager API
  slug: prometheus-alertmanager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-alertmanager-api-openapi.yml
apis:
- description: The Prometheus HTTP API provides endpoints for executing instant and range queries using PromQL, querying metadata such as labels and series, and managing targets and rules. The API is reachable under
  name: Prometheus HTTP API
  slug: prometheus-http-api
- description: The Prometheus Management API provides administrative endpoints for managing a running Prometheus server, including configuration reloads, taking snapshots of the TSDB, cleaning tombstones, and gracef
  name: Prometheus Management API
  slug: prometheus-management-api
- description: The Pushgateway API accepts metrics pushed from short-lived batch jobs and ephemeral processes via HTTP PUT, POST, and DELETE requests. Metrics are organized by job and optional grouping labels, and a
  name: Prometheus Pushgateway API
  slug: prometheus-pushgateway-api
- description: The Alertmanager API v2 provides HTTP endpoints for querying alert status, managing silences and inhibitions, retrieving receiver configurations, and checking cluster status. An OpenAPI 2.0 specificat
  name: Prometheus Alertmanager API
  slug: prometheus-alertmanager-api
- description: The Prometheus Remote Write API defines a standard protocol for sending time series data from Prometheus or compatible agents to remote storage backends via HTTP POST with Snappy-compressed protobuf p
  name: Prometheus Remote Write API
  slug: prometheus-remote-write-api
- description: Prometheus provides official client libraries for Go, Java/Scala, Python, Ruby, and Rust that enable application instrumentation. Libraries implement the Prometheus metric types (Counter, Gauge, Histo
  name: Prometheus Client Libraries
  slug: prometheus-client-libraries
asyncapis:
- description: The Prometheus Alertmanager webhook receiver sends HTTP POST requests to configured endpoints when alert groups are triggered. Each webhook payload contains a group of alerts sharing common routing la
  name: Prometheus Alertmanager Webhook Events
  slug: prometheus-alertmanager-webhook-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/prometheus-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/prometheus-metrics-schema.json
- title: ''
  type: Website
  url: https://prometheus.io
- title: ''
  type: Documentation
  url: https://prometheus.io/docs/
- title: ''
  type: Getting Started
  url: https://prometheus.io/docs/introduction/getting_started/
- title: ''
  type: GitHub Organization
  url: https://github.com/prometheus
- title: ''
  type: GitHubRepository
  url: https://github.com/prometheus/prometheus
- title: ''
  type: Blog
  url: https://prometheus.io/blog/
- title: ''
  type: Community
  url: https://prometheus.io/community/
- title: ''
  type: Change Log
  url: https://github.com/prometheus/prometheus/releases
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/prometheus
created: '2024-01-01'
description: An open-source systems monitoring and alerting toolkit originally built at SoundCloud. Prometheus collects and stores metrics as time series data and provides a powerful query language (PromQL) for analysis.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Prometheus Context
  property_count: 13
  slug: prometheus-context
layout: provider
modified: '2026-04-28'
name: Prometheus
skills: []
slug: prometheus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: prometheus\nname: Prometheus\ndescription: An open-source systems monitoring and alerting toolkit originally built at SoundCloud. Prometheus collects and stores metrics as time series data and provides a powerful query language (PromQL) for analysis.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Alerting\n  - Metrics\n  - Monitoring\n  - Observability\n  - Time Series\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: prometheus:prometheus-http-api\n    name: Prometheus HTTP API\n    description: >-\n      The Prometheus HTTP API provides endpoints for executing instant and\n      range queries using PromQL, querying metadata such as labels and series,\n      and managing targets and rules. The API is reachable under /api/v1 on a\n      Prometheus server and returns JSON\
  \ responses. An OpenAPI specification\n      is served at /api/v1/openapi.yaml.\n    humanURL: https://prometheus.io/docs/prometheus/latest/querying/api/\n    tags:\n      - Metrics\n      - PromQL\n      - Query\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/prometheus/latest/querying/api/\n      - type: OpenAPI\n        url: openapi/prometheus-http-api-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/prometheus/prometheus\n      - type: Change Log\n        url: https://github.com/prometheus/prometheus/blob/main/CHANGELOG.md\n      - type: JSONSchema\n        url: json-schema/prometheus-metrics-schema.json\n  - aid: prometheus:prometheus-management-api\n    name: Prometheus Management API\n    description: >-\n      The Prometheus Management API provides administrative endpoints for\n      managing a running Prometheus server, including configuration reloads,\n      taking snapshots of the TSDB, cleaning\
  \ tombstones, and graceful\n      shutdown. These endpoints are disabled by default and require the\n      --web.enable-lifecycle flag.\n    humanURL: https://prometheus.io/docs/prometheus/latest/management_api/\n    tags:\n      - Administration\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/prometheus/latest/management_api/\n      - type: OpenAPI\n        url: openapi/prometheus-management-api-openapi.yml\n  - aid: prometheus:prometheus-pushgateway-api\n    name: Prometheus Pushgateway API\n    description: >-\n      The Pushgateway API accepts metrics pushed from short-lived batch jobs\n      and ephemeral processes via HTTP PUT, POST, and DELETE requests. Metrics\n      are organized by job and optional grouping labels, and are exposed for\n      Prometheus scraping until explicitly deleted.\n    humanURL: https://github.com/prometheus/pushgateway\n    tags:\n      - Batch Jobs\n      - Metrics\n      -\
  \ Pushgateway\n    properties:\n      - type: Documentation\n        url: https://github.com/prometheus/pushgateway/blob/master/README.md\n      - type: OpenAPI\n        url: openapi/prometheus-pushgateway-api-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/prometheus/pushgateway\n      - type: Change Log\n        url: https://github.com/prometheus/pushgateway/releases\n  - aid: prometheus:prometheus-alertmanager-api\n    name: Prometheus Alertmanager API\n    description: >-\n      The Alertmanager API v2 provides HTTP endpoints for querying alert\n      status, managing silences and inhibitions, retrieving receiver\n      configurations, and checking cluster status. An OpenAPI 2.0\n      specification is available in the Alertmanager repository.\n    humanURL: https://prometheus.io/docs/alerting/latest/alertmanager/\n    tags:\n      - Alerting\n      - Notifications\n      - Silences\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/alerting/latest/alertmanager/\n\
  \      - type: OpenAPI\n        url: openapi/prometheus-alertmanager-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/prometheus-alertmanager-webhook-asyncapi.yml\n      - type: GitHubRepository\n        url: https://github.com/prometheus/alertmanager\n      - type: Change Log\n        url: https://github.com/prometheus/alertmanager/releases\n  - aid: prometheus:prometheus-remote-write-api\n    name: Prometheus Remote Write API\n    description: >-\n      The Prometheus Remote Write API defines a standard protocol for sending\n      time series data from Prometheus or compatible agents to remote storage\n      backends via HTTP POST with Snappy-compressed protobuf payloads. The\n      specification documents the wire format, required headers, and retry\n      semantics for interoperable remote write implementations.\n    humanURL: https://prometheus.io/docs/specs/prw/remote_write_spec/\n    tags:\n      - Integration\n      - Remote Write\n      - Storage\n      - Time Series\n\
  \    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/specs/prw/remote_write_spec/\n  - aid: prometheus:prometheus-client-libraries\n    name: Prometheus Client Libraries\n    description: >-\n      Prometheus provides official client libraries for Go, Java/Scala,\n      Python, Ruby, and Rust that enable application instrumentation. Libraries\n      implement the Prometheus metric types (Counter, Gauge, Histogram, Summary)\n      and expose metrics via an HTTP endpoint for Prometheus to scrape.\n    humanURL: https://prometheus.io/docs/instrumenting/clientlibs/\n    tags:\n      - Client Libraries\n      - Instrumentation\n      - Metrics\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/instrumenting/clientlibs/\n      - type: Reference\n        url: https://prometheus.io/docs/instrumenting/writing_clientlibs/\ncommon:\n  - type: JSON-LD\n    url: json-ld/prometheus-context.jsonld\n  - type: JSONSchema\n\
  \    url: json-schema/prometheus-metrics-schema.json\n  - type: Website\n    url: https://prometheus.io\n  - type: Documentation\n    url: https://prometheus.io/docs/\n  - type: Getting Started\n    url: https://prometheus.io/docs/introduction/getting_started/\n  - type: GitHub Organization\n    url: https://github.com/prometheus\n  - type: GitHubRepository\n    url: https://github.com/prometheus/prometheus\n  - type: Blog\n    url: https://prometheus.io/blog/\n  - type: Community\n    url: https://prometheus.io/community/\n  - type: Change Log\n    url: https://github.com/prometheus/prometheus/releases\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/prometheus\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/apis.yml
tags:
- Alerting
- Metrics
- Monitoring
- Observability
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/apis.yml
use_cases: []
---
