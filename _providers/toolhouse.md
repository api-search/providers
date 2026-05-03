---
api_count: 2
api_specs:
- filename: toolhouse-openapi-original.yml
  format: yaml
  label: Toolhouse Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/openapi/toolhouse-openapi-original.yml
apis:
- description: The Toolhouse Platform API provides management and orchestration capabilities for AI agents and tools. It includes endpoints for user profile management, billing, API key administration, tool discover
  name: Toolhouse Platform API
  slug: platform-api
- description: The Toolhouse Agents API enables execution of deployed AI agents via simple HTTP endpoints. Agents defined as code can be deployed and accessed through REST calls that support streaming responses, con
  name: Toolhouse Agents API
  slug: agents-api
capabilities:
- description: Workflow capability for managing the full AI agent lifecycle on Toolhouse — from agent creation and tool configuration to execution monitoring, Agent Studio sessions, and scheduled runs.
  name: Toolhouse Agent Management
  slug: agent-management
common:
- title: ''
  type: Website
  url: https://toolhouse.ai/
- title: ''
  type: Documentation
  url: https://docs.toolhouse.ai/toolhouse
- title: ''
  type: Blog
  url: https://toolhouse.ai/blog
- title: ''
  type: Pricing
  url: https://toolhouse.ai/pricing
- title: ''
  type: Login
  url: https://app.toolhouse.ai
- title: ''
  type: About
  url: https://toolhouse.ai/about
- title: ''
  type: GitHubOrganization
  url: https://github.com/toolhouseai
- title: ''
  type: PrivacyPolicy
  url: https://toolhouse.ai/privacy
- title: ''
  type: TermsOfService
  url: https://toolhouse.ai/tos
- title: ''
  type: Twitter
  url: https://x.com/toolhouseai
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/toolhouseai
- title: ''
  type: Discord
  url: https://discord.com/invite/xPvyBxhHtu
- title: ''
  type: YouTube
  url: https://youtube.com/@toolhouseai
- title: ''
  type: Support
  url: https://help.toolhouse.ai/
- title: ''
  type: Status
  url: https://toolhouse.betteruptime.com/
- title: ''
  type: SDK
  url: https://github.com/toolhouseai/toolhouse-sdk-python
- title: ''
  type: SDK
  url: https://github.com/toolhouseai/toolhouse-sdk-typescript
- title: ''
  type: Integration
  url: https://github.com/toolhouseai/toolhouse-mcp
- title: ''
  type: Integration
  url: https://github.com/toolhouseai/n8n-nodes-toolhouse
- title: ''
  type: JSON-LD
  url: json-ld/toolhouse-context.jsonld
- title: ''
  type: JSON-Schema
  url: json-schema/toolhouse-agent-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/toolhouse-agent-structure.json
- title: ''
  type: SpectralRules
  url: rules/toolhouse-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/agent-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/toolhouse-vocabulary.yml
created: '2026-03-26'
description: Toolhouse is a Backend-as-a-Service platform for building, deploying, and managing AI agents. Developers define agents as code and deploy them as APIs with a single command. Agents are automatically connected to over 40 pre-built tools including RAG, memory, code execution, browser automation, web scraping, and database connections. Toolhouse also provides an MCP server so any MCP-compatible client can access the full tool library. The platform includes Agent Studio for visual agent development, cron-based scheduling, and comprehensive observability through execution logs.
features:
- name: AI Agent Deployment
- name: Agent Studio
- name: Tool Library (40+ tools)
- name: MCP Server Integration
- name: RAG Memory
- name: Code Execution
- name: Browser Automation
- name: Web Scraping
- name: Scheduled Agent Runs
- name: Agent Observability
- name: API Key Management
- name: Agent Subscriptions
- name: Streaming Responses
- name: Bundle Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: OpenAI
- name: Anthropic Claude
- name: Vercel AI SDK
- name: LlamaIndex
- name: n8n
- name: MCP Clients
jsonld:
- class_count: 0
  name: Toolhouse Context
  property_count: 10
  slug: toolhouse-context
layout: provider
modified: '2026-05-03'
name: Toolhouse
rules:
- name: Toolhouse API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: toolhouse-rules
skills: []
slug: toolhouse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toolhouse\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml\napis:\n  - aid: toolhouse:platform-api\n    name: Toolhouse Platform API\n    tags:\n      - Agent Runs\n      - AI Agents\n      - API Keys\n      - Billing\n      - Bundles\n      - Management\n      - Schedules\n      - Tools\n    humanURL: https://docs.toolhouse.ai/toolhouse\n    properties:\n      - url: https://docs.toolhouse.ai/toolhouse\n        type: Documentation\n      - url: openapi/toolhouse-openapi-original.yml\n        type: OpenAPI\n      - url: rules/toolhouse-rules.yml\n        type: SpectralRules\n      - url: capabilities/shared/toolhouse-platform.yaml\n        type: NaftikoCapability\n    description: >-\n      The Toolhouse Platform API provides management and orchestration\n      capabilities for AI agents and tools. It includes endpoints for user\n      profile management, billing, API key administration, tool discovery\n      and execution,\
  \ agent run management with pagination, Agent Studio\n      chat sessions, agent file management, agent subscriptions, bundle\n      management, scheduled agent execution via cron expressions, and\n      MCP server configuration. Authentication uses HTTPBearer JWT tokens.\n  - aid: toolhouse:agents-api\n    name: Toolhouse Agents API\n    tags:\n      - AI Agents\n      - Conversations\n      - Execution\n      - Streaming\n    humanURL: https://docs.toolhouse.ai/toolhouse/advanced-concepts/publish-and-run-your-agents\n    properties:\n      - url: https://docs.toolhouse.ai/toolhouse/advanced-concepts/publish-and-run-your-agents\n        type: Documentation\n    description: >-\n      The Toolhouse Agents API enables execution of deployed AI agents via\n      simple HTTP endpoints. Agents defined as code can be deployed and\n      accessed through REST calls that support streaming responses,\n      conversation continuation via run IDs, and full conversation history\n      retrieval. Public\
  \ agents require no authentication while private\n      agents use Bearer token authorization.\nname: Toolhouse\ntags:\n  - Agent Infrastructure\n  - AI Agents\n  - Backend as a Service\n  - MCP\n  - Tools\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://toolhouse.ai/\n    name: Toolhouse Website\n    type: Website\n    description: 'null'\n  - url: https://docs.toolhouse.ai/toolhouse\n    name: Toolhouse Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://toolhouse.ai/blog\n    name: Toolhouse Blog\n    type: Blog\n    description: 'null'\n  - url: https://toolhouse.ai/pricing\n    name: Toolhouse Pricing\n    type: Pricing\n    description: 'null'\n  - url: https://app.toolhouse.ai\n    name: Toolhouse Login\n    type: Login\n    description: 'null'\n  - url: https://toolhouse.ai/about\n    name: Toolhouse About\n    type: About\n    description: 'null'\n  - url:\
  \ https://github.com/toolhouseai\n    name: Toolhouse GitHub\n    type: GitHubOrganization\n    description: 'null'\n  - url: https://toolhouse.ai/privacy\n    name: Toolhouse Privacy Policy\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://toolhouse.ai/tos\n    name: Toolhouse Terms of Service\n    type: TermsOfService\n    description: 'null'\n  - url: https://x.com/toolhouseai\n    name: Toolhouse Twitter\n    type: Twitter\n    description: 'null'\n  - url: https://www.linkedin.com/company/toolhouseai\n    name: Toolhouse LinkedIn\n    type: LinkedIn\n    description: 'null'\n  - url: https://discord.com/invite/xPvyBxhHtu\n    name: Toolhouse Discord\n    type: Discord\n    description: 'null'\n  - url: https://youtube.com/@toolhouseai\n    name: Toolhouse YouTube\n    type: YouTube\n    description: 'null'\n  - url: https://help.toolhouse.ai/\n    name: Toolhouse Support\n    type: Support\n    description: 'null'\n  - url: https://toolhouse.betteruptime.com/\n \
  \   name: Toolhouse Status\n    type: Status\n    description: 'null'\n  - url: https://github.com/toolhouseai/toolhouse-sdk-python\n    name: Toolhouse Python SDK\n    type: SDK\n    description: 'Official Python SDK for integrating Toolhouse into Python applications.'\n  - url: https://github.com/toolhouseai/toolhouse-sdk-typescript\n    name: Toolhouse TypeScript SDK\n    type: SDK\n    description: 'Official TypeScript/JavaScript SDK for Toolhouse integration.'\n  - url: https://github.com/toolhouseai/toolhouse-mcp\n    name: Toolhouse MCP Server\n    type: Integration\n    description: 'Connect Toolhouse tools to any MCP-compatible client or agent.'\n  - url: https://github.com/toolhouseai/n8n-nodes-toolhouse\n    name: Toolhouse n8n Integration\n    type: Integration\n    description: 'n8n workflow automation nodes for Toolhouse.'\n  - url: json-ld/toolhouse-context.jsonld\n    name: Toolhouse JSON-LD Context\n    type: JSON-LD\n    description: 'JSON-LD context defining Toolhouse\
  \ domain vocabulary and linked data mappings.'\n  - url: json-schema/toolhouse-agent-schema.json\n    name: Toolhouse Agent Schema\n    type: JSON-Schema\n    description: 'JSON Schema describing the Toolhouse agent entity model and related types.'\n  - url: json-structure/toolhouse-agent-structure.json\n    name: Toolhouse Agent Structure\n    type: JSONStructure\n    description: 'Structured documentation of the Toolhouse Agent object model.'\n  - url: rules/toolhouse-rules.yml\n    name: Toolhouse Spectral Rules\n    type: SpectralRules\n    description: 'Spectral ruleset enforcing Toolhouse API conventions and standards.'\n  - url: capabilities/agent-management.yaml\n    name: Toolhouse Agent Management Capability\n    type: NaftikoCapability\n    description: 'Naftiko workflow capability for full Toolhouse agent lifecycle management.'\n  - url: vocabulary/toolhouse-vocabulary.yml\n    name: Toolhouse Vocabulary\n    type: Vocabulary\n    description: 'Vocabulary and taxonomy for the\
  \ Toolhouse AI agent platform domain.'\n  - name: Features\n    type: Features\n    data:\n      - name: AI Agent Deployment\n      - name: Agent Studio\n      - name: Tool Library (40+ tools)\n      - name: MCP Server Integration\n      - name: RAG Memory\n      - name: Code Execution\n      - name: Browser Automation\n      - name: Web Scraping\n      - name: Scheduled Agent Runs\n      - name: Agent Observability\n      - name: API Key Management\n      - name: Agent Subscriptions\n      - name: Streaming Responses\n      - name: Bundle Management\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: AI Agent Backend-as-a-Service\n      - name: Automated Agent Scheduling\n      - name: Tool-Augmented LLM Pipelines\n      - name: Agent Studio Chat\n      - name: MCP Client Integration\n      - name: Production Agent Deployment\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: OpenAI\n      - name: Anthropic Claude\n      - name: Vercel AI SDK\n  \
  \    - name: LlamaIndex\n      - name: n8n\n      - name: MCP Clients\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nposition: Consumer\nsegments:\n  - AI Agents\n  - Tools\n  - Agent Infrastructure\ndescription: >-\n  Toolhouse is a Backend-as-a-Service platform for building, deploying, and managing\n  AI agents. Developers define agents as code and deploy them as APIs with a single\n  command. Agents are automatically connected to over 40 pre-built tools including\n  RAG, memory, code execution, browser automation, web scraping, and database connections.\n  Toolhouse also provides an MCP server so any MCP-compatible client can access the full\n  tool library. The platform includes Agent Studio for visual agent development, cron-based\n  scheduling, and comprehensive observability through execution logs.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml
tags:
- Agent Infrastructure
- AI Agents
- Backend as a Service
- MCP
- Tools
url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml
use_cases:
- name: AI Agent Backend-as-a-Service
- name: Automated Agent Scheduling
- name: Tool-Augmented LLM Pipelines
- name: Agent Studio Chat
- name: MCP Client Integration
- name: Production Agent Deployment
---
