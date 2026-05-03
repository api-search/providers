---
api_count: 5
api_specs:
- filename: api-docs
  format: yaml
  label: Spring Boot Admin Server API
  slug: ''
  spec_type: OpenAPI
  url: http://localhost:8080/v3/api-docs
apis:
- description: The main API for the Spring Boot Admin server that provides endpoints for registering applications, retrieving application information, and monitoring status.
  name: Spring Boot Admin Server API
  slug: ''
- description: Manage and retrieve information about registered Spring Boot applications.
  name: Applications API
  slug: ''
- description: Retrieve information about application instances.
  name: Instances API
  slug: ''
- description: Retrieve application lifecycle and state change events.
  name: Events API
  slug: ''
- description: Configure and manage notification channels for application events.
  name: Notifications API
  slug: ''
common:
- title: ''
  type: GitHub Repository
  url: https://github.com/codecentric/spring-boot-admin
- title: ''
  type: Issue Tracker
  url: https://github.com/codecentric/spring-boot-admin/issues
- title: ''
  type: Getting Started Guide
  url: https://codecentric.github.io/spring-boot-admin/current/#getting-started
- title: ''
  type: Reference Documentation
  url: https://codecentric.github.io/spring-boot-admin/current/
- title: ''
  type: Maven Central
  url: https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin
- title: ''
  type: License
  url: https://github.com/codecentric/spring-boot-admin/blob/master/LICENSE
- title: ''
  type: Community
  url: https://gitter.im/codecentric/spring-boot-admin
created: '2024-01-01'
description: Spring Boot Admin is a community project to manage and monitor Spring Boot applications. It provides a web-based UI to visualize and interact with Spring Boot Actuator endpoints.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-03-16'
name: Spring Boot Admin Console
skills: []
slug: spring-boot-admin-console
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Boot Admin Console\ndescription: Spring Boot Admin is a community project to manage and monitor Spring Boot applications. It provides a web-based UI to visualize and interact with Spring Boot Actuator endpoints.\nurl: https://github.com/codecentric/spring-boot-admin\ntype: Index\ntags:\n  - Actuator\n  - Administration\n  - Java\n  - Microservices\n  - Monitoring\n  - Spring Boot\ncreated: '2024-01-01'\nmodified: '2026-03-16'\napis:\n  - name: Spring Boot Admin Server API\n    description: The main API for the Spring Boot Admin server that provides endpoints for registering applications, retrieving application information, and monitoring status.\n    baseURL: http://localhost:8080\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/\n      - type: OpenAPI\n        url: http://localhost:8080/v3/api-docs\n    tags:\n      - Administration\n\
  \      - Monitoring\n      - Server\n  - name: Applications API\n    description: >-\n      Manage and retrieve information about registered Spring Boot applications.\n    baseURL: http://localhost:8080/applications\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_applications\n    endpoints:\n      - path: /applications\n        methods:\n          - GET\n          - POST\n        description: List all registered applications or register a new application\n      - path: /applications/{id}\n        methods:\n          - GET\n          - DELETE\n        description: Get or unregister a specific application by ID\n      - path: /applications/{id}/actuator\n        methods:\n          - GET\n        description: Get actuator endpoints for a specific application\n    tags:\n      - Applications\n      - Registration\n  - name: Instances API\n    description: >-\n      Retrieve information about application instances.\n  \
  \  baseURL: http://localhost:8080/instances\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_instances\n    endpoints:\n      - path: /instances\n        methods:\n          - GET\n        description: List all registered application instances\n      - path: /instances/{id}\n        methods:\n          - GET\n          - DELETE\n        description: Get or unregister a specific instance\n      - path: /instances/{id}/actuator/**\n        methods:\n          - GET\n          - POST\n        description: Proxy requests to actuator endpoints of the instance\n      - path: /instances/{id}/actuator/health\n        methods:\n          - GET\n        description: Get health information of the instance\n      - path: /instances/{id}/actuator/info\n        methods:\n          - GET\n        description: Get info about the instance\n      - path: /instances/{id}/actuator/metrics\n        methods:\n          - GET\n        description:\
  \ Get metrics from the instance\n      - path: /instances/{id}/actuator/env\n        methods:\n          - GET\n        description: Get environment properties of the instance\n      - path: /instances/{id}/actuator/loggers\n        methods:\n          - GET\n          - POST\n        description: View and modify logger configurations\n    tags:\n      - Actuator\n      - Instances\n      - Monitoring\n  - name: Events API\n    description: >-\n      Retrieve application lifecycle and state change events.\n    baseURL: http://localhost:8080/instances/events\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_event-store\n    endpoints:\n      - path: /instances/events\n        methods:\n          - GET\n        description: Stream of events (SSE - Server-Sent Events)\n    tags:\n      - Events\n      - Notifications\n  - name: Notifications API\n    description: >-\n      Configure and manage notification channels for application\
  \ events.\n    baseURL: http://localhost:8080\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_notifications\n    tags:\n      - Alerts\n      - Notifications\nmaintainers:\n  - name: codecentric AG\n    url: https://www.codecentric.de/\n    email: info@codecentric.de\ncommon:\n  - type: GitHub Repository\n    url: https://github.com/codecentric/spring-boot-admin\n  - type: Issue Tracker\n    url: https://github.com/codecentric/spring-boot-admin/issues\n  - type: Getting Started Guide\n    url: https://codecentric.github.io/spring-boot-admin/current/#getting-started\n  - type: Reference Documentation\n    url: https://codecentric.github.io/spring-boot-admin/current/\n  - type: Maven Central\n    url: https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin\n  - type: License\n    url: https://github.com/codecentric/spring-boot-admin/blob/master/LICENSE\n  - type: Community\n    url: https://gitter.im/codecentric/spring-boot-admin\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-admin-console/refs/heads/main/apis.yml
tags:
- Actuator
- Administration
- Java
- Microservices
- Monitoring
- Spring Boot
url: https://github.com/codecentric/spring-boot-admin
use_cases: []
---
