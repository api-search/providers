---
api_count: 2
api_specs:
- filename: spring-cloud-gateway-actuator-openapi.yml
  format: yaml
  label: Spring Cloud Gateway Actuator API
  slug: spring-cloud-gateway-actuator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-gateway/refs/heads/main/openapi/spring-cloud-gateway-actuator-openapi.yml
apis:
- description: Runtime management API for Spring Cloud Gateway exposing endpoints for retrieving, creating, updating, and deleting route definitions. Also provides access to global filters, route filter factories, r
  name: Spring Cloud Gateway Actuator API
  slug: spring-cloud-gateway-actuator
- description: Core routing and filtering capabilities including predicate factories (Path, Host, Method, Header, Query, Cookie, Weight, RemoteAddr), gateway filter factories (AddRequestHeader, RewritePath, RequestR
  name: Spring Cloud Gateway Core
  slug: spring-cloud-gateway-core
capabilities:
- description: Unified capability for managing an API gateway built on Spring Cloud Gateway. Enables dynamic route creation, predicate and filter management, cache refresh, and runtime gateway inspection for platfor
  name: Spring Cloud Gateway API Gateway Management
  slug: api-gateway-management
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-cloud-gateway
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/
- title: ''
  type: GitHub
  url: https://github.com/spring-cloud/spring-cloud-gateway
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-cloud
- title: ''
  type: Issues
  url: https://github.com/spring-cloud/spring-cloud-gateway/issues
- title: ''
  type: Releases
  url: https://github.com/spring-cloud/spring-cloud-gateway/releases
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-cloud-gateway
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-gateway-server
- title: ''
  type: Vocabulary
  url: vocabulary/spring-cloud-gateway-vocabulary.yml
created: '2026-03-16'
description: Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit breaking, rate limiting, and runtime route management through an Actuator API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Spring Cloud Gateway Context
  property_count: 9
  slug: spring-cloud-gateway-context
layout: provider
modified: '2026-05-02'
name: Spring Cloud Gateway
rules:
- name: Spring Cloud Gateway API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: spring-cloud-gateway-rules
skills: []
slug: spring-cloud-gateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-cloud-gateway\nname: Spring Cloud Gateway\ndescription: >-\n  Spring Cloud Gateway provides an intelligent, programmable router built on Spring\n  WebFlux that serves as the entry point to microservice architectures. It offers\n  routing, predicate evaluation, filter chaining, load balancing, circuit breaking,\n  rate limiting, and runtime route management through an Actuator API.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://spring.io/projects/spring-cloud-gateway\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - API Gateway\n  - Circuit Breaker\n  - Load Balancing\n  - Microservices\n  - Rate Limiting\n  - Routing\n  - Spring\n  - Spring WebFlux\napis:\n  - aid: spring-cloud-gateway:spring-cloud-gateway-actuator\n    name: Spring Cloud Gateway Actuator API\n    description: >-\n      Runtime management API for Spring Cloud Gateway exposing endpoints for\n      retrieving,\
  \ creating, updating, and deleting route definitions. Also provides\n      access to global filters, route filter factories, route predicate factories,\n      and cache refresh capabilities.\n    humanURL: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api\n    baseURL: http://localhost:8080/actuator/gateway\n    tags:\n      - Actuator\n      - API Gateway\n      - Filters\n      - Management\n      - Monitoring\n      - Routes\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api\n      - type: OpenAPI\n        url: openapi/spring-cloud-gateway-actuator-openapi.yml\n      - type: JSONSchema\n        url: json-schema/spring-cloud-gateway-route-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-cloud-gateway-route-structure.json\n      - type: JSONLDContext\n        url: json-ld/spring-cloud-gateway-context.jsonld\n      - type: SpectralRules\n\
  \        url: rules/spring-cloud-gateway-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/api-gateway-management.yaml\n  - aid: spring-cloud-gateway:spring-cloud-gateway-core\n    name: Spring Cloud Gateway Core\n    description: >-\n      Core routing and filtering capabilities including predicate factories (Path,\n      Host, Method, Header, Query, Cookie, Weight, RemoteAddr), gateway filter factories\n      (AddRequestHeader, RewritePath, RequestRateLimiter, CircuitBreaker, Retry),\n      and global filters for proxying requests to downstream services.\n    humanURL: https://spring.io/projects/spring-cloud-gateway\n    baseURL: http://localhost:8080\n    tags:\n      - API Gateway\n      - Filtering\n      - Load Balancing\n      - Predicates\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/\n      - type: Getting Started\n        url: https://spring.io/projects/spring-cloud-gateway#learn\n\
  \      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-gateway\n      - type: Releases\n        url: https://github.com/spring-cloud/spring-cloud-gateway/releases\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-cloud-gateway\n  - type: Documentation\n    url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/\n  - type: GitHub\n    url: https://github.com/spring-cloud/spring-cloud-gateway\n  - type: GitHub Organization\n    url: https://github.com/spring-cloud\n  - type: Issues\n    url: https://github.com/spring-cloud/spring-cloud-gateway/issues\n  - type: Releases\n    url: https://github.com/spring-cloud/spring-cloud-gateway/releases\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-cloud-gateway\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-gateway-server\n  - type: Vocabulary\n    url: vocabulary/spring-cloud-gateway-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-gateway/refs/heads/main/apis.yml
tags:
- API Gateway
- Circuit Breaker
- Load Balancing
- Microservices
- Rate Limiting
- Routing
- Spring
- Spring WebFlux
url: https://spring.io/projects/spring-cloud-gateway
use_cases: []
---
