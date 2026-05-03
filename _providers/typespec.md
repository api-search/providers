---
api_count: 6
apis:
- description: The TypeSpec compiler processes `.tsp` TypeSpec files and emits output for configured emitters (OpenAPI, JSON Schema, Protobuf, etc.). It provides a programmatic Node.js/TypeScript API for building Ty
  name: TypeSpec Compiler
  slug: typespec-compiler
- description: The TypeSpec OpenAPI emitter converts TypeSpec definitions to OpenAPI 3.0 specifications. It supports HTTP operations, request/response bodies, security schemes, and API versioning decorators.
  name: TypeSpec OpenAPI Emitter
  slug: typespec-openapi-emitter
- description: Emits JSON Schema documents from TypeSpec model definitions, enabling data validation and type documentation workflows.
  name: TypeSpec JSON Schema Emitter
  slug: typespec-json-schema-emitter
- description: Emits Protocol Buffer `.proto` files from TypeSpec service definitions, enabling gRPC service generation from a single TypeSpec source.
  name: TypeSpec Protobuf Emitter
  slug: typespec-protobuf-emitter
- description: The TypeSpec HTTP library provides decorators and types for describing HTTP REST APIs including routes, operations, request bodies, query parameters, headers, and response codes.
  name: TypeSpec HTTP Library
  slug: typespec-http-library
- description: The TypeSpec REST library provides decorators for REST API patterns including resource operations (CRUD), collection operations, and standardized error response shapes.
  name: TypeSpec REST Library
  slug: typespec-rest-library
common:
- title: ''
  type: Website
  url: https://typespec.io
- title: ''
  type: Documentation
  url: https://typespec.io/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft/typespec
- title: ''
  type: npm
  url: https://www.npmjs.com/package/@typespec/compiler
- title: ''
  type: Playground
  url: https://typespec.io/playground
- title: ''
  type: Blog
  url: https://typespec.io/blog
- title: ''
  type: Community
  url: https://github.com/microsoft/typespec/discussions
- title: ''
  type: Release Notes
  url: https://github.com/microsoft/typespec/releases
- title: ''
  type: JSON-LD
  url: json-ld/typespec-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/typespec-vocabulary.yml
- title: ''
  type: JSONSchema
  url: json-schema/typespec-program-schema.json
created: '2026-03-25'
description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services, and data schemas in a type-safe, composable way with built-in support for versioning, metadata, and extensibility via decorators and libraries.
features: []
image: https://typespec.io/img/favicon.svg
integrations: []
jsonld:
- class_count: 15
  name: Typespec Context
  property_count: 11
  slug: typespec-context
layout: provider
modified: '2026-05-03'
name: TypeSpec
skills: []
slug: typespec
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: typespec\nname: TypeSpec\ndescription: >-\n  TypeSpec is an API description language developed by Microsoft for defining\n  API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output\n  formats. It provides a language and toolchain for describing REST APIs,\n  gRPC services, and data schemas in a type-safe, composable way with\n  built-in support for versioning, metadata, and extensibility via decorators\n  and libraries.\ntype: Index\nimage: https://typespec.io/img/favicon.svg\ntags:\n  - API Design\n  - Code Generation\n  - OpenAPI\n  - Protocol Buffers\n  - Specification Language\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/typespec/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: typespec:typespec-compiler\n    name: TypeSpec Compiler\n    description: >-\n      The TypeSpec compiler processes `.tsp` TypeSpec files and emits output\n      for configured emitters (OpenAPI,\
  \ JSON Schema, Protobuf, etc.). It\n      provides a programmatic Node.js/TypeScript API for building TypeSpec\n      tooling, custom emitters, and compilers.\n    humanURL: https://typespec.io/docs\n    tags:\n      - API Design\n      - Code Generation\n      - Compiler\n      - Specification Language\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs\n      - type: GitHub Repository\n        url: https://github.com/microsoft/typespec\n      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/compiler\n      - type: Getting Started\n        url: https://typespec.io/docs/getting-started/getting-started-rest\n      - type: Language Reference\n        url: https://typespec.io/docs/language-basics/overview\n\n  - aid: typespec:typespec-openapi-emitter\n    name: TypeSpec OpenAPI Emitter\n    description: >-\n      The TypeSpec OpenAPI emitter converts TypeSpec definitions to OpenAPI 3.0\n      specifications. It supports HTTP operations,\
  \ request/response bodies,\n      security schemes, and API versioning decorators.\n    humanURL: https://typespec.io/docs/emitters/openapi3/reference\n    tags:\n      - Code Generation\n      - OpenAPI\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs/emitters/openapi3/reference\n      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/openapi3\n      - type: GitHub Repository\n        url: https://github.com/microsoft/typespec/tree/main/packages/openapi3\n\n  - aid: typespec:typespec-json-schema-emitter\n    name: TypeSpec JSON Schema Emitter\n    description: >-\n      Emits JSON Schema documents from TypeSpec model definitions, enabling\n      data validation and type documentation workflows.\n    humanURL: https://typespec.io/docs/emitters/json-schema/reference\n    tags:\n      - Code Generation\n      - JSON Schema\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs/emitters/json-schema/reference\n\
  \      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/json-schema\n\n  - aid: typespec:typespec-protobuf-emitter\n    name: TypeSpec Protobuf Emitter\n    description: >-\n      Emits Protocol Buffer `.proto` files from TypeSpec service definitions,\n      enabling gRPC service generation from a single TypeSpec source.\n    humanURL: https://typespec.io/docs/emitters/protobuf/reference\n    tags:\n      - Code Generation\n      - gRPC\n      - Protocol Buffers\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs/emitters/protobuf/reference\n      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/protobuf\n\n  - aid: typespec:typespec-http-library\n    name: TypeSpec HTTP Library\n    description: >-\n      The TypeSpec HTTP library provides decorators and types for describing\n      HTTP REST APIs including routes, operations, request bodies, query\n      parameters, headers, and response codes.\n    humanURL:\
  \ https://typespec.io/docs/libraries/http/reference\n    tags:\n      - Decorators\n      - HTTP\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs/libraries/http/reference\n      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/http\n\n  - aid: typespec:typespec-rest-library\n    name: TypeSpec REST Library\n    description: >-\n      The TypeSpec REST library provides decorators for REST API patterns\n      including resource operations (CRUD), collection operations, and\n      standardized error response shapes.\n    humanURL: https://typespec.io/docs/libraries/rest/reference\n    tags:\n      - Decorators\n      - Resource Pattern\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://typespec.io/docs/libraries/rest/reference\n      - type: npm Package\n        url: https://www.npmjs.com/package/@typespec/rest\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  common:\n  - type: Website\n    url: https://typespec.io\n  - type: Documentation\n    url: https://typespec.io/docs\n  - type: GitHub Organization\n    url: https://github.com/microsoft/typespec\n  - type: npm\n    url: https://www.npmjs.com/package/@typespec/compiler\n  - type: Playground\n    url: https://typespec.io/playground\n  - type: Blog\n    url: https://typespec.io/blog\n  - type: Community\n    url: https://github.com/microsoft/typespec/discussions\n  - type: Release Notes\n    url: https://github.com/microsoft/typespec/releases\n  - type: JSON-LD\n    url: json-ld/typespec-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/typespec-vocabulary.yml\n  - type: JSONSchema\n    url: json-schema/typespec-program-schema.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/typespec/refs/heads/main/apis.yml
tags:
- API Design
- Code Generation
- OpenAPI
- Protocol Buffers
- Specification Language
url: https://raw.githubusercontent.com/api-evangelist/typespec/refs/heads/main/apis.yml
use_cases: []
---
