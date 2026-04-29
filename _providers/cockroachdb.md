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
source_yaml: "aid: cockroachdb\nurl: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml\nname: CockroachDB\ndescription: >-\n  CockroachDB is a distributed SQL database with strong consistency,\n  PostgreSQL compatibility, and a managed cloud offering. The Cloud API\n  manages cluster lifecycle; the Cluster API exposes per-node operational\n  state for monitoring and troubleshooting.\ntags:\n  - Cluster Management\n  - Cloud\n  - Database\n  - Distributed SQL\n  - Infrastructure\n  - PostgreSQL Compatible\n  - SQL\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2024-11-24'\nmodified: '2026-04-26'\nposition: Consumer\nx-overview: >-\n  CockroachDB is a distributed, PostgreSQL-compatible SQL database built by\n  Cockroach Labs. It scales horizontally, survives disk, machine, rack, and\n  data-center failures with localized fallout, and provides ACID transactions\n\
  \  across geographies. CockroachDB is offered as a fully managed service on\n  cockroachlabs.cloud (Basic, Standard, Advanced plans) and as self-hosted\n  software. Two REST APIs are available: the CockroachDB Cloud API for\n  managing the lifecycle of cloud-hosted clusters, and the per-node CockroachDB\n  Cluster API for cluster health, monitoring, and operational status.\napis:\n  - aid: cockroachdb:cloud-api\n    name: CockroachDB Cloud API\n    tags:\n      - Cloud\n      - Cluster Management\n      - Database\n      - Infrastructure\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://cockroachlabs.cloud\n    humanURL: https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api\n    properties:\n      - url: https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api\n        type: Documentation\n      - url: https://www.cockroachlabs.com/docs/api/cloud/v1\n        type: APIReference\n      - url: openapi/cockroachdb-cloud-api-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      REST API for managing the lifecycle of CockroachDB Cloud clusters.\n      Supports cluster provisioning, scaling, deletion, SQL user management,\n      network authorization (IP allowlists, private endpoints), customer-managed\n      encryption keys (CMEK), maintenance windows, version deferral, audit log\n      export, metric and log export, SCIM v2 group/user provisioning, folder\n      organization, service accounts, API keys, invoices, and backup\n      configuration. Authenticated via bearer tokens and rate-limited to 10\n      requests per second per user.\n    x-features:\n      - Bearer-token authentication\n      - Cc-Version header for API versioning\n      - Service accounts and API keys\n      - Terraform provider for IaC\n      - SCIM v2 endpoints for SSO sync\n      - CMEK rotation and revocation\n      - Audit log and metric export configuration\n    x-use-cases:\n      - Programmatic cluster provisioning\n      - GitOps\
  \ with the CockroachDB Terraform provider\n      - SCIM-based identity sync\n      - Audit log export to SIEM\n      - Cost monitoring via invoices\n\n  - aid: cockroachdb:cluster-api\n    name: CockroachDB Cluster API\n    tags:\n      - Cluster\n      - Database\n      - Monitoring\n      - Nodes\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://localhost:8080/api/v2\n    humanURL: https://www.cockroachlabs.com/docs/stable/cluster-api\n    properties:\n      - url: https://www.cockroachlabs.com/docs/stable/cluster-api\n        type: Documentation\n      - url: https://www.cockroachlabs.com/docs/api/cluster/v2\n        type: APIReference\n      - url: openapi/cockroachdb-cluster-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      REST API hosted by every CockroachDB node under the /api/v2 base path,\n      exposed on the same HTTP port as the DB Console (default 8080). Provides\n      health\
  \ checks, node detail, hot range info, session and query\n      introspection, database and table metadata, and event log retrieval.\n      Authentication uses session tokens obtained via /api/v2/login/ and passed\n      in the X-Cockroach-API-Session header.\n    x-features:\n      - Available on every CockroachDB node\n      - Session-token auth via /api/v2/login/\n      - Health, node, range, and database introspection\n      - JSON responses suitable for monitoring pipelines\n    x-use-cases:\n      - Custom dashboards and alerting\n      - Liveness probes and readiness checks\n      - Hot-range and session troubleshooting\n      - Self-hosted observability integrations\n\ncommon:\n  - url: json-schema/cockroachdb-cluster-schema.json\n    type: JSONSchema\n  - url: json-ld/cockroachdb-context.jsonld\n    type: JSON-LD\n  - url: rules/cockroachdb-rules.yml\n    type: Spectral\n  - url: capabilities/cockroachdb-capabilities.yml\n    type: NaftikoCapabilities\n  - type: Website\n    url:\
  \ https://www.cockroachlabs.com/product/\n  - type: Documentation\n    url: https://www.cockroachlabs.com/docs/\n  - type: Pricing\n    url: https://www.cockroachlabs.com/pricing/\n  - type: Console\n    url: https://cockroachlabs.cloud/\n  - type: GitHub\n    url: https://github.com/cockroachdb/cockroach\n  - type: Status\n    url: https://status.cockroachlabs.cloud/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml
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
