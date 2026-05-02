---
api_count: 4
api_specs:
- filename: neon-management-api-openapi.yml
  format: yaml
  label: Neon Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/openapi/neon-management-api-openapi.yml
- filename: neon-auth-webhooks-asyncapi.yml
  format: yaml
  label: Neon Auth
  slug: auth
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/asyncapi/neon-auth-webhooks-asyncapi.yml
apis:
- description: The Neon Management API is a RESTful interface for programmatically managing Neon serverless Postgres resources. It allows developers to create and manage projects, branches, databases, roles, compute
  name: Neon Management API
  slug: management-api
- description: The Neon Data API provides a secure, stateless HTTP interface to Neon Postgres databases, allowing developers to access and manage data directly from web browsers, serverless functions, and edge runti
  name: Neon Data API
  slug: data-api
- description: The Neon Serverless Driver is a low-latency JavaScript and TypeScript driver that enables querying Neon Postgres databases from serverless and edge environments over HTTP or WebSockets in place of TCP
  name: Neon Serverless Driver
  slug: serverless-driver
- description: Neon Auth is a managed authentication service built on Better Auth that connects directly to a Neon Postgres database. It stores authentication data including users, sessions, and OAuth configurations
  name: Neon Auth
  slug: auth
asyncapis:
- description: 'Neon Auth webhooks deliver HTTP POST requests when authentication events occur, including OTP delivery, magic link delivery, and user creation. Webhooks can be used to replace built-in email delivery '
  name: Neon Auth Webhook Events
  slug: neon-auth-webhooks-asyncapi
common:
- title: ''
  type: Portal
  url: https://neon.com/docs
- title: ''
  type: Blog
  url: https://neon.com/blog
- title: ''
  type: Pricing
  url: https://neon.com/pricing
- title: ''
  type: Login
  url: https://console.neon.tech
- title: ''
  type: Sign Up
  url: https://console.neon.tech/signup
- title: ''
  type: Support
  url: https://neon.com/docs/introduction/support
- title: ''
  type: Status
  url: https://neonstatus.com
- title: ''
  type: TermsOfService
  url: https://neon.com/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://neon.com/privacy-policy
- title: ''
  type: Website
  url: https://neon.com
created: '2025-03-07'
description: Neon is a serverless Postgres platform that provides fully managed, scalable PostgreSQL databases optimized for modern cloud and edge application development. Their developer platform offers management APIs, data APIs, authentication services, and serverless drivers for building and automating database-driven workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Neon Context
  property_count: 7
  slug: neon-context
layout: provider
modified: '2026-04-28'
name: Neon
skills: []
slug: neon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: neon\nname: Neon\ndescription: >-\n  Neon is a serverless Postgres platform that provides fully managed,\n  scalable PostgreSQL databases optimized for modern cloud and edge\n  application development. Their developer platform offers management APIs,\n  data APIs, authentication services, and serverless drivers for building\n  and automating database-driven workflows.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Databases\n  - Serverless\n  - Postgres\n  - Infrastructure\n  - Authentication\n  - Edge\nurl: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml\ncreated: '2025-03-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: neon:management-api\n    name: Neon Management API\n    description: >-\n      The Neon Management API is a RESTful interface for programmatically\n      managing Neon serverless Postgres resources. It allows developers to\n      create\
  \ and manage projects, branches, databases, roles, compute\n      endpoints, and operations. The API uses bearer token authentication\n      and supports everything available through the Neon Console, enabling\n      automation of database infrastructure workflows. An OpenAPI 3.0\n      specification is available along with TypeScript, Python, and Go\n      SDKs.\n    humanURL: https://neon.com/docs/reference/api-reference\n    baseURL: https://console.neon.tech/api/v2\n    tags:\n      - Databases\n      - Serverless\n      - Postgres\n      - Projects\n      - Branches\n      - Compute\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://neon.com/docs/reference/api-reference\n      - type: Documentation\n        url: https://api-docs.neon.tech/reference/getting-started-with-neon-api\n      - type: OpenAPI\n        url: openapi/neon-management-api-openapi.yml\n  - aid: neon:data-api\n    name: Neon Data API\n    description: >-\n      The Neon Data\
  \ API provides a secure, stateless HTTP interface to Neon\n      Postgres databases, allowing developers to access and manage data\n      directly from web browsers, serverless functions, and edge runtimes\n      using standard HTTP methods. It is fully compatible with PostgREST,\n      enabling querying via standard HTTP clients like Postman or cURL. The\n      Data API supports JWT-based authentication and integrates with\n      Row-Level Security policies, making it suitable for building secure\n      client-facing applications without a traditional backend.\n    humanURL: https://neon.com/docs/data-api/overview\n    tags:\n      - Databases\n      - Serverless\n      - Postgres\n      - REST\n      - Data\n      - PostgREST\n      - HTTP\n    properties:\n      - type: Documentation\n        url: https://neon.com/docs/data-api/overview\n      - type: Documentation\n        url: https://neon.com/docs/data-api/get-started\n  - aid: neon:serverless-driver\n    name: Neon Serverless Driver\n\
  \    description: >-\n      The Neon Serverless Driver is a low-latency JavaScript and TypeScript\n      driver that enables querying Neon Postgres databases from serverless\n      and edge environments over HTTP or WebSockets in place of TCP. It\n      supports two query modes: HTTP mode using the neon function for fast\n      single non-interactive transactions, and WebSocket mode using Pool and\n      Client constructors for session and transaction support with\n      node-postgres compatibility. The driver is available as\n      @neondatabase/serverless on npm and is optimized for deployment on\n      platforms like Cloudflare Workers, Vercel Edge Functions, and AWS\n      Lambda.\n    humanURL: https://neon.com/docs/serverless/serverless-driver\n    tags:\n      - Databases\n      - Serverless\n      - Postgres\n      - JavaScript\n      - TypeScript\n      - WebSocket\n      - Edge\n      - Driver\n    properties:\n      - type: Documentation\n        url: https://neon.com/docs/serverless/serverless-driver\n\
  \  - aid: neon:auth\n    name: Neon Auth\n    description: >-\n      Neon Auth is a managed authentication service built on Better Auth\n      that connects directly to a Neon Postgres database. It stores\n      authentication data including users, sessions, and OAuth\n      configurations in the database's neon_auth schema. Neon Auth provides\n      client and server SDKs, supports multiple OAuth providers, and\n      integrates with the Neon Data API for automatic JWT validation. It\n      enables Row-Level Security policies through the auth.uid() function,\n      allowing developers to implement fine-grained data access control\n      based on authenticated users.\n    humanURL: https://neon.com/docs/auth/overview\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n      - JWT\n      - Security\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://neon.com/docs/auth/overview\n      - type: Documentation\n        url: https://neon.com/docs/neon-auth/api\n\
  \      - type: AsyncAPI\n        url: asyncapi/neon-auth-webhooks-asyncapi.yml\ncommon:\n  - type: Portal\n    url: https://neon.com/docs\n  - type: Blog\n    url: https://neon.com/blog\n  - type: Pricing\n    url: https://neon.com/pricing\n  - type: Login\n    url: https://console.neon.tech\n  - type: Sign Up\n    url: https://console.neon.tech/signup\n  - type: Support\n    url: https://neon.com/docs/introduction/support\n  - type: Status\n    url: https://neonstatus.com\n  - type: TermsOfService\n    url: https://neon.com/terms-of-service\n  - type: PrivacyPolicy\n    url: https://neon.com/privacy-policy\n  - type: Website\n    url: https://neon.com\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml
tags:
- Databases
- Serverless
- Postgres
- Infrastructure
- Authentication
- Edge
url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml
use_cases: []
---
