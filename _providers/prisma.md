---
api_count: 6
api_specs:
- filename: openapi.json
  format: json
  label: Prisma Data Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://api.cloud.prisma.io/openapi.json
- filename: prisma-accelerate-openapi.yml
  format: yaml
  label: Prisma Accelerate API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-accelerate-openapi.yml
- filename: prisma-pulse-openapi.yml
  format: yaml
  label: Prisma Pulse API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-pulse-openapi.yml
- filename: prisma-postgres-management-openapi.yml
  format: yaml
  label: Prisma Postgres Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-postgres-management-openapi.yml
- filename: prisma-client-openapi.yml
  format: yaml
  label: Prisma Client API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-client-openapi.yml
- filename: prisma-optimize-openapi.yml
  format: yaml
  label: Prisma Optimize API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-optimize-openapi.yml
apis:
- description: REST API for managing Prisma Data Platform resources including projects, environments, and database connections through the Prisma Console.
  name: Prisma Data Platform API
  slug: ''
- description: API for Prisma Accelerate, a fully managed global connection pool and caching layer for existing databases with query-level cache policies directly from the Prisma ORM.
  name: Prisma Accelerate API
  slug: ''
- description: API for Prisma Pulse, a managed Change Data Capture service enabling real-time database change events and type-safe subscriptions via Prisma Client.
  name: Prisma Pulse API
  slug: ''
- description: REST API for programmatically provisioning and managing Prisma Postgres databases, projects, and workspaces, supporting automation, CI/CD workflows, and partner integrations.
  name: Prisma Postgres Management API
  slug: ''
- description: Auto-generated, type-safe query builder for Node.js and TypeScript that provides programmatic database access for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB, and CockroachDB.
  name: Prisma Client API
  slug: ''
- description: Query performance tool for analyzing, debugging, and improving database queries during development, with AI-powered recommendations to reduce database load and improve responsiveness.
  name: Prisma Optimize API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://console.prisma.io/login
- title: ''
  type: Documentation
  url: https://www.prisma.io/docs
- title: ''
  type: Getting Started
  url: https://www.prisma.io/docs/getting-started
- title: ''
  type: Authentication
  url: https://www.prisma.io/docs/management-api/authentication
- title: ''
  type: Blog
  url: https://www.prisma.io/blog
- title: ''
  type: Change Log
  url: https://www.prisma.io/changelog
- title: ''
  type: GitHub Organization
  url: https://github.com/prisma
- title: ''
  type: Community
  url: https://www.prisma.io/community
- title: ''
  type: Discord
  url: https://pris.ly/discord
- title: ''
  type: Twitter
  url: https://twitter.com/prisma
- title: ''
  type: Pricing
  url: https://www.prisma.io/pricing
- title: ''
  type: Status
  url: https://www.prisma-status.com
- title: ''
  type: Support
  url: https://www.prisma.io/support
- title: ''
  type: Terms of Service
  url: https://www.prisma.io/terms
- title: ''
  type: Privacy Policy
  url: https://www.prisma.io/privacy
- title: ''
  type: Website
  url: https://www.prisma.io
- title: ''
  type: Login
  url: https://console.prisma.io/login
- title: ''
  type: Sign Up
  url: https://console.prisma.io/sign-up
- title: ''
  type: JSON-LD Context
  url: json-ld/prisma-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/prisma-workspace-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/prisma-project-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/prisma-database-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/prisma-cache-strategy-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/prisma-pulse-event-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/prisma-query-recommendation-schema.json
created: '2024'
description: Prisma is a next-generation ORM that helps developers build applications faster and with fewer errors. It provides a type-safe database client, migrations system, and visual database browser.
features: []
image: https://www.prisma.io/images/prisma-logo.svg
integrations: []
jsonld:
- class_count: 6
  name: Prisma Context
  property_count: 16
  slug: prisma-context
layout: provider
modified: '2026-04-28'
name: Prisma
skills: []
slug: prisma
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Prisma\ndescription: Prisma is a next-generation ORM that helps developers build applications faster and with fewer errors. It provides a type-safe database client, migrations system, and visual database browser.\nimage: https://www.prisma.io/images/prisma-logo.svg\nurl: https://www.prisma.io\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Prisma Data Platform API\n    description: REST API for managing Prisma Data Platform resources including projects, environments, and database connections through the Prisma Console.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/platform/about\n    baseUrl: https://api.cloud.prisma.io\n    tags:\n      - Database\n      - Developer Tools\n      - ORM\n      - Platform\n    properties:\n      - type: Documentation\n        url: https://www.prisma.io/docs/platform/about\n      - type: OpenAPI\n        url: https://api.cloud.prisma.io/openapi.json\n\
  \      - type: OpenAPI\n        url: openapi/prisma-data-platform-openapi.yml\n      - type: Authentication\n        url: https://www.prisma.io/docs/management-api/authentication\n      - type: Getting Started\n        url: https://www.prisma.io/docs/console/getting-started\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\n  - name: Prisma Accelerate API\n    description: API for Prisma Accelerate, a fully managed global connection pool and caching layer for existing databases with query-level cache policies directly from the Prisma ORM.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/accelerate\n    baseUrl: https://accelerate.prisma-data.net\n    tags:\n      - Caching\n      - Connection Pooling\n      - Database\n      - Performance\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://www.prisma.io/docs/accelerate\n      - type:\
  \ OpenAPI\n        url: openapi/prisma-accelerate-openapi.yml\n      - type: Getting Started\n        url: https://www.prisma.io/docs/accelerate/getting-started\n      - type: Reference\n        url: https://www.prisma.io/docs/accelerate/reference/api-reference\n      - type: FAQ\n        url: https://www.prisma.io/docs/accelerate/more/faq\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\n  - name: Prisma Pulse API\n    description: API for Prisma Pulse, a managed Change Data Capture service enabling real-time database change events and type-safe subscriptions via Prisma Client.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/pulse/database-events\n    baseUrl: https://pulse.prisma-data.net\n    tags:\n      - Change Data Capture\n      - Database\n      - Events\n      - Real-Time\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://www.prisma.io/docs/pulse/database-events\n\
  \      - type: OpenAPI\n        url: openapi/prisma-pulse-openapi.yml\n      - type: Getting Started\n        url: https://www.prisma.io/docs/pulse/getting-started\n      - type: FAQ\n        url: https://www.prisma.io/docs/pulse/faq\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\n  - name: Prisma Postgres Management API\n    description: REST API for programmatically provisioning and managing Prisma Postgres databases, projects, and workspaces, supporting automation, CI/CD workflows, and partner integrations.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/postgres/introduction/management-api\n    baseUrl: https://api.prisma.io/v1\n    tags:\n      - Database\n      - Infrastructure\n      - Managed Database\n      - PostgreSQL\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://www.prisma.io/docs/postgres/introduction/management-api\n\
  \      - type: OpenAPI\n        url: openapi/prisma-postgres-management-openapi.yml\n      - type: Getting Started\n        url: https://www.prisma.io/docs/guides/management-api-basic\n      - type: Authentication\n        url: https://www.prisma.io/docs/management-api/authentication\n      - type: SDKs\n        url: https://www.prisma.io/docs/management-api/sdk\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\n  - name: Prisma Client API\n    description: Auto-generated, type-safe query builder for Node.js and TypeScript that provides programmatic database access for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB, and CockroachDB.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/orm/reference/prisma-client-reference\n    tags:\n      - Database\n      - Node.js\n      - ORM\n      - Query Builder\n      - TypeScript\n    properties:\n      - type: Documentation\n  \
  \      url: https://www.prisma.io/docs/orm\n      - type: OpenAPI\n        url: openapi/prisma-client-openapi.yml\n      - type: Reference\n        url: https://www.prisma.io/docs/orm/reference/prisma-client-reference\n      - type: Getting Started\n        url: https://www.prisma.io/docs/getting-started/prisma-orm/quickstart/prisma-postgres\n      - type: SDKs\n        url: https://www.npmjs.com/package/@prisma/client\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\n  - name: Prisma Optimize API\n    description: Query performance tool for analyzing, debugging, and improving database queries during development, with AI-powered recommendations to reduce database load and improve responsiveness.\n    image: https://www.prisma.io/images/prisma-logo.svg\n    humanUrl: https://www.prisma.io/docs/optimize\n    tags:\n      - AI\n      - Database\n      - Developer Tools\n      - Performance\n      - Query Optimization\n\
  \    properties:\n      - type: Documentation\n        url: https://www.prisma.io/docs/optimize\n      - type: OpenAPI\n        url: openapi/prisma-optimize-openapi.yml\n      - type: Getting Started\n        url: https://www.prisma.io/docs/optimize/getting-started\n      - type: SDKs\n        url: https://www.npmjs.com/package/@prisma/extension-optimize\n    contact:\n      - FN: Prisma Support\n        email: support@prisma.io\n        url: https://www.prisma.io/support\ncommon:\n  - type: Portal\n    url: https://console.prisma.io/login\n  - type: Documentation\n    url: https://www.prisma.io/docs\n  - type: Getting Started\n    url: https://www.prisma.io/docs/getting-started\n  - type: Authentication\n    url: https://www.prisma.io/docs/management-api/authentication\n  - type: Blog\n    url: https://www.prisma.io/blog\n  - type: Change Log\n    url: https://www.prisma.io/changelog\n  - type: GitHub Organization\n    url: https://github.com/prisma\n  - type: Community\n    url: https://www.prisma.io/community\n\
  \  - type: Discord\n    url: https://pris.ly/discord\n  - type: Twitter\n    url: https://twitter.com/prisma\n  - type: Pricing\n    url: https://www.prisma.io/pricing\n  - type: Status\n    url: https://www.prisma-status.com\n  - type: Support\n    url: https://www.prisma.io/support\n  - type: Terms of Service\n    url: https://www.prisma.io/terms\n  - type: Privacy Policy\n    url: https://www.prisma.io/privacy\n  - type: Website\n    url: https://www.prisma.io\n  - type: Login\n    url: https://console.prisma.io/login\n  - type: Sign Up\n    url: https://console.prisma.io/sign-up\n  - type: JSON-LD Context\n    url: json-ld/prisma-context.jsonld\n  - type: JSON Schema\n    url: json-schema/prisma-workspace-schema.json\n  - type: JSON Schema\n    url: json-schema/prisma-project-schema.json\n  - type: JSON Schema\n    url: json-schema/prisma-database-schema.json\n  - type: JSON Schema\n    url: json-schema/prisma-cache-strategy-schema.json\n  - type: JSON Schema\n    url: json-schema/prisma-pulse-event-schema.json\n\
  \  - type: JSON Schema\n    url: json-schema/prisma-query-recommendation-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://www.prisma.io\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/apis.yml
tags: []
url: https://www.prisma.io
use_cases: []
---
