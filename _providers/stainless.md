---
api_count: 5
apis:
- description: Generate production-ready SDKs in TypeScript, Python, Go, Java, Kotlin, Ruby, C#, PHP, and Terraform from an OpenAPI specification. Stainless handles HTTP requests, retries with exponential backoff, s
  name: Stainless SDK Generator
  slug: stainless
- description: The Stainless Docs Platform combines your API reference, usage examples, and narrative guides into a single, cohesive experience that evolves with your API. Go from an OpenAPI spec to a live, interact
  name: Stainless Docs Platform
  slug: stainless-docs-platform
- description: 'Stainless generates production-ready MCP (Model Context Protocol) servers optimized for agentic coding and context limits directly from an OpenAPI spec. Production-grade capabilities including OAuth, '
  name: Stainless MCP Servers
  slug: stainless-mcp-servers
- description: The Stainless CLI generates production-ready command-line interfaces from an OpenAPI specification. Generated CLIs provide a consistent, typed interface for interacting with any API from the terminal.
  name: Stainless CLI
  slug: stainless-cli
- description: Stainless generates production-ready Terraform providers from an OpenAPI specification, enabling infrastructure-as-code access to any REST API without manual Terraform provider development.
  name: Stainless Terraform Providers
  slug: stainless-terraform
common:
- title: ''
  type: Portal
  url: https://www.stainless.com/
- title: ''
  type: Documentation
  url: https://www.stainless.com/docs/
- title: ''
  type: Pricing
  url: https://www.stainless.com/pricing
- title: ''
  type: Blog
  url: https://www.stainless.com/blog
- title: ''
  type: Change Log
  url: https://www.stainless.com/changelog
- title: ''
  type: Login
  url: https://app.stainless.com/login
- title: ''
  type: About
  url: https://www.stainless.com/company
- title: ''
  type: GitHub Organization
  url: https://github.com/stainless-api
- title: ''
  type: TermsOfService
  url: https://www.stainless.com/legal/terms-conditions
- title: ''
  type: Customers
  url: https://www.stainless.com/customers
created: '2025-01-08'
description: Stainless is an API developer experience platform that generates best-in-class SDKs, interactive documentation, production-ready CLI tools, MCP servers, and Terraform providers directly from an OpenAPI specification. Trusted by Anthropic, Cloudflare, Google, and OpenAI, Stainless automates the boilerplate of client library development including HTTP requests, retries with exponential backoff, streaming, and pagination. The platform supports TypeScript, Python, Go, Java, Kotlin, Ruby, C#, PHP, and Terraform, with Rust and Swift in development.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Stainless Context
  property_count: 4
  slug: stainless-context
layout: provider
modified: '2026-05-02'
name: Stainless
skills: []
slug: stainless
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stainless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stainless/refs/heads/main/apis.yml\nname: Stainless\ndescription: >-\n  Stainless is an API developer experience platform that generates best-in-class\n  SDKs, interactive documentation, production-ready CLI tools, MCP servers, and\n  Terraform providers directly from an OpenAPI specification. Trusted by Anthropic,\n  Cloudflare, Google, and OpenAI, Stainless automates the boilerplate of client\n  library development including HTTP requests, retries with exponential backoff,\n  streaming, and pagination. The platform supports TypeScript, Python, Go, Java,\n  Kotlin, Ruby, C#, PHP, and Terraform, with Rust and Swift in development.\ntags:\n  - Code Generation\n  - Documentation\n  - Developer Experience\n  - MCP\n  - Platform\n  - SDKs\n  - Terraform\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-05-02'\n\
  position: Consumer\nsegments:\n  - SDKs\n  - Developer Tooling\ncommon:\n  - url: https://www.stainless.com/\n    type: Portal\n  - url: https://www.stainless.com/docs/\n    type: Documentation\n  - url: https://www.stainless.com/pricing\n    type: Pricing\n  - url: https://www.stainless.com/blog\n    type: Blog\n  - url: https://www.stainless.com/changelog\n    type: Change Log\n  - url: https://app.stainless.com/login\n    type: Login\n  - url: https://www.stainless.com/company\n    type: About\n  - url: https://github.com/stainless-api\n    type: GitHub Organization\n  - url: https://www.stainless.com/legal/terms-conditions\n    type: TermsOfService\n  - url: https://www.stainless.com/customers\n    type: Customers\napis:\n  - aid: stainless:stainless\n    name: Stainless SDK Generator\n    tags:\n      - Code Generation\n      - Developer Experience\n      - SDKs\n    humanURL: https://www.stainless.com/\n    description: >-\n      Generate production-ready SDKs in TypeScript, Python,\
  \ Go, Java, Kotlin,\n      Ruby, C#, PHP, and Terraform from an OpenAPI specification. Stainless\n      handles HTTP requests, retries with exponential backoff, streaming,\n      pagination, and idiomatic patterns for each language. Trusted by\n      Anthropic, Cloudflare, Google, and OpenAI.\n    properties:\n      - url: https://www.stainless.com/\n        type: Documentation\n      - url: https://www.stainless.com/docs/\n        type: GettingStarted\n      - url: https://www.stainless.com/pricing\n        type: Pricing\n      - url: https://www.stainless.com/customers\n        type: Customers\n      - url: https://github.com/stainless-api/upload-openapi-spec-action\n        type: GitHubAction\n      - url: https://github.com/stainless-api/build-sdk-action\n        type: GitHubAction\n\n  - aid: stainless:stainless-docs-platform\n    name: Stainless Docs Platform\n    tags:\n      - API Reference\n      - Developer Experience\n      - Documentation\n    humanURL: https://www.stainless.com/products/docs\n\
  \    description: >-\n      The Stainless Docs Platform combines your API reference, usage examples,\n      and narrative guides into a single, cohesive experience that evolves with\n      your API. Go from an OpenAPI spec to a live, interactive documentation\n      site in minutes with a developer-centric docs-as-code workflow built on\n      Astro. Deploys to Cloudflare or custom clouds.\n    properties:\n      - url: https://www.stainless.com/products/docs\n        type: Documentation\n      - url: https://www.stainless.com/docs/docs-platform/\n        type: GettingStarted\n\n  - aid: stainless:stainless-mcp-servers\n    name: Stainless MCP Servers\n    tags:\n      - AI Agents\n      - Code Generation\n      - MCP\n    humanURL: https://www.stainless.com/products/mcp\n    description: >-\n      Stainless generates production-ready MCP (Model Context Protocol) servers\n      optimized for agentic coding and context limits directly from an OpenAPI\n      spec. Production-grade capabilities\
  \ including OAuth, SSE, and remote\n      servers are included by default. Generated MCP servers use a code tool\n      architecture enabling seamless integration with Claude Desktop, Cursor,\n      and other MCP clients.\n    properties:\n      - url: https://www.stainless.com/products/mcp\n        type: Documentation\n      - url: https://www.stainless.com/docs/targets/mcp/\n        type: GettingStarted\n      - url: https://www.stainless.com/mcp\n        type: Portal\n\n  - aid: stainless:stainless-cli\n    name: Stainless CLI\n    tags:\n      - CLI\n      - Code Generation\n      - Developer Tools\n    humanURL: https://www.stainless.com/docs/\n    description: >-\n      The Stainless CLI generates production-ready command-line interfaces from\n      an OpenAPI specification. Generated CLIs provide a consistent, typed\n      interface for interacting with any API from the terminal.\n    properties:\n      - url: https://www.stainless.com/docs/\n        type: Documentation\n\n  - aid:\
  \ stainless:stainless-terraform\n    name: Stainless Terraform Providers\n    tags:\n      - Code Generation\n      - Infrastructure as Code\n      - Terraform\n    humanURL: https://www.stainless.com/docs/\n    description: >-\n      Stainless generates production-ready Terraform providers from an OpenAPI\n      specification, enabling infrastructure-as-code access to any REST API\n      without manual Terraform provider development.\n    properties:\n      - url: https://www.stainless.com/docs/\n        type: Documentation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stainless/refs/heads/main/apis.yml
tags:
- Code Generation
- Documentation
- Developer Experience
- MCP
- Platform
- SDKs
- Terraform
url: https://raw.githubusercontent.com/api-evangelist/stainless/refs/heads/main/apis.yml
use_cases: []
---
