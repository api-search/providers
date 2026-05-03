---
api_count: 1
api_specs:
- filename: stacker-openapi.yml
  format: yaml
  label: Stacker API
  slug: stacker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/openapi/stacker-openapi.yml
apis:
- description: The Stacker API provides programmatic access to objects, records, accounts, and stacks within the Stacker platform. It enables external integrations, automation workflows, and data operations across S
  name: Stacker API
  slug: stacker-api
capabilities:
- description: Unified workflow capability for managing data within Stacker no-code applications. Covers account and stack discovery, object (table) inspection, and full record lifecycle operations including search,
  name: Stacker Data Management
  slug: data-management
common:
- title: ''
  type: Website
  url: https://stacker.ai/
- title: ''
  type: Documentation
  url: https://docs.stackerhq.com/
- title: ''
  type: GettingStarted
  url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview
- title: ''
  type: Authentication
  url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview/authentication
- title: ''
  type: Pricing
  url: https://stacker.ai/pricing
- title: ''
  type: Blog
  url: https://stacker.ai/blog
- title: ''
  type: Login
  url: https://app.stackerhq.com/
created: '2025-01-01'
description: Stacker is a no-code platform that enables organizations to build custom business applications, internal tools, and customer portals on top of their existing data sources — including Airtable, Google Sheets, SQL databases, and Salesforce — without writing code. Its drag-and-drop interface, role-based access controls, and Open API enable teams to create data-driven portals, automate workflows, and integrate with third-party services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Stacker Context
  property_count: 3
  slug: stacker-context
layout: provider
modified: '2026-05-02'
name: Stacker
rules:
- name: Stacker API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: stacker-rules
skills: []
slug: stacker
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stacker\nname: Stacker\ndescription: >-\n  Stacker is a no-code platform that enables organizations to build custom\n  business applications, internal tools, and customer portals on top of their\n  existing data sources — including Airtable, Google Sheets, SQL databases, and\n  Salesforce — without writing code. Its drag-and-drop interface, role-based\n  access controls, and Open API enable teams to create data-driven portals,\n  automate workflows, and integrate with third-party services.\nurl: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Development\n  - Low-Code\n  - No-Code\n  - Portals\n  - Workflow Automation\ntype: Index\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stacker:stacker-api\n    name: Stacker API\n    description: >-\n      The Stacker API provides\
  \ programmatic access to objects, records, accounts,\n      and stacks within the Stacker platform. It enables external integrations,\n      automation workflows, and data operations across Stacker applications using\n      token-based authentication.\n    humanURL: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview\n    baseURL: https://api.go.stackerhq.com\n    tags:\n      - No-Code\n      - Records\n      - Application Development\n    properties:\n      - type: Documentation\n        url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview\n      - type: Authentication\n        url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview/authentication\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/openapi/stacker-openapi.yml\ncommon:\n  - type: Website\n    url: https://stacker.ai/\n    name: Stacker - No-Code Platform\n  - type: Documentation\n    url: https://docs.stackerhq.com/\n\
  \    name: Stacker Documentation\n  - type: GettingStarted\n    url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview\n    name: Open API Overview\n  - type: Authentication\n    url: https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview/authentication\n    name: API Authentication\n  - type: Pricing\n    url: https://stacker.ai/pricing\n    name: Stacker Pricing\n  - type: Blog\n    url: https://stacker.ai/blog\n    name: Stacker Blog\n  - type: Login\n    url: https://app.stackerhq.com/\n    name: Stacker App Login\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/apis.yml
tags:
- Application Development
- Low-Code
- No-Code
- Portals
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/apis.yml
use_cases: []
---
