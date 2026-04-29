---
api_count: 1
apis:
- description: Apidog's public REST API allows developers to programmatically interact with Apidog projects for importing and exporting API specifications, managing endpoints, schemas, environments, and more. All AP
  name: Apidog
  slug: apidog
capabilities:
- description: Unified workflow for managing API specifications lifecycle with Apidog - importing from various sources, exporting to standard formats, and maintaining API definitions programmatically.
  name: Apidog API Lifecycle Management
  slug: api-lifecycle-management
common:
- title: ''
  type: Website
  url: https://apidog.com/
- title: ''
  type: Documentation
  url: https://docs.apidog.com/
- title: ''
  type: GettingStarted
  url: https://docs.apidog.com/overview-644404m0
- title: ''
  type: Pricing
  url: https://apidog.com/pricing/
- title: ''
  type: Blog
  url: https://apidog.com/blog/
- title: ''
  type: ReleaseNotes
  url: https://apidog.com/blog/product-updates/
- title: ''
  type: Articles
  url: https://apidog.com/articles/
- title: ''
  type: TermsOfService
  url: https://legal.apidog.com/
- title: ''
  type: Security
  url: https://trust.apidog.com/
- title: ''
  type: Support
  url: https://docs.apidog.com/apidog-support-center-748035m0
- title: ''
  type: GitHubOrganization
  url: https://github.com/Apidog
created: '2025-01-08'
description: Apidog is a complete set of tools that connects the entire API lifecycle, helping R&D teams implement best practices for API Design-first development. It provides API design, debugging, testing, mocking, and documentation capabilities in a single collaborative platform with multi-protocol support including HTTP, GraphQL, gRPC, WebSocket, and SOAP.
features:
- description: Visual OpenAPI/Swagger editor with JSON Schema support, reusable schemas, Git integration, and sprint branches for collaborative development.
  name: API Design
- description: Multi-protocol support for HTTP, REST, GraphQL, SOAP, WebSocket with auto-validation of responses against API specs and database connectivity.
  name: API Debugging
- description: Visual test scenarios with CI/CD integration, data-driven testing with CSV/JSON datasets, performance testing, and AI-generated test cases.
  name: API Testing
- description: Zero-configuration smart mock generation from specs, cloud-based and local mock servers, and custom mock rules.
  name: API Mocking
- description: Auto-generated interactive docs with custom domains, auto-generated SSL certificates, Markdown support, and versioning control.
  name: API Documentation
- description: Real-time synchronization, sprint branches for parallel development, role-based access control, and SSO support.
  name: Team Collaboration
- description: SOC 2 Type II certified, GDPR and ISO 27001 compliant, TLS 1.3+ encryption in transit, AES-256 encryption at rest.
  name: Enterprise Security
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import and export OpenAPI/Swagger specifications for interoperability with other API tools.
  name: OpenAPI/Swagger
- description: 100% compatible Postman collection import and scripting syntax support.
  name: Postman
- description: Integration with Jenkins, GitLab CI, GitHub Actions, and Bitbucket Pipelines for automated testing.
  name: CI/CD Platforms
- description: Connect to MySQL, PostgreSQL, Oracle, SQLServer, and ClickHouse for dynamic test data.
  name: Databases
- description: Integration with HashiCorp Vault, Azure Key Vault, and AWS Secrets Manager for secure credential management.
  name: Credential Vaults
- description: Support for SAML 2.0, Microsoft Active Directory, OIDC, and SCIM for enterprise identity management.
  name: Enterprise SSO
- description: IDEA plugin for JavaDoc annotation parsing and API definition generation.
  name: IntelliJ IDEA Plugin
jsonld:
- class_count: 2
  name: Apidog Context
  property_count: 9
  slug: apidog-context
layout: provider
modified: '2026-04-19'
name: Apidog
rules:
- name: Apidog API Rules
  rule_count: 20
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 12
  slug: apidog-spectral-rules
skills: []
slug: apidog
solutions: []
source_yaml: "aid: apidog\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/apis.yml\nname: Apidog\ndescription: >-\n  Apidog is a complete set of tools that connects the entire API lifecycle,\n  helping R&D teams implement best practices for API Design-first development.\n  It provides API design, debugging, testing, mocking, and documentation\n  capabilities in a single collaborative platform with multi-protocol support\n  including HTTP, GraphQL, gRPC, WebSocket, and SOAP.\ntags:\n  - API Design\n  - API Lifecycle\n  - API Testing\n  - Collaboration\n  - Design-First\n  - Documentation\n  - Mocking\n  - Platform\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: apidog:apidog\n    name: Apidog\n    description: >-\n      Apidog's public REST API allows developers to programmatically\
  \ interact\n      with Apidog projects for importing and exporting API specifications,\n      managing endpoints, schemas, environments, and more. All API URLs begin\n      with the base URL https://api.apidog.com. Authentication is via Bearer\n      Token passed in the Authorization header.\n    humanURL: https://apidog.com/\n    baseURL: https://api.apidog.com\n    tags:\n      - API Design\n      - API Lifecycle\n      - Documentation\n      - Import\n      - Export\n    properties:\n      - url: https://openapi.apidog.io/\n        type: Documentation\n      - url: https://docs.apidog.com/overview-644404m0\n        type: GettingStarted\n      - url: openapi/apidog-apidog-openapi.yml\n        type: OpenAPI\n      - url: https://legal.apidog.com/\n        type: TermsOfService\n      - url: https://apidog.com/pricing/\n        type: Pricing\n      - url: json-schema/apidog-project-schema.json\n        type: JSONSchema\n      - url: json-schema/apidog-import-result-schema.json\n       \
  \ type: JSONSchema\n      - url: json-schema/apidog-export-result-schema.json\n        type: JSONSchema\n      - url: json-schema/apidog-error-schema.json\n        type: JSONSchema\n      - url: json-ld/apidog-context.jsonld\n        type: JSON-LD\ncommon:\n  - url: https://apidog.com/\n    type: Website\n  - url: https://docs.apidog.com/\n    type: Documentation\n  - url: https://docs.apidog.com/overview-644404m0\n    type: GettingStarted\n  - url: https://apidog.com/pricing/\n    type: Pricing\n  - url: https://apidog.com/blog/\n    type: Blog\n  - url: https://apidog.com/blog/product-updates/\n    type: ReleaseNotes\n  - url: https://apidog.com/articles/\n    type: Articles\n  - url: https://legal.apidog.com/\n    type: TermsOfService\n  - url: https://trust.apidog.com/\n    type: Security\n  - url: https://docs.apidog.com/apidog-support-center-748035m0\n    type: Support\n  - url: https://github.com/Apidog\n    type: GitHubOrganization\n  - type: Features\n    data:\n      - name:\
  \ API Design\n        description: Visual OpenAPI/Swagger editor with JSON Schema support, reusable schemas, Git integration, and sprint branches for collaborative development.\n      - name: API Debugging\n        description: Multi-protocol support for HTTP, REST, GraphQL, SOAP, WebSocket with auto-validation of responses against API specs and database connectivity.\n      - name: API Testing\n        description: Visual test scenarios with CI/CD integration, data-driven testing with CSV/JSON datasets, performance testing, and AI-generated test cases.\n      - name: API Mocking\n        description: Zero-configuration smart mock generation from specs, cloud-based and local mock servers, and custom mock rules.\n      - name: API Documentation\n        description: Auto-generated interactive docs with custom domains, auto-generated SSL certificates, Markdown support, and versioning control.\n      - name: Team Collaboration\n        description: Real-time synchronization, sprint branches\
  \ for parallel development, role-based access control, and SSO support.\n      - name: Enterprise Security\n        description: SOC 2 Type II certified, GDPR and ISO 27001 compliant, TLS 1.3+ encryption in transit, AES-256 encryption at rest.\n  - type: UseCases\n    data:\n      - name: API Design-First Development\n        description: Design APIs visually before writing code, enabling frontend and backend teams to work in parallel.\n      - name: Automated API Testing\n        description: Build comprehensive regression test suites with CI/CD integration for automated API quality assurance.\n      - name: API Documentation Publishing\n        description: Automatically generate and publish interactive developer documentation from API specifications.\n      - name: Mock Server Development\n        description: Enable frontend development independent of backend completion using intelligent mock data generation.\n  - type: Integrations\n    data:\n      - name: OpenAPI/Swagger\n     \
  \   description: Import and export OpenAPI/Swagger specifications for interoperability with other API tools.\n      - name: Postman\n        description: 100% compatible Postman collection import and scripting syntax support.\n      - name: CI/CD Platforms\n        description: Integration with Jenkins, GitLab CI, GitHub Actions, and Bitbucket Pipelines for automated testing.\n      - name: Databases\n        description: Connect to MySQL, PostgreSQL, Oracle, SQLServer, and ClickHouse for dynamic test data.\n      - name: Credential Vaults\n        description: Integration with HashiCorp Vault, Azure Key Vault, and AWS Secrets Manager for secure credential management.\n      - name: Enterprise SSO\n        description: Support for SAML 2.0, Microsoft Active Directory, OIDC, and SCIM for enterprise identity management.\n      - name: IntelliJ IDEA Plugin\n        description: IDEA plugin for JavaDoc annotation parsing and API definition generation.\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/apis.yml
tags:
- API Design
- API Lifecycle
- API Testing
- Collaboration
- Design-First
- Documentation
- Mocking
- Platform
url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/apis.yml
use_cases:
- description: Design APIs visually before writing code, enabling frontend and backend teams to work in parallel.
  name: API Design-First Development
- description: Build comprehensive regression test suites with CI/CD integration for automated API quality assurance.
  name: Automated API Testing
- description: Automatically generate and publish interactive developer documentation from API specifications.
  name: API Documentation Publishing
- description: Enable frontend development independent of backend completion using intelligent mock data generation.
  name: Mock Server Development
---
