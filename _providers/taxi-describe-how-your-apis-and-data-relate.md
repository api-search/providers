---
api_count: 4
api_specs:
- filename: taxi-language-openapi.yml
  format: yaml
  label: Taxi Language
  slug: taxi-language
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/taxi-describe-how-your-apis-and-data-relate/refs/heads/main/openapi/taxi-language-openapi.yml
apis:
- description: The core Taxi schema language for defining types, models, API services, and semantic annotations. Used to describe OpenAPI, Protobuf, database schemas, and Kafka topics with rich type semantics that p
  name: Taxi Language
  slug: taxi-language
- description: TaxiQL is a declarative query language for federated data retrieval across multiple APIs and data sources. Queries specify the desired data structure using semantic types and Taxi automatically discov
  name: TaxiQL Query API
  slug: taxiql-query-api
- description: Orbital is the companion data platform for Taxi that hosts TaxiQL queries, provides a schema registry, and executes federated data integrations across APIs, databases, and streams using Taxi annotatio
  name: Orbital Platform
  slug: orbital-platform
- description: Interactive web-based editor for writing Taxi schemas and TaxiQL queries with live diagram generation and query execution preview.
  name: Taxi Playground
  slug: taxi-playground
capabilities:
- description: Workflow capability for schema-driven data integration using the Taxi language. Covers schema authoring, TaxiQL query execution, type and service discovery, and conversion of existing API specs to Tax
  name: Taxi Data Integration
  slug: data-integration
common:
- title: ''
  type: Website
  url: https://taxilang.org/
- title: ''
  type: Documentation
  url: https://docs.taxilang.org/
- title: ''
  type: GitHub Org
  url: https://github.com/taxilang
- title: ''
  type: Playground
  url: https://playground.taxilang.org
- title: ''
  type: Slack
  url: https://join.slack.com/t/taxi-lang/shared_invite
- title: ''
  type: OpenAPI
  url: openapi/taxi-language-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/taxi-schema-definition-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/taxi-schema-structure.json
- title: ''
  type: JSONLD
  url: json-ld/taxi-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/taxi-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-integration.yaml
created: '2026-01-05'
description: Taxi is an open-source language (Apache 2.0) for describing APIs, data models, and how data relates across an entire ecosystem. TaxiQL is a declarative query language that lets consumers define the data they want while Taxi handles orchestration across REST APIs, databases, Kafka topics, gRPC services, and S3 buckets. Taxi eliminates manual integration code by using semantic type annotations to automatically discover data paths and adapt to evolving API schemas.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 24
  name: Taxi Context
  property_count: 0
  slug: taxi-context
layout: provider
modified: '2026-05-03'
name: Taxi - Describe How Your APIs and Data Relate
rules:
- name: Taxi - Describe How Your APIs and Data Relate API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: taxi-spectral-rules
skills: []
slug: taxi-describe-how-your-apis-and-data-relate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: taxi-describe-how-your-apis-and-data-relate\nname: Taxi - Describe How Your APIs and Data Relate\ndescription: >-\n  Taxi is an open-source language (Apache 2.0) for describing APIs, data models, and\n  how data relates across an entire ecosystem. TaxiQL is a declarative query language\n  that lets consumers define the data they want while Taxi handles orchestration across\n  REST APIs, databases, Kafka topics, gRPC services, and S3 buckets. Taxi eliminates\n  manual integration code by using semantic type annotations to automatically discover\n  data paths and adapt to evolving API schemas.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Description\n  - Data Integration\n  - Open Source\n  - Query Language\n  - Schema\n  - Semantic\ncreated: '2026-01-05'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/taxi/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: taxi-describe-how-your-apis-and-data-relate:taxi-language\n    name: Taxi Language\n    description: >-\n      The core Taxi schema language for defining types, models, API services, and semantic\n      annotations. Used to describe OpenAPI, Protobuf, database schemas, and Kafka topics\n      with rich type semantics that power TaxiQL queries and data orchestration.\n    humanURL: https://taxilang.org/\n    tags:\n      - API Description\n      - Data Modeling\n      - Open Source\n      - Schema\n      - Semantic Types\n    properties:\n      - type: Documentation\n        url: https://docs.taxilang.org/\n      - type: GitHub\n        url: https://github.com/taxilang/taxilang\n      - type: OpenAPI\n        url: openapi/taxi-language-openapi.yml\n  - aid: taxi-describe-how-your-apis-and-data-relate:taxiql-query-api\n    name: TaxiQL Query API\n    description: >-\n      TaxiQL is a declarative query language for federated data retrieval across\
  \ multiple\n      APIs and data sources. Queries specify the desired data structure using semantic types\n      and Taxi automatically discovers the data paths, calls APIs, and assembles results.\n    humanURL: https://docs.taxilang.org/language-reference/querying-with-taxiql/\n    tags:\n      - Data Query\n      - Federated Query\n      - Open Source\n      - Query Language\n    properties:\n      - type: Documentation\n        url: https://docs.taxilang.org/language-reference/querying-with-taxiql/\n      - type: GitHub\n        url: https://github.com/taxilang/taxilang\n  - aid: taxi-describe-how-your-apis-and-data-relate:orbital-platform\n    name: Orbital Platform\n    description: >-\n      Orbital is the companion data platform for Taxi that hosts TaxiQL queries,\n      provides a schema registry, and executes federated data integrations across\n      APIs, databases, and streams using Taxi annotations.\n    humanURL: https://orbitalhq.com\n    tags:\n      - Data Platform\n   \
  \   - Federated Query\n      - Integration\n      - Schema Registry\n    properties:\n      - type: Documentation\n        url: https://orbitalhq.com\n  - aid: taxi-describe-how-your-apis-and-data-relate:taxi-playground\n    name: Taxi Playground\n    description: >-\n      Interactive web-based editor for writing Taxi schemas and TaxiQL queries with\n      live diagram generation and query execution preview.\n    humanURL: https://playground.taxilang.org\n    tags:\n      - Developer Tools\n      - Playground\n      - Schema Editor\n    properties:\n      - type: Documentation\n        url: https://playground.taxilang.org\ncommon:\n  - type: Website\n    url: https://taxilang.org/\n  - type: Documentation\n    url: https://docs.taxilang.org/\n  - type: GitHub Org\n    url: https://github.com/taxilang\n  - type: Playground\n    url: https://playground.taxilang.org\n  - type: Slack\n    url: https://join.slack.com/t/taxi-lang/shared_invite\n  - type: OpenAPI\n    url: openapi/taxi-language-openapi.yml\n\
  \  - type: JSONSchema\n    url: json-schema/taxi-schema-definition-schema.json\n  - type: JSONStructure\n    url: json-structure/taxi-schema-structure.json\n  - type: JSONLD\n    url: json-ld/taxi-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/taxi-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/data-integration.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/taxi-describe-how-your-apis-and-data-relate/refs/heads/main/apis.yml
tags:
- API Description
- Data Integration
- Open Source
- Query Language
- Schema
- Semantic
url: https://raw.githubusercontent.com/api-evangelist/taxi/refs/heads/main/apis.yml
use_cases: []
---
