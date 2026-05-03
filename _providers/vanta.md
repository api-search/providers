---
api_count: 2
api_specs:
- filename: vanta-openapi.yml
  format: yaml
  label: Vanta API
  slug: vanta-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml
- filename: vanta-auditor-openapi.yml
  format: yaml
  label: Vanta Auditor API
  slug: vanta-auditor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml
apis:
- description: 'The Vanta REST API enables programmatic access to compliance, security monitoring, vulnerability management, personnel management, vendor management, and custom integration capabilities. The API uses '
  name: Vanta API
  slug: vanta-api
- description: The Vanta Auditor API provides external audit firms programmatic access to customer compliance data. Auditors can query audits, vendors, monitored computers, people, vulnerabilities, evidence, control
  name: Vanta Auditor API
  slug: vanta-auditor-api
capabilities:
- description: Unified compliance management workflow combining Vanta's vulnerability tracking, control monitoring, framework oversight, and vendor security reviews. Designed for compliance managers and security eng
  name: Vanta Compliance Management
  slug: compliance-management
common:
- title: ''
  type: Portal
  url: https://developer.vanta.com/docs/vanta-api-overview
- title: ''
  type: Authentication
  url: https://developer.vanta.com/docs/api-access-setup
- title: ''
  type: GettingStarted
  url: https://developer.vanta.com/docs/vanta-first-api-request
- title: ''
  type: PostmanCollection
  url: https://developer.vanta.com/docs/vanta-postman-setup
- title: ''
  type: FAQ
  url: https://developer.vanta.com/docs/faq
- title: ''
  type: Documentation
  url: https://developer.vanta.com/docs/build-integrations
- title: ''
  type: Documentation
  url: https://developer.vanta.com/docs/manage-vendors
- title: ''
  type: Blog
  url: https://www.vanta.com/resources/introducing-vantas-connectors-api
- title: ''
  type: Product
  url: https://www.vanta.com/products/vanta-api
- title: ''
  type: SDK
  url: https://github.com/VantaInc/vanta-auditor-api-sdk-typescript
- title: ''
  type: SDK
  url: https://github.com/VantaInc/vanta-auditor-api-sdk-java
- title: ''
  type: SDK
  url: https://github.com/VantaInc/vanta-mcp-server
- title: ''
  type: SDK
  url: https://github.com/VantaInc/eslint-plugin-vanta
- title: ''
  type: Schema
  url: https://github.com/VantaInc/vanta-control-set
- title: ''
  type: Integration
  url: https://www.vanta.com/integrations/github
- title: ''
  type: ChangeLog
  url: https://www.vanta.com/resources/new-in-vanta-april-2026
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml
created: '2024-11-14'
description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate security monitoring, manage vulnerabilities, track controls, manage vendors, and integrate with existing tools and workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Vanta Context
  property_count: 27
  slug: vanta-context
layout: provider
modified: '2026-05-03'
name: Vanta
rules:
- name: Vanta API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: vanta-rules
skills: []
slug: vanta
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vanta\nurl: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/apis.yml\nname: Vanta\ntags:\n  - Cybersecurity\n  - Compliance\n  - Security\n  - Governance\n  - Risk Management\ntype: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-14'\nmodified: '2026-05-03'\ndescription: >-\n  Vanta is a trust management platform that automates security compliance for frameworks\n  including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations\n  to programmatically manage their compliance posture, automate security monitoring,\n  manage vulnerabilities, track controls, manage vendors, and integrate with existing\n  tools and workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\napis:\n  - aid: vanta:vanta-api\n    name: Vanta API\n    tags:\n      - Cybersecurity\n      - Compliance\n      - Security\n \
  \     - Governance\n      - Risk Management\n    humanURL: https://developer.vanta.com/docs/vanta-api-overview\n    baseURL: https://api.vanta.com\n    properties:\n      - url: https://developer.vanta.com/docs/vanta-api-overview\n        type: Documentation\n      - url: https://developer.vanta.com/docs/api-access-setup\n        type: Authentication\n      - url: https://developer.vanta.com/docs/faq\n        type: FAQ\n      - url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vanta REST API enables programmatic access to compliance, security monitoring,\n      vulnerability management, personnel management, vendor management, and custom\n      integration capabilities. The API uses OAuth 2.0 authentication and returns\n      JSON responses. Rate limits range from 5 to 250 requests per minute depending\n      on endpoint category.\n\n  - aid: vanta:vanta-auditor-api\n    name: Vanta\
  \ Auditor API\n    tags:\n      - Cybersecurity\n      - Compliance\n      - Audit\n      - Security\n    humanURL: https://developer.vanta.com/docs/vanta-api-overview\n    baseURL: https://api.vanta.com\n    properties:\n      - url: https://developer.vanta.com/docs/vanta-api-overview\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vanta Auditor API provides external audit firms programmatic access to customer\n      compliance data. Auditors can query audits, vendors, monitored computers, people,\n      vulnerabilities, evidence, controls, and comments during audit engagements.\n\ncommon:\n  - name: Developer Portal\n    url: https://developer.vanta.com/docs/vanta-api-overview\n    type: Portal\n  - name: Authentication Guide\n    url: https://developer.vanta.com/docs/api-access-setup\n    type: Authentication\n  - name: Getting Started\n\
  \    url: https://developer.vanta.com/docs/vanta-first-api-request\n    type: GettingStarted\n  - name: Postman Collection\n    url: https://developer.vanta.com/docs/vanta-postman-setup\n    type: PostmanCollection\n  - name: FAQ\n    url: https://developer.vanta.com/docs/faq\n    type: FAQ\n  - name: Build Integrations\n    url: https://developer.vanta.com/docs/build-integrations\n    type: Documentation\n  - name: Manage Vendors\n    url: https://developer.vanta.com/docs/manage-vendors\n    type: Documentation\n  - name: Connectors API Blog\n    url: https://www.vanta.com/resources/introducing-vantas-connectors-api\n    type: Blog\n  - name: API Product Overview\n    url: https://www.vanta.com/products/vanta-api\n    type: Product\n  - name: Auditor SDK TypeScript\n    url: https://github.com/VantaInc/vanta-auditor-api-sdk-typescript\n    type: SDK\n  - name: Auditor SDK Java\n    url: https://github.com/VantaInc/vanta-auditor-api-sdk-java\n    type: SDK\n  - name: MCP Server\n    url:\
  \ https://github.com/VantaInc/vanta-mcp-server\n    type: SDK\n  - name: ESLint Plugin\n    url: https://github.com/VantaInc/eslint-plugin-vanta\n    type: SDK\n  - name: Control Set\n    url: https://github.com/VantaInc/vanta-control-set\n    type: Schema\n  - name: GitHub Integration\n    url: https://www.vanta.com/integrations/github\n    type: Integration\n  - name: April 2026 Updates\n    url: https://www.vanta.com/resources/new-in-vanta-april-2026\n    type: ChangeLog\n  - name: OpenAPI Spec\n    url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml\n    type: OpenAPI\n  - name: Auditor OpenAPI Spec\n    url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml\n    type: OpenAPI\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Compliance
- Security
- Governance
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/apis.yml
use_cases: []
---
