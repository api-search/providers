---
api_count: 12
apis:
- description: REST API for managing GitHub Copilot seats, usage, and organization settings.
  name: GitHub Copilot API
  slug: ''
- description: Manage Copilot for Business subscriptions, seat assignments, and usage metrics.
  name: GitHub Copilot for Business API
  slug: ''
- description: API for GitHub Copilot Chat interactions and conversations.
  name: GitHub Copilot Chat API
  slug: ''
- description: REST API for managing GitHub Copilot seat assignments, billing information, and subscription details for organizations including adding and removing users and teams.
  name: GitHub Copilot User Management API
  slug: ''
- description: REST API for retrieving aggregated Copilot usage metrics at the organization and team level, including data on active users, engaged users, and breakdowns by language and editor.
  name: GitHub Copilot Metrics API
  slug: ''
- description: REST API for retrieving detailed Copilot usage metrics reports at the enterprise and organization level, including daily and 28-day aggregated reports for both entity-level and user-level data.
  name: GitHub Copilot Usage Metrics API
  slug: ''
- description: REST API for programmatically managing Copilot content exclusion path rules at both the organization and enterprise level, enabling automation and governance of which content Copilot can access.
  name: GitHub Copilot Content Exclusion API
  slug: ''
- description: Platform for building Copilot Extensions that integrate third-party tools, services, and custom agents into GitHub Copilot Chat, using GitHub Apps with agent or skillset configurations.
  name: GitHub Copilot Extensions API
  slug: ''
- description: Autonomous coding agent that works in the background to complete tasks, spinning up secure development environments powered by GitHub Actions to explore code, make changes, run tests, and open pull re
  name: GitHub Copilot Coding Agent
  slug: ''
- description: AI-powered code review agent that analyzes pull requests for issues, suggests fixes, and provides feedback across any programming language with agentic context gathering capabilities.
  name: GitHub Copilot Code Review
  slug: ''
- description: GitHub official Model Context Protocol server that enables AI tools to interact with GitHub repositories, issues, pull requests, and other resources through a standardized protocol.
  name: GitHub MCP Server
  slug: ''
- description: Configuration system for providing repository-level, path-specific, and organization-level custom instructions to guide Copilot behavior, code style, and response formatting.
  name: GitHub Copilot Custom Instructions
  slug: ''
common:
- title: ''
  type: Portal
  url: https://github.com/features/copilot
- title: ''
  type: StatusPage
  url: https://www.githubstatus.com/
- title: ''
  type: TermsOfService
  url: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement
- title: ''
  type: GettingStarted
  url: https://docs.github.com/en/copilot/quickstart
- title: ''
  type: Blog
  url: https://github.blog/tag/github-copilot/
- title: ''
  type: SignUp
  url: https://github.com/github-copilot/signup
- title: ''
  type: Pricing
  url: https://github.com/features/copilot/plans
- title: ''
  type: ChangeLog
  url: https://github.blog/changelog/label/copilot/
- title: ''
  type: Support
  url: https://support.github.com
- title: ''
  type: SDK
  url: https://github.com/github/copilot-sdk
- title: ''
  type: TrustCenter
  url: https://copilot.github.trust.page/
- title: ''
  type: RateLimits
  url: https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api
- title: ''
  type: Authentication
  url: https://docs.github.com/en/rest/authentication
- title: ''
  type: OpenAPI
  url: https://github.com/github/rest-api-description
- title: ''
  type: Documentation
  url: https://docs.github.com/en/copilot
- title: ''
  type: Marketplace
  url: https://github.com/marketplace?type=apps&copilot_app=true
created: '2024'
description: APIs and resources for GitHub Copilot, an AI pair programmer that helps you write code faster.
features:
- description: AI-powered inline code suggestions that complete lines, functions, and entire blocks as you type in your IDE.
  name: Code Completion
- description: Conversational AI assistant for asking questions about code, generating solutions, and debugging directly in your editor.
  name: Chat
- description: Autonomous agent that explores code, makes changes, runs tests, and opens pull requests from issue assignments.
  name: Coding Agent
- description: AI-powered pull request review that analyzes changes, identifies issues, and suggests fixes across any language.
  name: Code Review
- description: Third-party integrations that extend Copilot Chat with custom tools, services, and domain-specific agents.
  name: Extensions
- description: Repository-level and organization-level configuration to guide Copilot behavior, code style, and conventions.
  name: Custom Instructions
- description: Model Context Protocol server enabling AI tools to interact with GitHub repositories, issues, and pull requests.
  name: MCP Server
- description: Governance controls to specify which files and repositories Copilot can access at organization and enterprise level.
  name: Content Exclusion
- description: Detailed analytics on Copilot adoption, usage patterns, and productivity impact across organizations and enterprises.
  name: Usage Metrics
- description: Programmatic management of Copilot seat assignments, billing, and subscription details for organizations and teams.
  name: Seat Management
image: https://github.githubassets.com/images/modules/site/copilot/copilot-logo.png
integrations:
- description: Full Copilot integration in VS Code including code completion, chat, code review, and MCP support.
  name: Visual Studio Code
- description: Copilot code completion and chat support across IntelliJ, PyCharm, WebStorm, and other JetBrains IDEs.
  name: JetBrains IDEs
- description: Copilot Chat, code review, and coding agent capabilities directly in the GitHub web interface.
  name: GitHub.com
- description: Copilot coding agent uses GitHub Actions to spin up secure environments for autonomous coding tasks.
  name: GitHub Actions
- description: Standard protocol integration enabling AI tools to access GitHub data through the official MCP server.
  name: Model Context Protocol
jsonld:
- class_count: 0
  name: Github Copilot Context
  property_count: 0
  slug: github-copilot-context
layout: provider
modified: '2026-04-18'
name: GitHub Copilot
rules:
- name: GitHub Copilot API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: github-copilot-spectral-rules
skills: []
slug: github-copilot
solutions: []
source_yaml: "name: GitHub Copilot\ndescription: >-\n  APIs and resources for GitHub Copilot, an AI pair programmer that helps you write\n  code faster.\nimage: https://github.githubassets.com/images/modules/site/copilot/copilot-logo.png\nurl: https://api.github.com/apis.yaml\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Contract\naccess: 3rd-Party\napis:\n  - name: GitHub Copilot API\n    description: >-\n      REST API for managing GitHub Copilot seats, usage, and organization settings.\n    image: https://github.githubassets.com/images/modules/site/copilot/copilot-logo.png\n    humanURL: https://docs.github.com/en/copilot\n    baseURL: https://api.github.com\n    tags:\n      - AI\n      - Code Completion\n      - Developer Tools\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n\
  \      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: GettingStarted\n        url: https://docs.github.com/en/copilot/quickstart\n      - type: Features\n        url: https://docs.github.com/en/copilot/get-started/features\n      - type: Plans\n        url: https://docs.github.com/en/copilot/get-started/plans\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/github-copilot-seat-schema.json\n      - type: JSONSchema\n        url: json-schema/github-copilot-metrics-schema.json\n      - type: JSONLD\n        url: json-ld/github-copilot-context.jsonld\n    contact:\n      - FN: GitHub Support\n        email: support@github.com\n        url: https://support.github.com\n  - name: GitHub Copilot for Business API\n    description: >-\n      Manage Copilot for Business subscriptions, seat assignments, and usage metrics.\n    humanURL: https://docs.github.com/en/copilot/managing-copilot-for-business\n\
  \    baseURL: https://api.github.com\n    tags:\n      - Enterprise\n      - Seat Management\n      - Usage Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot/copilot-for-business\n      - type: Pricing\n        url: https://github.com/features/copilot#pricing\n      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/github-copilot-seat-schema.json\n  - name: GitHub Copilot Chat API\n    description: >-\n      API for GitHub Copilot Chat interactions and conversations.\n    humanURL: https://docs.github.com/en/copilot/github-copilot-chat\n    baseURL: https://api.github.com\n    tags:\n      - Chat\n      - Conversational AI\n\
  \      - IDE Integration\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/github-copilot-chat\n      - type: GettingStarted\n        url: https://docs.github.com/en/copilot/quickstart\n      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n  - name: GitHub Copilot User Management API\n    description: >-\n      REST API for managing GitHub Copilot seat assignments, billing information,\n      and subscription details for organizations including adding and removing users\n      and teams.\n    humanURL: https://docs.github.com/en/rest/copilot/copilot-user-management\n    baseURL: https://api.github.com\n    tags:\n      - Billing\n      - Organizations\n      - Seat Management\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot/copilot-user-management\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n\
  \      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/github-copilot-seat-schema.json\n      - type: JSONLD\n        url: json-ld/github-copilot-context.jsonld\n  - name: GitHub Copilot Metrics API\n    description: >-\n      REST API for retrieving aggregated Copilot usage metrics at the organization\n      and team level, including data on active users, engaged users, and breakdowns\n      by language and editor.\n    humanURL: https://docs.github.com/en/rest/copilot/copilot-metrics\n    baseURL: https://api.github.com\n    tags:\n      - Analytics\n      - Metrics\n      - Organizations\n      - Usage\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot/copilot-metrics\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n\
  \      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/github-copilot-metrics-schema.json\n      - type: JSONLD\n        url: json-ld/github-copilot-context.jsonld\n  - name: GitHub Copilot Usage Metrics API\n    description: >-\n      REST API for retrieving detailed Copilot usage metrics reports at the enterprise\n      and organization level, including daily and 28-day aggregated reports for both\n      entity-level and user-level data.\n    humanURL: https://docs.github.com/en/rest/copilot/copilot-usage-metrics\n    baseURL: https://api.github.com\n    tags:\n      - Analytics\n      - Enterprise\n      - Reporting\n      - Usage Metrics\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot/copilot-usage-metrics\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n\
  \      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/github-copilot-metrics-schema.json\n      - type: JSONLD\n        url: json-ld/github-copilot-context.jsonld\n  - name: GitHub Copilot Content Exclusion API\n    description: >-\n      REST API for programmatically managing Copilot content exclusion path rules\n      at both the organization and enterprise level, enabling automation and governance\n      of which content Copilot can access.\n    humanURL: https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management\n    baseURL: https://api.github.com\n    tags:\n      - Content Exclusion\n      - Governance\n      - Policy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management\n      - type: OpenAPI\n        url:\
  \ https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n      - type: OpenAPI\n        url: openapi/github-copilot-openapi.yml\n      - type: JSONLD\n        url: json-ld/github-copilot-context.jsonld\n  - name: GitHub Copilot Extensions API\n    description: >-\n      Platform for building Copilot Extensions that integrate third-party tools,\n      services, and custom agents into GitHub Copilot Chat, using GitHub Apps with\n      agent or skillset configurations.\n    humanURL: https://docs.github.com/en/copilot/building-copilot-extensions\n    baseURL: https://api.github.com\n    tags:\n      - Agents\n      - Extensions\n      - Integrations\n      - Skillsets\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/building-copilot-extensions/about-building-copilot-extensions\n      - type: GettingStarted\n\
  \        url: https://docs.github.com/en/copilot/building-copilot-extensions/creating-a-copilot-extension\n      - type: SDK\n        url: https://github.com/github/copilot-sdk\n      - type: GitHubOrganization\n        url: https://github.com/copilot-extensions\n      - type: CodeExamples\n        url: https://github.com/copilot-extensions/skillset-example\n  - name: GitHub Copilot Coding Agent\n    description: >-\n      Autonomous coding agent that works in the background to complete tasks, spinning\n      up secure development environments powered by GitHub Actions to explore code,\n      make changes, run tests, and open pull requests.\n    humanURL: https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent\n    baseURL: https://api.github.com\n    tags:\n      - Agents\n      - Automation\n      - Code Generation\n      - GitHub Actions\n      - Pull Requests\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent\n\
  \    contact:\n      - FN: GitHub Support\n        email: support@github.com\n        url: https://support.github.com\n  - name: GitHub Copilot Code Review\n    description: >-\n      AI-powered code review agent that analyzes pull requests for issues, suggests\n      fixes, and provides feedback across any programming language with agentic context\n      gathering capabilities.\n    humanURL: https://docs.github.com/en/copilot/concepts/agents/code-review\n    baseURL: https://api.github.com\n    tags:\n      - Agents\n      - Code Quality\n      - Code Review\n      - Pull Requests\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/concepts/agents/code-review\n    contact:\n      - FN: GitHub Support\n        email: support@github.com\n        url: https://support.github.com\n  - name: GitHub MCP Server\n    description: >-\n      GitHub official Model Context Protocol server that enables AI tools to interact\n      with GitHub repositories,\
  \ issues, pull requests, and other resources through\n      a standardized protocol.\n    humanURL: https://docs.github.com/en/copilot/concepts/context/mcp\n    baseURL: https://api.github.com\n    tags:\n      - Agents\n      - Context\n      - Integrations\n      - MCP\n      - Model Context Protocol\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/concepts/context/mcp\n      - type: GitHubRepository\n        url: https://github.com/github/github-mcp-server\n      - type: GettingStarted\n        url: https://docs.github.com/en/copilot/how-tos/provide-context/use-mcp/set-up-the-github-mcp-server\n    contact:\n      - FN: GitHub Support\n        email: support@github.com\n        url: https://support.github.com\n  - name: GitHub Copilot Custom Instructions\n    description: >-\n      Configuration system for providing repository-level, path-specific, and\n      organization-level custom instructions to guide Copilot behavior, code style,\n\
  \      and response formatting.\n    humanURL: https://docs.github.com/en/copilot/how-tos/configure-custom-instructions\n    baseURL: https://api.github.com\n    tags:\n      - Configuration\n      - Customization\n      - Instructions\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/copilot/how-tos/configure-custom-instructions\n    contact:\n      - FN: GitHub Support\n        email: support@github.com\n        url: https://support.github.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: http://apievangelist.com\ntags:\n  - Agents\n  - AI\n  - Artificial Intelligence\n  - Code Generation\n  - Code Review\n  - Coding Agent\n  - Custom Instructions\n  - Developer Tools\n  - Extensions\n  - IDE\n  - Machine Learning\n  - MCP\n  - Metrics\n  - Model Context Protocol\n  - Productivity\ncommon:\n  - type: Portal\n    url: https://github.com/features/copilot\n  - type: StatusPage\n    url: https://www.githubstatus.com/\n\
  \  - type: TermsOfService\n    url: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\n  - type: PrivacyPolicy\n    url: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement\n  - type: GettingStarted\n    url: https://docs.github.com/en/copilot/quickstart\n  - type: Blog\n    url: https://github.blog/tag/github-copilot/\n  - type: SignUp\n    url: https://github.com/github-copilot/signup\n  - type: Pricing\n    url: https://github.com/features/copilot/plans\n  - type: ChangeLog\n    url: https://github.blog/changelog/label/copilot/\n  - type: Support\n    url: https://support.github.com\n  - type: SDK\n    url: https://github.com/github/copilot-sdk\n  - type: TrustCenter\n    url: https://copilot.github.trust.page/\n  - type: RateLimits\n    url: https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api\n  - type: Authentication\n    url: https://docs.github.com/en/rest/authentication\n  - type: OpenAPI\n    url: https://github.com/github/rest-api-description\n\
  \  - type: Documentation\n    url: https://docs.github.com/en/copilot\n  - type: Marketplace\n    url: https://github.com/marketplace?type=apps&copilot_app=true\n  - type: Features\n    data:\n      - name: Code Completion\n        description: AI-powered inline code suggestions that complete lines, functions, and entire blocks as you type in your IDE.\n      - name: Chat\n        description: Conversational AI assistant for asking questions about code, generating solutions, and debugging directly in your editor.\n      - name: Coding Agent\n        description: Autonomous agent that explores code, makes changes, runs tests, and opens pull requests from issue assignments.\n      - name: Code Review\n        description: AI-powered pull request review that analyzes changes, identifies issues, and suggests fixes across any language.\n      - name: Extensions\n        description: Third-party integrations that extend Copilot Chat with custom tools, services, and domain-specific agents.\n\
  \      - name: Custom Instructions\n        description: Repository-level and organization-level configuration to guide Copilot behavior, code style, and conventions.\n      - name: MCP Server\n        description: Model Context Protocol server enabling AI tools to interact with GitHub repositories, issues, and pull requests.\n      - name: Content Exclusion\n        description: Governance controls to specify which files and repositories Copilot can access at organization and enterprise level.\n      - name: Usage Metrics\n        description: Detailed analytics on Copilot adoption, usage patterns, and productivity impact across organizations and enterprises.\n      - name: Seat Management\n        description: Programmatic management of Copilot seat assignments, billing, and subscription details for organizations and teams.\n  - type: UseCases\n    data:\n      - name: Developer Productivity\n        description: Accelerate software development with AI-powered code completions, chat\
  \ assistance, and automated code review.\n      - name: Enterprise Copilot Governance\n        description: Manage Copilot deployments at scale with seat management, content exclusion, usage metrics, and compliance controls.\n      - name: Custom AI Tooling\n        description: Build domain-specific Copilot Extensions and agents that integrate third-party tools and services into the developer workflow.\n      - name: Code Quality Automation\n        description: Automate code review, identify potential issues, and enforce coding standards using the Copilot Code Review agent.\n  - type: Integrations\n    data:\n      - name: Visual Studio Code\n        description: Full Copilot integration in VS Code including code completion, chat, code review, and MCP support.\n      - name: JetBrains IDEs\n        description: Copilot code completion and chat support across IntelliJ, PyCharm, WebStorm, and other JetBrains IDEs.\n      - name: GitHub.com\n        description: Copilot Chat, code review,\
  \ and coding agent capabilities directly in the GitHub web interface.\n      - name: GitHub Actions\n        description: Copilot coding agent uses GitHub Actions to spin up secure environments for autonomous coding tasks.\n      - name: Model Context Protocol\n        description: Standard protocol integration enabling AI tools to access GitHub data through the official MCP server.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/github-copilot/refs/heads/main/apis.yml
tags:
- Agents
- AI
- Artificial Intelligence
- Code Generation
- Code Review
- Coding Agent
- Custom Instructions
- Developer Tools
- Extensions
- IDE
- Machine Learning
- MCP
- Metrics
- Model Context Protocol
- Productivity
url: https://api.github.com/apis.yaml
use_cases:
- description: Accelerate software development with AI-powered code completions, chat assistance, and automated code review.
  name: Developer Productivity
- description: Manage Copilot deployments at scale with seat management, content exclusion, usage metrics, and compliance controls.
  name: Enterprise Copilot Governance
- description: Build domain-specific Copilot Extensions and agents that integrate third-party tools and services into the developer workflow.
  name: Custom AI Tooling
- description: Automate code review, identify potential issues, and enforce coding standards using the Copilot Code Review agent.
  name: Code Quality Automation
---
