---
api_count: 1
api_specs:
- filename: schema-registry.yml
  format: yaml
  label: Confluent Schema Registry REST API
  slug: schema-registry-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/openapi/schema-registry.yml
apis:
- description: The Confluent Schema Registry REST API provides programmatic management of schemas, subjects, schema versions, schema references, compatibility modes, and operating mode. Producers and consumers use i
  name: Confluent Schema Registry REST API
  slug: schema-registry-rest-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.confluent.io/
- title: ''
  type: Documentation
  url: https://docs.confluent.io/platform/current/schema-registry/
- title: ''
  type: Getting Started
  url: https://docs.confluent.io/platform/current/schema-registry/develop/using.html
- title: ''
  type: API Reference
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- title: ''
  type: GitHub
  url: https://github.com/confluentinc/schema-registry
- title: ''
  type: License
  url: https://www.confluent.io/confluent-community-license/
- title: ''
  type: Blog
  url: https://www.confluent.io/blog/
- title: ''
  type: Pricing
  url: https://www.confluent.io/pricing/
- title: ''
  type: JSON-LD
  url: json-ld/confluent-schema-registry-context.jsonld
- title: ''
  type: Spectral
  url: rules/confluent-schema-registry-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/confluent-schema-registry-capabilities.yml
created: '2026-03-26'
description: Confluent Schema Registry is the open-source serving layer for schema metadata used in Apache Kafka data pipelines. It exposes a RESTful interface for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages schema evolution through configurable compatibility rules (BACKWARD, FORWARD, FULL, and transitive variants), supports schema references and contexts, and integrates with Kafka producers and consumers via shipped serializers and deserializers. Schema Registry is distributed under the Confluent Community License and is a core component of both Confluent Platform and Confluent Cloud.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Confluent Schema Registry Context
  property_count: 10
  slug: confluent-schema-registry-context
layout: provider
modified: '2026-04-28'
name: Confluent Schema Registry
rules:
- name: Confluent Schema Registry API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: confluent-schema-registry-rules
skills: []
slug: confluent-schema-registry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: confluent-schema-registry\nname: Confluent Schema Registry\ndescription: >-\n  Confluent Schema Registry is the open-source serving layer for schema\n  metadata used in Apache Kafka data pipelines. It exposes a RESTful interface\n  for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages\n  schema evolution through configurable compatibility rules (BACKWARD,\n  FORWARD, FULL, and transitive variants), supports schema references and\n  contexts, and integrates with Kafka producers and consumers via shipped\n  serializers and deserializers. Schema Registry is distributed under the\n  Confluent Community License and is a core component of both Confluent\n  Platform and Confluent Cloud.\ntype: Index\nposition: Provider\naccess: Open Source\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml\ncreated: '2026-03-26'\n\
  modified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: opensource\ntags:\n  - Apache Kafka\n  - Avro\n  - Compatibility\n  - Confluent\n  - Data Governance\n  - Data Streaming\n  - JSON Schema\n  - Open Source\n  - Protobuf\n  - REST\n  - Schema Evolution\n  - Schema Registry\napis:\n  - aid: confluent-schema-registry:schema-registry-rest-api\n    name: Confluent Schema Registry REST API\n    description: >-\n      The Confluent Schema Registry REST API provides programmatic management\n      of schemas, subjects, schema versions, schema references, compatibility\n      modes, and operating mode. Producers and consumers use it to register\n      and look up Avro, JSON Schema, and Protobuf schemas, while platform\n      teams use it to enforce schema evolution policies through subject- and\n      cluster-level compatibility settings. The API uses the\n      application/vnd.schemaregistry.v1+json content type and supports\n      authentication via HTTP Basic, mTLS, or OAuth depending\
  \ on deployment.\n    humanURL: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n    baseURL: http://localhost:8081\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Compatibility\n      - REST\n      - Schemas\n      - Subjects\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n      - type: OpenAPI\n        url: openapi/schema-registry.yml\n      - type: JSONSchema\n        url: json-schema/schema-registry-schema.json\n      - type: JSON-LD\n        url: json-ld/confluent-schema-registry-context.jsonld\n      - type: Spectral\n        url: rules/confluent-schema-registry-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/confluent-schema-registry-capabilities.yml\n      - type: GitHub\n        url: https://github.com/confluentinc/schema-registry\n    x-features:\n      - Avro Schema Support\n \
  \     - JSON Schema Support\n      - Protobuf Schema Support\n      - Schema Versioning\n      - Compatibility Levels (BACKWARD, FORWARD, FULL)\n      - Transitive Compatibility\n      - Schema References\n      - Schema Contexts\n      - Schema Normalization\n      - Soft and Hard Delete\n      - Subject-Level and Global Configuration\n      - Operating Modes (READWRITE, READONLY, IMPORT)\n      - Schema Linking via Exporters\n      - HTTP Basic, mTLS, and OAuth Auth\n    x-use-cases:\n      - Register schemas for Kafka producers and consumers\n      - Evolve schemas safely with compatibility checks\n      - Reference shared schemas across subjects\n      - Migrate schemas between clusters with Schema Linking\n      - Govern data contracts in streaming pipelines\ncommon:\n  - type: Website\n    url: https://www.confluent.io/\n  - type: Documentation\n    url: https://docs.confluent.io/platform/current/schema-registry/\n  - type: Getting Started\n    url: https://docs.confluent.io/platform/current/schema-registry/develop/using.html\n\
  \  - type: API Reference\n    url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n  - type: GitHub\n    url: https://github.com/confluentinc/schema-registry\n  - type: License\n    url: https://www.confluent.io/confluent-community-license/\n  - type: Blog\n    url: https://www.confluent.io/blog/\n  - type: Pricing\n    url: https://www.confluent.io/pricing/\n  - type: JSON-LD\n    url: json-ld/confluent-schema-registry-context.jsonld\n  - type: Spectral\n    url: rules/confluent-schema-registry-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/confluent-schema-registry-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml
tags:
- Apache Kafka
- Avro
- Compatibility
- Confluent
- Data Governance
- Data Streaming
- JSON Schema
- Open Source
- Protobuf
- REST
- Schema Evolution
- Schema Registry
url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml
use_cases: []
---
