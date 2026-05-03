---
api_count: 2
apis:
- description: The Relay Compiler is Meta's ahead-of-time GraphQL compiler that generates optimized runtime artifacts and type-safe code for Relay applications. It processes GraphQL fragments in JavaScript/TypeScrip
  name: Relay Compiler
  slug: relay-compiler
- description: The Relay Runtime provides the client-side execution environment for Relay applications. It includes the normalized in-memory store, network layer, and React hooks including usePreloadedQuery, useFrag
  name: Relay Runtime
  slug: relay-runtime
common:
- title: ''
  type: Website
  url: https://relay.dev
- title: ''
  type: Documentation
  url: https://relay.dev/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/facebook/relay
- title: ''
  type: npm Package
  url: https://www.npmjs.com/package/relay-compiler
- title: ''
  type: Blog
  url: https://relay.dev/blog/
- title: ''
  type: Changelog
  url: https://github.com/facebook/relay/releases
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/json-ld/relay-compiler-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/vocabulary/relay-compiler-vocabulary.yml
created: '2026-03-25'
description: Relay is Meta's open-source JavaScript framework and ahead-of-time GraphQL compiler for building data-driven React applications. The Relay Compiler scans JavaScript code for GraphQL fragments, aggregates and optimizes data requirements for entire apps, pre-computes queries at build time for efficient runtime performance, and generates TypeScript/Flow types for React components. It supports pagination, mutations, subscriptions, and deferred data streaming via GraphQL directives.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Relay Compiler Context
  property_count: 20
  slug: relay-compiler-context
layout: provider
modified: '2026-05-02'
name: Relay Compiler
skills: []
slug: relay-compiler
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: relay-compiler\nname: Relay Compiler\ndescription: >-\n  Relay is Meta's open-source JavaScript framework and ahead-of-time GraphQL compiler\n  for building data-driven React applications. The Relay Compiler scans JavaScript\n  code for GraphQL fragments, aggregates and optimizes data requirements for entire\n  apps, pre-computes queries at build time for efficient runtime performance, and\n  generates TypeScript/Flow types for React components. It supports pagination,\n  mutations, subscriptions, and deferred data streaming via GraphQL directives.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code Generation\n  - GraphQL\n  - React\n  - Meta\n  - Open Source\n  - TypeScript\n  - Build Tools\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: relay-compiler:relay-compiler\n\
  \    name: Relay Compiler\n    description: >-\n      The Relay Compiler is Meta's ahead-of-time GraphQL compiler that generates\n      optimized runtime artifacts and type-safe code for Relay applications. It\n      processes GraphQL fragments in JavaScript/TypeScript source code, aggregates\n      data requirements, optimizes queries, and generates TypeScript or Flow types.\n      The compiler enforces GraphQL best practices including connection patterns,\n      pagination fragments, and data masking.\n    humanURL: https://relay.dev\n    tags:\n      - Compiler\n      - GraphQL\n      - Code Generation\n      - Build Tool\n      - TypeScript\n      - Flow\n    properties:\n      - type: Documentation\n        url: https://relay.dev/docs/\n      - type: Getting Started\n        url: https://relay.dev/docs/getting-started/\n      - type: API Reference\n        url: https://relay.dev/docs/api-reference/graphql-and-directives/\n      - type: GitHub Repository\n        url: https://github.com/facebook/relay\n\
  \      - type: Releases\n        url: https://github.com/facebook/relay/releases\n\n  - aid: relay-compiler:relay-runtime\n    name: Relay Runtime\n    description: >-\n      The Relay Runtime provides the client-side execution environment for Relay\n      applications. It includes the normalized in-memory store, network layer,\n      and React hooks including usePreloadedQuery, useFragment, usePaginationFragment,\n      useRefetchableFragment, useMutation, and useSubscription for declarative\n      data-fetching in React components.\n    humanURL: https://relay.dev/docs/api-reference/\n    tags:\n      - Runtime\n      - React Hooks\n      - State Management\n      - GraphQL Client\n      - Data Fetching\n    properties:\n      - type: Documentation\n        url: https://relay.dev/docs/api-reference/\n      - type: GitHub Repository\n        url: https://github.com/facebook/relay\n\ncommon:\n  - type: Website\n    url: https://relay.dev\n  - type: Documentation\n    url: https://relay.dev/docs/\n\
  \  - type: GitHub Organization\n    url: https://github.com/facebook/relay\n  - type: npm Package\n    url: https://www.npmjs.com/package/relay-compiler\n  - type: Blog\n    url: https://relay.dev/blog/\n  - type: Changelog\n    url: https://github.com/facebook/relay/releases\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/json-ld/relay-compiler-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/vocabulary/relay-compiler-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/apis.yml
tags:
- Code Generation
- GraphQL
- React
- Meta
- Open Source
- TypeScript
- Build Tools
url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/apis.yml
use_cases: []
---
