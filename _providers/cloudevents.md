---
api_count: 12
api_specs:
- filename: cloudevents-http-asyncapi.yml
  format: yaml
  label: CloudEvents Specification
  slug: cloudevents-spec
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/asyncapi/cloudevents-http-asyncapi.yml
- filename: cloudevents-subscriptions-openapi.yml
  format: yaml
  label: CloudEvents Subscriptions API
  slug: cloudevents-subscriptions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/openapi/cloudevents-subscriptions-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudevents\nname: CloudEvents\ndescription: >-\n  CloudEvents is a CNCF graduated specification for describing event data in\n  a common way. It provides a consistent format for event metadata across\n  services, platforms, and systems, enabling interoperability between event\n  producers and consumers. The specification includes protocol bindings for\n  HTTP, AMQP, Kafka, MQTT, and NATS, along with SDKs in multiple languages.\nurl: https://cloudevents.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Events\n  - Graduated\n  - Interoperability\n  - Messaging\n  - Specification\ncreated: '2026-03-16'\nmodified: '2026-04-26'\nx-type: standard\nx-governance: CNCF (Cloud Native Computing Foundation)\nx-status: Graduated\nx-spec-version: '1.0.2'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: cloudevents:cloudevents-spec\n    name: CloudEvents Specification\n    description: >-\n      The CloudEvents\
  \ specification defines a set of metadata attributes that\n      must be present in every event, including source, type, id, and\n      specversion. It provides a vendor-neutral way to describe events that\n      enables consistent routing, filtering, and processing across different\n      systems and cloud providers.\n    humanURL: https://cloudevents.io/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/spec.md\n      - type: Reference\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md\n      - type: GitHubRepository\n        url: https://github.com/cloudevents/spec\n      - type: Change Log\n        url: https://github.com/cloudevents/spec/releases\n      - type: JSONSchema\n        url: json-schema/cloudevents-event-schema.json\n      - type: AsyncAPI\n        url: asyncapi/cloudevents-http-asyncapi.yml\n\
  \    tags:\n      - Events\n      - Specification\n      - Standards\n  - aid: cloudevents:cloudevents-http-binding\n    name: CloudEvents HTTP Protocol Binding\n    description: >-\n      The HTTP protocol binding defines how CloudEvents are transported using\n      HTTP, including structured content mode where the entire event is in the\n      HTTP body, and binary content mode where event attributes are mapped to\n      HTTP headers. This enables REST APIs to produce and consume standardized\n      events.\n    humanURL: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md\n      - type: Reference\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/http-protocol-binding.md\n  \
  \  tags:\n      - HTTP\n      - Protocol Binding\n      - REST\n  - aid: cloudevents:cloudevents-kafka-binding\n    name: CloudEvents Kafka Protocol Binding\n    description: >-\n      The Kafka protocol binding for CloudEvents defines how events are mapped\n      to Apache Kafka messages. It specifies how CloudEvents attributes are\n      encoded as Kafka message headers and how the event payload is placed in\n      the Kafka message value, enabling standardized event interchange over\n      Kafka topics.\n    humanURL: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md\n      - type: Reference\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/kafka-protocol-binding.md\n  \
  \  tags:\n      - Kafka\n      - Messaging\n      - Protocol Binding\n  - aid: cloudevents:cloudevents-amqp-binding\n    name: CloudEvents AMQP Protocol Binding\n    description: >-\n      The AMQP protocol binding for CloudEvents defines how events are mapped\n      to OASIS AMQP 1.0 messages. In structured content mode, event attributes\n      and data are placed in the AMQP message application data section; in\n      binary content mode, event data is placed as-is with attributes mapped\n      to AMQP message properties.\n    humanURL: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md\n      - type: Reference\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/amqp-protocol-binding.md\n\
  \    tags:\n      - AMQP\n      - Messaging\n      - Protocol Binding\n  - aid: cloudevents:cloudevents-mqtt-binding\n    name: CloudEvents MQTT Protocol Binding\n    description: >-\n      The MQTT protocol binding for CloudEvents defines how events are mapped\n      to MQTT 3.1.1 and MQTT 5.0 messages. It supports both structured and\n      binary content modes for IoT and constrained device environments that\n      use MQTT as their messaging protocol.\n    humanURL: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md\n    tags:\n      - IoT\n      - MQTT\n      - Protocol Binding\n  - aid: cloudevents:cloudevents-nats-binding\n    name: CloudEvents NATS Protocol Binding\n    description: >-\n      The NATS protocol\
  \ binding for CloudEvents defines how events are mapped\n      to NATS messages. It enables CloudEvents to be produced and consumed\n      over the NATS messaging system, supporting both publish/subscribe and\n      request/reply patterns.\n    humanURL: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md\n    tags:\n      - Messaging\n      - NATS\n      - Protocol Binding\n  - aid: cloudevents:cloudevents-subscriptions\n    name: CloudEvents Subscriptions API\n    description: >-\n      The CloudEvents Subscriptions API specification defines a standard REST\n      API for managing subscriptions to event streams. It enables clients to\n      create, list, update, and delete subscriptions with filter criteria,\n\
  \      providing a vendor-neutral way to manage event delivery configurations\n      across different event brokers and message systems.\n    humanURL: https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md\n      - type: OpenAPI\n        url: openapi/cloudevents-subscriptions-openapi.yml\n    tags:\n      - REST\n      - Specification\n      - Subscriptions\n  - aid: cloudevents:cloudevents-cesql\n    name: CloudEvents SQL (CESQL)\n    description: >-\n      CloudEvents SQL (CESQL) is a v1.0 specification that defines a\n      standardized query language for filtering and routing CloudEvents based\n      on their attributes. It provides a SQL-like syntax for writing event\n      filter expressions that can be used across different event processing\n      platforms\
  \ and systems.\n    humanURL: https://github.com/cloudevents/spec/blob/main/cesql/spec.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/spec/blob/main/cesql/spec.md\n    tags:\n      - Filtering\n      - Specification\n      - SQL\n  - aid: cloudevents:cloudevents-sdk-go\n    name: CloudEvents Go SDK\n    description: >-\n      The official Go SDK for CloudEvents provides libraries for producing and\n      consuming CloudEvents in Go applications. It supports all CloudEvents\n      protocol bindings and content modes, and includes client implementations\n      for HTTP, Kafka, and other transports.\n    humanURL: https://github.com/cloudevents/sdk-go\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cloudevents.github.io/sdk-go/\n      - type: GitHubRepository\n\
  \        url: https://github.com/cloudevents/sdk-go\n    tags:\n      - Client Library\n      - Go\n      - SDK\n  - aid: cloudevents:cloudevents-sdk-javascript\n    name: CloudEvents JavaScript SDK\n    description: >-\n      The official JavaScript SDK for CloudEvents provides libraries for\n      producing and consuming CloudEvents in Node.js and browser environments.\n      It supports structured and binary content modes over HTTP and other\n      transports.\n    humanURL: https://github.com/cloudevents/sdk-javascript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/sdk-javascript/blob/main/README.md\n      - type: GitHubRepository\n        url: https://github.com/cloudevents/sdk-javascript\n    tags:\n      - Client Library\n      - JavaScript\n      - SDK\n  - aid: cloudevents:cloudevents-sdk-java\n    name: CloudEvents Java SDK\n    description: >-\n\
  \      The official Java SDK for CloudEvents provides libraries for producing\n      and consuming CloudEvents in Java applications. It includes support for\n      HTTP, Kafka, and other transports, and integrates with popular Java\n      frameworks.\n    humanURL: https://github.com/cloudevents/sdk-java\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/sdk-java/blob/main/README.md\n      - type: GitHubRepository\n        url: https://github.com/cloudevents/sdk-java\n    tags:\n      - Client Library\n      - Java\n      - SDK\n  - aid: cloudevents:cloudevents-sdk-python\n    name: CloudEvents Python SDK\n    description: >-\n      The official Python SDK for CloudEvents provides libraries for producing\n      and consuming CloudEvents in Python applications. It supports HTTP\n      transport bindings and both structured and binary content modes.\n    humanURL:\
  \ https://github.com/cloudevents/sdk-python\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/cloudevents/sdk-python/blob/main/README.md\n      - type: GitHubRepository\n        url: https://github.com/cloudevents/sdk-python\n    tags:\n      - Client Library\n      - Python\n      - SDK\ncommon:\n  - type: Website\n    url: https://cloudevents.io\n  - type: Documentation\n    url: https://github.com/cloudevents/spec\n  - type: Getting Started\n    url: https://github.com/cloudevents/spec/blob/main/cloudevents/primer.md\n  - type: Blog\n    url: https://cloudevents.io/blog/\n  - type: GitHubOrganization\n    url: https://github.com/cloudevents\n  - type: SDKs\n    url: https://github.com/cloudevents/spec/blob/main/cloudevents/SDK.md\n  - type: Change Log\n    url: https://github.com/cloudevents/spec/releases\n  - type: JSONSchema\n    url: json-schema/cloudevents-event-schema.json\n\
  \  - type: OpenAPI\n    url: openapi/cloudevents-subscriptions-openapi.yml\n  - type: AsyncAPI\n    url: asyncapi/cloudevents-http-asyncapi.yml\n  - type: JSON-LD\n    url: json-ld/cloudevents-context.jsonld\n  - type: Spectral\n    url: rules/cloudevents-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudevents-subscriptions-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/apis.yml
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
