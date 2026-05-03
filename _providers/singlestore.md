---
api_count: 2
api_specs:
- filename: singlestore-data-api-openapi.yml
  format: yaml
  label: SingleStore Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-data-api-openapi.yml
- filename: singlestore-management-api-openapi.yml
  format: yaml
  label: SingleStore Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-management-api-openapi.yml
apis:
- description: The SingleStore Data API enables developers to execute SQL statements against a SingleStore Helios database over standard HTTP connections without requiring a native database driver or MySQL-compatibl
  name: SingleStore Data API
  slug: data-api
- description: The SingleStore Management API is a REST interface for programmatically creating and managing workspace groups and workspaces within SingleStore Helios. It supports provisioning, updating, suspending,
  name: SingleStore Management API
  slug: management-api
capabilities:
- description: Unified database operations workflow combining SQL execution via the SingleStore Data API with workspace management via the Management API. Used by data engineers, application developers, and DevOps t
  name: SingleStore Database Operations
  slug: database-operations
common:
- title: ''
  type: Website
  url: https://www.singlestore.com/
- title: ''
  type: DeveloperPortal
  url: https://docs.singlestore.com/
- title: ''
  type: Documentation
  url: https://docs.singlestore.com/cloud/
- title: ''
  type: Pricing
  url: https://www.singlestore.com/pricing/
- title: ''
  type: Blog
  url: https://www.singlestore.com/blog/
- title: ''
  type: GitHubOrg
  url: https://github.com/singlestore-labs
- title: ''
  type: SignUp
  url: https://www.singlestore.com/cloud-trial/
- title: ''
  type: TermsOfService
  url: https://www.singlestore.com/cloud-terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.singlestore.com/privacy-policy/
- title: ''
  type: Support
  url: https://support.singlestore.com
created: '2025-01-01'
description: SingleStore is a cloud-native distributed SQL database designed for real-time analytics and mixed workloads. It offers a management API for provisioning and managing cloud workspaces, and a data API for executing SQL statements over HTTP without requiring native database drivers. SingleStore Helios is the fully managed cloud service providing serverless database capabilities with elastic scaling.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Singlestore Context
  property_count: 9
  slug: singlestore-context
layout: provider
modified: '2026-05-02'
name: SingleStore
rules:
- name: SingleStore API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: singlestore-rules
skills: []
slug: singlestore
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: singlestore\nname: SingleStore\ndescription: >-\n  SingleStore is a cloud-native distributed SQL database designed for\n  real-time analytics and mixed workloads. It offers a management API for\n  provisioning and managing cloud workspaces, and a data API for executing\n  SQL statements over HTTP without requiring native database drivers.\n  SingleStore Helios is the fully managed cloud service providing serverless\n  database capabilities with elastic scaling.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Database\n  - SQL\n  - Analytics\n  - Cloud\n  - Distributed SQL\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: singlestore:data-api\n    name: SingleStore Data API\n    description: >-\n      The SingleStore Data API enables\
  \ developers to execute SQL statements\n      against a SingleStore Helios database over standard HTTP connections\n      without requiring a native database driver or MySQL-compatible client.\n      It supports all SQL statements via /api/v2/exec, and returns query result\n      sets via /api/v2/query/rows and /api/v2/query/tuples. Authentication is\n      handled using HTTP Basic or Bearer Authentication over HTTPS.\n    humanURL: https://docs.singlestore.com/cloud/reference/data-api/\n    baseURL: https://{workspaceHost}\n    tags:\n      - SQL\n      - Database\n      - Query\n      - HTTP SQL\n    properties:\n      - type: Documentation\n        url: https://docs.singlestore.com/cloud/reference/data-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-data-api-openapi.yml\n\n  - aid: singlestore:management-api\n    name: SingleStore Management API\n    description: >-\n      The SingleStore\
  \ Management API is a REST interface for programmatically\n      creating and managing workspace groups and workspaces within SingleStore\n      Helios. It supports provisioning, updating, suspending, resuming, and\n      deleting workspaces, as well as managing private connections, regions,\n      organizations, jobs, files, secrets, and teams.\n    humanURL: https://docs.singlestore.com/cloud/reference/management-api/\n    baseURL: https://api.singlestore.com/v1\n    tags:\n      - Management\n      - Workspaces\n      - Provisioning\n      - Database\n    properties:\n      - type: Documentation\n        url: https://docs.singlestore.com/cloud/reference/management-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-management-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.singlestore.com/\n  - type: DeveloperPortal\n    url: https://docs.singlestore.com/\n  - type:\
  \ Documentation\n    url: https://docs.singlestore.com/cloud/\n  - type: Pricing\n    url: https://www.singlestore.com/pricing/\n  - type: Blog\n    url: https://www.singlestore.com/blog/\n  - type: GitHubOrg\n    url: https://github.com/singlestore-labs\n  - type: SignUp\n    url: https://www.singlestore.com/cloud-trial/\n  - type: TermsOfService\n    url: https://www.singlestore.com/cloud-terms-and-conditions/\n  - type: PrivacyPolicy\n    url: https://www.singlestore.com/privacy-policy/\n  - type: Support\n    url: https://support.singlestore.com\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml
tags:
- Database
- SQL
- Analytics
- Cloud
- Distributed SQL
url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml
use_cases: []
---
