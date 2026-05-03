---
api_count: 5
api_specs:
- filename: statsig-http-api-openapi.yml
  format: yaml
  label: Statsig HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-http-api-openapi.yml
- filename: statsig-console-api-openapi.yml
  format: yaml
  label: Statsig Console API
  slug: console-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-console-api-openapi.yml
- filename: statsig-client-sdk-api-openapi.yml
  format: yaml
  label: Statsig Client SDK API
  slug: client-sdk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-client-sdk-api-openapi.yml
- filename: statsig-server-sdk-api-openapi.yml
  format: yaml
  label: Statsig Server SDK API
  slug: server-sdk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-server-sdk-api-openapi.yml
- filename: statsig-events-api-openapi.yml
  format: yaml
  label: Statsig Events API
  slug: events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-events-api-openapi.yml
apis:
- description: The Statsig HTTP API allows developers to evaluate feature gates, dynamic configs, and experiments for users via server-side HTTP requests. It provides endpoints for checking gate values, fetching con
  name: Statsig HTTP API
  slug: http-api
- description: The Statsig Console API enables developers to programmatically manage their Statsig project configuration. It supports full CRUD operations on feature gates, dynamic configs, experiments, segments, la
  name: Statsig Console API
  slug: console-api
- description: 'The Statsig Client SDK API provides endpoints that power Statsig''s client-side SDKs for JavaScript, React, React Native, iOS, Android, Unity, and other platforms. Client SDKs use Client-SDK Keys that '
  name: Statsig Client SDK API
  slug: client-sdk-api
- description: The Statsig Server SDK API provides endpoints that power Statsig's server-side SDKs for Node.js, Python, Java, Ruby, Go, .NET, and other backend languages. Server SDKs use Server Secret Keys and acces
  name: Statsig Server SDK API
  slug: server-sdk-api
- description: The Statsig Events API handles the ingestion of event data from both client and server SDKs. It receives exposure events, custom events, and diagnostic data at the events.statsigapi.net endpoint. This
  name: Statsig Events API
  slug: events-api
asyncapis:
- description: 'Statsig''s webhook system provides real-time event-driven notifications for exposure events and configuration changes. Webhooks are triggered at runtime as users are assigned to gates and experiments, '
  name: Statsig Webhook Events
  slug: statsig-webhooks-asyncapi
capabilities:
- description: Unified feature management workflow combining Statsig's HTTP API and Console API. Enables product teams to evaluate feature gates in real-time, manage gate configuration, run A/B experiments, track ex
  name: Statsig Feature Management
  slug: feature-management
common:
- title: ''
  type: JSON-LD
  url: json-ld/statsig-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/statsig-feature-gate-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/statsig-experiment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/statsig-event-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/statsig-feature-gate-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/statsig-experiment-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/statsig-event-structure.json
- title: ''
  type: SpectralRules
  url: rules/statsig-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/feature-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/statsig-vocabulary.yml
created: ''
description: Statsig is a feature management and experimentation platform that helps product teams ship features safely with feature flags, run A/B tests, and measure the impact of every feature on key metrics.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Statsig Context
  property_count: 13
  slug: statsig-context
layout: provider
modified: '2026-03-20'
name: statsig
rules:
- name: statsig API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 3
    info: 0
    warn: 5
  slug: statsig-rules
skills: []
slug: statsig
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: statsig\nurl: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: statsig:http-api\n    name: Statsig HTTP API\n    tags:\n      - A/B Testing\n      - Analytics\n      - Dynamic Configuration\n      - Experimentation\n      - Feature Flags\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.statsig.com\n    humanURL: https://docs.statsig.com/http-api/\n    properties:\n      - url: https://docs.statsig.com/http-api/\n        type: Documentation\n      - url: openapi/statsig-http-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Statsig HTTP API allows developers to evaluate feature gates, dynamic configs,\n      and experiments for users via server-side HTTP requests. It provides endpoints\n      for checking gate values, fetching configuration data, and logging custom events.\n      All requests use the POST method with\
  \ JSON request bodies and require authentication\n      via the statsig-api-key header.\n  - aid: statsig:console-api\n    name: Statsig Console API\n    tags:\n      - Administration\n      - Automation\n      - Configuration Management\n      - Experimentation\n      - Feature Flags\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://statsigapi.net/console/v1\n    humanURL: https://docs.statsig.com/console-api/\n    properties:\n      - url: https://docs.statsig.com/console-api/\n        type: Documentation\n      - url: openapi/statsig-console-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Statsig Console API enables developers to programmatically manage their\n      Statsig project configuration. It supports full CRUD operations on feature gates,\n      dynamic configs, experiments, segments, layers, and other entities. The API\n      requires a Console API Key and uses versioned endpoints with the STATSIG-API-VERSION\n\
  \      header.\n  - aid: statsig:client-sdk-api\n    name: Statsig Client SDK API\n    tags:\n      - Client Side\n      - Feature Flags\n      - Mobile\n      - SDKs\n      - Web\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.statsig.com\n    humanURL: https://docs.statsig.com/client/introduction\n    properties:\n      - url: https://docs.statsig.com/client/introduction\n        type: Documentation\n      - url: openapi/statsig-client-sdk-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Statsig Client SDK API provides endpoints that power Statsig's client-side\n      SDKs for JavaScript, React, React Native, iOS, Android, Unity, and other platforms.\n      Client SDKs use Client-SDK Keys that are safe to embed in mobile apps and front-end\n      web applications. They access the initialize endpoint to retrieve all evaluated\n      gates, configs, and experiments for a given user, and the log_event\
  \ endpoint\n      for sending analytics events.\n  - aid: statsig:server-sdk-api\n    name: Statsig Server SDK API\n    tags:\n      - Backend\n      - Evaluation\n      - Feature Flags\n      - SDKs\n      - Server Side\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.statsig.com\n    humanURL: https://docs.statsig.com/server/introduction\n    properties:\n      - url: https://docs.statsig.com/server/introduction\n        type: Documentation\n      - url: openapi/statsig-server-sdk-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Statsig Server SDK API provides endpoints that power Statsig's server-side\n      SDKs for Node.js, Python, Java, Ruby, Go, .NET, and other backend languages.\n      Server SDKs use Server Secret Keys and access the download_config_specs endpoint\n      to retrieve the full project configuration for local evaluation. This enables\n      sub-millisecond feature gate checks without\
  \ per-request network calls.\n  - aid: statsig:events-api\n    name: Statsig Events API\n    tags:\n      - Analytics\n      - Data Ingestion\n      - Events\n      - Logging\n      - Metrics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://events.statsigapi.net\n    humanURL: https://docs.statsig.com/http-api/\n    properties:\n      - url: https://docs.statsig.com/http-api/\n        type: Documentation\n      - url: openapi/statsig-events-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/statsig-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Statsig Events API handles the ingestion of event data from both\n      client and server SDKs. It receives exposure events, custom events, and\n      diagnostic data at the events.statsigapi.net endpoint. This data powers\n      Statsig's experimentation analysis, product analytics, and metric\n      computations. The Events API is optimized for\
  \ high-throughput data\n      ingestion, processing over a trillion events daily with high reliability\n      and low latency, enabling real-time experiment monitoring and metric\n      updates.\ncommon:\n  - type: JSON-LD\n    url: json-ld/statsig-context.jsonld\n  - type: JSONSchema\n    url: json-schema/statsig-feature-gate-schema.json\n  - type: JSONSchema\n    url: json-schema/statsig-experiment-schema.json\n  - type: JSONSchema\n    url: json-schema/statsig-event-schema.json\n  - type: JSONStructure\n    url: json-structure/statsig-feature-gate-structure.json\n  - type: JSONStructure\n    url: json-structure/statsig-experiment-structure.json\n  - type: JSONStructure\n    url: json-structure/statsig-event-structure.json\n  - type: SpectralRules\n    url: rules/statsig-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/feature-management.yaml\n  - type: Vocabulary\n    url: vocabulary/statsig-vocabulary.yml\ndescription: >-\n  Statsig is a feature management and experimentation\
  \ platform that helps product\n  teams ship features safely with feature flags, run A/B tests, and measure the impact\n  of every feature on key metrics.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml
use_cases: []
---
