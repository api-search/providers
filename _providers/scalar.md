---
api_count: 6
apis:
- description: Scalar API References renders modern, interactive API documentation from OpenAPI and Swagger specifications. Features include multiple themes, custom styling, dark mode, mobile responsiveness, built-i
  name: Scalar API References
  slug: scalar-api-references
- description: Scalar API Client is a fully open-source, offline-first REST API client built on the OpenAPI standard. Supports collections, environments, pre/post-response scripting, test results, and collection run
  name: Scalar API Client
  slug: scalar-api-client
- description: Scalar Docs enables teams to create and publish developer documentation that stays in sync with their API and code. Supports writing with a WYSIWYG editor, pulling Markdown and MDX files from reposito
  name: Scalar Docs
  slug: scalar-docs
- description: Scalar Registry provides centralized management and versioning of OpenAPI Documents, JSON Schemas, and Spectral Rules with deep Git integration. Serves as the single source of truth for API definition
  name: Scalar Registry
  slug: scalar-registry
- description: 'Scalar SDKs generates type-safe client libraries from OpenAPI specifications. Supported languages include TypeScript, Python, Golang, PHP, Java, and Ruby. Features include automated GitHub workflows, '
  name: Scalar SDKs
  slug: scalar-sdks
- description: The Scalar CLI is a command-line interface for managing OpenAPI files, generating documentation, running mock servers, validating specs, and publishing to the Scalar Registry. Enables CI/CD integratio
  name: Scalar CLI
  slug: scalar-cli
common:
- title: ''
  type: Website
  url: https://scalar.com/
- title: ''
  type: Documentation
  url: https://guides.scalar.com/scalar/introduction
- title: ''
  type: Pricing
  url: https://guides.scalar.com/scalar/pricing
- title: ''
  type: GitHub
  url: https://github.com/scalar/scalar
- title: ''
  type: Discord
  url: https://discord.gg/scalar
- title: ''
  type: Blog
  url: https://scalar.com/blog
- title: ''
  type: ChangeLog
  url: https://github.com/scalar/scalar/releases
- title: ''
  type: Support
  url: mailto:support@scalar.com
- title: ''
  type: Dashboard
  url: https://dashboard.scalar.com/
- title: ''
  type: SpectralRules
  url: https://github.com/api-evangelist/scalar/blob/main/rules/scalar-rules.yml
- title: ''
  type: JSONSchema
  url: https://github.com/api-evangelist/scalar/blob/main/json-schema/scalar-openapi-document-schema.json
- title: ''
  type: JSONStructure
  url: https://github.com/api-evangelist/scalar/blob/main/json-structure/scalar-openapi-document-structure.json
- title: ''
  type: JSONLDContext
  url: https://github.com/api-evangelist/scalar/blob/main/json-ld/scalar-context.jsonld
- title: ''
  type: Vocabulary
  url: https://github.com/api-evangelist/scalar/blob/main/vocabulary/scalar-vocabulary.yml
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalar/blob/main/examples/
created: '2025-01-08'
description: Scalar is an open-source API platform built around the OpenAPI standard. It provides API documentation (API References), an offline-first API client, a centralized API registry for managing OpenAPI documents, JSON schemas and Spectral rules, and automated SDK generation for TypeScript, Python, Go, PHP, Java, and Ruby. Used by teams at SmartBear, Microsoft ASP.NET, and 30+ framework ecosystems including Express, FastAPI, NestJS, and Spring Boot. The platform has 14.9k GitHub stars and is MIT licensed. Scalar is backed by a strong open-source community and positions itself as the modern, open alternative to Swagger UI and Postman.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Scalar Context
  property_count: 1
  slug: scalar-context
layout: provider
modified: '2026-05-02'
name: Scalar
rules:
- name: Scalar API Rules
  rule_count: 16
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 12
  slug: scalar-rules
skills: []
slug: scalar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalar\nname: Scalar\ndescription: >-\n  Scalar is an open-source API platform built around the OpenAPI standard.\n  It provides API documentation (API References), an offline-first API client,\n  a centralized API registry for managing OpenAPI documents, JSON schemas and\n  Spectral rules, and automated SDK generation for TypeScript, Python, Go,\n  PHP, Java, and Ruby. Used by teams at SmartBear, Microsoft ASP.NET, and\n  30+ framework ecosystems including Express, FastAPI, NestJS, and Spring Boot.\n  The platform has 14.9k GitHub stars and is MIT licensed. Scalar is backed\n  by a strong open-source community and positions itself as the modern,\n  open alternative to Swagger UI and Postman.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/scalar/refs/heads/main/apis.yml\ntags:\n  - API Client\n  - API Documentation\n  - API References\n  - Code Generation\n  - Developer Tools\n  -\
  \ OpenAPI\n  - Registry\n  - SDKs\n  - Swagger\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-01-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalar:scalar-api-references\n    name: Scalar API References\n    description: >-\n      Scalar API References renders modern, interactive API documentation from\n      OpenAPI and Swagger specifications. Features include multiple themes,\n      custom styling, dark mode, mobile responsiveness, built-in search, and\n      an interactive request panel for testing APIs directly in the docs.\n      Supports OpenAPI 3.0 and 3.1, $ref resolution, allOf/oneOf/anyOf, and\n      authentication schemes. Framework integrations include React, Vue,\n      FastAPI, ASP.NET Core, Spring Boot, NestJS, Express, and 30+ others.\n    tags:\n      - Documentation\n      - Interactive\n      - OpenAPI\n      - References\n      - Swagger\n    humanURL: https://scalar.com/products/api-references/getting-started\n  \
  \  properties:\n      - type: GettingStarted\n        url: https://scalar.com/products/api-references/getting-started\n      - type: Documentation\n        url: https://guides.scalar.com/scalar/scalar-api-references/getting-started\n      - type: GitHub\n        url: https://github.com/scalar/scalar\n      - type: NPM\n        url: https://www.npmjs.com/package/@scalar/api-reference\n  - aid: scalar:scalar-api-client\n    name: Scalar API Client\n    description: >-\n      Scalar API Client is a fully open-source, offline-first REST API client\n      built on the OpenAPI standard. Supports collections, environments,\n      pre/post-response scripting, test results, and collection runners.\n      Available for Windows, macOS, and Linux as a desktop application and\n      as a browser-based version at client.scalar.com. Imports OpenAPI files\n      to auto-generate request collections with authentication pre-configured.\n    tags:\n      - API Client\n      - Collections\n      - OpenAPI\n\
  \      - REST\n      - Testing\n    humanURL: https://scalar.com/products/api-client/getting-started\n    properties:\n      - type: GettingStarted\n        url: https://scalar.com/products/api-client/getting-started\n      - type: Application\n        url: https://client.scalar.com/\n      - type: Download\n        url: https://scalar.com/download\n      - type: GitHub\n        url: https://github.com/scalar/scalar\n  - aid: scalar:scalar-docs\n    name: Scalar Docs\n    description: >-\n      Scalar Docs enables teams to create and publish developer documentation\n      that stays in sync with their API and code. Supports writing with a\n      WYSIWYG editor, pulling Markdown and MDX files from repositories, and\n      generating API references from OpenAPI documents with Git Sync and\n      CI/CD integration. Custom domains, team collaboration, and versioning\n      are available on paid plans.\n    tags:\n      - Developer Portal\n      - Documentation\n      - Git Sync\n      - Markdown\n\
  \      - MDX\n    humanURL: https://scalar.com/products/docs/getting-started\n    properties:\n      - type: GettingStarted\n        url: https://scalar.com/products/docs/getting-started\n      - type: Portal\n        url: https://docs.scalar.com/\n      - type: Documentation\n        url: https://guides.scalar.com/scalar/scalar-docs/getting-started\n      - type: GitHubActions\n        url: https://scalar.com/products/docs/github-actions\n  - aid: scalar:scalar-registry\n    name: Scalar Registry\n    description: >-\n      Scalar Registry provides centralized management and versioning of OpenAPI\n      Documents, JSON Schemas, and Spectral Rules with deep Git integration.\n      Serves as the single source of truth for API definitions across teams.\n      Supports both private and public registries with CI/CD workflows via\n      CLI and GitHub Actions. Publish via the scalar CLI:\n      `scalar registry publish`.\n    tags:\n      - Git Integration\n      - Governance\n      - JSON\
  \ Schema\n      - OpenAPI\n      - Registry\n      - Spectral\n      - Versioning\n    humanURL: https://scalar.com/products/registry/getting-started\n    properties:\n      - type: GettingStarted\n        url: https://scalar.com/products/registry/getting-started\n      - type: Documentation\n        url: https://guides.scalar.com/scalar/scalar-registry/getting-started\n      - type: CLI\n        url: https://guides.scalar.com/scalar/scalar-cli/getting-started\n      - type: GitHubActions\n        url: https://scalar.com/scalar/scalar-registry/github-actions\n  - aid: scalar:scalar-sdks\n    name: Scalar SDKs\n    description: >-\n      Scalar SDKs generates type-safe client libraries from OpenAPI\n      specifications. Supported languages include TypeScript, Python, Golang,\n      PHP, Java, and Ruby. Features include automated GitHub workflows, code\n      samples, full OpenAPI auth support, file streaming, and webhook support.\n      SDK generation is $100 per month per language on\
  \ paid plans.\n    tags:\n      - Code Generation\n      - Go\n      - Java\n      - PHP\n      - Python\n      - Ruby\n      - SDKs\n      - TypeScript\n    humanURL: https://scalar.com/products/sdks/getting-started\n    properties:\n      - type: GettingStarted\n        url: https://scalar.com/products/sdks/getting-started\n      - type: Documentation\n        url: https://guides.scalar.com/scalar/scalar-sdks/getting-started\n      - type: Pricing\n        url: https://guides.scalar.com/scalar/pricing\n  - aid: scalar:scalar-cli\n    name: Scalar CLI\n    description: >-\n      The Scalar CLI is a command-line interface for managing OpenAPI files,\n      generating documentation, running mock servers, validating specs, and\n      publishing to the Scalar Registry. Enables CI/CD integration and\n      automation of the API documentation workflow.\n    tags:\n      - CLI\n      - Developer Tools\n      - Mock Server\n      - OpenAPI\n      - Validation\n    humanURL: https://guides.scalar.com/scalar/scalar-cli/getting-started\n\
  \    properties:\n      - type: GettingStarted\n        url: https://guides.scalar.com/scalar/scalar-cli/getting-started\n      - type: Documentation\n        url: https://guides.scalar.com/scalar/scalar-cli/getting-started\n      - type: NPM\n        url: https://www.npmjs.com/package/@scalar/cli\ncommon:\n  - type: Website\n    url: https://scalar.com/\n    name: Scalar Website\n  - type: Documentation\n    url: https://guides.scalar.com/scalar/introduction\n    name: Scalar Documentation\n  - type: Pricing\n    url: https://guides.scalar.com/scalar/pricing\n    name: Scalar Pricing\n  - type: GitHub\n    url: https://github.com/scalar/scalar\n    name: Scalar GitHub Repository\n  - type: Discord\n    url: https://discord.gg/scalar\n    name: Scalar Discord Community\n  - type: Blog\n    url: https://scalar.com/blog\n    name: Scalar Blog\n  - type: ChangeLog\n    url: https://github.com/scalar/scalar/releases\n    name: Scalar Changelog\n  - type: Support\n    url: mailto:support@scalar.com\n\
  \    name: Scalar Support\n  - type: Dashboard\n    url: https://dashboard.scalar.com/\n    name: Scalar Dashboard\n  - type: SpectralRules\n    url: https://github.com/api-evangelist/scalar/blob/main/rules/scalar-rules.yml\n    name: Scalar Spectral Rules\n  - type: JSONSchema\n    url: https://github.com/api-evangelist/scalar/blob/main/json-schema/scalar-openapi-document-schema.json\n    name: Scalar OpenAPI Document JSON Schema\n  - type: JSONStructure\n    url: https://github.com/api-evangelist/scalar/blob/main/json-structure/scalar-openapi-document-structure.json\n    name: Scalar OpenAPI Document JSON Structure\n  - type: JSONLDContext\n    url: https://github.com/api-evangelist/scalar/blob/main/json-ld/scalar-context.jsonld\n    name: Scalar JSON-LD Context\n  - type: Vocabulary\n    url: https://github.com/api-evangelist/scalar/blob/main/vocabulary/scalar-vocabulary.yml\n    name: Scalar Vocabulary\n  - type: Examples\n    url: https://github.com/api-evangelist/scalar/blob/main/examples/\n\
  \    name: Scalar Usage Examples\nsegments:\n  - SDKs\n  - Clients\n  - Documentation\n  - Registries\n  - Developer Tools\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalar/refs/heads/main/apis.yml
tags:
- API Client
- API Documentation
- API References
- Code Generation
- Developer Tools
- OpenAPI
- Registry
- SDKs
- Swagger
url: https://raw.githubusercontent.com/api-evangelist/scalar/refs/heads/main/apis.yml
use_cases: []
---
