---
api_count: 11
apis:
- description: The Scala Standard Library provides core data structures, collections, concurrent primitives, and runtime utilities for Scala programs on the JVM, JavaScript (Scala.js), and Native (Scala Native) runt
  name: Scala Standard Library API
  slug: scala-lang
- description: Akka is a toolkit for building highly concurrent, distributed, and fault-tolerant applications on the JVM using the Actor model. Includes Akka Actors, Akka HTTP, Akka Streams, and Akka Cluster.
  name: Akka API
  slug: akka
- description: Akka HTTP provides a full server- and client-side HTTP stack built on Akka Streams. Offers high-throughput, non-blocking HTTP handling with a powerful Scala DSL for routing and marshalling.
  name: Akka HTTP API
  slug: akka-http
- description: Play is a reactive web framework for Scala (and Java) built on Akka and Akka Streams. Provides MVC routing, template engine, WS client, and reactive database integrations for building web applications
  name: Play Framework API
  slug: play-framework
- description: ZIO is a type-safe, composable library for asynchronous and concurrent programming in Scala. Provides a purely functional effect system with structured concurrency, resource management, and a rich eco
  name: ZIO API
  slug: zio
- description: 'Cats is a lightweight, modular library for functional programming in Scala. It provides type class abstractions (Functor, Monad, Applicative, etc.) and their instances for standard library types. The '
  name: Cats API
  slug: cats
- description: http4s is a typeful, functional, streaming HTTP library for Scala built on cats-effect and fs2. Provides server and client abstractions with backends for Blaze, Ember, Jetty, and Tomcat. Second most p
  name: http4s API
  slug: http4s
- description: Slick is Functional Relational Mapping (FRM) for Scala — a type-safe, composable database access library that lets you work with stored data almost as if you were using Scala collections. Supports Pos
  name: Slick API
  slug: slick
- description: Circe is the most widely used JSON library for Scala, built on top of Cats. Provides encoding, decoding, traversal, and transformation of JSON values with automatic derivation support for case classes
  name: Circe API
  slug: circe
- description: Apache Spark is the dominant big data processing framework in the Scala ecosystem. Its API enables large-scale data processing, SQL analytics, streaming, and machine learning across distributed cluste
  name: Apache Spark API
  slug: apache-spark
- description: sbt (Simple Build Tool) is the dominant build tool in the Scala ecosystem (90% adoption). Its Server API enables IDE integration via the Build Server Protocol (BSP). sbt 2.0 release candidates show up
  name: sbt Build Tool
  slug: sbt
common:
- title: ''
  type: Website
  url: https://www.scala-lang.org/
- title: ''
  type: Blog
  url: https://www.scala-lang.org/blog/
- title: ''
  type: Documentation
  url: https://docs.scala-lang.org/
- title: ''
  type: Forum
  url: https://users.scala-lang.org/
- title: ''
  type: GitHub
  url: https://github.com/scala
- title: ''
  type: Newsletter
  url: https://scalatimes.com/
- title: ''
  type: Social
  url: https://twitter.com/scala_lang
- title: ''
  type: Community
  url: https://discord.gg/scala
- title: ''
  type: JSONSchema
  url: https://github.com/api-evangelist/scala/blob/main/json-schema/scala-library-schema.json
- title: ''
  type: JSONStructure
  url: https://github.com/api-evangelist/scala/blob/main/json-structure/scala-library-structure.json
- title: ''
  type: JSONLDContext
  url: https://github.com/api-evangelist/scala/blob/main/json-ld/scala-context.jsonld
- title: ''
  type: Vocabulary
  url: https://github.com/api-evangelist/scala/blob/main/vocabulary/scala-vocabulary.yml
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scala/blob/main/examples/scala-zio-http-example.json
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scala/blob/main/examples/scala-cats-effect-http4s-example.json
created: '2024-01-15'
description: A topic collection covering the Scala programming language ecosystem, including its standard library, key frameworks, and widely-used libraries. Scala is a strongly-typed, JVM-based language that blends object-oriented and functional programming, widely used in big data engineering, distributed systems, fintech, and backend development. The ecosystem includes the Akka actor framework, Play web framework, ZIO effect system, Cats typeclass library, http4s, Slick, sbt build tool, and Spark. Scala 3.8 is the current major version (January 2026).
features: []
image: https://www.scala-lang.org/resources/img/scala-logo.png
integrations: []
jsonld:
- class_count: 34
  name: Scala Context
  property_count: 1
  slug: scala-context
layout: provider
modified: '2026-05-02'
name: Scala
skills: []
slug: scala
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scala\nname: Scala\ndescription: >-\n  A topic collection covering the Scala programming language ecosystem, including\n  its standard library, key frameworks, and widely-used libraries. Scala is a\n  strongly-typed, JVM-based language that blends object-oriented and functional\n  programming, widely used in big data engineering, distributed systems, fintech,\n  and backend development. The ecosystem includes the Akka actor framework, Play\n  web framework, ZIO effect system, Cats typeclass library, http4s, Slick,\n  sbt build tool, and Spark. Scala 3.8 is the current major version (January 2026).\nimage: https://www.scala-lang.org/resources/img/scala-logo.png\ntags:\n  - Big Data\n  - Distributed Systems\n  - Functional Programming\n  - JVM\n  - Programming Language\n  - Scala\n  - Scala 3\n  - Type Safety\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scala:scala-lang\n    name: Scala Standard Library API\n\
  \    description: >-\n      The Scala Standard Library provides core data structures, collections,\n      concurrent primitives, and runtime utilities for Scala programs on the JVM,\n      JavaScript (Scala.js), and Native (Scala Native) runtimes. Scala 3.8\n      shipped in January 2026 with a JDK 17 baseline.\n    tags:\n      - Core\n      - JVM\n      - Programming Language\n      - Scala\n      - Standard Library\n    humanURL: https://www.scala-lang.org/api/current/\n    properties:\n      - type: Documentation\n        url: https://www.scala-lang.org/api/current/\n      - type: Website\n        url: https://www.scala-lang.org/\n      - type: GitHub\n        url: https://github.com/scala/scala\n  - aid: scala:akka\n    name: Akka API\n    description: >-\n      Akka is a toolkit for building highly concurrent, distributed, and\n      fault-tolerant applications on the JVM using the Actor model. Includes\n      Akka Actors, Akka HTTP, Akka Streams, and Akka Cluster.\n    tags:\n \
  \     - Actors\n      - Concurrent\n      - Distributed Systems\n      - HTTP\n      - Reactive\n      - Scala\n    humanURL: https://doc.akka.io/\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/docs/akka/current/\n      - type: API Documentation\n        url: https://doc.akka.io/api/akka/current/akka/\n      - type: GitHub\n        url: https://github.com/akka/akka\n  - aid: scala:akka-http\n    name: Akka HTTP API\n    description: >-\n      Akka HTTP provides a full server- and client-side HTTP stack built on\n      Akka Streams. Offers high-throughput, non-blocking HTTP handling with a\n      powerful Scala DSL for routing and marshalling.\n    tags:\n      - Akka\n      - Client\n      - HTTP\n      - Reactive\n      - Scala\n      - Server\n    humanURL: https://doc.akka.io/docs/akka-http/current/\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/docs/akka-http/current/\n      - type: API Documentation\n        url: https://doc.akka.io/api/akka-http/current/akka/http/\n\
  \      - type: GitHub\n        url: https://github.com/akka/akka-http\n  - aid: scala:play-framework\n    name: Play Framework API\n    description: >-\n      Play is a reactive web framework for Scala (and Java) built on Akka and\n      Akka Streams. Provides MVC routing, template engine, WS client, and\n      reactive database integrations for building web applications and REST APIs.\n    tags:\n      - MVC\n      - Reactive\n      - REST\n      - Scala\n      - Web Framework\n    humanURL: https://www.playframework.com/\n    properties:\n      - type: Documentation\n        url: https://www.playframework.com/documentation/latest/Home\n      - type: API Documentation\n        url: https://www.playframework.com/documentation/latest/api/scala/\n      - type: GitHub\n        url: https://github.com/playframework/playframework\n  - aid: scala:zio\n    name: ZIO API\n    description: >-\n      ZIO is a type-safe, composable library for asynchronous and concurrent\n      programming in Scala.\
  \ Provides a purely functional effect system with\n      structured concurrency, resource management, and a rich ecosystem of\n      ZIO-based libraries (ZIO HTTP, ZIO Kafka, ZIO Quill, ZIO Schema).\n    tags:\n      - Async\n      - Concurrent\n      - Effect System\n      - Functional Programming\n      - Scala\n      - Type Safe\n    humanURL: https://zio.dev/\n    properties:\n      - type: Documentation\n        url: https://zio.dev/overview/\n      - type: API Documentation\n        url: https://javadoc.io/doc/dev.zio/zio_3/latest/\n      - type: GitHub\n        url: https://github.com/zio/zio\n  - aid: scala:cats\n    name: Cats API\n    description: >-\n      Cats is a lightweight, modular library for functional programming in Scala.\n      It provides type class abstractions (Functor, Monad, Applicative, etc.)\n      and their instances for standard library types. The most widely used\n      functional programming library in the Scala ecosystem (56% adoption).\n    tags:\n   \
  \   - Category Theory\n      - Functional Programming\n      - Scala\n      - Type Classes\n    humanURL: https://typelevel.org/cats/\n    properties:\n      - type: Documentation\n        url: https://typelevel.org/cats/\n      - type: API Documentation\n        url: https://typelevel.org/cats/api/\n      - type: GitHub\n        url: https://github.com/typelevel/cats\n  - aid: scala:http4s\n    name: http4s API\n    description: >-\n      http4s is a typeful, functional, streaming HTTP library for Scala built on\n      cats-effect and fs2. Provides server and client abstractions with backends\n      for Blaze, Ember, Jetty, and Tomcat. Second most popular HTTP library in the\n      Scala ecosystem (45% adoption).\n    tags:\n      - Cats Effect\n      - Functional Programming\n      - HTTP\n      - Scala\n      - Streaming\n    humanURL: https://http4s.org/\n    properties:\n      - type: Documentation\n        url: https://http4s.org/v1/docs/\n      - type: GitHub\n        url: https://github.com/http4s/http4s\n\
  \  - aid: scala:slick\n    name: Slick API\n    description: >-\n      Slick is Functional Relational Mapping (FRM) for Scala — a type-safe,\n      composable database access library that lets you work with stored data\n      almost as if you were using Scala collections. Supports PostgreSQL, MySQL,\n      H2, SQLite, and more.\n    tags:\n      - Database\n      - Functional\n      - ORM\n      - Scala\n      - SQL\n    humanURL: https://scala-slick.org/\n    properties:\n      - type: Documentation\n        url: https://scala-slick.org/doc/stable/\n      - type: API Documentation\n        url: https://scala-slick.org/doc/stable/api/\n      - type: GitHub\n        url: https://github.com/slick/slick\n  - aid: scala:circe\n    name: Circe API\n    description: >-\n      Circe is the most widely used JSON library for Scala, built on top of\n      Cats. Provides encoding, decoding, traversal, and transformation of\n      JSON values with automatic derivation support for case classes and\n\
  \      sealed traits.\n    tags:\n      - Cats\n      - Functional Programming\n      - JSON\n      - Parsing\n      - Scala\n      - Serialization\n    humanURL: https://circe.github.io/circe/\n    properties:\n      - type: Documentation\n        url: https://circe.github.io/circe/\n      - type: API Documentation\n        url: https://circe.github.io/circe/api/\n      - type: GitHub\n        url: https://github.com/circe/circe\n  - aid: scala:apache-spark\n    name: Apache Spark API\n    description: >-\n      Apache Spark is the dominant big data processing framework in the Scala\n      ecosystem. Its API enables large-scale data processing, SQL analytics,\n      streaming, and machine learning across distributed clusters.\n    tags:\n      - Big Data\n      - Data Engineering\n      - Distributed Systems\n      - Machine Learning\n      - Scala\n      - Spark\n    humanURL: https://spark.apache.org/docs/latest/api/scala/\n    properties:\n      - type: Documentation\n        url:\
  \ https://spark.apache.org/docs/latest/api/scala/\n      - type: REST API\n        url: https://spark.apache.org/docs/latest/monitoring.html#rest-api\n      - type: GitHub\n        url: https://github.com/apache/spark\n  - aid: scala:sbt\n    name: sbt Build Tool\n    description: >-\n      sbt (Simple Build Tool) is the dominant build tool in the Scala ecosystem\n      (90% adoption). Its Server API enables IDE integration via the Build Server\n      Protocol (BSP). sbt 2.0 release candidates show up to 41% faster startup.\n    tags:\n      - Build Tool\n      - Developer Tools\n      - Scala\n    humanURL: https://www.scala-sbt.org/\n    properties:\n      - type: Documentation\n        url: https://www.scala-sbt.org/1.x/docs/\n      - type: GitHub\n        url: https://github.com/sbt/sbt\ncommon:\n  - type: Website\n    url: https://www.scala-lang.org/\n    name: Scala Language Website\n  - type: Blog\n    url: https://www.scala-lang.org/blog/\n    name: Scala Official Blog\n  - type:\
  \ Documentation\n    url: https://docs.scala-lang.org/\n    name: Scala Documentation\n  - type: Forum\n    url: https://users.scala-lang.org/\n    name: Scala Users Forum\n  - type: GitHub\n    url: https://github.com/scala\n    name: Scala GitHub Organization\n  - type: Newsletter\n    url: https://scalatimes.com/\n    name: Scala Times Newsletter\n  - type: Social\n    url: https://twitter.com/scala_lang\n    name: Scala Twitter\n  - type: Community\n    url: https://discord.gg/scala\n    name: Scala Discord\n  - type: JSONSchema\n    url: https://github.com/api-evangelist/scala/blob/main/json-schema/scala-library-schema.json\n    name: Scala Library JSON Schema\n  - type: JSONStructure\n    url: https://github.com/api-evangelist/scala/blob/main/json-structure/scala-library-structure.json\n    name: Scala Library JSON Structure\n  - type: JSONLDContext\n    url: https://github.com/api-evangelist/scala/blob/main/json-ld/scala-context.jsonld\n    name: Scala JSON-LD Context\n  - type:\
  \ Vocabulary\n    url: https://github.com/api-evangelist/scala/blob/main/vocabulary/scala-vocabulary.yml\n    name: Scala Vocabulary\n  - type: Examples\n    url: https://github.com/api-evangelist/scala/blob/main/examples/scala-zio-http-example.json\n    name: ZIO HTTP Server Example\n  - type: Examples\n    url: https://github.com/api-evangelist/scala/blob/main/examples/scala-cats-effect-http4s-example.json\n    name: http4s REST API with cats-effect Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scala/refs/heads/main/apis.yml
tags:
- Big Data
- Distributed Systems
- Functional Programming
- JVM
- Programming Language
- Scala
- Scala 3
- Type Safety
url: ''
use_cases: []
---
