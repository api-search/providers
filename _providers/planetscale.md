---
api_count: 4
api_specs:
- filename: planetscale-platform-api-openapi.yml
  format: yaml
  label: PlanetScale Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/openapi/planetscale-platform-api-openapi.yml
apis:
- description: The PlanetScale Platform API provides programmatic access to manage PlanetScale serverless MySQL databases. It allows developers to create and delete database branches, manage deploy requests, automat
  name: PlanetScale Platform API
  slug: platform-api
- description: PlanetScale OAuth allows developers to create OAuth applications that can access users' PlanetScale accounts on their behalf. The implementation supports the Authorization Code grant type, enabling th
  name: PlanetScale OAuth
  slug: oauth
- description: The PlanetScale Serverless Driver for JavaScript is a Fetch API-compatible database driver designed for serverless and edge compute platforms such as Cloudflare Workers, Vercel Edge Functions, and Net
  name: PlanetScale Serverless Driver for JavaScript
  slug: serverless-driver
- description: The PlanetScale CLI (pscale) is a command-line tool that brings PlanetScale database management to the terminal. It allows developers to create, delete, and list databases and branches, open interacti
  name: PlanetScale CLI
  slug: cli
asyncapis:
- description: PlanetScale webhooks deliver HTTP POST callbacks to a configured URL when specific events occur within a PlanetScale organization. Webhooks enable real-time notifications for database branch lifecycle
  name: PlanetScale Webhook Events
  slug: planetscale-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/planetscale-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/planetscale-database-schema.json
created: ''
description: PlanetScale is a serverless MySQL database platform powered by Vitess, providing horizontal scaling, branching workflows, non-blocking schema changes, and other developer-friendly database features.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Planetscale Context
  property_count: 10
  slug: planetscale-context
layout: provider
modified: '2026-04-28'
name: planetscale
skills: []
slug: planetscale
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: planetscale\nurl: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml\napis:\n  - aid: planetscale:platform-api\n    name: PlanetScale Platform API\n    tags:\n      - Branching\n      - Cloud\n      - Databases\n      - Deploy Requests\n      - MySQL\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.planetscale.com/v1\n    humanURL: https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api\n    properties:\n      - url: https://api-docs.planetscale.com/reference/getting-started-with-planetscale-api\n        type: Documentation\n      - url: openapi/planetscale-platform-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/planetscale-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The PlanetScale Platform API provides programmatic access to manage\n      PlanetScale serverless MySQL databases. It allows\
  \ developers to create\n      and delete database branches, manage deploy requests, automate password\n      and connection string management, and integrate PlanetScale into CI/CD\n      pipelines and infrastructure-as-code workflows. The API supports\n      authentication via service tokens and OAuth, and its base URL is\n      https://api.planetscale.com/v1 with an OpenAPI 3.0 specification\n      available for download.\n  - aid: planetscale:oauth\n    name: PlanetScale OAuth\n    tags:\n      - Applications\n      - Authentication\n      - Authorization\n      - OAuth\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.planetscale.com\n    humanURL: https://planetscale.com/docs/api/planetscale-api-oauth-applications\n    properties:\n      - url: https://planetscale.com/docs/api/planetscale-api-oauth-applications\n        type: Documentation\n    description: >-\n      PlanetScale OAuth allows developers to create OAuth applications\
  \ that\n      can access users' PlanetScale accounts on their behalf. The\n      implementation supports the Authorization Code grant type, enabling\n      third-party applications to authenticate users and obtain delegated\n      access to PlanetScale resources. This is particularly useful for\n      building integrations and tools that need to interact with\n      organization-level PlanetScale endpoints on behalf of multiple users.\n  - aid: planetscale:serverless-driver\n    name: PlanetScale Serverless Driver for JavaScript\n    tags:\n      - Driver\n      - Edge Computing\n      - JavaScript\n      - MySQL\n      - SDK\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://planetscale.com/docs/tutorials/using-the-serverless-driver\n    properties:\n      - url: https://planetscale.com/docs/tutorials/using-the-serverless-driver\n        type: Documentation\n    description:\
  \ >-\n      The PlanetScale Serverless Driver for JavaScript is a Fetch API-compatible database\n      driver designed for serverless and edge compute platforms such as Cloudflare\n      Workers, Vercel Edge Functions, and Netlify Edge Functions. It enables developers\n      to query PlanetScale databases over HTTP connections, bypassing the TCP restrictions\n      common in edge environments.\n  - aid: planetscale:cli\n    name: PlanetScale CLI\n    tags:\n      - CLI\n      - Command Line\n      - Database Management\n      - Developer Tools\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://planetscale.com/docs/reference/planetscale-cli\n    properties:\n      - url: https://planetscale.com/docs/reference/planetscale-cli\n        type: Documentation\n    description: >-\n      The PlanetScale CLI (pscale) is a command-line tool that brings\n      PlanetScale database management to the terminal.\
  \ It allows developers\n      to create, delete, and list databases and branches, open interactive\n      MySQL shells for database branches, and manage deploy requests directly\n      from the command line. The CLI is available via Homebrew and as a\n      downloadable binary, and includes a Model Context Protocol (MCP)\n      server that provides AI tools with direct access to PlanetScale\n      databases.\ncommon:\n  - type: JSON-LD\n    url: json-ld/planetscale-context.jsonld\n  - type: JSONSchema\n    url: json-schema/planetscale-database-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  PlanetScale is a serverless MySQL database platform powered by Vitess, providing\n  horizontal scaling, branching workflows, non-blocking schema changes, and other\n  developer-friendly database features.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/apis.yml
use_cases: []
---
