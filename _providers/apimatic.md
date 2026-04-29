---
api_count: 2
apis:
- description: The APIMatic Platform API provides programmatic access to APIMatic's capabilities including SDK generation, API documentation portal generation, API specification validation and linting, and API speci
  name: APIMatic Platform API
  slug: apimatic-platform-api
- description: APIMatic API Transformer converts API definition files between more than 15 supported API specification formats including OpenAPI, RAML, API Blueprint, WSDL, WADL, and Postman Collections.
  name: APIMatic API Transformer API
  slug: apimatic-api-transformer-api
common:
- title: ''
  type: Website
  url: https://www.apimatic.io/
- title: ''
  type: Documentation
  url: https://docs.apimatic.io/
- title: ''
  type: GettingStarted
  url: https://docs.apimatic.io/getting-started/importing-api-spec/
- title: ''
  type: Pricing
  url: https://www.apimatic.io/pricing
- title: ''
  type: Blog
  url: https://www.apimatic.io/blog
- title: ''
  type: SignUp
  url: https://app.apimatic.io/account/register
- title: ''
  type: Login
  url: https://app.apimatic.io/account/login
- title: ''
  type: ChangeLog
  url: https://docs.apimatic.io/changelog/
- title: ''
  type: Support
  url: https://support.apimatic.io/hc/en-us
- title: ''
  type: GitHubOrganization
  url: https://github.com/apimatic
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/apimatic-limited/
- title: ''
  type: X
  url: https://x.com/APIMatic
- title: ''
  type: CLI
  url: https://www.npmjs.com/package/@apimatic/cli
- title: ''
  type: TermsOfService
  url: https://www.apimatic.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.apimatic.io/privacy
created: '2025-01-08'
description: APIMatic is a developer experience platform for APIs that specializes in automated SDK generation, API documentation portal creation, specification validation and linting, and API format transformation. It supports 15+ API specification formats and generates idiomatic SDKs in 7+ programming languages with CI/CD integration for automating the developer experience suite.
features:
- description: Generate production-ready SDKs in Python, Java, C# .NET, TypeScript, PHP, Ruby, and Go from any API specification.
  name: Idiomatic SDK Generation
- description: Generate interactive developer documentation portals with code samples, guided walkthroughs, and code playground.
  name: API Documentation Portals
- description: Validate and lint API specifications with detailed error reports and best practice recommendations.
  name: API Specification Validation
- description: Convert API definitions between 15+ formats including OpenAPI 3.0, Swagger 2.0, RAML, API Blueprint, and Postman Collections.
  name: API Format Transformation
- description: Generate Model Context Protocol (MCP) servers from API specifications for AI agent integration.
  name: MCP Server Generation
- description: Define and automate your entire developer experience pipeline as code with CI/CD integration.
  name: DX as Code
- description: Automatically validate OpenAPI specifications in GitHub pull requests via the APIMatic linter GitHub App.
  name: OpenAPI Linter GitHub App
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: APIMatic integration for generating SDKs from MuleSoft API definitions.
  name: MuleSoft
- description: Integration for enhanced API documentation workflows.
  name: Redocly
- description: CI/CD integration for automated SDK generation and API validation in GitHub workflows.
  name: GitHub Actions
jsonld:
- class_count: 9
  name: Apimatic Context
  property_count: 4
  slug: apimatic-context
layout: provider
modified: '2026-04-19'
name: APIMatic
skills: []
slug: apimatic
solutions:
- description: Basic SDK generation and API validation for individual developers.
  name: Free Plan
- description: Advanced SDK generation, portal publishing, and team collaboration features.
  name: Team Plan
- description: Full developer experience automation, custom branding, SLA, and dedicated support.
  name: Enterprise Plan
source_yaml: "aid: apimatic\nname: APIMatic\ndescription: >-\n  APIMatic is a developer experience platform for APIs that specializes in\n  automated SDK generation, API documentation portal creation, specification\n  validation and linting, and API format transformation. It supports 15+\n  API specification formats and generates idiomatic SDKs in 7+ programming\n  languages with CI/CD integration for automating the developer experience suite.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Transformation\n  - Code Generation\n  - Developer Experience\n  - Documentation\n  - SDK Generation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apimatic:apimatic-platform-api\n    name: APIMatic Platform API\n    description: >-\n      The APIMatic Platform API provides programmatic access to APIMatic's\n\
  \      capabilities including SDK generation, API documentation portal\n      generation, API specification validation and linting, and API\n      specification transformation. Integrate APIMatic into your CI/CD\n      workflows to automate your developer experience suite.\n    humanURL: https://docs.apimatic.io/platform-api/\n    baseURL: https://api.apimatic.io\n    tags:\n      - Code Generation\n      - Documentation\n      - SDK Generation\n      - Transformation\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://docs.apimatic.io/platform-api/\n      - type: GettingStarted\n        url: https://docs.apimatic.io/platform-api/#/http/getting-started\n      - type: OpenAPI\n        url: openapi/apimatic-platform-api.yaml\n      - type: JSONSchema\n        url: json-schema/apimatic-api-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/apimatic-sdk-generation-schema.json\n      - type: JSON-LD\n        url: json-ld/apimatic-context.jsonld\n\
  \  - aid: apimatic:apimatic-api-transformer-api\n    name: APIMatic API Transformer API\n    description: >-\n      APIMatic API Transformer converts API definition files between more\n      than 15 supported API specification formats including OpenAPI, RAML,\n      API Blueprint, WSDL, WADL, and Postman Collections.\n    humanURL: https://www.apimatic.io/solution/transformer\n    baseURL: https://api.apimatic.io\n    tags:\n      - API Conversion\n      - Format Transformation\n      - OpenAPI\n      - Postman\n      - RAML\n    properties:\n      - type: Documentation\n        url: https://docs.apimatic.io/api-transformer/overview-transformer/\ncommon:\n  - type: Website\n    url: https://www.apimatic.io/\n  - type: Documentation\n    url: https://docs.apimatic.io/\n  - type: GettingStarted\n    url: https://docs.apimatic.io/getting-started/importing-api-spec/\n  - type: Pricing\n    url: https://www.apimatic.io/pricing\n  - type: Blog\n    url: https://www.apimatic.io/blog\n  - type:\
  \ SignUp\n    url: https://app.apimatic.io/account/register\n  - type: Login\n    url: https://app.apimatic.io/account/login\n  - type: ChangeLog\n    url: https://docs.apimatic.io/changelog/\n  - type: Support\n    url: https://support.apimatic.io/hc/en-us\n  - type: GitHubOrganization\n    url: https://github.com/apimatic\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/apimatic-limited/\n  - type: X\n    url: https://x.com/APIMatic\n  - type: CLI\n    url: https://www.npmjs.com/package/@apimatic/cli\n  - type: TermsOfService\n    url: https://www.apimatic.io/terms\n  - type: PrivacyPolicy\n    url: https://www.apimatic.io/privacy\n  - type: Features\n    data:\n      - name: Idiomatic SDK Generation\n        description: Generate production-ready SDKs in Python, Java, C# .NET, TypeScript, PHP, Ruby, and Go from any API specification.\n      - name: API Documentation Portals\n        description: Generate interactive developer documentation portals with code samples, guided\
  \ walkthroughs, and code playground.\n      - name: API Specification Validation\n        description: Validate and lint API specifications with detailed error reports and best practice recommendations.\n      - name: API Format Transformation\n        description: Convert API definitions between 15+ formats including OpenAPI 3.0, Swagger 2.0, RAML, API Blueprint, and Postman Collections.\n      - name: MCP Server Generation\n        description: Generate Model Context Protocol (MCP) servers from API specifications for AI agent integration.\n      - name: DX as Code\n        description: Define and automate your entire developer experience pipeline as code with CI/CD integration.\n      - name: OpenAPI Linter GitHub App\n        description: Automatically validate OpenAPI specifications in GitHub pull requests via the APIMatic linter GitHub App.\n  - type: UseCases\n    data:\n      - name: Automated SDK Publishing\n        description: Automatically generate and publish SDKs to npm, PyPI,\
  \ Maven, and other package registries on every API change.\n      - name: Developer Portal Generation\n        description: Generate and host comprehensive API documentation portals with interactive examples and code playground.\n      - name: API Specification Migration\n        description: Transform legacy Swagger 2.0 or RAML specs to OpenAPI 3.0 for modern tooling compatibility.\n      - name: CI/CD API Governance\n        description: Integrate API validation and linting into CI/CD pipelines to enforce quality gates on API changes.\n  - type: Integrations\n    data:\n      - name: MuleSoft\n        description: APIMatic integration for generating SDKs from MuleSoft API definitions.\n      - name: Redocly\n        description: Integration for enhanced API documentation workflows.\n      - name: GitHub Actions\n        description: CI/CD integration for automated SDK generation and API validation in GitHub workflows.\n  - type: Solutions\n    data:\n      - name: Free Plan\n       \
  \ description: Basic SDK generation and API validation for individual developers.\n      - name: Team Plan\n        description: Advanced SDK generation, portal publishing, and team collaboration features.\n      - name: Enterprise Plan\n        description: Full developer experience automation, custom branding, SLA, and dedicated support.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/apis.yml
tags:
- API Transformation
- Code Generation
- Developer Experience
- Documentation
- SDK Generation
url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/apis.yml
use_cases:
- description: Automatically generate and publish SDKs to npm, PyPI, Maven, and other package registries on every API change.
  name: Automated SDK Publishing
- description: Generate and host comprehensive API documentation portals with interactive examples and code playground.
  name: Developer Portal Generation
- description: Transform legacy Swagger 2.0 or RAML specs to OpenAPI 3.0 for modern tooling compatibility.
  name: API Specification Migration
- description: Integrate API validation and linting into CI/CD pipelines to enforce quality gates on API changes.
  name: CI/CD API Governance
---
