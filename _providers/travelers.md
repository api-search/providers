---
api_count: 1
api_specs:
- filename: travelers-openapi.yml
  format: yaml
  label: Travelers API
  slug: travelers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/openapi/travelers-openapi.yml
apis:
- description: Business insurance APIs for claim reporting, commercial lines quoting, and policy management. Enables agents, brokers, and commercial clients to programmatically manage insurance workflows across prop
  name: Travelers API
  slug: travelers
capabilities:
- description: 'Workflow capability for commercial insurance agents, brokers, and enterprise clients integrating with Travelers Insurance. Covers the full commercial insurance lifecycle: obtaining quotes, managing po'
  name: Travelers Commercial Insurance Workflow
  slug: commercial-insurance-workflow
common:
- title: ''
  type: Website
  url: https://www.travelers.com/
- title: ''
  type: Developer Portal
  url: https://developer.travelers.com/s/
- title: ''
  type: Documentation
  url: https://developer.travelers.com/s/apis
- title: ''
  type: Sign Up
  url: https://developer.travelers.com/s/
created: '2026-05-03'
description: Travelers is one of the largest property casualty insurance companies in the United States and a Fortune 500 company. Through their developer portal, Travelers provides APIs for business insurance claim reporting, commercial quoting, and policy management to enable agents, brokers, and partners to programmatically manage insurance workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: Travelers Context
  property_count: 0
  slug: travelers-context
layout: provider
modified: '2026-05-03'
name: Travelers
rules:
- name: Travelers API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 7
  slug: travelers-rules
skills: []
slug: travelers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: travelers\nname: Travelers\ndescription: >-\n  Travelers is one of the largest property casualty insurance companies in the\n  United States and a Fortune 500 company. Through their developer portal,\n  Travelers provides APIs for business insurance claim reporting, commercial\n  quoting, and policy management to enable agents, brokers, and partners to\n  programmatically manage insurance workflows.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Insurance\n  - Property Casualty\n  - Commercial Insurance\n  - Claims\n  - Fintech\n  - Fortune 500\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: travelers:travelers\n    name: Travelers API\n    description: >-\n      Business insurance APIs for claim reporting, commercial lines quoting,\n\
  \      and policy management. Enables agents, brokers, and commercial clients\n      to programmatically manage insurance workflows across property, casualty,\n      workers compensation, and commercial auto lines.\n    humanURL: https://developer.travelers.com/s/\n    baseURL: https://api.travelers.com/v1\n    tags:\n      - Insurance\n      - Property Casualty\n      - Commercial Insurance\n      - Claims\n      - Quoting\n      - Fortune 500\n    properties:\n      - type: Documentation\n        url: https://developer.travelers.com/s/apis\n      - type: OpenAPI\n        url: openapi/travelers-openapi.yml\n      - type: JSONSchema\n        url: json-schema/travelers-claim-schema.json\n      - type: JSONStructure\n        url: json-structure/travelers-claim-structure.json\n      - type: JSONLD\n        url: json-ld/travelers-context.jsonld\n      - type: SpectralRules\n        url: rules/travelers-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/commercial-insurance-workflow.yaml\n\
  \      - type: Vocabulary\n        url: vocabulary/travelers-vocabulary.yml\n      - type: Sign Up\n        url: https://developer.travelers.com/s/\n    x-apis:\n      - Business Insurance Claim Reporting API\n      - Commercial Quoting API\n      - Policy Management API\n    x-policy-types:\n      - property\n      - casualty\n      - workers-compensation\n      - commercial-auto\n      - general-liability\n      - business-owners-policy\ncommon:\n  - type: Website\n    url: https://www.travelers.com/\n  - type: Developer Portal\n    url: https://developer.travelers.com/s/\n  - type: Documentation\n    url: https://developer.travelers.com/s/apis\n  - type: Sign Up\n    url: https://developer.travelers.com/s/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/apis.yml
tags:
- Insurance
- Property Casualty
- Commercial Insurance
- Claims
- Fintech
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/apis.yml
use_cases: []
---
