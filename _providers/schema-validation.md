---
api_count: 6
apis:
- description: AJV (Another JSON Validator) is the fastest JSON Schema validator for JavaScript and Node.js. It supports JSON Schema drafts 04/06/07/2019-09/ 2020-12 and JSON Type Definition (RFC 8927). AJV compiles
  name: AJV JSON Schema Validator
  slug: ajv
- description: 'Hyperjump is a JSON Schema validation, annotation, and bundling library for JavaScript. It supports JSON Schema drafts 04, 06, 07, 2019-09, 2020-12, OpenAPI 3.0, and OpenAPI 3.1 vocabularies. It also '
  name: Hyperjump JSON Schema
  slug: hyperjump-json-schema
- description: Spectral is an open-source JSON/YAML linter and schema validator from Stoplight. It provides customizable rulesets for validating OpenAPI, AsyncAPI, JSON Schema, and any custom schema format, enabling
  name: Spectral
  slug: spectral
- description: A Node.js library for validating OpenAPI schemas against the OpenAPI specification for versions 2.0 (Swagger), 3.0.x, and 3.1.x. Available as both a library and CLI tool.
  name: OpenAPI Schema Validator
  slug: openapi-schema-validator
- description: An ultra high-performance JSON Schema validator for C++ with support for JSON Schema Draft 4, Draft 6, Draft 7, 2019-09, and 2020-12. Suitable for high-throughput server-side validation scenarios.
  name: Blaze JSON Schema Validator
  slug: blaze-validator
- description: A tooling library for upgrading JSON Schema documents from previous versions (Draft 4, 6, 7, 2019-09) to the latest draft 2020-12, enabling schema modernization pipelines.
  name: AlterSchema
  slug: alterschema
common:
- title: ''
  type: Website
  url: https://json-schema.org/
- title: ''
  type: Documentation
  url: https://json-schema.org/learn
- title: ''
  type: Blog
  url: https://apievangelist.com/archive/
- title: ''
  type: GitHub Organization
  url: https://github.com/json-schema-org
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-schema/schema-validation-config-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-structure/schema-validation-config-structure.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-ld/schema-validation-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/vocabulary/schema-validation-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/examples/schema-validation-ajv-example.json
created: '2025'
description: Schema validation is the practice of verifying that data structures conform to a defined schema, contract, or specification. In API development, schema validation ensures API requests and responses match declared OpenAPI, JSON Schema, AsyncAPI, or GraphQL specifications, enabling contract testing, governance, and runtime integrity. Key tools include AJV, Hyperjump JSON Schema, Spectral, and Schemathesis, each addressing different validation contexts from CLI pipelines to runtime API testing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Schema Validation Context
  property_count: 1
  slug: schema-validation-context
layout: provider
modified: '2026-05-02'
name: Schema Validation
skills: []
slug: schema-validation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: schema-validation\nname: Schema Validation\ndescription: >-\n  Schema validation is the practice of verifying that data structures conform\n  to a defined schema, contract, or specification. In API development, schema\n  validation ensures API requests and responses match declared OpenAPI, JSON\n  Schema, AsyncAPI, or GraphQL specifications, enabling contract testing,\n  governance, and runtime integrity. Key tools include AJV, Hyperjump JSON\n  Schema, Spectral, and Schemathesis, each addressing different validation\n  contexts from CLI pipelines to runtime API testing.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Governance\n  - Contract Testing\n  - JSON Schema\n  - OpenAPI\n  - Schema Validation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/apis.yml\ncreated: '2025'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: schema-validation:ajv\n\
  \    name: AJV JSON Schema Validator\n    description: >-\n      AJV (Another JSON Validator) is the fastest JSON Schema validator for\n      JavaScript and Node.js. It supports JSON Schema drafts 04/06/07/2019-09/\n      2020-12 and JSON Type Definition (RFC 8927). AJV compiles schemas to\n      highly optimized JavaScript functions for maximum runtime performance.\n    humanURL: https://ajv.js.org/\n    tags:\n      - JSON Schema\n      - JavaScript\n      - Schema Validation\n      - Node.js\n    properties:\n      - type: Documentation\n        url: https://ajv.js.org/\n      - type: GitHub Repository\n        url: https://github.com/ajv-validator/ajv\n      - type: npm Package\n        url: https://www.npmjs.com/package/ajv\n      - type: API Reference\n        url: https://ajv.js.org/api.html\n  - aid: schema-validation:hyperjump-json-schema\n    name: Hyperjump JSON Schema\n    description: >-\n      Hyperjump is a JSON Schema validation, annotation, and bundling library\n     \
  \ for JavaScript. It supports JSON Schema drafts 04, 06, 07, 2019-09,\n      2020-12, OpenAPI 3.0, and OpenAPI 3.1 vocabularies. It also provides\n      an OAS Schema Validator for OpenAPI-specific validation.\n    humanURL: https://json-schema.hyperjump.io/\n    tags:\n      - JSON Schema\n      - JavaScript\n      - OpenAPI\n      - Schema Validation\n    properties:\n      - type: Documentation\n        url: https://json-schema.hyperjump.io/\n      - type: GitHub Repository\n        url: https://github.com/hyperjump-io/json-schema\n      - type: npm Package\n        url: https://www.npmjs.com/package/@hyperjump/json-schema\n  - aid: schema-validation:spectral\n    name: Spectral\n    description: >-\n      Spectral is an open-source JSON/YAML linter and schema validator from\n      Stoplight. It provides customizable rulesets for validating OpenAPI,\n      AsyncAPI, JSON Schema, and any custom schema format, enabling API\n      governance at the CLI, IDE, and CI/CD pipeline level.\n\
  \    humanURL: https://stoplight.io/open-source/spectral\n    tags:\n      - API Governance\n      - API Linting\n      - JSON Schema\n      - OpenAPI\n      - Schema Validation\n    properties:\n      - type: Documentation\n        url: https://docs.stoplight.io/docs/spectral/\n      - type: GitHub Repository\n        url: https://github.com/stoplightio/spectral\n      - type: npm Package\n        url: https://www.npmjs.com/package/@stoplight/spectral-core\n  - aid: schema-validation:openapi-schema-validator\n    name: OpenAPI Schema Validator\n    description: >-\n      A Node.js library for validating OpenAPI schemas against the OpenAPI\n      specification for versions 2.0 (Swagger), 3.0.x, and 3.1.x. Available\n      as both a library and CLI tool.\n    humanURL: https://github.com/seriousme/openapi-schema-validator\n    tags:\n      - OpenAPI\n      - Schema Validation\n      - Node.js\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/seriousme/openapi-schema-validator\n\
  \      - type: npm Package\n        url: https://www.npmjs.com/package/@seriousme/openapi-schema-validator\n  - aid: schema-validation:blaze-validator\n    name: Blaze JSON Schema Validator\n    description: >-\n      An ultra high-performance JSON Schema validator for C++ with support for\n      JSON Schema Draft 4, Draft 6, Draft 7, 2019-09, and 2020-12. Suitable\n      for high-throughput server-side validation scenarios.\n    humanURL: https://github.com/sourcemeta/blaze\n    tags:\n      - C++\n      - JSON Schema\n      - Performance\n      - Schema Validation\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/sourcemeta/blaze\n  - aid: schema-validation:alterschema\n    name: AlterSchema\n    description: >-\n      A tooling library for upgrading JSON Schema documents from previous\n      versions (Draft 4, 6, 7, 2019-09) to the latest draft 2020-12,\n      enabling schema modernization pipelines.\n    humanURL: https://github.com/sourcemeta/alterschema\n\
  \    tags:\n      - JSON Schema\n      - Schema Migration\n      - Schema Validation\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/sourcemeta/alterschema\ncommon:\n  - type: Website\n    url: https://json-schema.org/\n  - type: Documentation\n    url: https://json-schema.org/learn\n  - type: Blog\n    url: https://apievangelist.com/archive/\n  - type: GitHub Organization\n    url: https://github.com/json-schema-org\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-schema/schema-validation-config-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-structure/schema-validation-config-structure.json\n  - type: JSONLd\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-ld/schema-validation-context.jsonld\n  - type: Vocabulary\n \
  \   url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/vocabulary/schema-validation-vocabulary.yml\n  - type: Examples\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/examples/schema-validation-ajv-example.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/apis.yml
tags:
- API Governance
- Contract Testing
- JSON Schema
- OpenAPI
- Schema Validation
url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/apis.yml
use_cases: []
---
