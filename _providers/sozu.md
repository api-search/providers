---
api_count: 3
apis:
- description: 'The Sozu Command API provides programmatic control of the Sōzu HTTP reverse proxy at runtime. External tools communicate with the Sozu main process through a secure Unix socket using a protobuf-based '
  name: Sozu Command API
  slug: sozu-command-api
- description: The Sozu ACME integration automates TLS certificate requests from Let's Encrypt and other ACME-enabled certificate authorities. Originally a standalone tool in the sozu-acme repository, it has been in
  name: Sozu ACME Integration
  slug: sozu-acme-api
- description: The sozu-command-futures library provides a futures-based async Rust API for configuring the Sōzu HTTP reverse proxy programmatically. It wraps the low-level IPC protocol in an ergonomic async interfa
  name: Sozu Command Futures API
  slug: sozu-command-futures-api
common:
- title: ''
  type: Website
  url: https://www.sozu.io/
- title: ''
  type: Documentation
  url: https://docs.sozu.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/sozu-proxy
- title: ''
  type: GitHub Repository
  url: https://github.com/sozu-proxy/sozu
- title: ''
  type: Releases
  url: https://github.com/sozu-proxy/sozu/releases
- title: ''
  type: Dashboard
  url: https://github.com/sozu-proxy/dashboard
- title: ''
  type: Integration Tests
  url: https://github.com/sozu-proxy/sozu-integration-tests
- title: ''
  type: JSON-LD Context
  url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-ld/sozu-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/vocabulary/sozu-vocabulary.yml
created: '2026-03-27'
description: Sōzu is an open-source, fast and lightweight HTTP reverse proxy written in Rust, designed for high-performance traffic management in immutable infrastructure environments. It is configurable at runtime through a protobuf-based IPC protocol without requiring restarts, making it ideal for always-up deployments. Sōzu supports TLS termination, load balancing, and dynamic cluster configuration, and is developed by the sozu-proxy open-source organization on GitHub.
features: []
image: ''
integrations: []
jsonld:
- class_count: 8
  name: Sozu Context
  property_count: 16
  slug: sozu-context
layout: provider
modified: '2026-05-02'
name: Sozu
skills: []
slug: sozu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sozu\nname: Sozu\ndescription: >-\n  Sōzu is an open-source, fast and lightweight HTTP reverse proxy written in Rust,\n  designed for high-performance traffic management in immutable infrastructure environments.\n  It is configurable at runtime through a protobuf-based IPC protocol without requiring\n  restarts, making it ideal for always-up deployments. Sōzu supports TLS termination,\n  load balancing, and dynamic cluster configuration, and is developed by the sozu-proxy\n  open-source organization on GitHub.\nurl: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Proxy\n  - Reverse Proxy\n  - Load Balancing\n  - Rust\n  - Open Source\napis:\n  - aid: sozu:sozu-command-api\n    name: Sozu Command API\n    description: >-\n      The Sozu Command API provides programmatic control of the Sōzu HTTP reverse proxy\n      at runtime. External tools communicate\
  \ with the Sozu main process through a secure\n      Unix socket using a protobuf-based binary protocol (IPC). The sozu-command-lib crate\n      ships the protobuf schema, configuration parser, replicated state, channels, and\n      file descriptor passing helpers. This enables dynamic cluster configuration,\n      certificate management, and backend routing changes without restarts.\n    humanURL: https://docs.sozu.io/\n    baseURL: https://github.com/sozu-proxy/sozu\n    tags:\n      - Proxy\n      - Command API\n      - Protobuf\n      - Runtime Configuration\n    properties:\n      - type: Documentation\n        url: https://docs.sozu.io/\n      - type: GitHub\n        url: https://github.com/sozu-proxy/sozu\n      - type: Getting Started\n        url: https://docs.sozu.io/getting-started/\n      - type: Configuration\n        url: https://github.com/sozu-proxy/sozu/blob/main/doc/configure.md\n      - type: How To Use\n        url: https://github.com/sozu-proxy/sozu/blob/main/doc/how_to_use.md\n\
  \      - type: JSON Schema\n        url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-schema/sozu-cluster-schema.json\n      - type: JSON Schema\n        url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-schema/sozu-frontend-schema.json\n  - aid: sozu:sozu-acme-api\n    name: Sozu ACME Integration\n    description: >-\n      The Sozu ACME integration automates TLS certificate requests from Let's Encrypt\n      and other ACME-enabled certificate authorities. Originally a standalone tool in\n      the sozu-acme repository, it has been integrated directly into the main Sōzu\n      binary and is available as a command-line feature.\n    humanURL: https://github.com/sozu-proxy/sozu-acme\n    tags:\n      - TLS\n      - Certificates\n      - ACME\n      - Let's Encrypt\n    properties:\n      - type: GitHub\n        url: https://github.com/sozu-proxy/sozu-acme\n  - aid: sozu:sozu-command-futures-api\n    name: Sozu Command Futures API\n\
  \    description: >-\n      The sozu-command-futures library provides a futures-based async Rust API for\n      configuring the Sōzu HTTP reverse proxy programmatically. It wraps the low-level\n      IPC protocol in an ergonomic async interface for Rust applications.\n    humanURL: https://github.com/sozu-proxy/sozu-command-futures\n    tags:\n      - Proxy\n      - Rust\n      - Async\n      - Command API\n    properties:\n      - type: GitHub\n        url: https://github.com/sozu-proxy/sozu-command-futures\ncommon:\n  - type: Website\n    url: https://www.sozu.io/\n  - type: Documentation\n    url: https://docs.sozu.io/\n  - type: GitHub Organization\n    url: https://github.com/sozu-proxy\n  - type: GitHub Repository\n    url: https://github.com/sozu-proxy/sozu\n  - type: Releases\n    url: https://github.com/sozu-proxy/sozu/releases\n  - type: Dashboard\n    url: https://github.com/sozu-proxy/dashboard\n  - type: Integration Tests\n    url: https://github.com/sozu-proxy/sozu-integration-tests\n\
  \  - type: JSON-LD Context\n    url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-ld/sozu-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/vocabulary/sozu-vocabulary.yml\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/apis.yml
tags:
- Proxy
- Reverse Proxy
- Load Balancing
- Rust
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/apis.yml
use_cases: []
---
