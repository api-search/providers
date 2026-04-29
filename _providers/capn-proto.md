---
api_count: 5
apis:
- description: The Cap'n Proto schema language is used to define message types in .capnp files that are then compiled into native code for each supported language. The schema language defines structs, unions, enums,
  name: Cap'n Proto Schema Language
  slug: capn-proto-schema-language
- description: 'The Cap''n Proto encoding specification defines the binary wire format. The in-memory layout is the wire format, enabling zero-copy reads and writes, random field access, and safe memory-mapped access '
  name: Cap'n Proto Encoding (Wire Format)
  slug: capn-proto-encoding
- description: 'Cap''n Proto''s RPC protocol is a capability-based RPC layer that supports promise pipelining, object references passed as arguments or return values, and time-travel optimizations that eliminate round '
  name: Cap'n Proto RPC Protocol
  slug: capn-proto-rpc
- description: The C++ reference implementation is the canonical runtime for Cap'n Proto, providing the capnp compiler, serialization library, and KJ/RPC runtime. Other language implementations are maintained by the
  name: Cap'n Proto C++ Reference Implementation
  slug: capn-proto-cpp-runtime
- description: Community-maintained language bindings implement Cap'n Proto serialization and, in many cases, the full RPC protocol. Serialization plus RPC is supported in C++, C#, Erlang, Go, Haskell, JavaScript (N
  name: Cap'n Proto Language Bindings
  slug: capn-proto-language-bindings
common:
- title: ''
  type: Website
  url: https://capnproto.org/
- title: ''
  type: Documentation
  url: https://capnproto.org/language.html
- title: ''
  type: Getting Started
  url: https://capnproto.org/install.html
- title: ''
  type: GitHub Organization
  url: https://github.com/capnproto
- title: ''
  type: GitHub Repository
  url: https://github.com/capnproto/capnproto
- title: ''
  type: Discussion Group
  url: https://groups.google.com/g/capnproto
- title: ''
  type: License
  url: https://github.com/capnproto/capnproto/blob/master/LICENSE.txt
created: '2026-03-25'
description: Cap'n Proto is an open-source binary data interchange format and capability-based RPC protocol specification originally created by Kenton Varda. Unlike Protocol Buffers, Cap'n Proto's in-memory representation is identical to its wire format, enabling zero-copy deserialization, incremental reads, random field access, and memory-mapped I/O. The reference implementation is in C++; a broad ecosystem of community-maintained bindings covers C#, Erlang, Go, Haskell, JavaScript/Node, OCaml, Python, Rust, C, D, Java, Lua, Nim, Ruby, and Scala.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cap'n Proto
skills: []
slug: capn-proto
solutions: []
source_filename: apis.yml
source_yaml: "aid: capn-proto\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/capn-proto/refs/heads/main/apis.yml\nname: Cap'n Proto\ndescription: >-\n  Cap'n Proto is an open-source binary data interchange format and\n  capability-based RPC protocol specification originally created by\n  Kenton Varda. Unlike Protocol Buffers, Cap'n Proto's in-memory\n  representation is identical to its wire format, enabling zero-copy\n  deserialization, incremental reads, random field access, and\n  memory-mapped I/O. The reference implementation is in C++; a\n  broad ecosystem of community-maintained bindings covers C#, Erlang,\n  Go, Haskell, JavaScript/Node, OCaml, Python, Rust, C, D, Java, Lua,\n  Nim, Ruby, and Scala.\ntype: Index\nx-type: standard\nposition: Producer\naccess: Open Source\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Binary Format\n  - Capability-Based Security\n  - Code Generation\n  - IPC\n  - Open Source\n  - Protocol\n\
  \  - RPC\n  - Schema\n  - SDKs\n  - Serialization\n  - Specification\n  - Zero Copy\ncreated: '2026-03-25'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: capn-proto:capn-proto-schema-language\n    name: Cap'n Proto Schema Language\n    description: >-\n      The Cap'n Proto schema language is used to define message types\n      in .capnp files that are then compiled into native code for each\n      supported language. The schema language defines structs, unions,\n      enums, interfaces (for RPC), groups, generics, and annotations,\n      and carefully specifies evolution rules so schemas can be extended\n      without breaking forward or backward compatibility.\n    humanURL: https://capnproto.org/language.html\n    tags:\n      - Code Generation\n      - Schema\n      - Specification\n    properties:\n      - type: Specification\n        url: https://capnproto.org/language.html\n      - type: Documentation\n        url: https://capnproto.org/language.html\n  \
  \    - type: GitHub Repository\n        url: https://github.com/capnproto/capnproto\n    x-features:\n      - Struct, union, enum, interface, and group definitions\n      - Generic parameters for reusable types\n      - Annotations for custom metadata\n      - Schema evolution rules for forward and backward compatibility\n      - Compilation to native code in multiple languages\n      - Cross-language ABI through a canonical wire format\n    x-use-cases:\n      - Defining message types for zero-copy IPC\n      - Describing RPC interfaces across language boundaries\n      - Long-lived storage formats with schema evolution\n      - Replacing Protocol Buffers for latency-sensitive workloads\n  - aid: capn-proto:capn-proto-encoding\n    name: Cap'n Proto Encoding (Wire Format)\n    description: >-\n      The Cap'n Proto encoding specification defines the binary wire\n      format. The in-memory layout is the wire format, enabling zero-copy\n      reads and writes, random field access, and\
  \ safe memory-mapped\n      access to messages stored on disk.\n    humanURL: https://capnproto.org/encoding.html\n    tags:\n      - Binary Format\n      - Specification\n      - Zero Copy\n    properties:\n      - type: Specification\n        url: https://capnproto.org/encoding.html\n    x-features:\n      - In-memory layout equals the wire format\n      - Zero-copy deserialization\n      - Random field access without scanning\n      - Support for mmap-based message storage\n      - Packed encoding variant for bandwidth-constrained links\n      - Canonicalization rules for deterministic encoding\n    x-use-cases:\n      - Ultra-low-latency inter-process communication\n      - Large on-disk datasets with mmap access\n      - Network protocols where parsing cost matters\n      - Embedded or memory-constrained environments (packed form)\n  - aid: capn-proto:capn-proto-rpc\n    name: Cap'n Proto RPC Protocol\n    description: >-\n      Cap'n Proto's RPC protocol is a capability-based RPC\
  \ layer that\n      supports promise pipelining, object references passed as arguments\n      or return values, and time-travel optimizations that eliminate\n      round trips. It is the foundation of Cloudflare Workers' inter-\n      service communication and Sandstorm's capability-oriented sandbox.\n    humanURL: https://capnproto.org/rpc.html\n    tags:\n      - Capability-Based Security\n      - Protocol\n      - RPC\n      - Specification\n    properties:\n      - type: Specification\n        url: https://capnproto.org/rpc.html\n      - type: Documentation\n        url: https://capnproto.org/rpc.html\n    x-features:\n      - Capability-based security model\n      - Object (capability) references passed in messages\n      - Promise pipelining to eliminate round trips\n      - Bidirectional calls over a single connection\n      - Time-travel / path-compression optimizations\n      - Transport-agnostic (TCP, TLS, WebSocket, shared memory)\n    x-use-cases:\n      - Microservice RPC\
  \ with low round-trip overhead\n      - Secure capability-oriented sandboxing (Sandstorm, Workers)\n      - Bidirectional streaming between trusted peers\n      - Inter-process communication with fine-grained authorization\n  - aid: capn-proto:capn-proto-cpp-runtime\n    name: Cap'n Proto C++ Reference Implementation\n    description: >-\n      The C++ reference implementation is the canonical runtime for\n      Cap'n Proto, providing the capnp compiler, serialization library,\n      and KJ/RPC runtime. Other language implementations are maintained\n      by their respective authors and track the C++ reference.\n    humanURL: https://github.com/capnproto/capnproto\n    tags:\n      - IPC\n      - SDKs\n      - Serialization\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/capnproto/capnproto\n      - type: Getting Started\n        url: https://capnproto.org/install.html\n      - type: Documentation\n        url: https://capnproto.org/cxx.html\n    x-features:\n\
  \      - capnp schema compiler\n      - KJ async and concurrency library\n      - RPC runtime over TCP and in-process transports\n      - Arena allocator for fast message construction\n      - Packed and canonical encoding support\n  - aid: capn-proto:capn-proto-language-bindings\n    name: Cap'n Proto Language Bindings\n    description: >-\n      Community-maintained language bindings implement Cap'n Proto\n      serialization and, in many cases, the full RPC protocol.\n      Serialization plus RPC is supported in C++, C#, Erlang, Go,\n      Haskell, JavaScript (Node.js), OCaml, Python, and Rust.\n      Serialization-only bindings exist for C, D, Java, Lua, Nim,\n      Ruby, and Scala.\n    humanURL: https://capnproto.org/otherlang.html\n    tags:\n      - Code Generation\n      - SDKs\n      - Serialization\n    properties:\n      - type: Documentation\n        url: https://capnproto.org/otherlang.html\n      - type: GitHub Organization\n        url: https://github.com/capnproto\n  \
  \  x-features:\n      - Serialization + RPC in C++, C#, Erlang, Go, Haskell, JavaScript, OCaml, Python, Rust\n      - Serialization-only bindings in C, D, Java, Lua, Nim, Ruby, Scala\n      - Shared canonical wire format across all implementations\n      - Editor integrations and syntax highlighters for common IDEs\n    x-use-cases:\n      - Polyglot systems sharing message types across services\n      - Compiling schemas into idiomatic bindings for each language\n      - Migration paths from Protocol Buffers in non-C++ codebases\ncommon:\n  - type: Website\n    url: https://capnproto.org/\n  - type: Documentation\n    url: https://capnproto.org/language.html\n  - type: Getting Started\n    url: https://capnproto.org/install.html\n  - type: GitHub Organization\n    url: https://github.com/capnproto\n  - type: GitHub Repository\n    url: https://github.com/capnproto/capnproto\n  - type: Discussion Group\n    url: https://groups.google.com/g/capnproto\n  - type: License\n    url: https://github.com/capnproto/capnproto/blob/master/LICENSE.txt\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/capn-proto/refs/heads/main/apis.yml
tags:
- Binary Format
- Capability-Based Security
- Code Generation
- IPC
- Open Source
- Protocol
- RPC
- Schema
- SDKs
- Serialization
- Specification
- Zero Copy
url: https://raw.githubusercontent.com/api-evangelist/capn-proto/refs/heads/main/apis.yml
use_cases: []
---
