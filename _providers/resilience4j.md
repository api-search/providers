---
api_count: 1
apis:
- description: 'Resilience4j is a lightweight fault tolerance library for Java 17+ using functional programming patterns. It provides six core resilience patterns: Circuit Breaker (prevents cascading failures), Rate '
  name: Resilience4j
  slug: resilience4j
common:
- title: ''
  type: Website
  url: https://resilience4j.readme.io/
- title: ''
  type: Documentation
  url: https://resilience4j.readme.io/docs
- title: ''
  type: GettingStarted
  url: https://resilience4j.readme.io/docs/getting-started
- title: ''
  type: GitHub
  url: https://github.com/resilience4j/resilience4j
- title: ''
  type: GitHubOrganization
  url: https://github.com/resilience4j
- title: ''
  type: Releases
  url: https://github.com/resilience4j/resilience4j/releases
- title: ''
  type: Issues
  url: https://github.com/resilience4j/resilience4j/issues
- title: ''
  type: License
  url: https://github.com/resilience4j/resilience4j/blob/master/LICENSE.txt
- title: ''
  type: MavenCentral
  url: https://search.maven.org/search?q=io.github.resilience4j
- title: ''
  type: SpringBoot
  url: https://resilience4j.readme.io/docs/getting-started-3
- title: ''
  type: Micronaut
  url: https://resilience4j.readme.io/docs/getting-started-4
- title: ''
  type: SpringDemo
  url: https://github.com/resilience4j/resilience4j-spring-boot-demo
created: '2026-03-26'
description: Resilience4j is a lightweight fault tolerance library designed for Java 17+ and functional programming, providing higher-order functions to enhance functional interfaces with Circuit Breaker, Rate Limiter, Retry, Bulkhead, TimeLimiter, and Cache patterns. Designed as a replacement for Netflix Hystrix, it integrates with Spring Boot 2 and 3, Micronaut, RxJava, Spring Reactor, Micrometer, Prometheus, and Dropwizard Metrics. Used in production by Deutsche Telekom (400M+ requests/day), PlayStation Network, AOL, and Auto Trader Group.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Resilience4J Context
  property_count: 0
  slug: resilience4j-context
layout: provider
modified: '2026-05-02'
name: Resilience4j
skills: []
slug: resilience4j
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: resilience4j\nname: Resilience4j\ndescription: >-\n  Resilience4j is a lightweight fault tolerance library designed for Java 17+\n  and functional programming, providing higher-order functions to enhance\n  functional interfaces with Circuit Breaker, Rate Limiter, Retry, Bulkhead,\n  TimeLimiter, and Cache patterns. Designed as a replacement for Netflix Hystrix,\n  it integrates with Spring Boot 2 and 3, Micronaut, RxJava, Spring Reactor,\n  Micrometer, Prometheus, and Dropwizard Metrics. Used in production by Deutsche\n  Telekom (400M+ requests/day), PlayStation Network, AOL, and Auto Trader Group.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bulkhead\n  - Circuit Breaker\n  - Fault Tolerance\n  - Java\n  - Microservices\n  - Rate Limiter\n  - Resilience\n  - Retry\n  - Spring Boot\n  - Functional Programming\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/apis.yml\n\
  created: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: resilience4j:resilience4j\n    name: Resilience4j\n    description: >-\n      Resilience4j is a lightweight fault tolerance library for Java 17+ using\n      functional programming patterns. It provides six core resilience patterns:\n      Circuit Breaker (prevents cascading failures), Rate Limiter (controls\n      throughput), Bulkhead (isolates resources), Retry (automatic retries with\n      backoff), TimeLimiter (timeout handling), and Cache (result caching).\n      Spring Boot Actuator integration exposes management endpoints for\n      monitoring circuit breaker state, events, and metrics.\n    humanURL: https://resilience4j.readme.io/\n    tags:\n      - Bulkhead\n      - Circuit Breaker\n      - Fault Tolerance\n      - Java\n      - Microservices\n      - Rate Limiter\n      - Resilience\n      - Retry\n      - Spring Boot\n      - Functional Programming\n    properties:\n      - type:\
  \ Documentation\n        url: https://resilience4j.readme.io/docs\n      - type: GettingStarted\n        url: https://resilience4j.readme.io/docs/getting-started\n      - type: GitHub\n        url: https://github.com/resilience4j/resilience4j\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-schema/circuit-breaker-configuration.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-schema/retry-configuration.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-schema/rate-limiter-configuration.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-schema/bulkhead-configuration.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-schema/time-limiter-configuration.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-structure/resilience4j-circuit-breaker-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-structure/resilience4j-retry-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/json-ld/resilience4j-context.jsonld\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/vocabulary/resilience4j-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://resilience4j.readme.io/\n  - type: Documentation\n    url: https://resilience4j.readme.io/docs\n  - type: GettingStarted\n    url: https://resilience4j.readme.io/docs/getting-started\n  - type: GitHub\n    url: https://github.com/resilience4j/resilience4j\n\
  \  - type: GitHubOrganization\n    url: https://github.com/resilience4j\n  - type: Releases\n    url: https://github.com/resilience4j/resilience4j/releases\n  - type: Issues\n    url: https://github.com/resilience4j/resilience4j/issues\n  - type: License\n    url: https://github.com/resilience4j/resilience4j/blob/master/LICENSE.txt\n  - type: MavenCentral\n    url: https://search.maven.org/search?q=io.github.resilience4j\n  - type: SpringBoot\n    url: https://resilience4j.readme.io/docs/getting-started-3\n  - type: Micronaut\n    url: https://resilience4j.readme.io/docs/getting-started-4\n  - type: SpringDemo\n    url: https://github.com/resilience4j/resilience4j-spring-boot-demo\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/apis.yml
tags:
- Bulkhead
- Circuit Breaker
- Fault Tolerance
- Java
- Microservices
- Rate Limiter
- Resilience
- Retry
- Spring Boot
- Functional Programming
url: https://raw.githubusercontent.com/api-evangelist/resilience4j/refs/heads/main/apis.yml
use_cases: []
---
