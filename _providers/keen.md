---
api_count: 5
api_specs:
- filename: keen-event-collection-api-openapi.yml
  format: yaml
  label: Keen Event Collection API
  slug: event-collection-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/openapi/keen-event-collection-api-openapi.yml
- filename: keen-query-api-openapi.yml
  format: yaml
  label: Keen Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/openapi/keen-query-api-openapi.yml
- filename: keen-cached-queries-api-openapi.yml
  format: yaml
  label: Keen Cached Queries API
  slug: cached-queries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/openapi/keen-cached-queries-api-openapi.yml
- filename: keen-saved-queries-api-openapi.yml
  format: yaml
  label: Keen Saved Queries API
  slug: saved-queries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/openapi/keen-saved-queries-api-openapi.yml
- filename: keen-data-extraction-api-openapi.yml
  format: yaml
  label: Keen Data Extraction API
  slug: data-extraction-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/openapi/keen-data-extraction-api-openapi.yml
apis:
- description: The Keen Event Collection API enables developers to send individual or batched events to Keen for storage and analysis. Each event is a JSON object that can contain any arbitrary properties, giving de
  name: Keen Event Collection API
  slug: event-collection-api
- description: 'The Keen Query API provides a comprehensive set of analytical query types including count, sum, average, minimum, maximum, percentile, median, count unique, select unique, funnel, and multi-analysis. '
  name: Keen Query API
  slug: query-api
- description: The Keen Cached Queries API allows developers to create, manage, and retrieve pre-defined queries that are automatically refreshed on a schedule. Cached queries improve performance for frequently acce
  name: Keen Cached Queries API
  slug: cached-queries-api
- description: The Keen Saved Queries API enables developers to create and manage reusable query definitions. Saved queries store query parameters as named resources that can be retrieved and executed later, enablin
  name: Keen Saved Queries API
  slug: saved-queries-api
- description: 'The Keen Data Extraction API enables developers to retrieve raw event data from event collections. It supports filtering, sorting, and pagination of event records and is useful for exporting data for '
  name: Keen Data Extraction API
  slug: data-extraction-api
common:
- title: ''
  type: Website
  url: https://keen.io
- title: ''
  type: Documentation
  url: https://keen.io/docs
- title: ''
  type: APIDocumentation
  url: https://keen.io/docs/api
- title: ''
  type: GettingStarted
  url: https://keen.io/docs/getting-started
- title: ''
  type: Blog
  url: https://keen.io/blog
- title: ''
  type: Pricing
  url: https://keen.io/pricing
- title: ''
  type: GitHub
  url: https://github.com/keen
- title: ''
  type: Login
  url: https://keen.io/login
- title: ''
  type: Signup
  url: https://keen.io/signup
- title: ''
  type: Support
  url: https://keen.io/support
- title: ''
  type: SDKs
  url: https://keen.io/docs/sdks
- title: ''
  type: StatusPage
  url: https://status.keen.io
- title: ''
  type: TermsOfService
  url: https://keen.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://keen.io/privacy-policy
created: '2026-03-26'
description: Keen is an event analytics platform and API that enables developers to collect, store, analyze, and visualize custom event data. It provides a flexible RESTful API for streaming events, running multi-dimensional queries, and building embedded analytics dashboards for products and internal tools.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Keen
skills: []
slug: keen
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: keen\nname: Keen\ndescription: >-\n  Keen is an event analytics platform and API that enables developers to collect,\n  store, analyze, and visualize custom event data. It provides a flexible\n  RESTful API for streaming events, running multi-dimensional queries, and\n  building embedded analytics dashboards for products and internal tools.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Custom Events\n  - Data Collection\n  - Embedded Analytics\n  - Event Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: keen:event-collection-api\n    name: Keen Event Collection API\n    description: >-\n      The Keen Event Collection API enables developers to send individual or\n      batched events to Keen for storage and analysis. Each event is a JSON\n      object\
  \ that can contain any arbitrary properties, giving developers full\n      flexibility in defining their data model. The API supports single event\n      recording, multi-event uploads across collections, and inspection of\n      existing collections and properties.\n    humanURL: https://keen.io/docs/api/#record-a-single-event\n    tags:\n      - Analytics\n      - Data Collection\n      - Events\n      - Ingestion\n    properties:\n      - type: Documentation\n        url: https://keen.io/docs/api/#record-a-single-event\n      - type: OpenAPI\n        url: openapi/keen-event-collection-api-openapi.yml\n  - aid: keen:query-api\n    name: Keen Query API\n    description: >-\n      The Keen Query API provides a comprehensive set of analytical query types\n      including count, sum, average, minimum, maximum, percentile, median,\n      count unique, select unique, funnel, and multi-analysis. Queries support\n      filters, time frames, intervals, group-by, and time zone parameters for\n\
  \      flexible multi-dimensional analysis of event data.\n    humanURL: https://keen.io/docs/api/#analyses\n    tags:\n      - Aggregation\n      - Analytics\n      - Queries\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://keen.io/docs/api/#analyses\n      - type: OpenAPI\n        url: openapi/keen-query-api-openapi.yml\n  - aid: keen:cached-queries-api\n    name: Keen Cached Queries API\n    description: >-\n      The Keen Cached Queries API allows developers to create, manage, and\n      retrieve pre-defined queries that are automatically refreshed on a\n      schedule. Cached queries improve performance for frequently accessed\n      analytics by storing pre-computed results, making them ideal for\n      powering dashboards and embedded analytics experiences.\n    humanURL: https://keen.io/docs/api/#cached-queries\n    tags:\n      - Analytics\n      - Caching\n      - Performance\n      - Queries\n    properties:\n      - type: Documentation\n\
  \        url: https://keen.io/docs/api/#cached-queries\n      - type: OpenAPI\n        url: openapi/keen-cached-queries-api-openapi.yml\n  - aid: keen:saved-queries-api\n    name: Keen Saved Queries API\n    description: >-\n      The Keen Saved Queries API enables developers to create and manage\n      reusable query definitions. Saved queries store query parameters as\n      named resources that can be retrieved and executed later, enabling\n      consistent analytics across applications and simplifying the management\n      of complex query configurations.\n    humanURL: https://keen.io/docs/api/#saved-queries\n    tags:\n      - Analytics\n      - Queries\n      - Saved Queries\n    properties:\n      - type: Documentation\n        url: https://keen.io/docs/api/#saved-queries\n      - type: OpenAPI\n        url: openapi/keen-saved-queries-api-openapi.yml\n  - aid: keen:data-extraction-api\n    name: Keen Data Extraction API\n    description: >-\n      The Keen Data Extraction API enables\
  \ developers to retrieve raw event\n      data from event collections. It supports filtering, sorting, and\n      pagination of event records and is useful for exporting data for\n      external analysis, auditing, or feeding data into other systems\n      and processing pipelines.\n    humanURL: https://keen.io/docs/api/#extractions\n    tags:\n      - Analytics\n      - Data\n      - Events\n      - Export\n    properties:\n      - type: Documentation\n        url: https://keen.io/docs/api/#extractions\n      - type: OpenAPI\n        url: openapi/keen-data-extraction-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://keen.io\n  - type: Documentation\n    url: https://keen.io/docs\n  - type: APIDocumentation\n    url: https://keen.io/docs/api\n  - type: GettingStarted\n    url: https://keen.io/docs/getting-started\n  - type: Blog\n    url: https://keen.io/blog\n  - type: Pricing\n    url: https://keen.io/pricing\n  - type: GitHub\n    url: https://github.com/keen\n  - type:\
  \ Login\n    url: https://keen.io/login\n  - type: Signup\n    url: https://keen.io/signup\n  - type: Support\n    url: https://keen.io/support\n  - type: SDKs\n    url: https://keen.io/docs/sdks\n  - type: StatusPage\n    url: https://status.keen.io\n  - type: TermsOfService\n    url: https://keen.io/terms-of-service\n  - type: PrivacyPolicy\n    url: https://keen.io/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml
tags:
- Analytics
- Custom Events
- Data Collection
- Embedded Analytics
- Event Analytics
url: https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml
use_cases: []
---
