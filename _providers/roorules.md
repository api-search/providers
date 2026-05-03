---
api_count: 3
apis:
- description: Roo Code is an AI-powered autonomous coding agent for VS Code that reads and writes code across multiple files, executes terminal commands, manages browser interactions, and adapts to custom modes def
  name: Roo Code VS Code Extension
  slug: roo-code-extension-api
- description: Roo Code supports the Model Context Protocol (MCP), allowing it to connect to external MCP servers for extended tool access including file systems, databases, APIs, and cloud services. MCP servers are
  name: Roo Code MCP Integration
  slug: roo-code-mcp-integration
- description: API Configuration Profiles allow Roo Code users to create and switch between different sets of AI provider settings. Each profile configures a specific model and provider (e.g., Claude 3.7 Sonnet on A
  name: Roo Code API Configuration Profiles
  slug: roo-code-api-configuration
common:
- title: ''
  type: Website
  url: https://roocode.com/
- title: ''
  type: Documentation
  url: https://docs.roocode.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/RooCodeInc
- title: ''
  type: GitHubRepository
  url: https://github.com/RooCodeInc/Roo-Code
- title: ''
  type: Vocabulary
  url: vocabulary/roorules-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/roorules-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/roorules-config-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/roorules-config-structure.json
- title: ''
  type: Marketplace
  url: https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline
- title: ''
  type: Discord
  url: https://discord.gg/roocode
- title: ''
  type: X
  url: https://twitter.com/roo_code
created: '2025-01-01'
description: .roorules is a configuration file convention for Roo Code, an open-source AI-powered autonomous coding assistant built for VS Code. The .roorules file allows developers to define project-specific coding conventions, style rules, architecture guidelines, and behavioral instructions that guide Roo Code AI agents when working within a codebase. Roo Code supports multiple AI providers including Anthropic Claude, OpenAI GPT-4, Google Gemini, and local LLMs via OpenAI-compatible APIs.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Roorules Context
  property_count: 6
  slug: roorules-context
layout: provider
modified: '2026-05-02'
name: .Roorules
skills: []
slug: roorules
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: roorules\nname: .Roorules\ndescription: >-\n  .roorules is a configuration file convention for Roo Code, an open-source\n  AI-powered autonomous coding assistant built for VS Code. The .roorules file\n  allows developers to define project-specific coding conventions, style rules,\n  architecture guidelines, and behavioral instructions that guide Roo Code\n  AI agents when working within a codebase. Roo Code supports multiple AI\n  providers including Anthropic Claude, OpenAI GPT-4, Google Gemini, and local\n  LLMs via OpenAI-compatible APIs.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/roorules/refs/heads/main/apis.yml\ntags:\n  - AI Agents\n  - AI Copilot\n  - Coding Assistant\n  - Coding Standards\n  - Developer Workflow\n  - LLM\n  - MCP\n  - Roo Code\n  - VS Code\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: roorules:roo-code-extension-api\n    name: Roo Code VS Code Extension\n    description:\
  \ >-\n      Roo Code is an AI-powered autonomous coding agent for VS Code that reads\n      and writes code across multiple files, executes terminal commands, manages\n      browser interactions, and adapts to custom modes defined through .roorules\n      and .roomodes configuration files. It supports API configuration profiles\n      enabling switching between different AI providers and models per workflow.\n    humanURL: https://roocode.com/\n    properties:\n      - type: Documentation\n        url: https://docs.roocode.com/\n      - type: GitHub\n        url: https://github.com/RooCodeInc/Roo-Code\n      - type: Vocabulary\n        url: vocabulary/roorules-vocabulary.yml\n      - type: JSONSchema\n        url: json-schema/roorules-config-schema.json\n      - type: JSONStructure\n        url: json-structure/roorules-config-structure.json\n    tags:\n      - AI Agents\n      - AI Copilot\n      - Coding Assistant\n      - Developer Workflow\n      - VS Code\n  - aid: roorules:roo-code-mcp-integration\n\
  \    name: Roo Code MCP Integration\n    description: >-\n      Roo Code supports the Model Context Protocol (MCP), allowing it to connect\n      to external MCP servers for extended tool access including file systems,\n      databases, APIs, and cloud services. MCP servers are configured in the\n      Roo Code settings and expose tools that AI agents can use during coding\n      workflows.\n    humanURL: https://docs.roocode.com/features/mcp/\n    properties:\n      - type: Documentation\n        url: https://docs.roocode.com/features/mcp/\n    tags:\n      - AI Agents\n      - Integration\n      - MCP\n      - Model Context Protocol\n  - aid: roorules:roo-code-api-configuration\n    name: Roo Code API Configuration Profiles\n    description: >-\n      API Configuration Profiles allow Roo Code users to create and switch\n      between different sets of AI provider settings. Each profile configures\n      a specific model and provider (e.g., Claude 3.7 Sonnet on Anthropic,\n      GPT-4o\
  \ on OpenAI, Gemini Pro on Google) and can be mapped to specific\n      Roo Code modes (Architect, Code, Debug, Ask).\n    humanURL: https://docs.roocode.com/features/api-configuration-profiles\n    properties:\n      - type: Documentation\n        url: https://docs.roocode.com/features/api-configuration-profiles\n    tags:\n      - AI Agents\n      - Configuration\n      - Developer Workflow\n      - LLM\ncommon:\n  - type: Website\n    url: https://roocode.com/\n  - type: Documentation\n    url: https://docs.roocode.com/\n  - type: GitHub Organization\n    url: https://github.com/RooCodeInc\n  - type: GitHubRepository\n    url: https://github.com/RooCodeInc/Roo-Code\n  - type: Vocabulary\n    url: vocabulary/roorules-vocabulary.yml\n  - type: JSON-LD\n    url: json-ld/roorules-context.jsonld\n  - type: JSONSchema\n    url: json-schema/roorules-config-schema.json\n  - type: JSONStructure\n    url: json-structure/roorules-config-structure.json\n  - type: Marketplace\n    url: https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline\n\
  \  - type: Discord\n    url: https://discord.gg/roocode\n  - type: X\n    url: https://twitter.com/roo_code\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/roorules/refs/heads/main/apis.yml
tags:
- AI Agents
- AI Copilot
- Coding Assistant
- Coding Standards
- Developer Workflow
- LLM
- MCP
- Roo Code
- VS Code
url: https://raw.githubusercontent.com/api-evangelist/roorules/refs/heads/main/apis.yml
use_cases: []
---
