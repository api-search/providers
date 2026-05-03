---
api_count: 2
api_specs:
- filename: sandbox-banking-glyue-openapi.yml
  format: yaml
  label: Glyue Integration Gateway API
  slug: glyue
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandbox-banking/refs/heads/main/openapi/sandbox-banking-glyue-openapi.yml
apis:
- description: The Glyue Integration Gateway API provides programmatic access to the Sandbox Banking integration platform for building, managing, and monitoring banking integrations. The API supports creating and ex
  name: Glyue Integration Gateway API
  slug: glyue
- description: The Mock Bank API provides a sandbox environment for testing and developing banking integrations without connecting to production core banking systems. It simulates standard banking operations includi
  name: Mock Bank API
  slug: mockbank
capabilities:
- description: Banking integration workflow management capability using the Glyue Integration Gateway API. Provides unified access to integration workflow lifecycle management, service request adapter configuration,
  name: Sandbox Banking Integration Management
  slug: banking-integration-management
common:
- title: Glyue Integration Gateway Documentation
  type: Documentation
  url: https://glyue.docs.sandboxbanking.com/
- title: nCino Integration Gateway
  type: Documentation
  url: https://www.ncino.com/solutions/integrations
- title: Mock Bank API Documentation
  type: Documentation
  url: https://mockbank.docs.sandboxbanking.com/
- title: Sandbox Banking Website
  type: Website
  url: https://sandboxbanking.com/
- title: Sandbox Banking API Spectral Rules
  type: SpectralRules
  url: rules/sandbox-banking-rules.yml
- title: Sandbox Banking Integration Management Capability
  type: NaftikoCapability
  url: capabilities/banking-integration-management.yaml
- title: Sandbox Banking Integration Schema
  type: JSONSchema
  url: json-schema/sandbox-banking-integration-schema.json
- title: Sandbox Banking Integration Structure
  type: JSONStructure
  url: json-structure/sandbox-banking-integration-structure.json
- title: Sandbox Banking JSON-LD Context
  type: JSONLDContext
  url: json-ld/sandbox-banking-context.jsonld
- title: Sandbox Banking List Integrations Example
  type: Example
  url: examples/sandbox-banking-list-integrations-example.json
- title: Sandbox Banking Run Integration Example
  type: Example
  url: examples/sandbox-banking-run-integration-example.json
- title: Sandbox Banking Vocabulary
  type: Vocabulary
  url: vocabulary/sandbox-banking-vocabulary.yml
created: '2024-12-25'
description: Sandbox Banking (now nCino Integration Gateway) is an Integration Platform as a Service (iPaaS) purpose-built for financial institutions. The platform enables banks and credit unions to connect core banking systems (Fiserv, Jack Henry, FIS, and 14+ other cores) with fintech applications, loan origination systems, CRMs, KYC/AML providers, and 50+ financial services solutions. Glyue, the core integration framework, provides low-code workflow automation with Python extensibility, audit trails, role-based access control, and regulatory compliance features aligned with CFPB Section 1033, GLBA, and FFIEC guidelines.
features: []
image: ''
integrations: []
jsonld:
- class_count: 43
  name: Sandbox Banking Context
  property_count: 0
  slug: sandbox-banking-context
layout: provider
modified: '2026-05-02'
name: Sandbox Banking
rules:
- name: Sandbox Banking API Rules
  rule_count: 13
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 7
  slug: sandbox-banking-rules
skills: []
slug: sandbox-banking
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sandbox-banking\nname: Sandbox Banking\ndescription: >-\n  Sandbox Banking (now nCino Integration Gateway) is an Integration Platform as a\n  Service (iPaaS) purpose-built for financial institutions. The platform enables\n  banks and credit unions to connect core banking systems (Fiserv, Jack Henry, FIS,\n  and 14+ other cores) with fintech applications, loan origination systems, CRMs,\n  KYC/AML providers, and 50+ financial services solutions. Glyue, the core\n  integration framework, provides low-code workflow automation with Python extensibility,\n  audit trails, role-based access control, and regulatory compliance features aligned\n  with CFPB Section 1033, GLBA, and FFIEC guidelines.\nurl: https://glyue.docs.sandboxbanking.com/\ntags:\n  - API Integration\n  - Banking\n  - Core Banking\n  - Credit Unions\n  - Financial Services\n  - Fintech\n  - Integration Platform\n  - iPaaS\n  - Open Banking\ncreated: '2024-12-25'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: sandbox-banking:glyue\n    name: Glyue Integration Gateway API\n    description: >-\n      The Glyue Integration Gateway API provides programmatic access to the\n      Sandbox Banking integration platform for building, managing, and monitoring\n      banking integrations. The API supports creating and executing integration\n      workflows, managing service request adapters, configuring field mappings,\n      value mappings, validation rules, and accessing run history audit logs.\n    humanURL: https://glyue.docs.sandboxbanking.com/\n    baseURL: https://{tenant}.sandboxbanking.com/api\n    tags:\n      - Audit\n      - Banking Integration\n      - Core Banking\n      - Field Mapping\n      - Glyue\n      - Integration\n      - iPaaS\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://glyue.docs.sandboxbanking.com/\n      - type: Documentation\n        url: https://glyue.docs.sandboxbanking.com/reference/integration_anatomy\n\
  \      - type: OpenAPI\n        url: openapi/sandbox-banking-glyue-openapi.yml\n  - aid: sandbox-banking:mockbank\n    name: Mock Bank API\n    description: >-\n      The Mock Bank API provides a sandbox environment for testing and developing\n      banking integrations without connecting to production core banking systems.\n      It simulates standard banking operations including account management,\n      transactions, and customer data in a controlled test environment.\n    humanURL: https://mockbank.docs.sandboxbanking.com/\n    tags:\n      - Banking\n      - Mock API\n      - Sandbox\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://mockbank.docs.sandboxbanking.com/reference/introduction\ncommon:\n  - type: Documentation\n    url: https://glyue.docs.sandboxbanking.com/\n    title: Glyue Integration Gateway Documentation\n  - type: Documentation\n    url: https://www.ncino.com/solutions/integrations\n    title: nCino Integration Gateway\n  - type:\
  \ Documentation\n    url: https://mockbank.docs.sandboxbanking.com/\n    title: Mock Bank API Documentation\n  - type: Website\n    url: https://sandboxbanking.com/\n    title: Sandbox Banking Website\n  - type: SpectralRules\n    url: rules/sandbox-banking-rules.yml\n    title: Sandbox Banking API Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/banking-integration-management.yaml\n    title: Sandbox Banking Integration Management Capability\n  - type: JSONSchema\n    url: json-schema/sandbox-banking-integration-schema.json\n    title: Sandbox Banking Integration Schema\n  - type: JSONStructure\n    url: json-structure/sandbox-banking-integration-structure.json\n    title: Sandbox Banking Integration Structure\n  - type: JSONLDContext\n    url: json-ld/sandbox-banking-context.jsonld\n    title: Sandbox Banking JSON-LD Context\n  - type: Example\n    url: examples/sandbox-banking-list-integrations-example.json\n    title: Sandbox Banking List Integrations Example\n  -\
  \ type: Example\n    url: examples/sandbox-banking-run-integration-example.json\n    title: Sandbox Banking Run Integration Example\n  - type: Vocabulary\n    url: vocabulary/sandbox-banking-vocabulary.yml\n    title: Sandbox Banking Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sandbox-banking/refs/heads/main/apis.yml
tags:
- API Integration
- Banking
- Core Banking
- Credit Unions
- Financial Services
- Fintech
- Integration Platform
- iPaaS
- Open Banking
url: https://glyue.docs.sandboxbanking.com/
use_cases: []
---
