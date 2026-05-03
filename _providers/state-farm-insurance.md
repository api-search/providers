---
api_count: 4
api_specs:
- filename: state-farm-insurance-renters-openapi.yml
  format: yaml
  label: Renters Insurance API
  slug: renters-insurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/openapi/state-farm-insurance-renters-openapi.yml
apis:
- description: The State Farm Renters Insurance API allows property management companies, real estate platforms, and partner aggregators to embed renters insurance quoting and policy issuance directly into their wor
  name: Renters Insurance API
  slug: renters-insurance-api
- description: The State Farm Auto Insurance API enables partners in automotive, telematics, and financial services to embed State Farm auto insurance products into their platforms. Use cases include in-dealership i
  name: Auto Insurance API
  slug: auto-insurance-api
- description: The State Farm Homeowners Insurance API enables mortgage lenders, real estate platforms, and partner networks to offer homeowners insurance quoting and policy integration. Supports closing day insuran
  name: Homeowners Insurance API
  slug: homeowners-insurance-api
- description: The State Farm B2B Insurance Inquiry API provides home and auto lenders with a programmatic way to verify that borrowers maintain adequate insurance coverage on financed properties and vehicles. Lende
  name: B2B Insurance Inquiry API
  slug: b2b-insurance-inquiry-api
capabilities:
- description: Workflow capability for State Farm embedded insurance integrations. Enables property management platforms, real estate applications, and partner aggregators to embed State Farm renters insurance quoti
  name: State Farm Embedded Insurance
  slug: embedded-insurance
common:
- title: ''
  type: Website
  url: https://www.statefarm.com
- title: ''
  type: Developer Portal
  url: https://developer.statefarm.com
- title: ''
  type: GitHub
  url: https://github.com/StateFarmIns
- title: ''
  type: Engineering Blog
  url: https://engineering.statefarm.com/blog
- title: ''
  type: B2B Portal
  url: https://b2b.statefarm.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/state-farm
- title: ''
  type: Twitter
  url: https://twitter.com/StateFarm
- title: ''
  type: Newsroom
  url: https://newsroom.statefarm.com
- title: ''
  type: Privacy Policy
  url: https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.statefarm.com/customer-care/legal-disclaimer
- title: ''
  type: OpenAPI
  url: openapi/state-farm-insurance-renters-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/state-farm-insurance-renters-policy-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/state-farm-insurance-renters-policy-structure.json
- title: ''
  type: JSONLD
  url: json-ld/state-farm-insurance-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/state-farm-insurance-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/state-farm-insurance-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/embedded-insurance.yaml
created: ''
description: State Farm Insurance refers to the primary insurance operations of State Farm Mutual Automobile Insurance Company and its affiliated entities, headquartered in Bloomington, Illinois. As the largest property and casualty insurer in the United States, State Farm Insurance provides auto, home, renters, life, health, commercial, and farm insurance products to over 83 million policies across 91 million accounts. The company operates through approximately 19,000 exclusive agents and has a robust digital platform. State Farm Insurance maintains a Partner Gateway developer portal (developer.statefarm.com) offering APIs for embedded insurance, partner integrations, and B2B connectivity. The company has also heavily invested in cloud infrastructure on AWS and has open-sourced numerous DevOps and infrastructure tools via its GitHub organization.
features: []
image: ''
integrations: []
jsonld:
- class_count: 11
  name: State Farm Insurance Context
  property_count: 8
  slug: state-farm-insurance-context
layout: provider
modified: '2026-05-02'
name: State Farm Insurance
rules:
- name: State Farm Insurance API Rules
  rule_count: 15
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 5
  slug: state-farm-insurance-rules
skills: []
slug: state-farm-insurance
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: state-farm-insurance\nurl: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/apis.yml\nmodified: '2026-05-02'\nname: State Farm Insurance\ndescription: >-\n  State Farm Insurance refers to the primary insurance operations of State Farm Mutual Automobile\n  Insurance Company and its affiliated entities, headquartered in Bloomington, Illinois. As the\n  largest property and casualty insurer in the United States, State Farm Insurance provides auto,\n  home, renters, life, health, commercial, and farm insurance products to over 83 million policies\n  across 91 million accounts. The company operates through approximately 19,000 exclusive agents\n  and has a robust digital platform. State Farm Insurance maintains a Partner Gateway developer\n  portal (developer.statefarm.com) offering APIs for embedded insurance, partner integrations,\n  and B2B connectivity. The company has also heavily invested in cloud infrastructure on AWS and\n  has open-sourced\
  \ numerous DevOps and infrastructure tools via its GitHub organization.\napis:\n  - aid: state-farm-insurance:renters-insurance-api\n    name: Renters Insurance API\n    description: >-\n      The State Farm Renters Insurance API allows property management companies, real estate\n      platforms, and partner aggregators to embed renters insurance quoting and policy issuance\n      directly into their workflows. Renters can receive a customized State Farm quote without\n      leaving the partner application. State Farm is the top-ranked renters insurance provider\n      in the United States. The API supports quote requests, coverage selection, policy binding,\n      and policy status retrieval.\n    humanURL: https://developer.statefarm.com/api/renters\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Renters Insurance\n      - Embedded Insurance\n      - Property\n      - Partner\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/api/renters\n\
  \      - type: OpenAPI\n        url: openapi/state-farm-insurance-renters-openapi.yml\n\n  - aid: state-farm-insurance:auto-insurance-api\n    name: Auto Insurance API\n    description: >-\n      The State Farm Auto Insurance API enables partners in automotive, telematics, and financial\n      services to embed State Farm auto insurance products into their platforms. Use cases include\n      in-dealership insurance quoting at point of sale, connected car insurance integrations, and\n      lender-required coverage verification. State Farm is the largest auto insurer in the US with\n      over 40 million auto policies. The API supports quote generation, coverage retrieval, and\n      policy status inquiries.\n    humanURL: https://developer.statefarm.com/\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Auto Insurance\n      - Vehicles\n      - Telematics\n      - Partner\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/\n\
  \n  - aid: state-farm-insurance:homeowners-insurance-api\n    name: Homeowners Insurance API\n    description: >-\n      The State Farm Homeowners Insurance API enables mortgage lenders, real estate platforms,\n      and partner networks to offer homeowners insurance quoting and policy integration. Supports\n      closing day insurance coordination, escrow verification, and coverage inquiry for lenders\n      requiring collateral protection evidence. State Farm is one of the largest homeowners\n      insurance providers in the US.\n    humanURL: https://developer.statefarm.com/\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Homeowners Insurance\n      - Mortgage\n      - Real Estate\n      - Partner\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/\n\n  - aid: state-farm-insurance:b2b-insurance-inquiry-api\n    name: B2B Insurance Inquiry API\n    description: >-\n      The State Farm B2B Insurance Inquiry API\
  \ provides home and auto lenders with a\n      programmatic way to verify that borrowers maintain adequate insurance coverage on\n      financed properties and vehicles. Lenders can query active policy status, coverage\n      amounts, and expiration dates. This supports regulatory compliance requirements for\n      collateral insurance verification and helps lenders reduce force-placed insurance costs.\n    humanURL: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n    baseURL: https://b2b.statefarm.com/api/v1\n    tags:\n      - Insurance\n      - B2B\n      - Lenders\n      - Verification\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n\ncommon:\n  - type: Website\n    url: https://www.statefarm.com\n  - type: Developer Portal\n    url: https://developer.statefarm.com\n  - type: GitHub\n    url: https://github.com/StateFarmIns\n  - type: Engineering Blog\n    url:\
  \ https://engineering.statefarm.com/blog\n  - type: B2B Portal\n    url: https://b2b.statefarm.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/state-farm\n  - type: Twitter\n    url: https://twitter.com/StateFarm\n  - type: Newsroom\n    url: https://newsroom.statefarm.com\n  - type: Privacy Policy\n    url: https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy\n  - type: Terms of Service\n    url: https://www.statefarm.com/customer-care/legal-disclaimer\n  - type: OpenAPI\n    url: openapi/state-farm-insurance-renters-openapi.yml\n  - type: JSONSchema\n    url: json-schema/state-farm-insurance-renters-policy-schema.json\n  - type: JSONStructure\n    url: json-structure/state-farm-insurance-renters-policy-structure.json\n  - type: JSONLD\n    url: json-ld/state-farm-insurance-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/state-farm-insurance-vocabulary.yml\n  - type: SpectralRules\n    url: rules/state-farm-insurance-rules.yml\n\
  \  - type: NaftikoCapabilities\n    url: capabilities/embedded-insurance.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/apis.yml
use_cases: []
---
