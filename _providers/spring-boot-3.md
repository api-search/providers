---
api_count: 5
api_specs:
- filename: api-docs
  format: yaml
  label: Spring Boot Core API
  slug: ''
  spec_type: OpenAPI
  url: https://api.example.com/v3/api-docs
- filename: api-docs
  format: yaml
  label: Spring Web MVC API
  slug: ''
  spec_type: OpenAPI
  url: https://api.example.com/v3/api-docs
apis:
- description: Core Spring Boot 3 framework APIs for application development.
  name: Spring Boot Core API
  slug: ''
- description: Production-ready features for monitoring and managing Spring Boot applications.
  name: Spring Boot Actuator API
  slug: ''
- description: Web MVC framework for building web applications and RESTful services.
  name: Spring Web MVC API
  slug: ''
- description: Automatically expose Spring Data repositories as REST resources.
  name: Spring Data REST API
  slug: ''
- description: Security framework for authentication and authorization.
  name: Spring Security API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://spring.io/guides/gs/spring-boot/
- title: ''
  type: GitHub Repository
  url: https://github.com/spring-projects/spring-boot
- title: ''
  type: Release Notes
  url: https://github.com/spring-projects/spring-boot/releases
- title: ''
  type: Migration Guide
  url: https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide
- title: ''
  type: Community
  url: https://spring.io/community
- title: ''
  type: Blog
  url: https://spring.io/blog
- title: ''
  type: Twitter
  url: https://twitter.com/springboot
created: '2024-01-15'
description: Comprehensive collection of Spring Boot 3 framework APIs and resources.
features: []
image: https://spring.io/img/spring-logo.svg
integrations: []
layout: provider
modified: '2026-03-16'
name: Spring Boot 3
skills: []
slug: spring-boot-3
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Boot 3\ndescription: >-\n  Comprehensive collection of Spring Boot 3 framework APIs and resources.\nimage: https://spring.io/img/spring-logo.svg\nurl: https://spring.io/projects/spring-boot\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.16'\napis:\n  - name: Spring Boot Core API\n    description: >-\n      Core Spring Boot 3 framework APIs for application development.\n    image: https://spring.io/img/spring-boot-logo.svg\n    humanUrl: https://docs.spring.io/spring-boot/docs/3.0.x/reference/html/\n    baseUrl: https://api.example.com/v3\n    tags:\n      - Framework\n      - Java\n      - Microservices\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.0.x/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.0.x/api/\n      - type: OpenAPI\n        url: https://api.example.com/v3/api-docs\n      - type: Swagger\
  \ UI\n        url: https://api.example.com/swagger-ui.html\n    contact:\n      - type: GitHub\n        url: https://github.com/spring-projects/spring-boot\n      - type: Support\n        url: https://spring.io/support\n      - type: Stack Overflow\n        url: https://stackoverflow.com/questions/tagged/spring-boot\n  - name: Spring Boot Actuator API\n    description: >-\n      Production-ready features for monitoring and managing Spring Boot applications.\n    humanUrl: https://docs.spring.io/spring-boot/docs/3.0.x/reference/html/actuator.html\n    baseUrl: https://api.example.com/actuator\n    tags:\n      - Health Check\n      - Management\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.0.x/reference/html/actuator.html\n      - type: API Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.0.x/actuator-api/htmlsingle/\n      - type: Endpoints\n        url: https://api.example.com/actuator\n\
  \    endpoints:\n      - path: /health\n        description: Application health information\n      - path: /metrics\n        description: Application metrics\n      - path: /info\n        description: Application information\n      - path: /env\n        description: Environment properties\n      - path: /loggers\n        description: Logger configuration\n  - name: Spring Web MVC API\n    description: >-\n      Web MVC framework for building web applications and RESTful services.\n    humanUrl: https://docs.spring.io/spring-framework/docs/6.0.x/reference/html/web.html\n    baseUrl: https://api.example.com/api\n    tags:\n      - HTTP\n      - MVC\n      - REST\n      - Web\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/docs/6.0.x/reference/html/web.html\n      - type: Tutorial\n        url: https://spring.io/guides/gs/rest-service/\n      - type: OpenAPI\n        url: https://api.example.com/v3/api-docs\n  - name: Spring Data REST API\n\
  \    description: >-\n      Automatically expose Spring Data repositories as REST resources.\n    humanUrl: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n    baseUrl: https://api.example.com/api\n    tags:\n      - CRUD\n      - Data\n      - Repository\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/api/\n      - type: HAL Browser\n        url: https://api.example.com/browser/\n  - name: Spring Security API\n    description: >-\n      Security framework for authentication and authorization.\n    humanUrl: https://docs.spring.io/spring-security/reference/\n    baseUrl: https://api.example.com/api\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth2\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/\n\
  \      - type: API Documentation\n        url: https://docs.spring.io/spring-security/site/docs/6.0.x/api/\n      - type: OAuth2 Guide\n        url: https://spring.io/guides/tutorials/spring-boot-oauth2/\nmaintainers:\n  - name: VMware Tanzu (Broadcom)\n    email: spring-team@vmware.com\n    url: https://spring.io/team\ntags:\n  - Enterprise\n  - Framework\n  - Java\n  - Microservices\n  - REST API\n  - Spring Boot\ncommon:\n  - type: Getting Started\n    url: https://spring.io/guides/gs/spring-boot/\n  - type: GitHub Repository\n    url: https://github.com/spring-projects/spring-boot\n  - type: Release Notes\n    url: https://github.com/spring-projects/spring-boot/releases\n  - type: Migration Guide\n    url: https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide\n  - type: Community\n    url: https://spring.io/community\n  - type: Blog\n    url: https://spring.io/blog\n  - type: Twitter\n    url: https://twitter.com/springboot\ninclude:\n  - name: Spring\
  \ Framework\n    url: https://spring.io/projects/spring-framework\n  - name: Spring Cloud\n    url: https://spring.io/projects/spring-cloud\n  - name: Spring Data\n    url: https://spring.io/projects/spring-data\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/apis.yml
tags:
- Enterprise
- Framework
- Java
- Microservices
- REST API
- Spring Boot
url: https://spring.io/projects/spring-boot
use_cases: []
---
