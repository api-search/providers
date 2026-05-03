---
api_count: 8
api_specs:
- filename: wso2-publisher-api.yaml
  format: yaml
  label: WSO2 Publisher API
  slug: publisher-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-publisher-api.yaml
- filename: wso2-devportal-api.yaml
  format: yaml
  label: WSO2 Developer Portal API
  slug: devportal-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-devportal-api.yaml
- filename: wso2-admin-api.yaml
  format: yaml
  label: WSO2 Admin Portal API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-admin-api.yaml
- filename: wso2-gateway-api.yaml
  format: yaml
  label: WSO2 Gateway API
  slug: gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-gateway-api.yaml
- filename: wso2-service-catalog-api.yaml
  format: yaml
  label: WSO2 Service Catalog API
  slug: service-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-service-catalog-api.yaml
- filename: wso2-devops-api.yaml
  format: yaml
  label: WSO2 DevOps API
  slug: devops-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-devops-api.yaml
- filename: wso2-dcr-api.yaml
  format: yaml
  label: WSO2 DCR API
  slug: dcr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-dcr-api.yaml
- filename: wso2-governance-api.yaml
  format: yaml
  label: WSO2 Governance API
  slug: governance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/openapi/wso2-governance-api.yaml
apis:
- description: The WSO2 API Manager Publisher API enables programmatic management of APIs within the WSO2 API Manager Publisher portal. It provides RESTful endpoints for creating, designing, implementing, versioning
  name: WSO2 Publisher API
  slug: publisher-api
- description: The WSO2 API Manager Developer Portal API handles API discovery, application management, subscriptions, and access token generation. It enables consumption workflows for developers to discover, explor
  name: WSO2 Developer Portal API
  slug: devportal-api
- description: The WSO2 API Manager Admin Portal API manages users, roles, policies, and system configurations. It provides administrative control over subscription tiers, application policies, advanced throttling p
  name: WSO2 Admin Portal API
  slug: admin-api
- description: The WSO2 API Manager Gateway API provides gateway deployment and management capabilities. It handles API deployment across multiple gateway environments and provides endpoints for managing gateway-lev
  name: WSO2 Gateway API
  slug: gateway-api
- description: The WSO2 API Manager Service Catalog API manages service discovery and cataloging. It enables developers to register their backend services in a RESTful manner and supports the API-first integration a
  name: WSO2 Service Catalog API
  slug: service-catalog-api
- description: The WSO2 API Manager DevOps API supports continuous deployment and operations workflows. It provides endpoints for managing API deployments, logging, and operational tasks in DevOps pipelines.
  name: WSO2 DevOps API
  slug: devops-api
- description: The WSO2 API Manager Dynamic Client Registration (DCR) API enables OAuth2 client applications to register themselves programmatically with the WSO2 Identity Server key manager. It follows the OpenID C
  name: WSO2 DCR API
  slug: dcr-api
- description: The WSO2 API Manager Governance API provides endpoints for managing governance policies, rulesets, and API compliance. It enables teams to define and enforce API design standards, assess policy adhere
  name: WSO2 Governance API
  slug: governance-api
common:
- title: ''
  type: Website
  url: https://wso2.com/api-manager/
- title: ''
  type: Documentation
  url: https://apim.docs.wso2.com/en/latest/
- title: ''
  type: GettingStarted
  url: https://apim.docs.wso2.com/en/latest/get-started/api-manager-quick-start-guide/
- title: ''
  type: Blog
  url: https://wso2.com/library/blogs/
- title: ''
  type: Pricing
  url: https://wso2.com/api-platform/pricing/
- title: ''
  type: About
  url: https://wso2.com/about/
- title: ''
  type: GitHubOrg
  url: https://github.com/wso2
- title: ''
  type: TermsOfService
  url: https://wso2.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://wso2.com/privacy-policy/
- title: ''
  type: Support
  url: https://apim.docs.wso2.com/en/latest/reference/faq/
- title: ''
  type: Authentication
  url: https://apim.docs.wso2.com/en/latest/api-security/
- title: ''
  type: ChangeLog
  url: https://apim.docs.wso2.com/en/latest/get-started/overview/whats-new/
- title: ''
  type: StatusPage
  url: https://status.wso2.com/
- title: ''
  type: Community
  url: https://stackoverflow.com/questions/tagged/wso2
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/wso2
- title: ''
  type: GitHubRepository
  url: https://github.com/wso2/product-apim
- title: ''
  type: SpectralRules
  url: rules/wso2-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-lifecycle-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-governance.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/wso2-vocabulary.yaml
created: '2026-03-03'
description: WSO2 API Manager is an open-source API management platform supporting REST, SOAP, and GraphQL with flexible hybrid deployment. It provides a unified control plane for managing APIs, AI models, and agents across on-premises, hybrid, and cloud environments. WSO2 is recognized as a Leader in the Forrester Wave API Management Q3 2024 report.
features:
- description: Design, publish, deprecate, and retire APIs across the full lifecycle.
  name: Full API Lifecycle Management
- description: Manages REST, GraphQL, gRPC, WebSocket, and Webhook APIs.
  name: Multi-Protocol Support
- description: Routes and manages LLM traffic with guardrails and PII masking.
  name: AI Gateway
- description: Converts REST APIs into Model Context Protocol tools for AI agents.
  name: MCP Gateway
- description: Policy enforcement and compliance checking across API designs.
  name: API Governance
- description: Programmatic OAuth2 client registration following OpenID Connect DCR spec.
  name: Dynamic Client Registration
- description: Subscription tiers, application policies, and advanced rate limiting.
  name: Advanced Throttling
- description: Real-time traffic analytics and usage insights via Moesif integration.
  name: Analytics
- description: Auto-generates client SDKs in multiple languages from API definitions.
  name: SDK Generation
- description: Registers and discovers backend services for API-first integration.
  name: Service Catalog
- description: CI/CD pipeline integration for automated API deployment.
  name: DevOps Integration
- description: Manages APIs across WSO2, Kong, AWS, Azure, and Envoy gateways.
  name: Multi-Gateway Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AI Gateway supports routing to OpenAI models.
  name: OpenAI
- description: AI Gateway supports routing to Anthropic Claude models.
  name: Anthropic
- description: AI Gateway integrates with Azure OpenAI deployment.
  name: Azure OpenAI
- description: Multi-gateway management includes Kong.
  name: Kong Gateway
- description: Multi-gateway management includes AWS API Gateway.
  name: AWS API Gateway
- description: Analytics integration powered by Moesif.
  name: Moesif
- description: Native Kubernetes deployment support.
  name: Kubernetes
- description: Identity provider integration for OAuth2 flows.
  name: Keycloak
layout: provider
modified: '2026-05-03'
name: WSO2
skills: []
slug: wso2
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wso2\nname: WSO2\nsegments:\n  - Gateways\ndescription: >-\n  WSO2 API Manager is an open-source API management platform supporting REST,\n  SOAP, and GraphQL with flexible hybrid deployment. It provides a unified\n  control plane for managing APIs, AI models, and agents across on-premises,\n  hybrid, and cloud environments. WSO2 is recognized as a Leader in the\n  Forrester Wave API Management Q3 2024 report.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Gateways\n  - Open Source\n  - API Lifecycle\n  - GraphQL\n  - SOAP\n  - REST\ncreated: '2026-03-03'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: wso2:publisher-api\n    name: WSO2 Publisher API\n    description: >-\n      The WSO2 API Manager Publisher API enables programmatic management of\
  \ APIs\n      within the WSO2 API Manager Publisher portal. It provides RESTful endpoints\n      for creating, designing, implementing, versioning, and managing APIs\n      through the full API lifecycle including design, publish, and deprecate.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/publisher-apis/publisher-v4/publisher-v4/\n    tags:\n      - API Management\n      - Lifecycle\n      - Publisher\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/publisher-apis/publisher-v4/publisher-v4/\n      - type: OpenAPI\n        url: openapi/wso2-publisher-api.yaml\n\n  - aid: wso2:devportal-api\n    name: WSO2 Developer Portal API\n    description: >-\n      The WSO2 API Manager Developer Portal API handles API discovery,\n      application management, subscriptions, and access token generation. It\n      enables consumption workflows for developers to discover, explore,\n      subscribe to,\
  \ and consume APIs.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/devportal-apis/devportal-v3/devportal-v3/\n    tags:\n      - Developer Portal\n      - Discovery\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/devportal-apis/devportal-v3/devportal-v3/\n      - type: OpenAPI\n        url: openapi/wso2-devportal-api.yaml\n\n  - aid: wso2:admin-api\n    name: WSO2 Admin Portal API\n    description: >-\n      The WSO2 API Manager Admin Portal API manages users, roles, policies, and\n      system configurations. It provides administrative control over subscription\n      tiers, application policies, advanced throttling policies, and system-wide\n      settings.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/admin-apis/admin-v4/admin-v4/\n    tags:\n      - Administration\n      - Configuration\n      - Policies\n    properties:\n      - type:\
  \ Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/admin-apis/admin-v4/admin-v4/\n      - type: OpenAPI\n        url: openapi/wso2-admin-api.yaml\n\n  - aid: wso2:gateway-api\n    name: WSO2 Gateway API\n    description: >-\n      The WSO2 API Manager Gateway API provides gateway deployment and\n      management capabilities. It handles API deployment across multiple gateway\n      environments and provides endpoints for managing gateway-level operations.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/gateway-apis/gateway-v2/gateway-v2/\n    tags:\n      - Deployment\n      - Gateway\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/gateway-apis/gateway-v2/gateway-v2/\n      - type: OpenAPI\n        url: openapi/wso2-gateway-api.yaml\n\n  - aid: wso2:service-catalog-api\n    name: WSO2 Service Catalog API\n    description:\
  \ >-\n      The WSO2 API Manager Service Catalog API manages service discovery and\n      cataloging. It enables developers to register their backend services in a\n      RESTful manner and supports the API-first integration approach in WSO2 API\n      Manager.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/service-catalog-apis/service-catalog-v1/service-catalog-v1/\n    tags:\n      - Discovery\n      - Integration\n      - Service Catalog\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/service-catalog-apis/service-catalog-v1/service-catalog-v1/\n      - type: OpenAPI\n        url: openapi/wso2-service-catalog-api.yaml\n\n  - aid: wso2:devops-api\n    name: WSO2 DevOps API\n    description: >-\n      The WSO2 API Manager DevOps API supports continuous deployment and\n      operations workflows. It provides endpoints for managing API deployments,\n      logging, and operational tasks in\
  \ DevOps pipelines.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/devops-apis/devops-v0/devops-v0/\n    tags:\n      - Deployment\n      - DevOps\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/devops-apis/devops-v0/devops-v0/\n      - type: OpenAPI\n        url: openapi/wso2-devops-api.yaml\n\n  - aid: wso2:dcr-api\n    name: WSO2 DCR API\n    description: >-\n      The WSO2 API Manager Dynamic Client Registration (DCR) API enables\n      OAuth2 client applications to register themselves programmatically with\n      the WSO2 Identity Server key manager. It follows the OpenID Connect\n      Dynamic Client Registration specification and is used to automate\n      application onboarding for API access.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/\n    baseURL: https://apis.wso2.com\n    tags:\n      - Client Registration\n      - Identity\n\
  \      - OAuth2\n      - Security\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/\n      - type: OpenAPI\n        url: openapi/wso2-dcr-api.yaml\n\n  - aid: wso2:governance-api\n    name: WSO2 Governance API\n    description: >-\n      The WSO2 API Manager Governance API provides endpoints for managing\n      governance policies, rulesets, and API compliance. It enables teams to\n      define and enforce API design standards, assess policy adherence, and\n      validate artifact compliance across the API lifecycle.\n    humanURL: https://apim.docs.wso2.com/en/latest/reference/product-apis/governance-apis/governance-v1/governance-v1/\n    baseURL: https://apis.wso2.com\n    tags:\n      - API Management\n      - Compliance\n      - Governance\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://apim.docs.wso2.com/en/latest/reference/product-apis/governance-apis/governance-v1/governance-v1/\n\
  \      - type: OpenAPI\n        url: openapi/wso2-governance-api.yaml\n\ncommon:\n  - type: Website\n    name: WSO2 API Manager\n    url: https://wso2.com/api-manager/\n  - type: Documentation\n    name: Documentation\n    url: https://apim.docs.wso2.com/en/latest/\n  - type: GettingStarted\n    name: Quick Start Guide\n    url: https://apim.docs.wso2.com/en/latest/get-started/api-manager-quick-start-guide/\n  - type: Blog\n    name: Blog\n    url: https://wso2.com/library/blogs/\n  - type: Pricing\n    name: Pricing\n    url: https://wso2.com/api-platform/pricing/\n  - type: About\n    name: About WSO2\n    url: https://wso2.com/about/\n  - type: GitHubOrg\n    name: GitHub\n    url: https://github.com/wso2\n  - type: TermsOfService\n    name: Terms of Use\n    url: https://wso2.com/terms-of-use/\n  - type: PrivacyPolicy\n    name: Privacy Policy\n    url: https://wso2.com/privacy-policy/\n  - type: Support\n    name: FAQ\n    url: https://apim.docs.wso2.com/en/latest/reference/faq/\n\
  \  - type: Authentication\n    name: Authentication Overview\n    url: https://apim.docs.wso2.com/en/latest/api-security/\n  - type: ChangeLog\n    name: What's New\n    url: https://apim.docs.wso2.com/en/latest/get-started/overview/whats-new/\n  - type: StatusPage\n    name: WSO2 Status Page\n    url: https://status.wso2.com/\n  - type: Community\n    name: WSO2 Community Forum\n    url: https://stackoverflow.com/questions/tagged/wso2\n  - type: StackOverflow\n    name: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/wso2\n  - type: GitHubRepository\n    name: WSO2 API Manager GitHub\n    url: https://github.com/wso2/product-apim\n  - type: SpectralRules\n    name: WSO2 Spectral Rules\n    url: rules/wso2-rules.yml\n  - type: NaftikoCapability\n    name: WSO2 API Lifecycle Management Capability\n    url: capabilities/api-lifecycle-management.yaml\n  - type: NaftikoCapability\n    name: WSO2 API Governance Capability\n    url: capabilities/api-governance.yaml\n  - type:\
  \ Vocabulary\n    name: WSO2 Vocabulary\n    url: vocabulary/wso2-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Full API Lifecycle Management\n        description: Design, publish, deprecate, and retire APIs across the full lifecycle.\n      - name: Multi-Protocol Support\n        description: Manages REST, GraphQL, gRPC, WebSocket, and Webhook APIs.\n      - name: AI Gateway\n        description: Routes and manages LLM traffic with guardrails and PII masking.\n      - name: MCP Gateway\n        description: Converts REST APIs into Model Context Protocol tools for AI agents.\n      - name: API Governance\n        description: Policy enforcement and compliance checking across API designs.\n      - name: Dynamic Client Registration\n        description: Programmatic OAuth2 client registration following OpenID Connect DCR spec.\n      - name: Advanced Throttling\n        description: Subscription tiers, application policies, and advanced rate limiting.\n      - name: Analytics\n\
  \        description: Real-time traffic analytics and usage insights via Moesif integration.\n      - name: SDK Generation\n        description: Auto-generates client SDKs in multiple languages from API definitions.\n      - name: Service Catalog\n        description: Registers and discovers backend services for API-first integration.\n      - name: DevOps Integration\n        description: CI/CD pipeline integration for automated API deployment.\n      - name: Multi-Gateway Support\n        description: Manages APIs across WSO2, Kong, AWS, Azure, and Envoy gateways.\n  - type: UseCases\n    data:\n      - name: API Program Management\n        description: Centrally manage the full lifecycle of all enterprise APIs.\n      - name: Developer Self-Service\n        description: Developer portal for API discovery, subscription, and key management.\n      - name: AI Agent Integration\n        description: Expose REST APIs as MCP tools for AI and agent consumption.\n      - name: LLM Traffic Management\n\
  \        description: Route, monitor, and govern traffic to large language model APIs.\n      - name: Compliance and Governance\n        description: Enforce API design standards and validate compliance across teams.\n      - name: B2B API Monetization\n        description: Define subscription tiers and billing for API usage-based monetization.\n  - type: Integrations\n    data:\n      - name: OpenAI\n        description: AI Gateway supports routing to OpenAI models.\n      - name: Anthropic\n        description: AI Gateway supports routing to Anthropic Claude models.\n      - name: Azure OpenAI\n        description: AI Gateway integrates with Azure OpenAI deployment.\n      - name: Kong Gateway\n        description: Multi-gateway management includes Kong.\n      - name: AWS API Gateway\n        description: Multi-gateway management includes AWS API Gateway.\n      - name: Moesif\n        description: Analytics integration powered by Moesif.\n      - name: Kubernetes\n        description:\
  \ Native Kubernetes deployment support.\n      - name: Keycloak\n        description: Identity provider integration for OAuth2 flows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/apis.yml
tags:
- API Management
- Gateways
- Open Source
- API Lifecycle
- GraphQL
- SOAP
- REST
url: https://raw.githubusercontent.com/api-evangelist/wso2/refs/heads/main/apis.yml
use_cases:
- description: Centrally manage the full lifecycle of all enterprise APIs.
  name: API Program Management
- description: Developer portal for API discovery, subscription, and key management.
  name: Developer Self-Service
- description: Expose REST APIs as MCP tools for AI and agent consumption.
  name: AI Agent Integration
- description: Route, monitor, and govern traffic to large language model APIs.
  name: LLM Traffic Management
- description: Enforce API design standards and validate compliance across teams.
  name: Compliance and Governance
- description: Define subscription tiers and billing for API usage-based monetization.
  name: B2B API Monetization
---
