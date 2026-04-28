---
api_count: 2
apis:
- description: REST API for managing the lifecycle of CockroachDB Cloud clusters. Supports cluster provisioning, scaling, deletion, SQL user management, network authorization (IP allowlists, private endpoints), cust
  name: CockroachDB Cloud API
  slug: cloud-api
- description: 'REST API hosted by every CockroachDB node under the /api/v2 base path, exposed on the same HTTP port as the DB Console (default 8080). Provides health checks, node detail, hot range info, session and '
  name: CockroachDB Cluster API
  slug: cluster-api
capabilities: []
common:
- title: ''
  type: JSONSchema
  url: json-schema/cockroachdb-cluster-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/cockroachdb-context.jsonld
- title: ''
  type: Spectral
  url: rules/cockroachdb-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cockroachdb-capabilities.yml
- title: ''
  type: Website
  url: https://www.cockroachlabs.com/product/
- title: ''
  type: Documentation
  url: https://www.cockroachlabs.com/docs/
- title: ''
  type: Pricing
  url: https://www.cockroachlabs.com/pricing/
- title: ''
  type: Console
  url: https://cockroachlabs.cloud/
- title: ''
  type: GitHub
  url: https://github.com/cockroachdb/cockroach
- title: ''
  type: Status
  url: https://status.cockroachlabs.cloud/
created: '2024-11-24'
description: CockroachDB is a distributed SQL database with strong consistency, PostgreSQL compatibility, and a managed cloud offering. The Cloud API manages cluster lifecycle; the Cluster API exposes per-node operational state for monitoring and troubleshooting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cockroachdb Context
  property_count: 14
  slug: cockroachdb-context
layout: provider
modified: '2026-04-26'
name: CockroachDB
rules:
- name: CockroachDB API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 4
  slug: cockroachdb-rules
skills: []
slug: cockroachdb
solutions: []
tags:
- Cluster Management
- Cloud
- Database
- Distributed SQL
- Infrastructure
- PostgreSQL Compatible
- SQL
url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml
use_cases: []
---
