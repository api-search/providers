---
api_count: 5
apis:
- description: The WasmEdge C API provides a low-level interface for embedding the WasmEdge runtime into C/C++ host applications. It exposes the full WasmEdge runtime capabilities including module instantiation, fun
  name: WasmEdge C API
  slug: wasmedge-c-api
- description: 'The WasmEdge Rust SDK enables embedding WasmEdge WebAssembly functions in Rust host applications. It provides idiomatic Rust bindings for the WasmEdge C API, supporting module loading, instantiation, '
  name: WasmEdge Rust SDK
  slug: wasmedge-rust-sdk
- description: The WasmEdge Go SDK provides Go language bindings for embedding the WasmEdge runtime in Go applications. It enables loading and executing WebAssembly modules from Go, defining host functions, and mana
  name: WasmEdge Go SDK
  slug: wasmedge-go-sdk
- description: The WasmEdge Node.js SDK allows embedding and calling WebAssembly functions from Node.js applications. It provides bindings for executing Wasm modules within the WasmEdge runtime from JavaScript, enab
  name: WasmEdge Node.js SDK
  slug: wasmedge-nodejs-sdk
- description: WasmEdge's plugin system enables extending the runtime with custom host function packages. Plugins can be developed in Rust or C/C++ and loaded at runtime, providing capabilities like TensorFlow AI in
  name: WasmEdge Plugin System
  slug: wasmedge-plugin-system
common:
- title: ''
  type: Website
  url: https://wasmedge.org/
- title: ''
  type: Documentation
  url: https://wasmedge.org/docs/
- title: ''
  type: Getting Started
  url: https://wasmedge.org/docs/start/getting-started/
- title: ''
  type: GitHubOrganization
  url: https://github.com/WasmEdge
- title: ''
  type: GitHubRepository
  url: https://github.com/WasmEdge/WasmEdge
- title: ''
  type: Blog
  url: https://wasmedge.org/blog/
- title: ''
  type: Slack
  url: https://wasmedge.slack.com/
- title: ''
  type: Discord
  url: https://discord.gg/U4B5sFTkFc
- title: ''
  type: Vocabulary
  url: vocabulary/wasmedge-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/wasmedge-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/wasmedge-config-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/wasmedge-config-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/wasmedge-vocabulary.yml
created: '2026-03-26'
description: WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. It powers serverless apps, embedded functions, microservices, smart contracts, and IoT devices. WasmEdge is a CNCF sandbox project providing an LLVM-based AoT compiler for maximum performance, and supporting WASI extensions for non-blocking networking, database access, and AI inference via TensorFlow, PyTorch, and OpenVINO.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Wasmedge Context
  property_count: 14
  slug: wasmedge-context
layout: provider
modified: '2026-05-03'
name: WasmEdge
skills: []
slug: wasmedge
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wasmedge\nname: WasmEdge\ndescription: >-\n  WasmEdge is a lightweight, high-performance, and extensible WebAssembly\n  runtime for cloud native, edge, and decentralized applications. It powers\n  serverless apps, embedded functions, microservices, smart contracts, and IoT\n  devices. WasmEdge is a CNCF sandbox project providing an LLVM-based AoT\n  compiler for maximum performance, and supporting WASI extensions for\n  non-blocking networking, database access, and AI inference via TensorFlow,\n  PyTorch, and OpenVINO.\nurl: https://wasmedge.org\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - CNCF\n  - Edge Computing\n  - High Performance\n  - Runtime\n  - Serverless\n  - Wasm\n  - WebAssembly\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: wasmedge:wasmedge-c-api\n    name: WasmEdge C API\n    description: >-\n      The WasmEdge C API provides a\
  \ low-level interface for embedding the\n      WasmEdge runtime into C/C++ host applications. It exposes the full\n      WasmEdge runtime capabilities including module instantiation, function\n      invocation, memory access, and plugin management.\n    humanURL: https://wasmedge.org/docs/embed/c/intro/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmedge.org/docs/embed/c/intro/\n      - type: GitHubRepository\n        url: https://github.com/WasmEdge/WasmEdge\n    tags:\n      - C API\n      - Embedding\n      - Low Level\n  - aid: wasmedge:wasmedge-rust-sdk\n    name: WasmEdge Rust SDK\n    description: >-\n      The WasmEdge Rust SDK enables embedding WasmEdge WebAssembly functions\n      in Rust host applications. It provides idiomatic Rust bindings for the\n      WasmEdge C API, supporting module loading, instantiation, function calls,\n      host function definitions, and\
  \ plugin integration.\n    humanURL: https://wasmedge.org/docs/embed/rust/intro/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmedge.org/docs/embed/rust/intro/\n      - type: GitHubRepository\n        url: https://github.com/WasmEdge/wasmedge-rust-sdk\n    tags:\n      - Rust\n      - SDK\n      - Embedding\n  - aid: wasmedge:wasmedge-go-sdk\n    name: WasmEdge Go SDK\n    description: >-\n      The WasmEdge Go SDK provides Go language bindings for embedding the\n      WasmEdge runtime in Go applications. It enables loading and executing\n      WebAssembly modules from Go, defining host functions, and managing\n      WasmEdge configurations programmatically.\n    humanURL: https://wasmedge.org/docs/embed/go/intro/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmedge.org/docs/embed/go/intro/\n\
  \      - type: GitHubRepository\n        url: https://github.com/second-state/WasmEdge-go\n    tags:\n      - Go\n      - SDK\n      - Embedding\n  - aid: wasmedge:wasmedge-nodejs-sdk\n    name: WasmEdge Node.js SDK\n    description: >-\n      The WasmEdge Node.js SDK allows embedding and calling WebAssembly\n      functions from Node.js applications. It provides bindings for executing\n      Wasm modules within the WasmEdge runtime from JavaScript, enabling\n      high-performance compute from Node.js services.\n    humanURL: https://wasmedge.org/docs/embed/node/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmedge.org/docs/embed/node/\n    tags:\n      - Node.js\n      - JavaScript\n      - SDK\n      - Embedding\n  - aid: wasmedge:wasmedge-plugin-system\n    name: WasmEdge Plugin System\n    description: >-\n      WasmEdge's plugin system enables extending the runtime with\
  \ custom host\n      function packages. Plugins can be developed in Rust or C/C++ and loaded\n      at runtime, providing capabilities like TensorFlow AI inference, image\n      processing, database drivers, and WASI networking extensions.\n    humanURL: https://wasmedge.org/docs/contribute/plugin/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://wasmedge.org/docs/contribute/plugin/\n      - type: GitHubRepository\n        url: https://github.com/WasmEdge/WasmEdge\n    tags:\n      - Plugins\n      - Extensions\n      - TensorFlow\n      - AI\ncommon:\n  - type: Website\n    url: https://wasmedge.org/\n  - type: Documentation\n    url: https://wasmedge.org/docs/\n  - type: Getting Started\n    url: https://wasmedge.org/docs/start/getting-started/\n  - type: GitHubOrganization\n    url: https://github.com/WasmEdge\n  - type: GitHubRepository\n    url: https://github.com/WasmEdge/WasmEdge\n\
  \  - type: Blog\n    url: https://wasmedge.org/blog/\n  - type: Slack\n    url: https://wasmedge.slack.com/\n  - type: Discord\n    url: https://discord.gg/U4B5sFTkFc\n  - type: Vocabulary\n    url: vocabulary/wasmedge-vocabulary.yml\n  - type: JSON-LD\n    url: json-ld/wasmedge-context.jsonld\n  - type: JSONSchema\n    url: json-schema/wasmedge-config-schema.json\n  - type: JSONStructure\n    url: json-structure/wasmedge-config-structure.json\n  - type: Vocabulary\n    url: vocabulary/wasmedge-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wasmedge/refs/heads/main/apis.yml
tags:
- Cloud Native
- CNCF
- Edge Computing
- High Performance
- Runtime
- Serverless
- Wasm
- WebAssembly
url: https://wasmedge.org
use_cases: []
---
