---
api_count: 1
apis:
- description: 'ngrok AI Gateway exposes an OpenAI-compatible HTTP interface for routing requests across multiple AI providers and self-hosted models. Each AI Gateway instance has a unique base URL of the form https:'
  name: ngrok AI Gateway
  slug: ai-gateway
common:
- title: ''
  type: Website
  url: https://ngrok.com/ai-gateway
- title: ''
  type: Documentation
  url: https://ngrok.com/docs/ai-gateway/
- title: ''
  type: GettingStarted
  url: https://ngrok.com/docs/ai-gateway/quickstart/
- title: ''
  type: Blog
  url: https://ngrok.com/blog
- title: ''
  type: Pricing
  url: https://ngrok.com/pricing
- title: ''
  type: Support
  url: https://ngrok.com/support
- title: ''
  type: StatusPage
  url: https://status.ngrok.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/ngrok
created: '2026-03-16'
description: ngrok AI Gateway provides traffic management and security for AI APIs including multi-provider routing, automatic failover, LLM prompt inspection, rate limiting, caching, observability, PII redaction, and access control. It enables teams to manage, secure, and monitor traffic to AI model providers (OpenAI, Anthropic, Google, DeepSeek) and self-hosted models such as Ollama and vLLM through an OpenAI-compatible interface.
features:
- description: Direct requests to AI providers including OpenAI, Anthropic, Google, and DeepSeek through a single gateway endpoint.
  name: Multi-Provider Routing
- description: If one provider or model fails, the gateway automatically tries the next configured model.
  name: Automatic Failover
- description: Works with official and third-party OpenAI SDKs by changing only the base URL.
  name: OpenAI SDK Compatibility
- description: Route requests to local systems such as Ollama or vLLM alongside hosted providers.
  name: Self-Hosted Model Support
- description: Use ngrok/auto for intelligent model picking based on configured strategies.
  name: Automatic Model Selection
- description: Define custom routing logic using Common Expression Language expressions.
  name: CEL-Based Selection Strategies
- description: Direct traffic to the cheapest available model option meeting requirements.
  name: Cost-Based Routing
- description: Restrict which providers and models clients can use by API key, identity, or policy.
  name: Access Control
- description: Inspect and modify content to remove personally identifiable information from prompts and responses.
  name: PII Redaction
- description: Modify and filter responses before they reach clients.
  name: Response Sanitization
- description: Access OpenAI and Anthropic models without individual provider signup, using ngrok credits.
  name: No Provider Account Required
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native OpenAI-compatible interface and routing to OpenAI models.
  name: OpenAI
- description: Routing and access to Anthropic Claude models through the gateway.
  name: Anthropic
- description: Routing to Google AI models.
  name: Google
- description: Routing to DeepSeek models.
  name: DeepSeek
- description: Routing to self-hosted Ollama instances.
  name: Ollama
- description: Routing to self-hosted vLLM inference servers.
  name: vLLM
layout: provider
modified: '2026-04-28'
name: ngrok AI Gateway
skills: []
slug: ngrok-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ngrok-ai\nname: ngrok AI Gateway\ndescription: >-\n  ngrok AI Gateway provides traffic management and security for AI APIs including\n  multi-provider routing, automatic failover, LLM prompt inspection, rate limiting,\n  caching, observability, PII redaction, and access control. It enables teams to\n  manage, secure, and monitor traffic to AI model providers (OpenAI, Anthropic,\n  Google, DeepSeek) and self-hosted models such as Ollama and vLLM through an\n  OpenAI-compatible interface.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - AI Gateway\n  - API Gateway\n  - LLM\n  - OpenAI Compatible\n  - Routing\n  - Security\n  - Traffic Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: ngrok-ai:ai-gateway\n    name: ngrok\
  \ AI Gateway\n    description: >-\n      ngrok AI Gateway exposes an OpenAI-compatible HTTP interface for routing\n      requests across multiple AI providers and self-hosted models. Each AI\n      Gateway instance has a unique base URL of the form\n      https://your-ai-gateway.ngrok.app/v1 and accepts standard OpenAI SDK calls\n      including chat completions. Traffic policies provide rate limiting, prompt\n      inspection, PII redaction, response sanitization, model access control,\n      cost-based routing, and automatic provider failover.\n    humanURL: https://ngrok.com/docs/ai-gateway/\n    baseURL: https://your-ai-gateway.ngrok.app/v1\n    tags:\n      - AI Gateway\n      - API Gateway\n      - LLM\n      - OpenAI Compatible\n      - Routing\n      - Security\n    properties:\n      - type: Documentation\n        url: https://ngrok.com/docs/ai-gateway/\n      - type: GettingStarted\n        url: https://ngrok.com/docs/ai-gateway/quickstart/\n      - type: APIReference\n     \
  \   url: https://ngrok.com/docs/ai-gateway/\ncommon:\n  - type: Website\n    url: https://ngrok.com/ai-gateway\n  - type: Documentation\n    url: https://ngrok.com/docs/ai-gateway/\n  - type: GettingStarted\n    url: https://ngrok.com/docs/ai-gateway/quickstart/\n  - type: Blog\n    url: https://ngrok.com/blog\n  - type: Pricing\n    url: https://ngrok.com/pricing\n  - type: Support\n    url: https://ngrok.com/support\n  - type: StatusPage\n    url: https://status.ngrok.com\n  - type: GitHubOrganization\n    url: https://github.com/ngrok\n  - type: Features\n    data:\n      - name: Multi-Provider Routing\n        description: Direct requests to AI providers including OpenAI, Anthropic, Google, and DeepSeek through a single gateway endpoint.\n      - name: Automatic Failover\n        description: If one provider or model fails, the gateway automatically tries the next configured model.\n      - name: OpenAI SDK Compatibility\n        description: Works with official and third-party OpenAI\
  \ SDKs by changing only the base URL.\n      - name: Self-Hosted Model Support\n        description: Route requests to local systems such as Ollama or vLLM alongside hosted providers.\n      - name: Automatic Model Selection\n        description: Use ngrok/auto for intelligent model picking based on configured strategies.\n      - name: CEL-Based Selection Strategies\n        description: Define custom routing logic using Common Expression Language expressions.\n      - name: Cost-Based Routing\n        description: Direct traffic to the cheapest available model option meeting requirements.\n      - name: Access Control\n        description: Restrict which providers and models clients can use by API key, identity, or policy.\n      - name: PII Redaction\n        description: Inspect and modify content to remove personally identifiable information from prompts and responses.\n      - name: Response Sanitization\n        description: Modify and filter responses before they reach clients.\n\
  \      - name: No Provider Account Required\n        description: Access OpenAI and Anthropic models without individual provider signup, using ngrok credits.\n  - type: UseCases\n    data:\n      - name: Centralized AI API Management\n        description: Manage all AI provider traffic through a single gateway with unified observability and policy enforcement.\n      - name: Cost Optimization\n        description: Route traffic to the most cost-effective model that meets quality requirements.\n      - name: Compliance and Data Protection\n        description: Enforce PII redaction and prompt inspection policies before requests leave the organization.\n      - name: Multi-Provider Resilience\n        description: Failover automatically across providers to maintain AI service availability.\n      - name: Local and Hybrid Model Routing\n        description: Route between hosted providers and self-hosted models such as Ollama or vLLM.\n  - type: Integrations\n    data:\n      - name: OpenAI\n\
  \        description: Native OpenAI-compatible interface and routing to OpenAI models.\n      - name: Anthropic\n        description: Routing and access to Anthropic Claude models through the gateway.\n      - name: Google\n        description: Routing to Google AI models.\n      - name: DeepSeek\n        description: Routing to DeepSeek models.\n      - name: Ollama\n        description: Routing to self-hosted Ollama instances.\n      - name: vLLM\n        description: Routing to self-hosted vLLM inference servers.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml
tags:
- AI
- AI Gateway
- API Gateway
- LLM
- OpenAI Compatible
- Routing
- Security
- Traffic Management
url: https://raw.githubusercontent.com/api-evangelist/ngrok-ai/refs/heads/main/apis.yml
use_cases:
- description: Manage all AI provider traffic through a single gateway with unified observability and policy enforcement.
  name: Centralized AI API Management
- description: Route traffic to the most cost-effective model that meets quality requirements.
  name: Cost Optimization
- description: Enforce PII redaction and prompt inspection policies before requests leave the organization.
  name: Compliance and Data Protection
- description: Failover automatically across providers to maintain AI service availability.
  name: Multi-Provider Resilience
- description: Route between hosted providers and self-hosted models such as Ollama or vLLM.
  name: Local and Hybrid Model Routing
---
