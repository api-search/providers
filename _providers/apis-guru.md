---
api_count: 1
apis:
- description: 'The APIs.guru REST API provides programmatic access to the directory of public API definitions, allowing developers to search, browse, and retrieve OpenAPI specifications from the catalog. The API is '
  name: APIs.guru REST API
  slug: apis-guru-api
capabilities:
- description: Workflow capability for discovering, browsing, and retrieving API definitions from the APIs.guru directory. Enables developers and platform teams to programmatically find public APIs, retrieve their O
  name: APIs.guru API Discovery
  slug: api-discovery
common:
- title: ''
  type: Website
  url: https://apis.guru
- title: ''
  type: About
  url: https://apis.guru/about
- title: ''
  type: Documentation
  url: https://apis.guru/api-doc
- title: ''
  type: Blog
  url: https://apis.guru/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/APIs-guru
- title: ''
  type: GitHubRepository
  url: https://github.com/APIs-guru/openapi-directory
- title: AsyncAPI Directory
  type: GitHubRepository
  url: https://github.com/APIs-guru/asyncapi-directory
- title: GraphQL Voyager
  type: GitHubRepository
  url: https://github.com/APIs-guru/graphql-voyager
- title: Awesome OpenAPI 3
  type: GitHubRepository
  url: https://github.com/APIs-guru/awesome-openapi3
- title: AWS to OpenAPI Converter
  type: GitHubRepository
  url: https://github.com/APIs-guru/aws2openapi
- title: Google Discovery to OpenAPI Converter
  type: GitHubRepository
  url: https://github.com/APIs-guru/google-discovery-to-swagger
- title: GraphQL Faker
  type: GitHubRepository
  url: https://github.com/APIs-guru/graphql-faker
- title: Public GraphQL APIs Directory
  type: GitHubRepository
  url: https://github.com/APIs-guru/graphql-apis
- title: ''
  type: X
  url: https://x.com/APIs_guru
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/rules/apis-guru-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/vocabulary/apis-guru-vocabulary.yaml
- title: API Discovery Capability
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/capabilities/api-discovery.yaml
- title: ''
  type: Support
  url: https://github.com/APIs-guru/openapi-directory/issues
created: '2026-03-25'
description: APIs.guru is an open source, community-driven directory of public REST API definitions in OpenAPI 2.0/3.x format, described as the Wikipedia for Web APIs. The project searches for public API definitions, converts various formats to OpenAPI 3.0, corrects errors in approximately 80% of definitions, and enriches entries with logos, categories, and metadata. It catalogs over 2,500 API descriptions with 100,000+ endpoints, updating definitions weekly from original sources. The platform is licensed under CC0-1.0 for contributed definitions and welcomes community contributions through GitHub.
features:
- description: Comprehensive directory of over 2,500 public API definitions in OpenAPI 2.0 and 3.x format, updated weekly from original sources.
  name: OpenAPI Directory
- description: Converts various API description formats (RAML, Google Discovery, AWS, etc.) to OpenAPI 3.0 standard for consistency and compatibility.
  name: Format Conversion
- description: Corrects errors in approximately 80% of API definitions and validates all specifications before inclusion in the directory.
  name: Quality Control
- description: Companion directory of asynchronous API specifications in AsyncAPI format for event-driven and message-based APIs.
  name: AsyncAPI Directory
- description: Visual tool that represents any GraphQL API as an interactive graph, making schema exploration intuitive and visual.
  name: GraphQL Voyager
- description: Public REST API at api.apis.guru/v2 for programmatic access to the directory, metrics, provider lists, and individual API specs.
  name: REST API Access
- description: RSS feeds for both newly added and recently updated API definitions, allowing developers to stay current with directory changes.
  name: RSS Feeds
- description: Enriches API definitions with logos, categories, provider names, and other metadata to improve discoverability and browsability.
  name: Metadata Enrichment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: HTTP debugging and testing platform that integrates with API definitions from the APIs.guru directory for request interception.
  name: HTTP Toolkit
- description: Microsoft's API client generator that uses OpenAPI specs from APIs.guru to generate typed API clients in multiple languages.
  name: Microsoft Kiota
- description: SDK generation platform that pulls OpenAPI definitions from the directory to generate production-ready SDKs for API providers.
  name: Speakeasy
- description: API documentation generation tool that uses OpenAPI specs from APIs.guru to create beautiful, customizable documentation sites.
  name: ReDoc
- description: Community funding platform where APIs.guru receives financial support from sponsors who benefit from the open directory.
  name: Open Collective
jsonld:
- class_count: 5
  name: Apis Guru Context
  property_count: 23
  slug: apis-guru-context
layout: provider
modified: '2026-04-19'
name: APIs.guru
rules:
- name: APIs.guru API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 13
  slug: apis-guru-spectral-rules
skills: []
slug: apis-guru
solutions: []
tags:
- API Catalog
- API Directory
- API Discovery
- Community
- GraphQL
- Open Source
- OpenAPI
url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/apis.yml
use_cases:
- description: Developers can search and browse the directory to discover public APIs across thousands of providers by category, provider, or keyword.
  name: API Discovery
- description: OpenAPI specs from the directory can be used with tools like Microsoft Kiota and Speakeasy to generate API client SDKs.
  name: SDK Generation
- description: ReDoc and other documentation tools use the directory specs to generate beautiful, interactive API documentation automatically.
  name: API Documentation
- description: HTTP Toolkit and other testing tools leverage the directory for debugging and mocking API requests against standardized specs.
  name: API Testing
- description: GraphQL Voyager allows teams to visually explore GraphQL schema relationships to understand API structure quickly.
  name: Schema Exploration
- description: Organizations can use the directory as a foundation for building their own internal API catalogs and governance programs.
  name: API Catalog Building
---
