---
api_count: 4
apis:
- description: 'The OpenAPI Specification (OAS) is the industry-standard format for describing REST/HTTP APIs. Maintained by the OpenAPI Initiative under the Linux Foundation, it enables code generation, interactive '
  name: OpenAPI Specification
  slug: openapi
- description: AsyncAPI is the standard for defining event-driven and message-based APIs. Modeled on the OpenAPI Specification but extended for asynchronous protocols including Kafka, AMQP, MQTT, WebSocket, and SNS/
  name: AsyncAPI Specification
  slug: asyncapi
- description: JSON Schema is a vocabulary for annotating and validating JSON documents. It is the foundation of OpenAPI 3.1 schema definitions and used across the API ecosystem for request/response validation, code
  name: JSON Schema
  slug: json-schema
- description: The Arazzo Specification (formerly OpenAPI Workflows) describes multi-step API sequences, enabling documentation and automated testing of complex API interactions that span multiple operations. Used f
  name: Arazzo Specification
  slug: arazzo
common:
- title: ''
  type: Organization
  url: https://www.openapis.org/
- title: ''
  type: Organization
  url: https://www.asyncapi.com/
- title: ''
  type: Organization
  url: https://json-schema.org/
- title: ''
  type: Tools
  url: https://openapi.tools/
- title: ''
  type: Specification
  url: https://spec.openapis.org/oas/latest.html
created: '2025-01-01'
description: A subject-matter collection covering API specifications, specification formats, specification-driven development, and the broader specification landscape. This includes OpenAPI, AsyncAPI, JSON Schema, GraphQL SDL, Arazzo, gRPC Protocol Buffers, RAML, API Blueprint, and other machine-readable API description formats. Specification-first development treats the API contract as the source of truth for code generation, documentation, testing, and governance.
features:
- name: API Description
- name: Request Validation
- name: Response Validation
- name: Code Generation
- name: Mock Servers
- name: Interactive Documentation
- name: Contract Testing
- name: API Governance
- name: Schema Reuse
- name: Security Definitions
- name: Path Templates
- name: Content Negotiation
- name: Webhook Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Specification Context
  property_count: 11
  slug: specification-context
layout: provider
modified: '2026-05-02'
name: Specification
skills: []
slug: specification
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: specification\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/specification/refs/heads/main/apis.yml\nname: Specification\ndescription: >-\n  A subject-matter collection covering API specifications, specification formats,\n  specification-driven development, and the broader specification landscape. This\n  includes OpenAPI, AsyncAPI, JSON Schema, GraphQL SDL, Arazzo, gRPC Protocol\n  Buffers, RAML, API Blueprint, and other machine-readable API description formats.\n  Specification-first development treats the API contract as the source of truth\n  for code generation, documentation, testing, and governance.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ntags:\n  - API Design\n  - API Governance\n  - AsyncAPI\n  - Contract Testing\n  - JSON Schema\n  - OpenAPI\n  - Specifications\n  - Standards\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nposition: Consumer\nsegments:\n  - Specifications\n\
  \  - API Design\napis:\n  - aid: specification:openapi\n    name: OpenAPI Specification\n    tags:\n      - API Design\n      - Code Generation\n      - Documentation\n      - HTTP\n      - OpenAPI\n      - REST\n      - Standards\n    humanURL: https://www.openapis.org/\n    properties:\n      - url: https://www.openapis.org/\n        type: Website\n      - url: https://spec.openapis.org/oas/latest.html\n        type: Specification\n      - url: https://github.com/OAI/OpenAPI-Specification\n        type: GitHubRepo\n      - url: https://openapi.tools/\n        type: Tools\n    description: >-\n      The OpenAPI Specification (OAS) is the industry-standard format for\n      describing REST/HTTP APIs. Maintained by the OpenAPI Initiative under\n      the Linux Foundation, it enables code generation, interactive documentation,\n      mock servers, contract testing, and governance tooling from a single\n      machine-readable API contract. Current version is OpenAPI 3.1, which\n      achieves\
  \ full JSON Schema alignment.\n  - aid: specification:asyncapi\n    name: AsyncAPI Specification\n    tags:\n      - AsyncAPI\n      - Event-Driven\n      - Kafka\n      - Messaging\n      - Standards\n      - WebSocket\n    humanURL: https://www.asyncapi.com/\n    properties:\n      - url: https://www.asyncapi.com/\n        type: Website\n      - url: https://www.asyncapi.com/docs/reference/specification/latest\n        type: Specification\n      - url: https://github.com/asyncapi/spec\n        type: GitHubRepo\n    description: >-\n      AsyncAPI is the standard for defining event-driven and message-based APIs.\n      Modeled on the OpenAPI Specification but extended for asynchronous protocols\n      including Kafka, AMQP, MQTT, WebSocket, and SNS/SQS. Used for generating\n      documentation, code, and governance tooling for async API surfaces.\n  - aid: specification:json-schema\n    name: JSON Schema\n    tags:\n      - Data Validation\n      - JSON\n      - JSON Schema\n      - Standards\n\
  \    humanURL: https://json-schema.org/\n    properties:\n      - url: https://json-schema.org/\n        type: Website\n      - url: https://json-schema.org/specification\n        type: Specification\n      - url: https://github.com/json-schema-org/json-schema-spec\n        type: GitHubRepo\n    description: >-\n      JSON Schema is a vocabulary for annotating and validating JSON documents.\n      It is the foundation of OpenAPI 3.1 schema definitions and used across\n      the API ecosystem for request/response validation, code generation,\n      and data contract enforcement.\n  - aid: specification:arazzo\n    name: Arazzo Specification\n    tags:\n      - API Workflows\n      - Arazzo\n      - Contract Testing\n      - OpenAPI\n      - Sequences\n      - Standards\n    humanURL: https://spec.openapis.org/arazzo/latest.html\n    properties:\n      - url: https://spec.openapis.org/arazzo/latest.html\n        type: Specification\n      - url: https://github.com/OAI/Arazzo-Specification\n\
  \        type: GitHubRepo\n    description: >-\n      The Arazzo Specification (formerly OpenAPI Workflows) describes multi-step\n      API sequences, enabling documentation and automated testing of complex API\n      interactions that span multiple operations. Used for contract testing and\n      API workflow documentation by tools like Speakeasy.\ncommon:\n  - url: https://www.openapis.org/\n    name: OpenAPI Initiative\n    type: Organization\n    description: 'null'\n  - url: https://www.asyncapi.com/\n    name: AsyncAPI Initiative\n    type: Organization\n    description: 'null'\n  - url: https://json-schema.org/\n    name: JSON Schema Organization\n    type: Organization\n    description: 'null'\n  - url: https://openapi.tools/\n    name: OpenAPI Tools Directory\n    type: Tools\n    description: 'null'\n  - url: https://spec.openapis.org/oas/latest.html\n    name: OpenAPI Specification Latest\n    type: Specification\n    description: 'null'\n  - name: Features\n    type: Features\n\
  \    data:\n      - name: API Description\n      - name: Request Validation\n      - name: Response Validation\n      - name: Code Generation\n      - name: Mock Servers\n      - name: Interactive Documentation\n      - name: Contract Testing\n      - name: API Governance\n      - name: Schema Reuse\n      - name: Security Definitions\n      - name: Path Templates\n      - name: Content Negotiation\n      - name: Webhook Support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/specification/refs/heads/main/apis.yml
tags:
- API Design
- API Governance
- AsyncAPI
- Contract Testing
- JSON Schema
- OpenAPI
- Specifications
- Standards
url: https://raw.githubusercontent.com/api-evangelist/specification/refs/heads/main/apis.yml
use_cases: []
---
