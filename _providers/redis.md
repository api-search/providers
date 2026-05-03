---
api_count: 4
apis:
- description: Core Redis commands and data structure operations. Redis supports strings, hashes, lists, sets, sorted sets, streams, and more. The primary interface is the Redis Serialization Protocol (RESP) over TC
  name: Redis Core
  slug: redis-core
- description: The Redis Cloud REST API for managing subscriptions, databases, cloud accounts, access control, and logs on the Redis Cloud platform. Available at api.redislabs.com/v1 with API key authentication.
  name: Redis Cloud API
  slug: redis-cloud-api
- description: REST API for managing Redis Enterprise Software clusters. Provides endpoints for cluster configuration, database creation and management, user access control, and monitoring. Available at the cluster'
  name: Redis Enterprise API
  slug: redis-enterprise-api
- description: Redis Insight is a free GUI management tool for Redis. Provides database browsing, query execution, memory analysis, slow log inspection, and Redis Streams visualization. Available as a desktop app an
  name: Redis Insight
  slug: redis-insight
common:
- title: ''
  type: Website
  url: https://redis.io/
- title: ''
  type: Documentation
  url: https://redis.io/docs/
- title: ''
  type: GitHubOrg
  url: https://github.com/redis
- title: ''
  type: Blog
  url: https://redis.io/blog/
- title: ''
  type: Community
  url: https://redis.io/community/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/redis/
- title: ''
  type: X
  url: https://twitter.com/redisinc
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/Redisinc
- title: ''
  type: Status
  url: https://status.redis.com/
- title: ''
  type: Support
  url: https://redis.io/support/
- title: ''
  type: TermsOfService
  url: https://redis.io/legal/terms/
- title: ''
  type: PrivacyPolicy
  url: https://redis.io/legal/privacy/
- title: ''
  type: Documentation
  url: https://redis.io/docs/latest/commands/
- title: ''
  type: SDKs
  url: https://redis.io/docs/latest/develop/connect/clients/
- title: ''
  type: npm
  url: https://www.npmjs.com/package/redis
- title: ''
  type: PyPI
  url: https://pypi.org/project/redis/
created: '2024-01-01'
description: Redis is an open source, in-memory data structure store used as a database, cache, message broker, and streaming engine. It supports strings, hashes, lists, sets, sorted sets, streams, JSON, and more. Redis is used by millions of developers for caching, session management, leaderboards, pub/sub messaging, real-time analytics, and event streaming. The Redis project is governed by the Redis Community and maintained by Redis Inc.
features: []
image: https://redis.io/images/redis-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Redis Context
  property_count: 3
  slug: redis-context
layout: provider
modified: '2026-05-02'
name: Redis
skills: []
slug: redis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: redis\nname: Redis\ndescription: >-\n  Redis is an open source, in-memory data structure store used as a database,\n  cache, message broker, and streaming engine. It supports strings, hashes,\n  lists, sets, sorted sets, streams, JSON, and more. Redis is used by millions\n  of developers for caching, session management, leaderboards, pub/sub\n  messaging, real-time analytics, and event streaming. The Redis project is\n  governed by the Redis Community and maintained by Redis Inc.\ntype: Index\nimage: https://redis.io/images/redis-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/apis.yml\ntags:\n  - Cache\n  - Database\n  - In-Memory\n  - Key-Value Store\n  - NoSQL\n  - Open Source\n  - Streaming\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: redis:redis-core\n    name: Redis Core\n    description: >-\n      Core Redis commands and data structure operations. Redis supports strings,\n   \
  \   hashes, lists, sets, sorted sets, streams, and more. The primary interface\n      is the Redis Serialization Protocol (RESP) over TCP, with client libraries\n      for all major programming languages.\n    humanURL: https://redis.io/docs/latest/commands/\n    tags:\n      - Cache\n      - Commands\n      - Core\n      - Database\n      - Key-Value\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/latest/commands/\n      - type: GettingStarted\n        url: https://redis.io/docs/latest/get-started/\n      - type: GitHub\n        url: https://github.com/redis/redis\n      - type: JSONSchema\n        url: json-schema/redis-key-value-schema.json\n      - type: JSONSchema\n        url: json-schema/redis-command-schema.json\n      - type: JSONSchema\n        url: json-schema/redis-server-info-schema.json\n      - type: JSONStructure\n        url: json-structure/redis-key-value-structure.json\n      - type: JSONStructure\n        url: json-structure/redis-server-info-structure.json\n\
  \      - type: JSONLd\n        url: json-ld/redis-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/redis-vocabulary.yml\n\n  - aid: redis:redis-cloud-api\n    name: Redis Cloud API\n    description: >-\n      The Redis Cloud REST API for managing subscriptions, databases, cloud\n      accounts, access control, and logs on the Redis Cloud platform.\n      Available at api.redislabs.com/v1 with API key authentication.\n    humanURL: https://redis.io/docs/latest/operate/rc/api/\n    tags:\n      - Cloud\n      - Management\n      - REST\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/latest/operate/rc/api/\n      - type: Authentication\n        url: https://redis.io/docs/latest/operate/rc/api/get-started/\n      - type: Examples\n        url: https://redis.io/docs/latest/operate/rc/api/examples/\n\n  - aid: redis:redis-enterprise-api\n    name: Redis Enterprise API\n    description: >-\n      REST API for managing Redis\
  \ Enterprise Software clusters. Provides\n      endpoints for cluster configuration, database creation and management,\n      user access control, and monitoring. Available at the cluster's port 9443.\n    humanURL: https://redis.io/docs/latest/operate/rs/references/rest-api/\n    tags:\n      - Cluster\n      - Enterprise\n      - Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/latest/operate/rs/references/rest-api/\n      - type: APIReference\n        url: https://redis.io/docs/latest/operate/rs/references/rest-api/requests/\n\n  - aid: redis:redis-insight\n    name: Redis Insight\n    description: >-\n      Redis Insight is a free GUI management tool for Redis. Provides database\n      browsing, query execution, memory analysis, slow log inspection, and\n      Redis Streams visualization. Available as a desktop app and Docker image.\n    humanURL: https://redis.io/docs/latest/develop/tools/insight/\n    tags:\n      - Developer\
  \ Tools\n      - Management\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/latest/develop/tools/insight/\n      - type: Download\n        url: https://redis.io/insight/\n      - type: Docker\n        url: https://hub.docker.com/r/redis/redisinsight\n\ncommon:\n  - name: Redis Website\n    url: https://redis.io/\n    type: Website\n  - name: Redis Documentation\n    url: https://redis.io/docs/\n    type: Documentation\n  - name: Redis GitHub Organization\n    url: https://github.com/redis\n    type: GitHubOrg\n  - name: Redis Blog\n    url: https://redis.io/blog/\n    type: Blog\n  - name: Redis Community\n    url: https://redis.io/community/\n    type: Community\n  - name: Redis on LinkedIn\n    url: https://www.linkedin.com/company/redis/\n    type: LinkedIn\n  - name: Redis on X\n    url: https://twitter.com/redisinc\n    type: X\n  - name: Redis YouTube\n    url: https://www.youtube.com/c/Redisinc\n    type: YouTube\n  - name:\
  \ Redis Status\n    url: https://status.redis.com/\n    type: Status\n  - name: Redis Support\n    url: https://redis.io/support/\n    type: Support\n  - name: Redis Terms of Service\n    url: https://redis.io/legal/terms/\n    type: TermsOfService\n  - name: Redis Privacy Policy\n    url: https://redis.io/legal/privacy/\n    type: PrivacyPolicy\n  - name: Redis Command Reference\n    url: https://redis.io/docs/latest/commands/\n    type: Documentation\n  - name: Redis Client Libraries\n    url: https://redis.io/docs/latest/develop/connect/clients/\n    type: SDKs\n  - name: Redis npm Package\n    url: https://www.npmjs.com/package/redis\n    type: npm\n  - name: Redis PyPI Package\n    url: https://pypi.org/project/redis/\n    type: PyPI\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/apis.yml
tags:
- Cache
- Database
- In-Memory
- Key-Value Store
- NoSQL
- Open Source
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/apis.yml
use_cases: []
---
