---
api_count: 5
api_specs:
- filename: microsoft-copilot-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot APIs
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-copilot/refs/heads/main/openapi/microsoft-copilot-openapi.yml
apis:
- description: API for integrating Microsoft Copilot capabilities into applications.
  name: Microsoft Copilot API
  slug: ''
- description: Microsoft Graph API endpoints for accessing Copilot features within Microsoft 365, including the Copilot namespace with retrieval, chat, search, and meeting insights capabilities.
  name: Microsoft Graph API (Copilot Integration)
  slug: ''
- description: REST APIs under the Microsoft Graph /copilot/ namespace that enable secure access to Microsoft 365 Copilot capabilities including retrieval, chat, and search, for use in custom applications and agents
  name: Microsoft 365 Copilot APIs
  slug: ''
- description: API for building custom connectors that bring external data into Microsoft Graph to enhance Microsoft 365 Copilot experiences including search and retrieval augmented generation.
  name: Microsoft 365 Copilot Connectors API
  slug: ''
- description: APIs for building, publishing, and integrating custom agents and copilots using Microsoft Copilot Studio, including Direct Line API for connecting web and custom applications.
  name: Microsoft Copilot Studio API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/copilot/get-started
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-copilot/pricing
- title: ''
  type: Support
  url: https://support.microsoft.com/copilot
- title: ''
  type: Blog
  url: https://blogs.microsoft.com/blog/tag/copilot/
- title: ''
  type: StatusPage
  url: https://status.microsoft.com
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365/copilot
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries
- title: ''
  type: CodeExamples
  url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/samples
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/whats-new
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-privacy
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/CopilotStudioSamples
created: '2024-01-15'
description: Microsoft Copilot is an AI-powered assistant that helps users with productivity tasks, content generation, and information retrieval across Microsoft 365 applications and services.
features:
- description: Retrieve relevant enterprise content from Microsoft 365 using AI-powered retrieval augmented generation with permissions and sensitivity label awareness.
  name: Retrieval API
- description: Perform semantic search across Microsoft 365 content including SharePoint, OneDrive, and Exchange with AI-enhanced ranking.
  name: Search API
- description: Programmatically start and continue conversations with Microsoft 365 Copilot grounded in enterprise and web search data.
  name: Chat API
- description: Export and audit Copilot interaction history across the organization for compliance and governance purposes.
  name: Interaction Export
- description: Subscribe to real-time notifications for Copilot interactions and events across Microsoft 365.
  name: Change Notifications
- description: Low-code platform for building custom agents, copilots, and conversational AI experiences.
  name: Copilot Studio
- description: Bring external data into Microsoft Graph to enhance Copilot search and retrieval capabilities.
  name: Connectors
- description: Extend Copilot with custom plugins, agents, and API integrations using declarative or code-first approaches.
  name: Extensibility
image: https://www.microsoft.com/en-us/microsoft-copilot/assets/images/copilot-icon.png
integrations:
- description: Deep integration with Word, Excel, PowerPoint, Outlook, Teams, and other Microsoft 365 applications.
  name: Microsoft 365
- description: Access organizational data through the Microsoft Graph API for retrieval, search, and chat capabilities.
  name: Microsoft Graph
- description: Enterprise authentication and authorization using Azure AD with OAuth 2.0 and OIDC.
  name: Azure Active Directory
- description: Connect Copilot with Power Automate, Power Apps, and Power BI for end-to-end workflow automation.
  name: Power Platform
jsonld:
- class_count: 0
  name: Microsoft Copilot Context
  property_count: 0
  slug: microsoft-copilot-context
layout: provider
modified: '2026-04-18'
name: Microsoft Copilot
rules:
- name: Microsoft Copilot API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-copilot-spectral-rules
skills: []
slug: microsoft-copilot
solutions: []
source_filename: apis.yml
source_yaml: "name: Microsoft Copilot\ndescription: >-\n  Microsoft Copilot is an AI-powered assistant that helps users with productivity\n  tasks, content generation, and information retrieval across Microsoft 365\n  applications and services.\nimage: https://www.microsoft.com/en-us/microsoft-copilot/assets/images/copilot-icon.png\nurl: https://copilot.microsoft.com\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Contract\naccess: 3rd-Party\ntags:\n  - Agents\n  - AI Assistant\n  - Artificial Intelligence\n  - Chatbot\n  - Copilot\n  - Extensibility\n  - Generative AI\n  - Microsoft 365\n  - Productivity\napis:\n  - name: Microsoft Copilot API\n    description: >-\n      API for integrating Microsoft Copilot capabilities into applications.\n    image: https://www.microsoft.com/en-us/microsoft-copilot/assets/images/copilot-icon.png\n    humanURL: https://learn.microsoft.com/en-us/copilot/\n    baseURL: https://api.copilot.microsoft.com\n    tags:\n   \
  \   - AI\n      - Chat\n      - Completion\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/copilot/overview\n      - type: OpenAPI\n        url: https://api.copilot.microsoft.com/openapi.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/copilot/authentication\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/copilot/get-started\n  - name: Microsoft Graph API (Copilot Integration)\n    description: >-\n      Microsoft Graph API endpoints for accessing Copilot features within Microsoft\n      365, including the Copilot namespace with retrieval, chat, search, and meeting\n      insights capabilities.\n    humanURL: https://learn.microsoft.com/en-us/graph/overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Integration\n      - Microsoft 365\n      - Microsoft Graph\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/overview\n\
  \      - type: OpenAPI\n        url: https://graph.microsoft.com/openapi.json\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/use-the-api\n  - name: Microsoft 365 Copilot APIs\n    description: >-\n      REST APIs under the Microsoft Graph /copilot/ namespace that enable secure\n      access to Microsoft 365 Copilot capabilities including retrieval, chat, and\n      search, for use in custom applications and agents.\n    humanURL: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview\n    baseURL: https://graph.microsoft.com/v1.0/copilot\n    tags:\n      - AI\n      - Chat\n      - Microsoft 365\n      - RAG\n      - Retrieval\n      - Search\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/api/ai-services/retrieval/overview\n\
  \        title: Retrieval API\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/api/ai-services/chat/overview\n        title: Chat API\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries\n      - type: OpenAPI\n        url: openapi/microsoft-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-copilot-interaction-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-copilot-context.jsonld\n  - name: Microsoft 365 Copilot Connectors API\n    description: >-\n      API for building custom connectors that bring external data into Microsoft\n      Graph to enhance Microsoft 365 Copilot experiences including search and\n      retrieval augmented generation.\n    humanURL: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/overview-copilot-connector\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n\
  \      - Connectors\n      - External Data\n      - Indexing\n      - Microsoft Graph\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/connecting-external-content-connectors-api-overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/connectors-api-overview?view=graph-rest-1.0\n        title: Connectors API Reference\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/custom-connector-sdk-sample-overview\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/custom-connector-sdk-overview\n  - name: Microsoft Copilot Studio API\n    description: >-\n      APIs for building, publishing, and integrating custom agents and copilots\n      using Microsoft Copilot Studio, including Direct Line API for connecting web\n      and custom applications.\n    humanURL: https://learn.microsoft.com/en-us/microsoft-copilot-studio/\n    baseURL: https://directline.botframework.com\n\
  \    tags:\n      - Agents\n      - Bots\n      - Copilot Studio\n      - Direct Line\n      - Low-Code\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-api-reference?view=azure-bot-service-4.0\n        title: Direct Line API Reference\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/configure-web-security\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-connect-bot-to-custom-application\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/copilot/get-started\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/\n  - type: TermsOfService\n\
  \    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-copilot/pricing\n  - type: Support\n    url: https://support.microsoft.com/copilot\n  - type: Blog\n    url: https://blogs.microsoft.com/blog/tag/copilot/\n  - type: StatusPage\n    url: https://status.microsoft.com\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365/copilot\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries\n  - type: CodeExamples\n    url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/samples\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/whats-new\n  - type: Security\n    url: https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-privacy\n\
  \  - type: GitHubRepository\n    url: https://github.com/microsoft/CopilotStudioSamples\n  - type: Features\n    data:\n      - name: Retrieval API\n        description: Retrieve relevant enterprise content from Microsoft 365 using AI-powered retrieval augmented generation with permissions and sensitivity label awareness.\n      - name: Search API\n        description: Perform semantic search across Microsoft 365 content including SharePoint, OneDrive, and Exchange with AI-enhanced ranking.\n      - name: Chat API\n        description: Programmatically start and continue conversations with Microsoft 365 Copilot grounded in enterprise and web search data.\n      - name: Interaction Export\n        description: Export and audit Copilot interaction history across the organization for compliance and governance purposes.\n      - name: Change Notifications\n        description: Subscribe to real-time notifications for Copilot interactions and events across Microsoft 365.\n      - name: Copilot\
  \ Studio\n        description: Low-code platform for building custom agents, copilots, and conversational AI experiences.\n      - name: Connectors\n        description: Bring external data into Microsoft Graph to enhance Copilot search and retrieval capabilities.\n      - name: Extensibility\n        description: Extend Copilot with custom plugins, agents, and API integrations using declarative or code-first approaches.\n  - type: UseCases\n    data:\n      - name: Enterprise Knowledge Retrieval\n        description: Build applications that retrieve relevant enterprise content from Microsoft 365 while respecting permissions and compliance controls.\n      - name: AI-Assisted Productivity\n        description: Integrate Copilot capabilities into line-of-business applications for document summarization, drafting, and data analysis.\n      - name: Custom Agent Development\n        description: Create domain-specific AI agents using Copilot Studio that automate workflows and answer questions\
  \ from custom data sources.\n      - name: Compliance and Governance\n        description: Monitor and audit Copilot usage across the organization with interaction history export and change notifications.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Deep integration with Word, Excel, PowerPoint, Outlook, Teams, and other Microsoft 365 applications.\n      - name: Microsoft Graph\n        description: Access organizational data through the Microsoft Graph API for retrieval, search, and chat capabilities.\n      - name: Azure Active Directory\n        description: Enterprise authentication and authorization using Azure AD with OAuth 2.0 and OIDC.\n      - name: Power Platform\n        description: Connect Copilot with Power Automate, Power Apps, and Power BI for end-to-end workflow automation.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-copilot/refs/heads/main/apis.yml
tags:
- Agents
- AI Assistant
- Artificial Intelligence
- Chatbot
- Copilot
- Extensibility
- Generative AI
- Microsoft 365
- Productivity
url: https://copilot.microsoft.com
use_cases:
- description: Build applications that retrieve relevant enterprise content from Microsoft 365 while respecting permissions and compliance controls.
  name: Enterprise Knowledge Retrieval
- description: Integrate Copilot capabilities into line-of-business applications for document summarization, drafting, and data analysis.
  name: AI-Assisted Productivity
- description: Create domain-specific AI agents using Copilot Studio that automate workflows and answer questions from custom data sources.
  name: Custom Agent Development
- description: Monitor and audit Copilot usage across the organization with interaction history export and change notifications.
  name: Compliance and Governance
---
