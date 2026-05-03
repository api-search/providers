---
api_count: 1
api_specs:
- filename: windsurf-enterprise-openapi.yml
  format: yaml
  label: Windsurf Enterprise API
  slug: windsurf-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/openapi/windsurf-enterprise-openapi.yml
apis:
- description: The Windsurf Enterprise API provides programmatic access to analytics, usage data, billing configuration, and team management for enterprise customers. It enables teams to query code completion usage,
  name: Windsurf Enterprise API
  slug: windsurf-enterprise-api
capabilities:
- description: Analytics and billing management capability for Windsurf Enterprise. Enables platform administrators to query AI code completion usage, monitor Cascade agent activity, review per-user analytics, manag
  name: Windsurf Analytics and Billing
  slug: analytics-and-billing
common:
- title: ''
  type: Website
  url: https://windsurf.com
- title: ''
  type: Documentation
  url: https://docs.windsurf.com
- title: ''
  type: APIReference
  url: https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction
- title: ''
  type: Changelog
  url: https://windsurf.com/changelog
- title: ''
  type: Blog
  url: https://windsurf.com/blog
- title: ''
  type: Pricing
  url: https://windsurf.com/pricing
- title: ''
  type: Download
  url: https://windsurf.com/download
- title: ''
  type: GitHubOrg
  url: https://github.com/Exafunction
- title: ''
  type: GitHubRepo
  url: https://github.com/Exafunction/windsurf.nvim
- title: ''
  type: VSCodeExtension
  url: https://marketplace.visualstudio.com/items?itemName=Codeium.CodeiumVS
- title: ''
  type: X
  url: https://x.com/codeiumdev
- title: ''
  type: Discord
  url: https://discord.gg/3XFf78nAx5
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/json-ld/windsurfrules-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/vocabulary/windsurfrules-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/capabilities/analytics-and-billing.yaml
created: '2025'
description: Windsurf (formerly Codeium) is an AI-native code editor featuring Cascade, an autonomous AI agent that can plan multi-step code changes, execute terminal commands, read linter output, and modify files across entire projects. The .windsurfrules file format provides project-specific configuration for the Cascade AI assistant, defining coding conventions, standards, and behavioral instructions. Windsurf offers an Enterprise API for querying code completion analytics, Cascade AI usage, billing configuration, and team management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Windsurfrules Context
  property_count: 13
  slug: windsurfrules-context
layout: provider
modified: '2026-05-03'
name: Windsurf
rules:
- name: Windsurf API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: windsurf-enterprise-rules
skills: []
slug: windsurfrules
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: windsurfrules\nname: Windsurf\ndescription: >-\n  Windsurf (formerly Codeium) is an AI-native code editor featuring Cascade,\n  an autonomous AI agent that can plan multi-step code changes, execute terminal\n  commands, read linter output, and modify files across entire projects. The\n  .windsurfrules file format provides project-specific configuration for the\n  Cascade AI assistant, defining coding conventions, standards, and behavioral\n  instructions. Windsurf offers an Enterprise API for querying code completion\n  analytics, Cascade AI usage, billing configuration, and team management.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Agents\n  - AI Copilot\n  - Coding Standards\n  - Developer Workflow\n  - IDE\n  - Windsurf\ncreated: '2025'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: windsurfrules:windsurf-enterprise-api\n    name: Windsurf Enterprise API\n    description: >-\n      The Windsurf Enterprise API provides programmatic access to analytics,\n      usage data, billing configuration, and team management for enterprise\n      customers. It enables teams to query code completion usage, Cascade AI\n      analytics, billing configurations, and credit balances. Available for\n      Enterprise plans only. Authentication uses service keys.\n    humanURL: https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction\n    baseURL: https://server.codeium.com/api/v1\n    tags:\n      - AI Analytics\n      - Enterprise\n      - Billing\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/openapi/windsurf-enterprise-openapi.yml\n\
  common:\n  - type: Website\n    url: https://windsurf.com\n  - type: Documentation\n    url: https://docs.windsurf.com\n  - type: APIReference\n    url: https://docs.windsurf.com/plugins/accounts/api-reference/api-introduction\n  - type: Changelog\n    url: https://windsurf.com/changelog\n  - type: Blog\n    url: https://windsurf.com/blog\n  - type: Pricing\n    url: https://windsurf.com/pricing\n  - type: Download\n    url: https://windsurf.com/download\n  - type: GitHubOrg\n    url: https://github.com/Exafunction\n  - type: GitHubRepo\n    url: https://github.com/Exafunction/windsurf.nvim\n  - type: VSCodeExtension\n    url: https://marketplace.visualstudio.com/items?itemName=Codeium.CodeiumVS\n  - type: X\n    url: https://x.com/codeiumdev\n  - type: Discord\n    url: https://discord.gg/3XFf78nAx5\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/json-ld/windsurfrules-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/vocabulary/windsurfrules-vocabulary.yml\n\
  \  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/capabilities/analytics-and-billing.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/apis.yml
tags:
- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- IDE
- Windsurf
url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/apis.yml
use_cases: []
---
