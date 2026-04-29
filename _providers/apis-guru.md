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
source_filename: apis.yml
source_yaml: "aid: apis-guru\nname: APIs.guru\ndescription: >-\n  APIs.guru is an open source, community-driven directory of public REST API\n  definitions in OpenAPI 2.0/3.x format, described as the Wikipedia for Web\n  APIs. The project searches for public API definitions, converts various\n  formats to OpenAPI 3.0, corrects errors in approximately 80% of definitions,\n  and enriches entries with logos, categories, and metadata. It catalogs over\n  2,500 API descriptions with 100,000+ endpoints, updating definitions weekly\n  from original sources. The platform is licensed under CC0-1.0 for contributed\n  definitions and welcomes community contributions through GitHub.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Catalog\n  - API Directory\n  - API Discovery\n  - Community\n  - GraphQL\n  - Open Source\n  - OpenAPI\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/apis.yml\ncreated: '2026-03-25'\n\
  modified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apis-guru:apis-guru-api\n    name: APIs.guru REST API\n    description: >-\n      The APIs.guru REST API provides programmatic access to the directory of\n      public API definitions, allowing developers to search, browse, and\n      retrieve OpenAPI specifications from the catalog. The API is public and\n      requires no authentication. It provides endpoints to list all APIs, fetch\n      metrics, retrieve provider lists, and access specific API version details\n      including direct links to OpenAPI specs in JSON and YAML formats.\n    humanURL: https://apis.guru/api-doc\n    baseURL: https://api.apis.guru/v2\n    tags:\n      - API Catalog\n      - API Directory\n      - API Discovery\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://apis.guru/api-doc\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/openapi/apis-guru-openapi.yaml\n\
  \      - type: Postman Collection\n        url: https://www.postman.com/api-evangelist/apis-guru/documentation/wtbfnfn/apis-guru\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-api-schema.json\n        title: API Schema\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-api-version-schema.json\n        title: API Version Schema\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-metrics-schema.json\n        title: Metrics Schema\ncommon:\n  - type: Website\n    url: https://apis.guru\n  - type: About\n    url: https://apis.guru/about\n  - type: Documentation\n    url: https://apis.guru/api-doc\n  - type: Blog\n    url: https://apis.guru/blog\n  - type: GitHubOrganization\n    url: https://github.com/APIs-guru\n\
  \  - type: GitHubRepository\n    url: https://github.com/APIs-guru/openapi-directory\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/asyncapi-directory\n    title: AsyncAPI Directory\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/graphql-voyager\n    title: GraphQL Voyager\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/awesome-openapi3\n    title: Awesome OpenAPI 3\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/aws2openapi\n    title: AWS to OpenAPI Converter\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/google-discovery-to-swagger\n    title: Google Discovery to OpenAPI Converter\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/graphql-faker\n    title: GraphQL Faker\n  - type: GitHubRepository\n    url: https://github.com/APIs-guru/graphql-apis\n    title: Public GraphQL APIs Directory\n  - type: X\n    url: https://x.com/APIs_guru\n  - type: SpectralRules\n    url: >-\n\
  \      https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/rules/apis-guru-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/vocabulary/apis-guru-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/capabilities/api-discovery.yaml\n    title: API Discovery Capability\n  - type: Support\n    url: https://github.com/APIs-guru/openapi-directory/issues\n  - type: Features\n    data:\n      - name: OpenAPI Directory\n        description: >-\n          Comprehensive directory of over 2,500 public API definitions in\n          OpenAPI 2.0 and 3.x format, updated weekly from original sources.\n      - name: Format Conversion\n        description: >-\n          Converts various API description formats (RAML, Google Discovery,\n          AWS, etc.) to OpenAPI 3.0 standard for consistency and compatibility.\n\
  \      - name: Quality Control\n        description: >-\n          Corrects errors in approximately 80% of API definitions and validates\n          all specifications before inclusion in the directory.\n      - name: AsyncAPI Directory\n        description: >-\n          Companion directory of asynchronous API specifications in AsyncAPI\n          format for event-driven and message-based APIs.\n      - name: GraphQL Voyager\n        description: >-\n          Visual tool that represents any GraphQL API as an interactive graph,\n          making schema exploration intuitive and visual.\n      - name: REST API Access\n        description: >-\n          Public REST API at api.apis.guru/v2 for programmatic access to the\n          directory, metrics, provider lists, and individual API specs.\n      - name: RSS Feeds\n        description: >-\n          RSS feeds for both newly added and recently updated API definitions,\n          allowing developers to stay current with directory changes.\n\
  \      - name: Metadata Enrichment\n        description: >-\n          Enriches API definitions with logos, categories, provider names, and\n          other metadata to improve discoverability and browsability.\n  - type: UseCases\n    data:\n      - name: API Discovery\n        description: >-\n          Developers can search and browse the directory to discover public\n          APIs across thousands of providers by category, provider, or keyword.\n      - name: SDK Generation\n        description: >-\n          OpenAPI specs from the directory can be used with tools like\n          Microsoft Kiota and Speakeasy to generate API client SDKs.\n      - name: API Documentation\n        description: >-\n          ReDoc and other documentation tools use the directory specs to\n          generate beautiful, interactive API documentation automatically.\n      - name: API Testing\n        description: >-\n          HTTP Toolkit and other testing tools leverage the directory for\n          debugging\
  \ and mocking API requests against standardized specs.\n      - name: Schema Exploration\n        description: >-\n          GraphQL Voyager allows teams to visually explore GraphQL schema\n          relationships to understand API structure quickly.\n      - name: API Catalog Building\n        description: >-\n          Organizations can use the directory as a foundation for building\n          their own internal API catalogs and governance programs.\n  - type: Integrations\n    data:\n      - name: HTTP Toolkit\n        description: >-\n          HTTP debugging and testing platform that integrates with API\n          definitions from the APIs.guru directory for request interception.\n      - name: Microsoft Kiota\n        description: >-\n          Microsoft's API client generator that uses OpenAPI specs from\n          APIs.guru to generate typed API clients in multiple languages.\n      - name: Speakeasy\n        description: >-\n          SDK generation platform that pulls OpenAPI\
  \ definitions from the\n          directory to generate production-ready SDKs for API providers.\n      - name: ReDoc\n        description: >-\n          API documentation generation tool that uses OpenAPI specs from\n          APIs.guru to create beautiful, customizable documentation sites.\n      - name: Open Collective\n        description: >-\n          Community funding platform where APIs.guru receives financial support\n          from sponsors who benefit from the open directory.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/apis.yml
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
