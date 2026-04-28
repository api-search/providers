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
