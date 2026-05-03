---
api_count: 1
api_specs:
- filename: smithery-openapi.json
  format: json
  label: Smithery Registry API
  slug: registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/openapi/smithery-openapi.json
apis:
- description: The Smithery Registry API provides access to the MCP server registry, enabling search and discovery of community-built MCP servers and skills. Supports server management, skill publishing, namespace m
  name: Smithery Registry API
  slug: registry-api
capabilities:
- description: 'Workflow capability for discovering, evaluating, and managing Model Context Protocol servers in the Smithery registry. Used by AI developers and platform engineers to find the right MCP capabilities, '
  name: Smithery MCP Server Discovery
  slug: mcp-server-discovery
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/smithery-ai
- title: ''
  type: Documentation
  url: https://smithery.ai/docs
- title: ''
  type: CLI
  url: https://smithery.ai/docs/concepts/cli
- title: ''
  type: Website
  url: https://smithery.ai/
- title: ''
  type: Playground
  url: https://smithery.ai/playground
- title: ''
  type: Blog
  url: https://smithery.ai/blog
- title: ''
  type: Authentication
  url: https://smithery.ai/account/api-keys
- title: ''
  type: Documentation
  url: https://smithery.ai/skills
- title: ''
  type: SDK
  url: https://github.com/smithery-ai/cli
created: '2025-08-19'
description: Smithery is a platform for discovering, deploying, and managing Model Context Protocol (MCP) servers and skills. It provides a registry of 6000+ community-built MCP extensions that AI agents can use to access external tools, data sources, and services. The platform offers APIs for server management, skill discovery, connection management, and AI-agent integration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Smithery Context
  property_count: 0
  slug: smithery-context
layout: provider
modified: '2026-05-02'
name: Smithery
rules:
- name: Smithery API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: smithery-rules
skills: []
slug: smithery
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smithery\nname: Smithery\ndescription: >-\n  Smithery is a platform for discovering, deploying, and managing Model Context\n  Protocol (MCP) servers and skills. It provides a registry of 6000+ community-built\n  MCP extensions that AI agents can use to access external tools, data sources, and\n  services. The platform offers APIs for server management, skill discovery, connection\n  management, and AI-agent integration.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Large Language Models\n  - MCP\n  - Model Context Protocol\n  - AI Agents\n  - Developer Tools\ncreated: '2025-08-19'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: smithery:registry-api\n    name: Smithery Registry API\n    description: >-\n      The Smithery Registry\
  \ API provides access to the MCP server registry,\n      enabling search and discovery of community-built MCP servers and skills.\n      Supports server management, skill publishing, namespace management,\n      connection handling, and token-based machine-to-machine authentication.\n    humanURL: https://smithery.ai/docs\n    baseURL: https://api.smithery.ai\n    tags:\n      - Artificial Intelligence\n      - MCP\n      - Registry\n      - Servers\n      - Skills\n    properties:\n      - type: Documentation\n        url: https://smithery.ai/docs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/openapi/smithery-openapi.json\n      - type: OpenAPI Specification\n        url: https://smithery.ai/docs/openapi.json\n\ncommon:\n  - url: https://github.com/smithery-ai\n    name: GitHub Organization\n    type: GitHubOrganization\n  - name: Smithery Documentation\n    description: Complete API documentation and developer guides\n\
  \    url: https://smithery.ai/docs\n    type: Documentation\n  - name: Smithery CLI\n    description: Command-line interface for managing MCP servers and skills\n    url: https://smithery.ai/docs/concepts/cli\n    type: CLI\n  - name: Smithery Website\n    description: Main platform for discovering and using MCP extensions\n    url: https://smithery.ai/\n    type: Website\n  - name: Smithery Playground\n    description: Interactive playground for testing MCP servers\n    url: https://smithery.ai/playground\n    type: Playground\n  - name: Smithery Blog\n    description: Blog covering MCP, AI agents, and platform updates\n    url: https://smithery.ai/blog\n    type: Blog\n  - name: API Keys\n    description: Manage API keys for Smithery platform access\n    url: https://smithery.ai/account/api-keys\n    type: Authentication\n  - name: Skills Directory\n    description: Browse reusable skills and prompt-based AI capabilities\n    url: https://smithery.ai/skills\n    type: Documentation\n\
  \  - name: CLI GitHub Repository\n    description: Smithery CLI source code and documentation\n    url: https://github.com/smithery-ai/cli\n    type: SDK\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Large Language Models
- MCP
- Model Context Protocol
- AI Agents
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/apis.yml
use_cases: []
---
