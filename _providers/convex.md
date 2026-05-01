---
api_count: 5
api_specs:
- filename: convex-http-api-openapi.yml
  format: yaml
  label: Convex HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/openapi/convex-http-api-openapi.yml
- filename: openapi.json
  format: json
  label: Convex Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://api.convex.dev/v1/openapi.json
- filename: convex-deployment-platform-api-openapi.yml
  format: yaml
  label: Convex Deployment Platform API
  slug: deployment-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/openapi/convex-deployment-platform-api-openapi.yml
apis:
- description: The Convex HTTP API is a REST interface for executing backend functions deployed on a Convex backend. It provides endpoints for invoking query, mutation, and action functions using POST requests to pa
  name: Convex HTTP API
  slug: http-api
- description: The Convex Management API is a REST API for provisioning and managing Convex projects and deployments programmatically. It enables developers and platform integrations to create projects, list deploym
  name: Convex Management API
  slug: management-api
- description: The Convex Deployment Platform API is a deployment-scoped administrative API for configuring individual Convex deployments. It exposes private endpoints accessible only to deployment administrators, s
  name: Convex Deployment Platform API
  slug: deployment-platform-api
- description: The Convex JavaScript SDK is a collection of TypeScript/JavaScript packages for building applications on the Convex backend platform. It includes convex/server for defining backend functions and datab
  name: Convex JavaScript SDK
  slug: javascript-sdk
- description: The Convex Server SDK (convex/server) is the TypeScript library for defining backend logic deployed on Convex. It provides primitives for writing query functions for read-only database access, mutatio
  name: Convex Server SDK
  slug: server-sdk
capabilities: []
common:
- title: ''
  type: Portal
  url: https://www.convex.dev/developers
- title: ''
  type: Documentation
  url: https://docs.convex.dev/
- title: ''
  type: Website
  url: https://www.convex.dev
- title: ''
  type: Login
  url: https://dashboard.convex.dev/
- title: ''
  type: Blog
  url: https://stack.convex.dev/
- title: ''
  type: GitHub
  url: https://github.com/get-convex
- title: ''
  type: Discord
  url: https://convex.dev/community
- title: ''
  type: TermsOfService
  url: https://www.convex.dev/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.convex.dev/legal/privacy
- title: ''
  type: JSONSchema
  url: json-schema/convex-function-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/convex-deployment-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/convex-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/convex-vocabulary.yml
created: '2026-03-21'
description: Convex is a serverless backend platform that provides a real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessible through a suite of HTTP, management, and deployment APIs alongside JavaScript and server SDKs for full-stack application development. The platform is SOC 2 Type II, HIPAA, and GDPR compliant.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Convex Context
  property_count: 10
  slug: convex-context
layout: provider
modified: '2026-04-28'
name: Convex
rules:
- name: Convex API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: convex-deployment-platform-api-rules
- name: Convex API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: convex-http-api-rules
- name: Convex API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: convex-management-api-rules
skills: []
slug: convex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: convex\nurl: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml\nname: Convex\nx-type: company\ndescription: >-\n  Convex is a serverless backend platform that provides a real-time database,\n  cloud functions, and infrastructure for building modern web and mobile\n  applications. It offers a TypeScript-first developer experience with\n  reactive queries, transactional mutations, and integrated file storage,\n  all accessible through a suite of HTTP, management, and deployment APIs\n  alongside JavaScript and server SDKs for full-stack application\n  development. The platform is SOC 2 Type II, HIPAA, and GDPR compliant.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backend\n  - Database\n  - Functions\n  - Real-Time\n  - Reactive\n  - Serverless\n  - TypeScript\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: convex:http-api\n    name: Convex HTTP\
  \ API\n    tags:\n      - Backend\n      - Functions\n      - Real-Time\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://{deployment-name}.convex.cloud\n    humanURL: https://docs.convex.dev/http-api/\n    properties:\n      - url: https://docs.convex.dev/http-api/\n        type: Documentation\n      - url: openapi/convex-http-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Convex HTTP API is a REST interface for executing backend functions\n      deployed on a Convex backend. It provides endpoints for invoking query,\n      mutation, and action functions using POST requests to paths such as\n      /api/query, /api/mutation, /api/action, and the unified\n      /api/run/{functionIdentifier} endpoint. Each deployment has its own\n      base URL found in the Convex dashboard settings, typically in the\n      format https://{deployment-name}.convex.cloud.\n    x-features:\n      - POST /api/query\
  \ for reactive read-only function execution\n      - POST /api/mutation for transactional database writes\n      - POST /api/action for general-purpose server-side operations\n      - POST /api/run/{functionIdentifier} unified function invocation\n      - Optional bearer token auth for end users, Convex scheme for admin\n    x-useCases:\n      - Calling Convex functions from non-JavaScript backends\n      - Server-to-server orchestration of Convex queries and mutations\n      - Webhook handlers that trigger Convex actions\n      - Lightweight scripts that execute one-off function calls\n      - Testing deployed Convex functions from curl or HTTPie\n\n  - aid: convex:management-api\n    name: Convex Management API\n    tags:\n      - Administration\n      - Deployments\n      - Management\n      - Projects\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.convex.dev/v1\n    humanURL: https://docs.convex.dev/management-api\n\
  \    properties:\n      - url: https://docs.convex.dev/management-api\n        type: Documentation\n      - url: https://api.convex.dev/v1/openapi.json\n        type: OpenAPI\n      - url: openapi/convex-management-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Convex Management API is a REST API for provisioning and managing\n      Convex projects and deployments programmatically. It enables developers\n      and platform integrations to create projects, list deployments, manage\n      deploy keys, configure custom domains, and perform team-level\n      operations without using the Convex dashboard. The API uses Bearer\n      token authentication, supporting both Team Access Tokens and OAuth\n      Application Tokens for third-party integrations.\n    x-features:\n      - Projects and deployments lifecycle management\n      - Deploy key and preview deploy key issuance\n      - Personal access tokens and team access tokens\n      - Custom domain attachment for production\
  \ deployments\n      - Default environment variables and team membership management\n      - Published OpenAPI spec at https://api.convex.dev/v1/openapi.json\n    x-useCases:\n      - Building Convex platform integrations and CI/CD pipelines\n      - Provisioning preview deployments per pull request\n      - Automating environment variable configuration for new projects\n      - Inviting team members and rotating credentials programmatically\n      - Listing all deployments for governance and inventory tooling\n\n  - aid: convex:deployment-platform-api\n    name: Convex Deployment Platform API\n    tags:\n      - Administration\n      - Configuration\n      - Deployment\n      - Environment Variables\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://{deployment-name}.convex.cloud/api/v1\n    humanURL: https://docs.convex.dev/deployment-platform-api\n    properties:\n      - url: https://docs.convex.dev/deployment-platform-api\n\
  \        type: Documentation\n      - url: openapi/convex-deployment-platform-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Convex Deployment Platform API is a deployment-scoped administrative\n      API for configuring individual Convex deployments. It exposes private\n      endpoints accessible only to deployment administrators, supporting\n      operations such as managing environment variables and other deployment\n      configuration settings. Each deployment has its own endpoint in the\n      format https://{deployment-name}.convex.cloud/api/v1/.\n    x-features:\n      - Deployment-scoped administrative access\n      - Environment variable configuration management\n      - Bearer token Authorization with the Convex scheme\n      - Beta API surface intended for platform integrations\n    x-useCases:\n      - Pushing environment variable updates from CI/CD pipelines\n      - Reading deployment configuration for IaC drift detection\n      - Building admin tooling\
  \ that targets a specific deployment\n      - Synchronizing config across multiple Convex deployments\n\n  - aid: convex:javascript-sdk\n    name: Convex JavaScript SDK\n    tags:\n      - Client Library\n      - JavaScript\n      - SDK\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.convex.dev/api/\n    properties:\n      - url: https://docs.convex.dev/api/\n        type: Documentation\n      - url: https://www.npmjs.com/package/convex\n        type: Package\n    description: >-\n      The Convex JavaScript SDK is a collection of TypeScript/JavaScript\n      packages for building applications on the Convex backend platform. It\n      includes convex/server for defining backend functions and database\n      schemas, convex/react for React hooks and the ConvexReactClient,\n      convex/browser for the ConvexHttpClient in non-React browser\n      environments, convex/values for working with Convex-stored\
  \ data types,\n      and framework integrations for Next.js, React Native, and other\n      environments.\n    x-features:\n      - ConvexReactClient with reactive useQuery, useMutation hooks\n      - ConvexHttpClient for non-React JavaScript runtimes\n      - Strongly typed client generated from project schema\n      - Authentication helpers for Clerk, Auth0, and custom providers\n      - Framework integrations for Next.js, React Native, and Svelte\n    x-useCases:\n      - Building real-time React applications backed by Convex\n      - Embedding Convex queries in Next.js server components\n      - Server-rendered apps that read Convex data on the server\n      - Cross-platform mobile apps using React Native and Convex\n\n  - aid: convex:server-sdk\n    name: Convex Server SDK\n    tags:\n      - Backend\n      - Database\n      - Serverless Functions\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.convex.dev/functions\n\
  \    properties:\n      - url: https://docs.convex.dev/functions\n        type: Documentation\n      - url: https://docs.convex.dev/database/schemas\n        type: Documentation\n    description: >-\n      The Convex Server SDK (convex/server) is the TypeScript library for\n      defining backend logic deployed on Convex. It provides primitives for\n      writing query functions for read-only database access, mutation\n      functions for transactional writes, and action functions for\n      general-purpose server-side operations including calling external\n      services. The SDK supports schema definition, full-text search indexes,\n      vector search indexes, file storage, scheduled functions, cron jobs,\n      and HTTP routing via the HttpRouter class.\n    x-features:\n      - query, mutation, and action function primitives\n      - defineSchema and defineTable for typed database modeling\n      - Full-text and vector search indexes\n      - Cron jobs and scheduled function execution\n\
  \      - HttpRouter for custom HTTP endpoints\n      - File storage with signed URL generation\n    x-useCases:\n      - Authoring Convex backend functions in TypeScript\n      - Modeling reactive database schemas with type safety\n      - Implementing AI workflows with vector search\n      - Scheduling recurring background work with cron jobs\n      - Building HTTP webhook handlers inside Convex deployments\n\ncommon:\n  - type: Portal\n    url: https://www.convex.dev/developers\n  - type: Documentation\n    url: https://docs.convex.dev/\n  - type: Website\n    url: https://www.convex.dev\n  - type: Login\n    url: https://dashboard.convex.dev/\n  - type: Blog\n    url: https://stack.convex.dev/\n  - type: GitHub\n    url: https://github.com/get-convex\n  - type: Discord\n    url: https://convex.dev/community\n  - type: TermsOfService\n    url: https://www.convex.dev/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.convex.dev/legal/privacy\n  - type: JSONSchema\n    url: json-schema/convex-function-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/convex-deployment-schema.json\n  - type: JSON-LD\n    url: json-ld/convex-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/convex-vocabulary.yml\n\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml
tags:
- Backend
- Database
- Functions
- Real-Time
- Reactive
- Serverless
- TypeScript
url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/apis.yml
use_cases: []
---
