---
api_count: 5
api_specs:
- filename: nats-monitoring-api-openapi.yml
  format: yaml
  label: NATS Monitoring API
  slug: nats-monitoring-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/properties/nats-monitoring-api-openapi.yml
- filename: nats-messaging-asyncapi.yml
  format: yaml
  label: NATS Messaging API
  slug: nats-messaging-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/properties/nats-messaging-asyncapi.yml
- filename: nats-jetstream-api-asyncapi.yml
  format: yaml
  label: NATS JetStream Management API
  slug: nats-jetstream-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/properties/nats-jetstream-api-asyncapi.yml
apis:
- description: HTTP monitoring API providing real-time server status, connection information, route details, subscription statistics, JetStream metrics, and health check endpoints for observability and operations.
  name: NATS Monitoring API
  slug: nats-monitoring-api
- description: Asynchronous messaging API supporting core pub-sub, request-reply, queue groups, and JetStream persistent messaging with streams, consumers, key-value stores, and object stores.
  name: NATS Messaging API
  slug: nats-messaging-api
- description: 'The JetStream wire API provides a protocol-level management interface for configuring and operating JetStream streams, consumers, key-value buckets, and object stores. Requests are made by publishing '
  name: NATS JetStream Management API
  slug: nats-jetstream-api
- description: The NATS Key-Value Store API is a JetStream-backed abstraction that provides immediately consistent, persistent associative array semantics. Clients can create buckets, get, put, delete, and watch key
  name: NATS Key-Value Store API
  slug: nats-kv-api
- description: The NATS Object Store API is a JetStream-backed abstraction for storing and retrieving arbitrarily large binary objects using a chunking mechanism. Objects are identified by a bucket and a name, and t
  name: NATS Object Store API
  slug: nats-object-store-api
asyncapis:
- description: NATS provides cloud-native messaging with core pub-sub, request-reply, and queue group patterns, plus JetStream for persistent streaming with streams, consumers, key-value stores, and object stores.
  name: NATS Core and JetStream Messaging API
  slug: nats-messaging
common:
- title: ''
  type: Website
  url: https://nats.io
- title: ''
  type: Documentation
  url: https://docs.nats.io
- title: ''
  type: Getting Started
  url: https://docs.nats.io/running-a-nats-service/introduction/installation
- title: ''
  type: GitHub Repository
  url: https://github.com/nats-io/nats-server
- title: ''
  type: Blog
  url: https://nats.io/blog/
- title: ''
  type: Slack
  url: https://slack.nats.io
- title: ''
  type: Issues
  url: https://github.com/nats-io/nats-server/issues
- title: ''
  type: Change Log
  url: https://github.com/nats-io/nats-server/releases
- title: ''
  type: Examples
  url: https://natsbyexample.com
- title: ''
  type: CLI
  url: https://docs.nats.io/using-nats/nats-tools/nats_cli
- title: ''
  type: GitHub Organization
  url: https://github.com/nats-io
- title: ''
  type: JSONSchema
  url: properties/nats-server-config-json-schema.json
- title: ''
  type: JSONSchema
  url: properties/nats-jetstream-config-json-schema.json
- title: ''
  type: JSONSchema
  url: properties/nats-kv-schema.json
- title: ''
  type: JSONSchema
  url: properties/nats-object-store-schema.json
- title: ''
  type: JSON-LD
  url: properties/nats-context-jsonld.json
- title: ''
  type: Support
  url: https://nats.io/support/
- title: ''
  type: Privacy Policy
  url: https://nats.io/privacy/
- title: ''
  type: Community
  url: https://nats.io/community/
- title: ''
  type: SDKs
  url: https://docs.nats.io/using-nats/developer
- title: ''
  type: Download
  url: https://nats.io/download/
created: '2025-01-01'
description: A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-02'
name: NATS
skills: []
slug: nats
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nats\nname: NATS\ndescription: A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - IoT\n  - Message Broker\n  - Microservices\n  - Pub Sub\nurl: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: nats:nats-monitoring-api\n    name: NATS Monitoring API\n    description: HTTP monitoring API providing real-time server status, connection information, route details, subscription statistics, JetStream metrics, and health check endpoints for observability and operations.\n    humanURL: https://docs.nats.io/running-a-nats-service/nats_admin/monitoring\n    baseURL: http://localhost:8222\n\
  \    tags:\n      - Health\n      - Metrics\n      - Monitoring\n    properties:\n      - url: https://docs.nats.io/running-a-nats-service/nats_admin/monitoring\n        type: Documentation\n      - url: properties/nats-monitoring-api-openapi.yml\n        type: OpenAPI\n      - url: openapi/nats-monitoring.yml\n        type: OpenAPI\n  - aid: nats:nats-messaging-api\n    name: NATS Messaging API\n    description: Asynchronous messaging API supporting core pub-sub, request-reply, queue groups, and JetStream persistent messaging with streams, consumers, key-value stores, and object stores.\n    humanURL: https://docs.nats.io/nats-concepts/core-nats\n    tags:\n      - JetStream\n      - Messaging\n      - Pub Sub\n      - Streaming\n    properties:\n      - url: https://docs.nats.io/nats-concepts/core-nats\n        type: Documentation\n      - url: properties/nats-messaging-asyncapi.yml\n        type: AsyncAPI\n      - url: asyncapi/nats-messaging.yml\n        type: AsyncAPI\n      - url:\
  \ json-schema/nats-stream-config.json\n        type: JSONSchema\n  - aid: nats:nats-jetstream-api\n    name: NATS JetStream Management API\n    description: >-\n      The JetStream wire API provides a protocol-level management interface for\n      configuring and operating JetStream streams, consumers, key-value buckets,\n      and object stores. Requests are made by publishing to well-known\n      $JS.API.* subjects and responses are returned as typed JSON payloads.\n      This API underlies all official NATS client SDKs and the nats CLI.\n    humanURL: https://docs.nats.io/reference/reference-protocols/nats_api_reference\n    tags:\n      - JetStream\n      - Management\n      - Streaming\n    properties:\n      - url: https://docs.nats.io/reference/reference-protocols/nats_api_reference\n        type: Documentation\n      - url: https://docs.nats.io/nats-concepts/jetstream\n        type: Reference\n      - url: properties/nats-jetstream-api-asyncapi.yml\n        type: AsyncAPI\n   \
  \   - url: properties/nats-jetstream-config-json-schema.json\n        type: JSONSchema\n  - aid: nats:nats-kv-api\n    name: NATS Key-Value Store API\n    description: >-\n      The NATS Key-Value Store API is a JetStream-backed abstraction that\n      provides immediately consistent, persistent associative array semantics.\n      Clients can create buckets, get, put, delete, and watch keys, and receive\n      real-time change notifications. Buckets are implemented as JetStream\n      streams with the KV_ prefix.\n    humanURL: https://docs.nats.io/nats-concepts/jetstream/key-value-store\n    tags:\n      - JetStream\n      - Key-Value\n      - Storage\n    properties:\n      - url: https://docs.nats.io/nats-concepts/jetstream/key-value-store\n        type: Documentation\n      - url: https://docs.nats.io/using-nats/developer/develop_jetstream/kv\n        type: Reference\n      - url: properties/nats-kv-schema.json\n        type: JSONSchema\n  - aid: nats:nats-object-store-api\n    name:\
  \ NATS Object Store API\n    description: >-\n      The NATS Object Store API is a JetStream-backed abstraction for storing\n      and retrieving arbitrarily large binary objects using a chunking mechanism.\n      Objects are identified by a bucket and a name, and the API supports put,\n      get, delete, and watch operations for managing stored files and blobs.\n    humanURL: https://docs.nats.io/nats-concepts/jetstream/obj_store\n    tags:\n      - JetStream\n      - Object Store\n      - Storage\n    properties:\n      - url: https://docs.nats.io/nats-concepts/jetstream/obj_store\n        type: Documentation\n      - url: https://docs.nats.io/using-nats/developer/develop_jetstream/object\n        type: Reference\n      - url: properties/nats-object-store-schema.json\n        type: JSONSchema\ncommon:\n  - url: https://nats.io\n    type: Website\n  - url: https://docs.nats.io\n    type: Documentation\n  - url: https://docs.nats.io/running-a-nats-service/introduction/installation\n  \
  \  type: Getting Started\n  - url: https://github.com/nats-io/nats-server\n    type: GitHub Repository\n  - url: https://nats.io/blog/\n    type: Blog\n  - url: https://slack.nats.io\n    type: Slack\n  - url: https://github.com/nats-io/nats-server/issues\n    type: Issues\n  - url: https://github.com/nats-io/nats-server/releases\n    type: Change Log\n  - url: https://natsbyexample.com\n    type: Examples\n  - url: https://docs.nats.io/using-nats/nats-tools/nats_cli\n    type: CLI\n  - url: https://github.com/nats-io\n    type: GitHub Organization\n  - url: properties/nats-server-config-json-schema.json\n    type: JSONSchema\n  - url: properties/nats-jetstream-config-json-schema.json\n    type: JSONSchema\n  - url: properties/nats-kv-schema.json\n    type: JSONSchema\n  - url: properties/nats-object-store-schema.json\n    type: JSONSchema\n  - url: properties/nats-context-jsonld.json\n    type: JSON-LD\n  - url: https://nats.io/support/\n    type: Support\n  - url: https://nats.io/privacy/\n\
  \    type: Privacy Policy\n  - url: https://nats.io/community/\n    type: Community\n  - url: https://docs.nats.io/using-nats/developer\n    type: SDKs\n  - url: https://nats.io/download/\n    type: Download\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml
tags:
- Cloud Native
- IoT
- Message Broker
- Microservices
- Pub Sub
url: https://raw.githubusercontent.com/api-evangelist/nats/refs/heads/main/apis.yml
use_cases: []
---
