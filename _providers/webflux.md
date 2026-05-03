---
api_count: 8
api_specs:
- filename: webflux-websocket-asyncapi.yml
  format: yaml
  label: Spring WebFlux WebSocket
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/asyncapi/webflux-websocket-asyncapi.yml
apis:
- description: Reactive web framework providing annotated controllers, functional endpoints, dispatcher handler, and the full reactive request/response processing pipeline. Supports non-blocking I/O with Reactor Mon
  name: Spring WebFlux Core
  slug: ''
- description: Reactive, non-blocking HTTP client for consuming REST services and other APIs. Supports builder-based configuration, request/response filters, error handling, streaming, and bridging to blocking opera
  name: Spring WebFlux WebClient
  slug: ''
- description: 'Functional programming model for routing and request handling in WebFlux. RouterFunction and HandlerFunction provide a lightweight, lambda-based alternative to annotated controllers for defining HTTP '
  name: Spring WebFlux Router Functions
  slug: ''
- description: Reactive WebSocket support for full-duplex, bidirectional communication in WebFlux applications. Provides WebSocketHandler, WebSocketSession, and integration with STOMP messaging protocol.
  name: Spring WebFlux WebSocket
  slug: ''
- description: Integration with RSocket binary protocol for reactive, message-driven communication between microservices. Supports request-response, request-stream, fire-and-forget, and channel interaction models.
  name: Spring WebFlux RSocket
  slug: ''
- description: Project Reactor is the foundational reactive library powering Spring WebFlux. Provides Mono (0-1 element) and Flux (0-N element) publisher types implementing the Reactive Streams specification with co
  name: Reactor Core
  slug: ''
- description: Declarative HTTP service interface client allowing annotation-based HTTP client definitions with @HttpExchange. Simplifies HTTP client creation with generated proxies backed by WebClient.
  name: Spring WebFlux HTTP Service Client
  slug: ''
- description: Testing support for WebFlux applications including WebTestClient for integration testing of server endpoints, controller tests, and end-to-end testing with a full Spring application context.
  name: Spring WebFlux Testing
  slug: ''
asyncapis:
- description: AsyncAPI specification describing WebSocket communication patterns for Spring WebFlux applications. Spring WebFlux provides reactive WebSocket support via WebSocketHandler and WebSocketSession, enabli
  name: Spring WebFlux WebSocket API
  slug: webflux-websocket-asyncapi
common:
- title: ''
  type: Blog
  url: https://spring.io/blog/category/engineering
- title: ''
  type: Support
  url: https://spring.io/support
- title: ''
  type: Community
  url: https://spring.io/community
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-webflux
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-projects
- title: ''
  type: Twitter
  url: https://twitter.com/springcentral
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/SpringSourceDev
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework/spring-webflux
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-framework/releases
- title: ''
  type: Changelog
  url: https://github.com/spring-projects/spring-framework/wiki/Spring-Framework-Versions
- title: ''
  type: JSONLD
  url: json-ld/webflux-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/webflux-vocabulary.yml
created: '2024-01-01'
description: Spring WebFlux is a fully non-blocking, reactive-stack web framework built into Spring Framework 5.0+. It enables building highly scalable, asynchronous web applications using the Reactive Streams API with Project Reactor. WebFlux supports annotated controllers, functional routing endpoints, WebSocket communication, RSocket protocol, and a powerful reactive HTTP client (WebClient) for consuming APIs.
features: []
image: https://spring.io/img/projects/spring-framework.svg
integrations: []
jsonld:
- class_count: 0
  name: Webflux Context
  property_count: 24
  slug: webflux-context
layout: provider
modified: '2026-05-03'
name: Spring WebFlux
skills: []
slug: webflux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: webflux\nname: Spring WebFlux\ndescription: >-\n  Spring WebFlux is a fully non-blocking, reactive-stack web framework built into Spring\n  Framework 5.0+. It enables building highly scalable, asynchronous web applications\n  using the Reactive Streams API with Project Reactor. WebFlux supports annotated\n  controllers, functional routing endpoints, WebSocket communication, RSocket protocol,\n  and a powerful reactive HTTP client (WebClient) for consuming APIs.\nimage: https://spring.io/img/projects/spring-framework.svg\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/apis.yml\napis:\n  - name: Spring WebFlux Core\n    description: >-\n      Reactive web framework providing annotated controllers, functional endpoints,\n      dispatcher handler, and the full reactive request/response processing pipeline.\n      Supports non-blocking I/O with Reactor Mono and\
  \ Flux types.\n    image: https://spring.io/img/projects/spring-framework.svg\n    humanUrl: https://docs.spring.io/spring-framework/reference/web/webflux.html\n    baseUrl: https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/reactive/\n    tags:\n      - Annotated Controllers\n      - Dispatcher Handler\n      - Functional Endpoints\n      - Non-Blocking\n      - Reactive\n      - Spring Framework\n      - WebFlux\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/web/webflux.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/reactive/package-summary.html\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-framework/tree/main/spring-webflux\n      - type: Getting Started\n        url: https://spring.io/guides/gs/reactive-rest-service/\n      - type: Maven Repository\n \
  \       url: https://mvnrepository.com/artifact/org.springframework/spring-webflux\n\n  - name: Spring WebFlux WebClient\n    description: >-\n      Reactive, non-blocking HTTP client for consuming REST services and other APIs.\n      Supports builder-based configuration, request/response filters, error handling,\n      streaming, and bridging to blocking operations. Replaces the deprecated RestTemplate.\n    image: https://spring.io/img/projects/spring-framework.svg\n    humanUrl: https://docs.spring.io/spring-framework/reference/web/webflux-webclient.html\n    tags:\n      - HTTP Client\n      - Non-Blocking\n      - Reactive\n      - REST\n      - WebClient\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/web/webflux-webclient.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/reactive/function/client/WebClient.html\n      - type: Tutorial\n\
  \        url: https://www.baeldung.com/spring-5-webclient\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-framework/tree/main/spring-webflux\n      - type: JSONSchema\n        url: json-schema/webflux-webclient-request-schema.json\n      - type: JSONSchema\n        url: json-schema/webflux-webclient-response-schema.json\n      - type: JSONStructure\n        url: json-structure/webflux-webclient-request-structure.json\n\n  - name: Spring WebFlux Router Functions\n    description: >-\n      Functional programming model for routing and request handling in WebFlux.\n      RouterFunction and HandlerFunction provide a lightweight, lambda-based\n      alternative to annotated controllers for defining HTTP endpoints.\n    humanUrl: https://docs.spring.io/spring-framework/reference/web/webflux-functional.html\n    tags:\n      - Functional Programming\n      - Handler Functions\n      - Reactive\n      - Router Functions\n      - Routing\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/web/webflux-functional.html\n      - type: Code Examples\n        url: https://github.com/spring-projects/spring-framework/tree/main/spring-webflux/src/test/java/org/springframework/web/reactive/function\n      - type: JSONSchema\n        url: json-schema/webflux-router-function-schema.json\n\n  - name: Spring WebFlux WebSocket\n    description: >-\n      Reactive WebSocket support for full-duplex, bidirectional communication\n      in WebFlux applications. Provides WebSocketHandler, WebSocketSession, and\n      integration with STOMP messaging protocol.\n    humanUrl: https://docs.spring.io/spring-framework/reference/web/webflux-websocket.html\n    tags:\n      - Bidirectional\n      - Full Duplex\n      - Messaging\n      - Real-Time\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/web/webflux-websocket.html\n   \
  \   - type: Code Examples\n        url: https://spring.io/guides/gs/messaging-stomp-websocket/\n      - type: AsyncAPI\n        url: asyncapi/webflux-websocket-asyncapi.yml\n\n  - name: Spring WebFlux RSocket\n    description: >-\n      Integration with RSocket binary protocol for reactive, message-driven\n      communication between microservices. Supports request-response,\n      request-stream, fire-and-forget, and channel interaction models.\n    humanUrl: https://docs.spring.io/spring-framework/reference/rsocket.html\n    tags:\n      - Binary Protocol\n      - Microservices\n      - Reactive\n      - RSocket\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/rsocket.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/messaging/rsocket/package-summary.html\n\n  - name: Reactor Core\n    description: >-\n      Project Reactor\
  \ is the foundational reactive library powering Spring WebFlux.\n      Provides Mono (0-1 element) and Flux (0-N element) publisher types implementing\n      the Reactive Streams specification with composable operators.\n    humanUrl: https://projectreactor.io/\n    baseUrl: https://repo1.maven.org/maven2/io/projectreactor/reactor-core/\n    tags:\n      - Flux\n      - Mono\n      - Project Reactor\n      - Reactive Streams\n      - Reactor\n    properties:\n      - type: Documentation\n        url: https://projectreactor.io/docs/core/release/reference/\n      - type: API Reference\n        url: https://projectreactor.io/docs/core/release/api/\n      - type: GitHub Repository\n        url: https://github.com/reactor/reactor-core\n      - type: Learning Materials\n        url: https://projectreactor.io/learn\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/io.projectreactor/reactor-core\n\n  - name: Spring WebFlux HTTP Service Client\n    description: >-\n\
  \      Declarative HTTP service interface client allowing annotation-based HTTP\n      client definitions with @HttpExchange. Simplifies HTTP client creation\n      with generated proxies backed by WebClient.\n    humanUrl: https://docs.spring.io/spring-framework/reference/integration/rest-clients.html#rest-http-interface\n    tags:\n      - Declarative\n      - HTTP Client\n      - HTTP Interface\n      - Reactive\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/integration/rest-clients.html#rest-http-interface\n\n  - name: Spring WebFlux Testing\n    description: >-\n      Testing support for WebFlux applications including WebTestClient for\n      integration testing of server endpoints, controller tests, and end-to-end\n      testing with a full Spring application context.\n    humanUrl: https://docs.spring.io/spring-framework/reference/testing/webtestclient.html\n    tags:\n      - Integration Testing\n    \
  \  - Reactive Testing\n      - Spring Boot Test\n      - Testing\n      - WebTestClient\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/reference/testing/webtestclient.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/test/web/reactive/server/WebTestClient.html\n\ncommon:\n  - type: Blog\n    url: https://spring.io/blog/category/engineering\n  - type: Support\n    url: https://spring.io/support\n  - type: Community\n    url: https://spring.io/community\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-webflux\n  - type: GitHub Organization\n    url: https://github.com/spring-projects\n  - type: Twitter\n    url: https://twitter.com/springcentral\n  - type: YouTube\n    url: https://www.youtube.com/user/SpringSourceDev\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework/spring-webflux\n\
  \  - type: Releases\n    url: https://github.com/spring-projects/spring-framework/releases\n  - type: Changelog\n    url: https://github.com/spring-projects/spring-framework/wiki/Spring-Framework-Versions\n  - type: JSONLD\n    url: json-ld/webflux-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/webflux-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\ntags:\n  - Java\n  - Microservices\n  - Non-Blocking IO\n  - Reactive Programming\n  - REST API\n  - Spring Boot\n  - Spring Framework\n  - WebFlux\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/apis.yml
tags:
- Java
- Microservices
- Non-Blocking IO
- Reactive Programming
- REST API
- Spring Boot
- Spring Framework
- WebFlux
url: https://raw.githubusercontent.com/api-evangelist/webflux/refs/heads/main/apis.yml
use_cases: []
---
