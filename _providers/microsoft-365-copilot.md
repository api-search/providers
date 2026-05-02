---
api_count: 4
api_specs:
- filename: openapi
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.microsoft.com/en-us/graph/docs/concepts/openapi
apis:
- description: The Microsoft Graph API provides access to Microsoft 365 data and services, enabling developers to integrate Copilot functionality with user data, documents, emails, calendar, and more.
  name: Microsoft Graph API
  slug: ''
- description: Microsoft Copilot Studio allows developers to create, customize, and extend Copilot experiences with custom plugins and connectors to integrate business-specific data and workflows.
  name: Microsoft Copilot Studio API
  slug: ''
- description: API for extending Microsoft 365 Copilot with custom skills, plugins, and connectors to integrate third-party services and enterprise data sources.
  name: Microsoft 365 Copilot Extensibility API
  slug: ''
- description: Azure OpenAI Service provides REST API access to OpenAI's language models, which power Microsoft 365 Copilot's AI capabilities with enterprise-grade security and compliance.
  name: Azure OpenAI Service API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Blog
  url: https://www.microsoft.com/en-us/microsoft-365/blog/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft
created: '2024-01-15'
description: Microsoft 365 Copilot is an AI-powered productivity tool that combines large language models (LLMs) with Microsoft 365 apps and business data to enhance creativity, productivity, and skills across Microsoft 365 applications.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/copilot/copilot-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft 365 Copilot
skills: []
slug: microsoft-365-copilot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft 365 Copilot\ndescription: Microsoft 365 Copilot is an AI-powered productivity tool that combines large language models (LLMs) with Microsoft 365 apps and business data to enhance creativity, productivity, and skills across Microsoft 365 applications.\nimage: https://www.microsoft.com/en-us/microsoft-365/copilot/copilot-logo.png\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\nurl: https://www.microsoft.com/en-us/microsoft-365/copilot/apis.json\napis:\n  - name: Microsoft Graph API\n    description: The Microsoft Graph API provides access to Microsoft 365 data and services, enabling developers to integrate Copilot functionality with user data, documents, emails, calendar, and more.\n    image: https://docs.microsoft.com/graph/images/microsoft-graph.png\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - AI\n      - Data Integration\n      - Microsoft 365\n \
  \     - Productivity\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://developer.microsoft.com/en-us/graph/docs/concepts/openapi\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Changelog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Microsoft Copilot Studio API\n    description: Microsoft Copilot Studio allows developers to create, customize, and extend Copilot experiences with custom plugins and connectors to integrate business-specific data and workflows.\n    image: https://www.microsoft.com/en-us/copilot/studio-icon.png\n    humanURL: https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio\n    baseURL: https://api.powerplatform.com/\n    tags:\n      - AI Development\n      - Automation\n\
  \      - Custom Plugins\n      - Low Code\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-get-started\n      - type: Plugin Development\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/copilot-plugins-overview\n      - type: Connectors\n        url: https://learn.microsoft.com/en-us/connectors/\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/tutorials\n  - name: Microsoft 365 Copilot Extensibility API\n    description: API for extending Microsoft 365 Copilot with custom skills, plugins, and connectors to integrate third-party services and enterprise data sources.\n    image: https://www.microsoft.com/en-us/microsoft-365/copilot/extensibility-icon.png\n    humanURL: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/\n\
  \    baseURL: https://api.microsoft365.com/copilot/v1\n    tags:\n      - Custom Skills\n      - Extensibility\n      - Integration\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/\n      - type: Plugin Manifest\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/create-plugin\n      - type: Teams Message Extensions\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/build-message-extensions\n      - type: API Plugins\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/api-plugins\n      - type: Samples\n        url: https://github.com/microsoft/copilot-plugins-samples\n  - name: Azure OpenAI Service API\n    description: Azure OpenAI Service provides REST API access to OpenAI's language models, which power Microsoft 365 Copilot's AI capabilities with enterprise-grade security and compliance.\n\
  \    image: https://azure.microsoft.com/en-us/services/openai/openai-icon.png\n    humanURL: https://azure.microsoft.com/en-us/products/ai-services/openai-service\n    baseURL: https://{resource-name}.openai.azure.com/\n    tags:\n      - AI\n      - Azure\n      - GPT\n      - Language Models\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/ai-services/openai/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/azure/ai-services/openai/reference\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/ai-services/openai/quickstart\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/cognitive-services/openai-service/\n      - type: Models\n        url: https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Developer Portal\n    url: https://developer.microsoft.com/\n\
  \  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Blog\n    url: https://www.microsoft.com/en-us/microsoft-365/blog/\n  - type: Status\n    url: https://status.azure.com/\n  - type: GitHub Organization\n    url: https://github.com/microsoft\nmaintainers:\n  - name: Microsoft\n    email: support@microsoft.com\n    url: https://www.microsoft.com/\ntags:\n  - Artificial Intelligence\n  - Copilot\n  - Enterprise\n  - LLM\n  - Microsoft 365\n  - Natural Language Processing\n  - Productivity\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-365-copilot/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Copilot
- Enterprise
- LLM
- Microsoft 365
- Natural Language Processing
- Productivity
url: https://www.microsoft.com/en-us/microsoft-365/copilot/apis.json
use_cases: []
---
