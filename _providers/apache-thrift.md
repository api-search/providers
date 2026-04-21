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
