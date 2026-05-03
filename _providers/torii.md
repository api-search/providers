---
api_count: 1
api_specs:
- filename: torii-torii-openapi.yml
  format: yaml
  label: Torii SaaS Management API
  slug: torii
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/openapi/torii-torii-openapi.yml
apis:
- description: The Torii API provides programmatic access to the Torii SaaS Management Platform. It allows IT, Finance, and Security teams to manage apps, users, contracts, licenses, audit logs, and file uploads. Su
  name: Torii SaaS Management API
  slug: torii
capabilities:
- description: 'Workflow capability for SaaS governance and IT management using Torii — covering shadow IT discovery, user lifecycle management, contract renewals, spend optimization, compliance auditing, and custom '
  name: Torii SaaS Governance
  slug: saas-governance
common:
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/toriihq/
- title: ''
  type: Website
  url: https://www.toriihq.com/
- title: ''
  type: Documentation
  url: https://developers.toriihq.com
- title: ''
  type: About
  url: https://www.toriihq.com/about
- title: ''
  type: Pricing
  url: https://www.toriihq.com/pricing
- title: ''
  type: TermsOfService
  url: https://www.toriihq.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.toriihq.com/security
- title: ''
  type: Customers
  url: https://www.toriihq.com/customers
- title: ''
  type: Partners
  url: https://www.toriihq.com/partners
- title: ''
  type: Branding
  url: https://www.toriihq.com/brand-guidelines
- title: ''
  type: Login
  url: https://app.toriihq.com/login
- title: ''
  type: JSON-LD
  url: json-ld/torii-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/torii-app-structure.json
- title: ''
  type: SpectralRules
  url: rules/torii-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/saas-governance.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/torii-vocabulary.yml
created: '2025-07-15'
description: Torii is the market leading SaaS Management Platform built to bring all your software into one place. Discover shadow IT, enforce governance, cut costs, and operationalize every app. Torii integrates with 180+ SaaS applications to provide license and usage data, automate user onboarding and offboarding workflows, manage SaaS contracts and renewals, and maintain compliance audit trails.
features:
- name: SaaS Management Platform
- name: Shadow IT Discovery
- name: App Lifecycle Management
- name: License Optimization
- name: Contract and Renewal Management
- name: Workflow Automation
- name: User Onboarding and Offboarding
- name: SCIM 2.0 Provisioning
- name: Compliance Audit Logs
- name: Custom Integrations
- name: Browser Extension
- name: 180+ Native Integrations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Okta
- name: Microsoft Entra ID
- name: Google Workspace
- name: Slack
- name: Salesforce
- name: Jira Cloud
- name: GitHub Enterprise
- name: Azure DevOps
- name: Zoom
- name: Microsoft Teams
- name: Datadog
- name: ServiceNow
- name: BambooHR
- name: Workday HCM
- name: Rippling
- name: HubSpot
- name: Zendesk
- name: PagerDuty
- name: Confluence
- name: Notion
jsonld:
- class_count: 48
  name: Torii Context
  property_count: 0
  slug: torii-context
layout: provider
modified: '2026-05-03'
name: Torii
rules:
- name: Torii API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 5
  slug: torii-rules
skills: []
slug: torii
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: torii\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/apis.yml\napis:\n  - aid: torii:torii\n    name: Torii SaaS Management API\n    tags:\n      - Apps\n      - Audit\n      - Contracts\n      - Files\n      - Metadata\n      - Parsings\n      - SaaS Management\n      - SCIM\n      - Users\n    humanURL: https://developers.toriihq.com/reference/introduction-1\n    properties:\n      - url: https://developers.toriihq.com/reference/introduction-1\n        type: Documentation\n      - url: https://www.toriihq.com/\n        type: Website\n      - url: openapi/torii-torii-openapi.yml\n        type: OpenAPI\n      - url: rules/torii-rules.yml\n        type: SpectralRules\n      - url: capabilities/shared/torii-saas-management.yaml\n        type: NaftikoCapability\n      - url: json-schema/app.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/contract.json\n        type:\
  \ JSONSchema\n      - url: json-schema/audit-log-entry.json\n        type: JSONSchema\n      - url: json-schema/field-metadata.json\n        type: JSONSchema\n      - url: json-schema/parsing-request.json\n        type: JSONSchema\n      - url: json-schema/scim-user.json\n        type: JSONSchema\n      - url: json-ld/torii-context.jsonld\n        type: JSONLD\n    description: >-\n      The Torii API provides programmatic access to the Torii SaaS Management\n      Platform. It allows IT, Finance, and Security teams to manage apps, users,\n      contracts, licenses, audit logs, and file uploads. Supports custom\n      integration data sync, workflow execution monitoring, and SCIM 2.0 user\n      provisioning. The API closely follows REST semantics, uses JSON to encode\n      objects, cursor-based pagination, and relies on standard HTTP codes to\n      signal operation outcomes. Authentication uses Bearer API keys generated\n      in Torii Settings.\nname: Torii\ntags:\n  - Apps\n  - Compliance\n\
  \  - Cost Optimization\n  - Governance\n  - IT Management\n  - SaaS Management\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-07-15'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  Torii is the market leading SaaS Management Platform built to bring all your\n  software into one place. Discover shadow IT, enforce governance, cut costs, and\n  operationalize every app. Torii integrates with 180+ SaaS applications to provide\n  license and usage data, automate user onboarding and offboarding workflows, manage\n  SaaS contracts and renewals, and maintain compliance audit trails.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: LinkedIn\n    url: https://www.linkedin.com/company/toriihq/\n    type: LinkedIn\n  - name: Torii Website\n    url: https://www.toriihq.com/\n    type: Website\n  - name: Torii Developer Documentation\n\
  \    url: https://developers.toriihq.com\n    type: Documentation\n  - name: About Torii\n    url: https://www.toriihq.com/about\n    type: About\n  - name: Integrations\n    url: https://www.toriihq.com/integration/page/14\n    type: Integrations\n  - name: Pricing\n    url: https://www.toriihq.com/pricing\n    type: Pricing\n  - name: Terms of Service\n    url: https://www.toriihq.com/terms\n    type: TermsOfService\n  - name: Security\n    url: https://www.toriihq.com/security\n    type: PrivacyPolicy\n  - name: Customers\n    url: https://www.toriihq.com/customers\n    type: Customers\n  - name: Partners\n    url: https://www.toriihq.com/partners\n    type: Partners\n  - name: Brand Guidelines\n    url: https://www.toriihq.com/brand-guidelines\n    type: Branding\n  - name: Torii Login\n    url: https://app.toriihq.com/login\n    type: Login\n  - name: Torii JSON-LD Context\n    url: json-ld/torii-context.jsonld\n    type: JSON-LD\n    description: 'JSON-LD context for Torii SaaS Management\
  \ domain vocabulary.'\n  - name: Torii App JSON Structure\n    url: json-structure/torii-app-structure.json\n    type: JSONStructure\n    description: 'Structured documentation of the Torii App, User, Contract, and Audit objects.'\n  - name: Torii Spectral Rules\n    url: rules/torii-rules.yml\n    type: SpectralRules\n    description: 'Spectral ruleset for Torii API conventions.'\n  - name: Torii SaaS Governance Capability\n    url: capabilities/saas-governance.yaml\n    type: NaftikoCapability\n    description: 'Naftiko workflow capability for SaaS governance (REST + MCP, 14 tools).'\n  - name: Torii Vocabulary\n    url: vocabulary/torii-vocabulary.yml\n    type: Vocabulary\n    description: 'Domain vocabulary for the Torii SaaS Management Platform.'\n  - name: Features\n    type: Features\n    data:\n      - name: SaaS Management Platform\n      - name: Shadow IT Discovery\n      - name: App Lifecycle Management\n      - name: License Optimization\n      - name: Contract and Renewal\
  \ Management\n      - name: Workflow Automation\n      - name: User Onboarding and Offboarding\n      - name: SCIM 2.0 Provisioning\n      - name: Compliance Audit Logs\n      - name: Custom Integrations\n      - name: Browser Extension\n      - name: 180+ Native Integrations\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Shadow IT Discovery\n      - name: Onboarding and Offboarding Automation\n      - name: SaaS Spend Management\n      - name: SaaS Vendor and Renewal Management\n      - name: Compliance and Governance\n      - name: Open Platform Integration\n      - name: AI Powered SaaS Management\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Okta\n      - name: Microsoft Entra ID\n      - name: Google Workspace\n      - name: Slack\n      - name: Salesforce\n      - name: Jira Cloud\n      - name: GitHub Enterprise\n      - name: Azure DevOps\n      - name: Zoom\n      - name: Microsoft Teams\n      - name: Datadog\n      - name: ServiceNow\n\
  \      - name: BambooHR\n      - name: Workday HCM\n      - name: Rippling\n      - name: HubSpot\n      - name: Zendesk\n      - name: PagerDuty\n      - name: Confluence\n      - name: Notion\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/apis.yml
tags:
- Apps
- Compliance
- Cost Optimization
- Governance
- IT Management
- SaaS Management
url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/apis.yml
use_cases:
- name: Shadow IT Discovery
- name: Onboarding and Offboarding Automation
- name: SaaS Spend Management
- name: SaaS Vendor and Renewal Management
- name: Compliance and Governance
- name: Open Platform Integration
- name: AI Powered SaaS Management
---
