---
api_count: 1
api_specs:
- filename: aimlapi-openapi.yml
  format: yaml
  label: AIMLAPI
  slug: aimlapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/openapi/aimlapi-openapi.yml
apis:
- description: Access 400+ AI models from 40+ providers via a single OpenAI-compatible REST API. Supports chat completions, image generation, video generation, speech models, embeddings, music generation, and vision
  name: AIMLAPI
  slug: aimlapi
capabilities:
- description: Unified workflow for accessing 400+ AI models via AIMLAPI gateway including chat completions, image generation, embeddings, and model discovery. Used by developers building AI-powered applications.
  name: AIMLAPI AI Model Operations
  slug: ai-model-operations
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/aimlapi
- title: ''
  type: Blog
  url: https://aimlapi.com/blog
- title: ''
  type: Pricing
  url: https://aimlapi.com/ai-ml-api-pricing
- title: ''
  type: Documentation
  url: https://docs.aimlapi.com/
- title: ''
  type: FAQ
  url: https://docs.aimlapi.com/faq/can-i-use-api-in-python
- title: ''
  type: ChangeLog
  url: https://aimlapi.com/changelog
- title: ''
  type: SignUp
  url: https://aimlapi.com/app/sign-up/
- title: ''
  type: Affiliate
  url: https://aimlapi.com/affiliate
- title: ''
  type: PrivacyPolicy
  url: https://aimlapi.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://aimlapi.com/terms-and-conditions
- title: ''
  type: SpectralRules
  url: rules/aimlapi-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/ai-model-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/aimlapi-vocabulary.yaml
created: '2025-01-07'
description: AIMLAPI is a unified AI model API gateway providing access to 400+ state-of-the-art AI models from OpenAI, Anthropic, Google, Meta, DeepSeek, Mistral, Stability AI, and 40+ other providers through a single OpenAI-compatible API. Supported modalities include text/chat LLMs, image generation, video generation, music generation, speech-to-text, text-to-speech, vision/OCR, embeddings, and 3D generation.
features:
- description: Access to 400+ models from OpenAI, Anthropic, Google, Meta, DeepSeek, Mistral, Stability AI, and 40+ providers.
  name: 400+ AI Models
- description: Drop-in replacement for OpenAI API — use existing OpenAI client libraries with AIMLAPI endpoint.
  name: OpenAI-Compatible API
- description: Chat completions, completion, function calling, streaming, reasoning, and code generation.
  name: Text and Chat Completions
- description: Generate images via DALL-E, Flux, Stable Diffusion, and other image generation models.
  name: Image Generation
- description: Generate video via Sora 2, Runway, and other video generation models.
  name: Video Generation
- description: Text-to-speech and speech-to-text transcription via Whisper and other speech models.
  name: Speech Models
- description: AI music generation via dedicated music models.
  name: Music Generation
- description: Image understanding, visual question answering, and OCR via vision-capable LLMs.
  name: Vision and OCR
- description: Generate vector embeddings for semantic search and RAG applications.
  name: Embeddings
- description: Online playground for experimenting with all available models without writing code.
  name: Playground
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use the official OpenAI Python and Node.js SDKs with AIMLAPI base URL.
  name: OpenAI SDK
- description: Integrate AIMLAPI models with LangChain for agentic AI workflows.
  name: LangChain
- description: Use AIMLAPI with LlamaIndex for RAG and document intelligence pipelines.
  name: LlamaIndex
- description: Build AI-powered web apps using Vercel AI SDK with AIMLAPI as backend.
  name: Vercel AI SDK
- description: Native Python integration via requests library or OpenAI client.
  name: Python
- description: Node.js integration via OpenAI npm package pointed at AIMLAPI endpoint.
  name: Node.js
jsonld:
- class_count: 5
  name: Aimlapi Context
  property_count: 10
  slug: aimlapi-context
layout: provider
modified: '2026-04-19'
name: AIMLAPI
rules:
- name: AIMLAPI API Rules
  rule_count: 15
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 8
  slug: aimlapi-spectral-rules
skills: []
slug: aimlapi
solutions: []
source_filename: apis.yml
source_yaml: "aid: aimlapi\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/apis.yml\napis:\n- aid: aimlapi:aimlapi\n  name: AIMLAPI\n  tags:\n  - LLM\n  - Chat Completions\n  - Image Generation\n  - Video Generation\n  - Speech\n  - Embeddings\n  - Vision\n  - Music\n  - OpenAI Compatible\n  - API Gateway\n  humanURL: 'https://aimlapi.com/'\n  properties:\n  - url: https://docs.aimlapi.com/\n    type: Documentation\n  - url: https://docs.aimlapi.com/api-references/text-models\n    type: APIReference\n    title: Text Models API Reference\n  - url: https://docs.aimlapi.com/api-references/image-models\n    type: APIReference\n    title: Image Generation API Reference\n  - url: openapi/aimlapi-openapi.yml\n    type: OpenAPI\n  - url: https://docs.aimlapi.com/quickstart\n    type: Quickstart\n  - url: https://aimlapi.com/app/sign-up/\n    type: SignUp\n  - url: https://docs.aimlapi.com/faq\n    type: FAQ\n  description: >-\n    Access 400+ AI models from 40+\
  \ providers via a single OpenAI-compatible REST API. Supports chat completions, image generation, video generation, speech models, embeddings, music generation, and vision\n    tasks with streaming support and function calling.\nname: AIMLAPI\ntags:\n- Artificial Intelligence\n- Machine Learning\n- AI Models\n- LLM\n- Image Generation\n- Video Generation\n- Speech\n- Embeddings\n- API Gateway\n- Developer Tools\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- url: https://github.com/aimlapi\n  name: GitHub Organization\n  type: GitHubOrganization\n- url: https://aimlapi.com/blog\n  name: Explore AI with AIMLAPI Blog - Insights, Innovations, and Success Stories\n  type: Blog\n  description: 'null'\n- url: https://aimlapi.com/ai-ml-api-pricing\n  name: Pricing\n  type: Pricing\n  description: 'null'\n- url: https://docs.aimlapi.com/\n  name: Introduction | AI/ML API Documentation\n  type: Documentation\n  description:\
  \ 'null'\n- name: Can I use API in Python? | AI/ML API Documentation\n  description: 'null'\n  url: https://docs.aimlapi.com/faq/can-i-use-api-in-python\n  type: FAQ\n- name: 'AI/ML API Changelog: Latest Features and Improvements'\n  description: 'null'\n  url: https://aimlapi.com/changelog\n  type: ChangeLog\n- name: AI/ML API - Sign up\n  description: 'null'\n  url: https://aimlapi.com/app/sign-up/\n  type: SignUp\n- name: 'Join the AI/ML API Affiliate Program: Empower Innovation & Earn Rewards'\n  description: 'null'\n  url: https://aimlapi.com/affiliate\n  type: Affiliate\n- name: Privacy Policy\n  description: 'null'\n  url: https://aimlapi.com/privacy-policy\n  type: PrivacyPolicy\n- name: Terms and Conditions - aimlapi.com - 200+ AI Models via 1 API\n  description: 'null'\n  url: https://aimlapi.com/terms-and-conditions\n  type: TermsOfService\n- type: Features\n  data:\n  - name: 400+ AI Models\n    description: Access to 400+ models from OpenAI, Anthropic, Google, Meta, DeepSeek,\
  \ Mistral, Stability AI, and 40+ providers.\n  - name: OpenAI-Compatible API\n    description: Drop-in replacement for OpenAI API — use existing OpenAI client libraries with AIMLAPI endpoint.\n  - name: Text and Chat Completions\n    description: Chat completions, completion, function calling, streaming, reasoning, and code generation.\n  - name: Image Generation\n    description: Generate images via DALL-E, Flux, Stable Diffusion, and other image generation models.\n  - name: Video Generation\n    description: Generate video via Sora 2, Runway, and other video generation models.\n  - name: Speech Models\n    description: Text-to-speech and speech-to-text transcription via Whisper and other speech models.\n  - name: Music Generation\n    description: AI music generation via dedicated music models.\n  - name: Vision and OCR\n    description: Image understanding, visual question answering, and OCR via vision-capable LLMs.\n  - name: Embeddings\n    description: Generate vector embeddings\
  \ for semantic search and RAG applications.\n  - name: Playground\n    description: Online playground for experimenting with all available models without writing code.\n- type: UseCases\n  data:\n  - name: AI Chatbot Development\n    description: Build conversational AI chatbots and virtual assistants using leading LLMs.\n  - name: Content Generation\n    description: Automate text, image, video, and music content generation for media and marketing.\n  - name: RAG Applications\n    description: Build retrieval-augmented generation applications using embeddings and LLMs.\n  - name: Code Generation\n    description: Integrate AI code generation and review capabilities into developer tools.\n  - name: Document Processing\n    description: Extract information and summarize documents using vision and LLM models.\n  - name: Voice Applications\n    description: Add speech-to-text transcription and text-to-speech synthesis to applications.\n- type: Integrations\n  data:\n  - name: OpenAI SDK\n\
  \    description: Use the official OpenAI Python and Node.js SDKs with AIMLAPI base URL.\n  - name: LangChain\n    description: Integrate AIMLAPI models with LangChain for agentic AI workflows.\n  - name: LlamaIndex\n    description: Use AIMLAPI with LlamaIndex for RAG and document intelligence pipelines.\n  - name: Vercel AI SDK\n    description: Build AI-powered web apps using Vercel AI SDK with AIMLAPI as backend.\n  - name: Python\n    description: Native Python integration via requests library or OpenAI client.\n  - name: Node.js\n    description: Node.js integration via OpenAI npm package pointed at AIMLAPI endpoint.\n- name: AIMLAPI Spectral Rules\n  url: rules/aimlapi-spectral-rules.yml\n  type: SpectralRules\n  description: Spectral ruleset enforcing AIMLAPI API conventions.\n- name: AIMLAPI AI Model Operations\n  url: capabilities/ai-model-operations.yaml\n  type: NaftikoCapability\n  description: Naftiko workflow capability for AI model operations.\n- name: AIMLAPI Vocabulary\n\
  \  url: vocabulary/aimlapi-vocabulary.yaml\n  type: Vocabulary\n  description: Taxonomy vocabulary for AIMLAPI APIs.\ncreated: '2025-01-07'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  AIMLAPI is a unified AI model API gateway providing access to 400+ state-of-the-art AI models from OpenAI, Anthropic, Google, Meta, DeepSeek, Mistral, Stability AI, and 40+ other providers through a single\n  OpenAI-compatible API. Supported modalities include text/chat LLMs, image generation, video generation, music generation, speech-to-text, text-to-speech, vision/OCR, embeddings, and 3D generation.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Machine Learning
- AI Models
- LLM
- Image Generation
- Video Generation
- Speech
- Embeddings
- API Gateway
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/apis.yml
use_cases:
- description: Build conversational AI chatbots and virtual assistants using leading LLMs.
  name: AI Chatbot Development
- description: Automate text, image, video, and music content generation for media and marketing.
  name: Content Generation
- description: Build retrieval-augmented generation applications using embeddings and LLMs.
  name: RAG Applications
- description: Integrate AI code generation and review capabilities into developer tools.
  name: Code Generation
- description: Extract information and summarize documents using vision and LLM models.
  name: Document Processing
- description: Add speech-to-text transcription and text-to-speech synthesis to applications.
  name: Voice Applications
---
