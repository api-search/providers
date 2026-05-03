---
api_count: 3
api_specs:
- filename: state-farm-renters-insurance-openapi.yml
  format: yaml
  label: Renters Insurance API
  slug: renters-insurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/openapi/state-farm-renters-insurance-openapi.yml
apis:
- description: The State Farm Renters Insurance API enables partner platforms, real estate applications, and property management systems to offer embedded renters insurance quotes and policies to tenants. Partners c
  name: Renters Insurance API
  slug: renters-insurance-api
- description: The State Farm Auto Insurance API supports partner integrations for automobile insurance quoting, policy management, and claims inquiry. This API enables auto dealers, telematics platforms, and financ
  name: Auto Insurance API
  slug: auto-insurance-api
- description: The State Farm B2B Insurance Inquiry API is designed for lenders, mortgage servicers, and financial institutions that need to verify homeowner and auto insurance policy status for collateral protectio
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
  type: Privacy Policy
  url: https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.statefarm.com/customer-care/legal-disclaimer
- title: ''
  type: FAQ
  url: https://developer.statefarm.com/faq
- title: ''
  type: OpenAPI
  url: openapi/state-farm-renters-insurance-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/state-farm-renters-policy-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/state-farm-renters-policy-structure.json
- title: ''
  type: JSONLD
  url: json-ld/state-farm-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/state-farm-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/state-farm-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/embedded-insurance.yaml
created: ''
description: State Farm is the largest property and casualty insurance provider in the United States, headquartered in Bloomington, Illinois. Founded in 1922, the company offers a comprehensive range of insurance products including auto, home, renters, life, health, business, and farm/ranch insurance, as well as banking and financial services. State Farm operates through a network of approximately 19,000 agents across the US and Canada. The company has invested heavily in its digital transformation, operating a Partner Gateway developer portal at developer.statefarm.com that exposes APIs enabling partners, agents, and third-party platforms to integrate with State Farm's insurance products and services. State Farm is a mutual company owned by its policyholders, consistently ranked among the Fortune 50.
features: []
image: ''
integrations: []
jsonld:
- class_count: 18
  name: State Farm Context
  property_count: 11
  slug: state-farm-context
layout: provider
modified: '2026-05-02'
name: State Farm
rules:
- name: State Farm API Rules
  rule_count: 15
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 5
  slug: state-farm-rules
skills: []
slug: state-farm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: state-farm\nurl: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/apis.yml\nmodified: '2026-05-02'\nname: State Farm\ndescription: >-\n  State Farm is the largest property and casualty insurance provider in the United States,\n  headquartered in Bloomington, Illinois. Founded in 1922, the company offers a comprehensive\n  range of insurance products including auto, home, renters, life, health, business, and\n  farm/ranch insurance, as well as banking and financial services. State Farm operates through\n  a network of approximately 19,000 agents across the US and Canada. The company has invested\n  heavily in its digital transformation, operating a Partner Gateway developer portal at\n  developer.statefarm.com that exposes APIs enabling partners, agents, and third-party\n  platforms to integrate with State Farm's insurance products and services. State Farm is\n  a mutual company owned by its policyholders, consistently ranked among the Fortune\
  \ 50.\napis:\n  - aid: state-farm:renters-insurance-api\n    name: Renters Insurance API\n    description: >-\n      The State Farm Renters Insurance API enables partner platforms, real estate applications,\n      and property management systems to offer embedded renters insurance quotes and policies\n      to tenants. Partners can request quotes, initiate policy applications, and retrieve\n      policy status using this API. State Farm is the industry leader in renters insurance,\n      providing coverage for personal belongings, liability protection, and additional living\n      expenses. Available in all US states except California, Massachusetts, and Rhode Island.\n    humanURL: https://developer.statefarm.com/api/renters\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Renters Insurance\n      - Property\n      - Embedded Insurance\n      - Partner\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/api/renters\n\
  \      - type: OpenAPI\n        url: openapi/state-farm-renters-insurance-openapi.yml\n\n  - aid: state-farm:auto-insurance-api\n    name: Auto Insurance API\n    description: >-\n      The State Farm Auto Insurance API supports partner integrations for automobile insurance\n      quoting, policy management, and claims inquiry. This API enables auto dealers, telematics\n      platforms, and financial institutions to embed State Farm auto insurance products within\n      their own applications. State Farm is the largest auto insurer in the US. The API supports\n      retrieving quotes, checking policy status, and accessing coverage information.\n    humanURL: https://developer.statefarm.com/\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Auto Insurance\n      - Vehicles\n      - Partner\n      - Embedded Insurance\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/\n\n  - aid: state-farm:b2b-insurance-inquiry-api\n\
  \    name: B2B Insurance Inquiry API\n    description: >-\n      The State Farm B2B Insurance Inquiry API is designed for lenders, mortgage servicers,\n      and financial institutions that need to verify homeowner and auto insurance policy status\n      for collateral protection purposes. This API supports home and auto lenders in verifying\n      that borrowers maintain the required insurance coverage on financed assets. Accessible\n      through the State Farm B2B portal.\n    humanURL: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n    baseURL: https://b2b.statefarm.com/api/v1\n    tags:\n      - Insurance\n      - B2B\n      - Lenders\n      - Mortgage\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n\ncommon:\n  - type: Website\n    url: https://www.statefarm.com\n  - type: Developer Portal\n    url: https://developer.statefarm.com\n  - type: GitHub\n    url:\
  \ https://github.com/StateFarmIns\n  - type: Engineering Blog\n    url: https://engineering.statefarm.com/blog\n  - type: B2B Portal\n    url: https://b2b.statefarm.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/state-farm\n  - type: Twitter\n    url: https://twitter.com/StateFarm\n  - type: Privacy Policy\n    url: https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy\n  - type: Terms of Service\n    url: https://www.statefarm.com/customer-care/legal-disclaimer\n  - type: FAQ\n    url: https://developer.statefarm.com/faq\n  - type: OpenAPI\n    url: openapi/state-farm-renters-insurance-openapi.yml\n  - type: JSONSchema\n    url: json-schema/state-farm-renters-policy-schema.json\n  - type: JSONStructure\n    url: json-structure/state-farm-renters-policy-structure.json\n  - type: JSONLD\n    url: json-ld/state-farm-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/state-farm-vocabulary.yml\n  - type: SpectralRules\n    url: rules/state-farm-rules.yml\n\
  \  - type: NaftikoCapabilities\n    url: capabilities/embedded-insurance.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/state-farm/refs/heads/main/apis.yml
use_cases: []
---
