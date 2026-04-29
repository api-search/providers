---
api_count: 1
api_specs:
- filename: activepieces.json
  format: json
  label: Activepieces API
  slug: activepieces-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/openapi/activepieces.json
apis:
- description: The Activepieces API provides programmatic access to the automation platform, enabling management of flows, connections, projects, users, folders, pieces, templates, and execution monitoring. Uses Bea
  name: Activepieces API
  slug: activepieces-api
capabilities:
- description: Unified workflow capability for building, managing, monitoring, and debugging automation flows. Used by developers and no-code builders to orchestrate integrations across 400+ app connections.
  name: Activepieces Workflow Automation
  slug: workflow-automation
common:
- title: ''
  type: Portal
  url: https://www.activepieces.com/
- title: ''
  type: Documentation
  url: https://www.activepieces.com/docs/
- title: ''
  type: GettingStarted
  url: https://www.activepieces.com/docs/getting-started/introduction
- title: ''
  type: Authentication
  url: https://www.activepieces.com/docs/endpoints/overview
- title: ''
  type: Pricing
  url: https://www.activepieces.com/pricing
- title: ''
  type: GitHubOrganization
  url: https://github.com/activepieces
- title: ''
  type: GitHubRepository
  url: https://github.com/activepieces/activepieces
- title: ''
  type: StatusPage
  url: https://status.activepieces.com/
- title: ''
  type: SpectralRules
  url: rules/activepieces-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/activepieces-vocabulary.yaml
- title: Activepieces API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/activepieces.yaml
- title: Workflow Automation Capability
  type: NaftikoCapability
  url: capabilities/workflow-automation.yaml
- title: Activepieces Context
  type: JSON-LD
  url: json-ld/activepieces-context.jsonld
created: '2026-03-16'
description: Activepieces is an open-source, no-code automation platform that enables users to streamline workflows by connecting various applications and automating tasks. It supports over 400 MCP servers and integrations, allowing developers to build custom TypeScript-based pieces. The platform offers AI agents, MCPs, and workflow automation capabilities with both cloud and self-hosted deployment options.
features:
- description: No-code drag-and-drop interface for building automation workflows with triggers and actions.
  name: Visual Flow Builder
- description: Over 400 pre-built integrations (pieces) written in TypeScript, available as MCP servers for AI agents.
  name: 400+ Integration Pieces
- description: Native AI agent creation and orchestration within automation workflows.
  name: AI Agents
- description: Every piece automatically becomes an MCP server for use with AI agents and LLMs like Claude.
  name: MCP Servers
- description: Build custom TypeScript-based integration pieces and publish them to npm.
  name: Custom Pieces
- description: Version control for flows with publish/draft states and rollback capabilities.
  name: Flow Versioning
- description: Add approval steps, delays, and human decision points in automation workflows.
  name: Human-in-the-Loop
- description: Deploy on Docker, Kubernetes, AWS, GCP, or any cloud provider with full data control.
  name: Self-Hosting
- description: Synchronize flows with Git repositories for version control and CI/CD integration.
  name: Git Sync
- description: Trigger flows via webhooks from any external system or service.
  name: Webhook Triggers
- description: Full programmatic access to manage flows, connections, projects, and execution history.
  name: REST API
- description: Share and reuse flow templates across projects and teams.
  name: Flow Templates
image: /assets/icons/activepieces.png
integrations:
- description: Trigger workflows on GitHub events and automate repository operations.
  name: GitHub
- description: Send emails, parse inbound mail, and automate email workflows.
  name: Gmail
- description: Send notifications, create channels, and respond to Slack events.
  name: Slack
- description: Integrate GPT models for AI-powered automation and content generation.
  name: OpenAI
- description: Read and write data to Google Sheets for data synchronization workflows.
  name: Google Sheets
- description: Sync records and trigger workflows from Airtable database changes.
  name: Airtable
- description: Create and update Salesforce records from automation workflows.
  name: Salesforce
- description: Trigger flows on payment events and automate billing operations.
  name: Stripe
jsonld:
- class_count: 25
  name: Activepieces Context
  property_count: 35
  slug: activepieces-context
layout: provider
modified: '2026-04-19'
name: Activepieces
rules:
- name: Activepieces API Rules
  rule_count: 25
  severity_counts:
    error: 10
    hint: 0
    info: 4
    warn: 11
  slug: activepieces-spectral-rules
skills: []
slug: activepieces
solutions:
- description: Free, open-source self-hosted deployment with unlimited flows and no task limits.
  name: Community Edition
- description: Cloud plan at $25/mo with 10 active flows, AI agents, and 500 AI credits.
  name: Plus
- description: Cloud plan at $150/mo with 50 active flows, team collaboration, and 1,000 AI credits.
  name: Business
- description: Custom pricing with unlimited flows, SSO, audit logs, and custom AI model support.
  name: Enterprise
source_filename: apis.yml
source_yaml: "aid: activepieces\nname: Activepieces\ndescription: >-\n  Activepieces is an open-source, no-code automation platform that enables users to streamline\n  workflows by connecting various applications and automating tasks. It supports over 400 MCP\n  servers and integrations, allowing developers to build custom TypeScript-based pieces. The\n  platform offers AI agents, MCPs, and workflow automation capabilities with both cloud and\n  self-hosted deployment options.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - No-Code\n  - Open Source\n  - Workflow\n  - AI Agents\n  - MCP\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: activepieces:activepieces-api\n    name: Activepieces API\n    tags:\n      - Automation\n      - Workflow\n      - No-Code\n    humanURL: https://www.activepieces.com/docs/endpoints/overview\n\
  \    baseURL: https://cloud.activepieces.com/api/v1\n    properties:\n      - url: https://www.activepieces.com/docs/endpoints/overview\n        type: Documentation\n      - url: https://www.activepieces.com/docs/endpoints/overview\n        type: APIReference\n      - url: openapi/activepieces.json\n        type: OpenAPI\n      - url: json-schema/activepieces-flow-schema.json\n        type: JSONSchema\n        title: Flow\n      - url: json-schema/activepieces-flow-run-schema.json\n        type: JSONSchema\n        title: Flow Run\n      - url: json-schema/activepieces-connection-schema.json\n        type: JSONSchema\n        title: Connection\n      - url: json-schema/activepieces-project-schema.json\n        type: JSONSchema\n        title: Project\n      - url: json-structure/activepieces-flow-structure.json\n        type: JSONStructure\n        title: Flow\n      - url: json-structure/activepieces-flow-run-structure.json\n        type: JSONStructure\n        title: Flow Run\n     \
  \ - url: examples/activepieces-flow-example.json\n        type: Example\n        title: Flow Example\n      - url: examples/activepieces-flow-run-example.json\n        type: Example\n        title: Flow Run Example\n    description: >-\n      The Activepieces API provides programmatic access to the automation platform, enabling\n      management of flows, connections, projects, users, folders, pieces, templates, and\n      execution monitoring. Uses Bearer token authentication.\ncommon:\n  - type: Portal\n    url: https://www.activepieces.com/\n  - type: Documentation\n    url: https://www.activepieces.com/docs/\n  - type: GettingStarted\n    url: https://www.activepieces.com/docs/getting-started/introduction\n  - type: Authentication\n    url: https://www.activepieces.com/docs/endpoints/overview\n  - type: Pricing\n    url: https://www.activepieces.com/pricing\n  - type: GitHubOrganization\n    url: https://github.com/activepieces\n  - type: GitHubRepository\n    url: https://github.com/activepieces/activepieces\n\
  \  - type: StatusPage\n    url: https://status.activepieces.com/\n  - type: SpectralRules\n    url: rules/activepieces-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/activepieces-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/activepieces.yaml\n    title: Activepieces API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/workflow-automation.yaml\n    title: Workflow Automation Capability\n  - type: JSON-LD\n    url: json-ld/activepieces-context.jsonld\n    title: Activepieces Context\n  - type: Features\n    data:\n      - name: Visual Flow Builder\n        description: No-code drag-and-drop interface for building automation workflows with triggers and actions.\n      - name: 400+ Integration Pieces\n        description: Over 400 pre-built integrations (pieces) written in TypeScript, available as MCP servers for AI agents.\n      - name: AI Agents\n        description: Native AI agent creation and orchestration within automation\
  \ workflows.\n      - name: MCP Servers\n        description: Every piece automatically becomes an MCP server for use with AI agents and LLMs like Claude.\n      - name: Custom Pieces\n        description: Build custom TypeScript-based integration pieces and publish them to npm.\n      - name: Flow Versioning\n        description: Version control for flows with publish/draft states and rollback capabilities.\n      - name: Human-in-the-Loop\n        description: Add approval steps, delays, and human decision points in automation workflows.\n      - name: Self-Hosting\n        description: Deploy on Docker, Kubernetes, AWS, GCP, or any cloud provider with full data control.\n      - name: Git Sync\n        description: Synchronize flows with Git repositories for version control and CI/CD integration.\n      - name: Webhook Triggers\n        description: Trigger flows via webhooks from any external system or service.\n      - name: REST API\n        description: Full programmatic access\
  \ to manage flows, connections, projects, and execution history.\n      - name: Flow Templates\n        description: Share and reuse flow templates across projects and teams.\n  - type: UseCases\n    data:\n      - name: Marketing Automation\n        description: Automate lead capture, email sequences, and CRM updates from marketing platforms.\n      - name: Sales Operations\n        description: Sync contacts, deals, and activities between CRM, email, and communication tools.\n      - name: Data Synchronization\n        description: Keep data in sync across databases, spreadsheets, and SaaS applications.\n      - name: AI Agent Orchestration\n        description: Use Activepieces as an MCP server to give AI agents access to 400+ integrations.\n      - name: IT Automation\n        description: Automate user provisioning, notifications, and system integrations.\n      - name: E-Commerce Operations\n        description: Automate order processing, inventory updates, and customer notifications.\n\
  \      - name: Developer Integration Platform\n        description: Embed Activepieces as a white-label automation platform in SaaS products.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: Trigger workflows on GitHub events and automate repository operations.\n      - name: Gmail\n        description: Send emails, parse inbound mail, and automate email workflows.\n      - name: Slack\n        description: Send notifications, create channels, and respond to Slack events.\n      - name: OpenAI\n        description: Integrate GPT models for AI-powered automation and content generation.\n      - name: Google Sheets\n        description: Read and write data to Google Sheets for data synchronization workflows.\n      - name: Airtable\n        description: Sync records and trigger workflows from Airtable database changes.\n      - name: Salesforce\n        description: Create and update Salesforce records from automation workflows.\n      - name: Stripe\n     \
  \   description: Trigger flows on payment events and automate billing operations.\n  - type: Solutions\n    data:\n      - name: Community Edition\n        description: Free, open-source self-hosted deployment with unlimited flows and no task limits.\n      - name: Plus\n        description: Cloud plan at $25/mo with 10 active flows, AI agents, and 500 AI credits.\n      - name: Business\n        description: Cloud plan at $150/mo with 50 active flows, team collaboration, and 1,000 AI credits.\n      - name: Enterprise\n        description: Custom pricing with unlimited flows, SSO, audit logs, and custom AI model support.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/apis.yml
tags:
- Automation
- No-Code
- Open Source
- Workflow
- AI Agents
- MCP
url: https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/apis.yml
use_cases:
- description: Automate lead capture, email sequences, and CRM updates from marketing platforms.
  name: Marketing Automation
- description: Sync contacts, deals, and activities between CRM, email, and communication tools.
  name: Sales Operations
- description: Keep data in sync across databases, spreadsheets, and SaaS applications.
  name: Data Synchronization
- description: Use Activepieces as an MCP server to give AI agents access to 400+ integrations.
  name: AI Agent Orchestration
- description: Automate user provisioning, notifications, and system integrations.
  name: IT Automation
- description: Automate order processing, inventory updates, and customer notifications.
  name: E-Commerce Operations
- description: Embed Activepieces as a white-label automation platform in SaaS products.
  name: Developer Integration Platform
---
