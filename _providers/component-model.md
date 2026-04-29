---
api_count: 4
apis:
- description: The Component Model specification repository under the W3C WebAssembly Community Group. Contains design documents, the formal specification drafts, the WIT grammar, the canonical ABI, and the binary a
  name: WebAssembly Component Model Specification
  slug: specification
- description: WIT is the interface definition language for the Component Model. WIT describes the imports and exports of a component using interfaces and worlds. WIT is consumed by language toolchains to generate b
  name: WebAssembly Interface Type (WIT)
  slug: wit
- description: WASI Preview 2 is the first WASI release built on the Component Model. It defines a set of interfaces such as wasi:filesystem, wasi:io, wasi:http, wasi:cli, and wasi:sockets that components can import
  name: WebAssembly System Interface Preview 2
  slug: wasi-preview-2
- description: A landscape of toolchains and runtimes that implement the Component Model, including Wasmtime, Jco, wit-bindgen language bindings, cargo-component for Rust, ComponentizeJS, and Spin for serverless Was
  name: Component Model Implementations
  slug: bytecode-alliance-implementations
common:
- title: ''
  type: Website
  url: https://component-model.bytecodealliance.org/
- title: ''
  type: Documentation
  url: https://component-model.bytecodealliance.org/design/
- title: ''
  type: GitHubRepository
  url: https://github.com/WebAssembly/component-model
- title: ''
  type: GitHub Organization
  url: https://github.com/WebAssembly
- title: ''
  type: Reference
  url: https://wasi.dev/
- title: ''
  type: Reference
  url: https://bytecodealliance.org/
- title: ''
  type: Working Group
  url: https://www.w3.org/community/webassembly/
created: '2025-01-01'
description: The WebAssembly Component Model is a broad-reaching architecture for building interoperable WebAssembly libraries, applications, and environments. It defines components as portable, sandboxed units of code that can compose with each other across language and runtime boundaries. The model introduces interfaces, worlds, and the WebAssembly Interface Type (WIT) language, along with a canonical ABI, binary and text formats, and a concurrency model. The Component Model underpins the WebAssembly System Interface (WASI) Preview 2 and is the foundation for portable Wasm on browsers, servers, edge, and embedded environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Component Model
skills: []
slug: component-model
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: component-model\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/component-model/refs/heads/main/apis.yml\nname: Component Model\nx-type: standard\ndescription: >-\n  The WebAssembly Component Model is a broad-reaching architecture for\n  building interoperable WebAssembly libraries, applications, and\n  environments. It defines components as portable, sandboxed units of code\n  that can compose with each other across language and runtime boundaries.\n  The model introduces interfaces, worlds, and the WebAssembly Interface\n  Type (WIT) language, along with a canonical ABI, binary and text formats,\n  and a concurrency model. The Component Model underpins the WebAssembly\n  System Interface (WASI) Preview 2 and is the foundation for portable Wasm\n  on browsers, servers, edge, and embedded environments.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ABI\n  - Bytecode Alliance\n  - Component\n  - Interface\n  -\
  \ Modular\n  - Specification\n  - WASI\n  - WebAssembly\n  - WIT\n  - World\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: component-model:specification\n    name: WebAssembly Component Model Specification\n    description: >-\n      The Component Model specification repository under the W3C WebAssembly\n      Community Group. Contains design documents, the formal specification\n      drafts, the WIT grammar, the canonical ABI, and the binary and text\n      formats that define a WebAssembly component.\n    humanURL: https://github.com/WebAssembly/component-model\n    baseURL: https://github.com/WebAssembly\n    tags:\n      - Specification\n      - W3C\n      - WebAssembly\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/WebAssembly/component-model\n      - type: Documentation\n        url: https://github.com/WebAssembly/component-model/blob/main/design/mvp/Explainer.md\n      - type: Specification\n     \
  \   url: https://github.com/WebAssembly/component-model/tree/main/design/mvp\n      - type: Reference\n        url: https://github.com/WebAssembly/component-model/blob/main/design/mvp/CanonicalABI.md\n      - type: Reference\n        url: https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md\n    x-features:\n      - Defines components, interfaces, and worlds\n      - Introduces WIT, the WebAssembly Interface Type language\n      - Specifies a canonical ABI between components and host\n      - Provides binary and text formats for components\n      - Foundation for WASI Preview 2 system interfaces\n    x-useCases:\n      - Tracking the evolving Component Model standard\n      - Implementing language toolchains targeting components\n      - Implementing runtimes that load and link components\n  - aid: component-model:wit\n    name: WebAssembly Interface Type (WIT)\n    description: >-\n      WIT is the interface definition language for the Component Model. WIT\n    \
  \  describes the imports and exports of a component using interfaces and\n      worlds. WIT is consumed by language toolchains to generate bindings\n      and by runtimes to validate and link components at load time.\n    humanURL: https://component-model.bytecodealliance.org/design/wit.html\n    baseURL: https://component-model.bytecodealliance.org\n    tags:\n      - Bindings\n      - IDL\n      - Interface\n      - WIT\n    properties:\n      - type: Documentation\n        url: https://component-model.bytecodealliance.org/design/wit.html\n      - type: Specification\n        url: https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md\n      - type: Reference\n        url: https://github.com/bytecodealliance/wit-bindgen\n    x-features:\n      - Declarative IDL for components\n      - Records, variants, enums, flags, options, results\n      - Resources with methods for borrowed and owned references\n      - Interfaces compose into worlds\n    x-useCases:\n      -\
  \ Authoring portable component interfaces\n      - Generating language bindings via wit-bindgen\n      - Defining stable contracts between platform and components\n  - aid: component-model:wasi-preview-2\n    name: WebAssembly System Interface Preview 2\n    description: >-\n      WASI Preview 2 is the first WASI release built on the Component Model.\n      It defines a set of interfaces such as wasi:filesystem, wasi:io,\n      wasi:http, wasi:cli, and wasi:sockets that components can import to\n      interact with the host system in a portable, capability-based way.\n    humanURL: https://wasi.dev/\n    baseURL: https://wasi.dev\n    tags:\n      - System Interface\n      - WASI\n      - Capabilities\n    properties:\n      - type: Documentation\n        url: https://wasi.dev/\n      - type: GitHub Organization\n        url: https://github.com/WebAssembly/WASI\n      - type: Reference\n        url: https://github.com/WebAssembly/wasi-http\n      - type: Reference\n        url: https://github.com/WebAssembly/wasi-filesystem\n\
  \    x-features:\n      - Capability-based system access\n      - Defined as a collection of WIT worlds\n      - wasi:http provides a portable HTTP server interface\n      - Worlds for CLI, HTTP proxy, and embedder customization\n    x-useCases:\n      - Building portable WebAssembly server functions\n      - Running components in Wasmtime, Jco, WasmEdge, and Spin\n      - Implementing capability-secure host bindings\n  - aid: component-model:bytecode-alliance-implementations\n    name: Component Model Implementations\n    description: >-\n      A landscape of toolchains and runtimes that implement the Component\n      Model, including Wasmtime, Jco, wit-bindgen language bindings,\n      cargo-component for Rust, ComponentizeJS, and Spin for serverless\n      Wasm. These implementations are largely stewarded by the Bytecode\n      Alliance.\n    humanURL: https://bytecodealliance.org/\n    baseURL: https://bytecodealliance.org\n    tags:\n      - Bytecode Alliance\n      - Implementations\n\
  \      - Runtimes\n      - Toolchains\n    properties:\n      - type: Reference\n        url: https://github.com/bytecodealliance/wasmtime\n      - type: Reference\n        url: https://github.com/bytecodealliance/wit-bindgen\n      - type: Reference\n        url: https://github.com/bytecodealliance/cargo-component\n      - type: Reference\n        url: https://github.com/bytecodealliance/jco\n      - type: Reference\n        url: https://github.com/bytecodealliance/ComponentizeJS\n      - type: Reference\n        url: https://github.com/fermyon/spin\n    x-features:\n      - Wasmtime native runtime with component support\n      - Jco JavaScript host and tooling\n      - cargo-component for Rust component projects\n      - wit-bindgen for cross-language bindings\n    x-useCases:\n      - Running components on the server, edge, or in browsers\n      - Generating language bindings from WIT\n      - Building serverless Wasm functions on Spin\ncommon:\n  - type: Website\n    url: https://component-model.bytecodealliance.org/\n\
  \  - type: Documentation\n    url: https://component-model.bytecodealliance.org/design/\n  - type: GitHubRepository\n    url: https://github.com/WebAssembly/component-model\n  - type: GitHub Organization\n    url: https://github.com/WebAssembly\n  - type: Reference\n    url: https://wasi.dev/\n  - type: Reference\n    url: https://bytecodealliance.org/\n  - type: Working Group\n    url: https://www.w3.org/community/webassembly/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/component-model/refs/heads/main/apis.yml
tags:
- ABI
- Bytecode Alliance
- Component
- Interface
- Modular
- Specification
- WASI
- WebAssembly
- WIT
- World
url: https://raw.githubusercontent.com/api-evangelist/component-model/refs/heads/main/apis.yml
use_cases: []
---
