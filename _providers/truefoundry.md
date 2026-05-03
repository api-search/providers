---
api_count: 5
apis:
- description: The TrueFoundry AI Gateway API is a proxy layer that sits between applications and LLM providers, enabling unified access to 1000+ language models through a single OpenAI-compatible endpoint. It suppo
  name: TrueFoundry AI Gateway API
  slug: truefoundry-ai-gateway-api
- description: The TrueFoundry MCP (Model Context Protocol) Gateway provides a centralized registry and proxy for managing MCP servers accessible to AI agents. It handles authentication, access control, schema valid
  name: TrueFoundry MCP Gateway API
  slug: truefoundry-mcp-gateway-api
- description: The TrueFoundry Platform API provides programmatic access to the TrueFoundry MLOps platform for managing applications, deployments, users, and infrastructure resources. It enables automation of servic
  name: TrueFoundry Platform API
  slug: truefoundry-platform-api
- description: TrueFoundry's Model Serving capability enables deployment and management of LLM and embedding models using backends like vLLM and Triton on Kubernetes infrastructure. It provides APIs for deploying mo
  name: TrueFoundry Model Serving API
  slug: truefoundry-model-serving-api
- description: 'The TrueFoundry Model Registry provides a versioned repository for storing and managing machine learning models backed by cloud storage such as S3, GCS, Azure Blob, or Minio. It supports programmatic '
  name: TrueFoundry Model Registry API
  slug: truefoundry-model-registry-api
common:
- title: ''
  type: Website
  url: https://www.truefoundry.com/
- title: ''
  type: Documentation
  url: https://www.truefoundry.com/docs
- title: ''
  type: Getting Started
  url: https://www.truefoundry.com/docs/ai-gateway/quick-start
- title: ''
  type: Authentication
  url: https://www.truefoundry.com/docs/ai-gateway/authentication
- title: ''
  type: Pricing
  url: https://www.truefoundry.com/pricing
- title: ''
  type: Blog
  url: https://www.truefoundry.com/blog
- title: ''
  type: Change Log
  url: https://www.truefoundry.com/docs/changelog
- title: ''
  type: GitHub Organization
  url: https://github.com/truefoundry
- title: ''
  type: GitHubRepository
  url: https://github.com/truefoundry/truefoundry-python-sdk
- title: ''
  type: SDKs
  url: https://github.com/truefoundry/truefoundry-python-sdk
- title: ''
  type: Sign Up
  url: https://app.truefoundry.com/signup
created: '2026-03-16'
description: TrueFoundry is a Kubernetes-native enterprise AI platform for deploying and managing agentic AI workloads. It provides an AI Gateway, MCP Gateway, model serving, fine-tuning, and a full MLOps platform that works across on-premises, VPC, hybrid, or public cloud environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-18'
name: TrueFoundry
skills: []
slug: truefoundry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: truefoundry\nname: TrueFoundry\ndescription: >-\n  TrueFoundry is a Kubernetes-native enterprise AI platform for deploying and\n  managing agentic AI workloads. It provides an AI Gateway, MCP Gateway, model\n  serving, fine-tuning, and a full MLOps platform that works across on-premises,\n  VPC, hybrid, or public cloud environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Platform\n  - Enterprise AI\n  - Kubernetes\n  - LLM Gateway\n  - MLOps\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: truefoundry:truefoundry-ai-gateway-api\n    name: TrueFoundry AI Gateway API\n    description: >-\n      The TrueFoundry AI Gateway API is a proxy layer that sits between\n      applications and LLM providers, enabling unified access to 1000+ language\n      models through\
  \ a single OpenAI-compatible endpoint. It supports chat\n      completions, embeddings, image generation, audio processing, batch\n      operations, file management, content moderation, and model management with\n      centralized authentication, rate limiting, budget controls, and\n      observability.\n    humanURL: https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway\n    baseURL: https://gateway.truefoundry.ai/api/llm\n    tags:\n      - AI Gateway\n      - Chat Completions\n      - Embeddings\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway\n      - type: Getting Started\n        url: https://www.truefoundry.com/docs/ai-gateway/quick-start\n      - type: Authentication\n        url: https://www.truefoundry.com/docs/ai-gateway/authentication\n      - type: Reference\n        url: https://www.truefoundry.com/docs/api-reference\n  - aid: truefoundry:truefoundry-mcp-gateway-api\n    name:\
  \ TrueFoundry MCP Gateway API\n    description: >-\n      The TrueFoundry MCP (Model Context Protocol) Gateway provides a centralized\n      registry and proxy for managing MCP servers accessible to AI agents. It\n      handles authentication, access control, schema validation, and tool\n      orchestration across multiple MCP servers, supporting header auth, OAuth2,\n      and token passthrough authentication modes.\n    humanURL: https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started\n    baseURL: https://gateway.truefoundry.ai\n    tags:\n      - Agent Tools\n      - AI Agents\n      - MCP\n      - Tool Registry\n    properties:\n      - type: Documentation\n        url: https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started\n      - type: Authentication\n        url: https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-gateway-auth-security\n  - aid: truefoundry:truefoundry-platform-api\n    name: TrueFoundry Platform API\n    description: >-\n\
  \      The TrueFoundry Platform API provides programmatic access to the\n      TrueFoundry MLOps platform for managing applications, deployments, users,\n      and infrastructure resources. It enables automation of service deployments,\n      training jobs, model registry operations, and workflow orchestration across\n      Kubernetes-based compute environments.\n    humanURL: https://www.truefoundry.com/docs\n    baseURL: https://app.truefoundry.com/api\n    tags:\n      - Deployments\n      - Management\n      - MLOps\n      - Platform\n    properties:\n      - type: Documentation\n        url: https://www.truefoundry.com/docs\n      - type: Client Libraries\n        url: https://github.com/truefoundry/truefoundry-python-sdk\n  - aid: truefoundry:truefoundry-model-serving-api\n    name: TrueFoundry Model Serving API\n    description: >-\n      TrueFoundry's Model Serving capability enables deployment and management of\n      LLM and embedding models using backends like vLLM and Triton\
  \ on Kubernetes\n      infrastructure. It provides APIs for deploying models from a community\n      registry of 1000+ configurations, managing inference endpoints, and\n      controlling autoscaling behavior including scale-to-zero.\n    humanURL: https://www.truefoundry.com/docs/introduction-to-a-service\n    baseURL: https://app.truefoundry.com\n    tags:\n      - Kubernetes\n      - LLM Inference\n      - MLOps\n      - Model Serving\n    properties:\n      - type: Documentation\n        url: https://www.truefoundry.com/docs/introduction-to-a-service\n  - aid: truefoundry:truefoundry-model-registry-api\n    name: TrueFoundry Model Registry API\n    description: >-\n      The TrueFoundry Model Registry provides a versioned repository for storing\n      and managing machine learning models backed by cloud storage such as S3,\n      GCS, Azure Blob, or Minio. It supports programmatic model logging via the\n      truefoundry.ml Python client, multi-framework model formats, and automatic\n\
  \      versioning with metadata management.\n    humanURL: https://www.truefoundry.com/docs/model-registry\n    baseURL: https://app.truefoundry.com\n    tags:\n      - Machine Learning\n      - MLOps\n      - Model Registry\n      - Versioning\n    properties:\n      - type: Documentation\n        url: https://www.truefoundry.com/docs/model-registry\ncommon:\n  - type: Website\n    url: https://www.truefoundry.com/\n  - type: Documentation\n    url: https://www.truefoundry.com/docs\n  - type: Getting Started\n    url: https://www.truefoundry.com/docs/ai-gateway/quick-start\n  - type: Authentication\n    url: https://www.truefoundry.com/docs/ai-gateway/authentication\n  - type: Pricing\n    url: https://www.truefoundry.com/pricing\n  - type: Blog\n    url: https://www.truefoundry.com/blog\n  - type: Change Log\n    url: https://www.truefoundry.com/docs/changelog\n  - type: GitHub Organization\n    url: https://github.com/truefoundry\n  - type: GitHubRepository\n    url: https://github.com/truefoundry/truefoundry-python-sdk\n\
  \  - type: SDKs\n    url: https://github.com/truefoundry/truefoundry-python-sdk\n  - type: Sign Up\n    url: https://app.truefoundry.com/signup\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml
tags:
- AI Platform
- Enterprise AI
- Kubernetes
- LLM Gateway
- MLOps
url: https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml
use_cases: []
---
