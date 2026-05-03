---
api_count: 1
api_specs:
- filename: trpc-openapi.yml
  format: yaml
  label: tRPC HTTP Protocol
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/openapi/trpc-openapi.yml
apis:
- description: 'The tRPC HTTP API protocol surface. tRPC servers expose procedures via HTTP GET (queries) and HTTP POST (mutations). Clients use httpBatchLink to batch concurrent calls into single requests. Input is '
  name: tRPC HTTP Protocol
  slug: http-api
capabilities:
- description: Workflow capability for integrating with tRPC-based backends. tRPC enables end-to-end typesafe APIs for TypeScript applications using HTTP as the transport. This capability supports calling tRPC query
  name: tRPC Typesafe API Integration
  slug: typesafe-api-integration
common:
- title: ''
  type: Website
  url: https://trpc.io/
- title: ''
  type: Documentation
  url: https://trpc.io/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/trpc
- title: ''
  type: GitHubRepository
  url: https://github.com/trpc/trpc
- title: ''
  type: NPM
  url: https://www.npmjs.com/package/@trpc/server
- title: ''
  type: Discord
  url: https://trpc.io/discord
- title: ''
  type: Twitter
  url: https://twitter.com/alexdotjs
created: '2026-03-27'
description: tRPC is a TypeScript framework for building end-to-end typesafe APIs without code generation or schemas. It leverages TypeScript's type inference to provide full static typesafety and autocompletion between client and server, with zero runtime dependencies. tRPC v11 supports queries, mutations, and subscriptions via HTTP GET/POST and WebSocket adapters for Express, Fastify, Next.js, AWS Lambda, and edge runtimes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Trpc Context
  property_count: 0
  slug: trpc-context
layout: provider
modified: '2026-05-03'
name: tRPC
rules:
- name: tRPC API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 3
    info: 0
    warn: 2
  slug: trpc-rules
skills: []
slug: trpc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trpc\nname: tRPC\ndescription: >-\n  tRPC is a TypeScript framework for building end-to-end typesafe APIs without\n  code generation or schemas. It leverages TypeScript's type inference to provide\n  full static typesafety and autocompletion between client and server, with zero\n  runtime dependencies. tRPC v11 supports queries, mutations, and subscriptions\n  via HTTP GET/POST and WebSocket adapters for Express, Fastify, Next.js, AWS\n  Lambda, and edge runtimes.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Composition\n  - API Framework\n  - BFF\n  - End-to-End Type Safety\n  - RPC\n  - TypeScript\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trpc:http-api\n    name: tRPC HTTP Protocol\n    description: >-\n      The tRPC HTTP API protocol surface. tRPC servers expose\
  \ procedures via\n      HTTP GET (queries) and HTTP POST (mutations). Clients use httpBatchLink\n      to batch concurrent calls into single requests. Input is passed via\n      JSON-encoded query parameters (GET) or request bodies (POST).\n      Authentication uses Bearer tokens for protected procedures.\n    humanURL: https://trpc.io/docs/\n    baseURL: https://your-server.example.com/api/trpc\n    tags:\n      - API Framework\n      - HTTP\n      - RPC\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://trpc.io/docs\n      - type: Getting Started\n        url: https://trpc.io/docs/quickstart\n      - type: GitHubRepository\n        url: https://github.com/trpc/trpc\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/openapi/trpc-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/rules/trpc-rules.yml\n      - type: NaftikoCapabilities\n\
  \        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/capabilities/typesafe-api-integration.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-schema/trpc-procedure-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-schema/trpc-error-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-ld/trpc-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/vocabulary/trpc-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://trpc.io/\n  - type: Documentation\n    url: https://trpc.io/docs\n  - type: GitHub Organization\n    url: https://github.com/trpc\n  - type: GitHubRepository\n    url: https://github.com/trpc/trpc\n  - type: NPM\n    url: https://www.npmjs.com/package/@trpc/server\n\
  \  - type: Discord\n    url: https://trpc.io/discord\n  - type: Twitter\n    url: https://twitter.com/alexdotjs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml
tags:
- API Composition
- API Framework
- BFF
- End-to-End Type Safety
- RPC
- TypeScript
url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/apis.yml
use_cases: []
---
