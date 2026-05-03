---
api_count: 4
api_specs:
- filename: tikv-http-api-openapi.yml
  format: yaml
  label: TiKV HTTP Management API
  slug: tikv-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/openapi/tikv-http-api-openapi.yml
apis:
- description: TiKV exposes an HTTP API for cluster management, status monitoring, configuration retrieval and updates, and Prometheus metrics collection.
  name: TiKV HTTP Management API
  slug: tikv-http-api
- description: The official Java client for TiKV. Supports raw key-value operations and transactional operations via gRPC. Available on Maven Central.
  name: TiKV Java Client
  slug: tikv-client-java
- description: The official Rust client for TiKV providing raw and transactional key-value access to TiKV clusters.
  name: TiKV Rust Client
  slug: tikv-client-rust
- description: The official Python client for TiKV supporting raw and transactional key-value operations.
  name: TiKV Python Client
  slug: tikv-client-python
capabilities:
- description: Workflow capability for operating and monitoring TiKV distributed clusters. Uses the TiKV HTTP management API to inspect node health, retrieve configuration, collect metrics, and examine Raft region d
  name: TiKV Cluster Operations
  slug: cluster-operations
common:
- title: ''
  type: Website
  url: https://tikv.org/
- title: ''
  type: Documentation
  url: https://tikv.org/docs/
- title: ''
  type: Getting Started
  url: https://tikv.org/docs/7.1/concepts/overview/
- title: ''
  type: GitHub Organization
  url: https://github.com/tikv
- title: ''
  type: GitHub Repository
  url: https://github.com/tikv/tikv
- title: ''
  type: Governance
  url: https://github.com/tikv/tikv/blob/master/GOVERNANCE.md
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/tikv/
- title: ''
  type: Blog
  url: https://tikv.org/blog/
- title: ''
  type: Community
  url: https://tikv.org/community/
- title: ''
  type: Roadmap
  url: https://github.com/tikv/tikv/blob/master/ROADMAP.md
- title: ''
  type: License
  url: https://github.com/tikv/tikv/blob/master/LICENSE
- title: ''
  type: Slack
  url: https://slack.tidb.io/invite?team=tikv-wg
- title: ''
  type: Forum
  url: https://internals.tidb.io/
- title: ''
  type: SDK
  url: https://github.com/tikv/client-java
- title: ''
  type: SDK
  url: https://github.com/tikv/client-rust
- title: ''
  type: SDK
  url: https://github.com/tikv/client-py
- title: ''
  type: SDK
  url: https://github.com/tikv/client-go
created: '2025-01-01'
description: TiKV is a CNCF-graduated distributed transactional key-value database built in Rust with Raft consensus. Originally created to complement TiDB, it provides horizontal scalability, strong consistency, and high availability with ACID transaction support. Client APIs are available for Java, Rust, Python, Go, and C++. An HTTP management API provides status, configuration, and monitoring endpoints.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Tikv Context
  property_count: 0
  slug: tikv-context
layout: provider
modified: '2026-05-03'
name: TiKV
rules:
- name: TiKV API Rules
  rule_count: 4
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 2
  slug: tikv-rules
skills: []
slug: tikv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tikv\nname: TiKV\ndescription: >-\n  TiKV is a CNCF-graduated distributed transactional key-value database built\n  in Rust with Raft consensus. Originally created to complement TiDB, it\n  provides horizontal scalability, strong consistency, and high availability\n  with ACID transaction support. Client APIs are available for Java, Rust,\n  Python, Go, and C++. An HTTP management API provides status, configuration,\n  and monitoring endpoints.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/apis.yml\ntags:\n  - ACID\n  - CNCF\n  - Database\n  - Distributed Systems\n  - Key-Value Store\n  - Open Source\n  - Rust\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tikv:tikv-http-api\n    name: TiKV HTTP Management API\n    description: >-\n      TiKV exposes an HTTP API for cluster management, status monitoring,\n\
  \      configuration retrieval and updates, and Prometheus metrics collection.\n    humanURL: https://tikv.org/docs/dev/deploy/monitor/api/\n    baseURL: http://localhost:20160\n    tags:\n      - Database\n      - Distributed Systems\n      - Monitoring\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://tikv.org/docs/dev/deploy/monitor/api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/openapi/tikv-http-api-openapi.yml\n  - aid: tikv:tikv-client-java\n    name: TiKV Java Client\n    description: >-\n      The official Java client for TiKV. Supports raw key-value operations\n      and transactional operations via gRPC. Available on Maven Central.\n    humanURL: https://github.com/tikv/client-java\n    tags:\n      - Database\n      - Java\n      - Key-Value\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/tikv/client-java\n      - type:\
  \ GitHub\n        url: https://github.com/tikv/client-java\n  - aid: tikv:tikv-client-rust\n    name: TiKV Rust Client\n    description: >-\n      The official Rust client for TiKV providing raw and transactional\n      key-value access to TiKV clusters.\n    humanURL: https://github.com/tikv/client-rust\n    tags:\n      - Database\n      - Key-Value\n      - Rust\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/tikv/client-rust\n      - type: GitHub\n        url: https://github.com/tikv/client-rust\n  - aid: tikv:tikv-client-python\n    name: TiKV Python Client\n    description: >-\n      The official Python client for TiKV supporting raw and transactional\n      key-value operations.\n    humanURL: https://github.com/tikv/client-py\n    tags:\n      - Database\n      - Key-Value\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/tikv/client-py\n      - type: GitHub\n        url: https://github.com/tikv/client-py\n\
  common:\n  - type: Website\n    url: https://tikv.org/\n  - type: Documentation\n    url: https://tikv.org/docs/\n  - type: Getting Started\n    url: https://tikv.org/docs/7.1/concepts/overview/\n  - type: GitHub Organization\n    url: https://github.com/tikv\n  - type: GitHub Repository\n    url: https://github.com/tikv/tikv\n  - type: Governance\n    url: https://github.com/tikv/tikv/blob/master/GOVERNANCE.md\n  - type: CNCF\n    url: https://www.cncf.io/projects/tikv/\n  - type: Blog\n    url: https://tikv.org/blog/\n  - type: Community\n    url: https://tikv.org/community/\n  - type: Roadmap\n    url: https://github.com/tikv/tikv/blob/master/ROADMAP.md\n  - type: License\n    url: https://github.com/tikv/tikv/blob/master/LICENSE\n  - type: Slack\n    url: https://slack.tidb.io/invite?team=tikv-wg\n  - type: Forum\n    url: https://internals.tidb.io/\n  - type: SDK\n    url: https://github.com/tikv/client-java\n  - type: SDK\n    url: https://github.com/tikv/client-rust\n  - type: SDK\n\
  \    url: https://github.com/tikv/client-py\n  - type: SDK\n    url: https://github.com/tikv/client-go\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/apis.yml
tags:
- ACID
- CNCF
- Database
- Distributed Systems
- Key-Value Store
- Open Source
- Rust
url: https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/apis.yml
use_cases: []
---
