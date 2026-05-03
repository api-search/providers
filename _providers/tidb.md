---
api_count: 4
api_specs:
- filename: tidb-cloud-api-openapi.yml
  format: yaml
  label: TiDB Cloud API
  slug: tidb-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-api-openapi.yml
- filename: tidb-cloud-data-service-openapi.yml
  format: yaml
  label: TiDB Cloud Data Service API
  slug: tidb-cloud-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-data-service-openapi.yml
- filename: tidb-cloud-chat2query-openapi.yml
  format: yaml
  label: TiDB Cloud Chat2Query API
  slug: tidb-cloud-chat2query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-cloud-chat2query-openapi.yml
- filename: tidb-http-api-openapi.yml
  format: yaml
  label: TiDB HTTP API
  slug: tidb-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/openapi/tidb-http-api-openapi.yml
apis:
- description: The TiDB Cloud API is a REST interface that provides programmatic access to manage administrative objects within TiDB Cloud. It supports managing projects, clusters, backups, restores, data imports, b
  name: TiDB Cloud API
  slug: tidb-cloud-api
- description: 'TiDB Cloud Data Service enables developers to access TiDB Cloud data via HTTPS requests using custom API endpoints backed by SQL queries. Developers define endpoints within a Data App, specifying the '
  name: TiDB Cloud Data Service API
  slug: tidb-cloud-data-service-api
- description: The TiDB Cloud Chat2Query API is an AI-powered interface that allows developers to generate and execute SQL statements against TiDB Cloud clusters using natural language instructions. It is exposed as
  name: TiDB Cloud Chat2Query API
  slug: tidb-cloud-chat2query-api
- description: The TiDB HTTP API is a built-in administrative interface available on self-managed TiDB server instances, accessible on port 10080 by default. It exposes endpoints for retrieving server status, databa
  name: TiDB HTTP API
  slug: tidb-http-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/tidb-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tidb-cluster-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tidb-data-service-schema.json
created: ''
description: TiDB is an open-source distributed SQL database that supports Hybrid Transactional and Analytical Processing workloads, with horizontal scalability, strong consistency, and high availability.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Tidb Context
  property_count: 16
  slug: tidb-context
layout: provider
modified: '2026-03-21'
name: tidb
skills: []
slug: tidb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tidb\nurl: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/apis.yml\napis:\n  - aid: tidb:tidb-cloud-api\n    name: TiDB Cloud API\n    tags:\n      - Cloud\n      - Cluster Management\n      - Database\n      - Distributed SQL\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.tidbcloud.com\n    humanURL: https://docs.pingcap.com/tidbcloud/api-overview/\n    properties:\n      - url: https://docs.pingcap.com/tidbcloud/api-overview/\n        type: Documentation\n      - url: https://docs.pingcap.com/tidbcloud/api/v1beta/\n        type: Documentation\n      - url: openapi/tidb-cloud-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/tidb-cluster-schema.json\n        type: JSONSchema\n    description: >-\n      The TiDB Cloud API is a REST interface that provides programmatic access to\n      manage administrative objects within TiDB Cloud. It supports managing projects,\n \
  \     clusters, backups, restores, data imports, billing, and private endpoint connections\n      across both TiDB Cloud Serverless and TiDB Cloud Dedicated tiers. The API uses\n      digest authentication with public and private API keys and returns JSON-formatted\n      responses.\n\n  - aid: tidb:tidb-cloud-data-service-api\n    name: TiDB Cloud Data Service API\n    tags:\n      - Cloud\n      - Data Access\n      - Database\n      - REST\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://data.tidbcloud.com\n    humanURL: https://docs.pingcap.com/tidbcloud/data-service-overview/\n    properties:\n      - url: https://docs.pingcap.com/tidbcloud/data-service-overview/\n        type: Documentation\n      - url: https://docs.pingcap.com/tidbcloud/data-service-get-started/\n        type: Documentation\n      - url: openapi/tidb-cloud-data-service-openapi.yml\n        type: OpenAPI\n      - url: json-schema/tidb-data-service-schema.json\n\
  \        type: JSONSchema\n    description: >-\n      TiDB Cloud Data Service enables developers to access TiDB Cloud data via HTTPS\n      requests using custom API endpoints backed by SQL queries. Developers define\n      endpoints within a Data App, specifying the HTTP method, path, and the SQL logic\n      that the endpoint executes against a linked TiDB Cloud cluster. Endpoints support\n      GET, POST, PUT, and DELETE methods, return JSON-formatted results, and can be\n      configured with pagination, rate limiting, and caching.\n\n  - aid: tidb:tidb-cloud-chat2query-api\n    name: TiDB Cloud Chat2Query API\n    tags:\n      - AI\n      - Cloud\n      - Database\n      - Natural Language\n      - SQL Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://data.tidbcloud.com\n    humanURL: https://docs.pingcap.com/tidbcloud/use-chat2query-api/\n    properties:\n      - url: https://docs.pingcap.com/tidbcloud/use-chat2query-api/\n\
  \        type: Documentation\n      - url: openapi/tidb-cloud-chat2query-openapi.yml\n        type: OpenAPI\n    description: >-\n      The TiDB Cloud Chat2Query API is an AI-powered interface that allows developers\n      to generate and execute SQL statements against TiDB Cloud clusters using natural\n      language instructions. It is exposed as a special Data App within TiDB Cloud\n      and authenticated via API keys scoped to the Chat2Query Data App.\n\n  - aid: tidb:tidb-http-api\n    name: TiDB HTTP API\n    tags:\n      - Database\n      - Monitoring\n      - Operations\n      - Self-Managed\n      - Status\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: http://localhost:10080\n    humanURL: https://github.com/pingcap/tidb/blob/master/docs/tidb_http_api.md\n    properties:\n      - url: https://github.com/pingcap/tidb/blob/master/docs/tidb_http_api.md\n        type: Documentation\n      - url: https://docs.pingcap.com/tidb/stable/tidb-monitoring-api/\n\
  \        type: Documentation\n      - url: openapi/tidb-http-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The TiDB HTTP API is a built-in administrative interface available on self-managed\n      TiDB server instances, accessible on port 10080 by default. It exposes endpoints\n      for retrieving server status, database and table schema information, region\n      metadata, MVCC key details, DDL job history, and hot region data. Operators\n      and monitoring systems use this API to inspect the internal state of a running\n      TiDB node, integrate with observability tooling, and troubleshoot distributed\n      SQL execution.\n\ncommon:\n  - type: JSON-LD\n    url: json-ld/tidb-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tidb-cluster-schema.json\n  - type: JSONSchema\n    url: json-schema/tidb-data-service-schema.json\n\nmodified: '2026-03-21'\ndescription: >-\n  TiDB is an open-source distributed SQL database that supports Hybrid Transactional\n\
  \  and Analytical Processing workloads, with horizontal scalability, strong consistency,\n  and high availability.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/tidb/refs/heads/main/apis.yml
use_cases: []
---
