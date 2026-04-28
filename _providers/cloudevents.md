---
api_count: 12
apis:
- description: The CloudEvents specification defines a set of metadata attributes that must be present in every event, including source, type, id, and specversion. It provides a vendor-neutral way to describe events
  name: CloudEvents Specification
  slug: cloudevents-spec
- description: The HTTP protocol binding defines how CloudEvents are transported using HTTP, including structured content mode where the entire event is in the HTTP body, and binary content mode where event attribut
  name: CloudEvents HTTP Protocol Binding
  slug: cloudevents-http-binding
- description: The Kafka protocol binding for CloudEvents defines how events are mapped to Apache Kafka messages. It specifies how CloudEvents attributes are encoded as Kafka message headers and how the event payloa
  name: CloudEvents Kafka Protocol Binding
  slug: cloudevents-kafka-binding
- description: The AMQP protocol binding for CloudEvents defines how events are mapped to OASIS AMQP 1.0 messages. In structured content mode, event attributes and data are placed in the AMQP message application dat
  name: CloudEvents AMQP Protocol Binding
  slug: cloudevents-amqp-binding
- description: The MQTT protocol binding for CloudEvents defines how events are mapped to MQTT 3.1.1 and MQTT 5.0 messages. It supports both structured and binary content modes for IoT and constrained device environ
  name: CloudEvents MQTT Protocol Binding
  slug: cloudevents-mqtt-binding
- description: The NATS protocol binding for CloudEvents defines how events are mapped to NATS messages. It enables CloudEvents to be produced and consumed over the NATS messaging system, supporting both publish/sub
  name: CloudEvents NATS Protocol Binding
  slug: cloudevents-nats-binding
- description: The CloudEvents Subscriptions API specification defines a standard REST API for managing subscriptions to event streams. It enables clients to create, list, update, and delete subscriptions with filte
  name: CloudEvents Subscriptions API
  slug: cloudevents-subscriptions
- description: CloudEvents SQL (CESQL) is a v1.0 specification that defines a standardized query language for filtering and routing CloudEvents based on their attributes. It provides a SQL-like syntax for writing ev
  name: CloudEvents SQL (CESQL)
  slug: cloudevents-cesql
- description: 'The official Go SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Go applications. It supports all CloudEvents protocol bindings and content modes, and includes client '
  name: CloudEvents Go SDK
  slug: cloudevents-sdk-go
- description: The official JavaScript SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Node.js and browser environments. It supports structured and binary content modes over HTTP an
  name: CloudEvents JavaScript SDK
  slug: cloudevents-sdk-javascript
- description: The official Java SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Java applications. It includes support for HTTP, Kafka, and other transports, and integrates with po
  name: CloudEvents Java SDK
  slug: cloudevents-sdk-java
- description: The official Python SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Python applications. It supports HTTP transport bindings and both structured and binary content mo
  name: CloudEvents Python SDK
  slug: cloudevents-sdk-python
asyncapis:
- description: 'AsyncAPI definition for CloudEvents delivery over HTTP. This document describes the event-driven interface by which a CloudEvents-compatible broker pushes events to a subscriber''s HTTP sink endpoint. '
  name: CloudEvents HTTP Delivery
  slug: cloudevents-http-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://cloudevents.io
- title: ''
  type: Documentation
  url: https://github.com/cloudevents/spec
- title: ''
  type: Getting Started
  url: https://github.com/cloudevents/spec/blob/main/cloudevents/primer.md
- title: ''
  type: Blog
  url: https://cloudevents.io/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cloudevents
- title: ''
  type: SDKs
  url: https://github.com/cloudevents/spec/blob/main/cloudevents/SDK.md
- title: ''
  type: Change Log
  url: https://github.com/cloudevents/spec/releases
- title: ''
  type: JSONSchema
  url: json-schema/cloudevents-event-schema.json
- title: ''
  type: OpenAPI
  url: openapi/cloudevents-subscriptions-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/cloudevents-http-asyncapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/cloudevents-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudevents-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudevents-subscriptions-capabilities.yml
created: '2026-03-16'
description: CloudEvents is a CNCF graduated specification for describing event data in a common way. It provides a consistent format for event metadata across services, platforms, and systems, enabling interoperability between event producers and consumers. The specification includes protocol bindings for HTTP, AMQP, Kafka, MQTT, and NATS, along with SDKs in multiple languages.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Cloudevents Context
  property_count: 27
  slug: cloudevents-context
layout: provider
modified: '2026-04-26'
name: CloudEvents
rules:
- name: CloudEvents API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 6
  slug: cloudevents-rules
skills: []
slug: cloudevents
solutions: []
tags:
- Cloud Native
- Events
- Graduated
- Interoperability
- Messaging
- Specification
url: https://cloudevents.io
use_cases: []
---
