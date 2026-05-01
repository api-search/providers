---
api_count: 7
api_specs:
- filename: fauna-core-http-api-openapi.yml
  format: yaml
  label: Fauna Core HTTP API
  slug: core-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/openapi/fauna-core-http-api-openapi.yml
- filename: fauna-event-streaming-asyncapi.yml
  format: yaml
  label: Fauna Event Streaming API
  slug: event-streaming-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/asyncapi/fauna-event-streaming-asyncapi.yml
- filename: fauna-graphql-api-openapi.yml
  format: yaml
  label: Fauna GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/openapi/fauna-graphql-api-openapi.yml
apis:
- description: 'The Fauna Core HTTP API provides direct access to the Fauna serverless document database through HTTPS endpoints. It allows developers to execute Fauna Query Language (FQL) queries, manage databases, '
  name: Fauna Core HTTP API
  slug: core-http-api
- description: The Fauna Event Streaming API enables real-time change data capture by maintaining an open connection to the Fauna database and pushing events to clients as they occur. Developers can subscribe to doc
  name: Fauna Event Streaming API
  slug: event-streaming-api
- description: The Fauna Event Feeds API provides a polling-based approach to change data capture, complementing the real-time Event Streaming API. Event feeds allow developers to retrieve batches of change events a
  name: Fauna Event Feeds API
  slug: event-feeds-api
- description: 'The Fauna GraphQL API allows developers to interact with their Fauna databases using standard GraphQL queries and mutations. By uploading a GraphQL schema, Fauna automatically generates the necessary '
  name: Fauna GraphQL API
  slug: graphql-api
- description: The Fauna JavaScript Driver is the official client SDK for interacting with Fauna from JavaScript and TypeScript applications. It provides template-based FQL query interpolation with type safety and a
  name: Fauna JavaScript Driver
  slug: javascript-driver
- description: The Fauna Python Driver is the official client SDK for accessing Fauna from Python applications. It provides idiomatic Python interfaces for composing and executing FQL v10 queries, managing authentic
  name: Fauna Python Driver
  slug: python-driver
- description: The Fauna .NET Driver is the official client SDK for interacting with Fauna from C# and .NET applications. It is designed for use with FQL v10 and provides strongly-typed query construction and respon
  name: Fauna .NET Driver
  slug: dotnet-driver
asyncapis:
- description: The Fauna Event Streaming API enables real-time change data capture by maintaining an open connection to the Fauna database and pushing events to clients as they occur. Developers can subscribe to doc
  name: Fauna Event Streaming
  slug: fauna-event-streaming-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/fauna-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/fauna-document-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fauna-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fauna-query-schema.json
created: ''
description: Fauna is a distributed document-relational database delivered as a cloud API that combines the relational query power of SQL with the flexibility of documents and global serverless distribution.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Fauna Context
  property_count: 9
  slug: fauna-context
layout: provider
modified: '2026-04-28'
name: fauna
skills: []
slug: fauna
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fauna\nurl: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: fauna:core-http-api\n    name: Fauna Core HTTP API\n    tags:\n      - Database\n      - Document Database\n      - NoSQL\n      - Queries\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://db.fauna.com\n    humanURL: https://docs.fauna.com/fauna/current/reference/http/reference/core-api/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/reference/http/reference/core-api/\n        type: Documentation\n      - url: openapi/fauna-core-http-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fauna Core HTTP API provides direct access to the Fauna serverless\n      document database through HTTPS endpoints. It allows developers to execute\n      Fauna Query Language (FQL) queries, manage databases, and perform CRUD\n      operations\
  \ on documents. The API uses token-based authentication and\n      supports features such as transactions, indexes, and set operations. It\n      serves as the foundation upon which Fauna's client drivers and SDKs are\n      built.\n  - aid: fauna:event-streaming-api\n    name: Fauna Event Streaming API\n    tags:\n      - Change Data Capture\n      - Database\n      - Events\n      - Real-Time\n      - Streaming\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://db.fauna.com\n    humanURL: https://docs.fauna.com/fauna/current/reference/streaming/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/reference/streaming/\n        type: Documentation\n      - url: asyncapi/fauna-event-streaming-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Fauna Event Streaming API enables real-time change data capture by\n      maintaining an open connection to the Fauna database and pushing events to\n     \
  \ clients as they occur. Developers can subscribe to document or set changes\n      and receive add, remove, and update events in real time. The API supports\n      reconnection with a start timestamp to avoid missing events during\n      disconnections. It is accessible via the /stream/1 HTTP endpoint with\n      token-based authentication.\n  - aid: fauna:event-feeds-api\n    name: Fauna Event Feeds API\n    tags:\n      - Change Data Capture\n      - Database\n      - Events\n      - Polling\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://db.fauna.com\n    humanURL: https://docs.fauna.com/fauna/current/learn/cdc/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/learn/cdc/\n        type: Documentation\n    description: >-\n      The Fauna Event Feeds API provides a polling-based approach to change data\n      capture, complementing the real-time Event Streaming API. Event feeds\n      allow developers to\
  \ retrieve batches of change events at their own pace\n      rather than maintaining a persistent connection. This is useful for\n      scheduled synchronization tasks, batch processing workflows, and\n      scenarios where a pull-based model is preferred over push-based streaming.\n      Event feeds track the same add, remove, and update events as streams.\n  - aid: fauna:graphql-api\n    name: Fauna GraphQL API\n    tags:\n      - Database\n      - GraphQL\n      - Query Language\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://graphql.fauna.com\n    humanURL: https://docs.fauna.com/fauna/current/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/\n        type: Documentation\n      - url: openapi/fauna-graphql-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fauna GraphQL API allows developers to interact with their Fauna\n      databases using standard GraphQL queries\
  \ and mutations. By uploading a\n      GraphQL schema, Fauna automatically generates the necessary collections,\n      indexes, and resolvers. This API can be used from any programming language\n      or HTTP client without requiring a dedicated Fauna driver. It provides an\n      alternative to FQL for developers who prefer the GraphQL query paradigm\n      and ecosystem tooling.\n  - aid: fauna:javascript-driver\n    name: Fauna JavaScript Driver\n    tags:\n      - Driver\n      - JavaScript\n      - Node.js\n      - SDK\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.fauna.com/fauna/current/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/\n        type: Documentation\n    description: >-\n      The Fauna JavaScript Driver is the official client SDK for interacting\n      with Fauna from JavaScript and TypeScript applications. It provides\n\
  \      template-based FQL query interpolation with type safety and a secure wire\n      protocol that prevents injection vulnerabilities. The driver supports both\n      Node.js server environments and browser-based applications, and includes\n      built-in support for event streaming with automatic reconnection handling.\n  - aid: fauna:python-driver\n    name: Fauna Python Driver\n    tags:\n      - Driver\n      - Python\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.fauna.com/fauna/current/\n    properties:\n      - url: https://docs.fauna.com/fauna/current/\n        type: Documentation\n    description: >-\n      The Fauna Python Driver is the official client SDK for accessing Fauna\n      from Python applications. It provides idiomatic Python interfaces for\n      composing and executing FQL v10 queries, managing authentication tokens,\n      and handling pagination.\
  \ The driver includes support for event streaming\n      and event feeds, allowing Python developers to build real-time and\n      batch-oriented data processing pipelines against Fauna databases.\n  - aid: fauna:dotnet-driver\n    name: Fauna .NET Driver\n    tags:\n      - .NET\n      - C#\n      - Driver\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://github.com/fauna/fauna-dotnet\n    properties:\n      - url: https://github.com/fauna/fauna-dotnet\n        type: Documentation\n    description: >-\n      The Fauna .NET Driver is the official client SDK for interacting with\n      Fauna from C# and .NET applications. It is designed for use with FQL v10\n      and provides strongly-typed query construction and response handling. The\n      driver enables .NET developers to perform document operations, run\n      queries, and manage database resources using familiar C# patterns\
  \ and\n      conventions.\ncommon:\n  - type: JSON-LD\n    url: json-ld/fauna-context.jsonld\n  - type: JSONSchema\n    url: json-schema/fauna-document-schema.json\n  - type: JSONSchema\n    url: json-schema/fauna-event-schema.json\n  - type: JSONSchema\n    url: json-schema/fauna-query-schema.json\ndescription: >-\n  Fauna is a distributed document-relational database delivered as a cloud API that\n  combines the relational query power of SQL with the flexibility of documents and\n  global serverless distribution.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/apis.yml
use_cases: []
---
