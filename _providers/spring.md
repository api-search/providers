---
api_count: 6
api_specs:
- filename: spring-boot-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/openapi/spring-boot-actuator-openapi.yml
- filename: spring-initializr-api-openapi.yml
  format: yaml
  label: Spring Initializr API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/openapi/spring-initializr-api-openapi.yml
apis:
- description: The Spring Boot Actuator API provides production-ready endpoints for monitoring and managing Spring Boot applications. It exposes health checks, metrics, environment information, thread dumps, HTTP tr
  name: Spring Boot Actuator API
  slug: ''
- description: The Spring Initializr REST API enables programmatic generation of Spring Boot project scaffolding. It provides endpoints for listing available dependencies, project types, and boot versions, as well a
  name: Spring Initializr API
  slug: ''
- description: Spring Data REST automatically exports Spring Data repository interfaces as RESTful hypermedia-driven APIs using HAL (Hypertext Application Language). It enables CRUD operations on domain entities thr
  name: Spring Data REST API
  slug: ''
- description: 'Spring Cloud Gateway provides an API Gateway built on Spring WebFlux and Reactor. It offers route configuration, request/response filtering, load balancing, circuit breaking, rate limiting, and retry '
  name: Spring Cloud Gateway API
  slug: ''
- description: Spring Authorization Server provides a full OAuth 2.1 and OpenID Connect 1.0 authorization server implementation built on Spring Security. It supports authorization code flow, client credentials, devi
  name: Spring Authorization Server API
  slug: ''
- description: Spring AI provides a Spring-friendly API and abstractions for building AI-powered applications. It offers a unified ChatClient API for interacting with AI models (OpenAI, Anthropic, Google Gemini, Oll
  name: Spring AI API
  slug: ''
common:
- title: ''
  type: Website
  url: https://spring.io
- title: ''
  type: GitHub
  url: https://github.com/spring-projects
- title: ''
  type: Documentation
  url: https://docs.spring.io
- title: ''
  type: Blog
  url: https://spring.io/blog
- title: ''
  type: Community
  url: https://spring.io/community
- title: ''
  type: Guides
  url: https://spring.io/guides
- title: ''
  type: Events
  url: https://spring.io/events
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-framework/releases
created: '2026-05-02'
description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, messaging, cloud-native patterns, and AI integrations. Spring Boot enables rapid application development with embedded servers and auto-configuration. Spring is maintained by VMware and hosted under the Spring Projects GitHub organization.
features: []
image: https://spring.io/img/spring-logo.svg
integrations: []
jsonld:
- class_count: 23
  name: Spring Context
  property_count: 6
  slug: spring-context
layout: provider
modified: '2026-05-02'
name: Spring Framework
rules:
- name: Spring Framework API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 8
  slug: spring-rules
skills: []
slug: spring
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring\nname: Spring Framework\ndescription: >-\n  Spring is the leading open-source application framework for Java. The Spring\n  ecosystem provides a comprehensive programming and configuration model for modern\n  Java-based enterprise applications, covering web MVC, data access, security,\n  messaging, cloud-native patterns, and AI integrations. Spring Boot enables rapid\n  application development with embedded servers and auto-configuration. Spring is\n  maintained by VMware and hosted under the Spring Projects GitHub organization.\nimage: https://spring.io/img/spring-logo.svg\nurl: https://spring.io\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n  - name: Spring Boot Actuator API\n    description: >-\n      The Spring Boot Actuator API provides production-ready endpoints for monitoring\n      and managing Spring Boot applications. It exposes health checks, metrics,\n      environment information, thread dumps, HTTP traces, and application info\n      via REST\
  \ endpoints. The Actuator API is OpenAPI-documented and follows\n      standard HTTP REST conventions.\n    image: https://spring.io/img/projects/spring-boot.svg\n    humanUrl: https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html\n    baseUrl: https://api.spring.io/boot/actuator\n    tags:\n      - Monitoring\n      - Actuator\n      - Operations\n      - Spring Boot\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html\n      - type: OpenAPI\n        url: openapi/spring-boot-actuator-openapi.yml\n      - type: GitHub\n        url: https://github.com/spring-projects/spring-boot\n      - type: GettingStarted\n        url: https://spring.io/guides/gs/spring-boot/\n      - type: JSONSchema\n        url: json-schema/spring-actuator-health-schema.json\n      - type: SpectralRules\n        url: rules/spring-rules.yml\n      - type: Vocabulary\n        url: vocabulary/spring-vocabulary.yml\n\
  \    contact:\n      - type: Support\n        url: https://spring.io/support\n  - name: Spring Initializr API\n    description: >-\n      The Spring Initializr REST API enables programmatic generation of Spring Boot\n      project scaffolding. It provides endpoints for listing available dependencies,\n      project types, and boot versions, as well as generating ready-to-use project\n      archives in zip or tar.gz format. Used by IDEs (IntelliJ IDEA, Eclipse STS,\n      VS Code) and CLI tools to bootstrap new Spring projects.\n    humanUrl: https://start.spring.io\n    baseUrl: https://start.spring.io\n    tags:\n      - Bootstrap\n      - Code Generation\n      - Developer Tools\n      - Project Generator\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/initializr/docs/current/reference/html/\n      - type: OpenAPI\n        url: openapi/spring-initializr-api-openapi.yml\n      - type: OpenAPIUpstream\n        url: https://start.spring.io/v3/api-docs\n\
  \      - type: GitHub\n        url: https://github.com/spring-io/initializr\n      - type: WebInterface\n        url: https://start.spring.io\n      - type: JSONSchema\n        url: json-schema/spring-boot-application-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-boot-application-structure.json\n      - type: JSONLD\n        url: json-ld/spring-context.jsonld\n  - name: Spring Data REST API\n    description: >-\n      Spring Data REST automatically exports Spring Data repository interfaces as\n      RESTful hypermedia-driven APIs using HAL (Hypertext Application Language).\n      It enables CRUD operations on domain entities through discoverable REST\n      endpoints without writing controller code. The API supports HATEOAS linking,\n      projections, validation, and event hooks.\n    humanUrl: https://spring.io/projects/spring-data-rest\n    baseUrl: https://api.spring.io/data/rest\n    tags:\n      - CRUD\n      - Data\n      - HATEOAS\n      - Hypermedia\n\
  \      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n      - type: APIReference\n        url: https://docs.spring.io/spring-data/rest/docs/current/api/\n      - type: GitHub\n        url: https://github.com/spring-projects/spring-data-rest\n      - type: HALBrowser\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/#tools.hal-explorer\n  - name: Spring Cloud Gateway API\n    description: >-\n      Spring Cloud Gateway provides an API Gateway built on Spring WebFlux and\n      Reactor. It offers route configuration, request/response filtering, load\n      balancing, circuit breaking, rate limiting, and retry capabilities via a\n      fluent Java DSL or YAML configuration. The Actuator endpoint exposes live\n      route and filter information.\n    humanUrl: https://spring.io/projects/spring-cloud-gateway\n    baseUrl: https://api.spring.io/gateway\n    tags:\n      -\
  \ API Gateway\n      - Cloud\n      - Load Balancing\n      - Routing\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-gateway\n      - type: Samples\n        url: https://github.com/spring-cloud/spring-cloud-gateway/tree/main/spring-cloud-gateway-sample\n  - name: Spring Authorization Server API\n    description: >-\n      Spring Authorization Server provides a full OAuth 2.1 and OpenID Connect 1.0\n      authorization server implementation built on Spring Security. It supports\n      authorization code flow, client credentials, device authorization, token\n      introspection, and token revocation. Exposes standard OAuth 2 endpoints.\n    humanUrl: https://spring.io/projects/spring-authorization-server\n    baseUrl: https://api.spring.io/oauth\n    tags:\n      - Authorization\n      - OAuth 2.0\n      -\
  \ OpenID Connect\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-authorization-server/reference/\n      - type: GitHub\n        url: https://github.com/spring-projects/spring-authorization-server\n      - type: OAuthGuide\n        url: https://spring.io/guides/tutorials/spring-boot-oauth2/\n  - name: Spring AI API\n    description: >-\n      Spring AI provides a Spring-friendly API and abstractions for building\n      AI-powered applications. It offers a unified ChatClient API for interacting\n      with AI models (OpenAI, Anthropic, Google Gemini, Ollama, and others), along\n      with vector store integrations, prompt templates, output parsers, and function\n      calling support. Follows portable, modular Spring design principles.\n    humanUrl: https://spring.io/projects/spring-ai\n    baseUrl: https://api.spring.io/ai\n    tags:\n      - AI\n      - Chatbot\n      - GenAI\n      - LLM\n      - Machine Learning\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.spring.io/spring-ai/reference/\n      - type: GitHub\n        url: https://github.com/spring-projects/spring-ai\n      - type: GettingStarted\n        url: https://docs.spring.io/spring-ai/reference/getting-started.html\ncommon:\n  - type: Website\n    url: https://spring.io\n  - type: GitHub\n    url: https://github.com/spring-projects\n  - type: Documentation\n    url: https://docs.spring.io\n  - type: Blog\n    url: https://spring.io/blog\n  - type: Community\n    url: https://spring.io/community\n  - type: Guides\n    url: https://spring.io/guides\n  - type: Events\n    url: https://spring.io/events\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework\n  - type: Releases\n    url: https://github.com/spring-projects/spring-framework/releases\nmaintainers:\n  - name: Spring Team at VMware\n    email: spring-team@vmware.com\n    url: https://spring.io/team\ntags:\n  - AI\n  - Cloud Native\n\
  \  - Enterprise\n  - Framework\n  - Java\n  - Microservices\n  - Open Source\n  - REST\n  - Spring Boot\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/apis.yml
tags:
- AI
- Cloud Native
- Enterprise
- Framework
- Java
- Microservices
- Open Source
- REST
- Spring Boot
url: https://spring.io
use_cases: []
---
