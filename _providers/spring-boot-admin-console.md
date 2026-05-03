---
api_count: 5
api_specs:
- filename: spring-boot-admin-console-openapi.yml
  format: yaml
  label: Spring Boot Admin Server API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot-admin-console/refs/heads/main/openapi/spring-boot-admin-console-openapi.yml
apis:
- description: REST API for the Spring Boot Admin server that manages application registration, retrieves application and instance information, proxies Actuator endpoints, and streams lifecycle events via Server-Sen
  name: Spring Boot Admin Server API
  slug: ''
- description: Manage registered Spring Boot applications. Applications are logical groupings of instances sharing the same name and management URL base.
  name: Applications API
  slug: ''
- description: Manage individual application instances. Each instance represents a running Spring Boot application registered with the Admin server. Supports health monitoring, Actuator endpoint proxying, and deregi
  name: Instances API
  slug: ''
- description: Lifecycle event stream for application instances using Server-Sent Events (SSE). Events include status changes, registration, deregistration, and info updates.
  name: Events API
  slug: ''
- description: Configure and trigger notification channels for application lifecycle events. Supports email, Slack, PagerDuty, OpsGenie, Microsoft Teams, Telegram, and custom webhook notifications.
  name: Notifications API
  slug: ''
capabilities:
- description: 'Workflow capability for managing and monitoring a fleet of Spring Boot microservices via Spring Boot Admin. Provides unified visibility into application health, instance lifecycle, real-time metrics, '
  name: Spring Boot Admin Microservice Fleet Management
  slug: microservice-fleet-management
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
description: Spring Boot Admin is a community project by codecentric AG that provides a web-based administration UI for managing and monitoring Spring Boot applications. It visualizes Spring Boot Actuator endpoints in a graphical interface and provides application registration, health monitoring, log level management, metric graphs, instance lifecycle event tracking, and notification integrations (email, Slack, PagerDuty, OpsGenie, Hipchat, Teams, Telegram).
features: []
image: https://raw.githubusercontent.com/codecentric/spring-boot-admin/master/spring-boot-admin-docs/src/site/resources/images/spring-boot-admin-logo.png
integrations: []
jsonld:
- class_count: 6
  name: Spring Boot Admin Console Context
  property_count: 22
  slug: spring-boot-admin-console-context
layout: provider
modified: '2026-05-02'
name: Spring Boot Admin Console
rules:
- name: Spring Boot Admin Console API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: spring-boot-admin-console-rules
skills: []
slug: spring-boot-admin-console
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Boot Admin Console\ndescription: >-\n  Spring Boot Admin is a community project by codecentric AG that provides a\n  web-based administration UI for managing and monitoring Spring Boot applications.\n  It visualizes Spring Boot Actuator endpoints in a graphical interface and provides\n  application registration, health monitoring, log level management, metric graphs,\n  instance lifecycle event tracking, and notification integrations (email, Slack,\n  PagerDuty, OpsGenie, Hipchat, Teams, Telegram).\nurl: https://github.com/codecentric/spring-boot-admin\nimage: https://raw.githubusercontent.com/codecentric/spring-boot-admin/master/spring-boot-admin-docs/src/site/resources/images/spring-boot-admin-logo.png\ntype: opensource\ntags:\n  - Actuator\n  - Administration\n  - Java\n  - Microservices\n  - Monitoring\n  - Spring Boot\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\napis:\n  - name: Spring Boot Admin Server API\n    description:\
  \ >-\n      REST API for the Spring Boot Admin server that manages application registration,\n      retrieves application and instance information, proxies Actuator endpoints,\n      and streams lifecycle events via Server-Sent Events.\n    baseURL: http://localhost:8080\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/\n    tags:\n      - Administration\n      - Monitoring\n      - Server\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/\n      - type: GitHub Repository\n        url: https://github.com/codecentric/spring-boot-admin\n      - type: OpenAPI\n        url: openapi/spring-boot-admin-console-openapi.yml\n      - type: Spectral Rules\n        url: rules/spring-boot-admin-console-rules.yml\n      - type: Maven Central\n        url: https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin-server\n      - type: Release Notes\n        url: https://github.com/codecentric/spring-boot-admin/releases\n\
  \  - name: Applications API\n    description: >-\n      Manage registered Spring Boot applications. Applications are logical groupings\n      of instances sharing the same name and management URL base.\n    baseURL: http://localhost:8080/applications\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/#_applications\n    tags:\n      - Applications\n      - Registration\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_applications\n  - name: Instances API\n    description: >-\n      Manage individual application instances. Each instance represents a running\n      Spring Boot application registered with the Admin server. Supports health\n      monitoring, Actuator endpoint proxying, and deregistration.\n    baseURL: http://localhost:8080/instances\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/#_instances\n    tags:\n      - Actuator\n      - Instances\n      - Monitoring\n \
  \   properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_instances\n  - name: Events API\n    description: >-\n      Lifecycle event stream for application instances using Server-Sent Events\n      (SSE). Events include status changes, registration, deregistration, and\n      info updates.\n    baseURL: http://localhost:8080/instances/events\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/#_event-store\n    tags:\n      - Events\n      - Notifications\n      - SSE\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_event-store\n  - name: Notifications API\n    description: >-\n      Configure and trigger notification channels for application lifecycle events.\n      Supports email, Slack, PagerDuty, OpsGenie, Microsoft Teams, Telegram,\n      and custom webhook notifications.\n    baseURL: http://localhost:8080\n    humanURL: https://codecentric.github.io/spring-boot-admin/current/#_notifications\n\
  \    tags:\n      - Alerts\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/#_notifications\nmaintainers:\n  - name: codecentric AG\n    url: https://www.codecentric.de/\n    email: info@codecentric.de\ncommon:\n  - type: GitHub Repository\n    url: https://github.com/codecentric/spring-boot-admin\n  - type: Issue Tracker\n    url: https://github.com/codecentric/spring-boot-admin/issues\n  - type: Getting Started Guide\n    url: https://codecentric.github.io/spring-boot-admin/current/#getting-started\n  - type: Reference Documentation\n    url: https://codecentric.github.io/spring-boot-admin/current/\n  - type: Maven Central\n    url: https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin\n  - type: License\n    url: https://github.com/codecentric/spring-boot-admin/blob/master/LICENSE\n  - type: Community\n    url: https://gitter.im/codecentric/spring-boot-admin\n"
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
