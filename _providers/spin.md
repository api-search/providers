---
api_count: 5
apis:
- description: The Spin HTTP Trigger API handles incoming HTTP requests and routes them to the appropriate Spin component. Components receive an HTTP request object and return an HTTP response. Supported via the Spi
  name: Spin HTTP Trigger API
  slug: spin-http-trigger-api
- description: The Spin Key-Value Store API provides Spin components with access to a persistent key-value storage service. Components read, write, and delete key-value pairs using the Spin SDK. The underlying store
  name: Spin Key-Value Store API
  slug: spin-key-value-api
- description: The Spin SQLite API provides Spin components with access to an embedded relational database. Components can execute SQL queries and statements using the Spin SDK's SQLite interface, enabling structure
  name: Spin SQLite API
  slug: spin-sqlite-api
- description: The Spin Serverless AI API enables Spin components to run AI inference using built-in language model support (Llama 2, CodeLlama, etc.) via the Spin SDK's infer() function. Components must declare the
  name: Spin Serverless AI API
  slug: spin-serverless-ai-api
- description: The Spin Variables API provides runtime access to application configuration variables defined in spin.toml. Variables can be required or optional with defaults, and can be marked as secrets. At runtim
  name: Spin Variables API
  slug: spin-variables-api
common:
- title: ''
  type: JSONSchema
  url: json-schema/spin-manifest.json
- title: ''
  type: SpectralRules
  url: rules/spin-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/spin-vocabulary.yml
- title: ''
  type: Website
  url: https://spinframework.dev/
- title: ''
  type: Documentation
  url: https://spinframework.dev/v3/
- title: ''
  type: GettingStarted
  url: https://spinframework.dev/v3/quickstart
- title: ''
  type: GitHubOrganization
  url: https://github.com/fermyon
- title: ''
  type: GitHubRepository
  url: https://github.com/fermyon/spin
- title: ''
  type: Releases
  url: https://github.com/fermyon/spin/releases
- title: ''
  type: RoadMap
  url: https://github.com/fermyon/spin/blob/main/ROADMAP.md
- title: ''
  type: Community
  url: https://www.fermyon.com/community
- title: ''
  type: Blog
  url: https://www.fermyon.com/blog
- title: ''
  type: Discord
  url: https://discord.gg/AAFNfS7NGf
- title: ''
  type: X
  url: https://twitter.com/fermyon
created: '2026-03-26'
description: Spin is an open source framework by Fermyon for building and running fast, secure, and composable cloud microservices with WebAssembly. Spin provides a developer experience for creating event-driven serverless applications that compile to WebAssembly and run on any platform that supports the Spin runtime including local dev environments, Kubernetes (via SpinKube), and Fermyon Cloud.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Spin Context
  property_count: 15
  slug: spin-context
layout: provider
modified: '2026-05-02'
name: Spin
rules:
- name: Spin API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: spin-rules
skills: []
slug: spin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spin\nname: Spin\ndescription: >-\n  Spin is an open source framework by Fermyon for building and running fast, secure,\n  and composable cloud microservices with WebAssembly. Spin provides a developer\n  experience for creating event-driven serverless applications that compile to WebAssembly\n  and run on any platform that supports the Spin runtime including local dev environments,\n  Kubernetes (via SpinKube), and Fermyon Cloud.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Microservices\n  - Serverless\n  - WebAssembly\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spin/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spin:spin-http-trigger-api\n    name: Spin HTTP Trigger API\n    description: >-\n      The Spin HTTP Trigger API handles incoming HTTP requests and routes them to\n      the appropriate Spin\
  \ component. Components receive an HTTP request object and\n      return an HTTP response. Supported via the Spin SDK in Rust, Go, Python,\n      JavaScript, and other languages that target WASI.\n    humanURL: https://spinframework.dev/v3/http-trigger\n    tags:\n      - HTTP\n      - Trigger\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://spinframework.dev/v3/http-trigger\n      - type: GitHubRepository\n        url: https://github.com/fermyon/spin\n  - aid: spin:spin-key-value-api\n    name: Spin Key-Value Store API\n    description: >-\n      The Spin Key-Value Store API provides Spin components with access to a persistent\n      key-value storage service. Components read, write, and delete key-value pairs\n      using the Spin SDK. The underlying store can be an in-memory store (for development),\n      Redis, or cloud-managed storage depending on the deployment target.\n    humanURL: https://spinframework.dev/v3/kv-store-api\n    tags:\n \
  \     - Key-Value\n      - Storage\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://spinframework.dev/v3/kv-store-api\n      - type: GitHubRepository\n        url: https://github.com/fermyon/spin\n  - aid: spin:spin-sqlite-api\n    name: Spin SQLite API\n    description: >-\n      The Spin SQLite API provides Spin components with access to an embedded\n      relational database. Components can execute SQL queries and statements using\n      the Spin SDK's SQLite interface, enabling structured data persistence within\n      Spin applications.\n    humanURL: https://spinframework.dev/v3/sqlite-api\n    tags:\n      - Database\n      - SQLite\n      - Storage\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://spinframework.dev/v3/sqlite-api\n      - type: GitHubRepository\n        url: https://github.com/fermyon/spin\n  - aid: spin:spin-serverless-ai-api\n    name: Spin Serverless AI API\n    description: >-\n \
  \     The Spin Serverless AI API enables Spin components to run AI inference using\n      built-in language model support (Llama 2, CodeLlama, etc.) via the Spin SDK's\n      infer() function. Components must declare the ai_models they need in spin.toml.\n      Supported on Fermyon Cloud and SpinKube deployments.\n    humanURL: https://spinframework.dev/v3/serverless-ai-tutorial\n    tags:\n      - AI\n      - LLM\n      - Machine Learning\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://spinframework.dev/v3/serverless-ai-tutorial\n      - type: GitHubRepository\n        url: https://github.com/fermyon/spin\n  - aid: spin:spin-variables-api\n    name: Spin Variables API\n    description: >-\n      The Spin Variables API provides runtime access to application configuration\n      variables defined in spin.toml. Variables can be required or optional with\n      defaults, and can be marked as secrets. At runtime, variables are resolved\n      from environment\
  \ variables, Vault, or other configured providers.\n    humanURL: https://spinframework.dev/v3/variables\n    tags:\n      - Configuration\n      - Variables\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://spinframework.dev/v3/variables\n      - type: GitHubRepository\n        url: https://github.com/fermyon/spin\ncommon:\n  - type: JSONSchema\n    url: json-schema/spin-manifest.json\n  - type: SpectralRules\n    url: rules/spin-rules.yml\n  - type: Vocabulary\n    url: vocabulary/spin-vocabulary.yml\n  - type: Website\n    url: https://spinframework.dev/\n  - type: Documentation\n    url: https://spinframework.dev/v3/\n  - type: GettingStarted\n    url: https://spinframework.dev/v3/quickstart\n  - type: GitHubOrganization\n    url: https://github.com/fermyon\n  - type: GitHubRepository\n    url: https://github.com/fermyon/spin\n  - type: Releases\n    url: https://github.com/fermyon/spin/releases\n  - type: RoadMap\n    url: https://github.com/fermyon/spin/blob/main/ROADMAP.md\n\
  \  - type: Community\n    url: https://www.fermyon.com/community\n  - type: Blog\n    url: https://www.fermyon.com/blog\n  - type: Discord\n    url: https://discord.gg/AAFNfS7NGf\n  - type: X\n    url: https://twitter.com/fermyon\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spin/refs/heads/main/apis.yml
tags:
- Cloud Native
- Microservices
- Serverless
- WebAssembly
url: https://raw.githubusercontent.com/api-evangelist/spin/refs/heads/main/apis.yml
use_cases: []
---
