---
api_count: 6
api_specs:
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Tool Router API
  slug: tool-router-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Tools API
  slug: tools-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Connected Accounts API
  slug: connected-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Auth Configs API
  slug: auth-configs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Triggers API
  slug: triggers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Toolkits API
  slug: toolkits-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
apis:
- description: Session-based API for AI agents to discover and execute tools. The Tool Router provides the primary interface for AI agents to find relevant tools and execute actions through Composio's unified platfo
  name: Composio Tool Router API
  slug: tool-router-api
- description: Enables listing, searching, and executing individual actions within toolkits. The Tools API allows developers to discover available tools, filter by toolkit or capability, and execute specific actions
  name: Composio Tools API
  slug: tools-api
- description: Handles management of user OAuth connections to applications. The Connected Accounts API enables creating, listing, and managing authenticated connections between end users and third-party application
  name: Composio Connected Accounts API
  slug: connected-accounts-api
- description: Allows configuration of authentication methods for toolkit access. Auth configs contain developer credentials and app-level settings such as scopes and authentication methods, and can be reused across
  name: Composio Auth Configs API
  slug: auth-configs-api
- description: Manages webhook subscriptions from connected applications. The Triggers API enables developers to set up and manage event-driven notifications from third-party applications, allowing AI agents to resp
  name: Composio Triggers API
  slug: triggers-api
- description: Provides browsing capabilities for available applications and their associated tools. The Toolkits API allows developers to discover and explore the 1000+ available integrations across services like G
  name: Composio Toolkits API
  slug: toolkits-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://app.composio.dev/dashboard
- title: ''
  type: Documentation
  url: https://docs.composio.dev/docs
- title: ''
  type: Getting Started
  url: https://docs.composio.dev/docs/quickstart
- title: ''
  type: API Reference
  url: https://docs.composio.dev/reference
- title: ''
  type: OpenAPI
  url: https://backend.composio.dev/api/v3/openapi.json
- title: ''
  type: Authentication
  url: https://docs.composio.dev/faq/api_key/api_key
- title: ''
  type: Blog
  url: https://composio.dev/blog
- title: ''
  type: Status
  url: https://status.composio.dev
- title: ''
  type: Pricing
  url: https://composio.dev/pricing
- title: ''
  type: Change Log
  url: https://docs.composio.dev/docs/changelog
- title: ''
  type: Privacy Policy
  url: https://composio.dev/privacy
- title: ''
  type: Terms of Service
  url: https://composio.dev/terms
- title: ''
  type: GitHub Organization
  url: https://github.com/ComposioHQ
- title: ''
  type: GitHub Repo
  url: https://github.com/ComposioHQ/composio
- title: ''
  type: Python SDK
  url: https://github.com/ComposioHQ/composio
- title: ''
  type: Node.js SDK
  url: https://www.npmjs.com/package/@composio/client
- title: ''
  type: Sign Up
  url: https://app.composio.dev/dashboard
- title: ''
  type: JSON-LD
  url: json-ld/composio-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/composio-tool-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/composio-toolkit-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/composio-connected-account-schema.json
created: '2026-03-03'
description: Composio is a unified API and tooling platform for AI agents with 1000+ pre-built connectors, managed OAuth, tool search, context management, and a sandboxed workbench to help you build AI agents that turn intent into action.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Composio Context
  property_count: 7
  slug: composio-context
layout: provider
modified: '2026-04-28'
name: Composio
rules:
- name: Composio API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: composio-rules
skills: []
slug: composio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: composio\nname: Composio\ndescription: >-\n  Composio is a unified API and tooling platform for AI agents with 1000+ pre-built connectors, managed OAuth, tool search, context management, and a sandboxed workbench to help you build AI agents that turn intent into action.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Agents\n  - Authentication\n  - Integrations\n  - OAuth\n  - Tools\n  - Unified_API\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\nx-type: company\napis:\n  - aid: composio:tool-router-api\n    name: Composio Tool Router API\n    description: >-\n      Session-based API for AI agents to discover and execute tools. The Tool Router provides the primary interface for AI agents to find relevant tools and execute actions through Composio's unified\
  \ platform.\n    humanURL: https://docs.composio.dev/reference\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n      - AI Agents\n      - Sessions\n      - Tools\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference\n      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n      - title: Session Lifecycle\n        description: Create sessions that scope an AI agent's tool discovery and execution.\n      - title: Connected Account Binding\n        description: Sessions are scoped to a single connected account for authenticated calls.\n    useCases:\n      - title: Agent Runtime\n        description: Power AI agents that discover and execute tools at runtime within\
  \ an isolated session.\n  - aid: composio:tools-api\n    name: Composio Tools API\n    description: >-\n      Enables listing, searching, and executing individual actions within toolkits. The Tools API allows developers to discover available tools, filter by toolkit or capability, and execute specific actions on behalf of connected users.\n    humanURL: https://docs.composio.dev/reference/api-reference/tools\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n      - Actions\n      - Execution\n      - Tools\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference/api-reference/tools\n      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n      - title: Tool Discovery\n\
  \        description: List and search tools across toolkits with filtering on toolkit and capability.\n      - title: Action Execution\n        description: Execute a specific tool with structured arguments on behalf of a connected user.\n    useCases:\n      - title: Tool Calling\n        description: Surface a curated set of tools to an LLM for tool calling use cases.\n      - title: Agent Action Execution\n        description: Execute the tool selected by an agent to take real-world action.\n  - aid: composio:connected-accounts-api\n    name: Composio Connected Accounts API\n    description: >-\n      Handles management of user OAuth connections to applications. The Connected Accounts API enables creating, listing, and managing authenticated connections between end users and third-party applications through Composio's managed OAuth flow.\n    humanURL: https://docs.composio.dev/reference/api-reference/connected-accounts\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n\
  \      - Accounts\n      - Authentication\n      - Connections\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference/api-reference/connected-accounts\n      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n      - title: Managed OAuth\n        description: Initiate and manage OAuth flows that connect users to third-party apps.\n      - title: Account Lifecycle\n        description: List, retrieve, and disconnect connected accounts.\n    useCases:\n      - title: User Onboarding\n        description: Walk a user through connecting their third-party accounts to an AI agent.\n      - title: Account Management UI\n        description: Power \"connections\" management\
  \ screens in agent applications.\n  - aid: composio:auth-configs-api\n    name: Composio Auth Configs API\n    description: >-\n      Allows configuration of authentication methods for toolkit access. Auth configs contain developer credentials and app-level settings such as scopes and authentication methods, and can be reused across all users.\n    humanURL: https://docs.composio.dev/reference/api-reference/auth-configs\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n      - Authentication\n      - Configuration\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference/api-reference/auth-configs\n      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n\
  \      - title: Reusable Auth Profiles\n        description: Centralize OAuth client IDs, secrets, and scopes for reuse across users.\n      - title: Per-Toolkit Configuration\n        description: Define auth methods (OAuth2, API key, basic) per toolkit.\n    useCases:\n      - title: White-Label OAuth\n        description: Expose your own branded OAuth experience to end users for each integrated toolkit.\n  - aid: composio:triggers-api\n    name: Composio Triggers API\n    description: >-\n      Manages webhook subscriptions from connected applications. The Triggers API enables developers to set up and manage event-driven notifications from third-party applications, allowing AI agents to respond to real-time events.\n    humanURL: https://docs.composio.dev/reference/api-reference/triggers\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n      - Events\n      - Triggers\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference/api-reference/triggers\n\
  \      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n      - title: Webhook Subscriptions\n        description: Subscribe to event-driven notifications from connected applications.\n      - title: Trigger Inventory\n        description: List active trigger subscriptions per user, project, or toolkit.\n    useCases:\n      - title: Event-Driven Agents\n        description: Wake AI agents in response to real-world events from connected applications.\n  - aid: composio:toolkits-api\n    name: Composio Toolkits API\n    description: >-\n      Provides browsing capabilities for available applications and their associated tools. The Toolkits API allows developers to discover and explore the 1000+ available integrations\
  \ across services like GitHub, Gmail, Slack, Notion, and more.\n    humanURL: https://docs.composio.dev/reference/api-reference/toolkits\n    baseURL: https://backend.composio.dev/api/v3\n    tags:\n      - Applications\n      - Integrations\n      - Toolkits\n    properties:\n      - type: Documentation\n        url: https://docs.composio.dev/reference/api-reference/toolkits\n      - type: OpenAPI\n        url: openapi/composio-openapi-original.yml\n      - type: OpenAPI\n        url: https://backend.composio.dev/api/v3/openapi.json\n      - type: Spectral Rules\n        url: rules/composio-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/composio-tool-router.yml\n    features:\n      - title: Toolkit Catalog\n        description: Browse over 1000 toolkits across categories such as productivity, dev tools, and CRM.\n      - title: Toolkit Detail\n        description: Retrieve a single toolkit with its associated tools and metadata.\n    useCases:\n      - title:\
  \ Integration Selection\n        description: Allow agent builders to pick the right integrations for their use case.\n      - title: App Marketplace UI\n        description: Power an in-product app marketplace inside agentic applications.\ncommon:\n  - type: Portal\n    url: https://app.composio.dev/dashboard\n  - type: Documentation\n    url: https://docs.composio.dev/docs\n  - type: Getting Started\n    url: https://docs.composio.dev/docs/quickstart\n  - type: API Reference\n    url: https://docs.composio.dev/reference\n  - type: OpenAPI\n    url: https://backend.composio.dev/api/v3/openapi.json\n  - type: Authentication\n    url: https://docs.composio.dev/faq/api_key/api_key\n  - type: Blog\n    url: https://composio.dev/blog\n  - type: Status\n    url: https://status.composio.dev\n  - type: Pricing\n    url: https://composio.dev/pricing\n  - type: Change Log\n    url: https://docs.composio.dev/docs/changelog\n  - type: Privacy Policy\n    url: https://composio.dev/privacy\n  - type:\
  \ Terms of Service\n    url: https://composio.dev/terms\n  - type: GitHub Organization\n    url: https://github.com/ComposioHQ\n  - type: GitHub Repo\n    url: https://github.com/ComposioHQ/composio\n  - type: Python SDK\n    url: https://github.com/ComposioHQ/composio\n  - type: Node.js SDK\n    url: https://www.npmjs.com/package/@composio/client\n  - type: Sign Up\n    url: https://app.composio.dev/dashboard\n  - type: JSON-LD\n    url: json-ld/composio-context.jsonld\n  - type: JSONSchema\n    url: json-schema/composio-tool-schema.json\n  - type: JSONSchema\n    url: json-schema/composio-toolkit-schema.json\n  - type: JSONSchema\n    url: json-schema/composio-connected-account-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml
tags:
- AI Agents
- Authentication
- Integrations
- OAuth
- Tools
- Unified_API
url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml
use_cases: []
---
