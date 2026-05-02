---
api_count: 9
api_specs:
- filename: honeycomb-api-openapi.yml
  format: yaml
  label: Honeycomb API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-api-openapi.yml
- filename: honeycomb-events-api-openapi.yml
  format: yaml
  label: Honeycomb Events API
  slug: events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-events-api-openapi.yml
- filename: honeycomb-queries-api-openapi.yml
  format: yaml
  label: Honeycomb Queries API
  slug: queries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-queries-api-openapi.yml
- filename: honeycomb-slos-api-openapi.yml
  format: yaml
  label: Honeycomb SLOs API
  slug: slos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-slos-api-openapi.yml
- filename: honeycomb-datasets-api-openapi.yml
  format: yaml
  label: Honeycomb Datasets API
  slug: datasets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-datasets-api-openapi.yml
- filename: honeycomb-boards-api-openapi.yml
  format: yaml
  label: Honeycomb Boards API
  slug: boards-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-boards-api-openapi.yml
- filename: honeycomb-markers-api-openapi.yml
  format: yaml
  label: Honeycomb Markers API
  slug: markers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-markers-api-openapi.yml
- filename: honeycomb-triggers-api-openapi.yml
  format: yaml
  label: Honeycomb Triggers API
  slug: triggers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-triggers-api-openapi.yml
- filename: honeycomb-environments-api-openapi.yml
  format: yaml
  label: Honeycomb Environments API
  slug: environments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/openapi/honeycomb-environments-api-openapi.yml
apis:
- description: The Honeycomb API is a REST API that provides programmatic access to the Honeycomb observability platform. It enables developers to send events, manage datasets and columns, create and run queries, co
  name: Honeycomb API
  slug: api
- description: The Honeycomb Events API is the lowest-level interface for sending event data to Honeycomb. It supports both single event creation and batch event submission, allowing developers to send structured te
  name: Honeycomb Events API
  slug: events-api
- description: The Honeycomb Queries API allows developers to programmatically create and manage query specifications within Honeycomb. Queries are used to identify and reference queries across other parts of the AP
  name: Honeycomb Queries API
  slug: queries-api
- description: The Honeycomb SLOs API enables developers to define and monitor Service Level Objectives programmatically. It supports creating, listing, updating, and deleting SLO objects for an organization. Combin
  name: Honeycomb SLOs API
  slug: slos-api
- description: 'The Honeycomb Datasets API provides management capabilities for datasets, which represent collections of related events from the same source. It allows developers to list, create, and update datasets '
  name: Honeycomb Datasets API
  slug: datasets-api
- description: 'The Honeycomb Boards API allows developers to programmatically create and manage boards, which are collections of queries displayed together as a dashboard-like view. Boards provide a way to organize '
  name: Honeycomb Boards API
  slug: boards-api
- description: The Honeycomb Markers API enables developers to create and manage markers that indicate points in time on graphs where notable events occurred, such as deploys, configuration changes, or outages. Mark
  name: Honeycomb Markers API
  slug: markers-api
- description: 'The Honeycomb Triggers API allows developers to programmatically configure alerting rules that fire when query results meet specified conditions. Triggers work in conjunction with the Recipients API, '
  name: Honeycomb Triggers API
  slug: triggers-api
- description: The Honeycomb Environments API provides administrative capabilities for managing environments within a Honeycomb team. Environments allow organizations to separate telemetry data across different stag
  name: Honeycomb Environments API
  slug: environments-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/honeycomb-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/honeycomb-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/honeycomb-query-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/honeycomb-slo-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/honeycomb-trigger-schema.json
created: ''
description: Build integrations and automate workflows with the Honeycomb API. Programmatically manage datasets, queries, triggers, SLOs, environments, API keys, and more.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Honeycomb Context
  property_count: 11
  slug: honeycomb-context
layout: provider
modified: '2026-04-28'
name: honeycomb
skills: []
slug: honeycomb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: honeycomb\nurl: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: honeycomb:api\n    name: Honeycomb API\n    tags:\n      - Debugging\n      - Monitoring\n      - Observability\n      - Telemetry\n      - Tracing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api\n    properties:\n      - url: https://api-docs.honeycomb.io/api\n        type: Documentation\n      - url: openapi/honeycomb-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb API is a REST API that provides programmatic access to the Honeycomb\n      observability platform. It enables developers to send events, manage datasets\n      and columns, create and run queries, configure SLOs and burn alerts, set up\n      triggers and recipients, manage boards and markers, and administer environments\n\
  \      and API keys.\n  - aid: honeycomb:events-api\n    name: Honeycomb Events API\n    tags:\n      - Events\n      - Ingestion\n      - Observability\n      - Telemetry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/events\n    properties:\n      - url: https://api-docs.honeycomb.io/api/events\n        type: Documentation\n      - url: openapi/honeycomb-events-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Events API is the lowest-level interface for sending event\n      data to Honeycomb. It supports both single event creation and batch event\n      submission, allowing developers to send structured telemetry data directly\n      to Honeycomb datasets. While Honeycomb recommends using OpenTelemetry or\n      Beeline SDKs for most instrumentation use cases, the Events API provides\n      direct control for custom integrations\
  \ and specialized data pipelines.\n  - aid: honeycomb:queries-api\n    name: Honeycomb Queries API\n    tags:\n      - Analytics\n      - Data Analysis\n      - Observability\n      - Queries\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/queries\n    properties:\n      - url: https://api-docs.honeycomb.io/api/queries\n        type: Documentation\n      - url: openapi/honeycomb-queries-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Queries API allows developers to programmatically create\n      and manage query specifications within Honeycomb. Queries are used to\n      identify and reference queries across other parts of the API, including\n      boards, triggers, and query annotations. Developers can run queries\n      asynchronously by creating a Query Result that references a Query ID,\n      then polling the query result\
  \ endpoint until the data is ready. The\n      Query Data API complements this by providing access to query results.\n  - aid: honeycomb:slos-api\n    name: Honeycomb SLOs API\n    tags:\n      - Observability\n      - Reliability\n      - Service Level Objectives\n      - SLOs\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/slos\n    properties:\n      - url: https://api-docs.honeycomb.io/api/slos\n        type: Documentation\n      - url: openapi/honeycomb-slos-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb SLOs API enables developers to define and monitor Service\n      Level Objectives programmatically. It supports creating, listing,\n      updating, and deleting SLO objects for an organization. Combined with\n      the Burn Alerts API for notifications and the Reporting API for\n      historical SLO performance analysis, it\
  \ provides a complete interface\n      for managing reliability targets and tracking error budgets over time.\n  - aid: honeycomb:datasets-api\n    name: Honeycomb Datasets API\n    tags:\n      - Data Management\n      - Datasets\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/datasets\n    properties:\n      - url: https://api-docs.honeycomb.io/api/datasets\n        type: Documentation\n      - url: openapi/honeycomb-datasets-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Datasets API provides management capabilities for datasets,\n      which represent collections of related events from the same source. It\n      allows developers to list, create, and update datasets programmatically.\n      The related Columns API enables management of fields within datasets,\n      including listing, creating, updating,\
  \ and deleting columns that define\n      the structure of event data stored in Honeycomb.\n  - aid: honeycomb:boards-api\n    name: Honeycomb Boards API\n    tags:\n      - Dashboards\n      - Observability\n      - Visualization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/boards\n    properties:\n      - url: https://api-docs.honeycomb.io/api/boards\n        type: Documentation\n      - url: openapi/honeycomb-boards-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Boards API allows developers to programmatically create\n      and manage boards, which are collections of queries displayed together\n      as a dashboard-like view. Boards provide a way to organize and share\n      related queries for monitoring and debugging workflows. The API supports\n      listing, creating, updating, and deleting boards, making it possible\
  \ to\n      automate the setup of observability dashboards across environments.\n  - aid: honeycomb:markers-api\n    name: Honeycomb Markers API\n    tags:\n      - Annotations\n      - Deployments\n      - Markers\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/marker-settings\n    properties:\n      - url: https://api-docs.honeycomb.io/api/marker-settings\n        type: Documentation\n      - url: openapi/honeycomb-markers-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Markers API enables developers to create and manage markers\n      that indicate points in time on graphs where notable events occurred,\n      such as deploys, configuration changes, or outages. Marker Settings\n      allow grouping similar markers together with consistent visual styling.\n      The API supports listing, creating, updating,\
  \ and deleting both markers\n      and marker settings, making it straightforward to integrate deployment\n      pipelines and incident workflows with Honeycomb visualizations.\n  - aid: honeycomb:triggers-api\n    name: Honeycomb Triggers API\n    tags:\n      - Alerts\n      - Monitoring\n      - Notifications\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/triggers\n    properties:\n      - url: https://api-docs.honeycomb.io/api/triggers\n        type: Documentation\n      - url: openapi/honeycomb-triggers-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Triggers API allows developers to programmatically configure\n      alerting rules that fire when query results meet specified conditions.\n      Triggers work in conjunction with the Recipients API, which manages\n      notification destinations including\
  \ PagerDuty, Email, Webhook, Microsoft\n      Teams, and Slack. The API supports listing, creating, updating, and\n      deleting triggers, enabling automated setup of alerting workflows for\n      production observability.\n  - aid: honeycomb:environments-api\n    name: Honeycomb Environments API\n    tags:\n      - Administration\n      - Environments\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.honeycomb.io\n    humanURL: https://api-docs.honeycomb.io/api/environments\n    properties:\n      - url: https://api-docs.honeycomb.io/api/environments\n        type: Documentation\n      - url: openapi/honeycomb-environments-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Honeycomb Environments API provides administrative capabilities for\n      managing environments within a Honeycomb team. Environments allow\n      organizations to separate telemetry data across different stages\
  \ such\n      as development, staging, and production. The API supports listing,\n      creating, updating, and deleting environments, along with the Auth API\n      for validating API keys and determining their associated team and\n      environment permissions.\ncommon:\n  - type: JSON-LD\n    url: json-ld/honeycomb-context.jsonld\n  - type: JSONSchema\n    url: json-schema/honeycomb-event-schema.json\n  - type: JSONSchema\n    url: json-schema/honeycomb-query-schema.json\n  - type: JSONSchema\n    url: json-schema/honeycomb-slo-schema.json\n  - type: JSONSchema\n    url: json-schema/honeycomb-trigger-schema.json\ndescription: >-\n  Build integrations and automate workflows with the Honeycomb API. Programmatically\n  manage datasets, queries, triggers, SLOs, environments, API keys, and more.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml
use_cases: []
---
