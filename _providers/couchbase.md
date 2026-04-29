---
api_count: 12
api_specs:
- filename: couchbase-server-rest-api-openapi.yml
  format: yaml
  label: Couchbase Server REST API
  slug: couchbase-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-server-rest-api-openapi.yml
- filename: couchbase-query-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Query Service REST API
  slug: couchbase-query-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-query-service-rest-api-openapi.yml
- filename: couchbase-analytics-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Analytics Service REST API
  slug: couchbase-analytics-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-analytics-service-rest-api-openapi.yml
- filename: couchbase-search-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Search Service REST API
  slug: couchbase-search-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-search-service-rest-api-openapi.yml
- filename: couchbase-eventing-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Eventing Service REST API
  slug: couchbase-eventing-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-eventing-service-rest-api-openapi.yml
- filename: couchbase-backup-service-rest-api-openapi.yml
  format: yaml
  label: Couchbase Backup Service REST API
  slug: couchbase-backup-service-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-backup-service-rest-api-openapi.yml
- filename: couchbase-xdcr-rest-api-openapi.yml
  format: yaml
  label: Couchbase XDCR REST API
  slug: couchbase-xdcr-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-xdcr-rest-api-openapi.yml
- filename: couchbase-capella-management-api-openapi.yml
  format: yaml
  label: Couchbase Capella Management API
  slug: couchbase-capella-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-management-api-openapi.yml
- filename: couchbase-capella-app-services-public-api-openapi.yml
  format: yaml
  label: Couchbase Capella App Services Public API
  slug: couchbase-capella-app-services-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-app-services-public-api-openapi.yml
- filename: couchbase-capella-app-services-admin-api-openapi.yml
  format: yaml
  label: Couchbase Capella App Services Admin API
  slug: couchbase-capella-app-services-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-capella-app-services-admin-api-openapi.yml
- filename: couchbase-sync-gateway-public-rest-api-openapi.yml
  format: yaml
  label: Couchbase Sync Gateway Public REST API
  slug: couchbase-sync-gateway-public-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-sync-gateway-public-rest-api-openapi.yml
- filename: couchbase-sync-gateway-admin-rest-api-openapi.yml
  format: yaml
  label: Couchbase Sync Gateway Admin REST API
  slug: couchbase-sync-gateway-admin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/openapi/couchbase-sync-gateway-admin-rest-api-openapi.yml
apis:
- description: The Couchbase Server REST API provides programmatic access to manage and configure Couchbase Server clusters. It includes endpoints for cluster management, bucket operations, node administration, secu
  name: Couchbase Server REST API
  slug: couchbase-server-rest-api
- description: The Couchbase Query Service REST API enables developers to execute SQL++ (formerly N1QL) queries against Couchbase Server and manage query service settings. It supports ad-hoc queries, prepared statem
  name: Couchbase Query Service REST API
  slug: couchbase-query-service-rest-api
- description: The Couchbase Analytics Service REST API provides access to the Analytics service for running complex analytical queries on operational data without impacting performance of key-value operations. It s
  name: Couchbase Analytics Service REST API
  slug: couchbase-analytics-service-rest-api
- description: The Couchbase Search Service REST API allows developers to create, manage, and query Full Text Indexes on Couchbase Server. It supports full-text search queries with features like fuzzy matching, face
  name: Couchbase Search Service REST API
  slug: couchbase-search-service-rest-api
- description: The Couchbase Eventing Service REST API provides methods for deploying and managing Eventing Functions that respond to data changes in real time. Eventing Functions allow developers to write server-si
  name: Couchbase Eventing Service REST API
  slug: couchbase-eventing-service-rest-api
- description: The Couchbase Backup Service REST API supports management of the Backup Service for Couchbase Server, providing endpoints for cluster configuration, repository management, backup plans, task schedulin
  name: Couchbase Backup Service REST API
  slug: couchbase-backup-service-rest-api
- description: The Couchbase XDCR (Cross Data Center Replication) REST API enables configuration and management of data replication between Couchbase clusters across different data centers. It provides endpoints for
  name: Couchbase XDCR REST API
  slug: couchbase-xdcr-rest-api
- description: The Couchbase Capella Management API is a REST API for provisioning, deploying, and configuring Couchbase Capella database-as-a-service deployments across AWS, Azure, and Google Cloud. It enables prog
  name: Couchbase Capella Management API
  slug: couchbase-capella-management-api
- description: The Couchbase Capella App Services Public API provides REST endpoints for mobile and edge application data synchronization with Couchbase Capella. It enables developers to manage document access, hand
  name: Couchbase Capella App Services Public API
  slug: couchbase-capella-app-services-public-api
- description: The Couchbase Capella App Services Admin API provides administrative REST endpoints for managing Sync Gateway configurations within Couchbase Capella. It enables administrators to manage databases, us
  name: Couchbase Capella App Services Admin API
  slug: couchbase-capella-app-services-admin-api
- description: The Couchbase Sync Gateway Public REST API provides endpoints for mobile and edge clients to synchronize data with Couchbase Server through the Sync Gateway middleware. It supports document CRUD opera
  name: Couchbase Sync Gateway Public REST API
  slug: couchbase-sync-gateway-public-rest-api
- description: The Couchbase Sync Gateway Admin REST API provides administrative endpoints for configuring and managing Sync Gateway instances. It supports database management, user and role administration, sync fun
  name: Couchbase Sync Gateway Admin REST API
  slug: couchbase-sync-gateway-admin-rest-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.couchbase.com/
- title: ''
  type: Documentation
  url: https://docs.couchbase.com/
- title: ''
  type: Capella
  url: https://www.couchbase.com/products/capella/
- title: ''
  type: Server
  url: https://www.couchbase.com/products/server/
- title: ''
  type: Mobile
  url: https://www.couchbase.com/products/mobile/
- title: ''
  type: Login
  url: https://cloud.couchbase.com/sign-in
- title: ''
  type: Pricing
  url: https://www.couchbase.com/pricing/
- title: ''
  type: Blog
  url: https://www.couchbase.com/blog/
- title: ''
  type: Forums
  url: https://www.couchbase.com/forums/
- title: ''
  type: Support
  url: https://support.couchbase.com/
- title: ''
  type: Status
  url: https://status.couchbase.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/couchbase
- title: ''
  type: ChangeLog
  url: https://docs.couchbase.com/server/current/release-notes/relnotes.html
- title: ''
  type: PrivacyPolicy
  url: https://www.couchbase.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.couchbase.com/terms-of-use/
- title: ''
  type: JSONLD
  url: json-ld/couchbase-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/couchbase-document-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/couchbase-bucket-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/couchbase-cluster-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/couchbase-vocabulary.yml
created: '2025-03-01'
description: Couchbase is a distributed, document-oriented NoSQL cloud database platform that combines the flexibility of JSON, the power of SQL++ querying, and the performance of an in-memory key-value store. The Couchbase product line includes Couchbase Server (self-managed), Couchbase Capella (fully managed database-as-a-service across AWS, Azure, and Google Cloud), Sync Gateway and App Services for mobile and edge synchronization, and Couchbase Lite embedded databases. Couchbase exposes a comprehensive set of REST APIs covering cluster administration, SQL++ query execution, full-text and vector search, analytics, eventing, backup, cross data center replication, and Capella management.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Couchbase Context
  property_count: 14
  slug: couchbase-context
layout: provider
modified: '2026-04-28'
name: Couchbase
rules:
- name: Couchbase API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: couchbase-capella-management-rules
- name: Couchbase API Rules
  rule_count: 4
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 1
  slug: couchbase-query-rules
- name: Couchbase API Rules
  rule_count: 4
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 1
  slug: couchbase-search-rules
- name: Couchbase API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 1
  slug: couchbase-server-rules
- name: Couchbase API Rules
  rule_count: 4
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 1
  slug: couchbase-sync-gateway-rules
skills: []
slug: couchbase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: couchbase\nname: Couchbase\nx-type: company\ndescription: >-\n  Couchbase is a distributed, document-oriented NoSQL cloud database platform\n  that combines the flexibility of JSON, the power of SQL++ querying, and the\n  performance of an in-memory key-value store. The Couchbase product line\n  includes Couchbase Server (self-managed), Couchbase Capella (fully managed\n  database-as-a-service across AWS, Azure, and Google Cloud), Sync Gateway\n  and App Services for mobile and edge synchronization, and Couchbase Lite\n  embedded databases. Couchbase exposes a comprehensive set of REST APIs\n  covering cluster administration, SQL++ query execution, full-text and\n  vector search, analytics, eventing, backup, cross data center replication,\n  and Capella management.\nurl: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Public\nposition:\
  \ Provider\ntags:\n  - Analytics\n  - App Services\n  - Backup\n  - Capella\n  - Cloud\n  - Database\n  - DBaaS\n  - Eventing\n  - Full-Text Search\n  - Gateway\n  - JSON\n  - Mobile\n  - NoSQL\n  - Replication\n  - SQL++\n  - Sync\n  - Vector Search\n  - XDCR\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: couchbase:couchbase-server-rest-api\n    name: Couchbase Server REST API\n    description: >-\n      The Couchbase Server REST API provides programmatic access to manage and\n      configure Couchbase Server clusters. It includes endpoints for cluster\n      management, bucket operations, node administration, security settings,\n      and server configuration. The API enables automation of deployment,\n      monitoring, and maintenance tasks for Couchbase Server instances across\n      distributed environments.\n    humanURL: https://docs.couchbase.com/server/current/rest-api/rest-intro.html\n    baseURL: https://localhost:8091\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.couchbase.com/server/current/rest-api/rest-intro.html\n      - type: OpenAPI\n        url: openapi/couchbase-server-rest-api-openapi.yml\n      - type: Rules\n        url: rules/couchbase-server-rules.yml\n      - type: Capabilities\n        url: capabilities/couchbase-server-capabilities.yml\n    tags:\n      - Administration\n      - Buckets\n      - Clusters\n      - Database\n      - NoSQL\n  - aid: couchbase:couchbase-query-service-rest-api\n    name: Couchbase Query Service REST API\n    description: >-\n      The Couchbase Query Service REST API enables developers to execute SQL++\n      (formerly N1QL) queries against Couchbase Server and manage query service\n      settings. It supports ad-hoc queries, prepared statements, and\n      request-level parameter configuration. The API provides endpoints for\n      query execution, monitoring active requests, and managing query service\n      configuration across cluster nodes.\n\
  \    humanURL: https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html\n    baseURL: https://localhost:8093\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/n1ql/n1ql-rest-api/index.html\n      - type: OpenAPI\n        url: openapi/couchbase-query-service-rest-api-openapi.yml\n      - type: Rules\n        url: rules/couchbase-query-rules.yml\n      - type: Capabilities\n        url: capabilities/couchbase-query-capabilities.yml\n    tags:\n      - Database\n      - N1QL\n      - NoSQL\n      - Query\n      - SQL++\n  - aid: couchbase:couchbase-analytics-service-rest-api\n    name: Couchbase Analytics Service REST API\n    description: >-\n      The Couchbase Analytics Service REST API provides access to the Analytics\n      service for running complex analytical queries on operational data without\n      impacting performance of key-value operations. It supports SQL++ queries\n      for analytics, management of links\
  \ to external data sources, and\n      configuration of user-defined libraries. The service enables real-time\n      analytics on JSON data alongside transactional workloads.\n    humanURL: https://docs.couchbase.com/server/current/analytics/rest-analytics.html\n    baseURL: https://localhost:8095\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/analytics/rest-analytics.html\n      - type: OpenAPI\n        url: openapi/couchbase-analytics-service-rest-api-openapi.yml\n    tags:\n      - Analytics\n      - Database\n      - NoSQL\n      - SQL++\n  - aid: couchbase:couchbase-search-service-rest-api\n    name: Couchbase Search Service REST API\n    description: >-\n      The Couchbase Search Service REST API allows developers to create, manage,\n      and query Full Text Indexes on Couchbase Server. It supports full-text\n      search queries with features like fuzzy matching, faceted search,\n      highlighting, and geospatial queries.\
  \ The API provides endpoints for\n      index definition, index management, and executing search queries across\n      JSON documents stored in Couchbase buckets.\n    humanURL: https://docs.couchbase.com/server/current/rest-api/rest-fts.html\n    baseURL: https://localhost:8094\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/rest-api/rest-fts.html\n      - type: OpenAPI\n        url: openapi/couchbase-search-service-rest-api-openapi.yml\n      - type: Rules\n        url: rules/couchbase-search-rules.yml\n      - type: Capabilities\n        url: capabilities/couchbase-search-capabilities.yml\n    tags:\n      - Database\n      - Full-Text Search\n      - Indexing\n      - NoSQL\n      - Vector Search\n  - aid: couchbase:couchbase-eventing-service-rest-api\n    name: Couchbase Eventing Service REST API\n    description: >-\n      The Couchbase Eventing Service REST API provides methods for deploying and\n      managing Eventing Functions\
  \ that respond to data changes in real time.\n      Eventing Functions allow developers to write server-side JavaScript logic\n      triggered by document mutations, timers, or external events.\n    humanURL: https://docs.couchbase.com/server/current/eventing/eventing-api.html\n    baseURL: https://localhost:8096\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/eventing/eventing-api.html\n      - type: OpenAPI\n        url: openapi/couchbase-eventing-service-rest-api-openapi.yml\n    tags:\n      - Database\n      - Eventing\n      - NoSQL\n      - Serverless Functions\n  - aid: couchbase:couchbase-backup-service-rest-api\n    name: Couchbase Backup Service REST API\n    description: >-\n      The Couchbase Backup Service REST API supports management of the Backup\n      Service for Couchbase Server, providing endpoints for cluster\n      configuration, repository management, backup plans, task scheduling, and\n      data operations.\n\
  \    humanURL: https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html\n    baseURL: https://localhost:8097\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/rest-api/backup-rest-api.html\n      - type: OpenAPI\n        url: openapi/couchbase-backup-service-rest-api-openapi.yml\n    tags:\n      - Backup\n      - Database\n      - Disaster Recovery\n      - NoSQL\n  - aid: couchbase:couchbase-xdcr-rest-api\n    name: Couchbase XDCR REST API\n    description: >-\n      The Couchbase XDCR (Cross Data Center Replication) REST API enables\n      configuration and management of data replication between Couchbase\n      clusters across different data centers. It provides endpoints for creating\n      replication references, configuring replication streams, monitoring\n      replication statistics, and managing replication settings.\n    humanURL: https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html\n    baseURL:\
  \ https://localhost:8091\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/server/current/rest-api/rest-xdcr-intro.html\n      - type: OpenAPI\n        url: openapi/couchbase-xdcr-rest-api-openapi.yml\n    tags:\n      - Cross Data Center\n      - Database\n      - NoSQL\n      - Replication\n  - aid: couchbase:couchbase-capella-management-api\n    name: Couchbase Capella Management API\n    description: >-\n      The Couchbase Capella Management API is a REST API for provisioning,\n      deploying, and configuring Couchbase Capella database-as-a-service\n      deployments across AWS, Azure, and Google Cloud. It enables programmatic\n      management of clusters, buckets, users, and organizations using API key\n      authentication.\n    humanURL: https://docs.couchbase.com/cloud/management-api-reference/index.html\n    baseURL: https://cloudapi.cloud.couchbase.com\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/cloud/management-api-reference/index.html\n\
  \      - type: OpenAPI\n        url: openapi/couchbase-capella-management-api-openapi.yml\n      - type: Rules\n        url: rules/couchbase-capella-management-rules.yml\n      - type: Capabilities\n        url: capabilities/couchbase-capella-management-capabilities.yml\n    tags:\n      - Capella\n      - Cloud\n      - Database\n      - DBaaS\n      - Management\n      - NoSQL\n  - aid: couchbase:couchbase-capella-app-services-public-api\n    name: Couchbase Capella App Services Public API\n    description: >-\n      The Couchbase Capella App Services Public API provides REST endpoints for\n      mobile and edge application data synchronization with Couchbase Capella.\n      It enables developers to manage document access, handle user\n      authentication, and synchronize data between mobile devices and the cloud\n      database.\n    humanURL: https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/cloud/app-services/references/rest_api_public.html\n\
  \      - type: OpenAPI\n        url: openapi/couchbase-capella-app-services-public-api-openapi.yml\n    tags:\n      - App Services\n      - Capella\n      - Cloud\n      - Mobile\n      - NoSQL\n      - Sync\n  - aid: couchbase:couchbase-capella-app-services-admin-api\n    name: Couchbase Capella App Services Admin API\n    description: >-\n      The Couchbase Capella App Services Admin API provides administrative REST\n      endpoints for managing Sync Gateway configurations within Couchbase\n      Capella. It enables administrators to manage databases, users, roles,\n      sync functions, and replication settings for mobile data synchronization.\n    humanURL: https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/cloud/app-services/references/rest_api_admin.html\n      - type: OpenAPI\n        url: openapi/couchbase-capella-app-services-admin-api-openapi.yml\n    tags:\n   \
  \   - Administration\n      - App Services\n      - Capella\n      - Cloud\n      - Mobile\n      - NoSQL\n  - aid: couchbase:couchbase-sync-gateway-public-rest-api\n    name: Couchbase Sync Gateway Public REST API\n    description: >-\n      The Couchbase Sync Gateway Public REST API provides endpoints for mobile\n      and edge clients to synchronize data with Couchbase Server through the\n      Sync Gateway middleware. It supports document CRUD operations, changes\n      feeds for real-time data synchronization, and user authentication.\n    humanURL: https://docs.couchbase.com/sync-gateway/current/rest-api.html\n    baseURL: https://localhost:4984\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/sync-gateway/current/rest-api.html\n      - type: OpenAPI\n        url: openapi/couchbase-sync-gateway-public-rest-api-openapi.yml\n      - type: Rules\n        url: rules/couchbase-sync-gateway-rules.yml\n      - type: Capabilities\n        url: capabilities/couchbase-sync-gateway-capabilities.yml\n\
  \    tags:\n      - Database\n      - Gateway\n      - Mobile\n      - NoSQL\n      - Sync\n  - aid: couchbase:couchbase-sync-gateway-admin-rest-api\n    name: Couchbase Sync Gateway Admin REST API\n    description: >-\n      The Couchbase Sync Gateway Admin REST API provides administrative\n      endpoints for configuring and managing Sync Gateway instances. It\n      supports database management, user and role administration, sync function\n      configuration, and replication setup.\n    humanURL: https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html\n    baseURL: https://localhost:4985\n    properties:\n      - type: Documentation\n        url: https://docs.couchbase.com/sync-gateway/current/rest-api-admin.html\n      - type: OpenAPI\n        url: openapi/couchbase-sync-gateway-admin-rest-api-openapi.yml\n    tags:\n      - Administration\n      - Database\n      - Mobile\n      - NoSQL\n      - Sync\ncommon:\n  - type: Website\n    url: https://www.couchbase.com/\n \
  \ - type: Documentation\n    url: https://docs.couchbase.com/\n  - type: Capella\n    url: https://www.couchbase.com/products/capella/\n  - type: Server\n    url: https://www.couchbase.com/products/server/\n  - type: Mobile\n    url: https://www.couchbase.com/products/mobile/\n  - type: Login\n    url: https://cloud.couchbase.com/sign-in\n  - type: Pricing\n    url: https://www.couchbase.com/pricing/\n  - type: Blog\n    url: https://www.couchbase.com/blog/\n  - type: Forums\n    url: https://www.couchbase.com/forums/\n  - type: Support\n    url: https://support.couchbase.com/\n  - type: Status\n    url: https://status.couchbase.com/\n  - type: GitHubOrganization\n    url: https://github.com/couchbase\n  - type: ChangeLog\n    url: https://docs.couchbase.com/server/current/release-notes/relnotes.html\n  - type: PrivacyPolicy\n    url: https://www.couchbase.com/privacy-policy/\n  - type: TermsOfService\n    url: https://www.couchbase.com/terms-of-use/\n  - type: JSONLD\n    url: json-ld/couchbase-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/couchbase-document-schema.json\n  - type: JSONSchema\n    url: json-schema/couchbase-bucket-schema.json\n  - type: JSONSchema\n    url: json-schema/couchbase-cluster-schema.json\n  - type: Vocabulary\n    url: vocabulary/couchbase-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml
tags:
- Analytics
- App Services
- Backup
- Capella
- Cloud
- Database
- DBaaS
- Eventing
- Full-Text Search
- Gateway
- JSON
- Mobile
- NoSQL
- Replication
- SQL++
- Sync
- Vector Search
- XDCR
url: https://raw.githubusercontent.com/api-evangelist/couchbase/refs/heads/main/apis.yml
use_cases: []
---
