---
api_count: 1
api_specs:
- filename: zeebe-api.yml
  format: yaml
  label: Zeebe REST API
  slug: zeebe
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/openapi/zeebe-api.yml
apis:
- description: The Zeebe REST API provides programmatic access to the Zeebe workflow engine powering Camunda 8. It enables process deployment, process instance creation and management, job activation and completion,
  name: Zeebe REST API
  slug: zeebe
capabilities:
- description: 'Unified workflow capability for process orchestration with Zeebe, combining deployment, instance management, job handling, message correlation, signal broadcasting, incident resolution, and user task '
  name: Zeebe Process Orchestration
  slug: process-orchestration
- description: Unified workflow capability composing Zeebe APIs.
  name: Zeebe Workflow
  slug: zeebe-workflow
common:
- title: ''
  type: Website
  url: https://camunda.com/platform/zeebe/
- title: ''
  type: Documentation
  url: https://docs.camunda.io/docs/components/zeebe/zeebe-overview/
- title: ''
  type: Documentation
  url: https://docs.camunda.io/docs/apis-tools/zeebe-api-rest/zeebe-api-rest-overview/
- title: ''
  type: Getting Started
  url: https://docs.camunda.io/docs/guides/
- title: ''
  type: GitHub
  url: https://github.com/camunda/camunda
- title: ''
  type: GitHubOrg
  url: https://github.com/camunda
- title: ''
  type: GitHubOrg
  url: https://github.com/camunda-community-hub
- title: ''
  type: Pricing
  url: https://camunda.com/pricing/
- title: ''
  type: Blog
  url: https://camunda.com/blog/
- title: ''
  type: Issues
  url: https://github.com/camunda/camunda/issues
- title: ''
  type: SDK
  url: https://github.com/camunda/camunda-bpm-spring-boot-starter
- title: ''
  type: SDK
  url: https://github.com/camunda-community-hub/zeebe-client-csharp
- title: ''
  type: SDK
  url: https://github.com/camunda-community-hub/micronaut-zeebe-client
- title: ''
  type: ChangeLog
  url: https://github.com/camunda/camunda/releases
- title: ''
  type: Forum
  url: https://forum.camunda.io/
created: '2026-03-26'
description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It implements BPMN 2.0 process execution and provides a REST API for process deployment, instance management, job handling, message correlation, and cluster topology queries.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Zeebe Api Context
  property_count: 27
  slug: zeebe-api-context
layout: provider
modified: '2026-05-04'
name: Zeebe
rules:
- name: Zeebe API Rules
  rule_count: 18
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 13
  slug: zeebe-rules
skills: []
slug: zeebe
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zeebe\nname: Zeebe\ndescription: >-\n  Zeebe is the cloud-native workflow engine that powers Camunda 8, providing\n  scalable, resilient workflow automation and microservices orchestration without\n  relying on a central database, enabling high throughput with horizontal scaling.\n  It implements BPMN 2.0 process execution and provides a REST API for process\n  deployment, instance management, job handling, message correlation, and cluster\n  topology queries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - BPMN\n  - Camunda\n  - Cloud Native\n  - Distributed Systems\n  - Java\n  - Microservices\n  - Process Automation\n  - Workflow Orchestration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-04'\nspecificationVersion: '0.19'\napis:\n  - aid: zeebe:zeebe\n    name: Zeebe REST API\n    description: >-\n      The Zeebe REST API\
  \ provides programmatic access to the Zeebe workflow engine\n      powering Camunda 8. It enables process deployment, process instance creation\n      and management, job activation and completion, message and signal publishing,\n      incident resolution, user task management, and cluster topology queries.\n    humanURL: https://docs.camunda.io/docs/apis-tools/zeebe-api-rest/zeebe-api-rest-overview/\n    baseURL: https://{region}.zeebe.camunda.io:443/{clusterId}/v2\n    tags:\n      - BPMN\n      - Camunda\n      - Cloud Native\n      - Microservices\n      - Process Automation\n      - Workflow Orchestration\n    properties:\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/openapi/zeebe-api.yml\n      - type: Documentation\n        url: https://docs.camunda.io/docs/apis-tools/zeebe-api-rest/zeebe-api-rest-overview/\n      - type: Postman\n        url: https://www.postman.com/camundateam/camunda-8-postman/collection/j0knqwp/zeebe-api-rest\n\
  \      - type: Spectral Rules\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/rules/zeebe-rules.yml\n      - type: Examples\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/examples/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/json-schema/\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/json-structure/\n      - type: JSONLD\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/json-ld/zeebe-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/vocabulary/zeebe-vocabulary.yml\n      - type: Capabilities\n        url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/capabilities/\ncommon:\n  - type: Website\n    url: https://camunda.com/platform/zeebe/\n    name:\
  \ Zeebe Platform Page\n  - type: Documentation\n    url: https://docs.camunda.io/docs/components/zeebe/zeebe-overview/\n    name: Zeebe Documentation Overview\n  - type: Documentation\n    url: https://docs.camunda.io/docs/apis-tools/zeebe-api-rest/zeebe-api-rest-overview/\n    name: Zeebe REST API Documentation\n  - type: Getting Started\n    url: https://docs.camunda.io/docs/guides/\n    name: Getting Started with Camunda 8\n  - type: GitHub\n    url: https://github.com/camunda/camunda\n    name: Camunda GitHub Repository\n  - type: GitHubOrg\n    url: https://github.com/camunda\n    name: Camunda GitHub Organization\n  - type: GitHubOrg\n    url: https://github.com/camunda-community-hub\n    name: Camunda Community Hub\n  - type: Pricing\n    url: https://camunda.com/pricing/\n    name: Camunda Pricing\n  - type: Blog\n    url: https://camunda.com/blog/\n    name: Camunda Blog\n  - type: Issues\n    url: https://github.com/camunda/camunda/issues\n    name: GitHub Issues\n  - type: SDK\n\
  \    url: https://github.com/camunda/camunda-bpm-spring-boot-starter\n    name: Spring Boot Starter\n  - type: SDK\n    url: https://github.com/camunda-community-hub/zeebe-client-csharp\n    name: C# Client\n  - type: SDK\n    url: https://github.com/camunda-community-hub/micronaut-zeebe-client\n    name: Micronaut Client\n  - type: ChangeLog\n    url: https://github.com/camunda/camunda/releases\n    name: Release Notes\n  - type: Forum\n    url: https://forum.camunda.io/\n    name: Camunda Forum\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/apis.yml
tags:
- BPMN
- Camunda
- Cloud Native
- Distributed Systems
- Java
- Microservices
- Process Automation
- Workflow Orchestration
url: https://raw.githubusercontent.com/api-evangelist/zeebe/refs/heads/main/apis.yml
use_cases: []
---
