---
api_count: 4
apis:
- description: Retrofit is a type-safe HTTP client for the JVM that turns annotated Java/Kotlin interfaces into HTTP API calls. Supports all HTTP methods via annotations. Built on OkHttp with support for synchronous
  name: Retrofit
  slug: retrofit-core
- description: Pluggable serialization converters for Retrofit supporting Gson, Moshi, Jackson, Kotlinx Serialization, JAXB, Protocol Buffers (Wire), SimpleXML, and Scalars.
  name: Retrofit Converters
  slug: retrofit-converters
- description: Pluggable call adapters that allow Retrofit interfaces to return RxJava Observables (v1, v2, v3), Java 8 CompletableFuture, Guava ListenableFuture, and Scala Future types.
  name: Retrofit Call Adapters
  slug: retrofit-adapters
- description: Provides behavior-simulating implementations of Retrofit interfaces for local testing without requiring a network connection.
  name: Retrofit Mock
  slug: retrofit-mock
common:
- title: ''
  type: Website
  url: https://square.github.io/retrofit/
- title: ''
  type: Documentation
  url: https://square.github.io/retrofit/
- title: ''
  type: GitHub
  url: https://github.com/square/retrofit
- title: ''
  type: GitHubOrganization
  url: https://github.com/square
- title: ''
  type: Changelog
  url: https://github.com/square/retrofit/blob/trunk/CHANGELOG.md
- title: ''
  type: Issues
  url: https://github.com/square/retrofit/issues
- title: ''
  type: Maven
  url: https://search.maven.org/artifact/com.squareup.retrofit2/retrofit
- title: ''
  type: License
  url: https://github.com/square/retrofit/blob/trunk/LICENSE.txt
- title: ''
  type: JavaDoc
  url: https://square.github.io/retrofit/2.x/retrofit/
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/vocabulary/retrofit-vocabulary.yml
created: '2026-03-27'
description: Retrofit is a type-safe HTTP client for Android and the JVM (Java and Kotlin) built by Square, turning HTTP API interfaces into callable Java objects with annotation-based configuration and pluggable serialization. Retrofit is built on top of OkHttp and supports synchronous/asynchronous execution, JSON/XML/Protobuf converters, RxJava adapters, and Kotlin coroutines. Current stable version is 3.0.0.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Retrofit Context
  property_count: 4
  slug: retrofit-context
layout: provider
modified: '2026-05-02'
name: Retrofit
skills: []
slug: retrofit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: retrofit\nname: Retrofit\ndescription: >-\n  Retrofit is a type-safe HTTP client for Android and the JVM (Java and Kotlin)\n  built by Square, turning HTTP API interfaces into callable Java objects with\n  annotation-based configuration and pluggable serialization. Retrofit is built\n  on top of OkHttp and supports synchronous/asynchronous execution, JSON/XML/Protobuf\n  converters, RxJava adapters, and Kotlin coroutines. Current stable version is 3.0.0.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Android\n  - HTTP Client\n  - Java\n  - Kotlin\n  - Library\n  - Mobile\n  - Open Source\n  - SDK\n  - Square\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: retrofit:retrofit-core\n    name: Retrofit\n    description: >-\n      Retrofit is a type-safe HTTP client for the JVM\
  \ that turns annotated\n      Java/Kotlin interfaces into HTTP API calls. Supports all HTTP methods via\n      annotations. Built on OkHttp with support for synchronous Call, RxJava,\n      Java 8 CompletableFuture, and Kotlin coroutines.\n    humanURL: https://square.github.io/retrofit/\n    tags:\n      - Android\n      - HTTP Client\n      - Java\n      - Kotlin\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://square.github.io/retrofit/\n      - type: GitHub\n        url: https://github.com/square/retrofit\n      - type: Changelog\n        url: https://github.com/square/retrofit/blob/trunk/CHANGELOG.md\n      - type: JavaDoc\n        url: https://square.github.io/retrofit/2.x/retrofit/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/json-schema/retrofit-library-schema.json\n  - aid: retrofit:retrofit-converters\n    name: Retrofit Converters\n    description: >-\n      Pluggable\
  \ serialization converters for Retrofit supporting Gson, Moshi,\n      Jackson, Kotlinx Serialization, JAXB, Protocol Buffers (Wire), SimpleXML,\n      and Scalars.\n    humanURL: https://square.github.io/retrofit/#converters\n    tags:\n      - Converters\n      - Gson\n      - Jackson\n      - Moshi\n      - Protobuf\n      - Serialization\n    properties:\n      - type: Documentation\n        url: https://square.github.io/retrofit/#converters\n      - type: GitHub\n        url: https://github.com/square/retrofit/tree/trunk/retrofit-converters\n  - aid: retrofit:retrofit-adapters\n    name: Retrofit Call Adapters\n    description: >-\n      Pluggable call adapters that allow Retrofit interfaces to return RxJava\n      Observables (v1, v2, v3), Java 8 CompletableFuture, Guava ListenableFuture,\n      and Scala Future types.\n    humanURL: https://square.github.io/retrofit/#call-adapters\n    tags:\n      - Adapters\n      - Async\n      - Java 8\n      - RxJava\n      - Scala\n    properties:\n\
  \      - type: Documentation\n        url: https://square.github.io/retrofit/#call-adapters\n      - type: GitHub\n        url: https://github.com/square/retrofit/tree/trunk/retrofit-adapters\n  - aid: retrofit:retrofit-mock\n    name: Retrofit Mock\n    description: >-\n      Provides behavior-simulating implementations of Retrofit interfaces for\n      local testing without requiring a network connection.\n    humanURL: https://github.com/square/retrofit/tree/trunk/retrofit-mock\n    tags:\n      - Mock\n      - Testing\n    properties:\n      - type: GitHub\n        url: https://github.com/square/retrofit/tree/trunk/retrofit-mock\ncommon:\n  - type: Website\n    url: https://square.github.io/retrofit/\n  - type: Documentation\n    url: https://square.github.io/retrofit/\n  - type: GitHub\n    url: https://github.com/square/retrofit\n  - type: GitHubOrganization\n    url: https://github.com/square\n  - type: Changelog\n    url: https://github.com/square/retrofit/blob/trunk/CHANGELOG.md\n\
  \  - type: Issues\n    url: https://github.com/square/retrofit/issues\n  - type: Maven\n    url: https://search.maven.org/artifact/com.squareup.retrofit2/retrofit\n  - type: License\n    url: https://github.com/square/retrofit/blob/trunk/LICENSE.txt\n  - type: JavaDoc\n    url: https://square.github.io/retrofit/2.x/retrofit/\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/vocabulary/retrofit-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/apis.yml
tags:
- Android
- HTTP Client
- Java
- Kotlin
- Library
- Mobile
- Open Source
- SDK
- Square
url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/apis.yml
use_cases: []
---
