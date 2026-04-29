---
api_count: 6
apis:
- description: Run inference on 200,000+ machine learning models with a simple HTTP request.
  name: Hugging Face Inference API
  slug: ''
- description: Programmatically interact with the Hugging Face Hub - manage models, datasets, and spaces.
  name: Hugging Face Hub API
  slug: ''
- description: Deploy and scale machine learning models with dedicated, secure infrastructure.
  name: Hugging Face Inference Endpoints API
  slug: ''
- description: Unified proxy layer providing access to 15+ inference partners through a single OpenAI-compatible endpoint.
  name: Hugging Face Inference Providers API
  slug: ''
- description: Query and visualize datasets stored on the Hugging Face Hub through a lightweight REST API.
  name: Hugging Face Dataset Viewer API
  slug: ''
- description: High-performance toolkit for deploying and serving large language models with optimized inference.
  name: Hugging Face Text Generation Inference API
  slug: ''
capabilities:
- description: Unified workflow for deploying, scaling, and operating ML model inference endpoints on dedicated infrastructure. Combines Inference Endpoints management with TGI server monitoring. Used by ML platform
  name: Hugging Face Deployment and Operations
  slug: deployment-and-operations
- description: Unified workflow for managing models, datasets, and spaces on the Hugging Face Hub, and exploring dataset contents via the Dataset Viewer. Used by ML engineers, data scientists, and platform administr
  name: Hugging Face Hub and Data Management
  slug: hub-and-data-management
- description: Unified workflow for running AI/ML inference across Hugging Face APIs, combining the Inference API, Inference Providers, and Text Generation Inference for NLP, vision, audio, and multimodal tasks. Use
  name: Hugging Face Model Inference
  slug: model-inference
common:
- title: ''
  type: Portal
  url: https://huggingface.co
- title: ''
  type: Documentation
  url: https://huggingface.co/docs
- title: ''
  type: GettingStarted
  url: https://huggingface.co/inference/get-started
- title: ''
  type: Pricing
  url: https://huggingface.co/pricing
- title: ''
  type: Blog
  url: https://huggingface.co/blog
- title: ''
  type: ChangeLog
  url: https://huggingface.co/changelog
- title: ''
  type: SignUp
  url: https://huggingface.co/signup
- title: ''
  type: Login
  url: https://huggingface.co/login
- title: ''
  type: Support
  url: https://huggingface.co/support
- title: ''
  type: Contact
  url: https://huggingface.co/contact/sales
- title: ''
  type: Support
  url: https://discuss.huggingface.co
- title: ''
  type: GitHubOrganization
  url: https://github.com/huggingface
- title: ''
  type: X
  url: https://twitter.com/huggingface
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/huggingface
- title: ''
  type: Support
  url: https://huggingface.co/join/discord
- title: ''
  type: YouTube
  url: https://www.youtube.com/@HuggingFace
- title: ''
  type: StatusPage
  url: https://status.huggingface.co
- title: ''
  type: TermsOfService
  url: https://huggingface.co/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://huggingface.co/privacy
- title: ''
  type: SDK
  url: https://huggingface.co/docs/huggingface_hub/index
- title: ''
  type: SDK
  url: https://huggingface.co/docs/huggingface.js/en/index
- title: ''
  type: JSONSchema
  url: json-schema/hugging-face-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hugging-face-dataset-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hugging-face-space-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hugging-face-inference-endpoint-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hugging-face-user-schema.json
- title: ''
  type: JSONLD
  url: json-ld/hugging-face-context.jsonld
created: '2024'
description: The AI community building the future with open-source machine learning models, datasets, and applications.
features:
- description: Run inference on 200,000+ ML models with a simple HTTP request across NLP, vision, audio, and multimodal tasks.
  name: Model Inference
- description: Programmatically manage models, datasets, and spaces including creation, versioning, and access control.
  name: Hub Repository Management
- description: Deploy models on dedicated infrastructure with autoscaling, custom hardware, and private networking.
  name: Dedicated Endpoints
- description: Unified OpenAI-compatible API routing to 15+ inference providers with automatic model selection.
  name: Multi-Provider Routing
- description: Query, search, filter, and visualize datasets without downloading via the Dataset Viewer API.
  name: Dataset Exploration
- description: High-performance LLM serving with streaming, tool calling, structured output, and grammar constraints.
  name: Text Generation Inference
- description: Drop-in replacement for OpenAI API with chat completions, embeddings, and image generation endpoints.
  name: OpenAI Compatibility
image: https://huggingface.co/front/assets/huggingface_logo.svg
integrations:
- description: Deploy inference endpoints on AWS with SageMaker integration and GPU instances.
  name: AWS
- description: Route inference to Google Cloud TPUs and GPUs through the providers API.
  name: Google Cloud
- description: Deploy models on Azure infrastructure with managed endpoint support.
  name: Azure
- description: Use Hugging Face models as LangChain LLM and embedding providers.
  name: LangChain
- description: Build interactive ML demos with Gradio and deploy as Hugging Face Spaces.
  name: Gradio
jsonld:
- class_count: 4
  name: Hugging Face Context
  property_count: 15
  slug: hugging-face-context
- class_count: 0
  name: Hugging Face Dataset Viewer Context
  property_count: 0
  slug: hugging-face-dataset-viewer-context
- class_count: 0
  name: Hugging Face Hub Context
  property_count: 0
  slug: hugging-face-hub-context
- class_count: 0
  name: Hugging Face Inference Context
  property_count: 0
  slug: hugging-face-inference-context
- class_count: 0
  name: Hugging Face Inference Endpoints Context
  property_count: 0
  slug: hugging-face-inference-endpoints-context
- class_count: 0
  name: Hugging Face Inference Providers Context
  property_count: 0
  slug: hugging-face-inference-providers-context
- class_count: 0
  name: Hugging Face Text Generation Inference Context
  property_count: 0
  slug: hugging-face-text-generation-inference-context
layout: provider
modified: '2026-04-18'
name: Hugging Face
rules:
- name: Hugging Face API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: hugging-face-spectral-rules
skills: []
slug: hugging-face
solutions: []
source_yaml: "name: Hugging Face\ndescription: >-\n  The AI community building the future with open-source machine learning models, datasets,\n  and applications.\nimage: https://huggingface.co/front/assets/huggingface_logo.svg\nurl: https://huggingface.co\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\napis:\n  - name: Hugging Face Inference API\n    description: >-\n      Run inference on 200,000+ machine learning models with a simple HTTP request.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/api-inference/index\n    baseURL: https://api-inference.huggingface.co\n    tags:\n      - AI\n      - Inference\n      - Machine Learning\n      - Models\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/api-inference/index\n      - type: OpenAPI\n        url: https://huggingface.co/api-inference/openapi.json\n      - type: OpenAPI\n        url: openapi/hugging-face-inference-api.yml\n\
  \      - type: Authentication\n        url: https://huggingface.co/docs/api-inference/quicktour#authentication\n      - type: GettingStarted\n        url: https://huggingface.co/docs/api-inference/quicktour\n      - type: RateLimits\n        url: https://huggingface.co/docs/api-inference/en/rate-limits\n      - type: FAQ\n        url: https://huggingface.co/docs/api-inference/faq\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\n  - name: Hugging Face Hub API\n    description: >-\n      Programmatically interact with the Hugging Face Hub - manage models, datasets,\n      and spaces.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/hub/api\n    baseURL: https://huggingface.co/api\n    tags:\n      - Datasets\n      - Hub\n      - Models\n      - Repository Management\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/hub/api\n      - type: OpenAPI\n      \
  \  url: https://huggingface.co/.well-known/openapi.json\n      - type: OpenAPI\n        url: openapi/hugging-face-hub-api.yml\n      - type: SDK\n        url: https://huggingface.co/docs/huggingface_hub/index\n      - type: SDK\n        url: https://huggingface.co/docs/huggingface.js/hub/README\n      - type: Authentication\n        url: https://huggingface.co/docs/hub/security-tokens\n      - type: RateLimits\n        url: https://huggingface.co/docs/hub/en/rate-limits\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\n  - name: Hugging Face Inference Endpoints API\n    description: >-\n      Deploy and scale machine learning models with dedicated, secure infrastructure.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/inference-endpoints/index\n    baseURL: https://api.endpoints.huggingface.cloud\n    tags:\n      - Deployment\n      - Enterprise\n      - Inference\n      - Managed Service\n\
  \    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/inference-endpoints/api_reference\n      - type: OpenAPI\n        url: openapi/hugging-face-inference-endpoints-api.yml\n      - type: GettingStarted\n        url: https://huggingface.co/docs/inference-endpoints/index\n      - type: Pricing\n        url: https://huggingface.co/pricing#inference-endpoints\n      - type: Authentication\n        url: https://huggingface.co/docs/hub/security-tokens\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\n  - name: Hugging Face Inference Providers API\n    description: >-\n      Unified proxy layer providing access to 15+ inference partners through a single\n      OpenAI-compatible endpoint.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/inference-providers/en/index\n    baseURL: https://router.huggingface.co/v1\n    tags:\n      - AI\n      - Inference\n      - OpenAI\
  \ Compatible\n      - Providers\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/inference-providers/en/index\n      - type: OpenAPI\n        url: openapi/hugging-face-inference-providers-api.yml\n      - type: APIReference\n        url: https://huggingface.co/docs/inference-providers/en/tasks/index\n      - type: GettingStarted\n        url: https://huggingface.co/docs/inference-providers/en/guides/first-api-call\n      - type: Pricing\n        url: https://huggingface.co/docs/inference-providers/pricing\n      - type: Models\n        url: https://huggingface.co/inference/models\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\n  - name: Hugging Face Dataset Viewer API\n    description: >-\n      Query and visualize datasets stored on the Hugging Face Hub through a lightweight\n      REST API.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/dataset-viewer/index\n\
  \    baseURL: https://datasets-server.huggingface.co\n    tags:\n      - Data\n      - Datasets\n      - Viewer\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/dataset-viewer/index\n      - type: OpenAPI\n        url: https://datasets-server.huggingface.co/openapi.json\n      - type: OpenAPI\n        url: openapi/hugging-face-dataset-viewer-api.yml\n      - type: GettingStarted\n        url: https://huggingface.co/docs/dataset-viewer/en/quick_start\n      - type: GitHubRepository\n        url: https://github.com/huggingface/dataset-viewer\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\n  - name: Hugging Face Text Generation Inference API\n    description: >-\n      High-performance toolkit for deploying and serving large language models with\n      optimized inference.\n    image: https://huggingface.co/front/assets/huggingface_logo.svg\n    humanURL: https://huggingface.co/docs/text-generation-inference/en/index\n\
  \    baseURL: https://api-inference.huggingface.co\n    tags:\n      - AI\n      - Inference\n      - LLM\n      - Text Generation\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/text-generation-inference/en/index\n      - type: OpenAPI\n        url: openapi/hugging-face-text-generation-inference-api.yml\n      - type: APIReference\n        url: https://huggingface.co/docs/text-generation-inference/en/reference/api_reference\n      - type: GettingStarted\n        url: https://huggingface.co/docs/text-generation-inference/quicktour\n      - type: Documentation\n        url: https://huggingface.co/docs/text-generation-inference/en/messages_api\n      - type: GitHubRepository\n        url: https://github.com/huggingface/text-generation-inference\n    contact:\n      - type: Support\n        url: https://huggingface.co/support\ncommon:\n  - type: Portal\n    url: https://huggingface.co\n  - type: Documentation\n    url: https://huggingface.co/docs\n\
  \  - type: GettingStarted\n    url: https://huggingface.co/inference/get-started\n  - type: Pricing\n    url: https://huggingface.co/pricing\n  - type: Blog\n    url: https://huggingface.co/blog\n  - type: ChangeLog\n    url: https://huggingface.co/changelog\n  - type: SignUp\n    url: https://huggingface.co/signup\n  - type: Login\n    url: https://huggingface.co/login\n  - type: Support\n    url: https://huggingface.co/support\n  - type: Contact\n    url: https://huggingface.co/contact/sales\n  - type: Support\n    url: https://discuss.huggingface.co\n  - type: GitHubOrganization\n    url: https://github.com/huggingface\n  - type: X\n    url: https://twitter.com/huggingface\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/huggingface\n  - type: Support\n    url: https://huggingface.co/join/discord\n  - type: YouTube\n    url: https://www.youtube.com/@HuggingFace\n  - type: StatusPage\n    url: https://status.huggingface.co\n  - type: TermsOfService\n    url: https://huggingface.co/terms-of-service\n\
  \  - type: PrivacyPolicy\n    url: https://huggingface.co/privacy\n  - type: SDK\n    url: https://huggingface.co/docs/huggingface_hub/index\n  - type: SDK\n    url: https://huggingface.co/docs/huggingface.js/en/index\n  - type: Features\n    data:\n      - name: Model Inference\n        description: Run inference on 200,000+ ML models with a simple HTTP request across NLP, vision, audio, and multimodal tasks.\n      - name: Hub Repository Management\n        description: Programmatically manage models, datasets, and spaces including creation, versioning, and access control.\n      - name: Dedicated Endpoints\n        description: Deploy models on dedicated infrastructure with autoscaling, custom hardware, and private networking.\n      - name: Multi-Provider Routing\n        description: Unified OpenAI-compatible API routing to 15+ inference providers with automatic model selection.\n      - name: Dataset Exploration\n        description: Query, search, filter, and visualize datasets\
  \ without downloading via the Dataset Viewer API.\n      - name: Text Generation Inference\n        description: High-performance LLM serving with streaming, tool calling, structured output, and grammar constraints.\n      - name: OpenAI Compatibility\n        description: Drop-in replacement for OpenAI API with chat completions, embeddings, and image generation endpoints.\n  - type: UseCases\n    data:\n      - name: ML Model Prototyping\n        description: Rapidly prototype AI applications by running inference on pre-trained models without infrastructure setup.\n      - name: Production ML Deployment\n        description: Deploy and scale ML models for production workloads with dedicated endpoints and autoscaling.\n      - name: Dataset Curation\n        description: Explore, validate, and curate ML datasets programmatically for training pipeline automation.\n      - name: AI Application Development\n        description: Build AI-powered applications using unified inference APIs with\
  \ multi-provider routing.\n      - name: Model Benchmarking\n        description: Compare model performance across providers and hardware configurations for optimization.\n  - type: Integrations\n    data:\n      - name: AWS\n        description: Deploy inference endpoints on AWS with SageMaker integration and GPU instances.\n      - name: Google Cloud\n        description: Route inference to Google Cloud TPUs and GPUs through the providers API.\n      - name: Azure\n        description: Deploy models on Azure infrastructure with managed endpoint support.\n      - name: LangChain\n        description: Use Hugging Face models as LangChain LLM and embedding providers.\n      - name: Gradio\n        description: Build interactive ML demos with Gradio and deploy as Hugging Face Spaces.\n  - type: JSONSchema\n    url: json-schema/hugging-face-model-schema.json\n  - type: JSONSchema\n    url: json-schema/hugging-face-dataset-schema.json\n  - type: JSONSchema\n    url: json-schema/hugging-face-space-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/hugging-face-inference-endpoint-schema.json\n  - type: JSONSchema\n    url: json-schema/hugging-face-user-schema.json\n  - type: JSONLD\n    url: json-ld/hugging-face-context.jsonld\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hugging-face/refs/heads/main/apis.yml
tags: []
url: https://huggingface.co
use_cases:
- description: Rapidly prototype AI applications by running inference on pre-trained models without infrastructure setup.
  name: ML Model Prototyping
- description: Deploy and scale ML models for production workloads with dedicated endpoints and autoscaling.
  name: Production ML Deployment
- description: Explore, validate, and curate ML datasets programmatically for training pipeline automation.
  name: Dataset Curation
- description: Build AI-powered applications using unified inference APIs with multi-provider routing.
  name: AI Application Development
- description: Compare model performance across providers and hardware configurations for optimization.
  name: Model Benchmarking
---
