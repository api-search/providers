---
api_count: 5
apis:
- description: Swagger UI renders OpenAPI specifications as interactive API documentation, allowing developers to explore and test API endpoints directly in the browser. It generates a rich HTML interface with try-i
  name: Swagger UI
  slug: swagger-ui
- description: 'Swagger Editor is a browser-based editor for writing and validating OpenAPI and AsyncAPI specifications with real-time preview and validation. Available as a standalone web application and as Swagger '
  name: Swagger Editor
  slug: swagger-editor
- description: Swagger Codegen generates server stubs, client SDKs, and API documentation from OpenAPI specifications in over 40 languages including Python, Java, JavaScript, Go, Ruby, C#, Swift, and TypeScript.
  name: Swagger Codegen
  slug: swagger-codegen
- description: Swagger Parser (swagger-parser) is a JavaScript library for parsing, validating, and dereferencing OpenAPI 2.0 and 3.x specifications. Available as an npm package.
  name: Swagger Parser
  slug: swagger-parser
- description: The OpenAPI Specification (formerly Swagger Specification) is a language-agnostic standard for describing HTTP APIs. The current versions are OAS 3.1.1 (stable) and OAS 3.2.0 (latest). Governed by the
  name: OpenAPI Specification
  slug: openapi-specification
common:
- title: ''
  type: Website
  url: https://swagger.io
- title: ''
  type: Documentation
  url: https://swagger.io/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/swagger-api
- title: ''
  type: Blog
  url: https://swagger.io/blog/
- title: ''
  type: Tools
  url: https://swagger.io/tools/
- title: ''
  type: OpenAPI Specification
  url: https://swagger.io/specification/
- title: ''
  type: OpenAPI Initiative
  url: https://www.openapis.org/
- title: ''
  type: Community
  url: https://community.smartbear.com/
- title: ''
  type: Twitter
  url: https://twitter.com/SwaggerApi
created: '2025-01-01'
description: Swagger is an open-source framework by SmartBear for designing, building, documenting, and consuming RESTful APIs using the OpenAPI Specification. Originally created by Wordnik in 2011, Swagger became the OpenAPI Specification (OAS) in 2016 under the OpenAPI Initiative. The Swagger toolset includes Swagger UI for interactive documentation, Swagger Editor for writing OpenAPI specs, and Swagger Codegen for generating client SDKs and server stubs. The latest OpenAPI standard version is 3.2.0 (released September 2025).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Swagger Context
  property_count: 25
  slug: swagger-context
layout: provider
modified: '2026-05-02'
name: Swagger
rules:
- name: Swagger API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: swagger-rules
skills: []
slug: swagger
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: swagger\nname: Swagger\ndescription: >-\n  Swagger is an open-source framework by SmartBear for designing, building,\n  documenting, and consuming RESTful APIs using the OpenAPI Specification.\n  Originally created by Wordnik in 2011, Swagger became the OpenAPI Specification\n  (OAS) in 2016 under the OpenAPI Initiative. The Swagger toolset includes Swagger\n  UI for interactive documentation, Swagger Editor for writing OpenAPI specs, and\n  Swagger Codegen for generating client SDKs and server stubs. The latest OpenAPI\n  standard version is 3.2.0 (released September 2025).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - Documentation\n  - Open Source\n  - OpenAPI\n  - REST\n  - Standard\n  - Swagger\nurl: https://raw.githubusercontent.com/api-evangelist/swagger/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: swagger:swagger-ui\n\
  \    name: Swagger UI\n    description: >-\n      Swagger UI renders OpenAPI specifications as interactive API documentation,\n      allowing developers to explore and test API endpoints directly in the browser.\n      It generates a rich HTML interface with try-it-out functionality from any\n      OpenAPI 2.0, 3.0, or 3.1 specification.\n    humanURL: https://swagger.io/tools/swagger-ui/\n    tags:\n      - Documentation\n      - Interactive Docs\n      - Open Source\n      - OpenAPI\n      - UI\n    properties:\n      - type: Documentation\n        url: https://swagger.io/docs/open-source-tools/swagger-ui/usage/installation/\n      - type: Getting Started\n        url: https://swagger.io/docs/open-source-tools/swagger-ui/usage/installation/\n      - type: GitHub Repository\n        url: https://github.com/swagger-api/swagger-ui\n      - type: Docker\n        url: https://hub.docker.com/r/swaggerapi/swagger-ui\n      - type: npm\n        url: https://www.npmjs.com/package/swagger-ui\n\
  \n  - aid: swagger:swagger-editor\n    name: Swagger Editor\n    description: >-\n      Swagger Editor is a browser-based editor for writing and validating\n      OpenAPI and AsyncAPI specifications with real-time preview and validation.\n      Available as a standalone web application and as Swagger Editor Next (v5).\n    humanURL: https://swagger.io/tools/swagger-editor/\n    tags:\n      - API Design\n      - Editor\n      - Open Source\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://swagger.io/docs/open-source-tools/swagger-editor/\n      - type: GitHub Repository\n        url: https://github.com/swagger-api/swagger-editor\n      - type: Live Demo\n        url: https://editor.swagger.io/\n\n  - aid: swagger:swagger-codegen\n    name: Swagger Codegen\n    description: >-\n      Swagger Codegen generates server stubs, client SDKs, and API documentation\n      from OpenAPI specifications in over 40 languages including Python, Java,\n      JavaScript,\
  \ Go, Ruby, C#, Swift, and TypeScript.\n    humanURL: https://swagger.io/tools/swagger-codegen/\n    tags:\n      - Code Generation\n      - Open Source\n      - OpenAPI\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://swagger.io/docs/open-source-tools/swagger-codegen/\n      - type: GitHub Repository\n        url: https://github.com/swagger-api/swagger-codegen\n      - type: Docker\n        url: https://hub.docker.com/r/swaggerapi/swagger-codegen-cli-v3\n      - type: Generator API\n        url: https://generator3.swagger.io/\n\n  - aid: swagger:swagger-parser\n    name: Swagger Parser\n    description: >-\n      Swagger Parser (swagger-parser) is a JavaScript library for parsing,\n      validating, and dereferencing OpenAPI 2.0 and 3.x specifications.\n      Available as an npm package.\n    humanURL: https://github.com/swagger-api/swagger-parser\n    tags:\n      - JavaScript\n      - OpenAPI\n      - Parser\n      - Tooling\n    properties:\n      -\
  \ type: GitHub Repository\n        url: https://github.com/swagger-api/swagger-parser\n      - type: npm\n        url: https://www.npmjs.com/package/swagger-parser\n\n  - aid: swagger:openapi-specification\n    name: OpenAPI Specification\n    description: >-\n      The OpenAPI Specification (formerly Swagger Specification) is a\n      language-agnostic standard for describing HTTP APIs. The current versions\n      are OAS 3.1.1 (stable) and OAS 3.2.0 (latest). Governed by the OpenAPI\n      Initiative (OAI) under the Linux Foundation.\n    humanURL: https://swagger.io/specification/\n    tags:\n      - OpenAPI\n      - REST\n      - Standard\n    properties:\n      - type: Specification\n        url: https://swagger.io/specification/\n      - type: GitHub Repository\n        url: https://github.com/OAI/OpenAPI-Specification\n      - type: OpenAPI 3.2\n        url: https://spec.openapis.org/oas/v3.2.0.html\n      - type: OpenAPI 3.1\n        url: https://spec.openapis.org/oas/v3.1.0.html\n\
  \      - type: OpenAPI 2.0\n        url: https://swagger.io/specification/v2/\n\ncommon:\n  - type: Website\n    url: https://swagger.io\n  - type: Documentation\n    url: https://swagger.io/docs/\n  - type: GitHub Organization\n    url: https://github.com/swagger-api\n  - type: Blog\n    url: https://swagger.io/blog/\n  - type: Tools\n    url: https://swagger.io/tools/\n  - type: OpenAPI Specification\n    url: https://swagger.io/specification/\n  - type: OpenAPI Initiative\n    url: https://www.openapis.org/\n  - type: Community\n    url: https://community.smartbear.com/\n  - type: Twitter\n    url: https://twitter.com/SwaggerApi\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/swagger/refs/heads/main/apis.yml
tags:
- API Design
- Documentation
- Open Source
- OpenAPI
- REST
- Standard
- Swagger
url: https://raw.githubusercontent.com/api-evangelist/swagger/refs/heads/main/apis.yml
use_cases: []
---
