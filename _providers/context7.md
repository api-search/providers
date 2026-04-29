---
api_count: 3
apis:
- description: 'The Context7 REST API exposes endpoints for searching libraries, retrieving documentation context for LLMs, refreshing indexed sources, and submitting new sources (GitHub repositories, OpenAPI specs, '
  name: Context7 REST API
  slug: rest-api
- description: The Context7 MCP Server implements the Model Context Protocol so AI coding assistants such as Cursor, Claude, and Windsurf can call Context7 tools directly from a developer's editor. It exposes resolv
  name: Context7 MCP Server
  slug: mcp-server
- description: The Context7 CLI (ctx7) is a command-line tool for querying the Context7 index from the terminal. It provides ctx7 library for searching the catalog by library name and ctx7 docs for retrieving docume
  name: Context7 CLI
  slug: cli
common:
- title: ''
  type: Website
  url: https://context7.com/
- title: ''
  type: Documentation
  url: https://context7.com/docs
- title: ''
  type: Dashboard
  url: https://context7.com/dashboard
- title: ''
  type: GitHub Organization
  url: https://github.com/upstash
- title: ''
  type: GitHubRepository
  url: https://github.com/upstash/context7
- title: ''
  type: Pricing
  url: https://context7.com/pricing
created: '2026-03-16'
description: Context7 is an Upstash service providing up-to-date, version-specific documentation and code examples for libraries and frameworks, exposed as both a REST API and a Model Context Protocol (MCP) server so AI coding assistants can fetch authoritative reference material at prompt time.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Context7
skills: []
slug: context7
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: context7\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/context7/refs/heads/main/apis.yml\nname: Context7\ndescription: >-\n  Context7 is an Upstash service providing up-to-date, version-specific\n  documentation and code examples for libraries and frameworks, exposed as\n  both a REST API and a Model Context Protocol (MCP) server so AI coding\n  assistants can fetch authoritative reference material at prompt time.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Context\n  - Documentation\n  - LLM\n  - MCP\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: context7:rest-api\n    name: Context7 REST API\n    tags:\n      - Documentation\n      - LLM\n      - REST\n      - Search\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://context7.com/api\n  \
  \  humanURL: https://context7.com/docs/api-guide\n    properties:\n      - url: https://context7.com/docs/api-guide\n        type: Documentation\n      - url: https://context7.com/docs/llms.txt\n        type: LLMsTxt\n    description: >-\n      The Context7 REST API exposes endpoints for searching libraries,\n      retrieving documentation context for LLMs, refreshing indexed sources,\n      and submitting new sources (GitHub repositories, OpenAPI specs, llms.txt\n      files, websites, and Confluence spaces). Endpoints span v1 and v2 paths\n      under https://context7.com/api and use Bearer token authentication with\n      keys issued from the Context7 dashboard.\n\n  - aid: context7:mcp-server\n    name: Context7 MCP Server\n    tags:\n      - AI\n      - Context\n      - LLM\n      - MCP\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://mcp.context7.com/mcp\n    humanURL: https://github.com/upstash/context7\n    properties:\n\
  \      - url: https://github.com/upstash/context7\n        type: Documentation\n      - url: https://github.com/upstash/context7\n        type: GitHubRepository\n    description: >-\n      The Context7 MCP Server implements the Model Context Protocol so AI\n      coding assistants such as Cursor, Claude, and Windsurf can call Context7\n      tools directly from a developer's editor. It exposes resolve-library-id\n      (mapping a library name to a Context7-compatible identifier) and\n      query-docs (returning documentation snippets for a given library and\n      query) and is hosted at https://mcp.context7.com/mcp with API key\n      authentication.\n\n  - aid: context7:cli\n    name: Context7 CLI\n    tags:\n      - CLI\n      - Documentation\n      - Tooling\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/upstash/context7\n    properties:\n      - url: https://github.com/upstash/context7\n        type: Documentation\n\
  \      - url: https://github.com/upstash/context7\n        type: GitHubRepository\n    description: >-\n      The Context7 CLI (ctx7) is a command-line tool for querying the Context7\n      index from the terminal. It provides ctx7 library for searching the\n      catalog by library name and ctx7 docs for retrieving documentation\n      using a Context7-compatible library ID, useful for scripting and local\n      developer workflows.\n\ncommon:\n  - type: Website\n    url: https://context7.com/\n  - type: Documentation\n    url: https://context7.com/docs\n  - type: Dashboard\n    url: https://context7.com/dashboard\n  - type: GitHub Organization\n    url: https://github.com/upstash\n  - type: GitHubRepository\n    url: https://github.com/upstash/context7\n  - type: Pricing\n    url: https://context7.com/pricing\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/context7/refs/heads/main/apis.yml
tags:
- AI
- Context
- Documentation
- LLM
- MCP
url: https://raw.githubusercontent.com/api-evangelist/context7/refs/heads/main/apis.yml
use_cases: []
---
