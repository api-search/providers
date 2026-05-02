---
api_count: 2
api_specs:
- filename: linear-graphql-openapi.yml
  format: yaml
  label: Linear GraphQL API
  slug: linear-graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/openapi/linear-graphql-openapi.yml
- filename: linear-webhooks-asyncapi.yml
  format: yaml
  label: Linear Webhooks API
  slug: linear-webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/asyncapi/linear-webhooks-asyncapi.yml
apis:
- description: Linear's public GraphQL API provides full access to create, read, update, and query issues, projects, cycles, roadmaps, and teams. It is the same API Linear uses internally for its own applications, s
  name: Linear GraphQL API
  slug: linear-graphql-api
- description: Linear webhooks deliver HTTP push notifications whenever data is created, updated, or removed. Webhooks are organization-scoped and can be configured for all public teams or a single team, enabling in
  name: Linear Webhooks API
  slug: linear-webhooks-api
asyncapis:
- description: Linear webhooks deliver HTTP push notifications whenever data is created, updated, or removed. Webhooks are organization-scoped and can be configured for all public teams or a single team, enabling in
  name: Linear Webhooks API
  slug: linear-webhooks-asyncapi
common:
- title: ''
  type: Portal
  url: https://linear.app/developers
- title: ''
  type: Getting Started
  url: https://linear.app/developers/graphql
- title: ''
  type: Authentication
  url: https://linear.app/developers/oauth-2-0-authentication
- title: ''
  type: Rate Limits
  url: https://linear.app/developers/rate-limiting
- title: ''
  type: Change Log
  url: https://linear.app/changelog
- title: ''
  type: Deprecation Notice
  url: https://linear.app/developers/deprecations
- title: ''
  type: Migration Guide
  url: https://linear.app/developers/migrating-from-1-x-to-2-x
- title: ''
  type: Support
  url: https://linear.app/contact/support
- title: ''
  type: Website
  url: https://linear.app
- title: ''
  type: SDKs
  url: https://www.npmjs.com/package/@linear/sdk
- title: ''
  type: GitHub Organization
  url: https://github.com/linear/linear
- title: ''
  type: GitHubRepository
  url: https://github.com/linear/linear/tree/master/packages/sdk
- title: ''
  type: Developer Tools
  url: https://linear.app/developers/integration-directory
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/openapi/linear-graphql-openapi.yml
- title: ''
  type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/asyncapi/linear-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-schema/linear-issue-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-ld/linear-context.jsonld
created: ''
description: Linear's public API is built using GraphQL. It's the same API we use internally for developing our applications. If you are new to GraphQL, Apollo has resources for beginners. The official GraphQL documentation is another good starting point.
features: []
image: ''
integrations: []
jsonld:
- class_count: 17
  name: Linear Context
  property_count: 11
  slug: linear-context
layout: provider
modified: '2026-04-28'
name: linear
skills: []
slug: linear
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linear\nurl: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/apis.yml\nmodified: '2026-04-28'\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\napis:\n  - aid: linear:linear-graphql-api\n    name: Linear GraphQL API\n    tags:\n      - Agile\n      - GraphQL\n      - Issue Tracking\n      - Project Management\n    image: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/image.png\n    humanURL: https://linear.app/developers/graphql\n    baseURL: https://api.linear.app/graphql\n    properties:\n      - url: https://linear.app/developers/graphql\n        type: Documentation\n      - url: https://studio.apollographql.com/public/Linear-API/schema/reference?variant=current\n        type: Reference\n      - url: https://linear.app/developers/oauth-2-0-authentication\n        type: Authentication\n      - url: https://linear.app/developers/sdk\n        type: Getting Started\n      - url: https://linear.app/developers/rate-limiting\n\
  \        type: Rate Limits\n      - url: https://linear.app/developers/pagination\n        type: Pagination\n      - url: https://linear.app/developers/filtering\n        type: Filtering\n      - url: https://linear.app/developers/deprecations\n        type: Deprecation Notice\n      - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/openapi/linear-graphql-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-schema/linear-issue-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-ld/linear-context.jsonld\n        type: JSONLDContext\n    description: >-\n      Linear's public GraphQL API provides full access to create, read, update, and\n      query issues, projects, cycles, roadmaps, and teams. It is the same API Linear\n      uses internally for its own applications, supporting pagination, filtering,\n      attachments,\
  \ and file uploads.\n  - aid: linear:linear-webhooks-api\n    name: Linear Webhooks API\n    tags:\n      - Events\n      - Real-Time\n      - Webhooks\n    image: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/image.png\n    humanURL: https://linear.app/developers/webhooks\n    baseURL: https://api.linear.app/graphql\n    properties:\n      - url: https://linear.app/developers/webhooks\n        type: Documentation\n      - url: https://linear.app/developers/sdk-webhooks\n        type: Getting Started\n      - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/asyncapi/linear-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Linear webhooks deliver HTTP push notifications whenever data is created,\n      updated, or removed. Webhooks are organization-scoped and can be configured\n      for all public teams or a single team, enabling integrations that trigger\n      CI builds, update external systems, or send messages\
  \ based on issue activity.\ncommon:\n  - url: https://linear.app/developers\n    type: Portal\n  - url: https://linear.app/developers/graphql\n    type: Getting Started\n  - url: https://linear.app/developers/oauth-2-0-authentication\n    type: Authentication\n  - url: https://linear.app/developers/rate-limiting\n    type: Rate Limits\n  - url: https://linear.app/changelog\n    type: Change Log\n  - url: https://linear.app/developers/deprecations\n    type: Deprecation Notice\n  - url: https://linear.app/developers/migrating-from-1-x-to-2-x\n    type: Migration Guide\n  - url: https://linear.app/contact/support\n    type: Support\n  - url: https://linear.app\n    type: Website\n  - url: https://www.npmjs.com/package/@linear/sdk\n    type: SDKs\n  - url: https://github.com/linear/linear\n    type: GitHub Organization\n  - url: https://github.com/linear/linear/tree/master/packages/sdk\n    type: GitHubRepository\n  - url: https://linear.app/developers/integration-directory\n    type: Developer\
  \ Tools\n  - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/openapi/linear-graphql-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/asyncapi/linear-webhooks-asyncapi.yml\n    type: AsyncAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-schema/linear-issue-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-ld/linear-context.jsonld\n    type: JSONLDContext\ndescription: >-\n  Linear's public API is built using GraphQL. It's the same API we use internally\n  for developing our applications. If you are new to GraphQL, Apollo has resources\n  for beginners. The official GraphQL documentation is another good starting point.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/apis.yml
use_cases: []
---
