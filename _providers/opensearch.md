---
api_count: 2
api_specs:
- filename: opensearch-security-openapi.yml
  format: yaml
  label: OpenSearch Security Plugin REST API
  slug: opensearch-security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/openapi/opensearch-security-openapi.yml
apis:
- description: The Security plugin REST API lets administrators programmatically create and manage internal users, roles, role mappings, action groups, tenants, security configuration, audit log configuration, allow
  name: OpenSearch Security Plugin REST API
  slug: opensearch-security-api
- description: The core OpenSearch REST API for indexing documents, performing search queries (full text, vector, hybrid), aggregations, and managing indices, mappings, templates, aliases, and snapshots.
  name: OpenSearch Search and Indexing REST API
  slug: opensearch-search-api
common:
- title: ''
  type: Website
  url: https://opensearch.org/
- title: ''
  type: Portal
  url: https://docs.opensearch.org/
- title: ''
  type: Documentation
  url: https://docs.opensearch.org/latest/api-reference/
- title: ''
  type: GettingStarted
  url: https://docs.opensearch.org/latest/getting-started/
- title: ''
  type: Community
  url: https://opensearch.org/community/
- title: ''
  type: Forum
  url: https://forum.opensearch.org/
- title: ''
  type: Blog
  url: https://opensearch.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/opensearch-project
- title: ''
  type: GitHubRepository
  url: https://github.com/opensearch-project/security
- title: ''
  type: GitHubRepository
  url: https://github.com/opensearch-project/OpenSearch
- title: ''
  type: Download
  url: https://opensearch.org/downloads/
- title: ''
  type: License
  url: https://opensearch.org/license.html
- title: ''
  type: Security
  url: https://opensearch.org/security
created: '2025-01-08'
description: OpenSearch is the open source, community-driven search, analytics, and observability suite (forked from Elasticsearch and Kibana) maintained under the Linux Foundation's OpenSearch Software Foundation. The platform exposes REST APIs across the search engine, the OpenSearch Dashboards UI, and a set of plugins. The Security plugin REST API lets administrators programmatically create and manage internal users, roles, role mappings, action groups, tenants, security configuration, audit log configuration, and SSL certificates.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Opensearch Context
  property_count: 0
  slug: opensearch-context
layout: provider
modified: '2026-04-28'
name: OpenSearch
skills: []
slug: opensearch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: opensearch\nname: OpenSearch\ndescription: >-\n  OpenSearch is the open source, community-driven search, analytics, and\n  observability suite (forked from Elasticsearch and Kibana) maintained under\n  the Linux Foundation's OpenSearch Software Foundation. The platform exposes\n  REST APIs across the search engine, the OpenSearch Dashboards UI, and a set\n  of plugins. The Security plugin REST API lets administrators programmatically\n  create and manage internal users, roles, role mappings, action groups,\n  tenants, security configuration, audit log configuration, and SSL\n  certificates.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Search\n  - Analytics\n  - Observability\n  - Open Source\n  - Security\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: opensearch:opensearch-security-api\n    name: OpenSearch Security Plugin REST API\n    description: >-\n      The Security plugin REST API lets administrators programmatically\n      create and manage internal users, roles, role mappings, action groups,\n      tenants, security configuration, audit log configuration, allowlists,\n      node DN entries, and SSL certificates. Endpoints are exposed under\n      /_plugins/_security/api on the OpenSearch cluster and require\n      authentication.\n    humanURL: https://docs.opensearch.org/latest/security/access-control/api/\n    baseURL: https://{cluster-host}:9200\n    tags:\n      - Security\n      - Access Control\n      - Roles\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://docs.opensearch.org/latest/security/access-control/api/\n      - type: Documentation\n        url: https://docs.opensearch.org/latest/security/access-control/index/\n      - type: OpenAPI\n      \
  \  url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/openapi/opensearch-security-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/json-schema/opensearch-role-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/json-ld/opensearch-context.jsonld\n  - aid: opensearch:opensearch-search-api\n    name: OpenSearch Search and Indexing REST API\n    description: >-\n      The core OpenSearch REST API for indexing documents, performing search\n      queries (full text, vector, hybrid), aggregations, and managing\n      indices, mappings, templates, aliases, and snapshots.\n    humanURL: https://docs.opensearch.org/latest/api-reference/\n    baseURL: https://{cluster-host}:9200\n    tags:\n      - Search\n      - Indexing\n      - Vector Search\n      - Aggregations\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.opensearch.org/latest/api-reference/\n      - type: Documentation\n        url: https://docs.opensearch.org/latest/search-plugins/\n      - type: Reference\n        url: https://docs.opensearch.org/latest/api-reference/search/\ncommon:\n  - url: https://opensearch.org/\n    name: OpenSearch\n    type: Website\n  - url: https://docs.opensearch.org/\n    name: Documentation Portal\n    type: Portal\n  - url: https://docs.opensearch.org/latest/api-reference/\n    name: API Reference\n    type: Documentation\n  - url: https://docs.opensearch.org/latest/getting-started/\n    name: Getting Started\n    type: GettingStarted\n  - url: https://opensearch.org/community/\n    name: Community\n    type: Community\n  - url: https://forum.opensearch.org/\n    name: Discussion Forum\n    type: Forum\n  - url: https://opensearch.org/blog/\n    name: Blog\n    type: Blog\n  - url: https://github.com/opensearch-project\n    name: GitHub Organization\n    type: GitHubOrganization\n\
  \  - url: https://github.com/opensearch-project/security\n    name: Security Plugin Source\n    type: GitHubRepository\n  - url: https://github.com/opensearch-project/OpenSearch\n    name: OpenSearch Core Source\n    type: GitHubRepository\n  - url: https://opensearch.org/downloads/\n    name: Downloads\n    type: Download\n  - url: https://opensearch.org/license.html\n    name: License (Apache 2.0)\n    type: License\n  - url: https://opensearch.org/security\n    name: Security Advisories\n    type: Security\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/apis.yml
tags:
- Search
- Analytics
- Observability
- Open Source
- Security
url: https://raw.githubusercontent.com/api-evangelist/opensearch/refs/heads/main/apis.yml
use_cases: []
---
