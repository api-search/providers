---
api_count: 1
api_specs:
- filename: cyclr-cyclr-openapi.yml
  format: yaml
  label: Cyclr API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/openapi/cyclr-cyclr-openapi.yml
apis:
- description: 'Cyclr''s REST API allows partners to manage their accounts, install and authenticate connectors, install templates as cycles, build and configure cycle steps, and embed LAUNCH and Marketplace UIs into '
  name: Cyclr API
  slug: api
asyncapis:
- description: AsyncAPI specification for Cyclr webhook events. Cyclr is an embedded iPaaS/integration platform that emits webhook notifications when key events occur within accounts, cycles, connectors, and templat
  name: Cyclr Webhook Events
  slug: cyclr-cyclr-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://cyclr.com/
- title: ''
  type: Connectors
  url: https://cyclr.com/connectors
- title: ''
  type: Pricing
  url: https://cyclr.com/product/pricing
- title: ''
  type: CaseStudies
  url: https://cyclr.com/case-studies
- title: ''
  type: Webinars
  url: https://cyclr.com/resources/webinars
- title: ''
  type: Blog
  url: https://cyclr.com/blog
- title: ''
  type: Branding
  url: https://cyclr.com/brand
- title: ''
  type: Partners
  url: https://cyclr.com/become-a-partner
- title: ''
  type: Security
  url: https://cyclr.com/security-and-compliance
- title: ''
  type: GDPR
  url: https://cyclr.com/legal/gdpr-compliance
- title: ''
  type: SLA
  url: https://cyclr.com/sla
- title: ''
  type: ChangeLog
  url: https://community.cyclr.com/user-documentation/release-notes/introduction-to-release-notes
- title: ''
  type: Login
  url: https://my.cyclr.com/account/login
- title: ''
  type: GetStarted
  url: https://cyclr.com/get-started
- title: ''
  type: Vocabulary
  url: vocabulary/cyclr-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/cyclr-api-capabilities.yml
- title: ''
  type: Rules
  url: rules/cyclr-api-rules.yml
created: '2025-06-06'
description: Cyclr is an embedded iPaaS (integration platform as a service) used by SaaS vendors to deliver native integrations to their customers without each vendor building and maintaining one-off connectors. The platform provides a connector library covering hundreds of business applications (CRM, marketing, finance, support, ERP, e-commerce), drag-and-drop integration templates, embedded LAUNCH and Marketplace UIs, custom connector creation, fully managed authentication, and workflow orchestration. Cyclr exposes a public REST API at api.cyclr.com (with regional EU / AU / UK / US2 siblings) protected by OAuth 2.0 client credentials. Account-scoped calls require an X-Cyclr-Account header to identify the target Cyclr account.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cyclr Context
  property_count: 6
  slug: cyclr-context
layout: provider
modified: '2026-04-28'
name: Cyclr
rules:
- name: Cyclr API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: cyclr-api-rules
skills: []
slug: cyclr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cyclr\nname: Cyclr\nx-type: company\ndescription: >-\n  Cyclr is an embedded iPaaS (integration platform as a service) used\n  by SaaS vendors to deliver native integrations to their customers\n  without each vendor building and maintaining one-off connectors. The\n  platform provides a connector library covering hundreds of business\n  applications (CRM, marketing, finance, support, ERP, e-commerce),\n  drag-and-drop integration templates, embedded LAUNCH and Marketplace\n  UIs, custom connector creation, fully managed authentication, and\n  workflow orchestration. Cyclr exposes a public REST API at\n  api.cyclr.com (with regional EU / AU / UK / US2 siblings) protected\n  by OAuth 2.0 client credentials. Account-scoped calls require an\n  X-Cyclr-Account header to identify the target Cyclr account.\nurl: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype:\
  \ Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-06-06'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Connectors\n  - Custom Connectors\n  - Data Synchronization\n  - Embedded iPaaS\n  - Embedded SaaS Integration\n  - Embedded UI\n  - Integration Platform\n  - Integrations\n  - Marketplace\n  - OAuth 2.0\n  - REST API\n  - SaaS\n  - Templates\n  - Webhooks\n  - White Label\n  - Workflows\napis:\n  - aid: cyclr:api\n    name: Cyclr API\n    description: >-\n      Cyclr's REST API allows partners to manage their accounts, install\n      and authenticate connectors, install templates as cycles, build\n      and configure cycle steps, and embed LAUNCH and Marketplace UIs\n      into their host SaaS product. Authentication uses OAuth 2.0\n      client credentials issued in the Cyclr Console; account-scoped\n      operations include the X-Cyclr-Account HTTP header.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://cyclr.com\n    baseURL: https://api.cyclr.com/v1.0\n    tags:\n      - Accounts\n      - Connectors\n      - Cycles\n      - Embedded UI\n      - OAuth 2.0\n      - REST\n      - Steps\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://cyclr.com\n      - type: APIDocumentation\n        url: https://docs.cyclr.com/api/\n      - type: APIReference\n        url: https://api.cyclr.com/docs/index\n      - type: OpenAPI\n        url: openapi/cyclr-cyclr-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/cyclr-cyclr-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/cyclr-account.json\n      - type: JSONSchema\n        url: json-schema/cyclr-connector.json\n      - type: JSONSchema\n        url: json-schema/cyclr-installed-connector.json\n      - type: JSONSchema\n        url: json-schema/cyclr-template.json\n      - type: JSONSchema\n        url: json-schema/cyclr-cycle.json\n      - type: JSONSchema\n        url: json-schema/cyclr-step.json\n\
  \      - type: JSONLD\n        url: json-ld/cyclr-context.jsonld\n      - type: Capabilities\n        url: capabilities/cyclr-api-capabilities.yml\n      - type: Rules\n        url: rules/cyclr-api-rules.yml\ncommon:\n  - type: Website\n    url: https://cyclr.com/\n  - type: Connectors\n    url: https://cyclr.com/connectors\n  - type: Pricing\n    url: https://cyclr.com/product/pricing\n  - type: CaseStudies\n    url: https://cyclr.com/case-studies\n  - type: Webinars\n    url: https://cyclr.com/resources/webinars\n  - type: Blog\n    url: https://cyclr.com/blog\n  - type: Branding\n    url: https://cyclr.com/brand\n  - type: Partners\n    url: https://cyclr.com/become-a-partner\n  - type: Security\n    url: https://cyclr.com/security-and-compliance\n  - type: GDPR\n    url: https://cyclr.com/legal/gdpr-compliance\n  - type: SLA\n    url: https://cyclr.com/sla\n  - type: ChangeLog\n    url: https://community.cyclr.com/user-documentation/release-notes/introduction-to-release-notes\n  -\
  \ type: Login\n    url: https://my.cyclr.com/account/login\n  - type: GetStarted\n    url: https://cyclr.com/get-started\n  - type: Vocabulary\n    url: vocabulary/cyclr-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/cyclr-api-capabilities.yml\n  - type: Rules\n    url: rules/cyclr-api-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml
tags:
- Connectors
- Custom Connectors
- Data Synchronization
- Embedded iPaaS
- Embedded SaaS Integration
- Embedded UI
- Integration Platform
- Integrations
- Marketplace
- OAuth 2.0
- REST API
- SaaS
- Templates
- Webhooks
- White Label
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml
use_cases: []
---
