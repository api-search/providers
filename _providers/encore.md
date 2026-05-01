---
api_count: 2
apis:
- description: The encore.app configuration file is the canonical declaration of an Encore application, including its platform application ID, primary language, global CORS rules, and authenticator settings. The JSO
  name: Encore Application Configuration
  slug: encore-application-config
- description: The Encore CLI provides commands for creating, running, building, testing, deploying, and operating Encore applications. It also generates type-safe API clients in Go, TypeScript, JavaScript, and expe
  name: Encore CLI
  slug: encore-cli
common:
- title: ''
  type: Website
  url: https://encore.dev/
- title: ''
  type: Documentation
  url: https://encore.dev/docs
- title: ''
  type: Getting Started
  url: https://encore.dev/docs/ts/quick-start
- title: ''
  type: GitHub Organization
  url: https://github.com/encoredev
- title: ''
  type: GitHub Repository
  url: https://github.com/encoredev/encore
- title: ''
  type: Blog
  url: https://encore.dev/blog
- title: ''
  type: Pricing
  url: https://encore.dev/pricing
- title: ''
  type: Discord
  url: https://encore.dev/discord
- title: ''
  type: License
  url: https://github.com/encoredev/encore/blob/main/LICENSE
created: '2026-03-26'
description: Encore is an open source development platform for building type-safe, production-ready backend applications and distributed systems. It supports Go and TypeScript, provides built-in infrastructure automation for databases, caches, pub/sub, and cron jobs, and includes a local development dashboard with automatic API documentation, distributed tracing, and OpenAPI client generation.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Encore
skills: []
slug: encore
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: encore\nname: Encore\ndescription: >-\n  Encore is an open source development platform for building type-safe,\n  production-ready backend applications and distributed systems. It supports\n  Go and TypeScript, provides built-in infrastructure automation for\n  databases, caches, pub/sub, and cron jobs, and includes a local\n  development dashboard with automatic API documentation, distributed\n  tracing, and OpenAPI client generation.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backend\n  - Cloud Native\n  - Frameworks\n  - Go\n  - Infrastructure Automation\n  - Microservices\n  - Open Source\n  - TypeScript\nurl: https://raw.githubusercontent.com/api-evangelist/encore/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: encore:encore-application-config\n    name: Encore Application Configuration\n    description: >-\n      The encore.app configuration\
  \ file is the canonical declaration of an\n      Encore application, including its platform application ID, primary\n      language, global CORS rules, and authenticator settings. The\n      JSONSchema captures the supported fields and is used to validate\n      encore.app files in editors and CI pipelines.\n    humanURL: https://encore.dev/docs/ts/develop/app-config\n    tags:\n      - Application Configuration\n      - Encore App\n      - JSON Schema\n    properties:\n      - type: Documentation\n        url: https://encore.dev/docs/ts/develop/app-config\n      - type: JSONSchema\n        url: json-schema/encore-app-configuration.json\n  - aid: encore:encore-cli\n    name: Encore CLI\n    description: >-\n      The Encore CLI provides commands for creating, running, building,\n      testing, deploying, and operating Encore applications. It also\n      generates type-safe API clients in Go, TypeScript, JavaScript, and\n      experimental OpenAPI from any Encore backend, targeting local,\n\
  \      staging, and production environments on the Encore Cloud Platform.\n    humanURL: https://encore.dev/docs/ts/cli/cli-reference\n    tags:\n      - CLI\n      - Client Generation\n      - Developer Tooling\n    properties:\n      - type: Documentation\n        url: https://encore.dev/docs/ts/cli/cli-reference\n      - type: Client Generation\n        url: https://encore.dev/docs/ts/cli/client-generation\n      - type: Install\n        url: https://encore.dev/docs/ts/install\n      - type: Source Code\n        url: https://github.com/encoredev/encore\ncommon:\n  - type: Website\n    url: https://encore.dev/\n  - type: Documentation\n    url: https://encore.dev/docs\n  - type: Getting Started\n    url: https://encore.dev/docs/ts/quick-start\n  - type: GitHub Organization\n    url: https://github.com/encoredev\n  - type: GitHub Repository\n    url: https://github.com/encoredev/encore\n  - type: Blog\n    url: https://encore.dev/blog\n  - type: Pricing\n    url: https://encore.dev/pricing\n\
  \  - type: Discord\n    url: https://encore.dev/discord\n  - type: License\n    url: https://github.com/encoredev/encore/blob/main/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/encore/refs/heads/main/apis.yml
tags:
- Backend
- Cloud Native
- Frameworks
- Go
- Infrastructure Automation
- Microservices
- Open Source
- TypeScript
url: https://raw.githubusercontent.com/api-evangelist/encore/refs/heads/main/apis.yml
use_cases: []
---
