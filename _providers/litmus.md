---
api_count: 3
api_specs:
- filename: litmus-instant-openapi.yml
  format: yaml
  label: Litmus Instant API
  slug: litmus-instant-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-instant-openapi.yml
- filename: litmus-legacy-previews-openapi.yml
  format: yaml
  label: Litmus Legacy Previews API
  slug: litmus-legacy-previews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-legacy-previews-openapi.yml
- filename: litmus-email-analytics-openapi.yml
  format: yaml
  label: Litmus Email Analytics API
  slug: litmus-email-analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/openapi/litmus-email-analytics-openapi.yml
apis:
- description: The Litmus Instant API provides REST endpoints for generating email preview screenshots across 40+ email clients by submitting HTML directly without needing to send an actual email. It is used by emai
  name: Litmus Instant API
  slug: litmus-instant-api
- description: The Litmus Legacy Previews API provides REST endpoints for running email preview tests, spam filter tests, link-check tests, and code analysis against submitted email HTML. Tests are initiated by POST
  name: Litmus Legacy Previews API
  slug: litmus-legacy-previews-api
- description: The Litmus Email Analytics API provides REST endpoints for retrieving email campaign engagement metrics including read rates, deletion rates, device types, email clients, geographic data, and forwardi
  name: Litmus Email Analytics API
  slug: litmus-email-analytics-api
common:
- title: ''
  type: Website
  url: https://www.litmus.com/
- title: ''
  type: Documentation
  url: https://docs.litmus.com/
- title: ''
  type: Getting Started
  url: https://www.litmus.com/getting-started/test-your-email
- title: ''
  type: Blog
  url: https://www.litmus.com/blog/
- title: ''
  type: Community
  url: https://litmus.com/community
- title: ''
  type: Authentication
  url: https://docs.litmus.com/oauth-integration-guide
- title: ''
  type: Authentication
  url: https://docs.litmus.com/oauth/web-application-flow
- title: ''
  type: JSONSchema
  url: json-schema/litmus-email-test-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/litmus-context.jsonld
created: '2025-01-01'
description: Email testing and analytics platform that allows developers and marketers to preview, test, and analyze email campaigns across multiple email clients and devices before sending.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Litmus Context
  property_count: 46
  slug: litmus-context
layout: provider
modified: '2026-03-18'
name: Litmus
skills: []
slug: litmus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: litmus\nname: Litmus\ndescription: >-\n  Email testing and analytics platform that allows developers and marketers\n  to preview, test, and analyze email campaigns across multiple email clients\n  and devices before sending.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Tools\n  - Email Testing\n  - Marketing Tools\n  - Quality Assurance\nurl: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: litmus:litmus-instant-api\n    name: Litmus Instant API\n    description: >-\n      The Litmus Instant API provides REST endpoints for generating email\n      preview screenshots across 40+ email clients by submitting HTML\n      directly without needing to send an actual email. It is used by email\n      editors and ESP integrations to deliver real-time rendering previews\n      within their\
  \ own platforms.\n    humanURL: https://docs.litmus.com/instant\n    baseURL: https://instant-api.litmus.com/v1\n    tags:\n      - Email Clients\n      - Email Testing\n      - Previews\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.litmus.com/instant\n      - type: Authentication\n        url: https://docs.litmus.com/oauth-integration-guide\n      - type: OpenAPI\n        url: openapi/litmus-instant-openapi.yml\n  - aid: litmus:litmus-legacy-previews-api\n    name: Litmus Legacy Previews API\n    description: >-\n      The Litmus Legacy Previews API provides REST endpoints for running\n      email preview tests, spam filter tests, link-check tests, and code\n      analysis against submitted email HTML. Tests are initiated by POSTing\n      to the API and results are polled until rendering is complete.\n    humanURL: https://docs.litmus.com/legacy-previews\n    baseURL: https://previews-api.litmus.com/api/v1\n    tags:\n      - Email Testing\n\
  \      - Previews\n      - REST API\n      - Spam Testing\n    properties:\n      - type: Documentation\n        url: https://docs.litmus.com/legacy-previews\n      - type: OpenAPI\n        url: openapi/litmus-legacy-previews-openapi.yml\n  - aid: litmus:litmus-email-analytics-api\n    name: Litmus Email Analytics API\n    description: >-\n      The Litmus Email Analytics API provides REST endpoints for retrieving\n      email campaign engagement metrics including read rates, deletion rates,\n      device types, email clients, geographic data, and forwarding activity.\n      Campaign data is accessed by GUID and returns detailed activity summary\n      reports.\n    humanURL: https://docs.litmus.com/email-analytics\n    baseURL: https://analytics-api.litmus.com/api/v1\n    tags:\n      - Campaign Metrics\n      - Email Analytics\n      - Reporting\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.litmus.com/email-analytics\n      - type: OpenAPI\n\
  \        url: openapi/litmus-email-analytics-openapi.yml\ncommon:\n  - url: https://www.litmus.com/\n    type: Website\n  - url: https://docs.litmus.com/\n    type: Documentation\n  - url: https://www.litmus.com/getting-started/test-your-email\n    type: Getting Started\n  - url: https://www.litmus.com/blog/\n    type: Blog\n  - url: https://litmus.com/community\n    type: Community\n  - url: https://docs.litmus.com/oauth-integration-guide\n    type: Authentication\n  - url: https://docs.litmus.com/oauth/web-application-flow\n    type: Authentication\n  - type: JSONSchema\n    url: json-schema/litmus-email-test-schema.json\n    name: Litmus Email Test JSON Schema\n    description: JSON Schema for Litmus email test objects covering preview, spam filter, and link-check test requests and results.\n  - type: JSON-LD\n    url: json-ld/litmus-context.jsonld\n    name: Litmus JSON-LD Context\n    description: Linked data context mapping Litmus email test and campaign entities to standard vocabularies.\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml
tags:
- Developer Tools
- Email Testing
- Marketing Tools
- Quality Assurance
url: https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml
use_cases: []
---
