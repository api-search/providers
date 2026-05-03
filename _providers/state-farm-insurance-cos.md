---
api_count: 3
api_specs:
- filename: state-farm-insurance-cos-renters-openapi.yml
  format: yaml
  label: Renters Insurance API
  slug: renters-insurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/openapi/state-farm-insurance-cos-renters-openapi.yml
apis:
- description: The State Farm Partner Gateway API serves as the unified integration layer for all State Farm Insurance Companies subsidiaries, enabling external partners to access insurance products across the State
  name: Partner Gateway API
  slug: partner-gateway-api
- description: The Renters Insurance API from State Farm Insurance Companies enables property management platforms, multifamily housing operators, and partner aggregators to embed State Farm renters insurance into t
  name: Renters Insurance API
  slug: renters-insurance-api
- description: The State Farm B2B Lender Services API provides mortgage lenders and auto lenders with programmatic access to verify insurance coverage for collateral assets financed by their borrowers. Lenders can c
  name: B2B Lender Services API
  slug: b2b-lender-services-api
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
  url: openapi/state-farm-insurance-cos-renters-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/state-farm-insurance-cos-renters-policy-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/state-farm-insurance-cos-renters-policy-structure.json
- title: ''
  type: JSONLD
  url: json-ld/state-farm-insurance-cos-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/state-farm-insurance-cos-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/state-farm-insurance-cos-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/embedded-insurance.yaml
created: ''
description: State Farm Insurance Companies is the collective name for the group of insurance subsidiaries operating under State Farm Mutual Automobile Insurance Company, the parent organization headquartered in Bloomington, Illinois. The group comprises fourteen property and casualty insurance companies and two life insurance companies including State Farm Mutual Automobile Insurance Company, State Farm Fire and Casualty Company, State Farm Indemnity Company, State Farm Life Insurance Company, State Farm General Insurance Company, State Farm Florida Insurance Company, and State Farm Lloyds, among others. This multi-entity structure allows State Farm to manage its business across different US state regulatory environments. As a group, State Farm Insurance Companies is the largest property and casualty insurer in the United States. The group shares the common digital infrastructure and developer platform operated at developer.statefarm.com.
features: []
image: ''
integrations: []
jsonld:
- class_count: 11
  name: State Farm Insurance Cos Context
  property_count: 8
  slug: state-farm-insurance-cos-context
layout: provider
modified: '2026-05-02'
name: State Farm Insurance Companies
rules:
- name: State Farm Insurance Companies API Rules
  rule_count: 15
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 5
  slug: state-farm-insurance-cos-rules
skills: []
slug: state-farm-insurance-cos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: state-farm-insurance-cos\nurl: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/apis.yml\nmodified: '2026-05-02'\nname: State Farm Insurance Companies\ndescription: >-\n  State Farm Insurance Companies is the collective name for the group of insurance subsidiaries\n  operating under State Farm Mutual Automobile Insurance Company, the parent organization\n  headquartered in Bloomington, Illinois. The group comprises fourteen property and casualty\n  insurance companies and two life insurance companies including State Farm Mutual Automobile\n  Insurance Company, State Farm Fire and Casualty Company, State Farm Indemnity Company,\n  State Farm Life Insurance Company, State Farm General Insurance Company, State Farm Florida\n  Insurance Company, and State Farm Lloyds, among others. This multi-entity structure allows\n  State Farm to manage its business across different US state regulatory environments. As a group,\n  State Farm Insurance\
  \ Companies is the largest property and casualty insurer in the United States.\n  The group shares the common digital infrastructure and developer platform operated at\n  developer.statefarm.com.\napis:\n  - aid: state-farm-insurance-cos:partner-gateway-api\n    name: Partner Gateway API\n    description: >-\n      The State Farm Partner Gateway API serves as the unified integration layer for all\n      State Farm Insurance Companies subsidiaries, enabling external partners to access\n      insurance products across the State Farm family of companies through a single API\n      entry point. The Partner Gateway supports embedded insurance workflows, lender\n      integrations, real estate platforms, and third-party aggregators, routing requests\n      to the appropriate State Farm subsidiary based on the product type and state jurisdiction.\n    humanURL: https://developer.statefarm.com\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Partner\n      - Integration\n\
  \      - API Gateway\n      - Multi-line\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com\n      - type: FAQ\n        url: https://developer.statefarm.com/faq\n\n  - aid: state-farm-insurance-cos:renters-insurance-api\n    name: Renters Insurance API\n    description: >-\n      The Renters Insurance API from State Farm Insurance Companies enables property management\n      platforms, multifamily housing operators, and partner aggregators to embed State Farm renters\n      insurance into their tenant onboarding flows. State Farm is the number one writer of renters\n      insurance in the US. Partners can request quotes, bind policies, and retrieve policy status\n      through this API. Coverage is underwritten by the appropriate State Farm subsidiary for each\n      state jurisdiction.\n    humanURL: https://developer.statefarm.com/api/renters\n    baseURL: https://api.statefarm.com/v1\n    tags:\n      - Insurance\n      - Renters Insurance\n\
  \      - Embedded Insurance\n      - Partner\n      - Multi-line\n    properties:\n      - type: Documentation\n        url: https://developer.statefarm.com/api/renters\n      - type: OpenAPI\n        url: openapi/state-farm-insurance-cos-renters-openapi.yml\n\n  - aid: state-farm-insurance-cos:b2b-lender-services-api\n    name: B2B Lender Services API\n    description: >-\n      The State Farm B2B Lender Services API provides mortgage lenders and auto lenders with\n      programmatic access to verify insurance coverage for collateral assets financed by their\n      borrowers. Lenders can confirm active homeowners, auto, or property insurance policies\n      written by any State Farm Insurance Companies subsidiary. This supports lender compliance,\n      reduces force-placed insurance, and streamlines closing workflows.\n    humanURL: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n    baseURL: https://b2b.statefarm.com/api/v1\n    tags:\n      - Insurance\n      -\
  \ B2B\n      - Lenders\n      - Mortgage\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry\n\ncommon:\n  - type: Website\n    url: https://www.statefarm.com\n  - type: Developer Portal\n    url: https://developer.statefarm.com\n  - type: GitHub\n    url: https://github.com/StateFarmIns\n  - type: Engineering Blog\n    url: https://engineering.statefarm.com/blog\n  - type: B2B Portal\n    url: https://b2b.statefarm.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/state-farm\n  - type: Newsroom\n    url: https://newsroom.statefarm.com\n  - type: Privacy Policy\n    url: https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy\n  - type: Terms of Service\n    url: https://www.statefarm.com/customer-care/legal-disclaimer\n  - type: OpenAPI\n    url: openapi/state-farm-insurance-cos-renters-openapi.yml\n  - type: JSONSchema\n    url: json-schema/state-farm-insurance-cos-renters-policy-schema.json\n\
  \  - type: JSONStructure\n    url: json-structure/state-farm-insurance-cos-renters-policy-structure.json\n  - type: JSONLD\n    url: json-ld/state-farm-insurance-cos-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/state-farm-insurance-cos-vocabulary.yml\n  - type: SpectralRules\n    url: rules/state-farm-insurance-cos-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/embedded-insurance.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/apis.yml
use_cases: []
---
