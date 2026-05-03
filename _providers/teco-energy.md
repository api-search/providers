---
api_count: 3
api_specs:
- filename: teco-energy-outage-openapi.yml
  format: yaml
  label: Tampa Electric Outage API
  slug: outage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/openapi/teco-energy-outage-openapi.yml
- filename: teco-energy-account-openapi.yml
  format: yaml
  label: Tampa Electric Account API
  slug: account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/openapi/teco-energy-account-openapi.yml
apis:
- description: Tampa Electric provides a developer portal powered by Azure API Management at developer.tecoenergy.com. The portal enables developers to discover APIs, review documentation, try APIs interactively, an
  name: Tampa Electric API Management
  slug: developer-api
- description: Tampa Electric exposes outage reporting and outage map data through its customer portal and API infrastructure. The outage map at account.tecoenergy.com/Outage/Outagemap enables customers to report an
  name: Tampa Electric Outage API
  slug: outage-api
- description: Tampa Electric provides customer account management services including bill payment, usage history, paperless billing enrollment, service transfers, and energy audit tools. These customer-facing servi
  name: Tampa Electric Account API
  slug: account-api
capabilities:
- description: Unified utility operations capability for Tampa Electric (TECO Energy), combining outage management and account services into a single workflow. Enables customer service agents, field operations teams
  name: Tampa Electric Utility Operations
  slug: utility-operations
common:
- title: ''
  type: Website
  url: https://www.tecoenergy.com
- title: ''
  type: DeveloperPortal
  url: https://developer.tecoenergy.com/
- title: ''
  type: Website
  url: https://www.tampaelectric.com/
- title: ''
  type: Portal
  url: https://account.tecoenergy.com/
- title: ''
  type: Status
  url: https://account.tecoenergy.com/Outage/Outagemap
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/teco-energy
created: '2026-03-24'
description: TECO Energy is an energy holding company and subsidiary of Emera Inc., operating Tampa Electric (electric utility serving west central Florida) and Peoples Gas (natural gas utility serving Florida). TECO Energy provides a developer portal powered by Azure API Management at developer.tecoenergy.com, exposing APIs for outage management, account services, energy usage, billing, and grid operations. Tampa Electric serves approximately 800,000 customers across the Tampa Bay area and parts of central Florida.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 36
  name: Teco Energy Context
  property_count: 0
  slug: teco-energy-context
layout: provider
modified: '2026-05-03'
name: TECO Energy
rules:
- name: TECO Energy API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 5
  slug: teco-energy-rules
skills: []
slug: teco-energy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: teco-energy\nname: TECO Energy\ndescription: >-\n  TECO Energy is an energy holding company and subsidiary of Emera Inc.,\n  operating Tampa Electric (electric utility serving west central Florida) and\n  Peoples Gas (natural gas utility serving Florida). TECO Energy provides a\n  developer portal powered by Azure API Management at developer.tecoenergy.com,\n  exposing APIs for outage management, account services, energy usage, billing,\n  and grid operations. Tampa Electric serves approximately 800,000 customers\n  across the Tampa Bay area and parts of central Florida.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Energy\n  - Utilities\n  - Electric\n  - Natural Gas\n  - Smart Grid\n  - Tampa Bay\nurl: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: teco-energy:developer-api\n\
  \    name: Tampa Electric API Management\n    description: >-\n      Tampa Electric provides a developer portal powered by Azure API Management\n      at developer.tecoenergy.com. The portal enables developers to discover\n      APIs, review documentation, try APIs interactively, and sign up for API\n      keys. APIs likely include outage management, account services, energy\n      usage data, billing, and grid operations. Authentication is required to\n      access the full API catalog.\n    humanURL: https://developer.tecoenergy.com/\n    baseURL: https://developer.tecoenergy.com\n    tags:\n      - Electric Utility\n      - Energy\n      - API Management\n      - Azure\n      - Tampa Electric\n    properties:\n      - type: Documentation\n        url: https://developer.tecoenergy.com/\n      - type: DeveloperPortal\n        url: https://developer.tecoenergy.com/\n  - aid: teco-energy:outage-api\n    name: Tampa Electric Outage API\n    description: >-\n      Tampa Electric exposes outage\
  \ reporting and outage map data through its\n      customer portal and API infrastructure. The outage map at\n      account.tecoenergy.com/Outage/Outagemap enables customers to report and\n      track power outages, serving as the foundation for utility outage\n      management APIs covering outage creation, status, restoration times,\n      and affected customer counts.\n    humanURL: https://account.tecoenergy.com/Outage/Outagemap\n    baseURL: https://account.tecoenergy.com\n    tags:\n      - Outage\n      - Electric Utility\n      - Grid Operations\n      - Reliability\n    properties:\n      - type: Documentation\n        url: https://account.tecoenergy.com/Outage/Outagemap\n      - type: OpenAPI\n        url: openapi/teco-energy-outage-openapi.yml\n      - type: JSONSchema\n        url: json-schema/teco-energy-outage-schema.json\n  - aid: teco-energy:account-api\n    name: Tampa Electric Account API\n    description: >-\n      Tampa Electric provides customer account management\
  \ services including\n      bill payment, usage history, paperless billing enrollment, service\n      transfers, and energy audit tools. These customer-facing services are\n      backed by account APIs enabling programmatic access to billing data,\n      account status, payment history, and energy efficiency recommendations\n      for residential and commercial customers.\n    humanURL: https://account.tecoenergy.com/\n    baseURL: https://account.tecoenergy.com\n    tags:\n      - Account Management\n      - Billing\n      - Energy Usage\n      - Customer Service\n    properties:\n      - type: Documentation\n        url: https://account.tecoenergy.com/\n      - type: OpenAPI\n        url: openapi/teco-energy-account-openapi.yml\n      - type: JSONSchema\n        url: json-schema/teco-energy-account-schema.json\ncommon:\n  - url: https://www.tecoenergy.com\n    name: TECO Energy\n    type: Website\n    description: Main corporate website for TECO Energy.\n  - url: https://developer.tecoenergy.com/\n\
  \    name: Tampa Electric API Developer Portal\n    type: DeveloperPortal\n    description: Azure API Management developer portal for Tampa Electric APIs.\n  - url: https://www.tampaelectric.com/\n    name: Tampa Electric\n    type: Website\n    description: Tampa Electric subsidiary website.\n  - url: https://account.tecoenergy.com/\n    name: TECO Account Portal\n    type: Portal\n    description: Customer account management portal for billing and usage.\n  - url: https://account.tecoenergy.com/Outage/Outagemap\n    name: Tampa Electric Outage Map\n    type: Status\n    description: Real-time outage map for Tampa Electric service territory.\n  - url: https://www.linkedin.com/company/teco-energy\n    name: TECO Energy on LinkedIn\n    type: LinkedIn\n    description: TECO Energy LinkedIn company page.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml
tags:
- Energy
- Utilities
- Electric
- Natural Gas
- Smart Grid
- Tampa Bay
url: https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml
use_cases: []
---
