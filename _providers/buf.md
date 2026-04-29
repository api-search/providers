---
api_count: 3
apis:
- description: 'The Buf Schema Registry (BSR) is a centralized repository for managing, distributing, and documenting Protobuf schemas. It provides dependency management, generated SDKs in multiple languages, remote '
  name: Buf Schema Registry (BSR)
  slug: buf-schema-registry
- description: The Buf CLI is a local Protobuf development toolchain providing linting, breaking change detection, code generation, formatting, dependency management, and schema push/pull to the Buf Schema Registry.
  name: Buf CLI
  slug: buf-cli
- description: Bufstream is a Kafka-compatible streaming platform built on Protocol Buffers. It provides schema enforcement, Iceberg integration, and administrative tooling for managing Kafka-compatible streaming wo
  name: Bufstream
  slug: bufstream
common:
- title: ''
  type: Website
  url: https://buf.build
- title: ''
  type: Documentation
  url: https://buf.build/docs
- title: ''
  type: GitHubOrganization
  url: https://github.com/bufbuild
- title: ''
  type: GitHubRepository
  url: https://github.com/bufbuild/buf
- title: ''
  type: Blog
  url: https://buf.build/blog
- title: ''
  type: Pricing
  url: https://buf.build/pricing
- title: ''
  type: SignUp
  url: https://buf.build/signup
- title: ''
  type: Login
  url: https://buf.build/login
- title: ''
  type: Contact
  url: https://buf.build/contact
- title: ''
  type: TermsOfService
  url: https://buf.build/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://buf.build/legal/privacy-policy
- title: ''
  type: Community
  url: https://buf.build/b/slack
- title: ''
  type: SchemaRegistry
  url: https://buf.build/registry
created: '2026-03-25'
description: Buf is a modern developer platform for Protocol Buffers and gRPC, providing a CLI toolchain, schema registry, and streaming infrastructure. It replaces traditional protoc-based workflows with linting, breaking change detection, code generation, remote plugins, and the Buf Schema Registry (BSR) for centralized schema distribution. Buf also offers Bufstream, a Kafka-compatible streaming platform built on Protobuf. Used by enterprises including EA, Intel, IBM, OpenAI, and Okta.
features:
- features:
  - Style Guide Enforcement
  - Default and Custom Rules
  - CI/CD Compatible
  - Per-File Ignore Rules
  name: buf lint
  url: https://buf.build/docs/lint/
- features:
  - Breaking Change Detection
  - Wire Compatibility Checks
  - Source Compatibility Checks
  - Git-Based Comparison
  name: buf breaking
  url: https://buf.build/docs/breaking/
- features:
  - Multi-Language Code Generation
  - Remote Plugin Support
  - Managed Mode
  - Template Configuration
  name: buf generate
  url: https://buf.build/docs/generate/
- features:
  - Schema Publishing
  - Dependency Resolution
  - Module Locking
  - Version Tagging
  name: buf push / buf dep
  url: https://buf.build/docs/bsr/
- features:
  - Runtime Schema Discovery
  - gRPC Server Reflection
  - Prototransform Integration
  name: Reflection API
  url: https://buf.build/docs/bsr/reflection/
- features:
  - IDE Integration
  - Inline Linting
  - Autocomplete Support
  - VS Code Compatible
  name: Language Server Protocol
  url: https://buf.build/docs/cli/
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Buf
skills: []
slug: buf
solutions: []
source_filename: apis.yml
source_yaml: "aid: buf\nname: Buf\ndescription: >-\n  Buf is a modern developer platform for Protocol Buffers and gRPC, providing\n  a CLI toolchain, schema registry, and streaming infrastructure. It replaces\n  traditional protoc-based workflows with linting, breaking change detection,\n  code generation, remote plugins, and the Buf Schema Registry (BSR) for\n  centralized schema distribution. Buf also offers Bufstream, a Kafka-compatible\n  streaming platform built on Protobuf. Used by enterprises including EA, Intel,\n  IBM, OpenAI, and Okta.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/buf/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n  - Code Generation\n  - gRPC\n  - Kafka\n  - Open Source\n  - Protocol Buffers\n  - Schema Registry\n  - SDKs\n  - Streaming\napis:\n  - aid: buf:buf-schema-registry\n    name: Buf Schema\
  \ Registry (BSR)\n    description: >-\n      The Buf Schema Registry (BSR) is a centralized repository for managing,\n      distributing, and documenting Protobuf schemas. It provides dependency\n      management, generated SDKs in multiple languages, remote plugins for code\n      generation, and a Reflection API for runtime schema discovery.\n    humanURL: https://buf.build/product/bsr\n    tags:\n      - Code Generation\n      - Protocol Buffers\n      - Schema Registry\n      - SDKs\n    properties:\n      - type: Documentation\n        url: https://buf.build/docs/bsr/\n      - type: Getting Started\n        url: https://buf.build/docs/bsr/introduction/\n      - type: Authentication\n        url: https://buf.build/docs/bsr/authentication/\n      - type: Reference\n        url: https://buf.build/docs/reference/\n  - aid: buf:buf-cli\n    name: Buf CLI\n    description: >-\n      The Buf CLI is a local Protobuf development toolchain providing linting,\n      breaking change detection,\
  \ code generation, formatting, dependency\n      management, and schema push/pull to the Buf Schema Registry. It replaces\n      protoc with a faster, more developer-friendly interface.\n    humanURL: https://buf.build/product/cli\n    tags:\n      - CLI\n      - Code Generation\n      - Linting\n      - Protocol Buffers\n    properties:\n      - type: Documentation\n        url: https://buf.build/docs/cli/\n      - type: Getting Started\n        url: https://buf.build/docs/tutorials/getting-started-with-buf-cli\n      - type: GitHubRepository\n        url: https://github.com/bufbuild/buf\n  - aid: buf:bufstream\n    name: Bufstream\n    description: >-\n      Bufstream is a Kafka-compatible streaming platform built on Protocol\n      Buffers. It provides schema enforcement, Iceberg integration, and\n      administrative tooling for managing Kafka-compatible streaming workloads\n      with Protobuf as the data format.\n    humanURL: https://buf.build/product/bufstream\n    tags:\n    \
  \  - Kafka\n      - Protocol Buffers\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://buf.build/docs/bufstream/\n      - type: Getting Started\n        url: https://buf.build/docs/bufstream/introduction/\ncommon:\n  - type: Website\n    url: https://buf.build\n  - type: Documentation\n    url: https://buf.build/docs\n  - type: GitHubOrganization\n    url: https://github.com/bufbuild\n  - type: GitHubRepository\n    url: https://github.com/bufbuild/buf\n  - type: Blog\n    url: https://buf.build/blog\n  - type: Pricing\n    url: https://buf.build/pricing\n  - type: SignUp\n    url: https://buf.build/signup\n  - type: Login\n    url: https://buf.build/login\n  - type: Contact\n    url: https://buf.build/contact\n  - type: TermsOfService\n    url: https://buf.build/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://buf.build/legal/privacy-policy\n  - type: Community\n    url: https://buf.build/b/slack\n  - type: SchemaRegistry\n    url: https://buf.build/registry\n\
  \  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Protobuf Schema Management\n        url: https://buf.build/product/bsr\n        features:\n          - Centralized Schema Registry\n          - Module Versioning\n          - Dependency Management\n          - Schema Discovery\n          - API Documentation Generation\n          - Breaking Change Prevention\n      - name: Code Generation\n        url: https://buf.build/docs/generate/\n        features:\n          - Multi-Language SDK Generation\n          - Remote Plugin Execution\n          - Go SDK Generation\n          - Python SDK Generation\n          - TypeScript/npm SDK Generation\n          - Java/Maven SDK Generation\n          - Rust/Cargo SDK Generation\n          - Swift SDK Generation\n          - .NET/NuGet SDK Generation\n      - name: API Linting and Governance\n        url: https://buf.build/docs/lint/\n        features:\n          - Protobuf Style Enforcement\n          - Breaking Change Detection\n  \
  \        - CI/CD Integration\n          - Custom Policy Rules\n          - Field Deprecation Tracking\n      - name: gRPC and ConnectRPC Development\n        url: https://connectrpc.com/\n        features:\n          - gRPC Server Support\n          - Connect Protocol\n          - Browser-Compatible RPC\n          - Mobile Client Support\n          - Protovalidate Semantic Validation\n  - name: Features\n    type: Features\n    data:\n      - name: buf lint\n        url: https://buf.build/docs/lint/\n        features:\n          - Style Guide Enforcement\n          - Default and Custom Rules\n          - CI/CD Compatible\n          - Per-File Ignore Rules\n      - name: buf breaking\n        url: https://buf.build/docs/breaking/\n        features:\n          - Breaking Change Detection\n          - Wire Compatibility Checks\n          - Source Compatibility Checks\n          - Git-Based Comparison\n      - name: buf generate\n        url: https://buf.build/docs/generate/\n        features:\n\
  \          - Multi-Language Code Generation\n          - Remote Plugin Support\n          - Managed Mode\n          - Template Configuration\n      - name: buf push / buf dep\n        url: https://buf.build/docs/bsr/\n        features:\n          - Schema Publishing\n          - Dependency Resolution\n          - Module Locking\n          - Version Tagging\n      - name: Reflection API\n        url: https://buf.build/docs/bsr/reflection/\n        features:\n          - Runtime Schema Discovery\n          - gRPC Server Reflection\n          - Prototransform Integration\n      - name: Language Server Protocol\n        url: https://buf.build/docs/cli/\n        features:\n          - IDE Integration\n          - Inline Linting\n          - Autocomplete Support\n          - VS Code Compatible\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/buf/refs/heads/main/apis.yml
tags:
- Code Generation
- gRPC
- Kafka
- Open Source
- Protocol Buffers
- Schema Registry
- SDKs
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/buf/refs/heads/main/apis.yml
use_cases:
- features:
  - Centralized Schema Registry
  - Module Versioning
  - Dependency Management
  - Schema Discovery
  - API Documentation Generation
  - Breaking Change Prevention
  name: Protobuf Schema Management
  url: https://buf.build/product/bsr
- features:
  - Multi-Language SDK Generation
  - Remote Plugin Execution
  - Go SDK Generation
  - Python SDK Generation
  - TypeScript/npm SDK Generation
  - Java/Maven SDK Generation
  - Rust/Cargo SDK Generation
  - Swift SDK Generation
  - .NET/NuGet SDK Generation
  name: Code Generation
  url: https://buf.build/docs/generate/
- features:
  - Protobuf Style Enforcement
  - Breaking Change Detection
  - CI/CD Integration
  - Custom Policy Rules
  - Field Deprecation Tracking
  name: API Linting and Governance
  url: https://buf.build/docs/lint/
- features:
  - gRPC Server Support
  - Connect Protocol
  - Browser-Compatible RPC
  - Mobile Client Support
  - Protovalidate Semantic Validation
  name: gRPC and ConnectRPC Development
  url: https://connectrpc.com/
---
