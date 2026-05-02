---
api_count: 9
apis:
- description: Core Java SE API including fundamental classes and utilities for building Java applications, including the java.lang, java.util, java.io, and other foundational packages.
  name: Java Core API
  slug: java-core-api
- description: Interfaces and classes for storing and manipulating groups of objects including List, Set, Map, and Queue implementations.
  name: Java Collections Framework
  slug: java-collections-framework
- description: Input and output through data streams, serialization and the file system using the java.io package.
  name: Java I/O API
  slug: java-io-api
- description: Non-blocking I/O operations for buffers, channels, selectors, and asynchronous file system access.
  name: Java NIO API
  slug: java-nio-api
- description: APIs for networking applications including HTTP, sockets, and URLs.
  name: Java Networking API
  slug: java-networking-api
- description: Utilities for concurrent programming including executors, thread pools, locks, atomic variables, and concurrent collections.
  name: Java Concurrency API
  slug: java-concurrency-api
- description: API for connecting to relational databases and executing SQL queries from Java applications.
  name: Java Database Connectivity (JDBC)
  slug: jdbc-api
- description: Examine and modify the runtime behavior of applications by inspecting classes, methods, fields, and annotations.
  name: Java Reflection API
  slug: java-reflection-api
- description: Functional-style operations on streams of elements including map, filter, reduce, and collect operations.
  name: Java Stream API
  slug: java-stream-api
common:
- title: ''
  type: Website
  url: https://www.java.com/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/java/javase/
- title: ''
  type: Getting Started
  url: https://dev.java/learn/
- title: ''
  type: GitHub Organization
  url: https://github.com/openjdk
- title: ''
  type: License
  url: https://www.oracle.com/downloads/licenses/javase-license1.html
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Support
  url: https://www.oracle.com/java/technologies/javase/support-roadmap.html
created: '2024-01-01'
description: Java is a high-level, class-based, object-oriented programming language developed by Sun Microsystems and now stewarded by Oracle. The Java Standard Edition (SE) platform provides a comprehensive set of APIs and class libraries for building cross-platform applications. Key APIs include Collections, Concurrency, I/O, NIO, Networking, JDBC, Reflection, and Streams. Java is the foundation for the Jakarta EE enterprise platform and is supported by an extensive ecosystem of open source projects, frameworks, and runtimes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Java
skills: []
slug: java
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: java\nname: Java\ndescription: >-\n  Java is a high-level, class-based, object-oriented programming language\n  developed by Sun Microsystems and now stewarded by Oracle. The Java\n  Standard Edition (SE) platform provides a comprehensive set of APIs and\n  class libraries for building cross-platform applications. Key APIs include\n  Collections, Concurrency, I/O, NIO, Networking, JDBC, Reflection, and\n  Streams. Java is the foundation for the Jakarta EE enterprise platform and\n  is supported by an extensive ecosystem of open source projects, frameworks,\n  and runtimes.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise\n  - Java\n  - JVM\n  - Object-Oriented\n  - Oracle\n  - Programming Language\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/java/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: java:java-core-api\n \
  \   name: Java Core API\n    description: >-\n      Core Java SE API including fundamental classes and utilities for\n      building Java applications, including the java.lang, java.util,\n      java.io, and other foundational packages.\n    humanURL: https://docs.oracle.com/en/java/javase/\n    tags:\n      - Core\n      - Java\n      - Standard Library\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/module-summary.html\n      - type: Specification\n        url: https://docs.oracle.com/javase/specs/\n  - aid: java:java-collections-framework\n    name: Java Collections Framework\n    description: >-\n      Interfaces and classes for storing and manipulating groups of objects\n      including List, Set, Map, and Queue implementations.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/package-summary.html\n    tags:\n      - Collections\n      - Data Structures\n      - Utilities\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/package-summary.html\n      - type: Tutorial\n        url: https://docs.oracle.com/javase/tutorial/collections/\n  - aid: java:java-io-api\n    name: Java I/O API\n    description: >-\n      Input and output through data streams, serialization and the file\n      system using the java.io package.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/package-summary.html\n    tags:\n      - Files\n      - I/O\n      - Streams\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/package-summary.html\n  - aid: java:java-nio-api\n    name: Java NIO API\n    description: >-\n      Non-blocking I/O operations for buffers, channels, selectors, and\n      asynchronous file system access.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/package-summary.html\n\
  \    tags:\n      - Async I/O\n      - Buffers\n      - NIO\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/package-summary.html\n  - aid: java:java-networking-api\n    name: Java Networking API\n    description: >-\n      APIs for networking applications including HTTP, sockets, and URLs.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/net/package-summary.html\n    tags:\n      - HTTP\n      - Networking\n      - Sockets\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/net/package-summary.html\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.net.http/java/net/http/package-summary.html\n  - aid: java:java-concurrency-api\n    name: Java Concurrency API\n    description: >-\n      Utilities for concurrent programming including executors, thread\n  \
  \    pools, locks, atomic variables, and concurrent collections.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/concurrent/package-summary.html\n    tags:\n      - Concurrency\n      - Multithreading\n      - Parallel\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/concurrent/package-summary.html\n  - aid: java:jdbc-api\n    name: Java Database Connectivity (JDBC)\n    description: >-\n      API for connecting to relational databases and executing SQL queries\n      from Java applications.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/java/sql/package-summary.html\n    tags:\n      - Database\n      - JDBC\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/module-summary.html\n      - type: Specification\n        url: https://jcp.org/en/jsr/detail?id=221\n\
  \  - aid: java:java-reflection-api\n    name: Java Reflection API\n    description: >-\n      Examine and modify the runtime behavior of applications by inspecting\n      classes, methods, fields, and annotations.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/reflect/package-summary.html\n    tags:\n      - Introspection\n      - Metadata\n      - Reflection\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/reflect/package-summary.html\n  - aid: java:java-stream-api\n    name: Java Stream API\n    description: >-\n      Functional-style operations on streams of elements including map,\n      filter, reduce, and collect operations.\n    humanURL: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/stream/package-summary.html\n    tags:\n      - Functional\n      - Lambda\n      - Streams\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/stream/package-summary.html\n\
  \      - type: Tutorial\n        url: https://docs.oracle.com/javase/tutorial/collections/streams/\ncommon:\n  - type: Website\n    url: https://www.java.com/\n  - type: Documentation\n    url: https://docs.oracle.com/en/java/javase/\n  - type: Getting Started\n    url: https://dev.java/learn/\n  - type: GitHub Organization\n    url: https://github.com/openjdk\n  - type: License\n    url: https://www.oracle.com/downloads/licenses/javase-license1.html\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Support\n    url: https://www.oracle.com/java/technologies/javase/support-roadmap.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/java/refs/heads/main/apis.yml
tags:
- Enterprise
- Java
- JVM
- Object-Oriented
- Oracle
- Programming Language
url: https://raw.githubusercontent.com/api-evangelist/java/refs/heads/main/apis.yml
use_cases: []
---
