---
api_count: 7
apis:
- description: Primary API for sending messages to Claude and receiving responses.
  name: Claude Messages API
  slug: ''
- description: API for asynchronously processing large volumes of message requests at reduced cost with 50 percent discount.
  name: Claude Message Batches API
  slug: ''
- description: API for listing and retrieving metadata about available Claude models including capabilities and context windows.
  name: Claude Models API
  slug: ''
- description: API for uploading and managing files to reference in Claude API requests without re-uploading content each time.
  name: Claude Files API
  slug: ''
- description: API for programmatically managing organization resources including members workspaces API keys and invites.
  name: Claude Admin API
  slug: ''
- description: API for tracking token consumption and costs across your organization with breakdowns by model workspace and service tier.
  name: Claude Usage and Cost API
  slug: ''
- description: Legacy API for generating text completions - deprecated in favor of the Messages API.
  name: Claude Text Completions API
  slug: ''
capabilities:
- description: Unified workflow for AI-powered messaging, token counting, batch processing, and model discovery. Used by AI application developers and data scientists.
  name: Claude AI Messaging
  slug: ai-messaging
common:
- title: ''
  type: Portal
  url: https://console.anthropic.com
- title: ''
  type: Documentation
  url: https://docs.anthropic.com
- title: ''
  type: GettingStarted
  url: https://docs.anthropic.com/en/docs/get-started
- title: ''
  type: Pricing
  url: https://www.anthropic.com/pricing
- title: ''
  type: RateLimits
  url: https://docs.anthropic.com/en/api/rate-limits
- title: ''
  type: Authentication
  url: https://docs.anthropic.com/en/api/getting-started
- title: ''
  type: ChangeLog
  url: https://docs.anthropic.com/en/release-notes/api
- title: ''
  type: StatusPage
  url: https://status.anthropic.com
- title: ''
  type: Blog
  url: https://www.anthropic.com/news
- title: ''
  type: Support
  url: https://support.anthropic.com
- title: ''
  type: TermsOfService
  url: https://www.anthropic.com/legal/commercial-terms
- title: ''
  type: PrivacyPolicy
  url: https://www.anthropic.com/legal/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/anthropics
- title: ''
  type: SpectralRules
  url: rules/claude-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/claude-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ai-messaging.yaml
created: '2024'
description: Anthropic's Claude AI assistant API for natural language processing and conversation.
features:
- description: Maintain context across multiple message exchanges for natural dialogue interactions.
  name: Multi-Turn Conversations
- description: Enable Claude to call external tools and functions to perform actions and retrieve data.
  name: Tool Use
- description: Process and analyze images alongside text for multimodal understanding.
  name: Vision
- description: Allow Claude to reason step-by-step for complex tasks with visible thinking process.
  name: Extended Thinking
- description: Receive responses in real-time via server-sent events for responsive user experiences.
  name: Streaming Responses
- description: Process large volumes of requests asynchronously at 50 percent reduced cost.
  name: Message Batches
- description: Pre-calculate token usage for messages including tools, images, and documents.
  name: Token Counting
image: https://www.anthropic.com/images/icons/anthropic-icon.png
integrations:
- description: Access Claude models through AWS Bedrock for enterprise deployment with AWS infrastructure.
  name: Amazon Bedrock
- description: Use Claude on Google Cloud through Vertex AI integration.
  name: Google Cloud Vertex AI
- description: Integrate Claude into LangChain pipelines for advanced AI application development.
  name: LangChain
- description: Connect Claude to external data sources and tools via the Model Context Protocol.
  name: MCP Protocol
jsonld:
- class_count: 0
  name: Claude Context
  property_count: 20
  slug: claude-context
- class_count: 0
  name: Claude Messages Context
  property_count: 0
  slug: claude-messages-context
layout: provider
modified: '2026-04-18'
name: Claude
rules:
- name: Claude API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: claude-spectral-rules
skills: []
slug: claude
solutions: []
source_yaml: "name: Claude\ndescription: >-\n  Anthropic's Claude AI assistant API for natural language processing and conversation.\nimage: https://www.anthropic.com/images/icons/anthropic-icon.png\nurl: https://www.anthropic.com\ncreated: '2024'\nmodified: '2026-04-18'\ntags:\n  - Artificial Intelligence\n  - Chatbot\n  - Conversational AI\n  - Generative AI\n  - Large Language Models\n  - Machine Learning\n  - Natural Language Processing\napis:\n  - name: Claude Messages API\n    description: >-\n      Primary API for sending messages to Claude and receiving responses.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/messages\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Conversational AI\n      - Large Language Models\n      - Natural Language Processing\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/messages\n      - type: OpenAPI\n      \
  \  url: openapi/claude-messages-api.yml\n      - type: Authentication\n        url: https://docs.anthropic.com/claude/reference/authentication\n      - type: Pricing\n        url: https://www.anthropic.com/pricing\n      - type: RateLimits\n        url: https://docs.anthropic.com/en/api/rate-limits\n      - type: GettingStarted\n        url: https://docs.anthropic.com/en/api/getting-started\n      - type: JSONSchema\n        url: json-schema/claude-message-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-create-message-request-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-message-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-error-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-usage-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-tool-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-tool-use-block-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/claude-messages-content-block-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-text-block-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-thinking-block-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-token-count-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-count-tokens-request-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-output-config-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-thinking-config-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-tool-choice-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-cache-control-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-content-block-param-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/claude-messages-text-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-image-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-document-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-tool-use-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-tool-result-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-thinking-block-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-message-param-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-message-batch-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-message-batch-list-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-message-batch-result-schema.json\n      - type:\
  \ JSONSchema\n        url: json-schema/claude-messages-create-message-batch-request-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-batch-request-item-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-deleted-message-batch-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-model-info-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-messages-model-list-schema.json\n      - type: JSONSchema\n        url: json-schema/claude-tool-use-schema.json\n      - type: JSONLD\n        url: json-ld/claude-context.jsonld\n      - type: JSONLD\n        url: json-ld/claude-messages-context.jsonld\n      - type: SDK\n        url: https://github.com/anthropics/anthropic-sdk-python\n        title: Python SDK\n      - type: SDK\n        url: https://github.com/anthropics/anthropic-sdk-typescript\n        title: TypeScript SDK\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n\
  \    endpoints:\n      - name: Create Message\n        method: POST\n        path: /messages\n        description: Send a message to Claude and receive a response\n      - name: Stream Message\n        method: POST\n        path: /messages\n        description: Stream a message response from Claude using server-sent events\n      - name: Count Message Tokens\n        method: POST\n        path: /messages/count_tokens\n        description: Count the number of tokens in a message including tools images and documents without creating it\n  - name: Claude Message Batches API\n    description: >-\n      API for asynchronously processing large volumes of message requests at reduced\n      cost with 50 percent discount.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/creating-message-batches\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Asynchronous\n      - Batch Processing\n      - Large Language\
  \ Models\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/creating-message-batches\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n    endpoints:\n      - name: Create Message Batch\n        method: POST\n        path: /messages/batches\n        description: Create a batch of message requests for asynchronous processing\n      - name: List Message Batches\n        method: GET\n        path: /messages/batches\n        description: List all message batches within a workspace\n      - name: Retrieve Message Batch\n        method: GET\n        path: /messages/batches/{message_batch_id}\n        description: Retrieve the status and details of a specific message batch\n      - name: Retrieve Message Batch Results\n        method: GET\n        path: /messages/batches/{message_batch_id}/results\n        description: Stream the results of a completed message batch as a JSONL file\n      - name: Cancel Message Batch\n\
  \        method: POST\n        path: /messages/batches/{message_batch_id}/cancel\n        description: Cancel an in-progress message batch\n      - name: Delete Message Batch\n        method: DELETE\n        path: /messages/batches/{message_batch_id}\n        description: Delete a completed message batch\n  - name: Claude Models API\n    description: >-\n      API for listing and retrieving metadata about available Claude models including\n      capabilities and context windows.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/models-list\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Large Language Models\n      - Models\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/models-list\n      - type: Models\n        url: https://docs.anthropic.com/en/docs/about-claude/models\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n\
  \    endpoints:\n      - name: List Models\n        method: GET\n        path: /models\n        description: List all available Claude models with their metadata\n      - name: Get Model\n        method: GET\n        path: /models/{model_id}\n        description: Retrieve metadata for a specific Claude model\n  - name: Claude Files API\n    description: >-\n      API for uploading and managing files to reference in Claude API requests without\n      re-uploading content each time.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/docs/build-with-claude/files\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Document Processing\n      - File Management\n      - Files\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/docs/build-with-claude/files\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n    endpoints:\n      - name: Upload\
  \ File\n        method: POST\n        path: /files\n        description: Upload a file to be referenced in future API calls\n      - name: List Files\n        method: GET\n        path: /files\n        description: List uploaded files\n      - name: Get File Metadata\n        method: GET\n        path: /files/{file_id}\n        description: Retrieve metadata for a specific uploaded file\n      - name: Download File\n        method: GET\n        path: /files/{file_id}/content\n        description: Download file content created by skills or the code execution tool\n      - name: Delete File\n        method: DELETE\n        path: /files/{file_id}\n        description: Delete an uploaded file\n  - name: Claude Admin API\n    description: >-\n      API for programmatically managing organization resources including members workspaces\n      API keys and invites.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/administration-api\n\
  \    baseURL: https://api.anthropic.com/v1\n    tags:\n      - Administration\n      - AI\n      - API Keys\n      - Organization Management\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/administration-api\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n    endpoints:\n      - name: Get Organization\n        method: GET\n        path: /organizations/me\n        description: Retrieve information about your organization\n      - name: List Organization Members\n        method: GET\n        path: /organizations/users\n        description: List all members of the organization\n      - name: Update Organization Member\n        method: POST\n        path: /organizations/users/{user_id}\n        description: Update an organization member role\n      - name: Remove Organization Member\n        method: DELETE\n        path: /organizations/users/{user_id}\n        description: Remove a member from\
  \ the organization\n      - name: List Invites\n        method: GET\n        path: /organizations/invites\n        description: List all pending invitations\n      - name: Create Invite\n        method: POST\n        path: /organizations/invites\n        description: Invite a user to the organization\n      - name: Delete Invite\n        method: DELETE\n        path: /organizations/invites/{invite_id}\n        description: Delete a pending invitation\n      - name: List Workspaces\n        method: GET\n        path: /organizations/workspaces\n        description: List all workspaces in the organization\n      - name: Get Workspace\n        method: GET\n        path: /organizations/workspaces/{workspace_id}\n        description: Retrieve details of a specific workspace\n      - name: List Workspace Members\n        method: GET\n        path: /organizations/workspaces/{workspace_id}/members\n        description: List all members of a workspace\n      - name: Add Workspace Member\n      \
  \  method: POST\n        path: /organizations/workspaces/{workspace_id}/members\n        description: Add a member to a workspace\n      - name: Update Workspace Member\n        method: POST\n        path: /organizations/workspaces/{workspace_id}/members/{user_id}\n        description: Update a workspace member role\n      - name: Remove Workspace Member\n        method: DELETE\n        path: /organizations/workspaces/{workspace_id}/members/{user_id}\n        description: Remove a member from a workspace\n      - name: List API Keys\n        method: GET\n        path: /organizations/api_keys\n        description: List all API keys in the organization\n      - name: Update API Key\n        method: POST\n        path: /organizations/api_keys/{api_key_id}\n        description: Update an API key name or status\n  - name: Claude Usage and Cost API\n    description: >-\n      API for tracking token consumption and costs across your organization with breakdowns\n      by model workspace and service\
  \ tier.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/usage-cost-api\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Analytics\n      - Cost Tracking\n      - Usage\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/usage-cost-api\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n    endpoints:\n      - name: Get Usage Report\n        method: GET\n        path: /organizations/usage_report/messages\n        description: Retrieve token usage report with breakdowns by model workspace and service tier\n      - name: Get Cost Report\n        method: GET\n        path: /organizations/cost_report\n        description: Retrieve service-level cost breakdowns in USD including token usage web search and code execution costs\n  - name: Claude Text Completions API\n    description: >-\n      Legacy API for generating text completions\
  \ - deprecated in favor of the Messages\n      API.\n    image: https://www.anthropic.com/images/icons/anthropic-icon.png\n    humanURL: https://docs.anthropic.com/en/api/complete\n    baseURL: https://api.anthropic.com/v1\n    tags:\n      - AI\n      - Large Language Models\n      - Legacy\n      - Text Completion\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/api/complete\n    contact:\n      - type: Support\n        url: https://support.anthropic.com\n    endpoints:\n      - name: Create Text Completion\n        method: POST\n        path: /complete\n        description: Generate a text completion from Claude (legacy - use Messages API instead)\ncommon:\n  - type: Portal\n    url: https://console.anthropic.com\n  - type: Documentation\n    url: https://docs.anthropic.com\n  - type: GettingStarted\n    url: https://docs.anthropic.com/en/docs/get-started\n  - type: Pricing\n    url: https://www.anthropic.com/pricing\n  - type: RateLimits\n \
  \   url: https://docs.anthropic.com/en/api/rate-limits\n  - type: Authentication\n    url: https://docs.anthropic.com/en/api/getting-started\n  - type: ChangeLog\n    url: https://docs.anthropic.com/en/release-notes/api\n  - type: StatusPage\n    url: https://status.anthropic.com\n  - type: Blog\n    url: https://www.anthropic.com/news\n  - type: Support\n    url: https://support.anthropic.com\n  - type: TermsOfService\n    url: https://www.anthropic.com/legal/commercial-terms\n  - type: PrivacyPolicy\n    url: https://www.anthropic.com/legal/privacy\n  - type: GitHubOrganization\n    url: https://github.com/anthropics\n  - type: SpectralRules\n    url: rules/claude-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/claude-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/ai-messaging.yaml\n  - type: Features\n    data:\n      - name: Multi-Turn Conversations\n        description: Maintain context across multiple message exchanges for natural dialogue interactions.\n\
  \      - name: Tool Use\n        description: Enable Claude to call external tools and functions to perform actions and retrieve data.\n      - name: Vision\n        description: Process and analyze images alongside text for multimodal understanding.\n      - name: Extended Thinking\n        description: Allow Claude to reason step-by-step for complex tasks with visible thinking process.\n      - name: Streaming Responses\n        description: Receive responses in real-time via server-sent events for responsive user experiences.\n      - name: Message Batches\n        description: Process large volumes of requests asynchronously at 50 percent reduced cost.\n      - name: Token Counting\n        description: Pre-calculate token usage for messages including tools, images, and documents.\n  - type: UseCases\n    data:\n      - name: AI-Powered Chat Applications\n        description: Build conversational interfaces with context-aware responses and tool integration.\n      - name: Content Generation\n\
  \        description: Generate, edit, and transform text content for marketing, documentation, and creative writing.\n      - name: Code Assistance\n        description: Use Claude for code generation, review, debugging, and technical documentation.\n      - name: Document Analysis\n        description: Extract information, summarize, and answer questions about documents and images.\n      - name: Batch Processing\n        description: Process large datasets of prompts efficiently using the Message Batches API.\n  - type: Integrations\n    data:\n      - name: Amazon Bedrock\n        description: Access Claude models through AWS Bedrock for enterprise deployment with AWS infrastructure.\n      - name: Google Cloud Vertex AI\n        description: Use Claude on Google Cloud through Vertex AI integration.\n      - name: LangChain\n        description: Integrate Claude into LangChain pipelines for advanced AI application development.\n      - name: MCP Protocol\n        description: Connect\
  \ Claude to external data sources and tools via the Model Context Protocol.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n  - name: Anthropic\n    email: support@anthropic.com\n    url: https://www.anthropic.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/claude/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Chatbot
- Conversational AI
- Generative AI
- Large Language Models
- Machine Learning
- Natural Language Processing
url: https://www.anthropic.com
use_cases:
- description: Build conversational interfaces with context-aware responses and tool integration.
  name: AI-Powered Chat Applications
- description: Generate, edit, and transform text content for marketing, documentation, and creative writing.
  name: Content Generation
- description: Use Claude for code generation, review, debugging, and technical documentation.
  name: Code Assistance
- description: Extract information, summarize, and answer questions about documents and images.
  name: Document Analysis
- description: Process large datasets of prompts efficiently using the Message Batches API.
  name: Batch Processing
---
