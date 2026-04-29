---
api_count: 4
apis:
- description: 'Apicurio Registry is a high-performance, runtime registry for schemas and API designs. It stores and manages OpenAPI, AsyncAPI, Avro, JSON Schema, Protobuf, and other artifact types, providing a REST '
  name: Apicurio Registry
  slug: apicurio-registry
- description: 'Apicurio Studio is a visual, zero-code API design tool for creating and editing OpenAPI and AsyncAPI specifications. Note: Apicurio Studio is deprecated in favor of the integrated design capabilities '
  name: Apicurio Studio
  slug: apicurio-studio
- description: Apicurio Data Models is a Java and TypeScript library for parsing, validating, and manipulating OpenAPI and AsyncAPI specification documents programmatically.
  name: Apicurio Data Models
  slug: apicurio-data-models
- description: Apicurio Codegen generates Java JAX-RS server stubs and client code from OpenAPI specifications, enabling design-first API development workflows.
  name: Apicurio Codegen
  slug: apicurio-codegen
common:
- title: ''
  type: Website
  url: https://www.apicur.io
- title: ''
  type: Documentation
  url: https://www.apicur.io/registry/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Apicurio
- title: ''
  type: License
  url: https://github.com/Apicurio/apicurio-registry/blob/main/LICENSE
created: '2026-03-25'
description: Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for OpenAPI and AsyncAPI), Apicurio Data Models (a data modeling library), Apicurio Codegen (Java code generation from OpenAPI), and Apicurito (an embedded API editor).
features:
- description: High-performance registry for storing and versioning schemas including Avro, JSON Schema, Protobuf, OpenAPI, and AsyncAPI.
  name: Schema Registry
- description: Enforce backward, forward, or full compatibility rules when evolving schemas to prevent breaking changes.
  name: Schema Compatibility Checking
- description: Zero-code visual editor for creating OpenAPI and AsyncAPI specifications without writing raw YAML or JSON.
  name: Visual API Design
- description: Full REST API for programmatic schema registration, retrieval, and version management.
  name: REST API for Schema Management
- description: Generate JAX-RS server stubs and client code from OpenAPI specifications for design-first Java development.
  name: Java Code Generation
- description: Support for OpenAPI, AsyncAPI, Avro, JSON Schema, Protobuf, WSDL, XSD, and GraphQL artifact types.
  name: Multi-Format Support
- description: Open source under the Apache License 2.0, maintained by Red Hat with community contributions.
  name: Apache License 2.0
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Apicurio
skills: []
slug: apicurio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apicurio\nname: Apicurio\ndescription: >-\n  Apicurio is an open source API and schema tooling platform maintained by Red\n  Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance\n  schema and API design registry), Apicurio Studio (a visual API designer for OpenAPI\n  and AsyncAPI), Apicurio Data Models (a data modeling library), Apicurio Codegen\n  (Java code generation from OpenAPI), and Apicurito (an embedded API editor).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache License\n  - API Design\n  - API Registry\n  - Avro\n  - AsyncAPI\n  - Java\n  - Open Source\n  - OpenAPI\n  - Red Hat\n  - Schema Registry\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apicurio/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apicurio:apicurio-registry\n    name: Apicurio Registry\n    description: >-\n  \
  \    Apicurio Registry is a high-performance, runtime registry for schemas and\n      API designs. It stores and manages OpenAPI, AsyncAPI, Avro, JSON Schema,\n      Protobuf, and other artifact types, providing a REST API for schema\n      management with compatibility checking and content versioning.\n    humanURL: https://www.apicur.io/registry/\n    tags:\n      - Avro\n      - AsyncAPI\n      - Open Source\n      - OpenAPI\n      - Protobuf\n      - Schema Registry\n    properties:\n      - type: Documentation\n        url: https://www.apicur.io/registry/docs/\n      - type: GitHubRepository\n        url: https://github.com/Apicurio/apicurio-registry\n  - aid: apicurio:apicurio-studio\n    name: Apicurio Studio\n    description: >-\n      Apicurio Studio is a visual, zero-code API design tool for creating and\n      editing OpenAPI and AsyncAPI specifications. Note: Apicurio Studio is\n      deprecated in favor of the integrated design capabilities in Apicurio\n      Registry.\n \
  \   humanURL: https://www.apicur.io/studio/\n    tags:\n      - API Design\n      - AsyncAPI\n      - Deprecated\n      - OpenAPI\n      - Visual Designer\n    properties:\n      - type: Documentation\n        url: https://www.apicur.io/studio/docs/\n      - type: GitHubRepository\n        url: https://github.com/Apicurio/apicurio-studio\n  - aid: apicurio:apicurio-data-models\n    name: Apicurio Data Models\n    description: >-\n      Apicurio Data Models is a Java and TypeScript library for parsing,\n      validating, and manipulating OpenAPI and AsyncAPI specification documents\n      programmatically.\n    humanURL: https://github.com/Apicurio/apicurio-data-models\n    tags:\n      - AsyncAPI\n      - Data Modeling\n      - Java\n      - Library\n      - OpenAPI\n      - TypeScript\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/Apicurio/apicurio-data-models\n  - aid: apicurio:apicurio-codegen\n    name: Apicurio Codegen\n    description: >-\n    \
  \  Apicurio Codegen generates Java JAX-RS server stubs and client code from\n      OpenAPI specifications, enabling design-first API development workflows.\n    humanURL: https://github.com/Apicurio/apicurio-codegen\n    tags:\n      - Code Generation\n      - JAX-RS\n      - Java\n      - OpenAPI\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/Apicurio/apicurio-codegen\ncommon:\n  - type: Website\n    url: https://www.apicur.io\n  - type: Documentation\n    url: https://www.apicur.io/registry/docs/\n  - type: GitHubOrganization\n    url: https://github.com/Apicurio\n  - type: License\n    url: https://github.com/Apicurio/apicurio-registry/blob/main/LICENSE\n  - type: Features\n    data:\n      - name: Schema Registry\n        description: High-performance registry for storing and versioning schemas including Avro, JSON Schema, Protobuf, OpenAPI, and AsyncAPI.\n      - name: Schema Compatibility Checking\n        description: Enforce backward, forward,\
  \ or full compatibility rules when evolving schemas to prevent breaking changes.\n      - name: Visual API Design\n        description: Zero-code visual editor for creating OpenAPI and AsyncAPI specifications without writing raw YAML or JSON.\n      - name: REST API for Schema Management\n        description: Full REST API for programmatic schema registration, retrieval, and version management.\n      - name: Java Code Generation\n        description: Generate JAX-RS server stubs and client code from OpenAPI specifications for design-first Java development.\n      - name: Multi-Format Support\n        description: Support for OpenAPI, AsyncAPI, Avro, JSON Schema, Protobuf, WSDL, XSD, and GraphQL artifact types.\n      - name: Apache License 2.0\n        description: Open source under the Apache License 2.0, maintained by Red Hat with community contributions.\n  - type: UseCases\n    data:\n      - name: Schema Governance\n        description: Centrally manage and version schemas across\
  \ microservices with compatibility enforcement to prevent breaking changes.\n      - name: Design-First API Development\n        description: Design OpenAPI and AsyncAPI specifications visually before writing code for design-first development.\n      - name: Event-Driven Architecture\n        description: Manage Avro and Protobuf schemas for Kafka and other messaging systems in event-driven architectures.\n      - name: API Contract Management\n        description: Store and version API specifications as the system of record for API contracts across teams.\n      - name: Java Code Scaffolding\n        description: Generate JAX-RS server stubs from OpenAPI specs to accelerate Java API implementation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apicurio/refs/heads/main/apis.yml
tags:
- Apache License
- API Design
- API Registry
- Avro
- AsyncAPI
- Java
- Open Source
- OpenAPI
- Red Hat
- Schema Registry
url: https://raw.githubusercontent.com/api-evangelist/apicurio/refs/heads/main/apis.yml
use_cases:
- description: Centrally manage and version schemas across microservices with compatibility enforcement to prevent breaking changes.
  name: Schema Governance
- description: Design OpenAPI and AsyncAPI specifications visually before writing code for design-first development.
  name: Design-First API Development
- description: Manage Avro and Protobuf schemas for Kafka and other messaging systems in event-driven architectures.
  name: Event-Driven Architecture
- description: Store and version API specifications as the system of record for API contracts across teams.
  name: API Contract Management
- description: Generate JAX-RS server stubs from OpenAPI specs to accelerate Java API implementation.
  name: Java Code Scaffolding
---
