---
api_count: 1
api_specs:
- filename: apipark-api.yaml
  format: yaml
  label: APIPark API
  slug: apipark-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/openapi/apipark-api.yaml
apis:
- description: The APIPark API provides programmatic access to manage the APIPark AI gateway and developer portal, including AI model integration, service management, team administration, and API publishing workflow
  name: APIPark API
  slug: apipark-api
capabilities:
- description: Manage services, AI models, teams, and subscribers across the APIPark developer platform
  name: Platform Management
  slug: platform-management
common:
- title: ''
  type: Website
  url: https://apipark.com/
- title: ''
  type: Documentation
  url: https://docs.apipark.com/docs/overview
- title: ''
  type: GitHubOrganization
  url: https://github.com/APIParkLab
- title: ''
  type: Blog
  url: https://apipark.com/blog
- title: ''
  type: ChangeLog
  url: https://docs.apipark.com/docs/release
created: '2025-03-01'
description: APIPark is an open-source, cloud-native AI gateway and API developer portal that helps developers and enterprises manage, integrate, and deploy AI and API services. It supports 100+ AI models from all major AI providers, provides API lifecycle management, authentication, rate limiting, and cluster deployment for large-scale traffic. Teams can combine AI models with custom prompts to create new AI-powered services such as sentiment analysis, translation, or data analysis.
features:
- description: Unified AI gateway supporting 100+ AI models from OpenAI, Anthropic, Google, Meta, Mistral, and other major providers.
  name: AI Gateway
- description: Combine AI models with custom system prompts to create new API services for specific use cases.
  name: Prompt Engineering
- description: Full-featured developer portal for publishing, discovering, and subscribing to API services.
  name: API Developer Portal
- description: Team-based multi-tenancy for separating API services and subscriptions across organizational units.
  name: Multi-Tenant Teams
- description: Complete API lifecycle from service creation through publication, subscription, and deprecation.
  name: API Lifecycle Management
- description: Built-in API key authentication, rate limiting, and traffic management for all published services.
  name: Rate Limiting and Authentication
- description: Cloud-native cluster deployment supporting large-scale production traffic with high availability.
  name: Cluster Deployment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Apipark Context
  property_count: 1
  slug: apipark-context
layout: provider
modified: '2026-04-19'
name: APIPark
skills: []
slug: apipark
solutions:
- description: Free, Apache 2.0 licensed self-hosted deployment for organizations with full control over infrastructure.
  name: Open Source
- description: Managed cloud deployment for teams who prefer not to manage infrastructure.
  name: Cloud
- description: Enterprise support, SLA guarantees, and professional services for large-scale deployments.
  name: Enterprise
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apipark\nname: APIPark\ndescription: >-\n  APIPark is an open-source, cloud-native AI gateway and API developer portal\n  that helps developers and enterprises manage, integrate, and deploy AI and\n  API services. It supports 100+ AI models from all major AI providers,\n  provides API lifecycle management, authentication, rate limiting, and cluster\n  deployment for large-scale traffic. Teams can combine AI models with custom\n  prompts to create new AI-powered services such as sentiment analysis,\n  translation, or data analysis.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Gateway\n  - API Gateway\n  - API Management\n  - Developer Portal\n  - LLM\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apipark:apipark-api\n    name: APIPark API\n    description:\
  \ >-\n      The APIPark API provides programmatic access to manage the APIPark AI gateway\n      and developer portal, including AI model integration, service management,\n      team administration, and API publishing workflows.\n    humanURL: https://apipark.com/\n    baseURL: https://api.apipark.com/v1\n    tags:\n      - AI Gateway\n      - API Gateway\n      - API Management\n      - Developer Portal\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://docs.apipark.com/docs/overview\n      - type: GitHubRepository\n        url: https://github.com/APIParkLab/APIPark\n      - type: ChangeLog\n        url: https://docs.apipark.com/docs/release\n      - type: OpenAPI\n        url: openapi/apipark-api.yaml\n      - type: JSONSchema\n        url: json-schema/apipark-service-schema.json\n      - type: JSONSchema\n        url: json-schema/apipark-ai-model-schema.json\n      - type: JSON-LD\n        url: json-ld/apipark-context.jsonld\ncommon:\n  - type: Website\n\
  \    url: https://apipark.com/\n  - type: Documentation\n    url: https://docs.apipark.com/docs/overview\n  - type: GitHubOrganization\n    url: https://github.com/APIParkLab\n  - type: Blog\n    url: https://apipark.com/blog\n  - type: ChangeLog\n    url: https://docs.apipark.com/docs/release\n  - type: Features\n    data:\n      - name: AI Gateway\n        description: Unified AI gateway supporting 100+ AI models from OpenAI, Anthropic, Google, Meta, Mistral, and other major providers.\n      - name: Prompt Engineering\n        description: Combine AI models with custom system prompts to create new API services for specific use cases.\n      - name: API Developer Portal\n        description: Full-featured developer portal for publishing, discovering, and subscribing to API services.\n      - name: Multi-Tenant Teams\n        description: Team-based multi-tenancy for separating API services and subscriptions across organizational units.\n      - name: API Lifecycle Management\n      \
  \  description: Complete API lifecycle from service creation through publication, subscription, and deprecation.\n      - name: Rate Limiting and Authentication\n        description: Built-in API key authentication, rate limiting, and traffic management for all published services.\n      - name: Cluster Deployment\n        description: Cloud-native cluster deployment supporting large-scale production traffic with high availability.\n  - type: UseCases\n    data:\n      - name: AI API Standardization\n        description: Standardize access to 100+ AI models through a unified API interface, enabling model switching without code changes.\n      - name: AI Service Creation\n        description: Combine AI models with custom prompts to create specialized AI-powered APIs for specific domains.\n      - name: Enterprise AI Governance\n        description: Govern AI model access, usage costs, and rate limits across multiple teams from a centralized portal.\n      - name: Internal API Marketplace\n\
  \        description: Build an internal API marketplace for teams to discover and subscribe to AI and traditional API services.\n  - type: Solutions\n    data:\n      - name: Open Source\n        description: Free, Apache 2.0 licensed self-hosted deployment for organizations with full control over infrastructure.\n      - name: Cloud\n        description: Managed cloud deployment for teams who prefer not to manage infrastructure.\n      - name: Enterprise\n        description: Enterprise support, SLA guarantees, and professional services for large-scale deployments.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/apis.yml
tags:
- AI Gateway
- API Gateway
- API Management
- Developer Portal
- LLM
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/apis.yml
use_cases:
- description: Standardize access to 100+ AI models through a unified API interface, enabling model switching without code changes.
  name: AI API Standardization
- description: Combine AI models with custom prompts to create specialized AI-powered APIs for specific domains.
  name: AI Service Creation
- description: Govern AI model access, usage costs, and rate limits across multiple teams from a centralized portal.
  name: Enterprise AI Governance
- description: Build an internal API marketplace for teams to discover and subscribe to AI and traditional API services.
  name: Internal API Marketplace
---
