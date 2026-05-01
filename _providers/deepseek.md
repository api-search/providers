---
api_count: 4
api_specs:
- filename: deepseek-chat-completion-api-openapi.yml
  format: yaml
  label: DeepSeek Chat Completion API
  slug: deepseek-chat-completion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-chat-completion-api-openapi.yml
- filename: deepseek-fim-completion-openapi.yml
  format: yaml
  label: DeepSeek Fill-In-The-Middle (FIM) Completion API
  slug: deepseek-fim-completion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-fim-completion-openapi.yml
- filename: deepseek-lists-models-api-openapi.yml
  format: yaml
  label: DeepSeek List Models API
  slug: deepseek-lists-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-lists-models-api-openapi.yml
- filename: deepseek-user-balance-api-openapi.yml
  format: yaml
  label: DeepSeek User Balance API
  slug: deepseek-user-balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-user-balance-api-openapi.yml
apis:
- description: Creates a model response for a given chat conversation. Supports the deepseek-chat and deepseek-reasoner models with options for tool calling, JSON output, streaming, temperature, top-p, frequency and
  name: DeepSeek Chat Completion API
  slug: deepseek-chat-completion-api
- description: Beta endpoint that performs fill-in-the-middle completions where a prompt and an optional suffix are provided and the model fills the gap. Useful for code completion and inline code generation tasks.
  name: DeepSeek Fill-In-The-Middle (FIM) Completion API
  slug: deepseek-fim-completion
- description: Lists the currently available DeepSeek models, providing basic information about each one such as the model identifier, owner, and availability.
  name: DeepSeek List Models API
  slug: deepseek-lists-models-api
- description: Returns the current account balance for the authenticated DeepSeek user, including available credit and currency. Useful for monitoring spend and gating workloads programmatically.
  name: DeepSeek User Balance API
  slug: deepseek-user-balance-api
capabilities: []
common:
- title: ''
  type: Documentation
  url: https://api-docs.deepseek.com/
- title: ''
  type: Pricing
  url: https://api-docs.deepseek.com/quick_start/pricing
- title: ''
  type: Authentication
  url: https://api-docs.deepseek.com/quick_start/token_usage
- title: ''
  type: RateLimits
  url: https://api-docs.deepseek.com/quick_start/rate_limit
- title: ''
  type: Errors
  url: https://api-docs.deepseek.com/quick_start/error_codes
- title: ''
  type: Status
  url: https://status.deepseek.com/
- title: ''
  type: FAQ
  url: https://api-docs.deepseek.com/faq
- title: ''
  type: ChangeLog
  url: https://api-docs.deepseek.com/updates
- title: ''
  type: Website
  url: https://www.deepseek.com/
- title: ''
  type: PrivacyPolicy
  url: https://chat.deepseek.com/downloads/DeepSeek%20Privacy%20Policy.html
- title: ''
  type: TermsOfService
  url: https://chat.deepseek.com/downloads/DeepSeek%20Terms%20of%20Use.html
- title: ''
  type: JSON-LD
  url: json-ld/deepseek-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/deepseek-vocabulary.yml
created: '2025-01-27'
description: DeepSeek is an artificial intelligence company that provides advanced large language models accessible through an API that is compatible with the OpenAI and Anthropic SDKs. The DeepSeek API offers chat completions, fill-in-the-middle completions, function calling, JSON output, streaming, multi-turn conversations, context caching, and a thinking/reasoning mode for complex problem solving.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Deepseek Context
  property_count: 9
  slug: deepseek-context
layout: provider
modified: '2026-04-28'
name: DeepSeek
rules:
- name: DeepSeek API Rules
  rule_count: 4
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 3
  slug: deepseek-chat-completion-api-rules
- name: DeepSeek API Rules
  rule_count: 3
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 2
  slug: deepseek-fim-completion-rules
- name: DeepSeek API Rules
  rule_count: 3
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 2
  slug: deepseek-lists-models-api-rules
- name: DeepSeek API Rules
  rule_count: 3
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 2
  slug: deepseek-user-balance-api-rules
skills: []
slug: deepseek
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: deepseek\nname: DeepSeek\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml\ndescription: >-\n  DeepSeek is an artificial intelligence company that provides advanced large\n  language models accessible through an API that is compatible with the OpenAI\n  and Anthropic SDKs. The DeepSeek API offers chat completions, fill-in-the-middle\n  completions, function calling, JSON output, streaming, multi-turn conversations,\n  context caching, and a thinking/reasoning mode for complex problem solving.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consuming\nspecificationVersion: '0.19'\nxType: company\ntags:\n  - AI\n  - Artificial Intelligence\n  - Chat\n  - Chat Completion\n  - LLM\n  - Large Language Models\n  - Reasoning\n  - Code Completion\ncreated: '2025-01-27'\nmodified: '2026-04-28'\napis:\n  - aid: deepseek:deepseek-chat-completion-api\n    name:\
  \ DeepSeek Chat Completion API\n    description: >-\n      Creates a model response for a given chat conversation. Supports the\n      deepseek-chat and deepseek-reasoner models with options for tool calling,\n      JSON output, streaming, temperature, top-p, frequency and presence\n      penalties, and stop sequences. Compatible with the OpenAI Chat\n      Completions request and response shapes.\n    humanURL: https://api-docs.deepseek.com/api/create-chat-completion\n    baseURL: https://api.deepseek.com\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Chat\n      - Chat Completion\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://api-docs.deepseek.com/api/create-chat-completion\n      - type: OpenAPI\n        url: openapi/deepseek-chat-completion-api-openapi.yml\n      - type: Rules\n        url: rules/deepseek-chat-completion-api-rules.yml\n      - type: Capabilities\n        url: capabilities/deepseek-chat-completion-api-capabilities.yml\n\
  \  - aid: deepseek:deepseek-fim-completion\n    name: DeepSeek Fill-In-The-Middle (FIM) Completion API\n    description: >-\n      Beta endpoint that performs fill-in-the-middle completions where a prompt\n      and an optional suffix are provided and the model fills the gap. Useful\n      for code completion and inline code generation tasks.\n    humanURL: https://api-docs.deepseek.com/guides/fim_completion\n    baseURL: https://api.deepseek.com/beta\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Code Completion\n      - Fill-In-The-Middle\n      - FIM\n    properties:\n      - type: Documentation\n        url: https://api-docs.deepseek.com/guides/fim_completion\n      - type: OpenAPI\n        url: openapi/deepseek-fim-completion-openapi.yml\n      - type: Rules\n        url: rules/deepseek-fim-completion-rules.yml\n      - type: Capabilities\n        url: capabilities/deepseek-fim-completion-capabilities.yml\n  - aid: deepseek:deepseek-lists-models-api\n    name: DeepSeek\
  \ List Models API\n    description: >-\n      Lists the currently available DeepSeek models, providing basic\n      information about each one such as the model identifier, owner, and\n      availability.\n    humanURL: https://api-docs.deepseek.com/api/list-models\n    baseURL: https://api.deepseek.com\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Models\n    properties:\n      - type: Documentation\n        url: https://api-docs.deepseek.com/api/list-models\n      - type: OpenAPI\n        url: openapi/deepseek-lists-models-api-openapi.yml\n      - type: Rules\n        url: rules/deepseek-lists-models-api-rules.yml\n      - type: Capabilities\n        url: capabilities/deepseek-lists-models-api-capabilities.yml\n  - aid: deepseek:deepseek-user-balance-api\n    name: DeepSeek User Balance API\n    description: >-\n      Returns the current account balance for the authenticated DeepSeek user,\n      including available credit and currency. Useful for monitoring spend\
  \ and\n      gating workloads programmatically.\n    humanURL: https://api-docs.deepseek.com/api/get-user-balance\n    baseURL: https://api.deepseek.com\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Balance\n      - Billing\n      - Pricing\n    properties:\n      - type: Documentation\n        url: https://api-docs.deepseek.com/api/get-user-balance\n      - type: OpenAPI\n        url: openapi/deepseek-user-balance-api-openapi.yml\n      - type: Rules\n        url: rules/deepseek-user-balance-api-rules.yml\n      - type: Capabilities\n        url: capabilities/deepseek-user-balance-api-capabilities.yml\ncommon:\n  - type: Documentation\n    url: https://api-docs.deepseek.com/\n  - type: Pricing\n    url: https://api-docs.deepseek.com/quick_start/pricing\n  - type: Authentication\n    url: https://api-docs.deepseek.com/quick_start/token_usage\n  - type: RateLimits\n    url: https://api-docs.deepseek.com/quick_start/rate_limit\n  - type: Errors\n    url: https://api-docs.deepseek.com/quick_start/error_codes\n\
  \  - type: Status\n    url: https://status.deepseek.com/\n  - type: FAQ\n    url: https://api-docs.deepseek.com/faq\n  - type: ChangeLog\n    url: https://api-docs.deepseek.com/updates\n  - type: Website\n    url: https://www.deepseek.com/\n  - type: PrivacyPolicy\n    url: https://chat.deepseek.com/downloads/DeepSeek%20Privacy%20Policy.html\n  - type: TermsOfService\n    url: https://chat.deepseek.com/downloads/DeepSeek%20Terms%20of%20Use.html\n  - type: JSON-LD\n    url: json-ld/deepseek-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/deepseek-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml
tags:
- AI
- Artificial Intelligence
- Chat
- Chat Completion
- LLM
- Large Language Models
- Reasoning
- Code Completion
url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml
use_cases: []
---
