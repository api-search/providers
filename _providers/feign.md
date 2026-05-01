---
api_count: 12
apis:
- description: Feign Core is the base library that processes annotated Java interfaces into templated HTTP requests. It defines the contract, encoder, decoder, and client abstractions used across the entire OpenFeig
  name: Feign Core
  slug: feign-core
- description: Feign Jackson module provides Jackson-based JSON encoding and decoding for Feign-annotated client interfaces, the most common serialization choice in JVM applications.
  name: Feign Jackson
  slug: feign-jackson
- description: Feign Gson module provides Google Gson-based JSON encoding and decoding for Feign clients, useful in projects already standardized on Gson.
  name: Feign Gson
  slug: feign-gson
- description: Feign OkHttp module replaces the default JDK HTTP transport with Square's OkHttp client, adding HTTP/2, connection pooling, and modern transport features.
  name: Feign OkHttp
  slug: feign-okhttp
- description: Feign Apache HttpClient module integrates Apache HttpComponents (HC5) as the underlying HTTP transport for Feign clients.
  name: Feign Apache HttpClient
  slug: feign-httpclient
- description: Feign Java 11 HTTP module uses the JDK 11+ standard HttpClient as the transport, supporting HTTP/2 and asynchronous calls without external dependencies.
  name: Feign Java 11 HTTP
  slug: feign-java11
- description: Feign Ribbon module integrates Netflix Ribbon for client-side load balancing across a list of HTTP servers.
  name: Feign Ribbon
  slug: feign-ribbon
- description: Feign Hystrix module wraps Feign client calls in Netflix Hystrix commands, adding circuit breaking, fallbacks, and bulkhead isolation.
  name: Feign Hystrix
  slug: feign-hystrix
- description: Feign JAX-RS modules let developers reuse JAX-RS 1.x, 2.x, 3.x, and 4.x annotations on Feign client interfaces instead of Feign's native annotation set.
  name: Feign JAX-RS
  slug: feign-jaxrs
- description: Feign SLF4J module routes Feign request and response logging through the SLF4J facade, integrating with the host application's logging backend.
  name: Feign SLF4J
  slug: feign-slf4j
- description: Feign Form module adds support for application/x-www-form-urlencoded and multipart/form-data request bodies, including file uploads.
  name: Feign Form
  slug: feign-form
- description: Feign Micrometer module exposes Feign client metrics (timings, counts, errors) through Micrometer for shipment to Prometheus, Datadog, and other monitoring backends.
  name: Feign Micrometer
  slug: feign-micrometer
common:
- title: ''
  type: Website
  url: https://github.com/OpenFeign/feign
- title: ''
  type: Documentation
  url: https://github.com/OpenFeign/feign#readme
- title: ''
  type: GitHub Organization
  url: https://github.com/OpenFeign
- title: ''
  type: Issues
  url: https://github.com/OpenFeign/feign/issues
- title: ''
  type: Releases
  url: https://github.com/OpenFeign/feign/releases
- title: ''
  type: License
  url: https://github.com/OpenFeign/feign/blob/master/LICENSE
- title: ''
  type: Maven Central
  url: https://central.sonatype.com/namespace/io.github.openfeign
created: '2026-03-27'
description: Feign (OpenFeign) is a declarative Java HTTP client binder inspired by Retrofit, JAX-RS, and WebSocket. It turns annotated interfaces into templated HTTP requests with pluggable encoders, decoders, error handlers, and HTTP transports. The OpenFeign organization maintains a large set of modules covering serialization (Jackson, Gson, Moshi, FastJSON2, JAXB, SAX, SOAP), HTTP transports (OkHttp, Apache HttpClient, Java 11 client, Ribbon), JAX-RS contracts, resilience (Hystrix), logging (SLF4J), form encoding, GraphQL, and metrics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Feign
skills: []
slug: feign
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: feign\nname: Feign\ndescription: >-\n  Feign (OpenFeign) is a declarative Java HTTP client binder inspired by\n  Retrofit, JAX-RS, and WebSocket. It turns annotated interfaces into\n  templated HTTP requests with pluggable encoders, decoders, error handlers,\n  and HTTP transports. The OpenFeign organization maintains a large set of\n  modules covering serialization (Jackson, Gson, Moshi, FastJSON2, JAXB,\n  SAX, SOAP), HTTP transports (OkHttp, Apache HttpClient, Java 11 client,\n  Ribbon), JAX-RS contracts, resilience (Hystrix), logging (SLF4J), form\n  encoding, GraphQL, and metrics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - HTTP Client\n  - Java\n  - JVM\n  - Open Source\n  - REST\n  - SDKs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/feign/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: feign:feign-core\n    name: Feign Core\n    description: >-\n      Feign Core is the base library that processes annotated Java\n      interfaces into templated HTTP requests. It defines the contract,\n      encoder, decoder, and client abstractions used across the entire\n      OpenFeign ecosystem.\n    humanURL: https://github.com/OpenFeign/feign\n    tags:\n      - HTTP Client\n      - Java\n      - Core\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign#readme\n      - type: Getting Started\n        url: https://github.com/OpenFeign/feign#basics\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign\n      - type: Maven Central\n        url: https://central.sonatype.com/artifact/io.github.openfeign/feign-core\n  - aid: feign:feign-jackson\n    name: Feign Jackson\n    description: >-\n      Feign Jackson module provides Jackson-based JSON encoding and decoding\n      for Feign-annotated client interfaces, the\
  \ most common serialization\n      choice in JVM applications.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/jackson\n    tags:\n      - JSON\n      - Jackson\n      - Serialization\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/jackson\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/jackson\n  - aid: feign:feign-gson\n    name: Feign Gson\n    description: >-\n      Feign Gson module provides Google Gson-based JSON encoding and decoding\n      for Feign clients, useful in projects already standardized on Gson.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/gson\n    tags:\n      - JSON\n      - Gson\n      - Serialization\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/gson\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/gson\n  - aid: feign:feign-okhttp\n  \
  \  name: Feign OkHttp\n    description: >-\n      Feign OkHttp module replaces the default JDK HTTP transport with\n      Square's OkHttp client, adding HTTP/2, connection pooling, and modern\n      transport features.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/okhttp\n    tags:\n      - HTTP Client\n      - Transport\n      - OkHttp\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/okhttp\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/okhttp\n  - aid: feign:feign-httpclient\n    name: Feign Apache HttpClient\n    description: >-\n      Feign Apache HttpClient module integrates Apache HttpComponents (HC5)\n      as the underlying HTTP transport for Feign clients.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/httpclient\n    tags:\n      - HTTP Client\n      - Transport\n      - Apache\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/httpclient\n\
  \      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/httpclient\n  - aid: feign:feign-java11\n    name: Feign Java 11 HTTP\n    description: >-\n      Feign Java 11 HTTP module uses the JDK 11+ standard HttpClient as the\n      transport, supporting HTTP/2 and asynchronous calls without external\n      dependencies.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/java11\n    tags:\n      - HTTP Client\n      - Transport\n      - Java 11\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/java11\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/java11\n  - aid: feign:feign-ribbon\n    name: Feign Ribbon\n    description: >-\n      Feign Ribbon module integrates Netflix Ribbon for client-side load\n      balancing across a list of HTTP servers.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/ribbon\n    tags:\n      - Load Balancing\n\
  \      - Netflix\n      - Resilience\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/ribbon\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/ribbon\n  - aid: feign:feign-hystrix\n    name: Feign Hystrix\n    description: >-\n      Feign Hystrix module wraps Feign client calls in Netflix Hystrix\n      commands, adding circuit breaking, fallbacks, and bulkhead isolation.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/hystrix\n    tags:\n      - Resilience\n      - Circuit Breaker\n      - Netflix\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/hystrix\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/hystrix\n  - aid: feign:feign-jaxrs\n    name: Feign JAX-RS\n    description: >-\n      Feign JAX-RS modules let developers reuse JAX-RS 1.x, 2.x, 3.x, and\n      4.x annotations on Feign\
  \ client interfaces instead of Feign's native\n      annotation set.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/jaxrs\n    tags:\n      - JAX-RS\n      - Annotations\n      - Contracts\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/jaxrs\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/jaxrs\n  - aid: feign:feign-slf4j\n    name: Feign SLF4J\n    description: >-\n      Feign SLF4J module routes Feign request and response logging through\n      the SLF4J facade, integrating with the host application's logging\n      backend.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/slf4j\n    tags:\n      - Logging\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/slf4j\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/slf4j\n  - aid: feign:feign-form\n\
  \    name: Feign Form\n    description: >-\n      Feign Form module adds support for application/x-www-form-urlencoded\n      and multipart/form-data request bodies, including file uploads.\n    humanURL: https://github.com/OpenFeign/feign-form\n    tags:\n      - Forms\n      - Multipart\n      - File Upload\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign-form\n      - type: Source Code\n        url: https://github.com/OpenFeign/feign-form\n  - aid: feign:feign-micrometer\n    name: Feign Micrometer\n    description: >-\n      Feign Micrometer module exposes Feign client metrics (timings, counts,\n      errors) through Micrometer for shipment to Prometheus, Datadog, and\n      other monitoring backends.\n    humanURL: https://github.com/OpenFeign/feign/tree/master/micrometer\n    tags:\n      - Metrics\n      - Observability\n      - Micrometer\n    properties:\n      - type: Documentation\n        url: https://github.com/OpenFeign/feign/tree/master/micrometer\n\
  \      - type: Source Code\n        url: https://github.com/OpenFeign/feign/tree/master/micrometer\ncommon:\n  - type: Website\n    url: https://github.com/OpenFeign/feign\n  - type: Documentation\n    url: https://github.com/OpenFeign/feign#readme\n  - type: GitHub Organization\n    url: https://github.com/OpenFeign\n  - type: Issues\n    url: https://github.com/OpenFeign/feign/issues\n  - type: Releases\n    url: https://github.com/OpenFeign/feign/releases\n  - type: License\n    url: https://github.com/OpenFeign/feign/blob/master/LICENSE\n  - type: Maven Central\n    url: https://central.sonatype.com/namespace/io.github.openfeign\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/feign/refs/heads/main/apis.yml
tags:
- HTTP Client
- Java
- JVM
- Open Source
- REST
- SDKs
url: https://raw.githubusercontent.com/api-evangelist/feign/refs/heads/main/apis.yml
use_cases: []
---
