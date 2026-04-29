---
api_count: 1
apis:
- description: 'Knit''s unified API provides standardized endpoints for connecting with multiple HR, recruitment, and chat tools in one integration. Access employee data, departments, locations, time-off records, job '
  name: Knit Unified API
  slug: unified-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developers.getknit.dev/
- title: ''
  type: Documentation
  url: https://developers.getknit.dev/
- title: ''
  type: JSONSchema
  url: json-schema/knit-unified-api-schema.json
- title: ''
  type: JSONLD
  url: json-ld/knit-context.jsonld
created: '2026-03-16'
description: Knit is a unified API platform for B2B products, AI agents, and MCP clients, providing integrations infrastructure for HR, recruitment, and collaboration tools. Knit manages cron jobs, rate limits, and retries out of the box for predictable data syncing at scale.
features:
- Unified API for multiple HRIS and ATS platforms
- Automatic cron job management for data syncing
- Built-in rate limiting and retry logic
- Standardized data models across providers
- MCP client and AI agent support
- Real-time webhook notifications
- Incremental sync with updated_after filtering
image: /assets/icons/knit.png
integrations:
- BambooHR
- Gusto
- Workday
- ADP
- Rippling
- Greenhouse
- Lever
- Slack
- Microsoft Teams
jsonld:
- class_count: 0
  name: Knit Context
  property_count: 5
  slug: knit-context
layout: provider
modified: '2026-04-18'
name: Knit
skills: []
slug: knit
solutions: []
source_yaml: "aid: knit\nname: Knit\ndescription: >-\n  Knit is a unified API platform for B2B products, AI agents, and MCP clients,\n  providing integrations infrastructure for HR, recruitment, and collaboration\n  tools. Knit manages cron jobs, rate limits, and retries out of the box for\n  predictable data syncing at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - B2B\n  - HR Integrations\n  - HRIS\n  - Unified API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: knit:unified-api\n    name: Knit Unified API\n    description: >-\n      Knit's unified API provides standardized endpoints for connecting with\n      multiple HR, recruitment, and chat tools in one integration. Access employee\n      data, departments, locations, time-off records, job postings, and sync\n      statuses through\
  \ a single normalized interface.\n    humanURL: https://developers.getknit.dev/\n    baseURL: https://api.getknit.dev/v1\n    tags:\n      - Employees\n      - HR\n      - Integrations\n      - Recruitment\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://developers.getknit.dev/\n      - type: OpenAPI\n        url: openapi/knit-unified-api-openapi.yml\n      - type: GettingStarted\n        url: https://developers.getknit.dev/\n    contact:\n      - type: Support\n        url: https://www.getknit.dev/\ncommon:\n  - type: Portal\n    url: https://developers.getknit.dev/\n  - type: Documentation\n    url: https://developers.getknit.dev/\n  - type: Features\n    data:\n      - Unified API for multiple HRIS and ATS platforms\n      - Automatic cron job management for data syncing\n      - Built-in rate limiting and retry logic\n      - Standardized data models across providers\n      - MCP client and AI agent support\n      - Real-time webhook notifications\n\
  \      - Incremental sync with updated_after filtering\n  - type: UseCases\n    data:\n      - Synchronizing employee data across HR platforms\n      - Building B2B integrations without managing individual provider APIs\n      - Powering AI agents with unified HR and recruitment data\n      - Automating onboarding workflows across HRIS systems\n      - Aggregating time-off and attendance data from multiple providers\n  - type: Integrations\n    data:\n      - BambooHR\n      - Gusto\n      - Workday\n      - ADP\n      - Rippling\n      - Greenhouse\n      - Lever\n      - Slack\n      - Microsoft Teams\n  - type: JSONSchema\n    url: json-schema/knit-unified-api-schema.json\n  - type: JSONLD\n    url: json-ld/knit-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/apis.yml
tags:
- B2B
- HR Integrations
- HRIS
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/apis.yml
use_cases:
- Synchronizing employee data across HR platforms
- Building B2B integrations without managing individual provider APIs
- Powering AI agents with unified HR and recruitment data
- Automating onboarding workflows across HRIS systems
- Aggregating time-off and attendance data from multiple providers
---
