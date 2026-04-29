---
api_count: 4
apis:
- description: 'The Dagger Engine exposes a unified, introspectable GraphQL type system at a per-session endpoint. The schema includes Container, Directory, File, Secret, CacheVolume, and other first-class types and '
  name: Dagger Engine GraphQL API
  slug: graphql
- description: Native SDKs for Go, Python, TypeScript, PHP, Java, .NET, Elixir, and Rust that generate strongly typed clients against the Dagger Engine's GraphQL schema, allowing pipelines to be written as regular c
  name: Dagger SDKs
  slug: sdks
- description: Daggerverse is the free, public index of Dagger Modules. Developers search for, browse, and consume reusable Modules contributed by the Dagger community.
  name: Daggerverse Module Index
  slug: daggerverse
- description: Dagger Cloud is the hosted control plane providing pipeline traces, checks, module observability, and team collaboration. It integrates with the local Dagger Engine for seamless trace uploads.
  name: Dagger Cloud
  slug: cloud
capabilities: []
common:
- title: ''
  type: Website
  url: https://dagger.io/
- title: ''
  type: Documentation
  url: https://docs.dagger.io/
- title: ''
  type: GettingStarted
  url: https://docs.dagger.io/quickstart
- title: ''
  type: Reference
  url: https://docs.dagger.io/reference/
- title: ''
  type: GitHubOrganization
  url: https://github.com/dagger
- title: ''
  type: GitHubRepository
  url: https://github.com/dagger/dagger
- title: ''
  type: Daggerverse
  url: https://daggerverse.dev/
- title: ''
  type: Blog
  url: https://dagger.io/blog
- title: ''
  type: Pricing
  url: https://dagger.io/pricing
- title: ''
  type: SignUp
  url: https://dagger.cloud/signup
- title: ''
  type: Discord
  url: https://discord.gg/dagger-io
- title: ''
  type: YouTube
  url: https://www.youtube.com/@dagger-io
- title: ''
  type: Twitter
  url: https://twitter.com/dagger_io
- title: ''
  type: License
  url: https://github.com/dagger/dagger/blob/main/LICENSE
- title: ''
  type: JSON-LD
  url: json-ld/dagger-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dagger-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/dagger-graphql-capabilities.yml
created: '2026-03-26'
description: Dagger is an open-source programmable CI/CD engine that runs pipelines in containers using a unified, introspectable GraphQL API. Pipelines are written as code in the developer's preferred language (Go, Python, TypeScript, PHP, Java, .NET, Elixir, or Rust) using Dagger SDKs and packaged as Dagger Modules that can be published to the Daggerverse module index. The Dagger Engine exposes Container, Directory, File, Secret, and CacheVolume as first-class GraphQL types backed by a content-addressed store, enabling deterministic builds and aggressive caching. Dagger Cloud provides the hosted control plane for pipeline traces, checks, and module observability. Dagger does not expose a public REST API; clients connect to a per-session Dagger Engine GraphQL endpoint and the optional Dagger Cloud Web UI.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Dagger Context
  property_count: 0
  slug: dagger-context
layout: provider
modified: '2026-04-28'
name: Dagger
skills: []
slug: dagger
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dagger\nname: Dagger\nx-type: opensource\ndescription: >-\n  Dagger is an open-source programmable CI/CD engine that runs pipelines\n  in containers using a unified, introspectable GraphQL API. Pipelines\n  are written as code in the developer's preferred language (Go, Python,\n  TypeScript, PHP, Java, .NET, Elixir, or Rust) using Dagger SDKs and\n  packaged as Dagger Modules that can be published to the Daggerverse\n  module index. The Dagger Engine exposes Container, Directory, File,\n  Secret, and CacheVolume as first-class GraphQL types backed by a\n  content-addressed store, enabling deterministic builds and aggressive\n  caching. Dagger Cloud provides the hosted control plane for\n  pipeline traces, checks, and module observability. Dagger does not\n  expose a public REST API; clients connect to a per-session Dagger\n  Engine GraphQL endpoint and the optional Dagger Cloud Web UI.\nurl: https://raw.githubusercontent.com/api-evangelist/dagger/refs/heads/main/apis.yml\n\
  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Open Source\nposition: Consumer\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Build Automation\n  - BuildKit\n  - CI/CD\n  - Containers\n  - DAG\n  - Daggerverse\n  - DevOps\n  - GraphQL\n  - Modules\n  - OCI\n  - Open Source\n  - Pipelines\n  - Programmable Pipelines\n  - SDKs\napis:\n  - aid: dagger:graphql\n    name: Dagger Engine GraphQL API\n    description: >-\n      The Dagger Engine exposes a unified, introspectable GraphQL type\n      system at a per-session endpoint. The schema includes Container,\n      Directory, File, Secret, CacheVolume, and other first-class types\n      and is dynamically extended at runtime by loaded Dagger Modules.\n      All Dagger SDKs (Go, Python, TypeScript, PHP, Java, .NET, Elixir,\n      Rust) are generated against this schema. There is no\n      publicly-hosted REST endpoint.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.dagger.io/api/\n    tags:\n      - GraphQL\n      - Introspection\n      - Modules\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.dagger.io/api/\n      - type: APIReference\n        url: https://docs.dagger.io/reference/\n      - type: APIInternals\n        url: https://docs.dagger.io/api/internals/\n      - type: Blog\n        url: https://dagger.io/blog/graphql\n      - type: Capabilities\n        url: capabilities/dagger-graphql-capabilities.yml\n  - aid: dagger:sdks\n    name: Dagger SDKs\n    description: >-\n      Native SDKs for Go, Python, TypeScript, PHP, Java, .NET, Elixir,\n      and Rust that generate strongly typed clients against the Dagger\n      Engine's GraphQL schema, allowing pipelines to be written as\n      regular code in the developer's preferred language.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.dagger.io/sdk/\n    tags:\n\
  \      - .NET\n      - Elixir\n      - Go\n      - Java\n      - PHP\n      - Python\n      - Rust\n      - SDKs\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://docs.dagger.io/sdk/\n      - type: GitHubRepository\n        url: https://github.com/dagger/dagger\n  - aid: dagger:daggerverse\n    name: Daggerverse Module Index\n    description: >-\n      Daggerverse is the free, public index of Dagger Modules.\n      Developers search for, browse, and consume reusable Modules\n      contributed by the Dagger community.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://daggerverse.dev/\n    tags:\n      - Daggerverse\n      - Modules\n      - Registry\n    properties:\n      - type: Website\n        url: https://daggerverse.dev/\n      - type: Quickstart\n        url: https://docs.dagger.io/ci/quickstart/simplify/\n  - aid: dagger:cloud\n    name: Dagger Cloud\n    description: >-\n      Dagger\
  \ Cloud is the hosted control plane providing pipeline\n      traces, checks, module observability, and team collaboration.\n      It integrates with the local Dagger Engine for seamless trace\n      uploads.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://dagger.io/cloud\n    tags:\n      - Cloud\n      - Observability\n      - Telemetry\n      - Traces\n    properties:\n      - type: Website\n        url: https://dagger.io/cloud\n      - type: SignUp\n        url: https://dagger.cloud/signup\ncommon:\n  - type: Website\n    url: https://dagger.io/\n  - type: Documentation\n    url: https://docs.dagger.io/\n  - type: GettingStarted\n    url: https://docs.dagger.io/quickstart\n  - type: Reference\n    url: https://docs.dagger.io/reference/\n  - type: GitHubOrganization\n    url: https://github.com/dagger\n  - type: GitHubRepository\n    url: https://github.com/dagger/dagger\n  - type: Daggerverse\n    url: https://daggerverse.dev/\n\
  \  - type: Blog\n    url: https://dagger.io/blog\n  - type: Pricing\n    url: https://dagger.io/pricing\n  - type: SignUp\n    url: https://dagger.cloud/signup\n  - type: Discord\n    url: https://discord.gg/dagger-io\n  - type: YouTube\n    url: https://www.youtube.com/@dagger-io\n  - type: Twitter\n    url: https://twitter.com/dagger_io\n  - type: License\n    url: https://github.com/dagger/dagger/blob/main/LICENSE\n  - type: JSON-LD\n    url: json-ld/dagger-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dagger-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/dagger-graphql-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dagger/refs/heads/main/apis.yml
tags:
- Build Automation
- BuildKit
- CI/CD
- Containers
- DAG
- Daggerverse
- DevOps
- GraphQL
- Modules
- OCI
- Open Source
- Pipelines
- Programmable Pipelines
- SDKs
url: https://raw.githubusercontent.com/api-evangelist/dagger/refs/heads/main/apis.yml
use_cases: []
---
