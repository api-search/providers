---
api_count: 1
api_specs:
- filename: axon-server-api.yml
  format: yaml
  label: Axon Framework
  slug: axon-framework
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/openapi/axon-server-api.yml
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
source_filename: apis.yml
source_yaml: "aid: axon-framework\nname: Axon Framework\ndescription: >-\n  Axon Framework is a Java framework for building event-driven microservices\n  using CQRS (Command Query Responsibility Segregation) and event sourcing\n  patterns, providing the building blocks to implement scalable and\n  maintainable distributed systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- CQRS\n- Event Sourcing\n- Event-Driven\n- Java\n- Messaging\n- Microservices\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: axon-framework:axon-framework\n  name: Axon Framework\n  description: >-\n    Axon Framework is a Java framework for building event-driven\n    microservices using CQRS and event sourcing patterns, providing\n    infrastructure components for command handling, event processing, and\n    query\
  \ handling in distributed systems.\n  humanURL: https://www.axoniq.io/products/axon-framework\n  tags:\n  - CQRS\n  - Event Sourcing\n  - Event-Driven\n  - Java\n  - Messaging\n  - Microservices\n  properties:\n  - type: OpenAPI\n    url: openapi/axon-server-api.yml\n  - type: APIReference\n    url: https://docs.axoniq.io/axon-server/administration/axon-server-api\n  baseURL: https://axonserver:8024\ncommon:\n- type: Website\n  url: https://www.axoniq.io/\n- type: Documentation\n  url: https://docs.axoniq.io/\n- type: GettingStarted\n  url: https://docs.axoniq.io/axon-framework/getting-started\n- type: GitHubRepository\n  url: https://github.com/AxonFramework/AxonFramework\n- type: Blog\n  url: https://www.axoniq.io/blog\n- type: Pricing\n  url: https://www.axoniq.io/pricing\n- type: TermsOfService\n  url: https://www.axoniq.io/terms-and-conditions\n- type: StatusPage\n  url: https://status.axoniq.io/\n- type: SpectralRules\n  url: rules/axon-framework-spectral-rules.yml\n- type: Vocabulary\n\
  \  url: vocabulary/axon-framework-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/event-driven-workflow.yaml\n- type: Features\n  data:\n  - name: CQRS Pattern\n    description: Separate command and query models for scalable, maintainable \n      architecture.\n  - name: Event Sourcing\n    description: Store application state as a sequence of events for full audit \n      trail and time-travel debugging.\n  - name: Domain-Driven Design\n    description: First-class support for DDD patterns including aggregates, \n      sagas, and bounded contexts.\n  - name: Axon Server Integration\n    description: Zero-configuration event store and message router with Axon \n      Server.\n  - name: Distributed Systems Support\n    description: Built-in routing for commands, events, and queries across \n      distributed services.\n  - name: Spring Boot Integration\n    description: Seamless Spring Boot auto-configuration for rapid application \n      development.\n  - name: Testing\
  \ Support\n    description: Built-in testing fixtures for validating aggregate behavior \n      without infrastructure.\n  - name: Saga Management\n    description: Manage long-running business processes with durable saga state.\n- type: UseCases\n  data:\n  - name: Microservices Architecture\n    description: Build event-driven microservices with reliable message routing.\n  - name: Audit Trail\n    description: Maintain complete audit trails by storing all state changes as \n      events.\n  - name: Temporal Queries\n    description: Reconstruct system state at any point in time from the event \n      store.\n  - name: Collaborative Domains\n    description: Build complex collaborative domains with CQRS separation.\n  - name: Workflow Automation\n    description: Automate multi-step business workflows with event-driven sagas.\n- type: Integrations\n  data:\n  - name: Spring Boot\n    description: Auto-configuration and starter dependency for Spring Boot \n      integration.\n  - name:\
  \ Apache Kafka\n    description: Route events through Kafka as an alternative to Axon Server.\n  - name: RabbitMQ\n    description: Route commands and events through AMQP with RabbitMQ extension.\n  - name: JPA/Hibernate\n    description: Persist saga state and event-sourced entities with JPA.\n  - name: Micrometer\n    description: Expose framework metrics via Micrometer for Prometheus and \n      Grafana.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/axon-framework/refs/heads/main/apis.yml
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
