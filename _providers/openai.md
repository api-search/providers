---
api_count: 22
api_specs:
- filename: assistants-openapi-original.yml
  format: yaml
  label: OpenAI Assistants API
  slug: openai-assistants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/assistants-openapi-original.yml
- filename: audio-openapi-original.yml
  format: yaml
  label: OpenAI Audio API
  slug: openai-audio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/audio-openapi-original.yml
- filename: chat-openapi-original.yml
  format: yaml
  label: OpenAI Chat API
  slug: openai-chat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/chat-openapi-original.yml
- filename: openai-chat-completions-openapi.yml
  format: yaml
  label: OpenAI Chat Completions API
  slug: openai-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/openai-chat-completions-openapi.yml
- filename: embeddings-openapi-original.yml
  format: yaml
  label: OpenAI Embeddings API
  slug: openai-embeddings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/embeddings-openapi-original.yml
- filename: files-openapi-original.yml
  format: yaml
  label: OpenAI Files API
  slug: openai-files-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/files-openapi-original.yml
- filename: fine-tuning-openapi-original.yml
  format: yaml
  label: OpenAI Fine Tuning API
  slug: openai-fine-tuning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/fine-tuning-openapi-original.yml
- filename: images-openapi-original.yml
  format: yaml
  label: OpenAI Images API
  slug: openai-images-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/images-openapi-original.yml
- filename: models-openapi-original.yml
  format: yaml
  label: OpenAI Models API
  slug: openai-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/models-openapi-original.yml
- filename: threads-openapi-original.yml
  format: yaml
  label: OpenAI Threads API
  slug: openai-threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/threads-openapi-original.yml
- filename: completions-openapi-original.yml
  format: yaml
  label: OpenAI Completions API
  slug: openai-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/completions-openapi-original.yml
apis:
- description: The Assistants API allows you to build AI assistants within your own applications. An Assistant has instructions and can leverage models, tools, and knowledge to respond to user queries. The Assistant
  name: OpenAI Assistants API
  slug: openai-assistants-api
- description: The Audio API provides two speech to text endpoints, transcriptions and translations, based on our state-of-the-art open source large-v2 Whisper model.
  name: OpenAI Audio API
  slug: openai-audio-api
- description: Given a list of messages comprising a conversation, the model will return a response., providing an AI chat interface you can use to engage with users.
  name: OpenAI Chat API
  slug: openai-chat-api
- description: Chat models take a list of messages as input and return a model-generated message as output. Although the chat format is designed to make multi-turn conversations easy, it's just as useful for single-
  name: OpenAI Chat Completions API
  slug: openai-chat-completions-api
- description: Learn how to turn text into numbers, unlocking use cases like search. OpenAI's text embeddings measure the relatedness of text strings.
  name: OpenAI Embeddings API
  slug: openai-embeddings-api
- description: Files are used to upload documents that can be used with features like Assistants and Fine-tuning. Upload a file that can be used across various endpoints. The size of all the files uploaded by one or
  name: OpenAI Files API
  slug: openai-files-api
- description: Manage fine-tuning jobs to tailor a model to your specific training data. Creates a fine-tuning job which begins the process of creating a new model from a given dataset.Response includes details of t
  name: OpenAI Fine Tuning API
  slug: openai-fine-tuning-api
- description: Learn how to generate or manipulate images with DALL_E in the API. The Images API provides three methods for interacting with images - creating images from scratch based on a text prompt, creating edi
  name: OpenAI Images API
  slug: openai-images-api
- description: List and describe the various models available in the API. You can refer to the Models documentation to understand what models are available and the differences between them.
  name: OpenAI Models API
  slug: openai-models-api
- description: Create threads that assistants can interact with.
  name: OpenAI Threads API
  slug: openai-threads-api
- description: The Responses API is OpenAI's most advanced interface for generating model responses. It combines the strengths of the Chat Completions and Assistants APIs into a single streamlined interface, support
  name: OpenAI Responses API
  slug: openai-responses-api
- description: The Moderations API can be used to check whether text or images are potentially harmful. It classifies content across several categories including harassment, hate speech, sexual content, self-harm, v
  name: OpenAI Moderations API
  slug: openai-moderations-api
- description: The Batch API enables asynchronous processing of requests with 50% cost discount, higher rate limits, and completion within 24 hours. It supports /v1/responses, /v1/chat/completions, /v1/embeddings, /
  name: OpenAI Batch API
  slug: openai-batch-api
- description: Vector stores are collections of processed files that power semantic search for the file_search tool in the Responses and Assistants APIs. When you add a file to a vector store it is automatically chu
  name: OpenAI Vector Stores API
  slug: openai-vector-stores-api
- description: The Uploads API creates an intermediate Upload object that you can add Parts to, enabling large file uploads. Currently an Upload can accept at most 8 GB in total and expires after an hour. Once you c
  name: OpenAI Uploads API
  slug: openai-uploads-api
- description: The Realtime API enables low-latency, bidirectional communication with models that natively support speech-to-speech interactions as well as multimodal inputs (audio, images, and text) and outputs (au
  name: OpenAI Realtime API
  slug: openai-realtime-api
- description: The Evals API allows you to programmatically configure and run evaluations to test model outputs against your expectations. Evaluations ensure model responses meet style and content criteria you speci
  name: OpenAI Evals API
  slug: openai-evals-api
- description: 'The legacy Completions API endpoint provides a freeform text completion interface using a text prompt. Unlike the Chat Completions endpoint which uses a list of messages, the Completions API input is '
  name: OpenAI Completions API
  slug: openai-completions-api
- description: The Videos API enables programmatic creation, extension, and remixing of videos using Sora models. It provides endpoints for creating a new render job from a text prompt, checking video status, downlo
  name: OpenAI Videos API
  slug: openai-videos-api
- description: The Conversations API allows you to create and manage stateful conversations for use with the Responses API. A conversation object contains an id, a created_at timestamp, and metadata. Because convers
  name: OpenAI Conversations API
  slug: openai-conversations-api
- description: 'The Containers API manages sandboxed containers used by Code Interpreter for running Python, data work, file transforms, and iterative debugging. Containers can be created explicitly or auto-managed, '
  name: OpenAI Containers API
  slug: openai-containers-api
- description: ChatKit is the best way to build agentic chat experiences. It provides session and thread management for building internal knowledge base assistants, research companions, support agents, and more. Cha
  name: OpenAI ChatKit API
  slug: openai-chatkit-api
capabilities:
- description: Unified content generation combining Chat, Images, Audio, and Embeddings APIs for developers to generate text, images, speech, and vector representations.
  name: OpenAI Content Generation
  slug: content-generation
common:
- title: ''
  type: Portal
  url: https://platform.openai.com/docs/overview
- title: ''
  type: GettingStarted
  url: https://platform.openai.com/docs/quickstart
- title: ''
  type: SDKs
  url: https://platform.openai.com/docs/libraries
- title: ''
  type: Forums
  url: https://community.openai.com/categories
- title: ''
  type: RateLimits
  url: https://platform.openai.com/docs/guides/rate-limits
- title: ''
  type: Deprecations
  url: https://platform.openai.com/docs/deprecations
- title: ''
  type: TermsOfService
  url: https://openai.com/policies/
- title: ''
  type: TermsOfService
  url: https://openai.com/policies/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://openai.com/policies/privacy-policy/
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/overview
- title: ''
  type: Support
  url: https://help.openai.com/en
- title: ''
  type: Status
  url: https://status.openai.com/
- title: ''
  type: Authentication
  url: https://platform.openai.com/docs/api-reference/authentication
- title: ''
  type: Webhooks
  url: https://platform.openai.com/docs/api-reference/webhook_events/response
- title: ''
  type: OpenAPI
  url: properties/openai-openapi
- title: ''
  type: JSONSchema
  url: json-schema/openai-chat-completion-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/openai-embedding-schema.json
- title: ''
  type: JSONLD
  url: json-ld/openai-context.jsonld
- title: ''
  type: GitHubOrganization
  url: https://github.com/openai
- title: ''
  type: Plans
  url: https://openai.com/api/pricing/
- title: ''
  type: Pricing
  url: https://openai.com/api/pricing/
- title: ''
  type: Tiers
  url: https://openai.com/api/pricing/
- title: ''
  type: RateLimits
  url: https://example.com/rate-limits
- title: ''
  type: StatusPage
  url: https://status.openai.com/
- title: ''
  type: API Keys
  url: https://platform.openai.com/api-keys
- title: ''
  type: Signup
  url: https://platform.openai.com/signup
- title: ''
  type: Login
  url: https://platform.openai.com/login
- title: ''
  type: ChangeLog
  url: https://developers.openai.com/changelog/
- title: ''
  type: Blog
  url: https://developers.openai.com/blog/
- title: ''
  type: Cookbook
  url: https://cookbook.openai.com/
- title: ''
  type: SafetyBestPractices
  url: https://platform.openai.com/docs/guides/safety-best-practices
- title: ''
  type: BestPractices
  url: https://platform.openai.com/docs/guides/production-best-practices
- title: ''
  type: Security
  url: https://openai.com/security-and-privacy/
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/administration
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/audit-logs
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/usage
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/guides/function-calling
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/guides/structured-outputs
- title: ''
  type: GitHubRepository
  url: https://github.com/openai/openai-openapi
- title: ''
  type: GitHubRepository
  url: https://github.com/openai/openai-python
- title: ''
  type: GitHubRepository
  url: https://github.com/openai/openai-node
- title: ''
  type: TermsOfService
  url: https://openai.com/policies/service-terms/
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/guides/webhooks
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/webhook-events
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/docs/guides/deep-research/
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/docs/guides/voice-agents/
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/docs/guides/code-generation/
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/guides/images-vision
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/docs/guides/conversation-state/
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/docs/guides/migrate-to-responses/
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/containers
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/container-files
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/chatkit
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/videos
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference/conversations/create
- title: ''
  type: Portal
  url: https://developers.openai.com/
- title: ''
  type: Documentation
  url: https://developers.openai.com/api/reference/
- title: ''
  type: Documentation
  url: https://developers.openai.com/codex
- title: ''
  type: GitHubRepository
  url: https://github.com/openai/chatkit-js
- title: ''
  type: SpectralRules
  url: rules/openai-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/openai-vocabulary.yaml
created: '2024-04-14'
description: APIs for accessing OpenAI's artificial intelligence models including GPT, DALL-E, Whisper, and Embeddings.
features:
- description: Generate conversational responses using GPT models with multi-turn message history, function calling, and structured outputs.
  name: Chat Completions
- description: Advanced model response interface combining Chat Completions and Assistants with built-in tools like web search and code interpreter.
  name: Responses API
- description: Build AI assistants with persistent threads, code interpreter, file search, and function calling capabilities.
  name: Assistants
- description: Low-latency bidirectional communication for speech-to-speech interactions via WebRTC, WebSocket, and SIP connections.
  name: Realtime API
- description: Create, edit, and generate variations of images using DALL-E models from text prompts.
  name: Image Generation
- description: Text-to-speech synthesis and speech-to-text transcription and translation using Whisper and TTS models.
  name: Audio and Speech
- description: Generate vector representations of text for semantic search, clustering, and recommendation use cases.
  name: Embeddings
- description: Customize models on your own training data to improve performance for specific tasks and domains.
  name: Fine-Tuning
- description: Asynchronous processing of up to 50,000 requests at 50% cost discount with 24-hour completion window.
  name: Batch Processing
- description: Programmatically configure and run evaluations to test model outputs against quality and content criteria.
  name: Evals
- description: Create, extend, and remix videos using Sora models from text prompts via the Videos API.
  name: Video Generation
- description: Managed document storage with automatic chunking, embedding, and semantic search for file_search tool.
  name: Vector Stores
image: https://openai.com/favicon.ico
integrations:
- description: Official Python client library for accessing all OpenAI API endpoints with async support and streaming.
  name: Python SDK
- description: Official TypeScript and JavaScript client library for server-side and edge runtime OpenAI API integration.
  name: Node.js SDK
- description: Run OpenAI models on Azure infrastructure with enterprise security, compliance, and regional data residency.
  name: Microsoft Azure OpenAI
- description: Framework integration for building LLM-powered applications with chains, agents, and retrieval-augmented generation.
  name: LangChain
- description: Integration with Vercel AI SDK for building streaming AI-powered web applications with React and Next.js.
  name: Vercel AI SDK
- description: No-code automation integration connecting OpenAI to thousands of apps for automated AI-powered workflows.
  name: Zapier
jsonld:
- class_count: 0
  name: Openai Audio Context
  property_count: 0
  slug: openai-audio-context
- class_count: 0
  name: Openai Chat Completions Context
  property_count: 0
  slug: openai-chat-completions-context
- class_count: 0
  name: Openai Context
  property_count: 15
  slug: openai-context
- class_count: 0
  name: Openai Embeddings Context
  property_count: 0
  slug: openai-embeddings-context
- class_count: 0
  name: Openai Images Context
  property_count: 0
  slug: openai-images-context
layout: provider
modified: '2026-04-18'
name: OpenAI
rules:
- name: OpenAI API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: openai-spectral-rules
skills: []
slug: openai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openai\nurl: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/apis.yml\napis:\n  - aid: openai:openai-assistants-api\n    name: OpenAI Assistants API\n    tags:\n      - Assistants\n    score: 1329\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/assistants/overview\n    properties:\n      - url: https://platform.openai.com/docs/assistants/overview\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/assistants\n        type: Documentation\n      - url: openapi/assistants-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Assistants API allows you to build AI assistants within your own applications.\n      An Assistant has instructions and can leverage models, tools, and knowledge\n      to respond to user queries. The Assistants API currently supports three types\n      of tools - Code Interpreter, Retrieval, and Function calling. In the future,\n \
  \     we plan to release more OpenAI-built tools, and allow you to provide your own\n      tools on our platform.\n  - aid: openai:openai-audio-api\n    name: OpenAI Audio API\n    tags:\n      - Audio\n    score: 128\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/guides/text-to-speech\n    properties:\n      - url: https://platform.openai.com/docs/guides/text-to-speech\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/audio\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/speech-to-text\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/audio/\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/voice-agents/\n        type: Documentation\n      - url: openapi/audio-openapi-original.yml\n        type: OpenAPI\n      - url: openapi/openai-audio-openapi.yml\n        type: OpenAPI\n      - url: json-ld/openai-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Audio API provides two speech to text endpoints, transcriptions and translations,\n      based on our state-of-the-art open source large-v2 Whisper model.\n  - aid: openai:openai-chat-api\n    name: OpenAI Chat API\n    tags:\n      - Chat\n    score: 149\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/chat\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/chat\n        type: Documentation\n      - url: openapi/chat-openapi-original.yml\n        type: OpenAPI\n      - url: openapi/openai-chat-completions-openapi.yml\n        type: OpenAPI\n      - url: json-schema/openai-chat-completion-schema.json\n        type: JSONSchema\n      - url: json-ld/openai-context.jsonld\n        type: JSONLD\n    description: >-\n      Given a list of messages comprising a conversation, the model will return a\n      response., providing an AI chat interface you can use to engage\
  \ with users.\n  - aid: openai:openai-chat-completions-api\n    name: OpenAI Chat Completions API\n    tags:\n      - Chat\n      - Completions\n    score: 281\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/chat\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/chat\n        type: Documentation\n      - url: properties/openai-chat-completions-api-openapi.yml\n        type: OpenAPI\n      - url: openapi/openai-chat-completions-openapi.yml\n        type: OpenAPI\n      - url: json-schema/openai-chat-completion-schema.json\n        type: JSONSchema\n      - url: json-ld/openai-context.jsonld\n        type: JSONLD\n    description: >-\n      Chat models take a list of messages as input and return a model-generated message\n      as output. Although the chat format is designed to make multi-turn conversations\n      easy, it's just as useful for single-turn tasks without any conversation.\n  - aid: openai:openai-embeddings-api\n\
  \    name: OpenAI Embeddings API\n    tags:\n      - Embedding\n      - Embeddings\n      - Inputs\n      - Representing\n      - Text\n      - Vectors\n    score: 112\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/guides/embeddings\n    properties:\n      - url: https://platform.openai.com/docs/guides/embeddings\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/embeddings\n        type: Documentation\n      - url: openapi/embeddings-openapi-original.yml\n        type: OpenAPI\n      - url: openapi/openai-embeddings-openapi.yml\n        type: OpenAPI\n      - url: json-schema/openai-embedding-schema.json\n        type: JSONSchema\n      - url: json-ld/openai-context.jsonld\n        type: JSONLD\n    description: >-\n      Learn how to turn text into numbers, unlocking use cases like search. OpenAI's\n      text embeddings measure the relatedness of text strings.\n  - aid: openai:openai-files-api\n    name: OpenAI\
  \ Files API\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Files\n    score: 894\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/files\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/files\n        type: Documentation\n      - url: openapi/files-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      Files are used to upload documents that can be used with features like Assistants\n      and Fine-tuning. Upload a file that can be used across various endpoints. The\n      size of all the files uploaded by one organization can be up to 100 GB.\n  - aid: openai:openai-fine-tuning-api\n    name: OpenAI Fine Tuning API\n    tags:\n      - Fine Tune\n      - Fine Tuning\n    score: 492\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/guides/fine-tuning\n    properties:\n      - url: https://platform.openai.com/docs/guides/fine-tuning\n       \
  \ type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/fine-tuning\n        type: Documentation\n      - url: openapi/fine-tuning-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      Manage fine-tuning jobs to tailor a model to your specific training data. Creates\n      a fine-tuning job which begins the process of creating a new model from a given\n      dataset.Response includes details of the enqueued job including job status and\n      the name of the fine-tuned models once complete.\n  - aid: openai:openai-images-api\n    name: OpenAI Images API\n    tags:\n      - Images\n    score: 120\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/guides/images\n    properties:\n      - url: https://platform.openai.com/docs/guides/images\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/images\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/image-generation\n\
  \        type: Documentation\n      - url: https://platform.openai.com/docs/guides/images-vision\n        type: Documentation\n      - url: openapi/images-openapi-original.yml\n        type: OpenAPI\n      - url: openapi/openai-images-openapi.yml\n        type: OpenAPI\n      - url: json-ld/openai-context.jsonld\n        type: JSONLD\n    description: >-\n      Learn how to generate or manipulate images with DALL_E in the API. The Images\n      API provides three methods for interacting with images - creating images from\n      scratch based on a text prompt, creating edited versions of images by having\n      the model replace some areas of a pre-existing image, based on a new text prompt,\n      Creating variations of an existing image.\n  - aid: openai:openai-models-api\n    name: OpenAI Models API\n    tags:\n      - Large Language Models\n      - Models\n    score: 201\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/models\n    properties:\n  \
  \    - url: https://platform.openai.com/docs/models\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/models\n        type: Documentation\n      - url: openapi/models-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      List and describe the various models available in the API. You can refer to\n      the Models documentation to understand what models are available and the differences\n      between them.\n  - aid: openai:openai-threads-api\n    name: OpenAI Threads API\n    tags:\n      - Assistants\n      - Threads\n    score: 1861\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/assistants/how-it-works/managing-threads-and-messages\n    properties:\n      - url: https://platform.openai.com/docs/assistants/how-it-works/managing-threads-and-messages\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/threads\n        type: Documentation\n      - url: openapi/threads-openapi-original.yml\n\
  \        type: OpenAPI\n    description: Create threads that assistants can interact with.\n  - aid: openai:openai-responses-api\n    name: OpenAI Responses API\n    tags:\n      - Agents\n      - Responses\n      - Text Generation\n    score: 150\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/responses\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/responses\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/text\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/deep-research/\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/conversation-state/\n        type: Documentation\n    description: >-\n      The Responses API is OpenAI's most advanced interface for generating model\n      responses. It combines the strengths of the Chat Completions and Assistants\n      APIs into a single streamlined interface,\
  \ supporting text and image inputs,\n      text outputs, and built-in tools like web search, file search, computer use,\n      and code interpreter. Recommended for all new projects.\n  - aid: openai:openai-moderations-api\n    name: OpenAI Moderations API\n    tags:\n      - Content Safety\n      - Moderation\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/moderations\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/moderations\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/moderation\n        type: Documentation\n    description: >-\n      The Moderations API can be used to check whether text or images are\n      potentially harmful. It classifies content across several categories\n      including harassment, hate speech, sexual content, self-harm, violence,\n      and illicit content. The moderation endpoint is free to use and supports\n      the omni-moderation-latest\
  \ model for multi-modal inputs.\n  - aid: openai:openai-batch-api\n    name: OpenAI Batch API\n    tags:\n      - Async\n      - Batch\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/batch\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/batch\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/batch\n        type: Documentation\n    description: >-\n      The Batch API enables asynchronous processing of requests with 50% cost\n      discount, higher rate limits, and completion within 24 hours. It supports\n      /v1/responses, /v1/chat/completions, /v1/embeddings, /v1/completions,\n      and /v1/moderations endpoints. A single batch may include up to 50,000\n      requests with a batch input file size up to 200 MB.\n  - aid: openai:openai-vector-stores-api\n    name: OpenAI Vector Stores API\n    tags:\n      - Retrieval\n      - Search\n      - Vector Stores\n\
  \    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/vector-stores\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/vector-stores\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/retrieval\n        type: Documentation\n    description: >-\n      Vector stores are collections of processed files that power semantic search\n      for the file_search tool in the Responses and Assistants APIs. When you add\n      a file to a vector store it is automatically chunked, embedded, and indexed.\n      You can query a vector store using natural language to retrieve relevant\n      chunks with similarity scores.\n  - aid: openai:openai-uploads-api\n    name: OpenAI Uploads API\n    tags:\n      - Files\n      - Uploads\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/uploads\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/uploads\n\
  \        type: Documentation\n    description: >-\n      The Uploads API creates an intermediate Upload object that you can add\n      Parts to, enabling large file uploads. Currently an Upload can accept\n      at most 8 GB in total and expires after an hour. Once you complete the\n      Upload, a File object is created that can be used across the platform.\n  - aid: openai:openai-realtime-api\n    name: OpenAI Realtime API\n    tags:\n      - Audio\n      - Realtime\n      - Streaming\n      - Voice\n    score: 150\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/realtime\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/realtime\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/realtime\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/realtime-webrtc\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/realtime-server-controls\n\
  \        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/realtime-conversations/\n        type: Documentation\n    description: >-\n      The Realtime API enables low-latency, bidirectional communication with\n      models that natively support speech-to-speech interactions as well as\n      multimodal inputs (audio, images, and text) and outputs (audio and text).\n      It supports WebRTC, WebSocket, and SIP connection methods for real-time\n      voice agents and conversational interfaces.\n  - aid: openai:openai-evals-api\n    name: OpenAI Evals API\n    tags:\n      - Evals\n      - Evaluation\n      - Testing\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/evals\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/evals\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/evals\n        type: Documentation\n    description: >-\n\
  \      The Evals API allows you to programmatically configure and run evaluations\n      to test model outputs against your expectations. Evaluations ensure model\n      responses meet style and content criteria you specify, and are essential\n      for building reliable LLM applications, especially when upgrading or\n      trying new models.\n  - aid: openai:openai-completions-api\n    name: OpenAI Completions API\n    tags:\n      - Completions\n      - Legacy\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/completions\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/completions\n        type: Documentation\n      - url: openapi/completions-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The legacy Completions API endpoint provides a freeform text completion\n      interface using a text prompt. Unlike the Chat Completions endpoint which\n      uses a list of messages,\
  \ the Completions API input is a freeform text\n      string called a prompt. This endpoint received its last update in July\n      2023.\n  - aid: openai:openai-videos-api\n    name: OpenAI Videos API\n    tags:\n      - Sora\n      - Video Generation\n      - Videos\n    score: 150\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/videos\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/videos\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/video-generation\n        type: Documentation\n    description: >-\n      The Videos API enables programmatic creation, extension, and remixing of\n      videos using Sora models. It provides endpoints for creating a new render\n      job from a text prompt, checking video status, downloading finished MP4\n      files, listing videos with pagination, and deleting videos from storage.\n      Supported models include sora-2 and sora-2-pro.\n\
  \  - aid: openai:openai-conversations-api\n    name: OpenAI Conversations API\n    tags:\n      - Conversations\n      - State Management\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/conversations/create\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/conversations/create\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/conversation-state/\n        type: Documentation\n    description: >-\n      The Conversations API allows you to create and manage stateful\n      conversations for use with the Responses API. A conversation object\n      contains an id, a created_at timestamp, and metadata. Because\n      conversations are stateful, managing context across conversations is\n      handled automatically, and the /responses/compact endpoint can shrink\n      context for long-running conversations.\n  - aid: openai:openai-containers-api\n    name: OpenAI\
  \ Containers API\n    tags:\n      - Code Interpreter\n      - Containers\n      - Sandbox\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/containers\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/containers\n        type: Documentation\n      - url: https://platform.openai.com/docs/api-reference/container-files\n        type: Documentation\n      - url: https://developers.openai.com/api/docs/guides/tools-code-interpreter/\n        type: Documentation\n    description: >-\n      The Containers API manages sandboxed containers used by Code Interpreter\n      for running Python, data work, file transforms, and iterative debugging.\n      Containers can be created explicitly or auto-managed, with configurable\n      memory limits of 1g, 4g, 16g, or 64g. Container files can be uploaded,\n      listed, retrieved, and downloaded. Containers expire after 20 minutes of\n      inactivity.\n  - aid:\
  \ openai:openai-chatkit-api\n    name: OpenAI ChatKit API\n    tags:\n      - Agents\n      - Chat\n      - ChatKit\n    score: 100\n    baseURL: https://api.openai.com\n    humanURL: https://platform.openai.com/docs/api-reference/chatkit\n    properties:\n      - url: https://platform.openai.com/docs/api-reference/chatkit\n        type: Documentation\n      - url: https://platform.openai.com/docs/guides/chatkit\n        type: Documentation\n    description: >-\n      ChatKit is the best way to build agentic chat experiences. It provides\n      session and thread management for building internal knowledge base\n      assistants, research companions, support agents, and more. ChatKit\n      sessions include resolved feature configuration for automatic thread\n      titling, file upload, and history settings. Threads have statuses\n      including active, locked, and closed.\nname: OpenAI\ntags:\n  - AI\n  - Artificial Intelligence\n  - Large Language Models\n  - T1\ntype: Contract\nscore:\
  \ 308\naccess: 3rd-Party\ncommon:\n  - url: https://platform.openai.com/docs/overview\n    name: Overview - OpenAI API\n    type: Portal\n    description: 'null'\n  - url: https://platform.openai.com/docs/quickstart\n    name: Developer quickstart - OpenAI API\n    type: GettingStarted\n    description: 'null'\n  - url: https://platform.openai.com/docs/libraries\n    name: Libraries - OpenAI API\n    type: SDKs\n    description: 'null'\n  - url: https://community.openai.com/categories\n    name: Categories - OpenAI Developer Community\n    type: Forums\n    description: 'null'\n  - url: https://platform.openai.com/docs/guides/rate-limits\n    name: Rate limits - OpenAI API\n    type: RateLimits\n    description: 'null'\n  - url: https://platform.openai.com/docs/deprecations\n    name: Deprecations - OpenAI API\n    type: Deprecations\n    description: 'null'\n  - url: https://openai.com/policies/\n    name: Terms & policies | OpenAI\n    type: TermsOfService\n    description: 'null'\n\
  \  - url: https://openai.com/policies/terms-of-use/\n    name: Terms of use | OpenAI\n    type: TermsOfService\n    description: 'null'\n  - url: https://openai.com/policies/privacy-policy/\n    name: Privacy policy | OpenAI\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://platform.openai.com/docs/overview\n    name: Overview - OpenAI API\n    type: Documentation\n    description: 'null'\n  - url: https://help.openai.com/en\n    name: OpenAI Help Center\n    type: Support\n    description: 'null'\n  - url: https://status.openai.com/\n    name: OpenAI Status\n    type: Status\n    description: 'null'\n  - url: https://platform.openai.com/docs/api-reference/authentication\n    name: API Reference - OpenAI API\n    type: Authentication\n    description: 'null'\n  - url: https://platform.openai.com/docs/api-reference/webhook_events/response\n    name: API Reference - OpenAI API\n    type: Webhooks\n    description: 'null'\n  - url: properties/openai-openapi\n    name: OpenAPI\n\
  \    type: OpenAPI\n  - url: json-schema/openai-chat-completion-schema.json\n    name: Chat Completion JSON Schema\n    type: JSONSchema\n    description: 'null'\n  - url: json-schema/openai-embedding-schema.json\n    name: Embedding JSON Schema\n    type: JSONSchema\n    description: 'null'\n  - url: json-ld/openai-context.jsonld\n    name: OpenAI JSON-LD Context\n    type: JSONLD\n    description: 'null'\n  - url: https://github.com/openai\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://openai.com/api/pricing/\n    data:\n      - id: free\n        name: Free\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: 0\n            metric: user\n            timeFrame: month\n            description: User based pricing.\n        elements:\n          - name: Access to GPT5\n          - name: Real-time data from the web with search\n          - name: Limited access to file uploads, data analysis,\
  \ image generation, and voice mode\n          - name: Code edits with the ChatGPT desktop app for macOS\n          - name: Use custom GPTs\n        description: Explore how AI can help with everyday tasks\n      - id: plus\n        name: Plus\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: $20.00\n            metric: user\n            timeFrame: month\n            description: User based pricing.\n        elements:\n          - name: Extended access to GPT5, our flagship model\n          - name: Extended limits on messaging, file uploads, data analysis, and image generation\n          - name: Standard and advanced voice mode with video and screensharing\n          - name: Access to ChatGPT agent\n          - name: Create and use projects, tasks, and custom GPTs\n          - name: Limited access to Sora video generation\n          - name: Opportunities to test new features\n        description: Level up productivity\
  \ and creativity with expanded access\n      - id: pro\n        name: Pro\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: $200.00\n            metric: user\n            timeFrame: month\n            description: User based pricing.\n        elements:\n          - name: Unlimited access to GPT5\n          - name: Access to GPT5 pro, which uses more compute for the best answers to the hardest questions\n          - name: Unlimited access to advanced voice, with higher limits for video and screensharing\n          - name: Access to OpenAI o3pro, which uses more compute for the best answers to the hardest questions\n          - name: Extended access to ChatGPT agent\n          - name: Extended access to Sora video generation\n          - name: Access to research preview of Codex agent\n        description: Get the best of OpenAI with the highest level of access\n      - id: team\n        name: Team\n        entries:\n\
  \          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: $25.00\n            metric: user\n            timeFrame: month\n            description: User based pricing.\n        elements:\n          - name: Unlimited GPT5 messages, with generous access to GPT5 thinking, and access to GPT5 proplus the flexibility to add credits as needed\n          - name: A secure, dedicated workspace with essential admin controls, SAML SSO, and MFA\n          - name: Team data is excluded from training by default, with encryption at rest and in transit. Learn more`\n          - name: Support for compliance with GDPR, CCPA, and other privacy laws. Aligned with CSA STAR` and SOC 2 Type 2 Trust Services Criteria.\n          - name: Connectors to apps for more personalized answersGoogle Drive, SharePoint, GitHub, Notion, and more\n          - name: Business features like data analysis, record mode, canvas, projects, tasks, custom workspace GPTs, and deep research\n\
  \          - name: Includes access to Codex and ChatGPT agent for reasoning and taking action across your documents, tools, and codebases\n        description: A secure, collaborative workspace for startups and growing teams\n      - id: enterprise\n        name: Enterprise\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: Contact\n            metric: user\n            timeFrame: month\n            description: User based pricing.\n        elements:\n          - name: Expanded context window that supports longer inputs and larger files\n          - name: Enterprise-level security and controls, including SCIM, user analytics, domain verification, and role-based access controls\n          - name: Advanced data privacy with custom data retention policies, encryption at rest and in transit, and no training on your business data by default. Learn more`\n          - name: Support for data residency in seven regions\n\
  \          - name: 24/7 priority support, SLAs, custom legal terms, and access to AI advisors for eligible customers\n          - name: Built for scale with volume discounts, invoicing and ACH billing, and support for unlimited users\n        description: Enterprise-grade AI, security, and support at scale\n    name: Plans\n    type: Plans\n    description: This is the description of the plans for general OpenAI usage.\n  - url: https://openai.com/api/pricing/\n    data:\n      - id: gpt-5\n        name: GPT-5\n        type: Flagship\n        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 1.25\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.125\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n     \
  \     - geo: US\n            unit: 1M\n            label: Output\n            price: 10\n            metric: token\n            timeFrame: usage\n            description: Output token usage-based pricing.\n        description: The best model for coding and agentic tasks across industries.\n      - id: gpt-5-mini\n        name: GPT-5 mini\n        type: Flagship\n        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 0.25\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.025\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Output\n            price: 2\n            metric: token\n            timeFrame: usage\n            description: Output token\
  \ usage-based pricing.\n        description: A faster, cheaper version of GPT-5 for well-defined tasks.\n      - id: gpt-5-nano\n        name: GPT-5 nano\n        type: Flagship\n        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 0.05\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.005\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Output\n            price: 0.4\n            metric: token\n            timeFrame: usage\n            description: Output token usage-based pricing.\n        description: The fastest, cheapest version of GPT-5great for summarization and classification tasks.\n      - id: gpt-4-1\n        name: GPT-4.1\n  \
  \      type: Fine-Tuning\n        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 3\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.75\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Output\n            price: 12\n            metric: token\n            timeFrame: usage\n            description: Output token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Training\n            price: 25\n            metric: token\n            timeFrame: usage\n            description: Training token usage-based pricing.\n        description: No description.\n      - id: gpt-4-1-mini\n        name: GPT-4.1 mini\n        type:\
  \ Fine-Tuning\n        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 0.8\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.2\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Output\n            price: 3.2\n            metric: token\n            timeFrame: usage\n            description: Output token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Training\n            price: 5\n            metric: token\n            timeFrame: usage\n            description: Training token usage-based pricing.\n        description: No description.\n      - id: gpt-4-1-nano\n        name: GPT-4.1 nano\n        type: Fine-Tuning\n\
  \        entries:\n          - geo: US\n            unit: 1M\n            label: Input\n            price: 0.2\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 0.05\n            metric: token\n            timeFrame: usage\n            description: Cached input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Output\n            price: 0.8\n            metric: token\n            timeFrame: usage\n            description: Output token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Training\n            price: 1.5\n            metric: token\n            timeFrame: usage\n            description: Training token usage-based pricing.\n        description: No description.\n      - id: o4-mini\n        name: o4-mini\n        type: Fine-Tuning\n        entries:\n\
  \          - geo: US\n            unit: 1M\n            label: Input\n            price: 4\n            metric: token\n            timeFrame: usage\n            description: Input token usage-based pricing.\n          - geo: US\n            unit: 1M\n            label: Cached Input\n            price: 1\n            metric: token\n            timeFrame: usage\n            description: Cached input token usa\n\n# --- truncated at 32 KB (47 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/apis.yml
tags:
- AI
- Artificial Intelligence
- Large Language Models
- T1
url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/apis.yml
use_cases:
- description: Build chatbots, virtual assistants, and customer support agents using Chat Completions or Responses API.
  name: Conversational AI
- description: Generate marketing copy, articles, product descriptions, and creative writing with controllable tone and style.
  name: Content Generation
- description: Automate code writing, debugging, refactoring, and documentation generation across programming languages.
  name: Code Generation
- description: Extract, summarize, and answer questions from uploaded documents using Assistants with file search.
  name: Document Analysis
- description: Build real-time voice-based AI agents for customer service, sales, and interactive experiences.
  name: Voice Agents
- description: Implement intelligent search using embeddings and vector stores for knowledge bases and document retrieval.
  name: Semantic Search
- description: Automatically classify and filter harmful content across text and images using the Moderations API.
  name: Content Moderation
- description: Extract structured data from unstructured text using function calling and structured outputs.
  name: Data Extraction
---
