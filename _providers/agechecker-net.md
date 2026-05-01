---
api_count: 1
api_specs:
- filename: agechecker-net-age-verification-openapi.yml
  format: yaml
  label: AgeChecker.Net Age Verification API
  slug: agechecker-net-age-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/openapi/agechecker-net-age-verification-openapi.yml
apis:
- description: The AgeChecker.Net Age Verification API provides seamless age verification for online transactions. Send customer data directly to verify age without requiring a popup for most customers. Only custome
  name: AgeChecker.Net Age Verification API
  slug: agechecker-net-age-verification-api
capabilities:
- description: ''
  name: Age Verification
  slug: age-verification
common:
- title: ''
  type: Portal
  url: https://agechecker.net
- title: ''
  type: GettingStarted
  url: https://agechecker.net/age-verification-api
- title: ''
  type: TermsOfService
  url: https://agechecker.net/terms
- title: ''
  type: PrivacyPolicy
  url: https://agechecker.net/privacy
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/rules/agechecker-net-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/capabilities/age-verification.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/capabilities/shared/age-verification-api.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-verification-request-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-verification-response-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-session-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-ld/agechecker-verification-context.jsonld
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-verification-request-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-verification-response-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-session-example.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/vocabulary/agechecker-net-vocabulary.yaml
created: '2025-01-07'
description: AgeChecker.Net provides age verification API services for e-commerce businesses selling age-restricted products such as alcohol, tobacco, cannabis, and firearms. The API enables seamless background verification for most customers and guided photo ID verification for those who cannot be automatically verified.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Agechecker Net Age Context
  property_count: 25
  slug: agechecker-net-age-context
layout: provider
modified: '2026-04-19'
name: AgeChecker.Net
rules:
- name: AgeChecker.Net API Rules
  rule_count: 24
  severity_counts:
    error: 14
    hint: 0
    info: 0
    warn: 10
  slug: agechecker-net-spectral-rules
skills: []
slug: agechecker-net
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: agechecker-net\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/apis.yml\napis:\n  - aid: agechecker-net:agechecker-net-age-verification-api\n    name: AgeChecker.Net Age Verification API\n    tags:\n      - Age Verification\n      - Identity\n      - Compliance\n    humanURL: https://agechecker.net/age-verification-api\n    baseURL: https://api.agechecker.net/v1\n    properties:\n      - url: https://agechecker.net/age-verification-api\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/openapi/agechecker-net-age-verification-openapi.yml\n        type: OpenAPI\n    description: >-\n      The AgeChecker.Net Age Verification API provides seamless age verification\n      for online transactions. Send customer data directly to verify age without\n      requiring a popup for most customers. Only customers requiring photo ID\n      will be prompted\
  \ for additional verification.\n    contact:\n      - FN: AgeChecker.Net Support\n        url: https://agechecker.net/contact\nname: AgeChecker.Net\ntags:\n  - Age Verification\n  - Identity\n  - Compliance\n  - Regulatory\n  - E-Commerce\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-07'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  AgeChecker.Net provides age verification API services for e-commerce\n  businesses selling age-restricted products such as alcohol, tobacco,\n  cannabis, and firearms. The API enables seamless background verification\n  for most customers and guided photo ID verification for those who cannot\n  be automatically verified.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\nfeatures:\n  - Seamless Background Age Verification\n  - Photo ID Upload and Verification\n  - Webhook Notifications for Verification Events\n\
  \  - Session-Based Verification Tracking\n  - Support for Multiple Age Thresholds (18, 21+)\n  - US Address Verification Integration\n  - COPPA and CIPA Compliance Support\nuseCases:\n  - Alcohol and Beverage E-Commerce Age Gating\n  - Tobacco and Vape Product Age Verification\n  - Cannabis Dispensary Online Order Verification\n  - Firearms and Ammunition Purchase Compliance\n  - Adult Content Platform Age Gates\n  - Regulated Pharmaceutical Online Sales\nintegrations:\n  - Shopify Age Verification\n  - WooCommerce Age Gate Plugin\n  - BigCommerce Age Verification\n  - Magento Age Check Integration\n  - Custom E-Commerce Platform Integration\ncommon:\n  - url: https://agechecker.net\n    type: Portal\n  - url: https://agechecker.net/age-verification-api\n    type: GettingStarted\n  - url: https://agechecker.net/terms\n    type: TermsOfService\n  - url: https://agechecker.net/privacy\n    type: PrivacyPolicy\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/rules/agechecker-net-spectral-rules.yml\n\
  \    type: SpectralRules\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/capabilities/age-verification.yaml\n    type: NaftikoCapability\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/capabilities/shared/age-verification-api.yaml\n    type: NaftikoCapability\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-verification-request-schema.json\n    type: JSONSchema\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-verification-response-schema.json\n    type: JSONSchema\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-schema/agechecker-session-schema.json\n    type: JSONSchema\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/json-ld/agechecker-verification-context.jsonld\n\
  \    type: JSONLDContext\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-verification-request-example.json\n    type: Example\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-verification-response-example.json\n    type: Example\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/examples/agechecker-session-example.json\n    type: Example\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/vocabulary/agechecker-net-vocabulary.yaml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/apis.yml
tags:
- Age Verification
- Identity
- Compliance
- Regulatory
- E-Commerce
url: https://raw.githubusercontent.com/api-evangelist/agechecker-net/refs/heads/main/apis.yml
use_cases: []
---
