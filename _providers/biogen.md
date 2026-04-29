---
api_count: 1
apis:
- description: The Biogen Developer API provides programmatic access to Biogen services including the CCS-CRX API following REST standard specifications. The portal offers interactive I/O docs for testing API servic
  name: Biogen Developer API
  slug: developer-api
capabilities:
- description: ''
  name: Api Access Management
  slug: api-access-management
common:
- title: ''
  type: Portal
  url: https://developer.biogen.com/
- title: ''
  type: Website
  url: https://www.biogen.com/
- title: ''
  type: Documentation
  url: https://developer.biogen.com/io-docs
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/rules/biogen-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/vocabulary/biogen-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/capabilities/api-access-management.yaml
created: '2025-01-01'
description: Biogen is a global biotechnology company that discovers, develops, and delivers therapies for people living with serious neurological diseases including multiple sclerosis, Alzheimer's, and spinal muscular atrophy.
features:
- description: Programmatic access to Copaxone CRX pharmaceutical service.
  name: CCS-CRX API
- description: Self-service API key creation and usage monitoring via developer portal.
  name: API Key Management
- description: Interactive API documentation for testing endpoints directly in the browser.
  name: Interactive I/O Docs
- description: Monitor API request volumes and usage statistics per key.
  name: Usage Reporting
- description: REST-compliant API design following standard HTTP methods and response codes.
  name: REST Standards
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connect EHR and healthcare IT systems to Biogen pharmaceutical APIs.
  name: Healthcare IT Systems
- description: Integrate with Biogen patient support and copay assistance programs.
  name: Patient Support Programs
jsonld:
- class_count: 5
  name: Biogen Context
  property_count: 5
  slug: biogen-context
layout: provider
modified: '2026-04-21'
name: Biogen
rules:
- name: Biogen API Rules
  rule_count: 23
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 16
  slug: biogen-spectral-rules
skills: []
slug: biogen
solutions: []
source_filename: apis.yml
source_yaml: "aid: biogen\nurl: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/apis.yml\napis:\n- aid: biogen:developer-api\n  name: Biogen Developer API\n  tags:\n  - Biotechnology\n  - Healthcare\n  - Life Sciences\n  - Pharmaceuticals\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://developer.biogen.com\n  humanURL: https://developer.biogen.com/\n  properties:\n  - type: Portal\n    url: https://developer.biogen.com/\n  - type: Documentation\n    url: https://developer.biogen.com/io-docs\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/openapi/biogen-developer-api-openapi.yml\n  description: >-\n    The Biogen Developer API provides programmatic access to Biogen services\n    including the CCS-CRX API following REST standard specifications. The\n    portal offers interactive I/O docs for testing API services, access key\n    management, usage reporting,\
  \ and detailed documentation covering supported\n    methods, HTTP headers, request/response formats, and response codes.\ndescription: >-\n  Biogen is a global biotechnology company that discovers, develops, and delivers\n  therapies for people living with serious neurological diseases including multiple\n  sclerosis, Alzheimer's, and spinal muscular atrophy.\nname: Biogen\ntype: Contract\naccess: 3rd-Party\nposition: Consuming\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Biotechnology\n- Healthcare\n- Life Sciences\n- Pharmaceuticals\n- Neurology\ncreated: '2025-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://developer.biogen.com/\n- type: Website\n  url: https://www.biogen.com/\n- type: Documentation\n  url: https://developer.biogen.com/io-docs\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/rules/biogen-spectral-rules.yml\n\
  - type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/vocabulary/biogen-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/capabilities/api-access-management.yaml\n- type: Features\n  data:\n  - name: CCS-CRX API\n    description: Programmatic access to Copaxone CRX pharmaceutical service.\n  - name: API Key Management\n    description: Self-service API key creation and usage monitoring via developer portal.\n  - name: Interactive I/O Docs\n    description: Interactive API documentation for testing endpoints directly in the browser.\n  - name: Usage Reporting\n    description: Monitor API request volumes and usage statistics per key.\n  - name: REST Standards\n    description: REST-compliant API design following standard HTTP methods and response codes.\n- type: UseCases\n  data:\n  - name: Pharmaceutical Service Integration\n    description: Integrate with Biogen pharmaceutical\
  \ services like CCS-CRX programmatically.\n  - name: Developer Onboarding\n    description: Self-service API key registration and service access via developer portal.\n  - name: Healthcare System Integration\n    description: Connect healthcare systems to Biogen services for patient program support.\n- type: Integrations\n  data:\n  - name: Healthcare IT Systems\n    description: Connect EHR and healthcare IT systems to Biogen pharmaceutical APIs.\n  - name: Patient Support Programs\n    description: Integrate with Biogen patient support and copay assistance programs.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/apis.yml
tags:
- Biotechnology
- Healthcare
- Life Sciences
- Pharmaceuticals
- Neurology
url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/apis.yml
use_cases:
- description: Integrate with Biogen pharmaceutical services like CCS-CRX programmatically.
  name: Pharmaceutical Service Integration
- description: Self-service API key registration and service access via developer portal.
  name: Developer Onboarding
- description: Connect healthcare systems to Biogen services for patient program support.
  name: Healthcare System Integration
---
