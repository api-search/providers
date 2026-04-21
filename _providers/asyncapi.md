---
api_count: 1
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
