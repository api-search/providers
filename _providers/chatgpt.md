---
api_count: 13
api_specs:
- filename: chatgpt-chat-completions-api-openapi.yml
  format: yaml
  label: ChatGPT API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chatgpt/refs/heads/main/openapi/chatgpt-chat-completions-api-openapi.yml
- filename: chatgpt-responses-api-openapi.yml
  format: yaml
  label: OpenAI Responses API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chatgpt/refs/heads/main/openapi/chatgpt-responses-api-openapi.yml
apis:
- description: API for accessing OpenAI's ChatGPT language models for chat completions and conversations.
  name: ChatGPT API
  slug: ''
- description: The Responses API is OpenAI's recommended API primitive for new projects, an evolution of Chat Completions with built-in tools like web search, file search, code interpreter, and support for agentic w
  name: OpenAI Responses API
  slug: ''
- description: API for generating embedding vectors from input text using models like text-embedding-3-small and text-embedding-3-large, useful for search, clustering, and recommendations.
  name: OpenAI Embeddings API
  slug: ''
- description: API for generating and editing images from text prompts using DALL-E and GPT Image models, supporting image generations, edits, and variations.
  name: OpenAI Images API
  slug: ''
- description: API for audio capabilities including text-to-speech generation, speech transcription, and translation using Whisper and other audio models.
  name: OpenAI Audio API
  slug: ''
- description: API for classifying text and images to detect potentially harmful content across categories like hate, violence, and self-harm.
  name: OpenAI Moderations API
  slug: ''
- description: API for creating and managing fine-tuning jobs to customize OpenAI models on your own training data, supporting supervised fine-tuning and direct preference optimization.
  name: OpenAI Fine-Tuning API
  slug: ''
- description: API for uploading and managing files used across OpenAI features including fine-tuning, assistants, batch processing, and vision.
  name: OpenAI Files API
  slug: ''
- description: API for sending asynchronous groups of requests at lower cost with a separate pool of significantly higher rate limits, supporting chat completions, embeddings, and completions endpoints.
  name: OpenAI Batch API
  slug: ''
- description: API for uploading large files in multiple parts, supporting files up to 8 GB for use with fine-tuning, assistants, and batch processing.
  name: OpenAI Uploads API
  slug: ''
- description: API for creating and managing vector stores used by the file search tool, supporting collections of processed files for retrieval-augmented generation.
  name: OpenAI Vector Stores API
  slug: ''
- description: API for real-time multimodal communication with models over WebRTC, WebSocket, and SIP, supporting speech-to-speech, text, image, and audio inputs and outputs with ultra-low latency.
  name: OpenAI Realtime API
  slug: ''
- description: API for listing and retrieving information about available OpenAI models, including details on permissions and capabilities.
  name: OpenAI Models API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://platform.openai.com
- title: ''
  type: Documentation
  url: https://platform.openai.com/docs/api-reference
- title: ''
  type: GettingStarted
  url: https://platform.openai.com/docs/quickstart
- title: ''
  type: Authentication
  url: https://platform.openai.com/docs/api-reference/authentication
- title: ''
  type: Pricing
  url: https://openai.com/pricing
- title: ''
  type: RateLimits
  url: https://platform.openai.com/docs/guides/rate-limits
- title: ''
  type: ChangeLog
  url: https://platform.openai.com/docs/changelog
- title: ''
  type: Blog
  url: https://openai.com/blog
- title: ''
  type: StatusPage
  url: https://status.openai.com
- title: ''
  type: Support
  url: https://help.openai.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/openai
- title: ''
  type: SDK
  url: https://developers.openai.com/api/docs/libraries/
- title: ''
  type: CodeExamples
  url: https://cookbook.openai.com/
- title: ''
  type: OpenAPI
  url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml
- title: ''
  type: TermsOfService
  url: https://openai.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://openai.com/privacy
- title: ''
  type: Security
  url: https://openai.com/business-data/
- title: ''
  type: Models
  url: https://platform.openai.com/docs/models
- title: ''
  type: SignUp
  url: https://platform.openai.com/signup
- title: ''
  type: Login
  url: https://platform.openai.com/login
created: '2024'
description: OpenAI's ChatGPT API for conversational AI and language model interactions.
features:
- description: Generate conversational responses using GPT models with support for text, function calling, structured outputs, vision inputs, and streaming.
  name: Chat Completions
- description: Next-generation API with built-in tools for web search, file search, computer use, and code interpreter supporting agentic workflows.
  name: Responses API
- description: Generate vector representations of text for search, clustering, classification, and recommendation use cases.
  name: Embeddings
- description: Create and edit images from text prompts using DALL-E and GPT Image models.
  name: Image Generation
- description: Text-to-speech generation, speech transcription, and translation using Whisper and other audio models.
  name: Audio and Speech
- description: Classify text and images to detect potentially harmful content across safety categories.
  name: Content Moderation
- description: Customize OpenAI models on your own training data for domain-specific performance improvements.
  name: Fine-Tuning
- description: Send asynchronous groups of requests at lower cost with higher rate limits.
  name: Batch Processing
- description: Ultra-low latency multimodal communication over WebRTC, WebSocket, and SIP.
  name: Realtime Communication
- description: Manage collections of processed files for retrieval-augmented generation with the file search tool.
  name: Vector Stores
image: https://openai.com/content/images/2023/05/openai-avatar.png
integrations:
- description: Deploy OpenAI models on Azure infrastructure with enterprise security, compliance, and regional availability.
  name: Microsoft Azure OpenAI
- description: Build LLM-powered applications using the LangChain framework with OpenAI model providers.
  name: LangChain
- description: Connect ChatGPT to thousands of apps for automated workflows without code.
  name: Zapier
- description: Integrate ChatGPT into Slack workspaces for team collaboration and AI-assisted communication.
  name: Slack
jsonld:
- class_count: 0
  name: Chatgpt Chat Completions Context
  property_count: 0
  slug: chatgpt-chat-completions-context
- class_count: 0
  name: Chatgpt Context
  property_count: 16
  slug: chatgpt-context
- class_count: 0
  name: Chatgpt Responses Context
  property_count: 0
  slug: chatgpt-responses-context
layout: provider
modified: '2026-04-18'
name: ChatGPT
rules:
- name: ChatGPT API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: chatgpt-spectral-rules
skills: []
slug: chatgpt
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: ChatGPT\ndescription: >-\n  OpenAI's ChatGPT API for conversational AI and language model interactions.\nimage: https://openai.com/content/images/2023/05/openai-avatar.png\nurl: https://platform.openai.com/docs/api-reference\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Contract\naccess: 3rd-Party\napis:\n  - name: ChatGPT API\n    description: >-\n      API for accessing OpenAI's ChatGPT language models for chat completions and\n      conversations.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/guides/chat\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Chatbot\n      - Conversational AI\n      - Machine Learning\n      - Natural Language Processing\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/chat\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n\
  \      - type: OpenAPI\n        url: openapi/chatgpt-chat-completions-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/chatgpt-chat-completion-schema.json\n      - type: JSONLD\n        url: json-ld/chatgpt-context.jsonld\n      - type: Authentication\n        url: https://platform.openai.com/docs/api-reference/authentication\n      - type: Pricing\n        url: https://openai.com/pricing\n      - type: RateLimits\n        url: https://platform.openai.com/docs/guides/rate-limits\n      - type: TermsOfService\n        url: https://openai.com/terms\n      - type: PrivacyPolicy\n        url: https://openai.com/privacy\n      - type: StatusPage\n        url: https://status.openai.com\n      - type: Support\n        url: https://help.openai.com\n      - type: GitHubOrganization\n        url: https://github.com/openai\n      - type: GettingStarted\n        url: https://platform.openai.com/docs/quickstart\n      - type: ChangeLog\n        url: https://platform.openai.com/docs/changelog\n\
  \      - type: Blog\n        url: https://openai.com/blog\n      - type: SDK\n        url: https://developers.openai.com/api/docs/libraries/\n      - type: Security\n        url: https://openai.com/business-data/\n      - type: Models\n        url: https://platform.openai.com/docs/models\n      - type: SignUp\n        url: https://platform.openai.com/signup\n      - type: Login\n        url: https://platform.openai.com/login\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Responses API\n    description: >-\n      The Responses API is OpenAI's recommended API primitive for new projects, an\n      evolution of Chat Completions with built-in tools like web search, file search,\n      code interpreter, and support for agentic workflows.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/responses\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Agents\n\
  \      - Artificial Intelligence\n      - Conversational AI\n      - Responses\n      - Tools\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/responses\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n      - type: OpenAPI\n        url: openapi/chatgpt-responses-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/chatgpt-response-schema.json\n      - type: JSONLD\n        url: json-ld/chatgpt-responses-context.jsonld\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Embeddings API\n    description: >-\n      API for generating embedding vectors from input text using models like\n      text-embedding-3-small and text-embedding-3-large, useful for search,\n      clustering, and recommendations.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/embeddings\n\
  \    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Embeddings\n      - Machine Learning\n      - Search\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/embeddings\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Images API\n    description: >-\n      API for generating and editing images from text prompts using DALL-E and GPT\n      Image models, supporting image generations, edits, and variations.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/images\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Creative AI\n      - DALL-E\n      - Image Generation\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/images\n\
  \      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Audio API\n    description: >-\n      API for audio capabilities including text-to-speech generation, speech\n      transcription, and translation using Whisper and other audio models.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/audio\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Audio\n      - Speech\n      - Text-To-Speech\n      - Transcription\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/audio\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Moderations\
  \ API\n    description: >-\n      API for classifying text and images to detect potentially harmful content\n      across categories like hate, violence, and self-harm.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/moderations\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Content Safety\n      - Moderation\n      - Trust And Safety\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/moderations\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Fine-Tuning API\n    description: >-\n      API for creating and managing fine-tuning jobs to customize OpenAI models on\n      your own training data, supporting supervised fine-tuning and direct preference\n      optimization.\n\
  \    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/fine-tuning\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Fine-Tuning\n      - Machine Learning\n      - Model Customization\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/fine-tuning\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Files API\n    description: >-\n      API for uploading and managing files used across OpenAI features including\n      fine-tuning, assistants, batch processing, and vision.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/files\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial\
  \ Intelligence\n      - Files\n      - Storage\n      - Uploads\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/files\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Batch API\n    description: >-\n      API for sending asynchronous groups of requests at lower cost with a separate\n      pool of significantly higher rate limits, supporting chat completions,\n      embeddings, and completions endpoints.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/batch\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Asynchronous\n      - Batch Processing\n      - Cost Optimization\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/batch\n\
  \      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Uploads API\n    description: >-\n      API for uploading large files in multiple parts, supporting files up to 8 GB\n      for use with fine-tuning, assistants, and batch processing.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/uploads\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Files\n      - Large Files\n      - Uploads\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/uploads\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Vector Stores API\n    description:\
  \ >-\n      API for creating and managing vector stores used by the file search tool,\n      supporting collections of processed files for retrieval-augmented generation.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/vector-stores\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - File Search\n      - Retrieval\n      - Vector Stores\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/vector-stores\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Realtime API\n    description: >-\n      API for real-time multimodal communication with models over WebRTC, WebSocket,\n      and SIP, supporting speech-to-speech, text, image, and audio inputs and outputs\n      with\
  \ ultra-low latency.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/realtime\n    baseURL: https://api.openai.com/v1\n    tags:\n      - Artificial Intelligence\n      - Audio\n      - Realtime\n      - Speech\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/realtime\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\n  - name: OpenAI Models API\n    description: >-\n      API for listing and retrieving information about available OpenAI models,\n      including details on permissions and capabilities.\n    image: https://openai.com/content/images/2023/05/openai-avatar.png\n    humanURL: https://platform.openai.com/docs/api-reference/models\n    baseURL: https://api.openai.com/v1\n    tags:\n      -\
  \ Artificial Intelligence\n      - Models\n    properties:\n      - type: Documentation\n        url: https://platform.openai.com/docs/api-reference/models\n      - type: OpenAPI\n        url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n    contact:\n      - type: Support\n        url: https://help.openai.com\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n  - name: OpenAI\n    email: support@openai.com\n    url: https://openai.com\ncommon:\n  - type: Portal\n    url: https://platform.openai.com\n  - type: Documentation\n    url: https://platform.openai.com/docs/api-reference\n  - type: GettingStarted\n    url: https://platform.openai.com/docs/quickstart\n  - type: Authentication\n    url: https://platform.openai.com/docs/api-reference/authentication\n  - type: Pricing\n    url: https://openai.com/pricing\n  - type: RateLimits\n    url: https://platform.openai.com/docs/guides/rate-limits\n  - type: ChangeLog\n\
  \    url: https://platform.openai.com/docs/changelog\n  - type: Blog\n    url: https://openai.com/blog\n  - type: StatusPage\n    url: https://status.openai.com\n  - type: Support\n    url: https://help.openai.com\n  - type: GitHubOrganization\n    url: https://github.com/openai\n  - type: SDK\n    url: https://developers.openai.com/api/docs/libraries/\n  - type: CodeExamples\n    url: https://cookbook.openai.com/\n  - type: OpenAPI\n    url: https://github.com/openai/openai-openapi/blob/master/openapi.yaml\n  - type: TermsOfService\n    url: https://openai.com/terms\n  - type: PrivacyPolicy\n    url: https://openai.com/privacy\n  - type: Security\n    url: https://openai.com/business-data/\n  - type: Models\n    url: https://platform.openai.com/docs/models\n  - type: SignUp\n    url: https://platform.openai.com/signup\n  - type: Login\n    url: https://platform.openai.com/login\n  - type: Features\n    data:\n      - name: Chat Completions\n        description: Generate conversational\
  \ responses using GPT models with support for text, function calling, structured outputs, vision inputs, and streaming.\n      - name: Responses API\n        description: Next-generation API with built-in tools for web search, file search, computer use, and code interpreter supporting agentic workflows.\n      - name: Embeddings\n        description: Generate vector representations of text for search, clustering, classification, and recommendation use cases.\n      - name: Image Generation\n        description: Create and edit images from text prompts using DALL-E and GPT Image models.\n      - name: Audio and Speech\n        description: Text-to-speech generation, speech transcription, and translation using Whisper and other audio models.\n      - name: Content Moderation\n        description: Classify text and images to detect potentially harmful content across safety categories.\n      - name: Fine-Tuning\n        description: Customize OpenAI models on your own training data for domain-specific\
  \ performance improvements.\n      - name: Batch Processing\n        description: Send asynchronous groups of requests at lower cost with higher rate limits.\n      - name: Realtime Communication\n        description: Ultra-low latency multimodal communication over WebRTC, WebSocket, and SIP.\n      - name: Vector Stores\n        description: Manage collections of processed files for retrieval-augmented generation with the file search tool.\n  - type: UseCases\n    data:\n      - name: Customer Support Automation\n        description: Build AI-powered chatbots and support agents that handle customer inquiries, troubleshoot issues, and escalate complex cases.\n      - name: Content Generation\n        description: Generate marketing copy, blog posts, product descriptions, and creative content at scale.\n      - name: Code Assistance\n        description: Help developers write, review, debug, and explain code across multiple programming languages.\n      - name: Data Analysis\n        description:\
  \ Extract insights from unstructured text, summarize documents, and perform sentiment analysis.\n      - name: Multimodal Applications\n        description: Build applications that process text, images, and audio inputs together for richer user experiences.\n      - name: Agentic Workflows\n        description: Create autonomous AI agents that use tools, search the web, and execute multi-step tasks.\n  - type: Integrations\n    data:\n      - name: Microsoft Azure OpenAI\n        description: Deploy OpenAI models on Azure infrastructure with enterprise security, compliance, and regional availability.\n      - name: LangChain\n        description: Build LLM-powered applications using the LangChain framework with OpenAI model providers.\n      - name: Zapier\n        description: Connect ChatGPT to thousands of apps for automated workflows without code.\n      - name: Slack\n        description: Integrate ChatGPT into Slack workspaces for team collaboration and AI-assisted communication.\n\
  tags:\n  - Agents\n  - AI\n  - ChatGPT\n  - Embeddings\n  - Fine-Tuning\n  - GPT-4\n  - GPT-5\n  - Language Model\n  - OpenAI\n  - Realtime\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chatgpt/refs/heads/main/apis.yml
tags:
- Agents
- AI
- ChatGPT
- Embeddings
- Fine-Tuning
- GPT-4
- GPT-5
- Language Model
- OpenAI
- Realtime
url: https://platform.openai.com/docs/api-reference
use_cases:
- description: Build AI-powered chatbots and support agents that handle customer inquiries, troubleshoot issues, and escalate complex cases.
  name: Customer Support Automation
- description: Generate marketing copy, blog posts, product descriptions, and creative content at scale.
  name: Content Generation
- description: Help developers write, review, debug, and explain code across multiple programming languages.
  name: Code Assistance
- description: Extract insights from unstructured text, summarize documents, and perform sentiment analysis.
  name: Data Analysis
- description: Build applications that process text, images, and audio inputs together for richer user experiences.
  name: Multimodal Applications
- description: Create autonomous AI agents that use tools, search the web, and execute multi-step tasks.
  name: Agentic Workflows
---
