---
api_count: 1
api_specs:
- filename: cursor-admin-api-openapi.yml
  format: yaml
  label: Cursor Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/openapi/cursor-admin-api-openapi.yml
apis:
- description: 'The Cursor Admin API allows team and enterprise administrators to programmatically manage members, billing groups, audit logs, daily usage data, spending, repository indexing blocklists, and per-user '
  name: Cursor Admin API
  slug: admin-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://cursor.com
- title: ''
  type: Documentation
  url: https://cursor.com/docs
- title: ''
  type: Pricing
  url: https://cursor.com/pricing
- title: ''
  type: Forum
  url: https://forum.cursor.com
- title: ''
  type: Changelog
  url: https://cursor.com/changelog
- title: ''
  type: JSON-LD
  url: json-ld/cursor-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cursor-member-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cursor-daily-usage-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cursor-audit-event-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cursor-vocabulary.yml
- title: ''
  type: Rules
  url: rules/cursor-admin-api-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/cursor-admin-api-capabilities.yml
created: '2026-01-02'
description: Cursor is an AI-powered code editor built on a fork of Visual Studio Code, designed to make developers extraordinarily productive by deeply integrating large language models into the editing, navigation, refactoring, and chat experience. In addition to its consumer and team plans, Cursor exposes an Admin API for enterprise customers to programmatically manage team members, billing groups, audit logs, daily usage data, spending, repo indexing blocklists, and per-user spend limits.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Cursor Context
  property_count: 0
  slug: cursor-context
layout: provider
modified: '2026-04-28'
name: Cursor
rules:
- name: Cursor API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: cursor-admin-api-rules
skills: []
slug: cursor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cursor\nname: Cursor\ndescription: >-\n  Cursor is an AI-powered code editor built on a fork of Visual Studio Code, designed\n  to make developers extraordinarily productive by deeply integrating large language\n  models into the editing, navigation, refactoring, and chat experience. In addition\n  to its consumer and team plans, Cursor exposes an Admin API for enterprise customers\n  to programmatically manage team members, billing groups, audit logs, daily usage\n  data, spending, repo indexing blocklists, and per-user spend limits.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - AI Editor\n  - Code Generation\n  - Coding Assistant\n  - Copilot\n  - Developer Tools\n  - LLM\n  - Productivity\n  - VSCode Fork\ncreated: '2026-01-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: cursor:admin-api\n  \
  \  name: Cursor Admin API\n    description: >-\n      The Cursor Admin API allows team and enterprise administrators to programmatically\n      manage members, billing groups, audit logs, daily usage data, spending, repository\n      indexing blocklists, and per-user spend limits. Authentication uses HTTP Basic\n      Authentication with the API key as the username.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cursor.com/docs/account/teams/admin-api\n    baseURL: https://api.cursor.com\n    tags:\n      - Admin\n      - Audit Logs\n      - Billing\n      - Members\n      - Spend\n      - Teams\n      - Usage\n    properties:\n      - type: Documentation\n        url: https://cursor.com/docs/account/teams/admin-api\n      - type: OpenAPI\n        url: openapi/cursor-admin-api-openapi.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Website\n    url: https://cursor.com\n  - type: Documentation\n\
  \    url: https://cursor.com/docs\n  - type: Pricing\n    url: https://cursor.com/pricing\n  - type: Forum\n    url: https://forum.cursor.com\n  - type: Changelog\n    url: https://cursor.com/changelog\n  - type: JSON-LD\n    url: json-ld/cursor-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cursor-member-schema.json\n  - type: JSONSchema\n    url: json-schema/cursor-daily-usage-schema.json\n  - type: JSONSchema\n    url: json-schema/cursor-audit-event-schema.json\n  - type: Vocabulary\n    url: vocabulary/cursor-vocabulary.yml\n  - type: Rules\n    url: rules/cursor-admin-api-rules.yml\n  - type: Capabilities\n    url: capabilities/cursor-admin-api-capabilities.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml
tags:
- AI
- AI Editor
- Code Generation
- Coding Assistant
- Copilot
- Developer Tools
- LLM
- Productivity
- VSCode Fork
url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/apis.yml
use_cases: []
---
