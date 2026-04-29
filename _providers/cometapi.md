---
api_count: 1
api_specs:
- filename: cometapi-unified-api-openapi.yml
  format: yaml
  label: CometAPI Unified API
  slug: cometapi-unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/openapi/cometapi-unified-api-openapi.yml
apis:
- description: 'OpenAI-compatible REST API exposing chat completions, embeddings, image generation, video generation, speech synthesis, and audio transcription across hundreds of upstream models. Authentication uses '
  name: CometAPI Unified API
  slug: cometapi-unified-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cometapi.com/
- title: ''
  type: Documentation
  url: https://apidoc.cometapi.com/
- title: ''
  type: HelpCenter
  url: https://apidoc.cometapi.com/help-center
- title: ''
  type: GettingStarted
  url: https://apidoc.cometapi.com/how-to-use-cometapi-1792005m0
- title: ''
  type: JSON-LD
  url: json-ld/cometapi-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cometapi-chat-completion-schema.json
- title: ''
  type: Spectral
  url: rules/cometapi-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cometapi-multi-model-capabilities.yml
created: '2026-03-16'
description: CometAPI is an AI API aggregator that consolidates access to 500+ models from multiple providers (OpenAI, Anthropic, Google, xAI, DeepSeek, Alibaba, and more) behind a single OpenAI-compatible REST surface. It supports chat completions, embeddings, image generation, text-to-video and image-to-video, speech synthesis, and audio transcription. CometAPI positions itself as a drop-in replacement for the OpenAI SDK (changing only the base URL and key), with pay-as-you-go pricing reportedly 20-40% cheaper than direct vendor rates, sub-400ms median latency, and 99.9% service availability.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cometapi Context
  property_count: 4
  slug: cometapi-context
layout: provider
modified: '2026-04-26'
name: CometAPI
rules:
- name: CometAPI API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 3
  slug: cometapi-rules
skills: []
slug: cometapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cometapi\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/apis.yml\nname: CometAPI\ntags:\n  - AI\n  - Aggregator\n  - Audio\n  - Chat\n  - Embeddings\n  - Generative AI\n  - Images\n  - LLM\n  - Multi-Model\n  - OpenAI-Compatible\n  - Video\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2026-03-16'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  CometAPI is an AI API aggregator that consolidates access to 500+ models\n  from multiple providers (OpenAI, Anthropic, Google, xAI, DeepSeek,\n  Alibaba, and more) behind a single OpenAI-compatible REST surface. It\n  supports chat completions, embeddings, image generation, text-to-video\n  and image-to-video, speech synthesis, and audio transcription. CometAPI\n  positions itself as a drop-in replacement for the OpenAI SDK (changing\n  only the base URL and key), with pay-as-you-go\
  \ pricing reportedly 20-40%\n  cheaper than direct vendor rates, sub-400ms median latency, and 99.9%\n  service availability.\napis:\n  - aid: cometapi:cometapi-unified-api\n    name: CometAPI Unified API\n    tags:\n      - AI\n      - Aggregator\n      - Chat\n      - Embeddings\n      - Images\n      - OpenAI-Compatible\n      - Video\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cometapi.com/v1\n    humanURL: https://apidoc.cometapi.com/\n    properties:\n      - url: https://apidoc.cometapi.com/\n        type: Documentation\n      - url: https://www.cometapi.com/\n        type: Marketing\n      - url: openapi/cometapi-unified-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      OpenAI-compatible REST API exposing chat completions, embeddings,\n      image generation, video generation, speech synthesis, and audio\n      transcription across hundreds of upstream models. Authentication\n      uses a bearer\
  \ token, and the `model` field on each request selects\n      the upstream provider (e.g. gpt-5.5, claude-4-7-opus,\n      gemini-2.5-pro, deepseek-v4, sora, veo, kling, whisper).\n    x-features:\n      - One bearer-token credential for 500+ models\n      - OpenAI SDK drop-in (only base URL and key change)\n      - Chat, embeddings, images, video, speech, and transcription\n      - Streaming chat completions\n      - Tool/function calling support\n      - Pay-as-you-go billing with no monthly fees\n      - Real-time usage analytics and per-key budget controls\n      - Sub-400ms median latency, 99.9% availability\n    x-use-cases:\n      - Replacing single-vendor SDKs in SaaS apps\n      - Cross-vendor model evaluation and A/B testing\n      - Cost consolidation across an enterprise AI portfolio\n      - Multi-modal pipelines combining text, image, video, and audio models\n      - Internal model routers and prompt-experimentation tooling\ncommon:\n  - type: Website\n    url: https://www.cometapi.com/\n\
  \  - type: Documentation\n    url: https://apidoc.cometapi.com/\n  - type: HelpCenter\n    url: https://apidoc.cometapi.com/help-center\n  - type: GettingStarted\n    url: https://apidoc.cometapi.com/how-to-use-cometapi-1792005m0\n  - url: json-ld/cometapi-context.jsonld\n    type: JSON-LD\n  - url: json-schema/cometapi-chat-completion-schema.json\n    type: JSONSchema\n  - url: rules/cometapi-rules.yml\n    type: Spectral\n  - url: capabilities/cometapi-multi-model-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/apis.yml
tags:
- AI
- Aggregator
- Audio
- Chat
- Embeddings
- Generative AI
- Images
- LLM
- Multi-Model
- OpenAI-Compatible
- Video
url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/apis.yml
use_cases: []
---
