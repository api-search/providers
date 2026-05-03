---
api_count: 2
api_specs:
- filename: orbital-query-api-openapi.yml
  format: yaml
  label: Orbital Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/openapi/orbital-query-api-openapi.yml
- filename: orbital-schema-management-api-openapi.yml
  format: yaml
  label: Orbital Schema Management API
  slug: schema-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/openapi/orbital-schema-management-api-openapi.yml
apis:
- description: The Orbital Query API allows developers to submit TaxiQL queries to the Orbital data gateway for integrating, transforming, and discovering data across APIs, databases, event streams, and other data s
  name: Orbital Query API
  slug: query-api
- description: The Orbital Schema Management API provides endpoints for managing schemas, types, and data source definitions within an Orbital workspace. It allows developers to register, update, and remove Taxi sch
  name: Orbital Schema Management API
  slug: schema-management-api
common:
- title: ''
  type: Website
  url: https://orbitalhq.com/
- title: ''
  type: Documentation
  url: https://orbitalhq.com/docs
- title: ''
  type: ChangeLog
  url: https://orbitalhq.com/changelog
- title: ''
  type: Pricing
  url: https://orbitalhq.com/pricing
- title: ''
  type: Blog
  url: https://orbitalhq.com/blog
created: '2026-01-05'
description: Orbital is a data gateway and integration platform that connects APIs, databases, event streams, and other data sources without requiring glue code or manual integration maintenance. The platform delivers self-repairing integrations through instant, on-the-fly orchestration that automatically adapts as APIs and schemas evolve, eliminating the need to write resolvers, generate API clients, or maintain YAML mapping files.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Orbital Context
  property_count: 0
  slug: orbital-context
layout: provider
modified: '2026-04-28'
name: Orbital
skills: []
slug: orbital
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: orbital\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml\napis:\n  - aid: orbital:query-api\n    name: Orbital Query API\n    tags:\n      - Data\n      - Gateways\n      - Integration\n      - Queries\n    humanURL: https://orbitalhq.com/docs/querying/writing-queries\n    properties:\n      - url: https://orbitalhq.com/docs/querying/writing-queries\n        type: Documentation\n      - url: openapi/orbital-query-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/query.json\n        type: JSONSchema\n      - url: json-schema/connection.json\n        type: JSONSchema\n      - url: json-schema/cache.json\n        type: JSONSchema\n      - url: json-ld/orbital-context.jsonld\n        type: JSONLD\n    description: >-\n      The Orbital Query API allows developers to submit TaxiQL queries to the\n      Orbital data gateway for integrating, transforming, and discovering data\n      across APIs, databases, event streams,\
  \ and other data sources. Queries are\n      submitted to the /api/taxiql endpoint and results can be returned as JSON\n      or streamed via Server-Sent Events. The API also provides endpoints for\n      managing connections and caches.\n  - aid: orbital:schema-management-api\n    name: Orbital Schema Management API\n    tags:\n      - Data\n      - Gateways\n      - Schemas\n      - Types\n    humanURL: https://orbitalhq.com/docs/describing-data-sources/open-api\n    properties:\n      - url: https://orbitalhq.com/docs/describing-data-sources/open-api\n        type: Documentation\n      - url: openapi/orbital-schema-management-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/schema.json\n        type: JSONSchema\n      - url: json-schema/service.json\n        type: JSONSchema\n      - url: json-schema/type.json\n        type: JSONSchema\n      - url: json-ld/orbital-context.jsonld\n        type: JSONLD\n    description: >-\n      The Orbital Schema Management API provides\
  \ endpoints for managing schemas,\n      types, and data source definitions within an Orbital workspace. It allows\n      developers to register, update, and remove Taxi schemas and type\n      definitions that Orbital uses to understand the semantic relationships\n      between data across connected services. Schemas can originate from OpenAPI\n      specs, Protobuf definitions, database schemas, or Taxi projects.\nname: Orbital\ntags:\n  - Data\n  - Gateways\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-05'\nmodified: '2026-04-28'\nposition: Consuming\ndescription: >-\n  Orbital is a data gateway and integration platform that connects APIs, databases,\n  event streams, and other data sources without requiring glue code or manual integration\n  maintenance. The platform delivers self-repairing integrations through instant,\n  on-the-fly orchestration that automatically adapts as APIs and schemas\
  \ evolve, eliminating\n  the need to write resolvers, generate API clients, or maintain YAML mapping files.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Orbital - Automated integration for modern dev teams.\n    description: 'null'\n    url: https://orbitalhq.com/\n    type: Website\n  - name: Getting started - Orbital\n    description: 'null'\n    url: https://orbitalhq.com/docs\n    type: Documentation\n  - name: Changelog - Orbital\n    description: 'null'\n    url: https://orbitalhq.com/changelog\n    type: ChangeLog\n  - name: Pricing - Orbital\n    description: 'null'\n    url: https://orbitalhq.com/pricing\n    type: Pricing\n  - name: Blog - Orbital\n    description: 'null'\n    url: https://orbitalhq.com/blog\n    type: Blog\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml
tags:
- Data
- Gateways
url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml
use_cases: []
---
