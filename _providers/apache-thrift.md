---
api_count: 2
apis:
- description: The Thrift Interface Definition Language (IDL) is used to define data types and service interfaces in a language-neutral format. A .thrift file defines structs, enums, exceptions, typedefs, constants,
  name: Apache Thrift IDL
  slug: apache-thrift-idl
- description: The Thrift Server API provides server implementations for hosting Thrift services including TSimpleServer (single-threaded), TThreadedServer, TThreadPoolServer, and TNonblockingServer (async I/O). Thr
  name: Apache Thrift Server API
  slug: apache-thrift-server-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/thrift
- title: ''
  type: Documentation
  url: https://thrift.apache.org/docs/
- title: ''
  type: Portal
  url: https://thrift.apache.org/
- title: ''
  type: GettingStarted
  url: https://thrift.apache.org/tutorial/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/thrift/releases
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: Python Package
  type: SDK
  url: https://pypi.org/project/thrift/
- title: Java Maven Package
  type: SDK
  url: https://search.maven.org/search?q=org.apache.thrift
created: '2026-03-16'
description: Apache Thrift is a software framework for scalable cross-language services development. It provides an interface definition language (IDL) and code generation engine for building RPC services that work efficiently across C++, Java, Python, PHP, Ruby, Erlang, Go, JavaScript, Node.js, Haskell, C#, Cocoa, Delphi, and many more languages. Originally developed at Facebook, Thrift is now an Apache Software Foundation top-level project used for high-performance internal microservices and APIs.
features:
- description: Generate client and server stubs for 20+ programming languages from a single IDL file.
  name: Cross-Language Code Generation
- description: Compact binary serialization (TCompactProtocol) for high-performance inter-service communication.
  name: Binary Serialization
- description: TSocket, TFramedTransport, TFileTransport, TZlibTransport, and TMemoryBuffer transports.
  name: Multiple Transports
- description: TBinaryProtocol, TCompactProtocol, TJSONProtocol, and TSimpleJSONProtocol serialization formats.
  name: Multiple Protocols
- description: Non-blocking async server (TNonblockingServer) for high-throughput service deployments.
  name: Async Server Support
- description: Optional and default fields enable backward-compatible schema evolution across service versions.
  name: Versioned Schema Evolution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Cassandra uses Thrift (legacy) and CQL for client communication.
  name: Apache Cassandra
- description: HBase Thrift gateway for non-Java clients to access HBase.
  name: Apache HBase
- description: Hive Thrift server provides JDBC/ODBC access to Hive via Thrift protocol.
  name: Apache Hadoop
layout: provider
modified: '2026-04-19'
name: Apache Thrift
skills: []
slug: apache-thrift
solutions: []
source_yaml: "aid: apache-thrift\nname: Apache Thrift\ndescription: >-\n  Apache Thrift is a software framework for scalable cross-language services development.\n  It provides an interface definition language (IDL) and code generation engine for building\n  RPC services that work efficiently across C++, Java, Python, PHP, Ruby, Erlang, Go,\n  JavaScript, Node.js, Haskell, C#, Cocoa, Delphi, and many more languages. Originally\n  developed at Facebook, Thrift is now an Apache Software Foundation top-level project used\n  for high-performance internal microservices and APIs.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code Generation\n  - Cross-Language\n  - IDL\n  - RPC\n  - Serialization\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-thrift/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: apache-thrift:apache-thrift-idl\n    name: Apache Thrift IDL\n    description: >-\n      The Thrift Interface Definition Language (IDL) is used to define data types and service\n      interfaces in a language-neutral format. A .thrift file defines structs, enums, exceptions,\n      typedefs, constants, and services with typed method signatures. The thrift compiler generates\n      client and server code from .thrift files for over 20 target languages including Java, Python,\n      C++, Go, JavaScript, PHP, Ruby, Erlang, and Haskell.\n    humanURL: https://thrift.apache.org/docs/idl.html\n    tags:\n      - IDL\n      - Code Generation\n      - RPC\n      - Cross-Language\n    properties:\n      - type: Documentation\n        url: https://thrift.apache.org/docs/idl.html\n      - type: Documentation\n        url: https://thrift.apache.org/docs/types.html\n      - type: JSONSchema\n        url: json-schema/thrift-idl.yml\n  - aid: apache-thrift:apache-thrift-server-api\n    name:\
  \ Apache Thrift Server API\n    description: >-\n      The Thrift Server API provides server implementations for hosting Thrift services including\n      TSimpleServer (single-threaded), TThreadedServer, TThreadPoolServer, and TNonblockingServer\n      (async I/O). Thrift supports multiple transport protocols (TBinaryProtocol, TCompactProtocol,\n      TJSONProtocol) over various transports (TSocket, TFramedTransport, TFileTransport, TZlibTransport)\n      enabling flexible deployment configurations.\n    humanURL: https://thrift.apache.org/docs/concepts.html\n    tags:\n      - Server\n      - RPC\n      - Protocol\n      - Transport\n    properties:\n      - type: Documentation\n        url: https://thrift.apache.org/docs/concepts.html\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/thrift\n  - type: Documentation\n    url: https://thrift.apache.org/docs/\n  - type: Portal\n    url: https://thrift.apache.org/\n  - type: GettingStarted\n    url: https://thrift.apache.org/tutorial/\n\
  \  - type: ReleaseNotes\n    url: https://github.com/apache/thrift/releases\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://pypi.org/project/thrift/\n    title: Python Package\n  - type: SDK\n    url: https://search.maven.org/search?q=org.apache.thrift\n    title: Java Maven Package\n  - type: Features\n    data:\n      - name: Cross-Language Code Generation\n        description: Generate client and server stubs for 20+ programming languages from a single IDL file.\n      - name: Binary Serialization\n        description: Compact binary serialization (TCompactProtocol) for high-performance inter-service communication.\n      - name: Multiple Transports\n        description: TSocket, TFramedTransport, TFileTransport, TZlibTransport, and TMemoryBuffer transports.\n      - name: Multiple Protocols\n        description: TBinaryProtocol, TCompactProtocol, TJSONProtocol, and TSimpleJSONProtocol serialization formats.\n      - name: Async\
  \ Server Support\n        description: Non-blocking async server (TNonblockingServer) for high-throughput service deployments.\n      - name: Versioned Schema Evolution\n        description: Optional and default fields enable backward-compatible schema evolution across service versions.\n  - type: UseCases\n    data:\n      - name: Internal Microservices\n        description: High-performance binary RPC between internal microservices in polyglot environments.\n      - name: Cross-Language APIs\n        description: Type-safe APIs that work identically across Java, Python, C++, and other languages.\n      - name: Distributed Systems\n        description: Service mesh and distributed system communication with efficient binary serialization.\n  - type: Integrations\n    data:\n      - name: Apache Cassandra\n        description: Cassandra uses Thrift (legacy) and CQL for client communication.\n      - name: Apache HBase\n        description: HBase Thrift gateway for non-Java clients to access\
  \ HBase.\n      - name: Apache Hadoop\n        description: Hive Thrift server provides JDBC/ODBC access to Hive via Thrift protocol.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-thrift/refs/heads/main/apis.yml
tags:
- Code Generation
- Cross-Language
- IDL
- RPC
- Serialization
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-thrift/refs/heads/main/apis.yml
use_cases:
- description: High-performance binary RPC between internal microservices in polyglot environments.
  name: Internal Microservices
- description: Type-safe APIs that work identically across Java, Python, C++, and other languages.
  name: Cross-Language APIs
- description: Service mesh and distributed system communication with efficient binary serialization.
  name: Distributed Systems
---
