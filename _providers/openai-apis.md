---
api_count: 7
api_specs:
- filename: openai-chat-completions-openapi.yml
  format: yaml
  label: OpenAI Chat Completions API
  slug: openai-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-chat-completions-openapi.yml
- filename: openai-completions-openapi.yml
  format: yaml
  label: OpenAI Completions API
  slug: openai-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-completions-openapi.yml
- filename: openai-images-openapi.yml
  format: yaml
  label: OpenAI Images API
  slug: openai-images-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-images-openapi.yml
- filename: openai-embeddings-openapi.yml
  format: yaml
  label: OpenAI Embeddings API
  slug: openai-embeddings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-embeddings-openapi.yml
- filename: openai-audio-openapi.yml
  format: yaml
  label: OpenAI Audio API
  slug: openai-audio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-audio-openapi.yml
- filename: openai-moderations-openapi.yml
  format: yaml
  label: OpenAI Moderations API
  slug: openai-moderations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-moderations-openapi.yml
- filename: openai-assistants-openapi.yml
  format: yaml
  label: OpenAI Assistants API
  slug: openai-assistants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-assistants-openapi.yml
apis:
- description: API for conversational AI using GPT models.
  name: OpenAI Chat Completions API
  slug: openai-chat-completions-api
- description: Legacy text completion API for generating text continuations from a prompt.
  name: OpenAI Completions API
  slug: openai-completions-api
- description: API for generating, editing, and creating image variations using DALL-E.
  name: OpenAI Images API
  slug: openai-images-api
- description: API for converting text into vector representations.
  name: OpenAI Embeddings API
  slug: openai-embeddings-api
- description: API for speech-to-text transcription and text-to-speech generation.
  name: OpenAI Audio API
  slug: openai-audio-api
- description: API for detecting potentially harmful or unsafe content across text and images.
  name: OpenAI Moderations API
  slug: openai-moderations-api
- description: API for building AI assistants with custom instructions and tool access.
  name: OpenAI Assistants API
  slug: openai-assistants-api
common:
- title: ''
  type: Authentication
  url: https://platform.openai.com/docs/api-reference/authentication
- title: ''
  type: Pricing
  url: https://openai.com/api/pricing/
- title: ''
  type: Terms of Service
  url: https://openai.com/policies/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://openai.com/policies/privacy-policy
- title: ''
  type: Status
  url: https://status.openai.com/
created: '2024-01-01'
description: Collection of OpenAI's artificial intelligence APIs for natural language processing, image generation, speech, and embeddings including Chat Completions, Completions, Images, Audio, Embeddings, Moderations, and Assistants APIs.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Openai Context
  property_count: 13
  slug: openai-context
layout: provider
modified: '2026-04-28'
name: OpenAI APIs
skills: []
slug: openai-apis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openai-apis\nname: OpenAI APIs\ndescription: >-\n  Collection of OpenAI's artificial intelligence APIs for natural language\n  processing, image generation, speech, and embeddings including Chat\n  Completions, Completions, Images, Audio, Embeddings, Moderations, and\n  Assistants APIs.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Embeddings\n  - Image Generation\n  - Language Models\n  - Speech\nurl: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: openai-apis:openai-chat-completions-api\n    name: OpenAI Chat Completions API\n    description: API for conversational AI using GPT models.\n    humanURL: https://platform.openai.com/docs/api-reference/chat\n    baseURL: https://api.openai.com/v1\n    tags:\n      -\
  \ Chat\n      - GPT\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/chat\n      - type: OpenAPI\n        url: openapi/openai-chat-completions-openapi.yml\n  - aid: openai-apis:openai-completions-api\n    name: OpenAI Completions API\n    description: Legacy text completion API for generating text continuations from a prompt.\n    humanURL: https://platform.openai.com/docs/api-reference/completions\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Completions\n      - GPT\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/completions\n      - type: OpenAPI\n        url: openapi/openai-completions-openapi.yml\n  - aid: openai-apis:openai-images-api\n    name: OpenAI Images API\n    description: API for generating, editing, and creating image variations using DALL-E.\n    humanURL: https://platform.openai.com/docs/api-reference/images\n    baseURL: https://api.openai.com/v1\n\
  \    tags:\n      - DALL-E\n      - Image Generation\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/images\n      - type: OpenAPI\n        url: openapi/openai-images-openapi.yml\n  - aid: openai-apis:openai-embeddings-api\n    name: OpenAI Embeddings API\n    description: API for converting text into vector representations.\n    humanURL: https://platform.openai.com/docs/api-reference/embeddings\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Embeddings\n      - Vectors\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/embeddings\n      - type: OpenAPI\n        url: openapi/openai-embeddings-openapi.yml\n  - aid: openai-apis:openai-audio-api\n    name: OpenAI Audio API\n    description: API for speech-to-text transcription and text-to-speech generation.\n    humanURL: https://platform.openai.com/docs/api-reference/audio\n    baseURL: https://api.openai.com/v1\n\
  \    tags:\n      - Audio\n      - Speech\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/audio\n      - type: OpenAPI\n        url: openapi/openai-audio-openapi.yml\n  - aid: openai-apis:openai-moderations-api\n    name: OpenAI Moderations API\n    description: API for detecting potentially harmful or unsafe content across text and images.\n    humanURL: https://platform.openai.com/docs/api-reference/moderations\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Moderation\n      - Safety\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/moderations\n      - type: OpenAPI\n        url: openapi/openai-moderations-openapi.yml\n  - aid: openai-apis:openai-assistants-api\n    name: OpenAI Assistants API\n    description: API for building AI assistants with custom instructions and tool access.\n    humanURL: https://platform.openai.com/docs/api-reference/assistants\n\
  \    baseURL: https://api.openai.com/v1\n    tags:\n      - Agents\n      - Assistants\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/assistants\n      - type: OpenAPI\n        url: openapi/openai-assistants-openapi.yml\ncommon:\n  - type: Authentication\n    url: https://platform.openai.com/docs/api-reference/authentication\n  - type: Pricing\n    url: https://openai.com/api/pricing/\n  - type: Terms of Service\n    url: https://openai.com/policies/terms-of-use\n  - type: Privacy Policy\n    url: https://openai.com/policies/privacy-policy\n  - type: Status\n    url: https://status.openai.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Embeddings
- Image Generation
- Language Models
- Speech
url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/apis.yml
use_cases: []
---
