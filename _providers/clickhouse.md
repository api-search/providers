---
api_count: 6
apis:
- description: HTTP interface (default port 8123, HTTPS 8443) for executing SQL queries against ClickHouse. Supports SELECT via GET, mutations via POST, multiple output formats (JSON, CSV, XML, TabSeparated), and au
  name: ClickHouse HTTP Interface
  slug: clickhouse-http-interface
- description: OpenAPI 3.1-described REST API for managing ClickHouse Cloud organizations, services, API keys, members, backups, private endpoints, and ClickHouse settings. Endpoints under /v1 with consistent envelo
  name: ClickHouse Cloud API
  slug: clickhouse-cloud-api
- description: Native binary TCP protocol used by ClickHouse client libraries for maximum throughput between client and server (default port 9000).
  name: ClickHouse Native TCP Interface
  slug: clickhouse-native
- description: MySQL wire protocol compatibility allowing existing MySQL clients and BI tools to query ClickHouse without driver changes.
  name: ClickHouse MySQL Interface
  slug: clickhouse-mysql
- description: PostgreSQL wire protocol compatibility for connecting psql, JDBC and other PostgreSQL clients to ClickHouse.
  name: ClickHouse PostgreSQL Interface
  slug: clickhouse-postgresql
- description: gRPC interface defined by clickhouse_grpc.proto for efficient binary communication.
  name: ClickHouse gRPC Interface
  slug: clickhouse-grpc
capabilities: []
common:
- title: ''
  type: Website
  url: https://clickhouse.com/
- title: ''
  type: Documentation
  url: https://clickhouse.com/docs
- title: ''
  type: Getting Started
  url: https://clickhouse.com/docs/en/getting-started
- title: ''
  type: GitHub
  url: https://github.com/ClickHouse/ClickHouse
- title: ''
  type: Blog
  url: https://clickhouse.com/blog
- title: ''
  type: Community
  url: https://clickhouse.com/community
- title: ''
  type: Slack
  url: https://clickhouse.com/slack
- title: ''
  type: Pricing
  url: https://clickhouse.com/pricing
- title: ''
  type: Support
  url: https://clickhouse.com/support
- title: ''
  type: Status
  url: https://status.clickhouse.com/
- title: ''
  type: Privacy Policy
  url: https://clickhouse.com/legal/privacy-policy
- title: ''
  type: Terms of Service
  url: https://clickhouse.com/legal/terms-of-service
- title: ''
  type: JSON-LD
  url: json-ld/clickhouse-context.jsonld
- title: ''
  type: Spectral
  url: rules/clickhouse-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clickhouse-capabilities.yml
created: '2024-01-01'
description: ClickHouse is a fast open-source column-oriented database management system that enables real-time analytical reporting using SQL. ClickHouse exposes multiple interfaces - an HTTP interface for SQL queries, native TCP, MySQL and PostgreSQL wire-compatible interfaces, and a gRPC interface - and the ClickHouse Cloud management plane offers a public OpenAPI-described REST API for provisioning and managing services, organizations, members, API keys, backups, and private endpoints.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clickhouse Context
  property_count: 5
  slug: clickhouse-context
layout: provider
modified: '2026-04-26'
name: ClickHouse
rules:
- name: ClickHouse API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: clickhouse-rules
skills: []
slug: clickhouse
solutions: []
source_yaml: "aid: clickhouse\nname: ClickHouse\nurl: https://raw.githubusercontent.com/api-evangelist/clickhouse/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-26'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: opensource\ntags:\n  - Analytics\n  - Cloud Database\n  - Column-Oriented\n  - Database\n  - OLAP\n  - Open Source\n  - Real-Time\n  - SQL\ndescription: >-\n  ClickHouse is a fast open-source column-oriented database management system\n  that enables real-time analytical reporting using SQL. ClickHouse exposes\n  multiple interfaces - an HTTP interface for SQL queries, native TCP, MySQL\n  and PostgreSQL wire-compatible interfaces, and a gRPC interface - and the\n  ClickHouse Cloud management plane offers a public OpenAPI-described REST\n  API for provisioning and managing services, organizations, members, API\n  keys, backups, and private\
  \ endpoints.\napis:\n  - aid: clickhouse:clickhouse-http-interface\n    name: ClickHouse HTTP Interface\n    tags:\n      - Database\n      - HTTP\n      - SQL\n    humanURL: https://clickhouse.com/docs/en/interfaces/http\n    baseURL: http://localhost:8123\n    properties:\n      - url: https://clickhouse.com/docs/en/interfaces/http\n        type: Documentation\n    description: >-\n      HTTP interface (default port 8123, HTTPS 8443) for executing SQL\n      queries against ClickHouse. Supports SELECT via GET, mutations via\n      POST, multiple output formats (JSON, CSV, XML, TabSeparated), and\n      authentication via HTTP Basic, URL parameters, or\n      X-ClickHouse-User/X-ClickHouse-Key headers. Helper paths include\n      /ping and /replicas_status.\n  - aid: clickhouse:clickhouse-cloud-api\n    name: ClickHouse Cloud API\n    tags:\n      - Cloud\n      - Management\n      - REST\n    humanURL: https://clickhouse.com/docs/en/cloud/manage/api/api-overview\n    baseURL: https://api.clickhouse.cloud\n\
  \    properties:\n      - url: https://clickhouse.com/docs/en/cloud/manage/api/api-overview\n        type: Documentation\n      - url: https://clickhouse.com/docs/cloud/manage/api/swagger\n        type: Swagger\n      - url: https://api.clickhouse.cloud/v1\n        type: OpenAPI\n    description: >-\n      OpenAPI 3.1-described REST API for managing ClickHouse Cloud\n      organizations, services, API keys, members, backups, private\n      endpoints, and ClickHouse settings. Endpoints under /v1 with\n      consistent envelope responses (status, requestId, result, error)\n      and authentication via API key.\n  - aid: clickhouse:clickhouse-native\n    name: ClickHouse Native TCP Interface\n    tags:\n      - Native\n      - TCP\n    humanURL: https://clickhouse.com/docs/en/interfaces/tcp\n    properties:\n      - url: https://clickhouse.com/docs/en/interfaces/tcp\n        type: Documentation\n    description: >-\n      Native binary TCP protocol used by ClickHouse client libraries for\n\
  \      maximum throughput between client and server (default port 9000).\n  - aid: clickhouse:clickhouse-mysql\n    name: ClickHouse MySQL Interface\n    tags:\n      - MySQL\n      - Wire Protocol\n    humanURL: https://clickhouse.com/docs/en/interfaces/mysql\n    properties:\n      - url: https://clickhouse.com/docs/en/interfaces/mysql\n        type: Documentation\n    description: >-\n      MySQL wire protocol compatibility allowing existing MySQL clients\n      and BI tools to query ClickHouse without driver changes.\n  - aid: clickhouse:clickhouse-postgresql\n    name: ClickHouse PostgreSQL Interface\n    tags:\n      - PostgreSQL\n      - Wire Protocol\n    humanURL: https://clickhouse.com/docs/en/interfaces/postgresql\n    properties:\n      - url: https://clickhouse.com/docs/en/interfaces/postgresql\n        type: Documentation\n    description: >-\n      PostgreSQL wire protocol compatibility for connecting psql, JDBC\n      and other PostgreSQL clients to ClickHouse.\n  - aid:\
  \ clickhouse:clickhouse-grpc\n    name: ClickHouse gRPC Interface\n    tags:\n      - gRPC\n      - Protocol Buffers\n    humanURL: https://clickhouse.com/docs/en/interfaces/grpc\n    properties:\n      - url: https://clickhouse.com/docs/en/interfaces/grpc\n        type: Documentation\n      - url: https://github.com/ClickHouse/ClickHouse/blob/master/src/Server/grpc_protos/clickhouse_grpc.proto\n        type: Protocol Buffers\n    description: >-\n      gRPC interface defined by clickhouse_grpc.proto for efficient binary\n      communication.\ncommon:\n  - type: Website\n    url: https://clickhouse.com/\n  - type: Documentation\n    url: https://clickhouse.com/docs\n  - type: Getting Started\n    url: https://clickhouse.com/docs/en/getting-started\n  - type: GitHub\n    url: https://github.com/ClickHouse/ClickHouse\n  - type: Blog\n    url: https://clickhouse.com/blog\n  - type: Community\n    url: https://clickhouse.com/community\n  - type: Slack\n    url: https://clickhouse.com/slack\n\
  \  - type: Pricing\n    url: https://clickhouse.com/pricing\n  - type: Support\n    url: https://clickhouse.com/support\n  - type: Status\n    url: https://status.clickhouse.com/\n  - type: Privacy Policy\n    url: https://clickhouse.com/legal/privacy-policy\n  - type: Terms of Service\n    url: https://clickhouse.com/legal/terms-of-service\n  - type: JSON-LD\n    url: json-ld/clickhouse-context.jsonld\n  - type: Spectral\n    url: rules/clickhouse-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clickhouse-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clickhouse/refs/heads/main/apis.yml
tags:
- Analytics
- Cloud Database
- Column-Oriented
- Database
- OLAP
- Open Source
- Real-Time
- SQL
url: https://raw.githubusercontent.com/api-evangelist/clickhouse/refs/heads/main/apis.yml
use_cases: []
---
