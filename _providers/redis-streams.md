---
api_count: 1
apis:
- description: Redis Streams is a Redis data structure that acts as an append-only log, supporting consumer groups, range queries, and message acknowledgment for building event-driven architectures and real-time dat
  name: Redis Streams
  slug: redis-streams-api
common:
- title: ''
  type: Website
  url: https://redis.io/
- title: ''
  type: Documentation
  url: https://redis.io/docs/latest/develop/data-types/streams/
- title: ''
  type: Getting Started
  url: https://redis.io/docs/latest/get-started/
- title: ''
  type: GitHub
  url: https://github.com/redis/redis
- title: ''
  type: Blog
  url: https://redis.io/blog/
- title: ''
  type: Community
  url: https://redis.io/community/
- title: ''
  type: Commands Reference
  url: https://redis.io/docs/latest/commands/?group=stream
- title: ''
  type: Tutorial
  url: https://redis.io/docs/latest/develop/data-types/streams-tutorial/
created: '2026-03-26'
description: Redis Streams is a data structure in Redis that models an append-only log for managing streams of data, providing consumer groups, message acknowledgment, and the ability to process data in real time with high throughput and low latency.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Redis Streams Context
  property_count: 4
  slug: redis-streams-context
layout: provider
modified: '2026-05-02'
name: Redis Streams
skills: []
slug: redis-streams
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: redis-streams\nname: Redis Streams\ndescription: >-\n  Redis Streams is a data structure in Redis that models an append-only log\n  for managing streams of data, providing consumer groups, message\n  acknowledgment, and the ability to process data in real time with\n  high throughput and low latency.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Consumer Groups\n  - Event-Driven\n  - In-Memory\n  - Messaging\n  - Redis\n  - Streaming\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: redis-streams:redis-streams-api\n    name: Redis Streams\n    description: >-\n      Redis Streams is a Redis data structure that acts as an append-only\n      log, supporting consumer groups, range queries, and message\n      acknowledgment for building event-driven architectures and real-time\n\
  \      data processing pipelines.\n    humanURL: https://redis.io/docs/latest/develop/data-types/streams/\n    tags:\n      - Consumer Groups\n      - Event-Driven\n      - In-Memory\n      - Messaging\n      - Redis\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/latest/develop/data-types/streams/\n      - type: JSONSchema\n        url: json-schema/redis-stream-entry.json\n      - type: JSONSchema\n        url: json-schema/redis-consumer-group.json\n      - type: JSONSchema\n        url: json-schema/redis-stream-info.json\n      - type: JSONStructure\n        url: json-structure/redis-stream-entry-structure.json\n      - type: JSONStructure\n        url: json-structure/redis-consumer-group-structure.json\n      - type: JSONStructure\n        url: json-structure/redis-stream-info-structure.json\n      - type: JSONLd\n        url: json-ld/redis-streams-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/redis-streams-vocabulary.yml\n\
  \ncommon:\n  - type: Website\n    url: https://redis.io/\n  - type: Documentation\n    url: https://redis.io/docs/latest/develop/data-types/streams/\n  - type: Getting Started\n    url: https://redis.io/docs/latest/get-started/\n  - type: GitHub\n    url: https://github.com/redis/redis\n  - type: Blog\n    url: https://redis.io/blog/\n  - type: Community\n    url: https://redis.io/community/\n  - type: Commands Reference\n    url: https://redis.io/docs/latest/commands/?group=stream\n  - type: Tutorial\n    url: https://redis.io/docs/latest/develop/data-types/streams-tutorial/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/apis.yml
tags:
- Consumer Groups
- Event-Driven
- In-Memory
- Messaging
- Redis
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/apis.yml
use_cases: []
---
