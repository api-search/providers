---
api_count: 5
api_specs:
- filename: openapi.json
  format: json
  label: OpenRouter
  slug: openrouter
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Chat Completions API
  slug: chat-completions-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Models API
  slug: models-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Generation API
  slug: generation-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Keys Management API
  slug: keys-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
apis:
- description: OpenRouter provides unified access to hundreds of AI models through a single API endpoint. It implements the OpenAI API specification for chat completions, allowing developers to use any model with th
  name: OpenRouter
  slug: openrouter
- description: The Chat Completions API is the primary endpoint for generating model responses. It supports text and image inputs, streaming via Server-Sent Events, tool and function calling, structured outputs, and
  name: OpenRouter Chat Completions API
  slug: chat-completions-api
- description: 'The Models API allows developers to list and discover all available AI models and their properties, including pricing, context lengths, supported features, and provider information. Endpoints include '
  name: OpenRouter Models API
  slug: models-api
- description: The Generation API allows querying for generation statistics and historical usage data, including token counts, cost calculations, cached token tracking, and reasoning token counts for completed reque
  name: OpenRouter Generation API
  slug: generation-api
- description: The Keys Management API enables programmatic creation, rotation, and management of OpenRouter API keys. Common use cases include SaaS applications that automatically create unique keys for each custom
  name: OpenRouter Keys Management API
  slug: keys-api
common:
- title: ''
  type: Website
  url: https://openrouter.ai/
- title: ''
  type: Models
  url: https://openrouter.ai/models
- title: ''
  type: Status
  url: https://status.openrouter.ai/
- title: ''
  type: GettingStarted
  url: https://openrouter.ai/docs/quickstart
- title: ''
  type: FAQ
  url: https://openrouter.ai/docs/faq
- title: ''
  type: Pricing
  url: https://openrouter.ai/models?fmt=table
- title: ''
  type: PrivacyPolicy
  url: https://openrouter.ai/privacy
- title: ''
  type: TermsOfService
  url: https://openrouter.ai/terms
- title: ''
  type: Portal
  url: https://openrouter.ai/docs
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/api/reference/overview
- title: ''
  type: Authentication
  url: https://openrouter.ai/docs/api/reference/authentication
- title: ''
  type: RateLimits
  url: https://openrouter.ai/docs/api/reference/limits
- title: ''
  type: Errors
  url: https://openrouter.ai/docs/api/reference/errors-and-debugging
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/api/reference/streaming
- title: ''
  type: OpenAPI
  url: https://openrouter.ai/openapi.json
- title: ''
  type: OpenAPI
  url: https://openrouter.ai/openapi.yaml
- title: ''
  type: Pricing
  url: https://openrouter.ai/pricing
- title: ''
  type: Support
  url: https://openrouter.ai/support
- title: ''
  type: Blog
  url: https://openrouter.ai/announcements
- title: ''
  type: Discord
  url: https://discord.com/invite/openrouter
- title: ''
  type: GitHubOrganization
  url: https://github.com/OpenRouterTeam
- title: ''
  type: GitHubRepository
  url: https://github.com/OpenRouterTeam/typescript-sdk
- title: ''
  type: GitHubRepository
  url: https://github.com/OpenRouterTeam/python-sdk
- title: ''
  type: SDKs
  url: https://openrouter.ai/docs/sdks/typescript/overview
- title: ''
  type: SDKs
  url: https://openrouter.ai/docs/sdks/python/overview
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/community/openai-sdk
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/routing/provider-selection
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/tool-calling
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/structured-outputs
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/model-routing
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/guardrails
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/zdr
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/features/plugins/web-search
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/overview/auth/byok
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/guides/for-providers
- title: ''
  type: APIKeys
  url: https://openrouter.ai/settings/keys
- title: ''
  type: Documentation
  url: https://openrouter.ai/docs/guides/overview/principles
created: '2025-08-19T00:00:00.000Z'
description: OpenRouter is an API platform that provides unified access to multiple AI language models through a single interface. OpenRouter acts as a "router" or gateway that lets developers and applications access dozens of different AI models from various providers through one standardized API, rather than having to integrate with each provider separately.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Openrouter Context
  property_count: 1
  slug: openrouter-context
layout: provider
modified: '2026-04-28'
name: OpenRouter
skills: []
slug: openrouter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openrouter\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml\napis:\n  - aid: openrouter:openrouter\n    name: OpenRouter\n    tags:\n      - Artificial Intelligence\n      - Gateway\n      - Large Language Models\n      - Router\n    humanURL: https://openrouter.ai/\n    baseURL: https://openrouter.ai/api/v1\n    properties:\n      - url: https://openrouter.ai/\n        type: Documentation\n      - url: https://openrouter.ai/docs/api/reference/overview\n        type: Documentation\n      - url: https://openrouter.ai/openapi.json\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/openapi/openrouter-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-schema/openrouter-chat-message-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-ld/openrouter-context.jsonld\n\
  \        type: JSONLDContext\n    description: >-\n      OpenRouter provides unified access to hundreds of AI models through a\n      single API endpoint. It implements the OpenAI API specification for\n      chat completions, allowing developers to use any model with the same\n      request and response format. Better prices, better uptime, no\n      subscription.\n  - aid: openrouter:chat-completions-api\n    name: OpenRouter Chat Completions API\n    tags:\n      - Chat\n      - Completions\n      - Large Language Models\n    humanURL: https://openrouter.ai/docs/api/reference/overview\n    baseURL: https://openrouter.ai/api/v1\n    properties:\n      - url: https://openrouter.ai/docs/api/reference/overview\n        type: Documentation\n      - url: https://openrouter.ai/docs/api/reference/parameters\n        type: Documentation\n      - url: https://openrouter.ai/docs/api/reference/streaming\n        type: Documentation\n      - url: https://openrouter.ai/openapi.json\n        type:\
  \ OpenAPI\n    description: >-\n      The Chat Completions API is the primary endpoint for generating model\n      responses. It supports text and image inputs, streaming via\n      Server-Sent Events, tool and function calling, structured outputs,\n      and provider routing across 400+ AI models from 60+ providers through\n      a single standardized interface at /api/v1/chat/completions.\n  - aid: openrouter:models-api\n    name: OpenRouter Models API\n    tags:\n      - Discovery\n      - Models\n    humanURL: https://openrouter.ai/docs/api/api-reference/models/get-models\n    baseURL: https://openrouter.ai/api/v1\n    properties:\n      - url: https://openrouter.ai/docs/api/api-reference/models/get-models\n        type: Documentation\n      - url: https://openrouter.ai/docs/guides/overview/models\n        type: Documentation\n      - url: https://openrouter.ai/openapi.json\n        type: OpenAPI\n    description: >-\n      The Models API allows developers to list and discover all\
  \ available AI\n      models and their properties, including pricing, context lengths,\n      supported features, and provider information. Endpoints include\n      listing all models and listing all endpoints for a specific model.\n  - aid: openrouter:generation-api\n    name: OpenRouter Generation API\n    tags:\n      - Generation\n      - Stats\n      - Usage\n    humanURL: https://openrouter.ai/docs/api/reference/overview\n    baseURL: https://openrouter.ai/api/v1\n    properties:\n      - url: https://openrouter.ai/docs/api/reference/overview\n        type: Documentation\n      - url: https://openrouter.ai/openapi.json\n        type: OpenAPI\n    description: >-\n      The Generation API allows querying for generation statistics and\n      historical usage data, including token counts, cost calculations,\n      cached token tracking, and reasoning token counts for completed\n      requests via the /api/v1/generation endpoint.\n  - aid: openrouter:keys-api\n    name: OpenRouter Keys\
  \ Management API\n    tags:\n      - API Keys\n      - Management\n      - Provisioning\n    humanURL: https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys\n    baseURL: https://openrouter.ai/api/v1\n    properties:\n      - url: https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys\n        type: Documentation\n      - url: https://openrouter.ai/docs/guides/overview/auth/management-api-keys\n        type: Documentation\n      - url: https://openrouter.ai/openapi.json\n        type: OpenAPI\n    description: >-\n      The Keys Management API enables programmatic creation, rotation, and\n      management of OpenRouter API keys. Common use cases include SaaS\n      applications that automatically create unique keys for each customer,\n      key rotation for security compliance, and usage monitoring with\n      automatic key disabling when limits are exceeded.\nname: OpenRouter\ntags:\n  - Artificial Intelligence\n  - Gateway\n  - Large Language Models\n \
  \ - Router\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://openrouter.ai/\n    name: OpenRouter\n    type: Website\n    description: 'null'\n  - url: https://openrouter.ai/models\n    name: Models\n    type: Models\n    description: 'null'\n  - url: https://status.openrouter.ai/\n    name: OpenRouter Status\n    type: Status\n    description: 'null'\n  - url: https://openrouter.ai/docs/quickstart\n    name: Getting Started\n    type: GettingStarted\n    description: 'null'\n  - url: https://openrouter.ai/docs/faq\n    name: OpenRouter FAQ\n    type: FAQ\n    description: 'null'\n  - url: https://openrouter.ai/models?fmt=table\n    name: Pricing\n    type: Pricing\n    description: 'null'\n  - url: https://openrouter.ai/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://openrouter.ai/terms\n    name: Terms Of Service\n    type: TermsOfService\n\
  \    description: 'null'\n  - url: https://openrouter.ai/docs\n    name: Documentation Portal\n    type: Portal\n    description: 'null'\n  - url: https://openrouter.ai/docs/api/reference/overview\n    name: API Reference\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/api/reference/authentication\n    name: Authentication\n    type: Authentication\n    description: 'null'\n  - url: https://openrouter.ai/docs/api/reference/limits\n    name: Rate Limits\n    type: RateLimits\n    description: 'null'\n  - url: https://openrouter.ai/docs/api/reference/errors-and-debugging\n    name: Errors and Debugging\n    type: Errors\n    description: 'null'\n  - url: https://openrouter.ai/docs/api/reference/streaming\n    name: Streaming\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/openapi.json\n    name: OpenAPI Specification (JSON)\n    type: OpenAPI\n    description: 'null'\n  - url: https://openrouter.ai/openapi.yaml\n  \
  \  name: OpenAPI Specification (YAML)\n    type: OpenAPI\n    description: 'null'\n  - url: https://openrouter.ai/pricing\n    name: Platform Pricing\n    type: Pricing\n    description: 'null'\n  - url: https://openrouter.ai/support\n    name: Support\n    type: Support\n    description: 'null'\n  - url: https://openrouter.ai/announcements\n    name: Announcements and Blog\n    type: Blog\n    description: 'null'\n  - url: https://discord.com/invite/openrouter\n    name: Discord Community\n    type: Discord\n    description: 'null'\n  - url: https://github.com/OpenRouterTeam\n    name: GitHub Organization\n    type: GitHubOrganization\n    description: 'null'\n  - url: https://github.com/OpenRouterTeam/typescript-sdk\n    name: TypeScript SDK\n    type: GitHubRepository\n    description: 'null'\n  - url: https://github.com/OpenRouterTeam/python-sdk\n    name: Python SDK\n    type: GitHubRepository\n    description: 'null'\n  - url: https://openrouter.ai/docs/sdks/typescript/overview\n\
  \    name: TypeScript SDK Documentation\n    type: SDKs\n    description: 'null'\n  - url: https://openrouter.ai/docs/sdks/python/overview\n    name: Python SDK Documentation\n    type: SDKs\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/community/frameworks-and-integrations-overview\n    name: Frameworks and Integrations\n    type: Integrations\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/community/openai-sdk\n    name: OpenAI SDK Integration\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/routing/provider-selection\n    name: Provider Routing\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/features/tool-calling\n    name: Tool and Function Calling\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/features/structured-outputs\n    name: Structured Outputs\n    type: Documentation\n    description: 'null'\n\
  \  - url: https://openrouter.ai/docs/guides/features/model-routing\n    name: Model Routing\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/features/guardrails\n    name: Guardrails\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/features/zdr\n    name: Zero Data Retention\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/features/plugins/web-search\n    name: Web Search Plugin\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/overview/auth/byok\n    name: Bring Your Own Key (BYOK)\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/guides/for-providers\n    name: Provider Integration Guide\n    type: Documentation\n    description: 'null'\n  - url: https://openrouter.ai/settings/keys\n    name: API Keys\n    type: APIKeys\n    description: 'null'\n  - url: https://openrouter.ai/docs/guides/overview/principles\n\
  \    name: Principles\n    type: Documentation\n    description: 'null'\ncreated: '2025-08-19T00:00:00.000Z'\nmodified: '2026-04-28'\nposition: Consuming\nsegments:\n  - Gateways\ndescription: >-\n  OpenRouter is an API platform that provides unified access to multiple AI\n  language models through a single interface. OpenRouter acts as a \"router\" or\n  gateway that lets developers and applications access dozens of different AI\n  models from various providers through one standardized API, rather than having\n  to integrate with each provider separately.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Gateway
- Large Language Models
- Router
url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml
use_cases: []
---
