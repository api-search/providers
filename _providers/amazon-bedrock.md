---
api_count: 4
apis:
- description: The Amazon Bedrock management API provides operations for managing foundation models, custom models, model customization jobs, provisioned throughput, guardrails, knowledge bases, agents, and model ev
  name: Amazon Bedrock API
  slug: amazon-bedrock-api
- description: The Amazon Bedrock Runtime API provides operations for invoking foundation models for inference, including synchronous, streaming, and conversational invocation patterns. Also supports guardrail evalu
  name: Amazon Bedrock Runtime API
  slug: amazon-bedrock-runtime-api
- description: The Amazon Bedrock Agent API provides operations for managing and invoking autonomous AI agents, knowledge bases for RAG, data sources, and ingestion jobs.
  name: Amazon Bedrock Agent API
  slug: amazon-bedrock-agent-api
- description: The Amazon Bedrock Agent Runtime API provides operations for invoking Bedrock agents and retrieving from knowledge bases for RAG applications.
  name: Amazon Bedrock Agent Runtime API
  slug: amazon-bedrock-agent-runtime-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/bedrock/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/bedrock/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/bedrock/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://console.aws.amazon.com/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Pricing
  url: https://aws.amazon.com/bedrock/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/bedrock/faqs/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/bedrock/getting-started/
created: '2024-01-01'
description: Amazon Bedrock is a fully managed service that makes high-performing foundation models (FMs) from leading AI companies available through a unified API. It enables developers to build and scale generative AI applications using foundation models for text generation, summarization, image generation, and conversational AI without managing infrastructure. Bedrock supports model customization, fine-tuning, retrieval-augmented generation (RAG), autonomous agents, guardrails for responsible AI, and provisioned throughput for production workloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Amazon Bedrock Context
  property_count: 8
  slug: amazon-bedrock-context
layout: provider
modified: '2026-04-19'
name: Amazon Bedrock
skills: []
slug: amazon-bedrock
solutions: []
source_yaml: "aid: amazon-bedrock\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/apis.yml\nname: Amazon Bedrock\ntags:\n  - AI\n  - AWS\n  - Foundation Models\n  - Generative AI\n  - LLM\n  - Machine Learning\n  - RAG\n  - Agents\n  - Responsible AI\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Amazon Bedrock is a fully managed service that makes high-performing\n  foundation models (FMs) from leading AI companies available through a\n  unified API. It enables developers to build and scale generative AI\n  applications using foundation models for text generation, summarization,\n  image generation, and conversational AI without managing infrastructure.\n  Bedrock supports model customization, fine-tuning, retrieval-augmented\n  generation (RAG), autonomous agents, guardrails for responsible AI,\n  and provisioned throughput for production workloads.\ncreated: '2024-01-01'\nmodified:\
  \ '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-bedrock:amazon-bedrock-api\n    name: Amazon Bedrock API\n    description: >-\n      The Amazon Bedrock management API provides operations for managing\n      foundation models, custom models, model customization jobs, provisioned\n      throughput, guardrails, knowledge bases, agents, and model evaluation jobs.\n    humanURL: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n    baseURL: https://bedrock.us-east-1.amazonaws.com\n    tags:\n      - Foundation Models\n      - Generative AI\n      - Custom Models\n      - Guardrails\n      - Knowledge Bases\n      - Agents\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/openapi/amazon-bedrock-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/json-schema/amazon-bedrock-model-schema.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/json-structure/bedrock-resource-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/json-ld/amazon-bedrock-context.jsonld\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/vocabulary/vocabulary.yml\n\n  - aid: amazon-bedrock:amazon-bedrock-runtime-api\n    name: Amazon Bedrock Runtime API\n    description: >-\n      The Amazon Bedrock Runtime API provides operations\
  \ for invoking\n      foundation models for inference, including synchronous, streaming,\n      and conversational invocation patterns. Also supports guardrail\n      evaluation and async batch inference.\n    humanURL: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n    baseURL: https://bedrock-runtime.us-east-1.amazonaws.com\n    tags:\n      - Foundation Models\n      - Generative AI\n      - Inference\n      - Streaming\n      - Converse\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/openapi/amazon-bedrock-runtime-openapi.yml\n\n  - aid: amazon-bedrock:amazon-bedrock-agent-api\n    name: Amazon Bedrock Agent API\n    description: >-\n      The Amazon Bedrock Agent API provides operations for managing and\n      invoking autonomous AI agents, knowledge bases for RAG, data sources,\n\
  \      and ingestion jobs.\n    humanURL: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n    baseURL: https://bedrock-agent.us-east-1.amazonaws.com\n    tags:\n      - Agents\n      - Knowledge Bases\n      - RAG\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n\n  - aid: amazon-bedrock:amazon-bedrock-agent-runtime-api\n    name: Amazon Bedrock Agent Runtime API\n    description: >-\n      The Amazon Bedrock Agent Runtime API provides operations for invoking\n      Bedrock agents and retrieving from knowledge bases for RAG applications.\n    humanURL: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n    baseURL: https://bedrock-agent-runtime.us-east-1.amazonaws.com\n    tags:\n      - Agents\n      - RAG\n      - Retrieval\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/bedrock/latest/APIReference/\n\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n\
  \  - type: Website\n    url: https://aws.amazon.com/bedrock/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/bedrock/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/support/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/machine-learning/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/bedrock/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://console.aws.amazon.com/\n  - type: Status\n    url: https://health.aws.amazon.com/health/status\n  - type: Pricing\n    url: https://aws.amazon.com/bedrock/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/bedrock/faqs/\n  - type: GettingStarted\n    url: https://aws.amazon.com/bedrock/getting-started/\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/apis.yml
tags:
- AI
- AWS
- Foundation Models
- Generative AI
- LLM
- Machine Learning
- RAG
- Agents
- Responsible AI
url: https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/apis.yml
use_cases: []
---
