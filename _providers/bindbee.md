---
api_count: 1
apis:
- description: Unified HRIS and ATS integration API for connecting with multiple HR systems through a single integration.
  name: Bindbee API
  slug: bindbee-api
capabilities:
- description: ''
  name: Hr Integration
  slug: hr-integration
common:
- title: ''
  type: Portal
  url: https://bindbee.dev/
- title: ''
  type: Documentation
  url: https://docs.bindbee.dev/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/rules/bindbee-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/vocabulary/bindbee-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/capabilities/hr-integration.yaml
created: '2026-03-16'
description: Bindbee provides a unified HRIS and ATS integration API that allows companies to connect with multiple HR systems through a single integration, simplifying workforce data access and HR automation.
features:
- description: Access employee data from BambooHR, Workday, ADP, and 50+ HRIS systems through one API.
  name: Unified HRIS API
- description: Access job listings and candidates from Greenhouse, Lever, Workable, and other ATS systems.
  name: Unified ATS API
- description: Consistent normalized schema across all connected HR systems.
  name: Data Normalization
- description: Efficient cursor-based pagination for large employee datasets.
  name: Cursor Pagination
- description: Secure per-integration connector tokens for multi-tenant HR data access.
  name: Connector Tokens
- description: Webhooks and polling for real-time HR data synchronization.
  name: Real-Time Sync
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sync employee data from BambooHR via Bindbee unified API.
  name: BambooHR
- description: Access Workday employee and org data through normalized Bindbee API.
  name: Workday
- description: Connect ADP Workforce Now employee records via Bindbee.
  name: ADP
- description: Access Greenhouse ATS job listings and candidates via Bindbee.
  name: Greenhouse
- description: Sync Lever ATS recruiting pipeline data through Bindbee.
  name: Lever
jsonld:
- class_count: 10
  name: Bindbee Context
  property_count: 12
  slug: bindbee-context
layout: provider
modified: '2026-04-21'
name: Bindbee
rules:
- name: Bindbee API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 16
  slug: bindbee-spectral-rules
skills: []
slug: bindbee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bindbee\nname: Bindbee\ndescription: >-\n  Bindbee provides a unified HRIS and ATS integration API that allows companies\n  to connect with multiple HR systems through a single integration, simplifying\n  workforce data access and HR automation.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- ATS\n- HR Integration\n- HRIS\n- Workforce\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n- aid: bindbee:bindbee-api\n  name: Bindbee API\n  description: >-\n    Unified HRIS and ATS integration API for connecting with multiple\n    HR systems through a single integration.\n  humanURL: https://bindbee.dev/\n  tags:\n  - ATS\n  - HR Integration\n  - HRIS\n  properties:\n  - type: Documentation\n    url: https://docs.bindbee.dev/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/openapi/bindbee-api.yaml\n\
  common:\n- type: Portal\n  url: https://bindbee.dev/\n- type: Documentation\n  url: https://docs.bindbee.dev/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/rules/bindbee-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/vocabulary/bindbee-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/capabilities/hr-integration.yaml\n- type: Features\n  data:\n  - name: Unified HRIS API\n    description: Access employee data from BambooHR, Workday, ADP, and 50+ HRIS systems through one API.\n  - name: Unified ATS API\n    description: Access job listings and candidates from Greenhouse, Lever, Workable, and other ATS systems.\n  - name: Data Normalization\n    description: Consistent normalized schema across all connected HR systems.\n  - name: Cursor Pagination\n    description: Efficient cursor-based\
  \ pagination for large employee datasets.\n  - name: Connector Tokens\n    description: Secure per-integration connector tokens for multi-tenant HR data access.\n  - name: Real-Time Sync\n    description: Webhooks and polling for real-time HR data synchronization.\n- type: UseCases\n  data:\n  - name: Employee Directory Integration\n    description: Sync employee records from any HRIS into internal apps and directories.\n  - name: Onboarding Automation\n    description: Trigger onboarding workflows when new employees are added in the HRIS.\n  - name: Recruiting Pipeline Visibility\n    description: Track candidates across ATS stages in unified dashboards.\n  - name: HRIS Migration\n    description: Move between HRIS providers without rewriting integrations.\n  - name: HR Analytics\n    description: Aggregate people data from multiple HR systems for workforce analytics.\n- type: Integrations\n  data:\n  - name: BambooHR\n    description: Sync employee data from BambooHR via Bindbee unified\
  \ API.\n  - name: Workday\n    description: Access Workday employee and org data through normalized Bindbee API.\n  - name: ADP\n    description: Connect ADP Workforce Now employee records via Bindbee.\n  - name: Greenhouse\n    description: Access Greenhouse ATS job listings and candidates via Bindbee.\n  - name: Lever\n    description: Sync Lever ATS recruiting pipeline data through Bindbee.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\naccess: 3rd-Party\nposition: Consuming\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/apis.yml
tags:
- ATS
- HR Integration
- HRIS
- Workforce
url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/apis.yml
use_cases:
- description: Sync employee records from any HRIS into internal apps and directories.
  name: Employee Directory Integration
- description: Trigger onboarding workflows when new employees are added in the HRIS.
  name: Onboarding Automation
- description: Track candidates across ATS stages in unified dashboards.
  name: Recruiting Pipeline Visibility
- description: Move between HRIS providers without rewriting integrations.
  name: HRIS Migration
- description: Aggregate people data from multiple HR systems for workforce analytics.
  name: HR Analytics
---
