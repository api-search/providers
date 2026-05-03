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
  type: JSON-LD
  url: json-ld/toolhouse-context.jsonld
- title: ''
  type: JSON-Schema
  url: json-schema/toolhouse-agent-schema.json
created: '2026-03-26'
description: Toolhouse is a Backend-as-a-Service platform for building, deploying, and managing AI agents. Developers define agents as code and deploy them as APIs with a single command. Agents are automatically connected to over 40 pre-built tools including RAG, memory, code execution, browser automation, web scraping, and database connections.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Toolhouse Context
  property_count: 10
  slug: toolhouse-context
layout: provider
modified: '2026-03-26'
name: Toolhouse
skills: []
slug: toolhouse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toolhouse\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml\napis:\n  - aid: toolhouse:platform-api\n    name: Toolhouse Platform API\n    tags:\n      - Agent Runs\n      - AI Agents\n      - Management\n      - Tools\n    humanURL: https://docs.toolhouse.ai/toolhouse\n    properties:\n      - url: https://docs.toolhouse.ai/toolhouse\n        type: Documentation\n      - url: openapi/toolhouse-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Toolhouse Platform API provides management and orchestration\n      capabilities for AI agents and tools. It includes endpoints for user\n      profile management, billing, API key administration, tool discovery\n      and execution, agent run management with pagination, Agent Studio\n      chat sessions, and scheduled agent execution via cron expressions.\n      Authentication uses HTTPBearer JWT tokens.\n  - aid: toolhouse:agents-api\n    name: Toolhouse Agents\
  \ API\n    tags:\n      - AI Agents\n      - Conversations\n      - Execution\n      - Streaming\n    humanURL: https://docs.toolhouse.ai/toolhouse/advanced-concepts/publish-and-run-your-agents\n    properties:\n      - url: https://docs.toolhouse.ai/toolhouse/advanced-concepts/publish-and-run-your-agents\n        type: Documentation\n    description: >-\n      The Toolhouse Agents API enables execution of deployed AI agents via\n      simple HTTP endpoints. Agents defined as code can be deployed and\n      accessed through REST calls that support streaming responses,\n      conversation continuation via run IDs, and full conversation history\n      retrieval. Public agents require no authentication while private\n      agents use Bearer token authorization.\nname: Toolhouse\ntags:\n  - Agent Infrastructure\n  - AI Agents\n  - Backend as a Service\n  - Tools\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url:\
  \ https://toolhouse.ai/\n    name: Toolhouse Website\n    type: Website\n    description: 'null'\n  - url: https://docs.toolhouse.ai/toolhouse\n    name: Toolhouse Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://toolhouse.ai/blog\n    name: Toolhouse Blog\n    type: Blog\n    description: 'null'\n  - url: https://toolhouse.ai/pricing\n    name: Toolhouse Pricing\n    type: Pricing\n    description: 'null'\n  - url: https://app.toolhouse.ai\n    name: Toolhouse Login\n    type: Login\n    description: 'null'\n  - url: https://toolhouse.ai/about\n    name: Toolhouse About\n    type: About\n    description: 'null'\n  - url: https://github.com/toolhouseai\n    name: Toolhouse GitHub\n    type: GitHubOrganization\n    description: 'null'\n  - url: https://toolhouse.ai/privacy\n    name: Toolhouse Privacy Policy\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://toolhouse.ai/tos\n    name: Toolhouse Terms of Service\n    type: TermsOfService\n\
  \    description: 'null'\n  - url: https://x.com/toolhouseai\n    name: Toolhouse Twitter\n    type: Twitter\n    description: 'null'\n  - url: https://www.linkedin.com/company/toolhouseai\n    name: Toolhouse LinkedIn\n    type: LinkedIn\n    description: 'null'\n  - url: https://discord.com/invite/xPvyBxhHtu\n    name: Toolhouse Discord\n    type: Discord\n    description: 'null'\n  - url: https://youtube.com/@toolhouseai\n    name: Toolhouse YouTube\n    type: YouTube\n    description: 'null'\n  - url: https://help.toolhouse.ai/\n    name: Toolhouse Support\n    type: Support\n    description: 'null'\n  - url: https://toolhouse.betteruptime.com/\n    name: Toolhouse Status\n    type: Status\n    description: 'null'\n  - url: json-ld/toolhouse-context.jsonld\n    name: Toolhouse JSON-LD Context\n    type: JSON-LD\n    description: 'JSON-LD context defining Toolhouse domain vocabulary and linked data mappings.'\n  - url: json-schema/toolhouse-agent-schema.json\n    name: Toolhouse Agent\
  \ Schema\n    type: JSON-Schema\n    description: 'JSON Schema describing the Toolhouse agent entity model and related types.'\ncreated: '2026-03-26'\nmodified: '2026-03-26'\nposition: Consumer\nsegments:\n  - AI Agents\n  - Tools\n  - Agent Infrastructure\ndescription: >-\n  Toolhouse is a Backend-as-a-Service platform for building, deploying, and managing\n  AI agents. Developers define agents as code and deploy them as APIs with a single\n  command. Agents are automatically connected to over 40 pre-built tools including\n  RAG, memory, code execution, browser automation, web scraping, and database connections.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml
tags:
- Agent Infrastructure
- AI Agents
- Backend as a Service
- Tools
url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/apis.yml
use_cases: []
---
