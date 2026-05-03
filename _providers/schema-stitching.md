---
api_count: 4
apis:
- description: Schema Stitching is a GraphQL technique for combining multiple GraphQL schemas into a single unified API gateway. The @graphql-tools/stitch package creates a combined proxy layer that delegates reques
  name: Schema Stitching
  slug: schema-stitching
- description: GraphQL Mesh allows stitching together multiple data sources including REST APIs, databases, and other GraphQL APIs into a single unified GraphQL schema. It applies schema stitching techniques to tran
  name: GraphQL Mesh
  slug: graphql-mesh
- description: Hive Gateway is a federated GraphQL routing engine from The Guild that supports both Apollo Federation and Schema Stitching approaches to compose distributed GraphQL services.
  name: Hive Gateway
  slug: hive-gateway
- description: Apollo Federation is an alternative to schema stitching for composing distributed GraphQL services. It uses a supergraph approach with subgraph schemas annotated with federation directives, managed th
  name: Apollo Federation
  slug: apollo-federation
common:
- title: ''
  type: Website
  url: https://the-guild.dev/graphql/stitching
- title: ''
  type: Documentation
  url: https://the-guild.dev/graphql/stitching/docs
- title: ''
  type: Handbook
  url: https://the-guild.dev/graphql/stitching/handbook
- title: ''
  type: GitHub Organization
  url: https://github.com/ardatan
- title: ''
  type: Blog
  url: https://the-guild.dev/blog
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/vocabulary/schema-stitching-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/examples/schema-stitching-basic-gateway-example.json
created: '2026-03-27'
description: Schema Stitching is a GraphQL technique for combining multiple GraphQL schemas into a single unified API gateway. It enables developers to compose distributed GraphQL services, integrate third-party APIs, and build federated data layers by merging types, queries, and mutations from multiple subgraphs into one executable schema. The primary implementation is provided by The Guild's graphql-tools library, with support for type merging, stitching directives, schema delegation, and automated query planning.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Schema Stitching Context
  property_count: 4
  slug: schema-stitching-context
layout: provider
modified: '2026-05-02'
name: Schema Stitching
skills: []
slug: schema-stitching
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: schema-stitching\nname: Schema Stitching\ndescription: >-\n  Schema Stitching is a GraphQL technique for combining multiple GraphQL\n  schemas into a single unified API gateway. It enables developers to compose\n  distributed GraphQL services, integrate third-party APIs, and build federated\n  data layers by merging types, queries, and mutations from multiple subgraphs\n  into one executable schema. The primary implementation is provided by The\n  Guild's graphql-tools library, with support for type merging, stitching\n  directives, schema delegation, and automated query planning.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Composition\n  - API Gateway\n  - Federation\n  - GraphQL\n  - Microservices\n  - Schema Stitching\n  - Type Merging\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: schema-stitching:schema-stitching\n    name: Schema Stitching\n    description: >-\n      Schema Stitching is a GraphQL technique for combining multiple GraphQL\n      schemas into a single unified API gateway. The @graphql-tools/stitch\n      package creates a combined proxy layer that delegates requests through to\n      underlying service APIs, supporting type merging, stitching directives,\n      and automated query planning comparable to Apollo Federation.\n    humanURL: https://the-guild.dev/graphql/stitching\n    tags:\n      - API Composition\n      - GraphQL\n      - Schema Stitching\n      - Type Merging\n    properties:\n      - type: Documentation\n        url: https://the-guild.dev/graphql/stitching/docs\n      - type: Getting Started\n        url: https://the-guild.dev/graphql/stitching/docs/getting-started\n      - type: Handbook\n        url: https://the-guild.dev/graphql/stitching/handbook\n      - type: GitHub Repository\n        url: https://github.com/ardatan/graphql-tools\n\
  \      - type: npm Package\n        url: https://www.npmjs.com/package/@graphql-tools/stitch\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/json-schema/schema-stitching-config-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/json-structure/schema-stitching-config-structure.json\n      - type: JSONLd\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/json-ld/schema-stitching-context.jsonld\n  - aid: schema-stitching:graphql-mesh\n    name: GraphQL Mesh\n    description: >-\n      GraphQL Mesh allows stitching together multiple data sources including\n      REST APIs, databases, and other GraphQL APIs into a single unified GraphQL\n      schema. It applies schema stitching techniques to transform and federate\n      heterogeneous data sources.\n\
  \    humanURL: https://the-guild.dev/graphql/mesh\n    tags:\n      - API Gateway\n      - GraphQL\n      - Schema Stitching\n    properties:\n      - type: Documentation\n        url: https://the-guild.dev/graphql/mesh/docs\n      - type: GitHub Repository\n        url: https://github.com/ardatan/graphql-mesh\n  - aid: schema-stitching:hive-gateway\n    name: Hive Gateway\n    description: >-\n      Hive Gateway is a federated GraphQL routing engine from The Guild that\n      supports both Apollo Federation and Schema Stitching approaches to compose\n      distributed GraphQL services.\n    humanURL: https://the-guild.dev/graphql/hive/docs/gateway\n    tags:\n      - API Gateway\n      - Federation\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://the-guild.dev/graphql/hive/docs/gateway\n      - type: GitHub Repository\n        url: https://github.com/the-guild-org/gateway\n  - aid: schema-stitching:apollo-federation\n    name: Apollo Federation\n  \
  \  description: >-\n      Apollo Federation is an alternative to schema stitching for composing\n      distributed GraphQL services. It uses a supergraph approach with subgraph\n      schemas annotated with federation directives, managed through Apollo\n      Studio or self-hosted routers.\n    humanURL: https://www.apollographql.com/docs/federation/\n    tags:\n      - API Gateway\n      - Apollo\n      - Federation\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://www.apollographql.com/docs/federation/\n      - type: GitHub Repository\n        url: https://github.com/apollographql/federation\ncommon:\n  - type: Website\n    url: https://the-guild.dev/graphql/stitching\n  - type: Documentation\n    url: https://the-guild.dev/graphql/stitching/docs\n  - type: Handbook\n    url: https://the-guild.dev/graphql/stitching/handbook\n  - type: GitHub Organization\n    url: https://github.com/ardatan\n  - type: Blog\n    url: https://the-guild.dev/blog\n  - type:\
  \ Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/vocabulary/schema-stitching-vocabulary.yml\n  - type: Examples\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/examples/schema-stitching-basic-gateway-example.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/apis.yml
tags:
- API Composition
- API Gateway
- Federation
- GraphQL
- Microservices
- Schema Stitching
- Type Merging
url: https://raw.githubusercontent.com/api-evangelist/schema-stitching/refs/heads/main/apis.yml
use_cases: []
---
