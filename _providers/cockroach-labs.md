---
api_count: 2
apis:
- description: REST API for managing the lifecycle of CockroachDB Cloud clusters. Supports cluster provisioning, scaling, deletion, SQL user management, network authorization (IP allowlists, private endpoints), cust
  name: CockroachDB Cloud API
  slug: cockroach-labs-cloud-api
- description: 'REST API hosted by every CockroachDB node under the /api/v2 base path, exposed on the same HTTP port as the DB Console (default 8080). Provides health checks, node detail, hot range info, session and '
  name: CockroachDB Cluster API
  slug: cockroach-labs-cluster-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cockroachlabs.com/
- title: ''
  type: Documentation
  url: https://www.cockroachlabs.com/docs/
- title: ''
  type: Pricing
  url: https://www.cockroachlabs.com/pricing/
- title: ''
  type: Blog
  url: https://www.cockroachlabs.com/blog/
- title: ''
  type: Glossary
  url: https://www.cockroachlabs.com/docs/stable/architecture/glossary
- title: ''
  type: Console
  url: https://cockroachlabs.cloud/
- title: ''
  type: Status
  url: https://status.cockroachlabs.cloud/
- title: ''
  type: Support
  url: https://www.cockroachlabs.com/support/
- title: ''
  type: Partners
  url: https://www.cockroachlabs.com/partners/
- title: ''
  type: Security
  url: https://www.cockroachlabs.com/security/
- title: ''
  type: GitHub
  url: https://github.com/cockroachdb
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/cockroachdb/cockroach/latest
- title: ''
  type: PrivacyPolicy
  url: https://www.cockroachlabs.com/privacy/
- title: ''
  type: TermsOfService
  url: https://www.cockroachlabs.com/cloud-terms-and-conditions/
- title: ''
  type: JSON-LD
  url: json-ld/cockroach-labs-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cockroach-labs-cluster-schema.json
- title: ''
  type: Spectral
  url: rules/cockroach-labs-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cockroach-labs-capabilities.yml
created: '2024-11-24'
description: 'Cockroach Labs is the New York-based software company that builds CockroachDB, a cloud-native, distributed, PostgreSQL-compatible SQL database. CockroachDB is offered as Cockroach Labs'' fully managed cloud service (Basic, Standard, and Advanced plans) and as self-hosted software. The company provides two primary developer APIs: the CockroachDB Cloud API for managing the lifecycle of cloud-hosted clusters, and the CockroachDB Cluster API exposed by every node for cluster health, monitoring, and operational status. CockroachDB is used in production by banking, retail, gaming, and media companies including Bose, Hard Rock Digital, DoorDash, and Netflix.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cockroach Labs Context
  property_count: 14
  slug: cockroach-labs-context
layout: provider
modified: '2026-04-26'
name: Cockroach Labs
rules:
- name: Cockroach Labs API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 4
  slug: cockroach-labs-rules
skills: []
slug: cockroach-labs
solutions: []
source_yaml: "aid: cockroach-labs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cockroach-labs/refs/heads/main/apis.yml\nname: Cockroach Labs\ntags:\n  - Cluster Management\n  - Cloud\n  - Database\n  - Distributed SQL\n  - Infrastructure\n  - PostgreSQL Compatible\n  - SQL\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2024-11-24'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Cockroach Labs is the New York-based software company that builds CockroachDB,\n  a cloud-native, distributed, PostgreSQL-compatible SQL database. CockroachDB\n  is offered as Cockroach Labs' fully managed cloud service (Basic, Standard,\n  and Advanced plans) and as self-hosted software. The company provides two\n  primary developer APIs: the CockroachDB Cloud API for managing the lifecycle\n  of cloud-hosted clusters, and the CockroachDB Cluster API exposed by every\n  node for cluster health,\
  \ monitoring, and operational status. CockroachDB is\n  used in production by banking, retail, gaming, and media companies including\n  Bose, Hard Rock Digital, DoorDash, and Netflix.\napis:\n  - aid: cockroach-labs:cockroach-labs-cloud-api\n    name: CockroachDB Cloud API\n    tags:\n      - Cloud\n      - Cluster Management\n      - Database\n      - Infrastructure\n    humanURL: https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api\n    baseURL: https://cockroachlabs.cloud\n    properties:\n      - url: https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api\n        type: Documentation\n      - url: https://www.cockroachlabs.com/docs/api/cloud/v1\n        type: APIReference\n      - url: openapi/cockroach-labs-cloud-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      REST API for managing the lifecycle of CockroachDB Cloud clusters.\n      Supports cluster provisioning, scaling, deletion, SQL user management,\n      network authorization (IP allowlists, private\
  \ endpoints), customer-managed\n      encryption keys (CMEK), maintenance windows, version deferral, audit log\n      export, metric and log export, SCIM v2 group/user provisioning, folder\n      organization, service accounts, API keys, invoices, and backup\n      configuration. Authenticated via bearer tokens and rate-limited to 10\n      requests per second per user. Also available via the official\n      CockroachDB Cloud Terraform provider.\n    x-features:\n      - Bearer-token authentication with service accounts and API keys\n      - Cc-Version header for API versioning\n      - 10 RPS rate limit per user\n      - SCIM v2 endpoints for SSO group/user sync\n      - Terraform provider for IaC workflows\n      - CMEK rotation, revocation, and key-spec management\n      - Cluster scaling, maintenance windows, and version deferral\n      - Audit log and metric/log export configuration\n    x-use-cases:\n      - Programmatic provisioning of CockroachDB clusters\n      - GitOps/IaC management\
  \ with Terraform\n      - SCIM-based identity sync from Okta, Entra ID, Google Workspace\n      - Compliance automation via audit log export to SIEM\n      - Cost monitoring via invoices endpoint\n  - aid: cockroach-labs:cockroach-labs-cluster-api\n    name: CockroachDB Cluster API\n    tags:\n      - Cluster\n      - Database\n      - Monitoring\n      - Nodes\n      - Observability\n    humanURL: https://www.cockroachlabs.com/docs/stable/cluster-api\n    baseURL: https://localhost:8080\n    properties:\n      - url: https://www.cockroachlabs.com/docs/stable/cluster-api\n        type: Documentation\n      - url: https://www.cockroachlabs.com/docs/api/cluster/v2\n        type: APIReference\n      - url: openapi/cockroach-labs-cluster-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      REST API hosted by every CockroachDB node under the /api/v2 base path,\n      exposed on the same HTTP port as the DB Console (default 8080). Provides\n      health checks, node detail, hot\
  \ range info, session and query\n      introspection, database and table metadata, and event log retrieval.\n      Authentication uses session tokens obtained via /api/v2/login/ and\n      passed in the X-Cockroach-API-Session header. Self-hosted operators\n      typically front the cluster API with a load balancer or service mesh.\n    x-features:\n      - Available on every CockroachDB node\n      - Session-token authentication via /api/v2/login/\n      - Health, node, range, session, and database introspection\n      - JSON responses suitable for monitoring and alerting integrations\n    x-use-cases:\n      - Custom dashboards and observability pipelines\n      - Programmatic health/readiness checks\n      - Hot-range and session troubleshooting\n      - Liveness probes for self-hosted CockroachDB\ncommon:\n  - type: Website\n    url: https://www.cockroachlabs.com/\n  - type: Documentation\n    url: https://www.cockroachlabs.com/docs/\n  - type: Pricing\n    url: https://www.cockroachlabs.com/pricing/\n\
  \  - type: Blog\n    url: https://www.cockroachlabs.com/blog/\n  - type: Glossary\n    url: https://www.cockroachlabs.com/docs/stable/architecture/glossary\n  - type: Console\n    url: https://cockroachlabs.cloud/\n  - type: Status\n    url: https://status.cockroachlabs.cloud/\n  - type: Support\n    url: https://www.cockroachlabs.com/support/\n  - type: Partners\n    url: https://www.cockroachlabs.com/partners/\n  - type: Security\n    url: https://www.cockroachlabs.com/security/\n  - type: GitHub\n    url: https://github.com/cockroachdb\n  - type: TerraformProvider\n    url: https://registry.terraform.io/providers/cockroachdb/cockroach/latest\n  - type: PrivacyPolicy\n    url: https://www.cockroachlabs.com/privacy/\n  - type: TermsOfService\n    url: https://www.cockroachlabs.com/cloud-terms-and-conditions/\n  - url: json-ld/cockroach-labs-context.jsonld\n    type: JSON-LD\n  - url: json-schema/cockroach-labs-cluster-schema.json\n    type: JSONSchema\n  - url: rules/cockroach-labs-rules.yml\n\
  \    type: Spectral\n  - url: capabilities/cockroach-labs-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cockroach-labs/refs/heads/main/apis.yml
tags:
- Cluster Management
- Cloud
- Database
- Distributed SQL
- Infrastructure
- PostgreSQL Compatible
- SQL
url: https://raw.githubusercontent.com/api-evangelist/cockroach-labs/refs/heads/main/apis.yml
use_cases: []
---
