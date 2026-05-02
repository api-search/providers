---
api_count: 20
apis:
- description: Provides an OpenAI-compatible /chat/completions endpoint that routes requests to 100+ LLM providers with unified request and response formatting, streaming support, cost tracking, and load balancing.
  name: LiteLLM Chat Completions API
  slug: chat-completions-api
- description: Provides an OpenAI-compatible /completions endpoint for text completion requests routed through the LiteLLM proxy to supported LLM providers.
  name: LiteLLM Completions API
  slug: completions-api
- description: Provides an OpenAI-compatible /responses endpoint supporting the Responses API specification, including conversation history compression via /responses/compact.
  name: LiteLLM Responses API
  slug: responses-api
- description: Provides an OpenAI-compatible /embeddings endpoint for generating text embeddings across multiple providers including OpenAI, Cohere, HuggingFace, and Bedrock with unified formatting.
  name: LiteLLM Embeddings API
  slug: embeddings-api
- description: Provides OpenAI-compatible /images/generations, /images/edits, and /images/variations endpoints for image generation and manipulation routed through the LiteLLM proxy.
  name: LiteLLM Image Generation API
  slug: image-generation-api
- description: Provides OpenAI-compatible /audio/transcriptions and /audio/speech endpoints for audio transcription and text-to-speech conversion across supported providers.
  name: LiteLLM Audio API
  slug: audio-api
- description: Provides an OpenAI-compatible /moderations endpoint for content moderation across supported providers through the LiteLLM proxy.
  name: LiteLLM Moderations API
  slug: moderations-api
- description: Provides an OpenAI-compatible /batches endpoint for batch processing operations, enabling bulk request handling across LLM providers.
  name: LiteLLM Batches API
  slug: batches-api
- description: Provides an OpenAI-compatible /files endpoint for file management operations used in conjunction with fine-tuning and batch processing.
  name: LiteLLM Files API
  slug: files-api
- description: Provides an OpenAI-compatible /fine_tuning endpoint for model fine-tuning operations across supported providers through the LiteLLM proxy.
  name: LiteLLM Fine-Tuning API
  slug: fine-tuning-api
- description: Provides a /rerank endpoint for document reranking operations, supporting providers like Cohere through the LiteLLM proxy with a unified interface.
  name: LiteLLM Rerank API
  slug: rerank-api
- description: Provides /vector_stores endpoints for creating and managing vector stores, file operations within vector stores, and search functionality for retrieval-augmented generation (RAG) use cases.
  name: LiteLLM Vector Stores API
  slug: vector-stores-api
- description: Provides Anthropic-compatible /v1/messages and /v1/messages/count_tokens endpoints for native Anthropic API format support through the LiteLLM proxy.
  name: LiteLLM Anthropic Messages API
  slug: messages-api
- description: Provides /realtime WebSocket endpoints for real-time model interactions with load balancing and guardrails support across providers.
  name: LiteLLM Realtime API
  slug: realtime-api
- description: Provides /mcp endpoints for Model Context Protocol (MCP) integration, enabling LLMs to interact with external tools and APIs through OpenAPI specifications.
  name: LiteLLM MCP API
  slug: mcp-api
- description: Provides an /ocr endpoint for optical character recognition, enabling text extraction from images through supported providers via the LiteLLM proxy.
  name: LiteLLM OCR API
  slug: ocr-api
- description: Provides /guardrails/apply_guardrail endpoint for applying configured content filtering and safety guardrails to LLM requests and responses.
  name: LiteLLM Guardrails API
  slug: guardrails-api
- description: Provides /evals endpoints for the Evaluations API, enabling measurement and benchmarking of model performance through the LiteLLM proxy.
  name: LiteLLM Evals API
  slug: evals-api
- description: Provides /a2a endpoints for the Agent-to-Agent (A2A) gateway, enabling agent registration, publishing, and inter-agent communication.
  name: LiteLLM A2A Agent Gateway API
  slug: a2a-api
- description: Provides /videos endpoints for video generation and handling through supported providers like RunwayML via the LiteLLM proxy.
  name: LiteLLM Videos API
  slug: videos-api
common:
- title: ''
  type: Portal
  url: https://www.litellm.ai/
- title: ''
  type: Documentation
  url: https://docs.litellm.ai/docs/
- title: ''
  type: GettingStarted
  url: https://docs.litellm.ai/docs/proxy/quick_start
- title: ''
  type: GitHubOrg
  url: https://github.com/BerriAI/litellm
- title: ''
  type: Blog
  url: https://docs.litellm.ai/blog
- title: ''
  type: ChangeLog
  url: https://www.litellm.ai/changelog
- title: ''
  type: ReleaseNotes
  url: https://docs.litellm.ai/release_notes
- title: ''
  type: Status
  url: https://status.litellm.ai/
- title: ''
  type: Support
  url: https://www.litellm.ai/support
- title: ''
  type: Pricing
  url: https://docs.litellm.ai/docs/enterprise
- title: ''
  type: Dashboard
  url: https://admin.litellm.ai/
- title: ''
  type: Providers
  url: https://docs.litellm.ai/docs/providers
- title: ''
  type: Models
  url: https://models.litellm.ai/
- title: ''
  type: Configuration
  url: https://docs.litellm.ai/docs/proxy/configs
- title: ''
  type: Authentication
  url: https://docs.litellm.ai/docs/set_keys
- title: ''
  type: Guardrails
  url: https://docs.litellm.ai/docs/apply_guardrail
- title: ''
  type: Enterprise
  url: https://docs.litellm.ai/docs/proxy/enterprise
- title: ''
  type: ReleaseCycle
  url: https://docs.litellm.ai/docs/proxy/release_cycle
- title: ''
  type: SSO
  url: https://docs.litellm.ai/docs/proxy/admin_ui_sso
- title: ''
  type: Docker
  url: https://docs.litellm.ai/docs/proxy/docker_quick_start
- title: ''
  type: PyPI
  url: https://pypi.org/project/litellm/
created: '2026-03-03'
description: LiteLLM is an open-source Python SDK and proxy server providing a unified OpenAI-compatible interface to 100+ LLM providers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LiteLLM
skills: []
slug: litellm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: litellm\nname: LiteLLM\nsegments:\n  - Gateways\ndescription: >-\n  LiteLLM is an open-source Python SDK and proxy server providing a unified OpenAI-compatible interface to 100+ LLM providers.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Gateways\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/litellm/refs/heads/master/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: litellm:chat-completions-api\n    name: LiteLLM Chat Completions API\n    description: >-\n      Provides an OpenAI-compatible /chat/completions endpoint that routes\n      requests to 100+ LLM providers with unified request and response\n      formatting, streaming support, cost tracking, and load balancing.\n    humanURL: https://docs.litellm.ai/docs/completion\n    tags:\n      - AI\n      - Chat\n      - Completions\n      - LLM\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.litellm.ai/docs/completion\n      - type: GettingStarted\n        url: https://docs.litellm.ai/docs/proxy/quick_start\n  - aid: litellm:completions-api\n    name: LiteLLM Completions API\n    description: >-\n      Provides an OpenAI-compatible /completions endpoint for text completion\n      requests routed through the LiteLLM proxy to supported LLM providers.\n    humanURL: https://docs.litellm.ai/docs/text_completion\n    tags:\n      - Completions\n      - LLM\n      - Text\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/text_completion\n  - aid: litellm:responses-api\n    name: LiteLLM Responses API\n    description: >-\n      Provides an OpenAI-compatible /responses endpoint supporting the\n      Responses API specification, including conversation history compression\n      via /responses/compact.\n    humanURL: https://docs.litellm.ai/docs/response_api\n    tags:\n      - AI\n      -\
  \ LLM\n      - Responses\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/response_api\n  - aid: litellm:embeddings-api\n    name: LiteLLM Embeddings API\n    description: >-\n      Provides an OpenAI-compatible /embeddings endpoint for generating text\n      embeddings across multiple providers including OpenAI, Cohere, HuggingFace,\n      and Bedrock with unified formatting.\n    humanURL: https://docs.litellm.ai/docs/embedding/supported_embedding\n    tags:\n      - AI\n      - Embeddings\n      - Vectors\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/embedding/supported_embedding\n  - aid: litellm:image-generation-api\n    name: LiteLLM Image Generation API\n    description: >-\n      Provides OpenAI-compatible /images/generations, /images/edits, and\n      /images/variations endpoints for image generation and manipulation\n      routed through the LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/image_generation\n\
  \    tags:\n      - AI\n      - Generation\n      - Images\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/image_generation\n  - aid: litellm:audio-api\n    name: LiteLLM Audio API\n    description: >-\n      Provides OpenAI-compatible /audio/transcriptions and /audio/speech\n      endpoints for audio transcription and text-to-speech conversion across\n      supported providers.\n    humanURL: https://docs.litellm.ai/docs/audio_transcription\n    tags:\n      - AI\n      - Audio\n      - Speech\n      - Transcription\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/audio_transcription\n  - aid: litellm:moderations-api\n    name: LiteLLM Moderations API\n    description: >-\n      Provides an OpenAI-compatible /moderations endpoint for content\n      moderation across supported providers through the LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/moderation\n    tags:\n      - Content\n      - Moderation\n\
  \      - Safety\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/moderation\n  - aid: litellm:batches-api\n    name: LiteLLM Batches API\n    description: >-\n      Provides an OpenAI-compatible /batches endpoint for batch processing\n      operations, enabling bulk request handling across LLM providers.\n    humanURL: https://docs.litellm.ai/docs/batches\n    tags:\n      - Batches\n      - Bulk\n      - Processing\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/batches\n  - aid: litellm:files-api\n    name: LiteLLM Files API\n    description: >-\n      Provides an OpenAI-compatible /files endpoint for file management\n      operations used in conjunction with fine-tuning and batch processing.\n    humanURL: https://docs.litellm.ai/docs/files_endpoints\n    tags:\n      - Files\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/files_endpoints\n  -\
  \ aid: litellm:fine-tuning-api\n    name: LiteLLM Fine-Tuning API\n    description: >-\n      Provides an OpenAI-compatible /fine_tuning endpoint for model\n      fine-tuning operations across supported providers through the\n      LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/fine_tuning\n    tags:\n      - Fine-Tuning\n      - Models\n      - Training\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/fine_tuning\n  - aid: litellm:rerank-api\n    name: LiteLLM Rerank API\n    description: >-\n      Provides a /rerank endpoint for document reranking operations, supporting\n      providers like Cohere through the LiteLLM proxy with a unified interface.\n    humanURL: https://docs.litellm.ai/docs/rerank\n    tags:\n      - Relevance\n      - Rerank\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/rerank\n  - aid: litellm:vector-stores-api\n    name: LiteLLM Vector Stores API\n    description:\
  \ >-\n      Provides /vector_stores endpoints for creating and managing vector stores,\n      file operations within vector stores, and search functionality for\n      retrieval-augmented generation (RAG) use cases.\n    humanURL: https://docs.litellm.ai/docs/vector_stores/create\n    tags:\n      - RAG\n      - Search\n      - Storage\n      - Vectors\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/vector_stores/create\n  - aid: litellm:messages-api\n    name: LiteLLM Anthropic Messages API\n    description: >-\n      Provides Anthropic-compatible /v1/messages and /v1/messages/count_tokens\n      endpoints for native Anthropic API format support through the LiteLLM\n      proxy.\n    humanURL: https://docs.litellm.ai/docs/anthropic_unified/\n    tags:\n      - AI\n      - Anthropic\n      - Messages\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/anthropic_unified/\n  - aid: litellm:realtime-api\n    name:\
  \ LiteLLM Realtime API\n    description: >-\n      Provides /realtime WebSocket endpoints for real-time model interactions\n      with load balancing and guardrails support across providers.\n    humanURL: https://docs.litellm.ai/docs/realtime\n    tags:\n      - Realtime\n      - Streaming\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/realtime\n  - aid: litellm:mcp-api\n    name: LiteLLM MCP API\n    description: >-\n      Provides /mcp endpoints for Model Context Protocol (MCP) integration,\n      enabling LLMs to interact with external tools and APIs through\n      OpenAPI specifications.\n    humanURL: https://docs.litellm.ai/docs/mcp\n    tags:\n      - MCP\n      - Protocols\n      - Tools\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/mcp\n  - aid: litellm:ocr-api\n    name: LiteLLM OCR API\n    description: >-\n      Provides an /ocr endpoint for optical character recognition,\
  \ enabling\n      text extraction from images through supported providers via the\n      LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/ocr\n    tags:\n      - Images\n      - OCR\n      - Text Extraction\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/ocr\n  - aid: litellm:guardrails-api\n    name: LiteLLM Guardrails API\n    description: >-\n      Provides /guardrails/apply_guardrail endpoint for applying configured\n      content filtering and safety guardrails to LLM requests and responses.\n    humanURL: https://docs.litellm.ai/docs/apply_guardrail\n    tags:\n      - Content Filtering\n      - Guardrails\n      - Safety\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/apply_guardrail\n  - aid: litellm:evals-api\n    name: LiteLLM Evals API\n    description: >-\n      Provides /evals endpoints for the Evaluations API, enabling measurement\n      and benchmarking of model performance through\
  \ the LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/evals_api\n    tags:\n      - Benchmarks\n      - Evaluations\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/evals_api\n  - aid: litellm:a2a-api\n    name: LiteLLM A2A Agent Gateway API\n    description: >-\n      Provides /a2a endpoints for the Agent-to-Agent (A2A) gateway, enabling\n      agent registration, publishing, and inter-agent communication.\n    humanURL: https://docs.litellm.ai/docs/a2a\n    tags:\n      - A2A\n      - Agents\n      - Gateway\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/a2a\n  - aid: litellm:videos-api\n    name: LiteLLM Videos API\n    description: >-\n      Provides /videos endpoints for video generation and handling through\n      supported providers like RunwayML via the LiteLLM proxy.\n    humanURL: https://docs.litellm.ai/docs/videos\n    tags:\n      - AI\n      - Generation\n   \
  \   - Videos\n    properties:\n      - type: Documentation\n        url: https://docs.litellm.ai/docs/videos\ncommon:\n  - type: Portal\n    url: https://www.litellm.ai/\n  - type: Documentation\n    url: https://docs.litellm.ai/docs/\n  - type: GettingStarted\n    url: https://docs.litellm.ai/docs/proxy/quick_start\n  - type: GitHubOrg\n    url: https://github.com/BerriAI/litellm\n  - type: Blog\n    url: https://docs.litellm.ai/blog\n  - type: ChangeLog\n    url: https://www.litellm.ai/changelog\n  - type: ReleaseNotes\n    url: https://docs.litellm.ai/release_notes\n  - type: Status\n    url: https://status.litellm.ai/\n  - type: Support\n    url: https://www.litellm.ai/support\n  - type: Pricing\n    url: https://docs.litellm.ai/docs/enterprise\n  - type: Dashboard\n    url: https://admin.litellm.ai/\n  - type: Providers\n    url: https://docs.litellm.ai/docs/providers\n  - type: Models\n    url: https://models.litellm.ai/\n  - type: Configuration\n    url: https://docs.litellm.ai/docs/proxy/configs\n\
  \  - type: Authentication\n    url: https://docs.litellm.ai/docs/set_keys\n  - type: Guardrails\n    url: https://docs.litellm.ai/docs/apply_guardrail\n  - type: Enterprise\n    url: https://docs.litellm.ai/docs/proxy/enterprise\n  - type: ReleaseCycle\n    url: https://docs.litellm.ai/docs/proxy/release_cycle\n  - type: SSO\n    url: https://docs.litellm.ai/docs/proxy/admin_ui_sso\n  - type: Docker\n    url: https://docs.litellm.ai/docs/proxy/docker_quick_start\n  - type: PyPI\n    url: https://pypi.org/project/litellm/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/litellm/refs/heads/main/apis.yml
tags:
- Gateways
url: https://raw.githubusercontent.com/api-evangelist/litellm/refs/heads/master/apis.yml
use_cases: []
---
