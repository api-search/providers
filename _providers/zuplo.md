---
api_count: 1
api_specs:
- filename: zuplo-openapi.yml
  format: yaml
  label: Zuplo Developer API
  slug: zuplo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/openapi/zuplo-openapi.yml
apis:
- description: The Zuplo Developer API (ZAPI) enables developers to programmatically manage API keys, consumers, buckets, tunnels, deployments, metering, audit logs, and more. It is used to perform management action
  name: Zuplo Developer API
  slug: zuplo
capabilities:
- description: Unified API management workflow combining API key lifecycle management, consumer administration, deployment management, and tunnel configuration. Used by platform engineers and API product teams to pr
  name: Zuplo API Management
  slug: api-management
common:
- title: ''
  type: Documentation
  url: https://zuplo.com/docs/articles/what-is-zuplo
- title: ''
  type: Pricing
  url: https://zuplo.com/pricing
- title: ''
  type: Blog
  url: https://zuplo.com/blog
- title: ''
  type: Login
  url: https://auth.zuplo.com/u/login/identifier
- title: ''
  type: SignUp
  url: https://auth.zuplo.com/u/signup/identifier
- title: ''
  type: Support
  url: https://zuplo.com/docs/articles/support
- title: ''
  type: Customers
  url: https://zuplo.com/resources
- title: ''
  type: ChangeLog
  url: https://zuplo.com/changelog
- title: ''
  type: About
  url: https://zuplo.com/about
- title: ''
  type: Status
  url: https://status.zuplo.com/
- title: ''
  type: PrivacyPolicy
  url: https://zuplo.com/legal/privacy-policy
- title: ''
  type: TermsOfService
  url: https://zuplo.com/legal/terms
- title: ''
  type: Security
  url: https://zuplo.com/legal/security-policy
- title: ''
  type: Trust
  url: https://trust.zuplo.com/
- title: ''
  type: GettingStarted
  url: https://zuplo.com/docs
- title: ''
  type: LearningCenter
  url: https://zuplo.com/learning-center
- title: ''
  type: DeveloperPortal
  url: https://zuplo.com/features/developer-portal
- title: ''
  type: APIManagement
  url: https://zuplo.com/features/api-management
- title: ''
  type: RateLimiting
  url: https://zuplo.com/features/rate-limiting
- title: ''
  type: APIKeyManagement
  url: https://zuplo.com/features/api-key-management
- title: ''
  type: Monetization
  url: https://zuplo.com/features/api-monetization
- title: ''
  type: APISecurity
  url: https://zuplo.com/features/api-security
- title: ''
  type: Governance
  url: https://zuplo.com/features/api-governance
- title: ''
  type: OpenAPI
  url: https://zuplo.com/features/open-api
- title: ''
  type: GitOps
  url: https://zuplo.com/features/gitops
- title: ''
  type: MultiCloud
  url: https://zuplo.com/features/multi-cloud
- title: ''
  type: Environments
  url: https://zuplo.com/features/unlimited-environments
- title: ''
  type: SelfService
  url: https://zuplo.com/features/self-serve-devx
- title: ''
  type: AIGateway
  url: https://zuplo.com/features/ai-gateway
- title: ''
  type: MCPServers
  url: https://zuplo.com/mcp-servers
- title: ''
  type: GitHub
  url: https://github.com/zuplo
- title: ''
  type: GitHubRepo
  url: https://github.com/zuplo/zuplo
- title: ''
  type: GitHubRepo
  url: https://github.com/zuplo/zudoku
- title: ''
  type: GitHubRepo
  url: https://github.com/zuplo/rate-my-openapi
- title: ''
  type: X
  url: https://x.com/zuplo
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/zuplo
- title: ''
  type: Discord
  url: https://discord.com/invite/stPRhjbA55
- title: ''
  type: Careers
  url: https://zuplo.com/careers
- title: ''
  type: HelpCenter
  url: https://zuplo.com/support
- title: ''
  type: Overview
  url: https://zuplo.com/api-management
created: '2025-01-08'
description: Zuplo is the API management platform for developers. Build, deploy, and scale APIs faster with Zuplo.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Zuplo Context
  property_count: 0
  slug: zuplo-context
layout: provider
modified: '2026-05-03'
name: Zuplo
rules:
- name: Zuplo API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: zuplo-rules
skills: []
slug: zuplo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zuplo\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/apis.yml\napis:\n  - aid: zuplo:zuplo\n    name: Zuplo Developer API\n    tags:\n      - API Keys\n      - API Management\n      - Gateways\n    baseURL: https://dev.zuplo.com\n    humanURL: https://zuplo.com/docs/articles/developer-api\n    properties:\n      - url: https://zuplo.com/docs/articles/developer-api\n        type: Documentation\n      - url: https://zuplo.com/docs/api\n        type: APIReference\n      - url: https://zuplo.com/docs/api/~endpoints\n        type: APIEndpoints\n      - url: openapi/zuplo-openapi.yml\n        type: OpenAPI\n      - url: rules/zuplo-rules.yml\n        type: SpectralRules\n      - url: capabilities/api-management.yaml\n        type: NaftikoCapabilities\n      - url: json-schema/zuplo-api-key-schema.json\n        type: JSONSchema\n      - url: json-schema/zuplo-consumer-schema.json\n        type: JSONSchema\n      - url: json-schema/zuplo-tunnel-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/zuplo-deployment-schema.json\n        type: JSONSchema\n      - url: json-ld/zuplo-context.jsonld\n        type: JSONLDContext\n      - url: vocabulary/zuplo-vocabulary.yml\n        type: Vocabulary\n      - url: https://zuplo.com/docs/articles/api-key-api\n        type: GettingStarted\n    description: >-\n      The Zuplo Developer API (ZAPI) enables developers to programmatically\n      manage API keys, consumers, buckets, tunnels, deployments, metering, audit\n      logs, and more. It is used to perform management actions on your Zuplo\n      account and integrations.\nname: Zuplo\ntags:\n  - AI Gateway\n  - API Management\n  - Gateways\n  - Platform\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://zuplo.com/docs/articles/what-is-zuplo\n    name: What is Zuplo? - Zuplo Docs\n    type: Documentation\n    description: 'null'\n  - url: https://zuplo.com/pricing\n\
  \    name: Affordable Plans for Every Team | Zuplo\n    type: Pricing\n    description: 'null'\n  - url: https://zuplo.com/blog\n    name: Zuplo Blog - Articles on API Development and Best Practices\n    type: Blog\n    description: 'null'\n  - url: https://auth.zuplo.com/u/login/identifier\n    name: Log in | Zuplo\n    type: Login\n    description: 'null'\n  - url: https://auth.zuplo.com/u/signup/identifier\n    name: Log in | Zuplo\n    type: SignUp\n    description: 'null'\n  - url: https://zuplo.com/docs/articles/support\n    name: Support - Zuplo Docs\n    type: Support\n    description: 'null'\n  - url: https://zuplo.com/resources\n    name: Zuplo Resources\n    type: Customers\n    description: 'null'\n  - url: https://zuplo.com/changelog\n    name: Zuplo Changelog - Latest platform updates and new features\n    type: ChangeLog\n    description: 'null'\n  - url: https://zuplo.com/integrations\n    name: Zuplo Integrations\n    type: Integrations\n    description: 'null'\n  - url:\
  \ https://zuplo.com/about\n    name: About Zuplo\n    type: About\n    description: 'null'\n  - url: https://status.zuplo.com/\n    name: Zuplo Status\n    type: Status\n    description: 'null'\n  - url: https://zuplo.com/legal/privacy-policy\n    name: Privacy Policy - Zuplo\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://zuplo.com/legal/terms\n    name: Terms of Service - Zuplo\n    type: TermsOfService\n    description: 'null'\n  - url: https://zuplo.com/legal/security-policy\n    name: Security Policies - Zuplo\n    type: Security\n    description: 'null'\n  - url: https://trust.zuplo.com/\n    name: Trust Center - Zuplo\n    type: Trust\n    description: 'null'\n  - url: https://zuplo.com/docs\n    name: Zuplo Docs\n    type: GettingStarted\n    description: 'null'\n  - url: https://zuplo.com/learning-center\n    name: Zuplo Learning Center\n    type: LearningCenter\n    description: 'null'\n  - url: https://zuplo.com/features/developer-portal\n    name: API Developer\
  \ Portal - Zuplo\n    type: DeveloperPortal\n    description: 'null'\n  - url: https://zuplo.com/features/api-management\n    name: API Management - Zuplo\n    type: APIManagement\n    description: 'null'\n  - url: https://zuplo.com/features/programmable\n    name: Programmable API Gateway - Zuplo\n    type: Features\n    description: 'null'\n  - url: https://zuplo.com/features/rate-limiting\n    name: API Rate Limiting - Zuplo\n    type: RateLimiting\n    description: 'null'\n  - url: https://zuplo.com/features/api-key-management\n    name: API Key Management - Zuplo\n    type: APIKeyManagement\n    description: 'null'\n  - url: https://zuplo.com/features/api-monetization\n    name: API Monetization - Zuplo\n    type: Monetization\n    description: 'null'\n  - url: https://zuplo.com/features/api-security\n    name: API Security - Zuplo\n    type: APISecurity\n    description: 'null'\n  - url: https://zuplo.com/features/api-governance\n    name: API Governance - Zuplo\n    type: Governance\n\
  \    description: 'null'\n  - url: https://zuplo.com/features/open-api\n    name: OpenAPI Native API Gateway - Zuplo\n    type: OpenAPI\n    description: 'null'\n  - url: https://zuplo.com/features/gitops\n    name: GitOps - Zuplo\n    type: GitOps\n    description: 'null'\n  - url: https://zuplo.com/features/multi-cloud\n    name: Multi-cloud API Gateway - Zuplo\n    type: MultiCloud\n    description: 'null'\n  - url: https://zuplo.com/features/unlimited-environments\n    name: Unlimited API Development Environments - Zuplo\n    type: Environments\n    description: 'null'\n  - url: https://zuplo.com/features/self-serve-devx\n    name: Self-Serve DevX - Zuplo\n    type: SelfService\n    description: 'null'\n  - url: https://zuplo.com/features/ai-gateway\n    name: AI Gateway - Zuplo\n    type: AIGateway\n    description: 'null'\n  - url: https://zuplo.com/mcp-servers\n    name: Zuplo MCP Servers\n    type: MCPServers\n    description: 'null'\n  - url: https://github.com/zuplo\n    name:\
  \ Zuplo GitHub Organization\n    type: GitHub\n    description: 'null'\n  - url: https://github.com/zuplo/zuplo\n    name: Zuplo GitHub Repository\n    type: GitHubRepo\n    description: 'null'\n  - url: https://github.com/zuplo/zudoku\n    name: Zudoku - API Documentation Framework\n    type: GitHubRepo\n    description: 'null'\n  - url: https://github.com/zuplo/rate-my-openapi\n    name: Rate My OpenAPI\n    type: GitHubRepo\n    description: 'null'\n  - url: https://x.com/zuplo\n    name: Zuplo on X\n    type: X\n    description: 'null'\n  - url: https://www.linkedin.com/company/zuplo\n    name: Zuplo on LinkedIn\n    type: LinkedIn\n    description: 'null'\n  - url: https://discord.com/invite/stPRhjbA55\n    name: Zuplo Discord Community\n    type: Discord\n    description: 'null'\n  - url: https://zuplo.com/careers\n    name: Careers at Zuplo\n    type: Careers\n    description: 'null'\n  - url: https://zuplo.com/support\n    name: Zuplo Support & Help Center\n    type: HelpCenter\n\
  \    description: 'null'\n  - url: https://zuplo.com/api-management\n    name: Zuplo API Management Overview\n    type: Overview\n    description: 'null'\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nposition: Consumer\nsegments:\n  - Gateways\ndescription: >-\n  Zuplo is the API management platform for developers. Build, deploy, and scale\n  APIs faster with Zuplo.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/apis.yml
tags:
- AI Gateway
- API Management
- Gateways
- Platform
url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/apis.yml
use_cases: []
---
