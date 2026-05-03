---
api_count: 4
api_specs:
- filename: strapi-rest-api-openapi.yml
  format: yaml
  label: Strapi REST API
  slug: strapi-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml
- filename: strapi-admin-panel-api-openapi.yml
  format: yaml
  label: Strapi Admin Panel API
  slug: strapi-admin-panel-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml
- filename: strapi-users-and-permissions-api-openapi.yml
  format: yaml
  label: Strapi Users and Permissions API
  slug: strapi-users-permissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml
- filename: strapi-webhooks-asyncapi.yml
  format: yaml
  label: Strapi Webhooks
  slug: strapi-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml
apis:
- description: The Strapi REST API provides automatically generated endpoints for accessing and managing content-types created within the Strapi headless CMS. Supports full CRUD operations with filtering, sorting, p
  name: Strapi REST API
  slug: strapi-rest-api
- description: The Strapi Admin Panel API powers the back-office interface for managing content-types, content entries, media assets, and administrator accounts. Provides endpoints for the Content-Type Builder, Cont
  name: Strapi Admin Panel API
  slug: strapi-admin-panel-api
- description: The Strapi Users and Permissions API provides a full JWT-based authentication system for protecting API endpoints, along with an access-control list strategy for managing permissions between user grou
  name: Strapi Users and Permissions API
  slug: strapi-users-permissions-api
- description: Strapi includes a built-in webhook system that notifies external services whenever content entries or media assets are created, updated, deleted, published, or unpublished. Webhooks are configured thr
  name: Strapi Webhooks
  slug: strapi-webhooks
asyncapis:
- description: Strapi includes a built-in webhook system that notifies external services whenever certain events occur in the CMS. Rather than polling the Strapi API for changes, you can configure Strapi to send HTT
  name: Strapi Webhooks
  slug: strapi-webhooks-asyncapi
capabilities:
- description: Unified capability for managing content in Strapi headless CMS. Combines the REST content API, admin panel API, and users/permissions API into a single workflow for content authors, developers, and pl
  name: Strapi Content Management
  slug: content-management
common:
- title: ''
  type: Website
  url: https://strapi.io
- title: ''
  type: Documentation
  url: https://docs.strapi.io
- title: ''
  type: GitHub
  url: https://github.com/strapi/strapi
- title: ''
  type: Blog
  url: https://strapi.io/blog
- title: ''
  type: Forum
  url: https://forum.strapi.io
- title: ''
  type: Discord
  url: https://discord.strapi.io
- title: ''
  type: Roadmap
  url: https://feedback.strapi.io
- title: ''
  type: Changelog
  url: https://github.com/strapi/strapi/releases
- title: ''
  type: Pricing
  url: https://strapi.io/pricing-cloud
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml
- title: ''
  type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-schema/strapi-content-entry-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-ld/strapi-context.jsonld
created: '2025-01-01'
description: Strapi is an open-source, headless CMS built with Node.js that gives developers full control over their content API. It provides a customizable admin panel for content management, automatically generates REST and GraphQL APIs for every content-type, and supports flexible database options including SQLite, PostgreSQL, MySQL, and MongoDB. Strapi v5 introduces a Document Service API with flattened response format, improved TypeScript support, and an enhanced content delivery API for building fast, decoupled frontends.
features: []
image: https://strapi.io/assets/strapi-logo-dark.svg
integrations: []
jsonld:
- class_count: 0
  name: Strapi Context
  property_count: 8
  slug: strapi-context
layout: provider
modified: '2026-05-02'
name: Strapi
rules:
- name: Strapi API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 4
    warn: 5
  slug: strapi-rules
skills: []
slug: strapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: strapi\nname: Strapi\ndescription: >-\n  Strapi is an open-source, headless CMS built with Node.js that gives\n  developers full control over their content API. It provides a customizable\n  admin panel for content management, automatically generates REST and GraphQL\n  APIs for every content-type, and supports flexible database options including\n  SQLite, PostgreSQL, MySQL, and MongoDB. Strapi v5 introduces a Document\n  Service API with flattened response format, improved TypeScript support,\n  and an enhanced content delivery API for building fast, decoupled frontends.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml\nimage: https://strapi.io/assets/strapi-logo-dark.svg\ntags:\n  - CMS\n  - Content Management\n  - Headless CMS\n  - Node.js\n  - Open Source\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: strapi:strapi-rest-api\n\
  \    name: Strapi REST API\n    description: >-\n      The Strapi REST API provides automatically generated endpoints for\n      accessing and managing content-types created within the Strapi headless\n      CMS. Supports full CRUD operations with filtering, sorting, pagination,\n      population of relational fields, and internationalization. Content-types\n      are private by default and require authenticated requests or configured\n      public permissions. The API also includes a media library Upload plugin\n      for file management.\n    humanURL: https://docs.strapi.io/cms/api/rest\n    baseURL: https://{host}\n    tags:\n      - CMS\n      - Content Management\n      - REST API\n      - Headless CMS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml\n      - type: Documentation\n        url: https://docs.strapi.io/cms/api/rest\n      - type: Documentation\n\
  \        url: https://docs.strapi.io/cms/api/rest/parameters\n  - aid: strapi:strapi-admin-panel-api\n    name: Strapi Admin Panel API\n    description: >-\n      The Strapi Admin Panel API powers the back-office interface for managing\n      content-types, content entries, media assets, and administrator accounts.\n      Provides endpoints for the Content-Type Builder, Content Manager, Media\n      Library, and role-based access control configuration. Supports three\n      default roles (Super Admin, Editor, Author) and includes management of\n      API tokens, transfer tokens, and webhooks.\n    humanURL: https://docs.strapi.io/cms/features/admin-panel\n    baseURL: https://{host}\n    tags:\n      - Admin\n      - CMS\n      - Content Management\n      - RBAC\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml\n      - type: Documentation\n        url: https://docs.strapi.io/cms/features/admin-panel\n\
  \      - type: Documentation\n        url: https://docs.strapi.io/cms/features/rbac\n  - aid: strapi:strapi-users-permissions-api\n    name: Strapi Users and Permissions API\n    description: >-\n      The Strapi Users and Permissions API provides a full JWT-based\n      authentication system for protecting API endpoints, along with an\n      access-control list strategy for managing permissions between user\n      groups. Supports user registration, login, password reset, email\n      confirmation, and social provider authentication via OAuth. The API\n      enables configuration of roles and permissions to control endpoint\n      accessibility.\n    humanURL: https://docs.strapi.io/cms/features/users-permissions\n    baseURL: https://{host}\n    tags:\n      - Authentication\n      - CMS\n      - Permissions\n      - User Management\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml\n\
  \      - type: Documentation\n        url: https://docs.strapi.io/cms/features/users-permissions\n  - aid: strapi:strapi-webhooks\n    name: Strapi Webhooks\n    description: >-\n      Strapi includes a built-in webhook system that notifies external services\n      whenever content entries or media assets are created, updated, deleted,\n      published, or unpublished. Webhooks are configured through the admin panel\n      and include a custom X-Strapi-Event header identifying the event type.\n    humanURL: https://docs.strapi.io/cms/backend-customization/webhooks\n    tags:\n      - CMS\n      - Events\n      - Webhooks\n    properties:\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml\n      - type: Documentation\n        url: https://docs.strapi.io/cms/backend-customization/webhooks\ncommon:\n  - type: Website\n    url: https://strapi.io\n  - type: Documentation\n    url:\
  \ https://docs.strapi.io\n  - type: GitHub\n    url: https://github.com/strapi/strapi\n  - type: Blog\n    url: https://strapi.io/blog\n  - type: Forum\n    url: https://forum.strapi.io\n  - type: Discord\n    url: https://discord.strapi.io\n  - type: Roadmap\n    url: https://feedback.strapi.io\n  - type: Changelog\n    url: https://github.com/strapi/strapi/releases\n  - type: Pricing\n    url: https://strapi.io/pricing-cloud\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml\n  - type: AsyncAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-schema/strapi-content-entry-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-ld/strapi-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml
tags:
- CMS
- Content Management
- Headless CMS
- Node.js
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml
use_cases: []
---
