---
api_count: 3
api_specs:
- filename: krakend-service-api-openapi.yml
  format: yaml
  label: KrakenD Service API
  slug: krakend-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/openapi/krakend-service-api-openapi.yml
apis:
- description: KrakenD Community Edition is an ultra-high performance API gateway that aggregates multiple service calls into a single endpoint, transforming and filtering responses with a declarative JSON configura
  name: KrakenD
  slug: krakend
- description: The KrakenD Service API exposes built-in operational endpoints on a running KrakenD gateway instance. It includes the health check endpoint at /__health (enabled by default), the debug endpoint at /__
  name: KrakenD Service API
  slug: krakend-service-api
- description: 'The KrakenD Async Agent enables event-driven API consumption by connecting KrakenD to message brokers and event queues such as AMQP, Kafka, and NATS. It allows KrakenD to consume messages from topics '
  name: KrakenD Async Agent
  slug: krakend-async-agent
common:
- title: ''
  type: Website
  url: https://www.krakend.io/
- title: ''
  type: Documentation
  url: https://www.krakend.io/docs/
- title: ''
  type: Getting Started
  url: https://www.krakend.io/docs/overview/introduction/
- title: ''
  type: Blog
  url: https://www.krakend.io/blog/
- title: ''
  type: Change Log
  url: https://github.com/krakend/krakend-ce/releases
- title: ''
  type: GitHub Organization
  url: https://github.com/krakend
- title: ''
  type: GitHubRepository
  url: https://github.com/krakend/krakend-ce
- title: ''
  type: Community
  url: https://community.krakend.io/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/krakend
- title: ''
  type: Issue Tracker
  url: https://github.com/krakend/krakend-ce/issues
- title: ''
  type: Developer Tools
  url: https://designer.krakend.io/
- title: ''
  type: JSONSchema
  url: json-schema/service-config.json
- title: ''
  type: JSON-LD
  url: json-ld/krakend-context.jsonld
created: '2026-03-18'
description: KrakenD is a stateless, distributed, high-performance open-source API gateway written in Go, focused on API aggregation, transformation, and security with a declarative configuration approach.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Krakend Context
  property_count: 6
  slug: krakend-context
layout: provider
modified: '2026-04-28'
name: KrakenD
skills: []
slug: krakend
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: krakend\nname: KrakenD\ndescription: >-\n  KrakenD is a stateless, distributed, high-performance open-source API\n  gateway written in Go, focused on API aggregation, transformation, and\n  security with a declarative configuration approach.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Aggregation\n  - API Gateway\n  - Go\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: krakend:krakend\n    name: KrakenD\n    description: >-\n      KrakenD Community Edition is an ultra-high performance API gateway that\n      aggregates multiple service calls into a single endpoint, transforming\n      and filtering responses with a declarative JSON configuration.\n    humanURL: https://www.krakend.io/\n    tags:\n      - Aggregation\n      - API Gateway\n      - Go\n   \
  \ properties:\n      - type: Documentation\n        url: https://www.krakend.io/docs/overview/\n      - type: Getting Started\n        url: https://www.krakend.io/docs/overview/introduction/\n      - type: Reference\n        url: https://www.krakend.io/docs/configuration/structure/\n      - type: Change Log\n        url: https://github.com/krakend/krakend-ce/releases\n      - type: GitHubRepository\n        url: https://github.com/krakend/krakend-ce\n      - type: JSONSchema\n        url: json-schema/service-config.json\n      - type: JSON-LD\n        url: json-ld/krakend-context.jsonld\n  - aid: krakend:krakend-service-api\n    name: KrakenD Service API\n    description: >-\n      The KrakenD Service API exposes built-in operational endpoints on a\n      running KrakenD gateway instance. It includes the health check endpoint\n      at /__health (enabled by default), the debug endpoint at /__debug\n      (enabled via configuration), and the extended metrics endpoint at\n      /__stats\
  \ for detailed runtime telemetry. These endpoints are used for\n      monitoring, debugging, and health checking KrakenD deployments.\n    humanURL: https://www.krakend.io/docs/service-settings/health/\n    baseURL: http://localhost:8080\n    tags:\n      - Health Check\n      - Monitoring\n      - Observability\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://www.krakend.io/docs/service-settings/health/\n      - type: Reference\n        url: https://www.krakend.io/docs/service-settings/debug-endpoint/\n      - type: OpenAPI\n        url: openapi/krakend-service-api-openapi.yml\n  - aid: krakend:krakend-async-agent\n    name: KrakenD Async Agent\n    description: >-\n      The KrakenD Async Agent enables event-driven API consumption by\n      connecting KrakenD to message brokers and event queues such as AMQP,\n      Kafka, and NATS. It allows KrakenD to consume messages from topics and\n      queues and forward them to backend services without requiring\
  \ an inbound\n      HTTP request from a client.\n    humanURL: https://www.krakend.io/docs/async/\n    tags:\n      - Async\n      - Event-Driven\n      - Kafka\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://www.krakend.io/docs/async/\n      - type: Reference\n        url: https://www.krakend.io/docs/async/amqp/\n      - type: JSONSchema\n        url: json-schema/async-agent.json\n      - type: GitHubRepository\n        url: https://github.com/krakend/krakend-ce\ncommon:\n  - type: Website\n    url: https://www.krakend.io/\n  - type: Documentation\n    url: https://www.krakend.io/docs/\n  - type: Getting Started\n    url: https://www.krakend.io/docs/overview/introduction/\n  - type: Blog\n    url: https://www.krakend.io/blog/\n  - type: Change Log\n    url: https://github.com/krakend/krakend-ce/releases\n  - type: GitHub Organization\n    url: https://github.com/krakend\n  - type: GitHubRepository\n    url: https://github.com/krakend/krakend-ce\n\
  \  - type: Community\n    url: https://community.krakend.io/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/krakend\n  - type: Issue Tracker\n    url: https://github.com/krakend/krakend-ce/issues\n  - type: Developer Tools\n    url: https://designer.krakend.io/\n  - type: JSONSchema\n    url: json-schema/service-config.json\n  - type: JSON-LD\n    url: json-ld/krakend-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml
tags:
- Aggregation
- API Gateway
- Go
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml
use_cases: []
---
