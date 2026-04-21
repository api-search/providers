---
api_count: 1
apis:
- description: Axon Framework is a Java framework for building event-driven microservices using CQRS and event sourcing patterns, providing infrastructure components for command handling, event processing, and query
  name: Axon Framework
  slug: axon-framework
capabilities:
- description: Workflow capability for managing Axon Server applications, contexts, and event streaming.
  name: Axon Framework Event-Driven Workflow
  slug: event-driven-workflow
common:
- title: ''
  type: Website
  url: https://www.axoniq.io/
- title: ''
  type: Documentation
  url: https://docs.axoniq.io/
- title: ''
  type: GettingStarted
  url: https://docs.axoniq.io/axon-framework/getting-started
- title: ''
  type: GitHubRepository
  url: https://github.com/AxonFramework/AxonFramework
- title: ''
  type: Blog
  url: https://www.axoniq.io/blog
- title: ''
  type: Pricing
  url: https://www.axoniq.io/pricing
- title: ''
  type: TermsOfService
  url: https://www.axoniq.io/terms-and-conditions
- title: ''
  type: StatusPage
  url: https://status.axoniq.io/
- title: ''
  type: SpectralRules
  url: rules/axon-framework-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/axon-framework-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/event-driven-workflow.yaml
created: '2026-03-26'
description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed systems.
features:
- description: Separate command and query models for scalable, maintainable architecture.
  name: CQRS Pattern
- description: Store application state as a sequence of events for full audit trail and time-travel debugging.
  name: Event Sourcing
- description: First-class support for DDD patterns including aggregates, sagas, and bounded contexts.
  name: Domain-Driven Design
- description: Zero-configuration event store and message router with Axon Server.
  name: Axon Server Integration
- description: Built-in routing for commands, events, and queries across distributed services.
  name: Distributed Systems Support
- description: Seamless Spring Boot auto-configuration for rapid application development.
  name: Spring Boot Integration
- description: Built-in testing fixtures for validating aggregate behavior without infrastructure.
  name: Testing Support
- description: Manage long-running business processes with durable saga state.
  name: Saga Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Auto-configuration and starter dependency for Spring Boot integration.
  name: Spring Boot
- description: Route events through Kafka as an alternative to Axon Server.
  name: Apache Kafka
- description: Route commands and events through AMQP with RabbitMQ extension.
  name: RabbitMQ
- description: Persist saga state and event-sourced entities with JPA.
  name: JPA/Hibernate
- description: Expose framework metrics via Micrometer for Prometheus and Grafana.
  name: Micrometer
jsonld:
- class_count: 10
  name: Axon Framework Context
  property_count: 0
  slug: axon-framework-context
layout: provider
modified: '2026-04-19'
name: Axon Framework
rules:
- name: Axon Framework API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 1
  slug: axon-framework-spectral-rules
skills: []
slug: axon-framework
solutions: []
tags:
- CQRS
- Event Sourcing
- Event-Driven
- Java
- Messaging
- Microservices
url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/apis.yml
use_cases:
- description: Build event-driven microservices with reliable message routing.
  name: Microservices Architecture
- description: Maintain complete audit trails by storing all state changes as events.
  name: Audit Trail
- description: Reconstruct system state at any point in time from the event store.
  name: Temporal Queries
- description: Build complex collaborative domains with CQRS separation.
  name: Collaborative Domains
- description: Automate multi-step business workflows with event-driven sagas.
  name: Workflow Automation
---
