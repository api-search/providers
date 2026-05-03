---
api_count: 2
api_specs:
- filename: rabbitmq-management.yml
  format: yaml
  label: RabbitMQ Management HTTP API
  slug: rabbitmq-management-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rabbitmq/refs/heads/main/openapi/rabbitmq-management.yml
- filename: rabbitmq-messaging.yml
  format: yaml
  label: RabbitMQ AMQP Messaging API
  slug: rabbitmq-amqp-messaging-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/rabbitmq/refs/heads/main/asyncapi/rabbitmq-messaging.yml
apis:
- description: HTTP-based API for management and monitoring of RabbitMQ nodes and clusters. Allows you to manage exchanges, queues, bindings, users, virtual hosts, permissions, and more.
  name: RabbitMQ Management HTTP API
  slug: rabbitmq-management-http-api
- description: AMQP 0-9-1 messaging protocol for producing and consuming messages via exchanges, queues, and bindings with support for multiple exchange types, message acknowledgment, and consumer groups.
  name: RabbitMQ AMQP Messaging API
  slug: rabbitmq-amqp-messaging-api
asyncapis:
- description: RabbitMQ messaging via AMQP 0-9-1 protocol. Producers publish messages to exchanges which route them to queues based on bindings and routing keys. Consumers subscribe to queues to receive messages.
  name: RabbitMQ AMQP Messaging API
  slug: rabbitmq-messaging
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/rabbitmq
- title: ''
  type: Community
  url: https://www.rabbitmq.com/community.html
- title: ''
  type: Support
  url: https://www.rabbitmq.com/contact.html
- title: ''
  type: Blog
  url: https://www.rabbitmq.com/blog/
- title: ''
  type: Website
  url: https://www.rabbitmq.com/
created: '2024-01-01'
description: RabbitMQ is a widely deployed open source message broker. It supports multiple messaging protocols and can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements.
features: []
image: https://www.rabbitmq.com/img/rabbitmq-logo.svg
integrations: []
layout: provider
modified: '2026-03-26'
name: RabbitMQ
skills: []
slug: rabbitmq
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rabbitmq\nname: RabbitMQ\ndescription: RabbitMQ is a widely deployed open source message broker. It supports multiple messaging protocols and can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements.\ntype: Index\nimage: https://www.rabbitmq.com/img/rabbitmq-logo.svg\nurl: https://raw.githubusercontent.com/api-evangelist/rabbitmq/refs/heads/main/apis.yml\ntags:\n  - AMQP\n  - Distributed Systems\n  - Event Streaming\n  - Message Broker\n  - Messaging\n  - Queue\ncreated: '2024-01-01'\nmodified: '2026-03-26'\nspecificationVersion: '0.19'\napis:\n  - aid: rabbitmq:rabbitmq-management-http-api\n    name: RabbitMQ Management HTTP API\n    description: HTTP-based API for management and monitoring of RabbitMQ nodes and clusters. Allows you to manage exchanges, queues, bindings, users, virtual hosts, permissions, and more.\n    humanURL: https://www.rabbitmq.com/management.html\n    baseURL: http://localhost:15672/api\n  \
  \  tags:\n      - HTTP\n      - Management\n      - Monitoring\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://rawcdn.githack.com/rabbitmq/rabbitmq-server/v3.12.0/deps/rabbitmq_management/priv/www/api/index.html\n      - type: OpenAPI\n        url: openapi/rabbitmq-management.yml\n      - type: Authentication\n        url: https://www.rabbitmq.com/management.html#permissions\n  - aid: rabbitmq:rabbitmq-amqp-messaging-api\n    name: RabbitMQ AMQP Messaging API\n    description: >-\n      AMQP 0-9-1 messaging protocol for producing and consuming messages via\n      exchanges, queues, and bindings with support for multiple exchange types,\n      message acknowledgment, and consumer groups.\n    humanURL: https://www.rabbitmq.com/tutorials/amqp-concepts.html\n    tags:\n      - AMQP\n      - Messaging\n      - Pub-Sub\n      - Queues\n    properties:\n      - type: Documentation\n        url: https://www.rabbitmq.com/tutorials/amqp-concepts.html\n    \
  \  - type: AsyncAPI\n        url: asyncapi/rabbitmq-messaging.yml\n      - type: JSONSchema\n        url: json-schema/rabbitmq-message.json\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/rabbitmq\n  - type: Community\n    url: https://www.rabbitmq.com/community.html\n  - type: Support\n    url: https://www.rabbitmq.com/contact.html\n  - type: Blog\n    url: https://www.rabbitmq.com/blog/\n  - type: Website\n    url: https://www.rabbitmq.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rabbitmq/refs/heads/main/apis.yml
tags:
- AMQP
- Distributed Systems
- Event Streaming
- Message Broker
- Messaging
- Queue
url: https://raw.githubusercontent.com/api-evangelist/rabbitmq/refs/heads/main/apis.yml
use_cases: []
---
