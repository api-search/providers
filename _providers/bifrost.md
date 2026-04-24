---
api_count: 3
apis:
- description: The Bifrost HTTP Gateway API provides an OpenAI-compatible RESTful interface that routes requests to any of 20+ supported AI providers. Requests specify the provider and model using provider/model-nam
  name: Bifrost HTTP Gateway API
  slug: bifrost-http-gateway-api
- description: The Bifrost Go SDK provides a native Go client for embedding the Bifrost AI gateway directly into Go applications using the github.com/maximhq/bifrost/core package.
  name: Bifrost Go SDK
  slug: bifrost-go-sdk
- description: The Bifrost Model Context Protocol (MCP) Gateway enables AI agents to discover and execute external tools through a standardized protocol, with OAuth 2.0 authentication and tool approval controls.
  name: Bifrost MCP Gateway
  slug: bifrost-mcp-gateway
capabilities:
- description: ''
  name: Ai Chat Routing
  slug: ai-chat-routing
common:
- title: ''
  type: Portal
  url: https://www.getmaxim.ai/bifrost/enterprise
- title: ''
  type: Documentation
  url: https://docs.getbifrost.ai
- title: ''
  type: GettingStarted
  url: https://docs.getbifrost.ai/quickstart/gateway/setting-up
- title: ''
  type: GitHubRepository
  url: https://github.com/maximhq/bifrost
- title: ''
  type: GitHubOrganization
  url: https://github.com/maximhq
- title: ''
  type: ChangeLog
  url: https://github.com/maximhq/bifrost/releases
- title: ''
  type: Community
  url: https://discord.gg/exN5KAydbU
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/rules/bifrost-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/vocabulary/bifrost-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/capabilities/ai-chat-routing.yaml
created: '2026-03-16'
description: Bifrost is a high-performance open-source AI gateway that unifies access to 20+ AI providers through a single OpenAI-compatible API. It supports 1,000+ models with adaptive load balancing, automatic failover, semantic caching, and enterprise observability features. Bifrost is open-source under Apache 2.0.
features:
- description: Single API interface compatible with OpenAI SDK for all 20+ providers.
  name: OpenAI-Compatible API
- description: Distribute requests across providers and models based on availability and performance.
  name: Adaptive Load Balancing
- description: Automatically retry failed requests on alternative providers without client changes.
  name: Automatic Failover
- description: Cache semantically similar prompts to reduce latency and API costs.
  name: Semantic Caching
- description: Model Context Protocol gateway for AI agent tool discovery and execution.
  name: MCP Gateway
- description: Native Go library for embedding Bifrost gateway directly into applications.
  name: Go SDK
- description: Built-in metrics, tracing, and logging for production AI gateway deployments.
  name: Enterprise Observability
- description: Centralized API key management for all connected AI providers.
  name: Provider Key Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Route to OpenAI GPT-4o, GPT-4, and other OpenAI models.
  name: OpenAI
- description: Route to Claude 3.5 Sonnet, Claude 3 Opus, and other Anthropic models.
  name: Anthropic
- description: Route to Cohere Command and other Cohere models.
  name: Cohere
- description: Route to models hosted on AWS Bedrock including Titan and Claude.
  name: AWS Bedrock
- description: Route to Azure-hosted OpenAI deployments.
  name: Azure OpenAI
- description: Route to Gemini and other models on Google Vertex AI.
  name: Google Vertex AI
jsonld:
- class_count: 8
  name: Bifrost Context
  property_count: 16
  slug: bifrost-context
layout: provider
modified: '2026-04-19'
name: Bifrost
rules:
- name: Bifrost API Rules
  rule_count: 24
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 17
  slug: bifrost-spectral-rules
skills: []
slug: bifrost
solutions: []
tags:
- AI Gateway
- LLM
- Load Balancing
- Open Source
- OpenAI Compatible
- MCP
url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/apis.yml
use_cases:
- description: Build applications that can seamlessly switch between OpenAI, Anthropic, and other providers.
  name: Multi-Provider AI Applications
- description: Route requests to cheaper providers during peak costs or use caching to reduce API spend.
  name: Cost Optimization
- description: Ensure AI features remain available by failing over across multiple provider accounts.
  name: High Availability AI
- description: Enable AI agents to discover and execute tools through the MCP gateway protocol.
  name: AI Agent Tooling
- description: A/B test different models and providers without changing application code.
  name: LLM Provider Evaluation
---
