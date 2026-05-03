---
api_count: 6
api_specs:
- filename: supabase-management-api-openapi.yml
  format: yaml
  label: Supabase Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-management-api-openapi.yml
- filename: supabase-auth-api-openapi.yml
  format: yaml
  label: Supabase Auth API
  slug: auth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-auth-api-openapi.yml
- filename: supabase-storage-api-openapi.yml
  format: yaml
  label: Supabase Storage API
  slug: storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-storage-api-openapi.yml
- filename: supabase-database-rest-api-openapi.yml
  format: yaml
  label: Supabase Database REST API
  slug: database-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-database-rest-api-openapi.yml
- filename: supabase-edge-functions-api-openapi.yml
  format: yaml
  label: Supabase Edge Functions API
  slug: edge-functions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-edge-functions-api-openapi.yml
- filename: supabase-realtime-api-asyncapi.yml
  format: yaml
  label: Supabase Realtime API
  slug: realtime-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/asyncapi/supabase-realtime-api-asyncapi.yml
apis:
- description: The Supabase Management API provides programmatic access to manage Supabase projects and organizations. Supports creating, configuring, pausing, and deleting projects; managing database migrations and
  name: Supabase Management API
  slug: management-api
- description: The Supabase Auth API (based on GoTrue) is a JWT-based authentication service supporting user signup, email/password sign-in, magic links, one-time passwords (OTP), OAuth2 social login (Google, GitHub
  name: Supabase Auth API
  slug: auth-api
- description: The Supabase Storage API enables developers to store, organize, and serve large files in S3-compatible object storage. Provides bucket management (public/private), file upload (standard and TUS resuma
  name: Supabase Storage API
  slug: storage-api
- description: The Supabase Database REST API provides auto-generated RESTful endpoints for every table, view, and stored function in the PostgreSQL database, powered by PostgREST. Supports full CRUD operations with
  name: Supabase Database REST API
  slug: database-rest-api
- description: Supabase Edge Functions are globally distributed, server-side TypeScript functions powered by the Deno runtime. They are deployed and invoked via HTTP requests to a project-specific URL. Functions can
  name: Supabase Edge Functions API
  slug: edge-functions-api
- description: 'The Supabase Realtime API provides WebSocket-based subscriptions for real-time data changes from PostgreSQL databases. It supports three channel types: database change events (INSERT/UPDATE/DELETE on '
  name: Supabase Realtime API
  slug: realtime-api
asyncapis:
- description: 'The Supabase Realtime API enables real-time communication over WebSocket connections using the Phoenix Channel protocol (v2). It supports three main features: Postgres Changes for subscribing to INSER'
  name: Supabase Realtime API
  slug: supabase-realtime-api-asyncapi
capabilities:
- description: Unified workflow capability combining Supabase's database, authentication, and storage services for full-stack application development. Used by developers building web and mobile applications who need
  name: Supabase Backend As A Service
  slug: backend-as-a-service
common:
- title: ''
  type: Website
  url: https://supabase.com
- title: ''
  type: Documentation
  url: https://supabase.com/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/supabase
- title: ''
  type: Status Page
  url: https://status.supabase.com
- title: ''
  type: Pricing
  url: https://supabase.com/pricing
- title: ''
  type: Blog
  url: https://supabase.com/blog
- title: ''
  type: Community
  url: https://github.com/supabase/supabase/discussions
- title: ''
  type: X
  url: https://twitter.com/supabase
created: '2026-05-02'
description: Supabase is an open-source Firebase alternative that provides a suite of backend services built on top of PostgreSQL. It offers a managed PostgreSQL database with auto-generated REST and GraphQL APIs via PostgREST, real-time data subscriptions via WebSockets, user authentication with JWT (GoTrue), file storage with S3-compatible object storage, edge compute via globally distributed TypeScript functions on the Deno runtime, and a management API for programmatic control of projects and organizations. Supabase is available as a fully managed cloud service (app.supabase.com) and as a self-hosted open-source deployment.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Supabase Context
  property_count: 9
  slug: supabase-context
layout: provider
modified: '2026-05-02'
name: Supabase
rules:
- name: Supabase API Rules
  rule_count: 11
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 8
  slug: supabase-rules
skills: []
slug: supabase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: supabase\nname: Supabase\ndescription: >-\n  Supabase is an open-source Firebase alternative that provides a suite of\n  backend services built on top of PostgreSQL. It offers a managed PostgreSQL\n  database with auto-generated REST and GraphQL APIs via PostgREST, real-time\n  data subscriptions via WebSockets, user authentication with JWT (GoTrue),\n  file storage with S3-compatible object storage, edge compute via globally\n  distributed TypeScript functions on the Deno runtime, and a management API\n  for programmatic control of projects and organizations. Supabase is available\n  as a fully managed cloud service (app.supabase.com) and as a self-hosted\n  open-source deployment.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backend As A Service\n  - PostgreSQL\n  - Open Source\n  - Authentication\n  - Real Time\n  - Storage\n  - Edge Functions\n  - Database\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: supabase:management-api\n    name: Supabase Management API\n    description: >-\n      The Supabase Management API provides programmatic access to manage\n      Supabase projects and organizations. Supports creating, configuring,\n      pausing, and deleting projects; managing database migrations and\n      extensions; deploying Edge Functions; managing secrets; configuring\n      custom domains and vanity subdomains; controlling network restrictions;\n      and managing organization membership. Authentication uses personal access\n      tokens or OAuth2 tokens. Base URL: https://api.supabase.com/v1.\n    humanURL: https://supabase.com/docs/reference/api/introduction\n    tags:\n      - Management\n      - Projects\n      - Organizations\n      - Edge Functions\n      - Database\n    properties:\n      - type: Documentation\n        url: https://supabase.com/docs/reference/api/introduction\n  \
  \    - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-management-api-openapi.yml\n  - aid: supabase:auth-api\n    name: Supabase Auth API\n    description: >-\n      The Supabase Auth API (based on GoTrue) is a JWT-based authentication\n      service supporting user signup, email/password sign-in, magic links,\n      one-time passwords (OTP), OAuth2 social login (Google, GitHub, etc.),\n      token refresh, multi-factor authentication (TOTP/WebAuthn), SAML-based\n      SSO, and administrative user management. Authentication uses an apikey\n      header (anon or service_role key) plus JWT bearer tokens for user context.\n      Per-project base URL: https://{project_ref}.supabase.co/auth/v1.\n    humanURL: https://supabase.com/docs/guides/auth\n    tags:\n      - Authentication\n      - Users\n      - OAuth\n      - JWT\n      - MFA\n      - SAML\n    properties:\n      - type: Documentation\n        url:\
  \ https://supabase.com/docs/guides/auth\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-auth-api-openapi.yml\n  - aid: supabase:storage-api\n    name: Supabase Storage API\n    description: >-\n      The Supabase Storage API enables developers to store, organize, and\n      serve large files in S3-compatible object storage. Provides bucket\n      management (public/private), file upload (standard and TUS resumable),\n      download, deletion, and on-the-fly image transformations (resize, format,\n      quality). Access control is enforced via Row Level Security policies.\n      Supports signed URLs for temporary access. Per-project base URL:\n      https://{project_ref}.supabase.co/storage/v1.\n    humanURL: https://supabase.com/docs/guides/storage\n    tags:\n      - Storage\n      - File Upload\n      - Buckets\n      - Images\n      - S3\n    properties:\n      - type: Documentation\n     \
  \   url: https://supabase.com/docs/guides/storage\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-storage-api-openapi.yml\n  - aid: supabase:database-rest-api\n    name: Supabase Database REST API\n    description: >-\n      The Supabase Database REST API provides auto-generated RESTful endpoints\n      for every table, view, and stored function in the PostgreSQL database,\n      powered by PostgREST. Supports full CRUD operations with advanced\n      filtering operators (eq, neq, gt, lt, like, ilike, in, fts, cs, cd,\n      ov, adj, not, or, and), horizontal and vertical filtering, pagination,\n      ordering, and embedding related resources via foreign key relationships.\n      Row Level Security policies are enforced on all requests. Per-project\n      base URL: https://{project_ref}.supabase.co/rest/v1.\n    humanURL: https://supabase.com/docs/guides/api\n    tags:\n      - Database\n    \
  \  - REST\n      - PostgreSQL\n      - PostgREST\n      - CRUD\n    properties:\n      - type: Documentation\n        url: https://supabase.com/docs/guides/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-database-rest-api-openapi.yml\n  - aid: supabase:edge-functions-api\n    name: Supabase Edge Functions API\n    description: >-\n      Supabase Edge Functions are globally distributed, server-side TypeScript\n      functions powered by the Deno runtime. They are deployed and invoked via\n      HTTP requests to a project-specific URL. Functions can access Supabase\n      client libraries to interact with the database, auth, and storage\n      services. JWT verification is required by default but can be disabled\n      per function. Per-project base URL:\n      https://{project_ref}.supabase.co/functions/v1.\n    humanURL: https://supabase.com/docs/guides/functions\n    tags:\n      - Edge Functions\n\
  \      - Serverless\n      - Deno\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://supabase.com/docs/guides/functions\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-edge-functions-api-openapi.yml\n  - aid: supabase:realtime-api\n    name: Supabase Realtime API\n    description: >-\n      The Supabase Realtime API provides WebSocket-based subscriptions for\n      real-time data changes from PostgreSQL databases. It supports three\n      channel types: database change events (INSERT/UPDATE/DELETE on tables\n      via logical replication), presence (track and synchronize connected\n      users' state), and broadcast (low-latency message passing between\n      clients). Authentication uses JWT tokens. Implemented using the Phoenix\n      channels protocol.\n    humanURL: https://supabase.com/docs/guides/realtime\n    tags:\n      - Realtime\n      - WebSocket\n\
  \      - Database\n      - Presence\n      - Broadcast\n    properties:\n      - type: Documentation\n        url: https://supabase.com/docs/guides/realtime\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/asyncapi/supabase-realtime-api-asyncapi.yml\ncommon:\n  - type: Website\n    url: https://supabase.com\n  - type: Documentation\n    url: https://supabase.com/docs\n  - type: GitHub Organization\n    url: https://github.com/supabase\n  - type: Status Page\n    url: https://status.supabase.com\n  - type: Pricing\n    url: https://supabase.com/pricing\n  - type: Blog\n    url: https://supabase.com/blog\n  - type: Community\n    url: https://github.com/supabase/supabase/discussions\n  - type: X\n    url: https://twitter.com/supabase\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml
tags:
- Backend As A Service
- PostgreSQL
- Open Source
- Authentication
- Real Time
- Storage
- Edge Functions
- Database
url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml
use_cases: []
---
