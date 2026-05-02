---
api_count: 5
api_specs:
- filename: microsoft-azure-api-management-rest-api-openapi.yaml
  format: yaml
  label: Azure API Management REST API
  slug: azure-api-management-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-rest-api-openapi.yaml
- filename: microsoft-azure-api-management-gateway-openapi.yaml
  format: yaml
  label: Azure API Management Gateway
  slug: azure-api-management-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-gateway-openapi.yaml
- filename: microsoft-azure-api-management-self-hosted-gateway-openapi.yaml
  format: yaml
  label: Azure API Management Self-Hosted Gateway
  slug: azure-api-management-self-hosted-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-self-hosted-gateway-openapi.yaml
- filename: microsoft-azure-api-management-ai-gateway-openapi.yaml
  format: yaml
  label: Azure API Management AI Gateway
  slug: azure-api-management-ai-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-ai-gateway-openapi.yaml
- filename: microsoft-azure-api-management-developer-portal-openapi.yaml
  format: yaml
  label: Azure API Management Developer Portal
  slug: azure-api-management-developer-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-developer-portal-openapi.yaml
apis:
- description: The Azure API Management REST API provides programmatic access to manage API Management service instances and their entities, including APIs, products, subscriptions, users, groups, policies, gateways
  name: Azure API Management REST API
  slug: azure-api-management-rest-api
- description: The Azure API Management gateway (data plane) acts as a facade to backend services, routing API requests, enforcing policies, verifying credentials, applying rate limits and quotas, caching responses,
  name: Azure API Management Gateway
  slug: azure-api-management-gateway
- description: The Azure API Management self-hosted gateway is a containerized, Linux-based Docker image that can be deployed to Kubernetes, Docker, or any container orchestration platform in on-premises or other cl
  name: Azure API Management Self-Hosted Gateway
  slug: azure-api-management-self-hosted-gateway
- description: 'The Azure API Management AI gateway is a set of capabilities for managing, securing, scaling, and observing AI backends including Microsoft Foundry and Azure OpenAI deployments, OpenAI-compatible LLM '
  name: Azure API Management AI Gateway
  slug: azure-api-management-ai-gateway
- description: The Azure API Management developer portal is an automatically generated, fully customizable website that allows API consumers to discover APIs, read documentation, test APIs through an interactive con
  name: Azure API Management Developer Portal
  slug: azure-api-management-developer-portal
capabilities:
- description: Workflow capability for AI Engineers to manage AI backends and LLM deployments through Azure API Management. Covers proxying chat completions, completions, and embeddings to Azure OpenAI and compatibl
  name: AI Gateway Management
  slug: ai-gateway-management
- description: Workflow capability for API Platform Admins to manage the full API lifecycle including creating and versioning APIs, configuring policies, managing products and subscriptions, organizing with tags, an
  name: API Lifecycle Management
  slug: api-lifecycle-management
- description: Workflow capability for API Developers to discover, test, and subscribe to APIs through the developer portal and management plane. Covers user registration, API discovery, product subscription, API ke
  name: Developer Onboarding
  slug: developer-onboarding
- description: Workflow capability for DevOps Engineers to deploy, configure, and monitor API gateways including cloud-hosted and self-hosted gateways. Covers gateway provisioning, API routing, hostname configuratio
  name: Gateway Operations
  slug: gateway-operations
common:
- title: ''
  type: Website
  url: https://azure.microsoft.com/products/api-management/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/api-management/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance
- title: ''
  type: Quickstart
  url: https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance-cli
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/rest/api/apimanagement/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/pricing/details/api-management/
- title: ''
  type: Tiers
  url: https://learn.microsoft.com/en-us/azure/api-management/api-management-features
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/overview
- title: ''
  type: Support
  url: https://learn.microsoft.com/answers/tags/29/azure-api-management/
- title: ''
  type: Console
  url: https://portal.azure.com/
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/cli/azure/apim
- title: ''
  type: SDK
  url: https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/apimanagement
- title: ''
  type: Tutorials
  url: https://learn.microsoft.com/en-us/azure/api-management/import-and-publish
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/modules/explore-api-management/
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview
- title: ''
  type: BestPractices
  url: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-policies
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure/ct-p/Azure
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/api-management-samples
- title: ''
  type: GitHubOrganization
  url: https://github.com/Azure
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: Regions
  url: https://azure.microsoft.com/explore/global-infrastructure/products-by-region/
- title: ''
  type: Compliance
  url: https://learn.microsoft.com/en-us/azure/compliance/
- title: ''
  type: TrustCenter
  url: https://www.microsoft.com/trust-center
- title: ''
  type: SignUp
  url: https://azure.microsoft.com/free/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: DeveloperPortal
  url: https://learn.microsoft.com/en-us/azure/api-management/developer-portal-overview
- title: ''
  type: SDK
  url: https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/apimanagement
- title: ''
  type: SDK
  url: https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/apimanagement
- title: ''
  type: SDK
  url: https://github.com/Azure/azure-sdk-for-js/tree/main/sdk/apimanagement
- title: ''
  type: SDK
  url: https://github.com/Azure/azure-sdk-for-go/tree/main/sdk/resourcemanager/apimanagement
- title: ''
  type: CodeExamples
  url: https://github.com/Azure/api-management-samples
- title: ''
  type: PolicySnippets
  url: https://github.com/Azure/api-management-policy-snippets
- title: ''
  type: Tools
  url: https://github.com/Azure/azure-api-management-policy-toolkit
- title: ''
  type: ChangeLog
  url: https://github.com/Azure/API-Management/blob/master/changelogs/api-management-service.md
- title: ''
  type: SpectralRules
  url: rules/microsoft-azure-api-management-rules.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-azure-api-management-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ai-gateway-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-lifecycle-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/developer-onboarding.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/gateway-operations.yaml
created: '2026-03-16'
description: Microsoft Azure API Management is a hybrid, multicloud management platform for APIs across all environments. It provides an API gateway, management plane, and developer portal supporting the complete API lifecycle including publishing, securing, monitoring, and transforming APIs for external, partner, and internal developers. It includes an AI gateway for governing LLM deployments, MCP servers, and agentic AI workloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Azure Api Management Ai Gateway Context
  property_count: 8
  slug: microsoft-azure-api-management-ai-gateway-context
layout: provider
modified: '2026-04-28'
name: Microsoft Azure API Management
rules:
- name: Microsoft Azure API Management API Rules
  rule_count: 15
  severity_counts:
    error: 1
    hint: 0
    info: 8
    warn: 6
  slug: microsoft-azure-api-management-rules
skills: []
slug: microsoft-azure-api-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-azure-api-management\nname: Microsoft Azure API Management\ndescription: >-\n  Microsoft Azure API Management is a hybrid, multicloud management platform\n  for APIs across all environments. It provides an API gateway, management\n  plane, and developer portal supporting the complete API lifecycle including\n  publishing, securing, monitoring, and transforming APIs for external, partner,\n  and internal developers. It includes an AI gateway for governing LLM\n  deployments, MCP servers, and agentic AI workloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Gateway\n  - API Gateway\n  - API Management\n  - Enterprise\n  - Microsoft Azure\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-azure-api-management:azure-api-management-rest-api\n\
  \    name: Azure API Management REST API\n    description: >-\n      The Azure API Management REST API provides programmatic access to manage\n      API Management service instances and their entities, including APIs,\n      products, subscriptions, users, groups, policies, gateways, backends,\n      certificates, and workspaces. It uses Azure Resource Manager conventions\n      and supports API versions up to 2024-05-01 with over 100 operation groups\n      covering the full management plane.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n    baseURL: https://management.azure.com/\n    tags:\n      - Azure Resource Manager\n      - Configuration\n      - Management Plane\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/apimanagement/operation-groups\n      - type: Authentication\n        url:\
  \ https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview\n      - type: SDK\n        url: https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/apimanagement\n      - type: SDK\n        url: https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/apimanagement\n      - type: SDK\n        url: https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/apimanagement\n      - type: SDK\n        url: https://github.com/Azure/azure-sdk-for-js/tree/main/sdk/apimanagement\n      - type: SDK\n        url: https://github.com/Azure/azure-sdk-for-go/tree/main/sdk/resourcemanager/apimanagement\n      - type: OpenAPI\n        url: openapi/microsoft-azure-api-management-rest-api-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/shared/rest-api.yaml\n  - aid: microsoft-azure-api-management:azure-api-management-gateway\n    name: Azure API Management Gateway\n    description: >-\n      The Azure API Management gateway (data plane) acts\
  \ as a facade to backend\n      services, routing API requests, enforcing policies, verifying credentials,\n      applying rate limits and quotas, caching responses, and emitting telemetry.\n      It supports managed cloud-hosted and self-hosted containerized deployments\n      for hybrid and multicloud environments.\n    humanURL: https://learn.microsoft.com/en-us/azure/api-management/api-management-key-concepts\n    baseURL: https://azure-api.net\n    tags:\n      - API Gateway\n      - Policies\n      - Proxy\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/api-management/api-management-key-concepts\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/azure/api-management/api-management-policies\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/api-management/import-and-publish\n\
  \      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/azure/api-management/transform-api\n      - type: PolicySnippets\n        url: https://github.com/Azure/api-management-policy-snippets\n      - type: Tools\n        url: https://github.com/Azure/azure-api-management-policy-toolkit\n      - type: OpenAPI\n        url: openapi/microsoft-azure-api-management-gateway-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/shared/gateway.yaml\n  - aid: microsoft-azure-api-management:azure-api-management-self-hosted-gateway\n    name: Azure API Management Self-Hosted Gateway\n    description: >-\n      The Azure API Management self-hosted gateway is a containerized,\n      Linux-based Docker image that can be deployed to Kubernetes, Docker, or\n      any container orchestration platform in on-premises or other cloud\n      environments. It federates with a cloud-based API Management instance for\n      centralized configuration and management while routing\
  \ API traffic locally\n      to reduce latency and address compliance requirements.\n    humanURL: https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-overview\n    baseURL: https://mcr.microsoft.com/product/azure-api-management/gateway\n    tags:\n      - Hybrid\n      - Kubernetes\n      - On-Premises\n      - Self-Hosted\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-azure-kubernetes-service\n      - type: GitHubRepository\n        url: https://github.com/Azure/api-management-self-hosted-gateway\n      - type: HelmChart\n        url: https://github.com/Azure/api-management-self-hosted-gateway/tree/main/helm-charts/azure-api-management-gateway\n      - type: CodeExamples\n        url: https://github.com/Azure/api-management-self-hosted-gateway-ingress\n\
  \      - type: OpenAPI\n        url: openapi/microsoft-azure-api-management-self-hosted-gateway-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/shared/self-hosted-gateway.yaml\n  - aid: microsoft-azure-api-management:azure-api-management-ai-gateway\n    name: Azure API Management AI Gateway\n    description: >-\n      The Azure API Management AI gateway is a set of capabilities for managing,\n      securing, scaling, and observing AI backends including Microsoft Foundry\n      and Azure OpenAI deployments, OpenAI-compatible LLM endpoints, MCP\n      servers, and A2A agent APIs. It provides token rate limiting and quotas,\n      semantic caching, load balancing across AI backends, content safety\n      enforcement, and token usage observability through Application Insights.\n    humanURL: https://learn.microsoft.com/en-us/azure/api-management/genai-gateway-capabilities\n    baseURL: https://management.azure.com/\n    tags:\n      - AI Gateway\n      - Azure OpenAI\n\
  \      - LLM\n      - MCP\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/api-management/genai-gateway-capabilities\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/api-management/azure-openai-api-from-specification\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/api-management/azure-ai-foundry-api\n      - type: OpenAPI\n        url: openapi/microsoft-azure-api-management-ai-gateway-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/ai-gateway-chat-completion-request-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-chat-completion-response-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-completion-request-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-completion-response-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-embedding-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/ai-gateway-embedding-response-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-mcp-request-schema.json\n      - type: JSONSchema\n        url: json-schema/ai-gateway-mcp-response-schema.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-chat-completion-request-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-chat-completion-response-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-completion-request-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-completion-response-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-embedding-request-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-embedding-response-structure.json\n      - type: JSONStructure\n        url: json-structure/ai-gateway-mcp-request-structure.json\n    \
  \  - type: JSONStructure\n        url: json-structure/ai-gateway-mcp-response-structure.json\n      - type: JSONLD\n        url: json-ld/microsoft-azure-api-management-ai-gateway-context.jsonld\n      - type: Example\n        url: examples/ai-gateway-chat-completion-request-example.json\n      - type: Example\n        url: examples/ai-gateway-chat-completion-response-example.json\n      - type: Example\n        url: examples/ai-gateway-completion-request-example.json\n      - type: Example\n        url: examples/ai-gateway-completion-response-example.json\n      - type: Example\n        url: examples/ai-gateway-embedding-request-example.json\n      - type: Example\n        url: examples/ai-gateway-embedding-response-example.json\n      - type: Example\n        url: examples/ai-gateway-mcp-request-example.json\n      - type: Example\n        url: examples/ai-gateway-mcp-response-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/ai-gateway.yaml\n  - aid: microsoft-azure-api-management:azure-api-management-developer-portal\n\
  \    name: Azure API Management Developer Portal\n    description: >-\n      The Azure API Management developer portal is an automatically generated,\n      fully customizable website that allows API consumers to discover APIs,\n      read documentation, test APIs through an interactive console, create\n      accounts, subscribe to API products, and manage API keys. It can be\n      self-hosted and extended with custom content and branding.\n    humanURL: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-developer-portal-customize\n    baseURL: https://developer.azure-api.net\n    tags:\n      - API Discovery\n      - Developer Portal\n      - Documentation\n      - Self-Service\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-developer-portal-customize\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-developer-portal-customize\n\
  \      - type: GitHubRepository\n        url: https://github.com/Azure/api-management-developer-portal\n      - type: OpenAPI\n        url: openapi/microsoft-azure-api-management-developer-portal-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/shared/developer-portal.yaml\ncommon:\n  - type: Website\n    url: https://azure.microsoft.com/products/api-management/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/api-management/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance\n  - type: Quickstart\n    url: https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance-cli\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview\n  - type: Pricing\n    url: https://azure.microsoft.com/pricing/details/api-management/\n\
  \  - type: Tiers\n    url: https://learn.microsoft.com/en-us/azure/api-management/api-management-features\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/overview\n  - type: Support\n    url: https://learn.microsoft.com/answers/tags/29/azure-api-management/\n  - type: Console\n    url: https://portal.azure.com/\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/cli/azure/apim\n  - type: SDK\n    url: https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/apimanagement\n  - type: Tutorials\n    url: https://learn.microsoft.com/en-us/azure/api-management/import-and-publish\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/modules/explore-api-management/\n  - type: Security\n    url: https://learn.microsoft.com/en-us/azure/api-management/authentication-authorization-overview\n  - type: BestPractices\n    url: https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-policies\n  - type:\
  \ Blog\n    url: https://techcommunity.microsoft.com/t5/azure/ct-p/Azure\n  - type: GitHubRepository\n    url: https://github.com/Azure/api-management-samples\n  - type: GitHubOrganization\n    url: https://github.com/Azure\n  - type: TermsOfService\n    url: https://azure.microsoft.com/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/privacystatement\n  - type: Regions\n    url: https://azure.microsoft.com/explore/global-infrastructure/products-by-region/\n  - type: Compliance\n    url: https://learn.microsoft.com/en-us/azure/compliance/\n  - type: TrustCenter\n    url: https://www.microsoft.com/trust-center\n  - type: SignUp\n    url: https://azure.microsoft.com/free/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: DeveloperPortal\n    url: https://learn.microsoft.com/en-us/azure/api-management/developer-portal-overview\n  - type: SDK\n    url: https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/apimanagement\n  - type: SDK\n \
  \   url: https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/apimanagement\n  - type: SDK\n    url: https://github.com/Azure/azure-sdk-for-js/tree/main/sdk/apimanagement\n  - type: SDK\n    url: https://github.com/Azure/azure-sdk-for-go/tree/main/sdk/resourcemanager/apimanagement\n  - type: CodeExamples\n    url: https://github.com/Azure/api-management-samples\n  - type: PolicySnippets\n    url: https://github.com/Azure/api-management-policy-snippets\n  - type: Tools\n    url: https://github.com/Azure/azure-api-management-policy-toolkit\n  - type: ChangeLog\n    url: https://github.com/Azure/API-Management/blob/master/changelogs/api-management-service.md\n  - type: SpectralRules\n    url: rules/microsoft-azure-api-management-rules.yaml\n  - type: Vocabulary\n    url: vocabulary/microsoft-azure-api-management-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/ai-gateway-management.yaml\n  - type: NaftikoCapability\n    url: capabilities/api-lifecycle-management.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/developer-onboarding.yaml\n  - type: NaftikoCapability\n    url: capabilities/gateway-operations.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/apis.yml
tags:
- AI Gateway
- API Gateway
- API Management
- Enterprise
- Microsoft Azure
url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/apis.yml
use_cases: []
---
