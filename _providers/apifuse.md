---
api_count: 1
api_specs:
- filename: apifuse-api.yaml
  format: yaml
  label: Apifuse API
  slug: apifuse-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/openapi/apifuse-api.yaml
apis:
- description: The Apifuse API enables developers to programmatically manage embedded integrations, connectors, workflows, and user authentication within their SaaS applications. Build and monitor native integration
  name: Apifuse API
  slug: apifuse-api
capabilities:
- description: Unified workflow for managing embedded integrations within SaaS products - browsing connectors, building workflows, monitoring usage analytics, and managing user connections.
  name: Apifuse Embedded Integration Management
  slug: embedded-integration-management
common:
- title: ''
  type: Website
  url: https://apifuse.io/
- title: ''
  type: Documentation
  url: https://docs.apifuse.io/
- title: ''
  type: GettingStarted
  url: https://docs.apifuse.io/getting-started
- title: ''
  type: Pricing
  url: https://apifuse.io/pricing
- title: ''
  type: Blog
  url: https://apifuse.io/blog
- title: ''
  type: SignUp
  url: https://app.apifuse.io/register
- title: ''
  type: Login
  url: https://app.apifuse.io/login
- title: ''
  type: GitHubOrganization
  url: https://github.com/apifuse
created: '2026-03-16'
description: Apifuse is a native integration platform that enables SaaS companies to build and embed integrations directly into their products. It provides a white-label integration solution with pre-built connectors across 20+ categories, an embeddable UI, workflow automation, and analytics tools that help developers add native integrations without building from scratch.
features:
- description: Build a branded integration marketplace within your SaaS product, allowing customers to connect their preferred business tools.
  name: Embedded Integration Marketplace
- description: 150+ pre-built connectors across 20+ categories including CRM, Accounting, Email, Project Management, and more.
  name: Pre-Built Connectors
- description: Visual workflow builder with triggers (polling, realtime, scheduled, webhook) and steps (actions, conditionals, loops, delays, scripts).
  name: Workflow Builder
- description: Fully white-labeled integration UI that embeds seamlessly into your product's look and feel.
  name: White-Label Solution
- description: Build custom connectors for proprietary or internal systems using the Apifuse SDK.
  name: Custom Connector SDK
- description: Track integration usage, task counts, active users, and monitor workflow health in real time.
  name: Analytics and Monitoring
- description: Manage user OAuth connections, API keys, and integration authentication within your platform.
  name: User Authentication
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: CRM integration for managing leads, contacts, and opportunities.
  name: Salesforce
- description: Email marketing integration for campaign management and audience sync.
  name: Mailchimp
- description: E-signature integration for document workflow automation.
  name: DocuSign
- description: Communication integration for notifications and workflow triggers.
  name: Slack
- description: Accounting integration for financial data synchronization.
  name: QuickBooks
- description: CRM and marketing automation integration.
  name: HubSpot
jsonld:
- class_count: 6
  name: Apifuse Context
  property_count: 8
  slug: apifuse-context
layout: provider
modified: '2026-04-19'
name: Apifuse
rules:
- name: Apifuse API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: apifuse-spectral-rules
skills: []
slug: apifuse
solutions:
- description: Up to 500,000 tasks/month with 6 pre-built connectors for companies starting with embedded integrations.
  name: Growth Plan
- description: Up to 5,000,000 tasks/month with unlimited pre-built connectors for established SaaS companies.
  name: Platform Plan
- description: Custom task volume, fully managed integrations, and dedicated support for enterprise SaaS platforms.
  name: Enterprise Plan
source_filename: apis.yml
source_yaml: "aid: apifuse\nname: Apifuse\ndescription: >-\n  Apifuse is a native integration platform that enables SaaS companies to build\n  and embed integrations directly into their products. It provides a white-label\n  integration solution with pre-built connectors across 20+ categories, an\n  embeddable UI, workflow automation, and analytics tools that help developers\n  add native integrations without building from scratch.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Embedded Integrations\n  - Integration Platform\n  - Integrations\n  - iPaaS\n  - Marketplace\n  - SaaS\n  - Workflow Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apifuse:apifuse-api\n    name: Apifuse API\n    description: >-\n      The Apifuse API enables developers to programmatically manage embedded\n\
  \      integrations, connectors, workflows, and user authentication within their\n      SaaS applications. Build and monitor native integration marketplaces with\n      full programmatic control over the integration lifecycle.\n    humanURL: https://apifuse.io/\n    baseURL: https://api.apifuse.io\n    tags:\n      - Analytics\n      - Connectors\n      - Embedded Integrations\n      - Integrations\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.apifuse.io/\n      - type: GettingStarted\n        url: https://docs.apifuse.io/getting-started\n      - type: OpenAPI\n        url: openapi/apifuse-api.yaml\n      - type: Pricing\n        url: https://apifuse.io/pricing\n      - type: JSONSchema\n        url: json-schema/apifuse-integration-schema.json\n      - type: JSONSchema\n        url: json-schema/apifuse-workflow-schema.json\n      - type: JSONSchema\n        url: json-schema/apifuse-connector-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/apifuse-analytics-schema.json\n      - type: JSON-LD\n        url: json-ld/apifuse-context.jsonld\ncommon:\n  - type: Website\n    url: https://apifuse.io/\n  - type: Documentation\n    url: https://docs.apifuse.io/\n  - type: GettingStarted\n    url: https://docs.apifuse.io/getting-started\n  - type: Pricing\n    url: https://apifuse.io/pricing\n  - type: Blog\n    url: https://apifuse.io/blog\n  - type: SignUp\n    url: https://app.apifuse.io/register\n  - type: Login\n    url: https://app.apifuse.io/login\n  - type: GitHubOrganization\n    url: https://github.com/apifuse\n  - type: Features\n    data:\n      - name: Embedded Integration Marketplace\n        description: Build a branded integration marketplace within your SaaS product, allowing customers to connect their preferred business tools.\n      - name: Pre-Built Connectors\n        description: 150+ pre-built connectors across 20+ categories including CRM, Accounting, Email, Project Management, and more.\n    \
  \  - name: Workflow Builder\n        description: Visual workflow builder with triggers (polling, realtime, scheduled, webhook) and steps (actions, conditionals, loops, delays, scripts).\n      - name: White-Label Solution\n        description: Fully white-labeled integration UI that embeds seamlessly into your product's look and feel.\n      - name: Custom Connector SDK\n        description: Build custom connectors for proprietary or internal systems using the Apifuse SDK.\n      - name: Analytics and Monitoring\n        description: Track integration usage, task counts, active users, and monitor workflow health in real time.\n      - name: User Authentication\n        description: Manage user OAuth connections, API keys, and integration authentication within your platform.\n  - type: UseCases\n    data:\n      - name: SaaS Integration Marketplace\n        description: Embed a branded integration marketplace into your SaaS product to let customers connect Salesforce, Mailchimp, DocuSign,\
  \ and 150+ other tools.\n      - name: Workflow Automation\n        description: Allow customers to build no-code automation workflows between their connected apps and your platform.\n      - name: Platform Expansion\n        description: Transform a product into a comprehensive platform by adding native integration capabilities without building each connector from scratch.\n      - name: Customer Data Sync\n        description: Keep customer data synchronized across CRM, marketing automation, and your platform in real time.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: CRM integration for managing leads, contacts, and opportunities.\n      - name: Mailchimp\n        description: Email marketing integration for campaign management and audience sync.\n      - name: DocuSign\n        description: E-signature integration for document workflow automation.\n      - name: Slack\n        description: Communication integration for notifications and workflow\
  \ triggers.\n      - name: QuickBooks\n        description: Accounting integration for financial data synchronization.\n      - name: HubSpot\n        description: CRM and marketing automation integration.\n  - type: Solutions\n    data:\n      - name: Growth Plan\n        description: Up to 500,000 tasks/month with 6 pre-built connectors for companies starting with embedded integrations.\n      - name: Platform Plan\n        description: Up to 5,000,000 tasks/month with unlimited pre-built connectors for established SaaS companies.\n      - name: Enterprise Plan\n        description: Custom task volume, fully managed integrations, and dedicated support for enterprise SaaS platforms.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/apis.yml
tags:
- Embedded Integrations
- Integration Platform
- Integrations
- iPaaS
- Marketplace
- SaaS
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/apis.yml
use_cases:
- description: Embed a branded integration marketplace into your SaaS product to let customers connect Salesforce, Mailchimp, DocuSign, and 150+ other tools.
  name: SaaS Integration Marketplace
- description: Allow customers to build no-code automation workflows between their connected apps and your platform.
  name: Workflow Automation
- description: Transform a product into a comprehensive platform by adding native integration capabilities without building each connector from scratch.
  name: Platform Expansion
- description: Keep customer data synchronized across CRM, marketing automation, and your platform in real time.
  name: Customer Data Sync
---
