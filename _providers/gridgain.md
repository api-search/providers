---
api_count: 2
api_specs:
- filename: gridgain-openapi.yml
  format: yaml
  label: GridGain 9 Management API
  slug: gridgain-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gridgain/refs/heads/main/openapi/gridgain-openapi.yml
apis:
- description: Legacy GridGain 8 / Apache Ignite REST API for cache operations, SQL and scan queries, cluster activation, and node management over HTTP.
  name: GridGain REST API
  slug: gridgain-rest-api
- description: The GridGain 9 management API exposes cluster initialization, node and cluster configuration, authentication and JWT, RBAC, snapshots, CDC, compute jobs, recovery, deployment units, SQL monitoring, an
  name: GridGain 9 Management API
  slug: gridgain-management-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.gridgain.com/
- title: ''
  type: Documentation
  url: https://www.gridgain.com/docs/latest/
- title: ''
  type: Getting Started
  url: https://www.gridgain.com/docs/latest/getting-started/quick-start/java
- title: ''
  type: Support
  url: https://www.gridgain.com/support
- title: ''
  type: Blog
  url: https://www.gridgain.com/resources/blog
- title: ''
  type: GitHub Organization
  url: https://github.com/gridgain
created: '2025-08-19'
description: GridGain is a unified real-time data platform that provides in-memory computing for transactions, analytics, and AI workloads. Built on top of Apache Ignite, it offers distributed database, caching, and computing capabilities for high-performance data-intensive applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: GridGain
rules:
- name: GridGain API Rules
  rule_count: 3
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 1
  slug: gridgain-rules
skills: []
slug: gridgain
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gridgain\nname: GridGain\ndescription: >-\n  GridGain is a unified real-time data platform that provides in-memory\n  computing for transactions, analytics, and AI workloads. Built on top of\n  Apache Ignite, it offers distributed database, caching, and computing\n  capabilities for high-performance data-intensive applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Caching\n  - Data Grid\n  - Distributed Database\n  - In-Memory Computing\n  - Real-Time\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gridgain/refs/heads/main/apis.yml\ncreated: '2025-08-19'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: gridgain:gridgain-rest-api\n    name: GridGain REST API\n    description: >-\n      Legacy GridGain 8 / Apache Ignite REST API for cache operations,\n      SQL and scan queries, cluster activation, and node management over HTTP.\n    humanURL: https://www.gridgain.com/docs/gridgain8/latest/developers-guide/restapi\n\
  \    baseURL: http://localhost:8080/ignite\n    tags:\n      - Caching\n      - Distributed Database\n      - In-Memory Computing\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.gridgain.com/docs/gridgain8/latest/developers-guide/restapi\n      - type: Getting Started\n        url: https://www.gridgain.com/docs/gridgain8/latest/getting-started/quick-start/restapi\n  - aid: gridgain:gridgain-management-api\n    name: GridGain 9 Management API\n    description: >-\n      The GridGain 9 management API exposes cluster initialization, node and\n      cluster configuration, authentication and JWT, RBAC, snapshots, CDC,\n      compute jobs, recovery, deployment units, SQL monitoring, and license\n      management for production GridGain 9 clusters.\n    humanURL: https://www.gridgain.com/sdk/gridgain9/latest/openapi.html\n    baseURL: http://localhost:10300/management/v1\n    tags:\n      - Cluster Management\n      - In-Memory Computing\n      - Management\n\
  \      - REST\n    properties:\n      - type: Documentation\n        url: https://www.gridgain.com/sdk/gridgain9/latest/openapi.html\n      - type: OpenAPI\n        url: openapi/gridgain-openapi.yml\n      - type: Capabilities\n        url: capabilities/gridgain-capabilities.yml\n      - type: Rules\n        url: rules/gridgain-rules.yml\n      - type: JSONSchema\n        url: json-schema/gridgain-schema-index.yml\ncommon:\n  - type: Website\n    url: https://www.gridgain.com/\n  - type: Documentation\n    url: https://www.gridgain.com/docs/latest/\n  - type: Getting Started\n    url: https://www.gridgain.com/docs/latest/getting-started/quick-start/java\n  - type: Support\n    url: https://www.gridgain.com/support\n  - type: Blog\n    url: https://www.gridgain.com/resources/blog\n  - type: GitHub Organization\n    url: https://github.com/gridgain\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gridgain/refs/heads/main/apis.yml
tags:
- Caching
- Data Grid
- Distributed Database
- In-Memory Computing
- Real-Time
url: https://raw.githubusercontent.com/api-evangelist/gridgain/refs/heads/main/apis.yml
use_cases: []
---
