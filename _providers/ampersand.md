---
api_count: 1
api_specs:
- filename: ampersand-api-openapi-original.yml
  format: yaml
  label: Ampersand API
  slug: ampersand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/openapi/ampersand-api-openapi-original.yml
apis:
- description: The Ampersand API enables developers to programmatically manage integrations, connections, installations, destinations, and data flows for SaaS-to-SaaS connectivity. It provides endpoints for managing
  name: Ampersand API
  slug: ampersand-api
capabilities:
- description: Workflow capability for product developers and platform engineers to manage SaaS integrations, connections, installations, and destinations programmatically through the Ampersand platform.
  name: Ampersand Integration Management
  slug: integration-management
common:
- title: ''
  type: Website
  url: https://www.withampersand.com/
- title: ''
  type: Documentation
  url: https://docs.withampersand.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/amp-labs
- title: ''
  type: Blog
  url: https://www.withampersand.com/blog
- title: ''
  type: SignUp
  url: https://dashboard.withampersand.com/sign-up
- title: ''
  type: Login
  url: https://dashboard.withampersand.com/sign-in
- title: React UI SDK
  type: SDK
  url: https://www.npmjs.com/package/@amp-labs/react
- title: ''
  type: CLI
  url: https://github.com/amp-labs/cli
- title: ''
  type: SpectralRules
  url: rules/ampersand-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/ampersand-api.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/integration-management.yaml
- title: ''
  type: JSONLD
  url: json-ld/ampersand-api-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/ampersand-vocabulary.yaml
created: '2026-03-16'
description: Ampersand is a developer-first platform for building native SaaS integrations. It provides an embeddable UI component and managed infrastructure that lets developers add product integrations quickly, handling OAuth, data sync, webhooks, and field mapping out of the box. The platform supports hundreds of SaaS connectors including Salesforce, HubSpot, Marketo, Microsoft Dynamics 365, Zendesk, and Gong with bi-directional sync and declarative configuration.
features:
- description: Code-based, composable integration building that is version-controllable and CI/CD compatible for professional engineering workflows.
  name: Declarative Integration Framework
- description: Free auth token management with auto-refresh for all supported SaaS providers, eliminating OAuth complexity from product teams.
  name: Managed OAuth Authentication
- description: On-demand read/write operations, scheduled reads, and bulk write capabilities for synchronizing data between SaaS applications.
  name: Bi-directional Data Sync
- description: Authenticated passthrough requests to customer systems enabling direct API calls without managing OAuth tokens.
  name: Proxy API
- description: Historical data retrieval during customer onboarding to populate integrations with existing customer data.
  name: Backfill Support
- description: Automated retries, error handling, quota management, detailed logging, and alerting for production-grade integration reliability.
  name: DevOps Infrastructure
- description: Support for custom objects and fields allowing customers to configure integrations without being constrained by inflexible unified APIs.
  name: Custom Objects and Fields
- description: React UI library with pre-built integration setup flows enabling customers to configure their own SaaS connections within your product.
  name: Embeddable UI Components
- description: Official AI SDK enabling AI agents to read from and write to SaaS applications through natural language via Ampersand integrations.
  name: AI SDK
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Bi-directional CRM integration with Salesforce for contacts, accounts, opportunities, and custom objects.
  name: Salesforce
- description: CRM and marketing automation integration with HubSpot for contacts, deals, companies, and email tracking.
  name: HubSpot
- description: Marketing automation integration with Marketo for lead management, campaigns, and activity data.
  name: Marketo
- description: CRM integration with Microsoft Dynamics 365 for enterprise sales and customer service workflows.
  name: Microsoft Dynamics 365
- description: Customer support integration with Zendesk for tickets, users, organizations, and support metrics.
  name: Zendesk
- description: Conversation intelligence integration with Gong for call recordings, transcripts, and revenue insights.
  name: Gong
jsonld:
- class_count: 49
  name: Ampersand Api Context
  property_count: 113
  slug: ampersand-api-context
layout: provider
modified: '2026-04-19'
name: Ampersand
rules:
- name: Ampersand API Rules
  rule_count: 26
  severity_counts:
    error: 15
    hint: 0
    info: 2
    warn: 9
  slug: ampersand-spectral-rules
skills: []
slug: ampersand
solutions: []
source_filename: apis.yml
source_yaml: "aid: ampersand\nurl: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/apis.yml\nname: Ampersand\ndescription: >-\n  Ampersand is a developer-first platform for building native SaaS integrations.\n  It provides an embeddable UI component and managed infrastructure that lets\n  developers add product integrations quickly, handling OAuth, data sync,\n  webhooks, and field mapping out of the box. The platform supports hundreds of\n  SaaS connectors including Salesforce, HubSpot, Marketo, Microsoft Dynamics 365,\n  Zendesk, and Gong with bi-directional sync and declarative configuration.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Tools\n  - Integrations\n  - Platform\n  - SaaS\n  - OAuth\n  - Data Sync\n  - Webhooks\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: ampersand:ampersand-api\n    name: Ampersand API\n    description: >-\n      The Ampersand\
  \ API enables developers to programmatically manage\n      integrations, connections, installations, destinations, and data flows\n      for SaaS-to-SaaS connectivity. It provides endpoints for managing\n      installations, connections, destinations, API keys, projects, organizations,\n      providers, and integration configurations within the Ampersand platform.\n    humanURL: https://docs.withampersand.com/\n    baseURL: https://api.withampersand.com\n    tags:\n      - Integrations\n      - Platform\n      - SaaS\n      - OAuth\n      - Data Sync\n    properties:\n      - type: Documentation\n        url: https://docs.withampersand.com/\n      - type: GettingStarted\n        url: https://docs.withampersand.com/getting-started\n      - type: Authentication\n        url: https://docs.withampersand.com/reference/authentication\n      - type: OpenAPI\n        url: openapi/ampersand-api-openapi-original.yml\ncommon:\n  - type: Website\n    url: https://www.withampersand.com/\n  - type:\
  \ Documentation\n    url: https://docs.withampersand.com/\n  - type: GitHubOrganization\n    url: https://github.com/amp-labs\n  - type: Blog\n    url: https://www.withampersand.com/blog\n  - type: SignUp\n    url: https://dashboard.withampersand.com/sign-up\n  - type: Login\n    url: https://dashboard.withampersand.com/sign-in\n  - type: SDK\n    url: https://www.npmjs.com/package/@amp-labs/react\n    title: React UI SDK\n  - type: CLI\n    url: https://github.com/amp-labs/cli\n  - type: SpectralRules\n    url: rules/ampersand-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/ampersand-api.yaml\n  - type: NaftikoCapability\n    url: capabilities/integration-management.yaml\n  - type: JSONLD\n    url: json-ld/ampersand-api-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/ampersand-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Declarative Integration Framework\n        description: Code-based, composable integration building that is version-controllable\
  \ and CI/CD compatible for professional engineering workflows.\n      - name: Managed OAuth Authentication\n        description: Free auth token management with auto-refresh for all supported SaaS providers, eliminating OAuth complexity from product teams.\n      - name: Bi-directional Data Sync\n        description: On-demand read/write operations, scheduled reads, and bulk write capabilities for synchronizing data between SaaS applications.\n      - name: Proxy API\n        description: Authenticated passthrough requests to customer systems enabling direct API calls without managing OAuth tokens.\n      - name: Backfill Support\n        description: Historical data retrieval during customer onboarding to populate integrations with existing customer data.\n      - name: DevOps Infrastructure\n        description: Automated retries, error handling, quota management, detailed logging, and alerting for production-grade integration reliability.\n      - name: Custom Objects and Fields\n \
  \       description: Support for custom objects and fields allowing customers to configure integrations without being constrained by inflexible unified APIs.\n      - name: Embeddable UI Components\n        description: React UI library with pre-built integration setup flows enabling customers to configure their own SaaS connections within your product.\n      - name: AI SDK\n        description: Official AI SDK enabling AI agents to read from and write to SaaS applications through natural language via Ampersand integrations.\n  - type: UseCases\n    data:\n      - name: CRM Integration\n        description: Build native Salesforce, HubSpot, and Dynamics 365 integrations to sync customer data bidirectionally with your SaaS product.\n      - name: Marketing Automation Integration\n        description: Connect Marketo, HubSpot, and other marketing platforms to enable customer data flows for campaign automation and lead management.\n      - name: Customer Support Integration\n        description:\
  \ Integrate Zendesk and other support platforms to sync tickets, contacts, and customer data with your application.\n      - name: Conversation Intelligence Integration\n        description: Connect Gong and other conversation platforms to access call recordings, transcripts, and insights within your application.\n      - name: AI Agent Integration\n        description: Enable AI agents to read from and write to customer SaaS systems through the Ampersand AI SDK for autonomous workflow automation.\n      - name: Developer Portal Embedding\n        description: Embed Ampersand's React UI components into your product so customers can self-service configure their own SaaS integrations.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Bi-directional CRM integration with Salesforce for contacts, accounts, opportunities, and custom objects.\n      - name: HubSpot\n        description: CRM and marketing automation integration with HubSpot for contacts, deals,\
  \ companies, and email tracking.\n      - name: Marketo\n        description: Marketing automation integration with Marketo for lead management, campaigns, and activity data.\n      - name: Microsoft Dynamics 365\n        description: CRM integration with Microsoft Dynamics 365 for enterprise sales and customer service workflows.\n      - name: Zendesk\n        description: Customer support integration with Zendesk for tickets, users, organizations, and support metrics.\n      - name: Gong\n        description: Conversation intelligence integration with Gong for call recordings, transcripts, and revenue insights.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/apis.yml
tags:
- Developer Tools
- Integrations
- Platform
- SaaS
- OAuth
- Data Sync
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/apis.yml
use_cases:
- description: Build native Salesforce, HubSpot, and Dynamics 365 integrations to sync customer data bidirectionally with your SaaS product.
  name: CRM Integration
- description: Connect Marketo, HubSpot, and other marketing platforms to enable customer data flows for campaign automation and lead management.
  name: Marketing Automation Integration
- description: Integrate Zendesk and other support platforms to sync tickets, contacts, and customer data with your application.
  name: Customer Support Integration
- description: Connect Gong and other conversation platforms to access call recordings, transcripts, and insights within your application.
  name: Conversation Intelligence Integration
- description: Enable AI agents to read from and write to customer SaaS systems through the Ampersand AI SDK for autonomous workflow automation.
  name: AI Agent Integration
- description: Embed Ampersand's React UI components into your product so customers can self-service configure their own SaaS integrations.
  name: Developer Portal Embedding
---
