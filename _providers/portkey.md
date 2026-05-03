---
api_count: 3
api_specs:
- filename: portkey-openapi.yml
  format: yaml
  label: Portkey
  slug: portkey
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/openapi/portkey-openapi.yml
- filename: portkey-openapi.yml
  format: yaml
  label: Portkey Inference API
  slug: portkey-inference-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/openapi/portkey-openapi.yml
- filename: portkey-openapi.yml
  format: yaml
  label: Portkey Admin API
  slug: portkey-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/openapi/portkey-openapi.yml
apis:
- description: Portkey equips AI teams with everything they need to go to production - Gateway, Observability, Guardrails, Governance, and Prompt Management, all in one platform.
  name: Portkey
  slug: portkey
- description: Portkey Inference API provides a universal API for routing to 200+ LLMs across chat completions, completions, embeddings, images, audio, assistants, fine-tuning, batch processing, and moderations endp
  name: Portkey Inference API
  slug: portkey-inference-api
- description: Portkey Admin API enables programmatic management of Portkey organizations and workspaces, including resource management for configs, virtual keys, and API keys, analytics and monitoring for usage sta
  name: Portkey Admin API
  slug: portkey-admin-api
common:
- title: ''
  type: Website
  url: https://portkey.ai/
- title: ''
  type: Documentation
  url: https://portkey.ai/docs/introduction/what-is-portkey
- title: ''
  type: ChangeLog
  url: https://portkey.ai/docs/changelog/2025/july
- title: ''
  type: Blog
  url: https://portkey.ai/blog
- title: ''
  type: Status
  url: https://status.portkey.ai/
- title: ''
  type: Pricing
  url: https://portkey.ai/pricing
- title: ''
  type: PrivacyPolicy
  url: https://portkey.ai/privacy-policy
- title: ''
  type: TermsOfService
  url: https://portkey.ai/terms
- title: ''
  type: Login
  url: https://new.portkey.ai/login
- title: ''
  type: GettingStarted
  url: https://portkey.ai/docs/guides/getting-started/getting-started-with-ai-gateway
- title: ''
  type: APIReference
  url: https://portkey.ai/docs/api-reference/inference-api/chat
- title: ''
  type: APIReference
  url: https://portkey.ai/docs/api-reference/admin-api/introduction
- title: ''
  type: OpenAPI
  url: https://github.com/Portkey-AI/openapi
- title: ''
  type: GitHubOrg
  url: https://github.com/Portkey-AI/gateway
- title: ''
  type: GitHubOrg
  url: https://github.com/Portkey-AI/portkey-python-sdk
- title: ''
  type: GitHubOrg
  url: https://github.com/Portkey-AI/portkey-node-sdk
- title: ''
  type: PythonPackage
  url: https://pypi.org/project/portkey-ai/
- title: ''
  type: NodePackage
  url: https://www.npmjs.com/package/portkey-ai
- title: ''
  type: SDK
  url: https://portkey.ai/docs/api-reference/portkey-sdk-client
- title: ''
  type: Forum
  url: https://portkey.ai/docs/support/developer-forum
- title: ''
  type: Security
  url: https://portkey.ai/features/security-compliance
- title: ''
  type: Observability
  url: https://portkey.ai/features/observability
- title: ''
  type: Guardrails
  url: https://portkey.ai/features/guardrails
- title: ''
  type: Documentation
  url: https://portkey.ai/docs/product/guardrails
- title: ''
  type: Providers
  url: https://portkey.ai/docs/api-reference/inference-api/supported-providers
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/portkey-ai
created: '2025-08-19'
description: Portkey equips AI teams with everything they need to go to production - Gateway, Observability, Guardrails, Governance, and Prompt Management, all in one platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Portkey
skills: []
slug: portkey
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: portkey\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/apis.yml\napis:\n  - aid: portkey:portkey\n    name: Portkey\n    tags:\n      - AI Gateways\n      - Governance\n      - Guardrails\n      - Observability\n      - Prompt Management\n    humanURL: https://portkey.ai/\n    properties:\n      - url: https://portkey.ai/docs/introduction/what-is-portkey\n        type: Documentation\n      - url: https://portkey.ai/docs/api-reference/inference-api/chat\n        type: APIReference\n      - url: openapi/portkey-openapi.yml\n        type: OpenAPI\n      - url: https://portkey.ai/docs/guides/getting-started/getting-started-with-ai-gateway\n        type: GettingStarted\n    description: >-\n      Portkey equips AI teams with everything they need to go to production -\n      Gateway, Observability, Guardrails, Governance, and Prompt Management, all\n      in one platform.\n  - aid: portkey:portkey-inference-api\n    name: Portkey Inference\
  \ API\n    tags:\n      - AI Gateways\n      - Assistants\n      - Audio\n      - Batch\n      - Chat Completions\n      - Completions\n      - Embeddings\n      - Fine-Tuning\n      - Images\n      - Inference\n      - Moderations\n    humanURL: https://portkey.ai/docs/product/ai-gateway/universal-api\n    baseURL: https://api.portkey.ai/v1\n    properties:\n      - url: https://portkey.ai/docs/api-reference/inference-api/chat\n        type: APIReference\n      - url: https://portkey.ai/docs/api-reference/inference-api/completions\n        type: APIReference\n      - url: https://portkey.ai/docs/api-reference/inference-api/embeddings\n        type: APIReference\n      - url: openapi/portkey-openapi.yml\n        type: OpenAPI\n    description: >-\n      Portkey Inference API provides a universal API for routing to 200+ LLMs\n      across chat completions, completions, embeddings, images, audio,\n      assistants, fine-tuning, batch processing, and moderations endpoints with\n      a single\
  \ unified interface. Supports OpenAI, Anthropic, and Portkey API\n      formats with automatic translation between providers.\n  - aid: portkey:portkey-admin-api\n    name: Portkey Admin API\n    tags:\n      - Administration\n      - Analytics\n      - API Keys\n      - Audit Logs\n      - Configs\n      - Logs\n      - Rate Limits\n      - Users\n      - Virtual Keys\n      - Workspaces\n    humanURL: https://portkey.ai/docs/api-reference/admin-api/introduction\n    baseURL: https://api.portkey.ai/v1\n    properties:\n      - url: https://portkey.ai/docs/api-reference/admin-api/introduction\n        type: APIReference\n      - url: openapi/portkey-openapi.yml\n        type: OpenAPI\n    description: >-\n      Portkey Admin API enables programmatic management of Portkey organizations\n      and workspaces, including resource management for configs, virtual keys,\n      and API keys, analytics and monitoring for usage statistics and\n      performance trends, and user and workspace administration\
  \ for managing\n      accounts, permissions, and team membership. Includes audit logging of all\n      administrative operations.\nname: Portkey\ntags:\n  - AI Gateways\n  - Gateways\n  - Governance\n  - Guardrails\n  - Observability\n  - Prompt Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://portkey.ai/\n    name: Production Stack for Gen AI Builders|Portkey\n    type: Website\n    description: 'null'\n  - url: https://portkey.ai/docs/introduction/what-is-portkey\n    name: What is Portkey? - Portkey Docs\n    type: Documentation\n    description: 'null'\n  - url: https://portkey.ai/docs/integrations/ecosystem\n    name: Integrations - Portkey Docs\n    type: Integrations\n    description: 'null'\n  - url: https://portkey.ai/docs/changelog/2025/july\n    name: July - Portkey Docs\n    type: ChangeLog\n    description: 'null'\n  - url: https://portkey.ai/blog\n    name: LLMs in Prod\
  \ Blog ● Portkey\n    type: Blog\n    description: 'null'\n  - url: https://status.portkey.ai/\n    name: Portkey AI status\n    type: Status\n    description: 'null'\n  - url: https://portkey.ai/pricing\n    name: Portkey | Control Panel for Production AI\n    type: Pricing\n    description: 'null'\n  - url: https://portkey.ai/privacy-policy\n    name: Privacy Policy | Portkey\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://portkey.ai/terms\n    name: Portkey | Control Panel for Production AI\n    type: TermsOfService\n    description: 'null'\n  - url: https://new.portkey.ai/login\n    name: Portkey Login\n    type: Login\n    description: 'null'\n  - url: https://portkey.ai/docs/guides/getting-started/getting-started-with-ai-gateway\n    name: Getting Started with AI Gateway - Portkey Docs\n    type: GettingStarted\n    description: 'null'\n  - url: https://portkey.ai/docs/api-reference/inference-api/chat\n    name: Portkey API Reference - Chat\n    type: APIReference\n\
  \    description: 'null'\n  - url: https://portkey.ai/docs/api-reference/admin-api/introduction\n    name: Portkey Admin API Reference\n    type: APIReference\n    description: 'null'\n  - url: https://github.com/Portkey-AI/openapi\n    name: Portkey OpenAPI Specification\n    type: OpenAPI\n    description: 'null'\n  - url: https://github.com/Portkey-AI/gateway\n    name: Portkey AI Gateway - Open Source\n    type: GitHubOrg\n    description: 'null'\n  - url: https://github.com/Portkey-AI/portkey-python-sdk\n    name: Portkey Python SDK - GitHub\n    type: GitHubOrg\n    description: 'null'\n  - url: https://github.com/Portkey-AI/portkey-node-sdk\n    name: Portkey Node.js SDK - GitHub\n    type: GitHubOrg\n    description: 'null'\n  - url: https://pypi.org/project/portkey-ai/\n    name: portkey-ai - PyPI\n    type: PythonPackage\n    description: 'null'\n  - url: https://www.npmjs.com/package/portkey-ai\n    name: portkey-ai - npm\n    type: NodePackage\n    description: 'null'\n  -\
  \ url: https://portkey.ai/docs/api-reference/portkey-sdk-client\n    name: Portkey SDK Client - Portkey Docs\n    type: SDK\n    description: 'null'\n  - url: https://portkey.ai/docs/support/developer-forum\n    name: Developer Forum - Portkey Docs\n    type: Forum\n    description: 'null'\n  - url: https://portkey.ai/features/security-compliance\n    name: Enterprise-grade Security and Compliance - Portkey\n    type: Security\n    description: 'null'\n  - url: https://portkey.ai/features/ai-gateway\n    name: Enterprise-grade AI Gateway - Portkey\n    type: Features\n    description: 'null'\n  - url: https://portkey.ai/features/observability\n    name: Full-stack Observability for AI Apps - Portkey\n    type: Observability\n    description: 'null'\n  - url: https://portkey.ai/features/guardrails\n    name: Safeguard Your AI Requests with Guardrails - Portkey\n    type: Guardrails\n    description: 'null'\n  - url: https://portkey.ai/docs/product/guardrails\n    name: Guardrails - Portkey\
  \ Docs\n    type: Documentation\n    description: 'null'\n  - url: https://portkey.ai/docs/api-reference/inference-api/supported-providers\n    name: Supported Providers - Portkey Docs\n    type: Providers\n    description: 'null'\n  - url: https://www.linkedin.com/company/portkey-ai\n    name: Portkey AI on LinkedIn\n    type: LinkedIn\n    description: 'null'\ncreated: '2025-08-19'\nmodified: '2026-04-28'\nposition: Consumer\nsegments:\n  - Gateways\ndescription: >-\n  Portkey equips AI teams with everything they need to go to production - Gateway,\n  Observability, Guardrails, Governance, and Prompt Management, all in one platform.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/apis.yml
tags:
- AI Gateways
- Gateways
- Governance
- Guardrails
- Observability
- Prompt Management
url: https://raw.githubusercontent.com/api-evangelist/portkey/refs/heads/main/apis.yml
use_cases: []
---
