---
api_count: 2
api_specs:
- filename: albato-automations-openapi.yaml
  format: yaml
  label: Albato Automations API
  slug: automations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/openapi/albato-automations-openapi.yaml
- filename: albato-embedded-openapi.yaml
  format: yaml
  label: Albato Embedded API
  slug: embedded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/openapi/albato-embedded-openapi.yaml
apis:
- description: REST API for managing multi-step automation workflows in Albato. Supports creating, enabling, disabling, and monitoring automation executions across 1,000+ connected apps.
  name: Albato Automations API
  slug: automations-api
- description: REST API for Albato Embedded iPaaS enabling SaaS companies to manage customer teams, app connectors, and automation templates for white-label integration delivery.
  name: Albato Embedded API
  slug: embedded-api
capabilities:
- description: Workflow capability for managing no-code automation and embedded iPaaS functionality in Albato. Combines automation workflow management and embedded team management to support operations teams and Saa
  name: Albato iPaaS Automation
  slug: ipaas-automation
common:
- title: ''
  type: Website
  url: https://albato.com
- title: ''
  type: Documentation
  url: https://wiki.albato.com/en
- title: Albato Embedded iPaaS
  type: GettingStarted
  url: https://albato.com/embedded
- title: ''
  type: Pricing
  url: https://albato.com/pricing
- title: Albato Embedded Pricing
  type: Pricing
  url: https://albato.com/embedded/pricing
- title: ''
  type: Blog
  url: https://albato.com/blog/all
- title: ''
  type: CaseStudies
  url: https://albato.com/blog/case-studies
- title: ''
  type: FAQ
  url: https://wiki.albato.com/en/collections/8343168-faq
- title: ''
  type: Licensing
  url: https://albato.com/license
- title: ''
  type: PrivacyPolicy
  url: https://albato.com/privacy
- title: ''
  type: FacebookGroup
  url: https://www.facebook.com/groups/albatocommunity
- title: ''
  type: Roadmap
  url: https://roadmap.albato.com/public
- title: ''
  type: SpectralRules
  url: rules/albato-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/albato-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/albato-albato-context.jsonld
- title: Albato Automations Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/automations-api.yaml
- title: Albato Embedded Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/embedded-api.yaml
- title: iPaaS Automation Workflow
  type: NaftikoCapability
  url: capabilities/ipaas-automation.yaml
created: '2025-06-06'
description: Albato is a no-code automation platform and embedded iPaaS that enables businesses to automate workflows by connecting 1,000+ apps without writing code. Supports multi-step automations with triggers, actions, conditions, and delays. Albato Embedded allows SaaS companies to offer white-label native integrations to their customers.
features:
- description: Visual automation builder for creating multi-step workflows connecting 1,000+ apps without writing code, with conditions, delays, and data transformations.
  name: No-Code Automation Builder
- description: Pre-built connectors for CRM, marketing, e-commerce, communication, and productivity apps including HubSpot, Salesforce, Google Workspace, Slack, Shopify, and more.
  name: 1,000+ App Integrations
- description: White-label integration platform for SaaS companies to embed Albato's automation capabilities natively in their products with full branding control.
  name: Albato Embedded iPaaS
- description: Support for complex automations with sequential and conditional steps, delays, loops, and data transformations without coding.
  name: Multi-Step Workflows
- description: Webhook-based real-time triggers for instant event processing and scheduled polling triggers for API-based app integrations.
  name: Real-Time and Scheduled Triggers
- description: Build custom API connectors from any REST API using the App Integrator without development handoff, supporting all major auth methods.
  name: Custom App Integrator
- description: Detailed execution history with step-level logging, success/error rates, real-time notifications, and dashboard insights.
  name: Execution Monitoring
- description: Built-in data mapping, field transformation, and JavaScript code steps for processing data between connected apps.
  name: Data Transformation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: CRM and marketing automation for contact and deal management.
  name: HubSpot
- description: Enterprise CRM for sales pipeline and opportunity workflows.
  name: Salesforce
- description: Google Sheets, Gmail, Drive, Calendar, and Forms integrations.
  name: Google Workspace
- description: Team messaging integration for workflow notifications and alerts.
  name: Slack
- description: E-commerce integration for order, product, and customer automation.
  name: Shopify
- description: Payment processing integration for subscription and payment workflows.
  name: Stripe
- description: Workspace integration for task and project data synchronization.
  name: Notion
- description: Database integration for spreadsheet and grid data workflows.
  name: Airtable
jsonld:
- class_count: 0
  name: Albato Albato Context
  property_count: 36
  slug: albato-albato-context
layout: provider
modified: '2026-04-19'
name: Albato
rules:
- name: Albato API Rules
  rule_count: 24
  severity_counts:
    error: 15
    hint: 0
    info: 0
    warn: 9
  slug: albato-spectral-rules
skills: []
slug: albato
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: albato\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/apis.yml\nname: Albato\ntags:\n  - No-Code Automation\n  - Workflow Automation\n  - Embedded iPaaS\n  - App Integration\n  - Integrations\n  - Webhooks\n  - White-Label\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Albato is a no-code automation platform and embedded iPaaS that enables\n  businesses to automate workflows by connecting 1,000+ apps without writing\n  code. Supports multi-step automations with triggers, actions, conditions,\n  and delays. Albato Embedded allows SaaS companies to offer white-label\n  native integrations to their customers.\ncreated: '2025-06-06'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: albato:automations-api\n    name: Albato Automations API\n    tags:\n      - Automation\n      - Workflow\n      - No-Code\n      - Executions\n    properties:\n      - url:\
  \ https://albato.com\n        type: Documentation\n      - url: openapi/albato-automations-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/albato-albato-automations-automation-schema.json\n        type: JSONSchema\n      - url: json-schema/albato-albato-automations-automation-step-schema.json\n        type: JSONSchema\n      - url: json-schema/albato-albato-automations-execution-schema.json\n        type: JSONSchema\n      - url: json-structure/albato-albato-automations-automation-structure.json\n        type: JSONStructure\n      - url: json-structure/albato-albato-automations-automation-step-structure.json\n        type: JSONStructure\n      - url: json-structure/albato-albato-automations-execution-structure.json\n        type: JSONStructure\n      - url: examples/albato-albato-automations-automation-example.json\n        type: Example\n      - url: examples/albato-albato-automations-automation-step-example.json\n        type: Example\n      - url: examples/albato-albato-automations-execution-example.json\n\
  \        type: Example\n    humanURL: https://albato.com\n    baseURL: https://albato.com/api/v1\n    description: >-\n      REST API for managing multi-step automation workflows in Albato. Supports\n      creating, enabling, disabling, and monitoring automation executions across\n      1,000+ connected apps.\n\n  - aid: albato:embedded-api\n    name: Albato Embedded API\n    tags:\n      - Embedded iPaaS\n      - White-Label\n      - Teams\n      - Connectors\n      - Templates\n    properties:\n      - url: https://albato.com/embedded\n        type: Documentation\n      - url: openapi/albato-embedded-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/albato-albato-embedded-team-schema.json\n        type: JSONSchema\n      - url: json-schema/albato-albato-embedded-user-schema.json\n        type: JSONSchema\n      - url: json-schema/albato-albato-embedded-connector-schema.json\n        type: JSONSchema\n      - url: json-schema/albato-albato-embedded-template-schema.json\n \
  \       type: JSONSchema\n      - url: json-structure/albato-albato-embedded-team-structure.json\n        type: JSONStructure\n      - url: json-structure/albato-albato-embedded-user-structure.json\n        type: JSONStructure\n      - url: json-structure/albato-albato-embedded-connector-structure.json\n        type: JSONStructure\n      - url: json-structure/albato-albato-embedded-template-structure.json\n        type: JSONStructure\n      - url: examples/albato-albato-embedded-team-example.json\n        type: Example\n      - url: examples/albato-albato-embedded-user-example.json\n        type: Example\n      - url: examples/albato-albato-embedded-connector-example.json\n        type: Example\n      - url: examples/albato-albato-embedded-template-example.json\n        type: Example\n    humanURL: https://albato.com/embedded\n    baseURL: https://albato.com/api/v1/embedded\n    description: >-\n      REST API for Albato Embedded iPaaS enabling SaaS companies to manage\n      customer\
  \ teams, app connectors, and automation templates for white-label\n      integration delivery.\n\ncommon:\n  - url: https://albato.com\n    type: Website\n  - url: https://wiki.albato.com/en\n    type: Documentation\n  - url: https://albato.com/embedded\n    type: GettingStarted\n    title: Albato Embedded iPaaS\n  - url: https://albato.com/pricing\n    type: Pricing\n  - url: https://albato.com/embedded/pricing\n    type: Pricing\n    title: Albato Embedded Pricing\n  - url: https://albato.com/apps/all-integrations\n    type: Integrations\n    title: 1,000+ App Integrations\n  - url: https://albato.com/blog/all\n    type: Blog\n  - url: https://albato.com/blog/case-studies\n    type: CaseStudies\n  - url: https://wiki.albato.com/en/collections/8343168-faq\n    type: FAQ\n  - url: https://albato.com/license\n    type: Licensing\n  - url: https://albato.com/privacy\n    type: PrivacyPolicy\n  - url: https://www.facebook.com/groups/albatocommunity\n    type: FacebookGroup\n  - url: https://roadmap.albato.com/public\n\
  \    type: Roadmap\n  - url: rules/albato-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/albato-vocabulary.yaml\n    type: Vocabulary\n  - url: json-ld/albato-albato-context.jsonld\n    type: JSONLD\n  - url: capabilities/shared/automations-api.yaml\n    type: NaftikoCapability\n    title: Albato Automations Shared Capability\n  - url: capabilities/shared/embedded-api.yaml\n    type: NaftikoCapability\n    title: Albato Embedded Shared Capability\n  - url: capabilities/ipaas-automation.yaml\n    type: NaftikoCapability\n    title: iPaaS Automation Workflow\n  - type: Features\n    data:\n      - name: No-Code Automation Builder\n        description: >-\n          Visual automation builder for creating multi-step workflows connecting\n          1,000+ apps without writing code, with conditions, delays, and data\n          transformations.\n      - name: 1,000+ App Integrations\n        description: >-\n          Pre-built connectors for CRM, marketing, e-commerce, communication,\n\
  \          and productivity apps including HubSpot, Salesforce, Google Workspace,\n          Slack, Shopify, and more.\n      - name: Albato Embedded iPaaS\n        description: >-\n          White-label integration platform for SaaS companies to embed Albato's\n          automation capabilities natively in their products with full branding\n          control.\n      - name: Multi-Step Workflows\n        description: >-\n          Support for complex automations with sequential and conditional steps,\n          delays, loops, and data transformations without coding.\n      - name: Real-Time and Scheduled Triggers\n        description: >-\n          Webhook-based real-time triggers for instant event processing and\n          scheduled polling triggers for API-based app integrations.\n      - name: Custom App Integrator\n        description: >-\n          Build custom API connectors from any REST API using the App Integrator\n          without development handoff, supporting all major auth\
  \ methods.\n      - name: Execution Monitoring\n        description: >-\n          Detailed execution history with step-level logging, success/error rates,\n          real-time notifications, and dashboard insights.\n      - name: Data Transformation\n        description: >-\n          Built-in data mapping, field transformation, and JavaScript code steps\n          for processing data between connected apps.\n  - type: UseCases\n    data:\n      - name: CRM and Marketing Automation\n        description: >-\n          Sync leads between CRM and marketing tools, automate email campaigns,\n          and route prospects based on behavioral conditions.\n      - name: E-Commerce Order Processing\n        description: >-\n          Automate order notifications, inventory updates, fulfillment triggers,\n          and customer communication across e-commerce platforms.\n      - name: SaaS Native Integration Delivery\n        description: >-\n          Use Albato Embedded to offer customers white-labeled\
  \ integrations in\n          your SaaS product without in-house iPaaS development.\n      - name: Customer Support Automation\n        description: >-\n          Route tickets, trigger alerts, and sync customer data between helpdesk,\n          CRM, and communication platforms automatically.\n      - name: Data Synchronization\n        description: >-\n          Keep data consistent across business systems with bidirectional syncs,\n          scheduled automations, and event-driven updates.\n  - type: Integrations\n    data:\n      - name: HubSpot\n        description: CRM and marketing automation for contact and deal management.\n      - name: Salesforce\n        description: Enterprise CRM for sales pipeline and opportunity workflows.\n      - name: Google Workspace\n        description: Google Sheets, Gmail, Drive, Calendar, and Forms integrations.\n      - name: Slack\n        description: Team messaging integration for workflow notifications and alerts.\n      - name: Shopify\n  \
  \      description: E-commerce integration for order, product, and customer automation.\n      - name: Stripe\n        description: Payment processing integration for subscription and payment workflows.\n      - name: Notion\n        description: Workspace integration for task and project data synchronization.\n      - name: Airtable\n        description: Database integration for spreadsheet and grid data workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/apis.yml
tags:
- No-Code Automation
- Workflow Automation
- Embedded iPaaS
- App Integration
- Integrations
- Webhooks
- White-Label
url: https://raw.githubusercontent.com/api-evangelist/albato/refs/heads/main/apis.yml
use_cases:
- description: Sync leads between CRM and marketing tools, automate email campaigns, and route prospects based on behavioral conditions.
  name: CRM and Marketing Automation
- description: Automate order notifications, inventory updates, fulfillment triggers, and customer communication across e-commerce platforms.
  name: E-Commerce Order Processing
- description: Use Albato Embedded to offer customers white-labeled integrations in your SaaS product without in-house iPaaS development.
  name: SaaS Native Integration Delivery
- description: Route tickets, trigger alerts, and sync customer data between helpdesk, CRM, and communication platforms automatically.
  name: Customer Support Automation
- description: Keep data consistent across business systems with bidirectional syncs, scheduled automations, and event-driven updates.
  name: Data Synchronization
---
