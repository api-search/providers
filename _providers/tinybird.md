---
api_count: 1
api_specs:
- filename: tinybird-openapi.yml
  format: yaml
  label: Tinybird API
  slug: tinybird
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/openapi/tinybird-openapi.yml
apis:
- description: Tinybird provides a real-time data platform with comprehensive REST APIs for managing data sources, executing SQL queries, managing pipes and transformations, ingesting events, managing authentication
  name: Tinybird API
  slug: tinybird
capabilities:
- description: 'Workflow capability for real-time data analytics using Tinybird. Combines data ingestion, SQL transformation pipelines, and instant API publishing to support analytics engineers, data platform teams, '
  name: Tinybird Real-Time Analytics
  slug: real-time-analytics
common:
- title: ''
  type: Website
  url: https://www.tinybird.co/
- title: ''
  type: Documentation
  url: https://www.tinybird.co/docs/api-reference
- title: ''
  type: Getting Started
  url: https://www.tinybird.co/docs/get-started
- title: ''
  type: Sign Up
  url: https://www.tinybird.co/signup
- title: ''
  type: Blog
  url: https://www.tinybird.co/blog
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/openapi/tinybird-openapi.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-ld/tinybird-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/vocabulary/tinybird-vocabulary.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/rules/tinybird-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/capabilities/real-time-analytics.yaml
- title: ''
  type: GitHub Organization
  url: https://github.com/tinybirdco
created: '2025-01-08'
description: Tinybird is a real-time data platform that allows you to ingest, process, and expose data through low-latency, high-concurrency APIs. The platform supports real-time analytics at scale with a SQL-based transformation layer and instant REST API endpoint publishing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Tinybird Context
  property_count: 2
  slug: tinybird-context
layout: provider
modified: '2026-05-03'
name: Tinybird
rules:
- name: Tinybird API Rules
  rule_count: 12
  severity_counts:
    error: 6
    hint: 2
    info: 0
    warn: 4
  slug: tinybird-rules
skills: []
slug: tinybird
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tinybird\nname: Tinybird\ndescription: >-\n  Tinybird is a real-time data platform that allows you to ingest, process, and\n  expose data through low-latency, high-concurrency APIs. The platform supports\n  real-time analytics at scale with a SQL-based transformation layer and instant\n  REST API endpoint publishing.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Data\n  - Real-Time\n  - SQL\n  - Streaming\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tinybird:tinybird\n    name: Tinybird API\n    description: >-\n      Tinybird provides a real-time data platform with comprehensive REST APIs for\n      managing data sources, executing SQL queries, managing pipes and transformations,\n      ingesting events, managing authentication\
  \ tokens, monitoring jobs, and\n      administering organizations and workspaces.\n    humanURL: https://www.tinybird.co/docs/api-reference\n    baseURL: https://api.tinybird.co\n    tags:\n      - Analytics\n      - Data\n      - Real-Time\n      - SQL\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://www.tinybird.co/docs/api-reference\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/openapi/tinybird-openapi.yml\n      - type: Getting Started\n        url: https://www.tinybird.co/docs/get-started\n      - type: Authentication\n        url: https://www.tinybird.co/docs/api-reference/token-api\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-schema/tinybird-data-source-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-structure/tinybird-data-source-structure.json\n\
  \      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-ld/tinybird-context.jsonld\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/rules/tinybird-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/capabilities/real-time-analytics.yaml\nfeatures:\n  - Real-time data ingestion via Events API\n  - SQL-based data transformation with Pipes\n  - Instant REST API endpoint publishing\n  - Multi-region deployment support\n  - Materialized views for query optimization\n  - Sink pipes for data export\n  - Token-based access control with scopes\n  - Job tracking for async operations\n  - Organization and workspace management\n  - Environment variables for pipeline configuration\nuseCases:\n  - Real-time analytics dashboards\n  - User-facing analytics\
  \ APIs\n  - Event stream processing\n  - Log analytics and monitoring\n  - A/B testing and experimentation data\n  - Financial data processing\n  - IoT sensor data analytics\nintegrations:\n  - Kafka data ingestion\n  - DynamoDB connector\n  - S3 data sources\n  - Snowflake\n  - Confluent\n  - dbt transformations\n  - TypeScript SDK\n  - Python SDK\nsolutions:\n  - Real-time API publishing\n  - Analytics backend infrastructure\n  - Data pipeline management\n  - Multi-tenant data analytics\ncommon:\n  - type: Website\n    url: https://www.tinybird.co/\n  - type: Documentation\n    url: https://www.tinybird.co/docs/api-reference\n  - type: Getting Started\n    url: https://www.tinybird.co/docs/get-started\n  - type: Sign Up\n    url: https://www.tinybird.co/signup\n  - type: Blog\n    url: https://www.tinybird.co/blog\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/openapi/tinybird-openapi.yml\n  - type: JSONLDContext\n   \
  \ url: >-\n      https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-ld/tinybird-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/vocabulary/tinybird-vocabulary.yml\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/rules/tinybird-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/capabilities/real-time-analytics.yaml\n  - type: GitHub Organization\n    url: https://github.com/tinybirdco\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/apis.yml
tags:
- Analytics
- Data
- Real-Time
- SQL
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/apis.yml
use_cases: []
---
