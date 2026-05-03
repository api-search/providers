---
api_count: 4
api_specs:
- filename: osmapi-chat-completions-openapi.yml
  format: yaml
  label: osmAPI Chat Completions API
  slug: osmapi-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-chat-completions-openapi.yml
- filename: osmapi-anthropic-messages-openapi.yml
  format: yaml
  label: osmAPI Anthropic Messages API
  slug: osmapi-anthropic-messages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-anthropic-messages-openapi.yml
- filename: osmapi-models-openapi.yml
  format: yaml
  label: osmAPI Models API
  slug: osmapi-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-models-openapi.yml
- filename: osmapi-health-openapi.yml
  format: yaml
  label: osmAPI Health API
  slug: osmapi-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-health-openapi.yml
apis:
- description: OpenAI-compatible chat completions endpoint with smart routing, streaming, function calling, web search, and response healing across multiple LLM providers.
  name: osmAPI Chat Completions API
  slug: osmapi-chat-completions-api
- description: Anthropic-compatible messages endpoint supporting system prompts, extended thinking, tool use, and streaming through osmAPI's gateway.
  name: osmAPI Anthropic Messages API
  slug: osmapi-anthropic-messages-api
- description: Endpoint for listing available AI models with pricing, context length, capabilities, and provider details.
  name: osmAPI Models API
  slug: osmapi-models-api
- description: Health check endpoint reporting service status and dependency connectivity.
  name: osmAPI Health API
  slug: osmapi-health-api
common:
- title: ''
  type: Portal
  url: https://www.osmapi.com/
- title: ''
  type: Documentation
  url: https://docs.osmapi.com/
- title: ''
  type: Dashboard
  url: https://app.osmapi.com/
- title: ''
  type: Authentication
  url: https://docs.osmapi.com/features/api-keys
- title: ''
  type: RateLimits
  url: https://docs.osmapi.com/resources/rate-limits
- title: ''
  type: Routing
  url: https://docs.osmapi.com/features/routing
- title: ''
  type: Caching
  url: https://docs.osmapi.com/features/caching
- title: ''
  type: Pricing
  url: https://docs.osmapi.com/features/cost-breakdown
- title: ''
  type: JSONLDContext
  url: json-ld/osmapi-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/osmapi-chat-completion-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/osmapi-model-schema.json
created: '2026-03-21'
description: osmAPI is a unified AI gateway that routes requests to OpenAI, Anthropic, Google, and 14+ LLM providers through a single API. Drop-in compatible with the OpenAI SDK, it provides smart routing, streaming, function calling, web search, response healing, embeddings, audio, and realtime endpoints.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Osmapi Context
  property_count: 6
  slug: osmapi-context
layout: provider
modified: '2026-04-28'
name: osmAPI
skills: []
slug: osmapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: osmapi\nname: osmAPI\ndescription: >-\n  osmAPI is a unified AI gateway that routes requests to OpenAI, Anthropic,\n  Google, and 14+ LLM providers through a single API. Drop-in compatible with\n  the OpenAI SDK, it provides smart routing, streaming, function calling, web\n  search, response healing, embeddings, audio, and realtime endpoints.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Anthropic\n  - Gateway\n  - LLM\n  - OpenAI\n  - Routing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: osmapi:osmapi-chat-completions-api\n    name: osmAPI Chat Completions API\n    description: >-\n      OpenAI-compatible chat completions endpoint with smart routing, streaming,\n      function calling, web search, and response healing across multiple LLM\n      providers.\n    humanURL:\
  \ https://docs.osmapi.com/v1_chat_completions\n    baseURL: https://api.osmapi.com/v1\n    tags:\n      - AI\n      - Chat\n      - LLM\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.osmapi.com/v1_chat_completions\n      - type: OpenAPI\n        url: openapi/osmapi-chat-completions-openapi.yml\n  - aid: osmapi:osmapi-anthropic-messages-api\n    name: osmAPI Anthropic Messages API\n    description: >-\n      Anthropic-compatible messages endpoint supporting system prompts, extended\n      thinking, tool use, and streaming through osmAPI's gateway.\n    humanURL: https://docs.osmapi.com/v1_messages\n    baseURL: https://api.osmapi.com/v1\n    tags:\n      - AI\n      - Anthropic\n      - Messages\n      - Tool Use\n    properties:\n      - type: Documentation\n        url: https://docs.osmapi.com/v1_messages\n      - type: OpenAPI\n        url: openapi/osmapi-anthropic-messages-openapi.yml\n  - aid: osmapi:osmapi-models-api\n    name: osmAPI Models\
  \ API\n    description: >-\n      Endpoint for listing available AI models with pricing, context length,\n      capabilities, and provider details.\n    humanURL: https://docs.osmapi.com/v1_models\n    baseURL: https://api.osmapi.com/v1\n    tags:\n      - AI\n      - Models\n    properties:\n      - type: Documentation\n        url: https://docs.osmapi.com/v1_models\n      - type: OpenAPI\n        url: openapi/osmapi-models-openapi.yml\n  - aid: osmapi:osmapi-health-api\n    name: osmAPI Health API\n    description: >-\n      Health check endpoint reporting service status and dependency\n      connectivity.\n    humanURL: https://docs.osmapi.com/health\n    baseURL: https://api.osmapi.com\n    tags:\n      - Health\n      - Status\n    properties:\n      - type: Documentation\n        url: https://docs.osmapi.com/health\n      - type: OpenAPI\n        url: openapi/osmapi-health-openapi.yml\ncommon:\n  - type: Portal\n    url: https://www.osmapi.com/\n  - type: Documentation\n    url:\
  \ https://docs.osmapi.com/\n  - type: Dashboard\n    url: https://app.osmapi.com/\n  - type: Authentication\n    url: https://docs.osmapi.com/features/api-keys\n  - type: RateLimits\n    url: https://docs.osmapi.com/resources/rate-limits\n  - type: Routing\n    url: https://docs.osmapi.com/features/routing\n  - type: Caching\n    url: https://docs.osmapi.com/features/caching\n  - type: Pricing\n    url: https://docs.osmapi.com/features/cost-breakdown\n  - type: JSONLDContext\n    url: json-ld/osmapi-context.jsonld\n  - type: JSONSchema\n    url: json-schema/osmapi-chat-completion-schema.json\n  - type: JSONSchema\n    url: json-schema/osmapi-model-schema.json\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml
tags:
- AI
- Anthropic
- Gateway
- LLM
- OpenAI
- Routing
url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml
use_cases: []
---
