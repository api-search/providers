---
api_count: 1
api_specs:
- filename: asyncapi.md
  format: yaml
  label: AsyncAPI Specification
  slug: asyncapi-spec
  spec_type: AsyncAPI
  url: https://github.com/asyncapi/spec/blob/master/spec/asyncapi.md
apis:
- description: The AsyncAPI Specification is an open standard for describing asynchronous and event-driven APIs. It provides a machine-readable format for defining messaging interfaces across protocols like Kafka, M
  name: AsyncAPI Specification
  slug: asyncapi-spec
common:
- title: AsyncAPI Website
  type: Portal
  url: https://www.asyncapi.com/
- title: Documentation
  type: Documentation
  url: https://www.asyncapi.com/docs
- title: AsyncAPI GitHub Organization
  type: GitHubOrganization
  url: https://github.com/asyncapi
- title: Blog
  type: Blog
  url: https://www.asyncapi.com/blog
created: '2026-03-16'
description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, validate, generate code, and manage message-driven APIs across protocols including Kafka, MQTT, WebSocket, AMQP, and others. The AsyncAPI specification serves as the industry standard for describing asynchronous messaging interfaces, similar to how OpenAPI serves REST APIs.
features:
- description: An open specification standard for describing asynchronous and event-driven APIs, supporting multiple messaging protocols including Kafka, MQTT, WebSocket, AMQP, and more.
  name: AsyncAPI Specification
- description: Code and documentation generation tool that uses AsyncAPI definitions to produce boilerplate code, documentation, and other artifacts in multiple programming languages.
  name: AsyncAPI Generator
- description: Command-line interface tool for working with AsyncAPI files including validation, generation, and conversion operations from the terminal.
  name: AsyncAPI CLI
- description: Web-based editor and visualization tool for creating, editing, and previewing AsyncAPI specification documents with real-time validation.
  name: AsyncAPI Studio
- description: Broad protocol support covering Kafka, MQTT, WebSocket, AMQP, NATS, JMS, and other messaging protocols through a unified specification format.
  name: Protocol Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AsyncAPI supports defining Kafka-based event-driven APIs with topic, message schema, and broker configuration documentation.
  name: Apache Kafka
- description: IoT and messaging platforms using MQTT can document their pub/sub interfaces using AsyncAPI specifications for device and service integration.
  name: MQTT Brokers
- description: AsyncAPI CLI integrates into continuous integration pipelines for automated validation and linting of AsyncAPI specification files.
  name: CI/CD Pipelines
layout: provider
modified: '2026-04-19'
name: AsyncAPI
skills: []
slug: asyncapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: asyncapi\nname: AsyncAPI\ndescription: >-\n  AsyncAPI is a Linux Foundation project that improves the state of\n  event-driven architectures by providing an open specification and tooling\n  ecosystem for defining asynchronous and event-driven APIs. It enables\n  developers to document, validate, generate code, and manage message-driven\n  APIs across protocols including Kafka, MQTT, WebSocket, AMQP, and others.\n  The AsyncAPI specification serves as the industry standard for describing\n  asynchronous messaging interfaces, similar to how OpenAPI serves REST APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Event-Driven\n  - Linux Foundation\n  - Messaging\n  - Standards\n  - Specification\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/asyncapi/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: asyncapi:asyncapi-spec\n    name:\
  \ AsyncAPI Specification\n    description: >-\n      The AsyncAPI Specification is an open standard for describing asynchronous\n      and event-driven APIs. It provides a machine-readable format for defining\n      messaging interfaces across protocols like Kafka, MQTT, WebSocket, and\n      AMQP, enabling documentation generation, code generation, and validation\n      tooling for event-driven architectures.\n    humanURL: https://www.asyncapi.com/docs\n    tags:\n      - Event-Driven\n      - Messaging\n      - Specification\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://www.asyncapi.com/docs\n      - type: GettingStarted\n        url: https://www.asyncapi.com/docs/tutorials/getting-started\n      - type: AsyncAPI\n        url: https://github.com/asyncapi/spec/blob/master/spec/asyncapi.md\ncommon:\n  - type: Portal\n    url: https://www.asyncapi.com/\n    title: AsyncAPI Website\n  - type: Documentation\n    url: https://www.asyncapi.com/docs\n\
  \    title: Documentation\n  - type: GitHubOrganization\n    url: https://github.com/asyncapi\n    title: AsyncAPI GitHub Organization\n  - type: Blog\n    url: https://www.asyncapi.com/blog\n    title: Blog\n  - type: Features\n    data:\n      - name: AsyncAPI Specification\n        description: >-\n          An open specification standard for describing asynchronous and\n          event-driven APIs, supporting multiple messaging protocols including\n          Kafka, MQTT, WebSocket, AMQP, and more.\n      - name: AsyncAPI Generator\n        description: >-\n          Code and documentation generation tool that uses AsyncAPI definitions\n          to produce boilerplate code, documentation, and other artifacts\n          in multiple programming languages.\n      - name: AsyncAPI CLI\n        description: >-\n          Command-line interface tool for working with AsyncAPI files including\n          validation, generation, and conversion operations from the terminal.\n      - name: AsyncAPI\
  \ Studio\n        description: >-\n          Web-based editor and visualization tool for creating, editing, and\n          previewing AsyncAPI specification documents with real-time validation.\n      - name: Protocol Support\n        description: >-\n          Broad protocol support covering Kafka, MQTT, WebSocket, AMQP, NATS,\n          JMS, and other messaging protocols through a unified specification\n          format.\n  - type: UseCases\n    data:\n      - name: Event-Driven API Documentation\n        description: >-\n          Development teams use AsyncAPI to create machine-readable documentation\n          for their message-driven APIs, making it easier for consumers to\n          understand and integrate with event streams.\n      - name: Code Generation for Messaging\n        description: >-\n          Engineers generate boilerplate code for Kafka consumers, MQTT\n          publishers, and other messaging clients directly from AsyncAPI\n          specifications to accelerate\
  \ development.\n      - name: API Governance for Event-Driven Systems\n        description: >-\n          Platform teams apply AsyncAPI specifications to enforce standards\n          and governance across microservices architectures using event-driven\n          communication.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: >-\n          AsyncAPI supports defining Kafka-based event-driven APIs with\n          topic, message schema, and broker configuration documentation.\n      - name: MQTT Brokers\n        description: >-\n          IoT and messaging platforms using MQTT can document their pub/sub\n          interfaces using AsyncAPI specifications for device and service\n          integration.\n      - name: CI/CD Pipelines\n        description: >-\n          AsyncAPI CLI integrates into continuous integration pipelines for\n          automated validation and linting of AsyncAPI specification files.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/asyncapi/refs/heads/main/apis.yml
tags:
- Event-Driven
- Linux Foundation
- Messaging
- Standards
- Specification
url: https://raw.githubusercontent.com/api-evangelist/asyncapi/refs/heads/main/apis.yml
use_cases:
- description: Development teams use AsyncAPI to create machine-readable documentation for their message-driven APIs, making it easier for consumers to understand and integrate with event streams.
  name: Event-Driven API Documentation
- description: Engineers generate boilerplate code for Kafka consumers, MQTT publishers, and other messaging clients directly from AsyncAPI specifications to accelerate development.
  name: Code Generation for Messaging
- description: Platform teams apply AsyncAPI specifications to enforce standards and governance across microservices architectures using event-driven communication.
  name: API Governance for Event-Driven Systems
---
