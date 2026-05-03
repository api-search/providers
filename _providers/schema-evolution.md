---
api_count: 3
apis:
- description: The Confluent Schema Registry provides a serving layer for your metadata. It provides a RESTful interface for storing and retrieving your Avro, JSON Schema, and Protobuf schemas. It stores a versioned
  name: Confluent Schema Registry API
  slug: ''
- description: 'AWS Glue Schema Registry is a feature that enables you to centrally discover, control, and evolve data stream schemas. The AWS Glue Schema Registry API supports creating, deleting, listing, updating, '
  name: AWS Glue Schema Registry API
  slug: ''
- description: Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables you to add, update, and remove artifacts from the registry using a REST API interface. It support
  name: Apicurio Schema Registry API
  slug: ''
common:
- title: ''
  type: Website
  url: https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html
- title: ''
  type: JSONSchema
  url: json-schema/schema-evolution-change-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/schema-evolution-compatibility-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/schema-evolution-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/schema-evolution-vocabulary.yml
created: '2026-05-02'
description: Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers. Effective schema evolution is critical for maintaining API contracts and enabling independent deployment of distributed system components.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Schema Evolution Context
  property_count: 17
  slug: schema-evolution-context
layout: provider
modified: '2026-05-02'
name: Schema Evolution
skills: []
slug: schema-evolution
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Schema Evolution\ndescription: Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers. Effective schema evolution is critical for maintaining API contracts and enabling independent deployment of distributed system components.\nurl: https://github.com/api-evangelist/schema-evolution\nx-type: topic\ntags:\n- Schema Evolution\n- Backward Compatibility\n- Forward Compatibility\n- API Versioning\n- Breaking Changes\n- Schema Registry\n- Data Migration\n- Kafka\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n- name: Confluent Schema Registry API\n  description: The Confluent Schema Registry provides a serving layer for your metadata. It\
  \ provides a RESTful interface for storing and retrieving your Avro, JSON Schema, and Protobuf schemas. It stores a versioned history of all schemas based on a specified subject name strategy, provides multiple compatibility settings and allows evolution of schemas according to the configured compatibility setting. It is used by Kafka producers and consumers to enforce schema compatibility when reading and writing Kafka messages.\n  humanURL: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n  baseURL: https://your-schema-registry-host/\n  tags:\n  - Schema Registry\n  - Confluent\n  - Kafka\n  - Avro\n  - Compatibility\n  properties:\n  - type: Documentation\n    url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n  - type: Reference\n    url: https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html\n\n- name: AWS Glue Schema Registry API\n  description: AWS Glue Schema Registry is a feature\
  \ that enables you to centrally discover, control, and evolve data stream schemas. The AWS Glue Schema Registry API supports creating, deleting, listing, updating, and fetching schemas, and it supports compatibility checking for Avro and JSON Schema formats.\n  humanURL: https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html\n  baseURL: https://glue.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - Schema Registry\n  - Cloud\n  - Avro\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html\n\n- name: Apicurio Schema Registry API\n  description: Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables you to add, update, and remove artifacts from the registry using a REST API interface. It supports Apache Avro, JSON Schema, Protobuf, GraphQL SDL, and more, with configurable compatibility rules including backward, forward, and full compatibility.\n  humanURL: https://www.apicur.io/registry/\n\
  \  baseURL: https://registry.example.com/apis/registry/v2\n  tags:\n  - Schema Registry\n  - Open Source\n  - Avro\n  - Compatibility\n  properties:\n  - type: Documentation\n    url: https://www.apicur.io/registry/\n  - type: GitHub Repository\n    url: https://github.com/Apicurio/apicurio-registry\n\ncommon:\n- type: Website\n  url: https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html\n- type: JSONSchema\n  url: json-schema/schema-evolution-change-schema.json\n- type: JSONStructure\n  url: json-structure/schema-evolution-compatibility-structure.json\n- type: JSONLDContext\n  url: json-ld/schema-evolution-context.jsonld\n- type: Vocabulary\n  url: vocabulary/schema-evolution-vocabulary.yml\nmaintainers:\n- FN: API Evangelist\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schema-evolution/refs/heads/main/apis.yml
tags:
- Schema Evolution
- Backward Compatibility
- Forward Compatibility
- API Versioning
- Breaking Changes
- Schema Registry
- Data Migration
- Kafka
url: https://github.com/api-evangelist/schema-evolution
use_cases: []
---
