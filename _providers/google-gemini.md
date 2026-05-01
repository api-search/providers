---
api_count: 14
api_specs:
- filename: google-gemini-api-openapi.yml
  format: yaml
  label: Gemini API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-gemini/refs/heads/main/openapi/google-gemini-api-openapi.yml
apis:
- description: Generate content using Google's Gemini models with text, image, audio, and video inputs.
  name: Gemini API
  slug: ''
- description: Advanced reasoning and complex task handling.
  name: Gemini Pro API
  slug: ''
- description: Multimodal understanding of text and images.
  name: Gemini Pro Vision API
  slug: ''
- description: Most capable model for highly complex tasks.
  name: Gemini Ultra API
  slug: ''
- description: Generate text embedding vectors for semantic search, classification, clustering, and retrieval tasks using the gemini-embedding-001 model.
  name: Gemini Embedding API
  slug: ''
- description: Low-latency real-time voice and video interactions with Gemini using WebSockets for streaming multimodal input and output.
  name: Gemini Live API
  slug: ''
- description: Cache input tokens for repeated use across multiple requests to reduce costs and improve latency for large context workloads.
  name: Gemini Context Caching API
  slug: ''
- description: Customize Gemini model behavior for specific tasks using supervised fine-tuning with your own training data.
  name: Gemini Fine-Tuning API
  slug: ''
- description: Unified interface for interacting with Gemini models and agents providing a consistent way to manage multi-turn conversations and tool use.
  name: Gemini Interactions API
  slug: ''
- description: Enterprise-grade access to Gemini models through Google Cloud Vertex AI with advanced features including grounding, safety filters, and regional endpoints.
  name: Vertex AI Gemini API
  slug: ''
- description: Generate and edit images using Google Imagen models on Vertex AI for high-quality image creation from text prompts.
  name: Vertex AI Imagen API
  slug: ''
- description: Enterprise real-time multimodal streaming API on Vertex AI for building low-latency voice and video AI agents.
  name: Vertex AI Gemini Live API
  slug: ''
- description: Generate text embeddings for semantic search and classification tasks using Google embedding models on Vertex AI.
  name: Vertex AI Text Embeddings API
  slug: ''
- description: Access Gemini API capabilities through Firebase SDKs for mobile and web applications with built-in security and authentication.
  name: Firebase AI Logic API
  slug: ''
common:
- title: ''
  type: Terms of Service
  url: https://ai.google.dev/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Status Page
  url: https://status.cloud.google.com/
- title: ''
  type: Support
  url: https://ai.google.dev/docs/support
- title: ''
  type: Blog
  url: https://developers.googleblog.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/google-gemini
- title: ''
  type: Discord
  url: https://discord.gg/google-dev
- title: ''
  type: Forum
  url: https://discuss.ai.google.dev/
- title: ''
  type: Cookbook
  url: https://github.com/google-gemini/cookbook
- title: ''
  type: Google AI Studio
  url: https://aistudio.google.com/
- title: ''
  type: Safety Guidance
  url: https://ai.google.dev/gemini-api/docs/safety-guidance
- title: ''
  type: Vertex AI Studio
  url: https://cloud.google.com/generative-ai-studio
- title: ''
  type: Google Cloud Documentation
  url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs
created: '2024-01-01'
description: Google's multimodal AI model APIs for text, image, audio, and video understanding.
features: []
image: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg
integrations: []
jsonld:
- class_count: 0
  name: Google Gemini Context
  property_count: 23
  slug: google-gemini-context
layout: provider
modified: '2026-04-28'
name: Google Gemini
skills: []
slug: google-gemini
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-gemini\nname: Google Gemini\ndescription: >-\n  Google's multimodal AI model APIs for text, image, audio, and video understanding.\nimage: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg\nurl: https://ai.google.dev/\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Agentic AI\n  - Artificial Intelligence\n  - Code Generation\n  - Embeddings\n  - Generative AI\n  - Image Generation\n  - LLM\n  - Machine Learning\n  - Multimodal\napis:\n  - name: Gemini API\n    description: >-\n      Generate content using Google's Gemini models with text, image, audio, and video\n      inputs.\n    image: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg\n    humanURL: https://ai.google.dev/\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Audio Understanding\n      - Chat\n      - Image Understanding\n      - Multimodal\n      - Structured\
  \ Output\n      - Text Generation\n      - Video Understanding\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/docs\n      - type: OpenAPI\n        url: openapi/google-gemini-api-openapi.yml\n      - type: OpenAPI\n        url: https://generativelanguage.googleapis.com/$discovery/rest?version=v1beta\n      - type: JSON Schema\n        url: json-schema/google-gemini-generate-content-schema.json\n      - type: JSON-LD Context\n        url: json-ld/google-gemini-context.jsonld\n      - type: Getting Started\n        url: https://ai.google.dev/tutorials/get_started_web\n      - type: API Keys\n        url: https://aistudio.google.com/app/apikey\n      - type: Pricing\n        url: https://ai.google.dev/pricing\n      - type: Rate Limits\n        url: https://ai.google.dev/docs/rate_limits\n      - type: Models\n        url: https://ai.google.dev/models\n      - type: API Reference\n        url: https://ai.google.dev/api\n      - type: Quickstart\n        url:\
  \ https://ai.google.dev/gemini-api/docs/quickstart\n      - type: Change Log\n        url: https://ai.google.dev/gemini-api/docs/changelog\n      - type: SDKs\n        url: https://ai.google.dev/gemini-api/docs/libraries\n      - type: OpenAI Compatibility\n        url: https://ai.google.dev/gemini-api/docs/openai\n      - type: Safety Settings\n        url: https://ai.google.dev/gemini-api/docs/safety-settings\n      - type: Structured Output\n        url: https://ai.google.dev/gemini-api/docs/structured-output\n      - type: Token Counting\n        url: https://ai.google.dev/gemini-api/docs/tokens\n  - name: Gemini Pro API\n    description: >-\n      Advanced reasoning and complex task handling.\n    baseURL: https://generativelanguage.googleapis.com/v1beta/models/gemini-pro\n    tags:\n      - Reasoning\n      - Text Generation\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/models/gemini\n  - name: Gemini Pro Vision API\n    description: >-\n     \
  \ Multimodal understanding of text and images.\n    baseURL: https://generativelanguage.googleapis.com/v1beta/models/gemini-pro-vision\n    tags:\n      - Image Understanding\n      - Multimodal\n      - Vision\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/tutorials/prompting_with_media\n  - name: Gemini Ultra API\n    description: >-\n      Most capable model for highly complex tasks.\n    baseURL: https://generativelanguage.googleapis.com/v1beta/models/gemini-ultra\n    tags:\n      - Advanced AI\n      - Complex Tasks\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/models/gemini\n  - name: Gemini Embedding API\n    description: >-\n      Generate text embedding vectors for semantic search, classification, clustering,\n      and retrieval tasks using the gemini-embedding-001 model.\n    humanURL: https://ai.google.dev/gemini-api/docs/embeddings\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n  \
  \    - Embeddings\n      - Retrieval\n      - Semantic Search\n      - Text Similarity\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/embeddings\n  - name: Gemini Live API\n    description: >-\n      Low-latency real-time voice and video interactions with Gemini using WebSockets\n      for streaming multimodal input and output.\n    humanURL: https://ai.google.dev/gemini-api/docs/live\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Multimodal\n      - Real-Time\n      - Streaming\n      - Video\n      - Voice\n      - WebSockets\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/live\n  - name: Gemini Context Caching API\n    description: >-\n      Cache input tokens for repeated use across multiple requests to reduce costs\n      and improve latency for large context workloads.\n    humanURL: https://ai.google.dev/gemini-api/docs/caching\n    baseURL: https://generativelanguage.googleapis.com\n\
  \    tags:\n      - Caching\n      - Cost Optimization\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/caching\n      - type: API Reference\n        url: https://ai.google.dev/api/caching\n  - name: Gemini Fine-Tuning API\n    description: >-\n      Customize Gemini model behavior for specific tasks using supervised fine-tuning\n      with your own training data.\n    humanURL: https://ai.google.dev/gemini-api/docs/model-tuning\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Fine-Tuning\n      - Model Customization\n      - Supervised Learning\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/model-tuning\n      - type: API Reference\n        url: https://ai.google.dev/api/tuning\n  - name: Gemini Interactions API\n    description: >-\n      Unified interface for interacting with Gemini models and agents providing a\n      consistent way to\
  \ manage multi-turn conversations and tool use.\n    humanURL: https://ai.google.dev/gemini-api/docs/interactions\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Agents\n      - Interactions\n      - Multi-Turn\n      - Tool Use\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/interactions\n  - name: Vertex AI Gemini API\n    description: >-\n      Enterprise-grade access to Gemini models through Google Cloud Vertex AI with\n      advanced features including grounding, safety filters, and regional endpoints.\n    humanURL: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-reference/inference\n    baseURL: https://aiplatform.googleapis.com\n    tags:\n      - Enterprise\n      - Generative AI\n      - Google Cloud\n      - Vertex AI\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-reference/inference\n      - type: API Reference\n\
  \        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/reference/rest\n      - type: Quickstart\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/start/quickstart\n      - type: OpenAI Compatibility\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/start/openai\n      - type: Models\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models\n      - type: Release Notes\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/release-notes\n      - type: Pricing\n        url: https://cloud.google.com/vertex-ai/pricing\n  - name: Vertex AI Imagen API\n    description: >-\n      Generate and edit images using Google Imagen models on Vertex AI for high-quality\n      image creation from text prompts.\n    humanURL: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/image/overview\n    baseURL: https://aiplatform.googleapis.com\n    tags:\n      - Google Cloud\n      - Image Generation\n\
  \      - Imagen\n      - Text-To-Image\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/image/overview\n      - type: API Reference\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-reference/imagen-api\n  - name: Vertex AI Gemini Live API\n    description: >-\n      Enterprise real-time multimodal streaming API on Vertex AI for building low-latency\n      voice and video AI agents.\n    humanURL: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/live-api\n    baseURL: https://aiplatform.googleapis.com\n    tags:\n      - Enterprise\n      - Real-Time\n      - Streaming\n      - Vertex AI\n      - Video\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/live-api\n      - type: API Reference\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-reference/multimodal-live\n  -\
  \ name: Vertex AI Text Embeddings API\n    description: >-\n      Generate text embeddings for semantic search and classification tasks using\n      Google embedding models on Vertex AI.\n    humanURL: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/embeddings/get-text-embeddings\n    baseURL: https://aiplatform.googleapis.com\n    tags:\n      - Embeddings\n      - Semantic Search\n      - Text Similarity\n      - Vertex AI\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/embeddings/get-text-embeddings\n      - type: API Reference\n        url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-reference/text-embeddings-api\n  - name: Firebase AI Logic API\n    description: >-\n      Access Gemini API capabilities through Firebase SDKs for mobile and web applications\n      with built-in security and authentication.\n    humanURL: https://firebase.google.com/docs/ai-logic\n    baseURL: https://firebaseml.googleapis.com\n\
  \    tags:\n      - Client-Side\n      - Firebase\n      - Mobile\n      - Web\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/ai-logic\n      - type: Getting Started\n        url: https://firebase.google.com/docs/ai-logic/get-started\n      - type: Models\n        url: https://firebase.google.com/docs/ai-logic/models\ncommon:\n  - type: Terms of Service\n    url: https://ai.google.dev/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Status Page\n    url: https://status.cloud.google.com/\n  - type: Support\n    url: https://ai.google.dev/docs/support\n  - type: Blog\n    url: https://developers.googleblog.com/\n  - type: GitHub Organization\n    url: https://github.com/google-gemini\n  - type: Discord\n    url: https://discord.gg/google-dev\n  - type: Forum\n    url: https://discuss.ai.google.dev/\n  - type: Cookbook\n    url: https://github.com/google-gemini/cookbook\n  - type: Google AI Studio\n    url:\
  \ https://aistudio.google.com/\n  - type: Safety Guidance\n    url: https://ai.google.dev/gemini-api/docs/safety-guidance\n  - type: Vertex AI Studio\n    url: https://cloud.google.com/generative-ai-studio\n  - type: Google Cloud Documentation\n    url: https://docs.cloud.google.com/vertex-ai/generative-ai/docs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-gemini/refs/heads/main/apis.yml
tags:
- Agentic AI
- Artificial Intelligence
- Code Generation
- Embeddings
- Generative AI
- Image Generation
- LLM
- Machine Learning
- Multimodal
url: https://ai.google.dev/
use_cases: []
---
