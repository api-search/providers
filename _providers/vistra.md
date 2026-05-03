---
api_count: 1
api_specs:
- filename: vistra-incorporations-openapi.yml
  format: yaml
  label: Vistra Incorporations API
  slug: incorporations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/openapi/vistra-incorporations-openapi.yml
apis:
- description: The Vistra Incorporations API enables programmatic submission of company incorporation requests in supported jurisdictions. Currently available for the British Virgin Islands (BVI) on an invite-only b
  name: Vistra Incorporations API
  slug: incorporations-api
capabilities:
- description: 'Workflow capability for automating company entity formation and incorporation via the Vistra REST API. Covers the complete BVI incorporation workflow: document upload preparation, upload confirmation,'
  name: Vistra Entity Formation
  slug: entity-formation
common:
- title: ''
  type: Website
  url: https://www.vistra.com
- title: ''
  type: Developer Portal
  url: https://devportal.vistra.com/
- title: ''
  type: Help Center
  url: https://help.vistra.com/en/
- title: ''
  type: Client Portals
  url: https://www.vistra.com/client-portals
- title: ''
  type: Entity Management
  url: https://www.vistra.com/corporate/entity-management
- title: ''
  type: Privacy Policy
  url: https://www.vistra.com/privacy-policy
- title: ''
  type: OpenAPI
  url: openapi/vistra-incorporations-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/vistra-incorporation-schema.json
- title: ''
  type: JSONLD
  url: json-ld/vistra-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/vistra-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/vistra-rules.yml
created: '2026-03-21'
description: Vistra is a global corporate services provider operating in over 45 jurisdictions, offering entity management, incorporation, compliance, payroll, and fund administration services. The Vistra REST API enables developers to programmatically submit company incorporation requests in supported jurisdictions (initially British Virgin Islands), upload supporting documents to pre-signed storage URLs, and integrate Vistra's corporate services into business process workflows. Authentication uses OAuth2 bearer tokens obtained through the Vistra Developer Portal.
features: []
image: https://www.vistra.com/themes/custom/vistra/logo.svg
integrations: []
jsonld:
- class_count: 32
  name: Vistra Context
  property_count: 5
  slug: vistra-context
layout: provider
modified: '2026-05-03'
name: Vistra
rules:
- name: Vistra API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 7
  slug: vistra-rules
skills: []
slug: vistra
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vistra\nname: Vistra\ndescription: >-\n  Vistra is a global corporate services provider operating in over 45 jurisdictions,\n  offering entity management, incorporation, compliance, payroll, and fund administration\n  services. The Vistra REST API enables developers to programmatically submit company\n  incorporation requests in supported jurisdictions (initially British Virgin Islands),\n  upload supporting documents to pre-signed storage URLs, and integrate Vistra's\n  corporate services into business process workflows. Authentication uses OAuth2 bearer\n  tokens obtained through the Vistra Developer Portal.\nimage: https://www.vistra.com/themes/custom/vistra/logo.svg\ntype: Index\ntags:\n  - Compliance\n  - Corporate Services\n  - Entity Management\n  - Finance\n  - Fortune 500\n  - Legal\nurl: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ vistra:incorporations-api\n    name: Vistra Incorporations API\n    description: >-\n      The Vistra Incorporations API enables programmatic submission of company\n      incorporation requests in supported jurisdictions. Currently available for\n      the British Virgin Islands (BVI) on an invite-only basis, the API supports\n      the full incorporation workflow: generating pre-signed S3 document upload URLs,\n      confirming document upload completion, and submitting incorporation requests with\n      entity details, stakeholder information, shareholding structure, and compliance data.\n      Authentication requires OAuth2 bearer tokens obtained from the Vistra Developer Portal.\n    humanURL: https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands\n    baseURL: https://api.vistra.com\n    tags:\n      - BVI\n      - British Virgin Islands\n      - Compliance\n      - Corporate Services\n      - Entity Management\n      - Incorporation\n    \
  \  - Legal\n      - OAuth2\n    properties:\n      - type: Documentation\n        url: https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands\n      - type: Developer Portal\n        url: https://devportal.vistra.com/\n      - type: OpenAPI\n        url: openapi/vistra-incorporations-openapi.yml\n    contact:\n      - FN: Vistra Support\n        url: https://help.vistra.com/en/\ncommon:\n  - type: Website\n    url: https://www.vistra.com\n  - type: Developer Portal\n    url: https://devportal.vistra.com/\n  - type: Help Center\n    url: https://help.vistra.com/en/\n  - type: Client Portals\n    url: https://www.vistra.com/client-portals\n  - type: Entity Management\n    url: https://www.vistra.com/corporate/entity-management\n  - type: Privacy Policy\n    url: https://www.vistra.com/privacy-policy\n  - type: OpenAPI\n    url: openapi/vistra-incorporations-openapi.yml\n  - type: JSONSchema\n    url: json-schema/vistra-incorporation-schema.json\n  -\
  \ type: JSONLD\n    url: json-ld/vistra-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/vistra-vocabulary.yml\n  - type: SpectralRules\n    url: rules/vistra-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml
tags:
- Compliance
- Corporate Services
- Entity Management
- Finance
- Fortune 500
- Legal
url: https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml
use_cases: []
---
