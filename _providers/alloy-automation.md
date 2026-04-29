---
api_count: 3
apis:
- description: The Alloy Embedded API enables SaaS companies to embed native integration workflows directly in their products. Manage end users, retrieve available integrations, trigger events, monitor workflow exec
  name: Alloy Automation Embedded API
  slug: embedded-api
- description: The Alloy Connectivity API enables companies to build native integration UIs with a single API endpoint. Manage users, discover connector resources, configure credentials, and execute connector action
  name: Alloy Automation Connectivity API
  slug: connectivity-api
- description: The Alloy Unified API enables companies to accomplish access-based app integrations across commerce, CRM, ERP, and other categories through a single standardized interface.
  name: Alloy Automation Unified API
  slug: unified-api
capabilities:
- description: ''
  name: Integration Platform
  slug: integration-platform
common:
- title: ''
  type: Website
  url: https://runalloy.com/
- title: ''
  type: Documentation
  url: https://docs.runalloy.com/
- title: ''
  type: Blog
  url: https://runalloy.com/blog/
- title: ''
  type: Pricing
  url: https://runalloy.com/platform/pricing/
- title: ''
  type: StatusPage
  url: https://status.runalloy.com/
- title: ''
  type: About
  url: https://runalloy.com/about-us/
- title: ''
  type: GitHubOrganization
  url: https://github.com/alloy-automation
- title: Node.js SDK
  type: SDK
  url: https://github.com/alloy-automation/alloy-node
- title: Python SDK
  type: SDK
  url: https://github.com/alloy-automation/alloy-python
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/alloy-automation
- title: ''
  type: SpectralRules
  url: rules/alloy-automation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/alloy-automation-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/integration-platform.yaml
created: '2026-03-16'
description: Alloy Automation is the all-in-one integration infrastructure platform for SaaS and AI, offering embedded iPaaS, unified API, and connectivity API products that let companies launch native integrations, build workflows, and connect to 1000+ apps with a single endpoint.
features:
- description: Drag-and-drop orchestration platform for shipping native integrations directly in your SaaS product, handling auth, deployment, and observability.
  name: Embedded iPaaS
- description: Single endpoint to access 1000+ third-party app connectors with built-in credential management, resource discovery, and real-time action execution.
  name: Connectivity API
- description: Model Context Protocol server providing AI agents secure, remote-hosted access to 1000+ tools with built-in context, permissioning, and authentication.
  name: MCP Server
- description: Visual workflow builder with logic blocks (Branch, If-Else, Iterate, Error Handler) and data transformation for building complex automation flows.
  name: Workflow Builder
- description: Self-service integration marketplace experience enabling end users to discover, install, and configure integrations within your product.
  name: Installation Manager
- description: Build custom connectors for proprietary or internal APIs using Alloy's connector framework with custom OAuth and authentication handling.
  name: Custom Connectors
- description: Custom event triggers and webhook destinations for real-time integration workflows responding to external events.
  name: Webhook Support
- description: GDPR, CCPA, HIPAA, and SOC 2 compliance with user data purging, static IP addresses, encryption, and SSO/SAML support.
  name: Compliance Controls
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: E-commerce order management, product catalog, and customer data integration
  name: Shopify
- description: CRM contact, opportunity, and account sync integration
  name: Salesforce
- description: Accounting GL sync, invoice creation, and payment reconciliation
  name: QuickBooks
- description: CRM and marketing automation contact and deal sync
  name: HubSpot
- description: Anthropic Claude AI agent integration via Alloy MCP server
  name: Claude
- description: LangChain AI agent integration using Alloy MCP tools
  name: LangChain
- description: Vercel AI SDK integration for building AI-powered workflows
  name: Vercel AI SDK
jsonld:
- class_count: 0
  name: Alloy Automation Connectivity Context
  property_count: 22
  slug: alloy-automation-connectivity-context
- class_count: 0
  name: Alloy Automation Embedded Context
  property_count: 23
  slug: alloy-automation-embedded-context
layout: provider
modified: '2026-04-19'
name: Alloy Automation
rules:
- name: Alloy Automation API Rules
  rule_count: 16
  severity_counts:
    error: 4
    hint: 0
    info: 5
    warn: 7
  slug: alloy-automation-spectral-rules
skills: []
slug: alloy-automation
solutions: []
source_yaml: "aid: alloy-automation\nname: Alloy Automation\ndescription: >-\n  Alloy Automation is the all-in-one integration infrastructure platform for\n  SaaS and AI, offering embedded iPaaS, unified API, and connectivity API\n  products that let companies launch native integrations, build workflows, and\n  connect to 1000+ apps with a single endpoint.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Embedded Integrations\n  - Integrations\n  - iPaaS\n  - Unified API\n  - Workflows\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alloy-automation:embedded-api\n    name: Alloy Automation Embedded API\n    description: >-\n      The Alloy Embedded API enables SaaS companies to embed native integration\n      workflows directly in their products. Manage end users, retrieve\
  \ available\n      integrations, trigger events, monitor workflow execution, and control workflow\n      lifecycle for your embedded iPaaS experience.\n    humanURL: https://docs.runalloy.com/embedded/quick-start\n    baseURL: https://embedded.runalloy.com/2025-09\n    tags:\n      - Embedded\n      - iPaaS\n      - Workflows\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.runalloy.com/embedded/quick-start\n      - type: OpenAPI\n        url: openapi/alloy-automation-embedded.yaml\n      - type: JSONSchema\n        url: json-schema/alloy-embedded-user-schema.json\n      - type: JSONStructure\n        url: json-structure/alloy-embedded-user-structure.json\n      - type: JSONLD\n        url: json-ld/alloy-automation-embedded-context.jsonld\n      - type: Example\n        url: examples/alloy-embedded-user-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/embedded.yaml\n\n  - aid: alloy-automation:connectivity-api\n    name:\
  \ Alloy Automation Connectivity API\n    description: >-\n      The Alloy Connectivity API enables companies to build native integration UIs\n      with a single API endpoint. Manage users, discover connector resources, configure\n      credentials, and execute connector actions across 1000+ third-party applications.\n    humanURL: https://docs.runalloy.com/connectivity-api/quick-start\n    baseURL: https://production.runalloy.com\n    tags:\n      - Connectivity\n      - Integrations\n      - Unified API\n      - Connectors\n    properties:\n      - type: Documentation\n        url: https://docs.runalloy.com/connectivity-api/quick-start\n      - type: OpenAPI\n        url: openapi/alloy-automation-connectivity.yaml\n      - type: JSONSchema\n        url: json-schema/alloy-connectivity-connector-schema.json\n      - type: JSONStructure\n        url: json-structure/alloy-connectivity-connector-structure.json\n      - type: JSONLD\n        url: json-ld/alloy-automation-connectivity-context.jsonld\n\
  \      - type: Example\n        url: examples/alloy-connectivity-connector-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/connectivity.yaml\n\n  - aid: alloy-automation:unified-api\n    name: Alloy Automation Unified API\n    description: >-\n      The Alloy Unified API enables companies to accomplish access-based app\n      integrations across commerce, CRM, ERP, and other categories through a\n      single standardized interface.\n    humanURL: https://docs.runalloy.com/unified-api/1.0.0/getting-started/quick-start/\n    baseURL: https://production.runalloy.com\n    tags:\n      - Commerce\n      - CRM\n      - ERP\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.runalloy.com/unified-api/1.0.0/getting-started/quick-start/\n\ncommon:\n  - url: https://runalloy.com/\n    type: Website\n  - url: https://docs.runalloy.com/\n    type: Documentation\n  - url: https://runalloy.com/blog/\n    type: Blog\n  - url: https://runalloy.com/platform/pricing/\n\
  \    type: Pricing\n  - url: https://status.runalloy.com/\n    type: StatusPage\n  - url: https://runalloy.com/about-us/\n    type: About\n  - url: https://github.com/alloy-automation\n    type: GitHubOrganization\n  - url: https://github.com/alloy-automation/alloy-node\n    title: Node.js SDK\n    type: SDK\n  - url: https://github.com/alloy-automation/alloy-python\n    title: Python SDK\n    type: SDK\n  - url: https://www.linkedin.com/company/alloy-automation\n    type: LinkedIn\n  - url: rules/alloy-automation-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/alloy-automation-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/integration-platform.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Embedded iPaaS\n        description: >-\n          Drag-and-drop orchestration platform for shipping native integrations\n          directly in your SaaS product, handling auth, deployment, and observability.\n      - name: Connectivity\
  \ API\n        description: >-\n          Single endpoint to access 1000+ third-party app connectors with built-in\n          credential management, resource discovery, and real-time action execution.\n      - name: MCP Server\n        description: >-\n          Model Context Protocol server providing AI agents secure, remote-hosted\n          access to 1000+ tools with built-in context, permissioning, and authentication.\n      - name: Workflow Builder\n        description: >-\n          Visual workflow builder with logic blocks (Branch, If-Else, Iterate,\n          Error Handler) and data transformation for building complex automation flows.\n      - name: Installation Manager\n        description: >-\n          Self-service integration marketplace experience enabling end users to\n          discover, install, and configure integrations within your product.\n      - name: Custom Connectors\n        description: >-\n          Build custom connectors for proprietary or internal APIs using\
  \ Alloy's\n          connector framework with custom OAuth and authentication handling.\n      - name: Webhook Support\n        description: >-\n          Custom event triggers and webhook destinations for real-time integration\n          workflows responding to external events.\n      - name: Compliance Controls\n        description: >-\n          GDPR, CCPA, HIPAA, and SOC 2 compliance with user data purging, static\n          IP addresses, encryption, and SSO/SAML support.\n  - type: UseCases\n    data:\n      - name: Native Integration Marketplace\n        description: >-\n          Embed a branded integration marketplace in your SaaS product allowing\n          customers to self-serve connections to Shopify, Salesforce, NetSuite, and 1000+ apps.\n      - name: AI Agent Integration\n        description: >-\n          Connect LLM-powered AI agents to third-party business applications using\n          the Alloy MCP server with Claude, LangChain, and Vercel AI SDK.\n      - name: E-Commerce\
  \ Automation\n        description: >-\n          Automate order management, returns, 3PL fulfillment, and inventory sync\n          across Shopify, BigCommerce, WooCommerce, and marketplace platforms.\n      - name: Accounting Integration\n        description: >-\n          Sync general ledger entries, invoices, and journal entries between your\n          platform and QuickBooks, NetSuite, Xero, and SAP.\n  - type: Integrations\n    data:\n      - name: Shopify\n        description: E-commerce order management, product catalog, and customer data integration\n      - name: Salesforce\n        description: CRM contact, opportunity, and account sync integration\n      - name: QuickBooks\n        description: Accounting GL sync, invoice creation, and payment reconciliation\n      - name: HubSpot\n        description: CRM and marketing automation contact and deal sync\n      - name: Claude\n        description: Anthropic Claude AI agent integration via Alloy MCP server\n      - name: LangChain\n\
  \        description: LangChain AI agent integration using Alloy MCP tools\n      - name: Vercel AI SDK\n        description: Vercel AI SDK integration for building AI-powered workflows\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/apis.yml
tags:
- Automation
- Embedded Integrations
- Integrations
- iPaaS
- Unified API
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/apis.yml
use_cases:
- description: Embed a branded integration marketplace in your SaaS product allowing customers to self-serve connections to Shopify, Salesforce, NetSuite, and 1000+ apps.
  name: Native Integration Marketplace
- description: Connect LLM-powered AI agents to third-party business applications using the Alloy MCP server with Claude, LangChain, and Vercel AI SDK.
  name: AI Agent Integration
- description: Automate order management, returns, 3PL fulfillment, and inventory sync across Shopify, BigCommerce, WooCommerce, and marketplace platforms.
  name: E-Commerce Automation
- description: Sync general ledger entries, invoices, and journal entries between your platform and QuickBooks, NetSuite, Xero, and SAP.
  name: Accounting Integration
---
