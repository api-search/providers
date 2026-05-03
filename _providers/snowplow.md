---
api_count: 2
api_specs:
- filename: snowplow-console-api-openapi.yml
  format: yaml
  label: Snowplow Console API
  slug: snowplow-console-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/openapi/snowplow-console-api-openapi.yml
apis:
- description: The Snowplow Console API provides programmatic management of the Snowplow behavioral data platform. Covers data structures (JSON schemas for event validation), data products (tracking plans), event sp
  name: Snowplow Console API
  slug: snowplow-console-api
- description: 'Snowplow provides tracker SDKs for all major platforms including JavaScript (web), iOS, Android, Python, Java, Go, Ruby, .NET, PHP, and Rust. Trackers generate self-describing events and send them to '
  name: Snowplow Tracker SDKs
  slug: snowplow-trackers
capabilities:
- description: 'Unified workflow capability for governing Snowplow behavioral data pipelines. Provides data engineers, analytics engineers, and data product managers with programmatic control over the data structure '
  name: Snowplow Data Pipeline Governance
  slug: data-pipeline-governance
common:
- title: ''
  type: Website
  url: https://snowplow.io
- title: ''
  type: Documentation
  url: https://docs.snowplow.io
- title: ''
  type: Blog
  url: https://snowplow.io/blog
- title: ''
  type: Pricing
  url: https://snowplow.io/pricing
- title: ''
  type: GitHub
  url: https://github.com/snowplow
- title: ''
  type: Login
  url: https://console.snowplowanalytics.com
- title: ''
  type: Signup
  url: https://snowplow.io/get-started
- title: ''
  type: Support
  url: https://snowplow.io/support
- title: ''
  type: GettingStarted
  url: https://docs.snowplow.io/docs/getting-started-on-snowplow-open-source
- title: ''
  type: Community
  url: https://discourse.snowplow.io
- title: ''
  type: DataStructuresAPI
  url: https://docs.snowplow.io/docs/data-product-studio/data-structures/manage/api/
- title: ''
  type: TrackingPlansAPI
  url: https://docs.snowplow.io/docs/data-product-studio/data-products/api/
- title: ''
  type: CredentialsAPI
  url: https://docs.snowplow.io/docs/account-management/
created: '2026-03-26'
description: Snowplow is a behavioral data platform that enables organizations to collect, process, and model granular event-level data from web, mobile, and server-side sources, providing a data pipeline for analytics and AI use cases. The platform uses a schema-first approach with self-describing JSON events validated against the Iglu schema registry. The Snowplow Console API provides programmatic governance of data structures (schemas), data products (tracking plans), and event specifications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Snowplow Context
  property_count: 30
  slug: snowplow-context
layout: provider
modified: '2026-05-02'
name: Snowplow
rules:
- name: Snowplow API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: snowplow-rules
skills: []
slug: snowplow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: snowplow\nname: Snowplow\ndescription: >-\n  Snowplow is a behavioral data platform that enables organizations to collect,\n  process, and model granular event-level data from web, mobile, and server-side\n  sources, providing a data pipeline for analytics and AI use cases. The platform\n  uses a schema-first approach with self-describing JSON events validated against\n  the Iglu schema registry. The Snowplow Console API provides programmatic\n  governance of data structures (schemas), data products (tracking plans), and\n  event specifications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics Platform\n  - Behavioral Data\n  - Data Collection\n  - Data Engineering\n  - Data Pipeline\n  - Event Tracking\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ snowplow:snowplow-console-api\n    name: Snowplow Console API\n    description: >-\n      The Snowplow Console API provides programmatic management of the Snowplow\n      behavioral data platform. Covers data structures (JSON schemas for event\n      validation), data products (tracking plans), event specifications, and\n      credentials. All endpoints are scoped to an organization and require JWT\n      bearer authentication. Accessible via Swagger UI at\n      https://console.snowplowanalytics.com/api/msc/v1/docs/.\n    humanURL: https://docs.snowplow.io/docs/event-studio/programmatic-management/\n    tags:\n      - Analytics Platform\n      - Data Governance\n      - Data Structures\n      - Schema Management\n    properties:\n      - type: Documentation\n        url: https://docs.snowplow.io/docs/event-studio/programmatic-management/\n      - type: SwaggerUI\n        url: https://console.snowplowanalytics.com/api/msc/v1/docs/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/openapi/snowplow-console-api-openapi.yml\n\
  \  - aid: snowplow:snowplow-trackers\n    name: Snowplow Tracker SDKs\n    description: >-\n      Snowplow provides tracker SDKs for all major platforms including JavaScript\n      (web), iOS, Android, Python, Java, Go, Ruby, .NET, PHP, and Rust. Trackers\n      generate self-describing events and send them to the Snowplow Collector.\n      All trackers support self-describing events, contexts, page views, structured\n      events, and session tracking.\n    humanURL: https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications\n    tags:\n      - Analytics\n      - Event Tracking\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications\n      - type: GitHubOrg\n        url: https://github.com/snowplow\ncommon:\n  - type: Website\n    url: https://snowplow.io\n  - type: Documentation\n    url: https://docs.snowplow.io\n  - type: Blog\n    url: https://snowplow.io/blog\n  - type:\
  \ Pricing\n    url: https://snowplow.io/pricing\n  - type: GitHub\n    url: https://github.com/snowplow\n  - type: Login\n    url: https://console.snowplowanalytics.com\n  - type: Signup\n    url: https://snowplow.io/get-started\n  - type: Support\n    url: https://snowplow.io/support\n  - type: GettingStarted\n    url: https://docs.snowplow.io/docs/getting-started-on-snowplow-open-source\n  - type: Community\n    url: https://discourse.snowplow.io\n  - type: DataStructuresAPI\n    url: https://docs.snowplow.io/docs/data-product-studio/data-structures/manage/api/\n  - type: TrackingPlansAPI\n    url: https://docs.snowplow.io/docs/data-product-studio/data-products/api/\n  - type: CredentialsAPI\n    url: https://docs.snowplow.io/docs/account-management/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/apis.yml
tags:
- Analytics Platform
- Behavioral Data
- Data Collection
- Data Engineering
- Data Pipeline
- Event Tracking
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/apis.yml
use_cases: []
---
