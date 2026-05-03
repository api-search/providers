---
api_count: 1
api_specs:
- filename: salesloft-openapi.yml
  format: yaml
  label: Salesloft API
  slug: salesloft-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/openapi/salesloft-openapi.yml
apis:
- description: The Salesloft REST API provides programmatic access to Salesloft platform data including accounts, people, cadences, calls, emails, tasks, opportunities, and analytics. Uses OAuth 2.0 and Bearer token
  name: Salesloft API
  slug: salesloft-api
capabilities:
- description: Revenue intelligence workflow combining calls, conversations, signals, and opportunities to provide pipeline visibility and AI-driven coaching insights. Used by sales managers and revenue leaders to m
  name: Salesloft Revenue Intelligence
  slug: revenue-intelligence
- description: Sales engagement workflow combining account and people management with cadence enrollment. Used by sales reps to discover accounts, add prospects, and enroll them in structured outreach sequences to d
  name: Salesloft Sales Engagement
  slug: sales-engagement
common:
- title: ''
  type: Website
  url: https://www.salesloft.com
- title: ''
  type: Portal
  url: https://developers.salesloft.com
- title: ''
  type: Documentation
  url: https://developers.salesloft.com/docs/api/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SalesLoft
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/salesloft-dev/salesloft/overview
- title: ''
  type: Marketplace
  url: https://marketplace.salesloft.com/
- title: ''
  type: Blog
  url: https://www.salesloft.com/resources/blog
- title: ''
  type: Pricing
  url: https://www.salesloft.com/pricing
- title: ''
  type: CaseStudies
  url: https://www.salesloft.com/resources/case-studies
- title: ''
  type: Events
  url: https://www.salesloft.com/events
- title: ''
  type: Status
  url: https://status.salesloft.com/
- title: ''
  type: Governance
  url: https://www.salesloft.com/platform/governance
- title: ''
  type: Security
  url: https://www.salesloft.com/security-compliance
- title: ''
  type: Login
  url: https://accounts.salesloft.com/sign_in
- title: ''
  type: Webhooks
  url: https://developers.salesloft.com/docs/platform/webhooks/
- title: ''
  type: Changelog
  url: https://developers.salesloft.com/docs/platform/changelog/
created: '2025-02-09'
description: Salesloft delivers a performance force multiplier for the world's most demanding companies. Salesloft's Revenue Orchestration Platform, delivering the first AI-powered durable revenue engagement model, keeps market-facing teams on top of all buyer signals, with outcomes-driven prioritization so they always act first on what matters most.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Salesloft Context
  property_count: 5
  slug: salesloft-context
layout: provider
modified: '2026-05-02'
name: Salesloft
rules:
- name: Salesloft API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 4
    info: 0
    warn: 5
  slug: salesloft-rules
skills: []
slug: salesloft
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salesloft\nurl: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/apis.yml\nname: Salesloft\ndescription: >-\n  Salesloft delivers a performance force multiplier for the world's most demanding\n  companies. Salesloft's Revenue Orchestration Platform, delivering the first AI-powered\n  durable revenue engagement model, keeps market-facing teams on top of all buyer\n  signals, with outcomes-driven prioritization so they always act first on what matters\n  most.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sales\n  - CRM\n  - Revenue\n  - Automation\n  - AI\naccess: 3rd-Party\ncreated: '2025-02-09'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nspecificationVersion: '0.19'\napis:\n  - aid: salesloft:salesloft-api\n    name: Salesloft API\n    description: >-\n      The Salesloft REST API provides programmatic access to Salesloft platform data\n      including accounts, people, cadences,\
  \ calls, emails, tasks, opportunities, and\n      analytics. Uses OAuth 2.0 and Bearer token authentication. Base URL is\n      https://api.salesloft.com/v2.\n    humanURL: https://developers.salesloft.com/docs/platform/intro/\n    tags:\n      - Sales\n      - CRM\n      - Revenue Orchestration\n      - Cadences\n      - People\n    properties:\n      - type: Documentation\n        url: https://developers.salesloft.com/docs/platform/intro/\n      - type: OpenAPI\n        url: openapi/salesloft-openapi.yml\n      - type: Authentication\n        url: https://developers.salesloft.com/docs/platform/oauth-authorization-code\n      - type: Summary\n        data:\n          numberOfAPITags: 56\n          numberOfAPIGetMethods: 103\n          numberOfAPIPostMethods: 40\n          numberOfAPIPutMethods: 18\n          numberOfAPIPatchMethods: 0\n          numberOfAPIDeleteMethods: 15\n          numberOfAPIOperations: 176\n\ncommon:\n  - type: Website\n    url: https://www.salesloft.com\n  - type:\
  \ Portal\n    url: https://developers.salesloft.com\n  - type: Documentation\n    url: https://developers.salesloft.com/docs/api/\n  - type: GitHubOrganization\n    url: https://github.com/SalesLoft\n  - type: PostmanWorkspace\n    url: https://www.postman.com/salesloft-dev/salesloft/overview\n  - type: Marketplace\n    url: https://marketplace.salesloft.com/\n  - type: Blog\n    url: https://www.salesloft.com/resources/blog\n  - type: Pricing\n    url: https://www.salesloft.com/pricing\n  - type: CaseStudies\n    url: https://www.salesloft.com/resources/case-studies\n  - type: Events\n    url: https://www.salesloft.com/events\n  - type: Status\n    url: https://status.salesloft.com/\n  - type: Governance\n    url: https://www.salesloft.com/platform/governance\n  - type: Security\n    url: https://www.salesloft.com/security-compliance\n  - type: Login\n    url: https://accounts.salesloft.com/sign_in\n  - type: Webhooks\n    url: https://developers.salesloft.com/docs/platform/webhooks/\n\
  \  - type: Changelog\n    url: https://developers.salesloft.com/docs/platform/changelog/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/apis.yml
tags:
- Sales
- CRM
- Revenue
- Automation
- AI
url: https://raw.githubusercontent.com/api-evangelist/salesloft/refs/heads/main/apis.yml
use_cases: []
---
