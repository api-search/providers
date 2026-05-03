---
api_count: 1
api_specs:
- filename: resend-openapi.yml
  format: yaml
  label: Resend API
  slug: resend
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/openapi/resend-openapi.yml
apis:
- description: The Resend REST API provides endpoints for sending emails, managing domains, managing API keys, managing audiences and contacts, and sending broadcast campaigns. Authentication uses Bearer tokens. Rat
  name: Resend API
  slug: resend
capabilities:
- description: Workflow capability for sending and managing transactional emails, batch email campaigns, scheduled emails, domain configuration, and audience-based broadcast campaigns using the Resend email API.
  name: Resend Email Delivery
  slug: email-delivery
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/resend
- title: ''
  type: ChangeLog
  url: https://resend.com/changelog
- title: ''
  type: Blog
  url: https://resend.com/blog
- title: ''
  type: Migrations
  url: https://resend.com/migrate
- title: ''
  type: Customers
  url: https://resend.com/customers
- title: ''
  type: About
  url: https://resend.com/about
- title: ''
  type: Security
  url: https://resend.com/security
- title: ''
  type: Examples
  url: https://resend.com/docs/examples
- title: ''
  type: SDKs
  url: https://resend.com/docs/sdks
- title: ''
  type: Pricing
  url: https://resend.com/pricing
- title: ''
  type: Login
  url: https://resend.com/login
- title: ''
  type: SignUp
  url: https://resend.com/signup
- title: ''
  type: SDK
  url: https://github.com/resend/resend-node
- title: ''
  type: SDK
  url: https://github.com/resend/resend-python
- title: ''
  type: SDK
  url: https://github.com/resend/resend-go
- title: ''
  type: SDK
  url: https://github.com/resend/resend-dotnet
- title: ''
  type: CLI
  url: https://github.com/resend/resend-cli
- title: ''
  type: MCPServer
  url: https://github.com/resend/resend-mcp
- title: ''
  type: Library
  url: https://github.com/resend/react-email
- title: ''
  type: Status
  url: https://resend-status.com/
- title: ''
  type: RateLimits
  url: https://resend.com/docs/api-reference/introduction
created: '2024-11-07'
description: Resend is a developer-first email API platform that simplifies sending and managing transactional and marketing emails. It provides a clean REST API with bearer token authentication, supporting email sending, domain management, API key management, audience and contact management, and broadcast campaigns. Resend offers SDKs for Node.js, Python, Go, Ruby, PHP, Java, .NET, Rust, Elixir, and more, along with a React Email library and official MCP server.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Resend Context
  property_count: 0
  slug: resend-context
layout: provider
modified: '2026-05-02'
name: Resend
rules:
- name: Resend API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 6
  slug: resend-rules
skills: []
slug: resend
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: resend\nname: Resend\ndescription: >-\n  Resend is a developer-first email API platform that simplifies sending and\n  managing transactional and marketing emails. It provides a clean REST API with\n  bearer token authentication, supporting email sending, domain management,\n  API key management, audience and contact management, and broadcast campaigns.\n  Resend offers SDKs for Node.js, Python, Go, Ruby, PHP, Java, .NET, Rust,\n  Elixir, and more, along with a React Email library and official MCP server.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Email\n  - Developer Tools\n  - Transactional Email\n  - Marketing Email\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/apis.yml\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: resend:resend\n    name: Resend API\n    description: >-\n      The Resend REST API provides endpoints for\
  \ sending emails, managing\n      domains, managing API keys, managing audiences and contacts, and sending\n      broadcast campaigns. Authentication uses Bearer tokens. Rate limit is\n      5 requests per second per team by default. Base URL is https://api.resend.com.\n    humanURL: https://resend.com/\n    baseURL: https://api.resend.com\n    tags:\n      - Email\n      - Domains\n      - API Keys\n      - Audiences\n      - Contacts\n      - Broadcasts\n      - Transactional Email\n    properties:\n      - url: https://resend.com/\n        type: Documentation\n      - url: openapi/resend-openapi.yml\n        type: OpenAPI\n      - type: Webhooks\n        url: https://resend.com/docs/dashboard/webhooks/introduction\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-schema/resend-email-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-schema/resend-audience-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-schema/resend-domain-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-structure/resend-email-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/json-ld/resend-context.jsonld\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/rules/resend-rules.yml\n      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/capabilities/email-delivery.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/vocabulary/resend-vocabulary.yml\n    contact:\n      - FN:\
  \ Resend Support\n        url: https://resend.com/docs/support\ncommon:\n  - url: https://github.com/resend\n    name: GitHub Organization\n    type: GitHubOrganization\n  - name: Changelog\n    url: https://resend.com/changelog\n    type: ChangeLog\n  - name: Blog\n    url: https://resend.com/blog\n    type: Blog\n  - name: Migration Guides\n    url: https://resend.com/migrate\n    type: Migrations\n  - name: Customers\n    url: https://resend.com/customers\n    type: Customers\n  - name: About\n    url: https://resend.com/about\n    type: About\n  - name: Security\n    url: https://resend.com/security\n    type: Security\n  - name: Integrations\n    url: https://resend.com/docs/integrations\n    type: Integrations\n  - name: Examples\n    url: https://resend.com/docs/examples\n    type: Examples\n  - name: SDKs\n    url: https://resend.com/docs/sdks\n    type: SDKs\n  - name: Pricing\n    url: https://resend.com/pricing\n    type: Pricing\n  - name: Login\n    url: https://resend.com/login\n\
  \    type: Login\n  - name: Sign Up\n    url: https://resend.com/signup\n    type: SignUp\n  - name: Node.js SDK\n    url: https://github.com/resend/resend-node\n    type: SDK\n  - name: Python SDK\n    url: https://github.com/resend/resend-python\n    type: SDK\n  - name: Go SDK\n    url: https://github.com/resend/resend-go\n    type: SDK\n  - name: .NET SDK\n    url: https://github.com/resend/resend-dotnet\n    type: SDK\n  - name: CLI\n    url: https://github.com/resend/resend-cli\n    type: CLI\n  - name: MCP Server\n    url: https://github.com/resend/resend-mcp\n    type: MCPServer\n  - name: React Email\n    url: https://github.com/resend/react-email\n    type: Library\n  - name: Status\n    url: https://resend-status.com/\n    type: Status\n  - name: Rate Limits\n    url: https://resend.com/docs/api-reference/introduction\n    type: RateLimits\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/apis.yml
tags:
- Email
- Developer Tools
- Transactional Email
- Marketing Email
url: https://raw.githubusercontent.com/api-evangelist/resend/refs/heads/main/apis.yml
use_cases: []
---
