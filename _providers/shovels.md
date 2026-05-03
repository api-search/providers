---
api_count: 1
api_specs:
- filename: shovels-openapi.yml
  format: yaml
  label: Shovels API
  slug: shovels-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/openapi/shovels-openapi.yml
apis:
- description: The Shovels API v2 provides programmatic access to building permit intelligence and contractor data from 1,800+ US jurisdictions. Access 130M+ permits, 2.3M+ contractor profiles, geographic metrics, r
  name: Shovels API
  slug: shovels-api
capabilities:
- description: 'Workflow capability for identifying qualified contractors, researching their work history, accessing decision maker contacts, and analyzing market activity. Combines permit search, contractor search, '
  name: Shovels Contractor Intelligence
  slug: contractor-intelligence
common: []
created: '2026-05-02'
description: Shovels is the intelligence layer for the built world, providing building permit data and contractor intelligence aggregated from 1,800+ jurisdictions across the United States. The platform offers 130M+ building permits, 2.3M+ contractor profiles, property details, resident information, and geographic market metrics. Shovels helps materials suppliers, construction tech companies, energy and climate firms, home services companies, real estate professionals, and telecommunications providers identify qualified contractors, understand work history, and power sales and marketing with rich permit data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Shovels Context
  property_count: 13
  slug: shovels-context
layout: provider
modified: '2026-05-02'
name: Shovels
rules:
- name: Shovels API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: shovels-rules
skills: []
slug: shovels
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shovels\nname: Shovels\ndescription: >-\n  Shovels is the intelligence layer for the built world, providing building\n  permit data and contractor intelligence aggregated from 1,800+ jurisdictions\n  across the United States. The platform offers 130M+ building permits,\n  2.3M+ contractor profiles, property details, resident information, and\n  geographic market metrics. Shovels helps materials suppliers, construction\n  tech companies, energy and climate firms, home services companies, real\n  estate professionals, and telecommunications providers identify qualified\n  contractors, understand work history, and power sales and marketing with\n  rich permit data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Construction\n  - Building Permits\n  - Contractors\n  - Real Estate\n  - Property Data\n  - Market Intelligence\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: shovels:shovels-api\n    name: Shovels API\n    description: >-\n      The Shovels API v2 provides programmatic access to building permit\n      intelligence and contractor data from 1,800+ US jurisdictions. Access\n      130M+ permits, 2.3M+ contractor profiles, geographic metrics, resident\n      data, and market analytics. Authentication uses an X-API-Key header.\n      Supports cursor-based pagination, credit tracking, and advanced filtering\n      by geography, date range, tags, job value, property type, and contractor\n      attributes. Data refreshes on the 1st and 15th of each month.\n    humanURL: https://www.shovels.ai/api\n    baseURL: https://api.shovels.ai/v2\n    tags:\n      - Construction\n      - Building Permits\n      - Contractors\n      - Property Data\n      - Market Intelligence\n      - Real Estate\n    properties:\n      - type: Documentation\n        url: https://docs.shovels.ai\n\
  \      - type: GettingStarted\n        url: https://docs.shovels.ai/docs/shovels-api-introduction\n      - type: Authentication\n        url: https://docs.shovels.ai/docs/shovels-api-introduction\n      - type: Pricing\n        url: https://www.shovels.ai/pricing\n      - type: SignUp\n        url: https://app.shovels.ai\n      - type: GitHubOrganization\n        url: https://github.com/ShovelsAI\n      - type: OpenAPI\n        url: openapi/shovels-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shovels-permit-schema.json\n      - type: JSONSchema\n        url: json-schema/shovels-contractor-schema.json\n      - type: JSONStructure\n        url: json-structure/shovels-permit-structure.json\n      - type: JSONLD\n        url: json-ld/shovels-context.jsonld\n      - type: SpectralRules\n        url: rules/shovels-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/contractor-intelligence.yaml\n      - type: Vocabulary\n        url: vocabulary/shovels-vocabulary.yml\n\
  \    contact:\n      - FN: Shovels Support\n        url: https://docs.shovels.ai\n        email: sales@shovels.ai\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/apis.yml
tags:
- Construction
- Building Permits
- Contractors
- Real Estate
- Property Data
- Market Intelligence
url: https://raw.githubusercontent.com/api-evangelist/shovels/refs/heads/main/apis.yml
use_cases: []
---
