---
api_count: 8
api_specs:
- filename: mistral-ai-chat-completions-openapi.yml
  format: yaml
  label: Mistral AI Chat Completions API
  slug: chat-completions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-chat-completions-openapi.yml
- filename: mistral-ai-embeddings-openapi.yml
  format: yaml
  label: Mistral AI Embeddings API
  slug: embeddings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-embeddings-openapi.yml
- filename: mistral-ai-agents-openapi.yml
  format: yaml
  label: Mistral AI Agents API
  slug: agents
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-agents-openapi.yml
- filename: mistral-ai-fine-tuning-openapi.yml
  format: yaml
  label: Mistral AI Fine-Tuning API
  slug: fine-tuning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-fine-tuning-openapi.yml
- filename: mistral-ai-ocr-openapi.yml
  format: yaml
  label: Mistral AI OCR API
  slug: ocr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-ocr-openapi.yml
- filename: mistral-ai-models-openapi.yml
  format: yaml
  label: Mistral AI Models API
  slug: models
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-models-openapi.yml
- filename: mistral-ai-forge-openapi.yml
  format: yaml
  label: Mistral AI Forge API
  slug: forge
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-forge-openapi.yml
- filename: mistral-ai-batch-openapi.yml
  format: yaml
  label: Mistral AI Batch API
  slug: batch
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-batch-openapi.yml
apis:
- description: 'The Mistral AI Chat Completions API enables developers to interact with Mistral''s language models in a conversational manner. It supports multi-turn conversations, function calling, and JSON mode for '
  name: Mistral AI Chat Completions API
  slug: chat-completions
- description: 'The Mistral AI Embeddings API allows developers to compute document and text embeddings using Mistral''s embedding models. These embeddings can be used for semantic search, clustering, classification, '
  name: Mistral AI Embeddings API
  slug: embeddings
- description: The Mistral AI Agents API provides a dedicated framework for building agentic applications. It complements the Chat Completion API by enabling AI agents to handle complex tasks, maintain context acros
  name: Mistral AI Agents API
  slug: agents
- description: The Mistral AI Fine-Tuning API allows developers to create and manage fine-tuning jobs that customize Mistral models on proprietary datasets. Users can upload training data, configure hyperparameters,
  name: Mistral AI Fine-Tuning API
  slug: fine-tuning
- description: The Mistral AI OCR API provides optical character recognition capabilities powered by the mistral-ocr-latest model. It can extract text and structured content from PDF documents and images, comprehend
  name: Mistral AI OCR API
  slug: ocr
- description: The Mistral AI Models API provides endpoints for listing and retrieving information about available models on the Mistral platform. Developers can query which models are accessible, inspect model capa
  name: Mistral AI Models API
  slug: models
- description: Mistral AI Forge is a model-training platform providing a unified API for the entire model lifecycle from pre-training to reinforcement learning. Forge enables enterprises to build frontier-grade AI m
  name: Mistral AI Forge API
  slug: forge
- description: 'The Mistral AI Batch API enables developers to submit large volumes of requests for asynchronous processing at reduced cost. It is designed for workloads that do not require real-time responses, such '
  name: Mistral AI Batch API
  slug: batch
common:
- title: ''
  type: Portal
  url: https://console.mistral.ai/
- title: ''
  type: Documentation
  url: https://docs.mistral.ai/
- title: ''
  type: Website
  url: https://mistral.ai/
- title: ''
  type: PrivacyPolicy
  url: https://mistral.ai/terms/#privacy-policy
- title: ''
  type: TermsOfService
  url: https://mistral.ai/terms/#terms-of-use
- title: ''
  type: Blog
  url: https://mistral.ai/news/
- title: ''
  type: Login
  url: https://console.mistral.ai/
- title: ''
  type: JSON-LD
  url: json-ld/mistral-ai-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/mistral-ai-chat-completion-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mistral-ai-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mistral-ai-fine-tuning-job-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mistral-ai-batch-job-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mistral-ai-ocr-response-schema.json
created: '2025-03-07'
description: Mistral AI is a French artificial intelligence company that develops and provides frontier large language models and APIs for developers and enterprises. Their developer platform offers APIs for chat completions, embeddings, fine-tuning, OCR, batch processing, and agentic workflows, enabling teams to build sophisticated AI-powered applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Mistral Ai Context
  property_count: 8
  slug: mistral-ai-context
layout: provider
modified: '2026-04-28'
name: Mistral AI
skills: []
slug: mistral-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mistral-ai\nname: Mistral AI\ndescription: >-\n  Mistral AI is a French artificial intelligence company that develops and\n  provides frontier large language models and APIs for developers and\n  enterprises. Their developer platform offers APIs for chat completions,\n  embeddings, fine-tuning, OCR, batch processing, and agentic workflows,\n  enabling teams to build sophisticated AI-powered applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/apis.yml\ntags:\n  - Agents\n  - Artificial Intelligence\n  - Batch Processing\n  - Chat\n  - Embeddings\n  - Fine-Tuning\n  - Large Language Models\n  - OCR\ncreated: '2025-03-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: mistral-ai:chat-completions\n    name: Mistral AI Chat Completions API\n    description: >-\n      The Mistral AI Chat Completions API enables developers\
  \ to interact with\n      Mistral's language models in a conversational manner. It supports\n      multi-turn conversations, function calling, and JSON mode for structured\n      outputs. The API provides access to a range of models including Mistral\n      Large, Mistral Small, and Codestral, each optimized for different use\n      cases from general reasoning to code generation.\n    humanURL: https://docs.mistral.ai/api/endpoint/chat\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Chat\n      - Completions\n      - Conversational AI\n      - Large Language Models\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/api/endpoint/chat\n      - type: OpenAPI\n        url: openapi/mistral-ai-chat-completions-openapi.yml\n  - aid: mistral-ai:embeddings\n    name: Mistral AI Embeddings API\n    description: >-\n      The Mistral AI Embeddings API allows developers to compute document and\n      text embeddings using\
  \ Mistral's embedding models. These embeddings can be\n      used for semantic search, clustering, classification, and retrieval\n      augmented generation workflows. The API accepts text inputs and returns\n      high-dimensional vector representations suitable for a variety of natural\n      language processing tasks.\n    humanURL: https://docs.mistral.ai/capabilities/embeddings\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Embeddings\n      - Semantic Search\n      - Vector Search\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/capabilities/embeddings\n      - type: OpenAPI\n        url: openapi/mistral-ai-embeddings-openapi.yml\n  - aid: mistral-ai:agents\n    name: Mistral AI Agents API\n    description: >-\n      The Mistral AI Agents API provides a dedicated framework for building\n      agentic applications. It complements the Chat Completion API by enabling\n      AI agents to handle complex tasks,\
  \ maintain context across interactions,\n      and coordinate multiple actions. Developers can create agents with\n      specific configurations, tools, and instructions, making it suitable for\n      enterprise-grade agentic platforms and multi-step workflow automation.\n    humanURL: https://docs.mistral.ai/api/endpoint/agents\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Agentic Workflows\n      - Agents\n      - Artificial Intelligence\n      - Automation\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/api/endpoint/agents\n      - type: OpenAPI\n        url: openapi/mistral-ai-agents-openapi.yml\n  - aid: mistral-ai:fine-tuning\n    name: Mistral AI Fine-Tuning API\n    description: >-\n      The Mistral AI Fine-Tuning API allows developers to create and manage\n      fine-tuning jobs that customize Mistral models on proprietary datasets.\n      Users can upload training data, configure hyperparameters, and monitor\n\
  \      job progress through the API. Fine-tuned models can then be deployed and\n      accessed through the Chat Completions endpoint, enabling domain-specific\n      performance improvements for enterprise applications.\n    humanURL: https://docs.mistral.ai/api/endpoint/fine-tuning\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Customization\n      - Fine-Tuning\n      - Machine Learning\n      - Model Training\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/api/endpoint/fine-tuning\n      - type: OpenAPI\n        url: openapi/mistral-ai-fine-tuning-openapi.yml\n  - aid: mistral-ai:ocr\n    name: Mistral AI OCR API\n    description: >-\n      The Mistral AI OCR API provides optical character recognition\n      capabilities powered by the mistral-ocr-latest model. It can extract text\n      and structured content from PDF documents and images, comprehending\n      complex document elements including media,\
  \ tables, equations, and\n      interleaved text. The API returns ordered, structured content suitable\n      for downstream processing and retrieval augmented generation pipelines.\n    humanURL: https://docs.mistral.ai/api/endpoint/ocr\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Document AI\n      - OCR\n      - PDF Processing\n      - Text Extraction\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/api/endpoint/ocr\n      - type: OpenAPI\n        url: openapi/mistral-ai-ocr-openapi.yml\n  - aid: mistral-ai:models\n    name: Mistral AI Models API\n    description: >-\n      The Mistral AI Models API provides endpoints for listing and retrieving\n      information about available models on the Mistral platform. Developers\n      can query which models are accessible, inspect model capabilities and\n      metadata, and manage fine-tuned model deployments. This API serves as the\n      foundation for model\
  \ discovery and lifecycle management within the\n      Mistral ecosystem.\n    humanURL: https://docs.mistral.ai/api/endpoint/models\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Infrastructure\n      - Model Management\n      - Models\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/api/endpoint/models\n      - type: OpenAPI\n        url: openapi/mistral-ai-models-openapi.yml\n  - aid: mistral-ai:forge\n    name: Mistral AI Forge API\n    description: >-\n      Mistral AI Forge is a model-training platform providing a unified API for\n      the entire model lifecycle from pre-training to reinforcement learning.\n      Forge enables enterprises to build frontier-grade AI models grounded in\n      proprietary knowledge, supporting pre-training on large internal\n      datasets, post-training through supervised fine-tuning with DPO and\n      ODPO, and reinforcement learning pipelines for aligning models with\n\
  \      internal policies. Forge is optimized for agentic workflows, allowing AI\n      agents to programmatically schedule training jobs, optimize\n      hyperparameters, and generate synthetic data. The platform supports both\n      Dense and Mixture-of-Experts model architectures with serverless\n      infrastructure.\n    humanURL: https://mistral.ai/news/forge\n    tags:\n      - Agentic Workflows\n      - Artificial Intelligence\n      - Enterprise AI\n      - Model Training\n      - Pre-Training\n      - Reinforcement Learning\n    properties:\n      - type: Documentation\n        url: https://mistral.ai/news/forge\n      - type: OpenAPI\n        url: openapi/mistral-ai-forge-openapi.yml\n  - aid: mistral-ai:batch\n    name: Mistral AI Batch API\n    description: >-\n      The Mistral AI Batch API enables developers to submit large volumes of\n      requests for asynchronous processing at reduced cost. It is designed for\n      workloads that do not require real-time responses, such\
  \ as bulk text\n      classification, large-scale content generation, and data processing\n      pipelines. Developers can submit batch jobs, monitor their progress, and\n      retrieve results once processing is complete.\n    humanURL: https://docs.mistral.ai/capabilities/batch\n    baseURL: https://api.mistral.ai/v1\n    tags:\n      - Artificial Intelligence\n      - Asynchronous\n      - Batch Processing\n      - Large Scale\n    properties:\n      - type: Documentation\n        url: https://docs.mistral.ai/capabilities/batch\n      - type: OpenAPI\n        url: openapi/mistral-ai-batch-openapi.yml\ncommon:\n  - type: Portal\n    url: https://console.mistral.ai/\n  - type: Documentation\n    url: https://docs.mistral.ai/\n  - type: Website\n    url: https://mistral.ai/\n  - type: PrivacyPolicy\n    url: https://mistral.ai/terms/#privacy-policy\n  - type: TermsOfService\n    url: https://mistral.ai/terms/#terms-of-use\n  - type: Blog\n    url: https://mistral.ai/news/\n  - type: Login\n\
  \    url: https://console.mistral.ai/\n  - type: JSON-LD\n    url: json-ld/mistral-ai-context.jsonld\n  - type: JSONSchema\n    url: json-schema/mistral-ai-chat-completion-schema.json\n  - type: JSONSchema\n    url: json-schema/mistral-ai-model-schema.json\n  - type: JSONSchema\n    url: json-schema/mistral-ai-fine-tuning-job-schema.json\n  - type: JSONSchema\n    url: json-schema/mistral-ai-batch-job-schema.json\n  - type: JSONSchema\n    url: json-schema/mistral-ai-ocr-response-schema.json\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/apis.yml
tags:
- Agents
- Artificial Intelligence
- Batch Processing
- Chat
- Embeddings
- Fine-Tuning
- Large Language Models
- OCR
url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/apis.yml
use_cases: []
---
