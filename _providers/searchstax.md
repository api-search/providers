---
api_count: 2
api_specs:
- filename: searchstax-provisioning-openapi.yml
  format: yaml
  label: SearchStax Provisioning API
  slug: searchstax-provisioning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/openapi/searchstax-provisioning-openapi.yml
apis:
- description: The SearchStax Provisioning API is a REST interface for creating and managing Solr deployments in the SearchStax Managed Search cloud. It supports deployment lifecycle management, backup and restore o
  name: SearchStax Provisioning API
  slug: searchstax-provisioning-api
- description: The SearchStax Site Search API returns JSON search results from a SearchStax Studio Site Search application. It provides real-time search via the /emselect endpoint, supporting faceted search, auto-su
  name: SearchStax Site Search API
  slug: searchstax-site-search-api
capabilities:
- description: Unified capability for managing SearchStax Solr search infrastructure including deployment lifecycle, health monitoring, backup and restore operations, and usage reporting. Designed for DevOps and pla
  name: SearchStax Search Infrastructure Management
  slug: search-infrastructure-management
common:
- title: ''
  type: Website
  url: https://www.searchstax.com
- title: ''
  type: Documentation
  url: https://www.searchstax.com/docs/hc/searchstax-api-library/
- title: ''
  type: Documentation
  url: https://www.searchstax.com/docs/searchstax-cloud-apis-overview/
- title: ''
  type: GitHubOrganization
  url: https://github.com/searchstax
- title: ''
  type: Documentation
  url: https://www.searchstax.com/docs/searchstax-cloud-deployment-api/
- title: ''
  type: Documentation
  url: https://www.searchstax.com/docs/searchstax-cloud-backup-restore-api/
- title: ''
  type: Documentation
  url: https://www.searchstax.com/docs/searchstax-cloud-authentication-api/
- title: ''
  type: JSONSchema
  url: json-schema/searchstax-deployment-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/searchstax-deployment-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/searchstax-context.jsonld
- title: ''
  type: Example
  url: examples/searchstax-list-deployments-example.json
- title: ''
  type: SpectralRuleset
  url: rules/searchstax-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/search-infrastructure-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/searchstax-vocabulary.yml
created: '2026-05-02'
description: SearchStax is a managed Solr search infrastructure company that provides cloud-hosted Apache Solr deployments and a Site Search platform. SearchStax eliminates the complexity of running and scaling Solr by offering fully managed dedicated and serverless deployments on AWS, Azure, and Google Cloud. The platform exposes a comprehensive REST Provisioning API for managing deployments, backup and restore, authentication, webhooks, and infrastructure configuration, along with a Site Search API for delivering search results from SearchStax Studio applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Searchstax Context
  property_count: 1
  slug: searchstax-context
layout: provider
modified: '2026-05-02'
name: SearchStax
rules:
- name: SearchStax API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: searchstax-rules
skills: []
slug: searchstax
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: searchstax\nurl: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml\napis:\n  - aid: searchstax:searchstax-provisioning-api\n    name: SearchStax Provisioning API\n    tags:\n      - Provisioning\n      - Solr\n      - Deployments\n      - Infrastructure\n    humanURL: https://www.searchstax.com/docs/searchstax-cloud-apis-overview/\n    baseURL: https://app.searchstax.com/api/rest/v2\n    properties:\n      - url: openapi/searchstax-provisioning-openapi.yml\n        type: OpenAPI\n      - url: https://www.searchstax.com/docs/searchstax-cloud-apis-overview/\n        type: Documentation\n      - url: https://www.searchstax.com/docs/searchstax-cloud-deployment-api/\n        type: Documentation\n    description: >-\n      The SearchStax Provisioning API is a REST interface for creating and managing\n      Solr deployments in the SearchStax Managed Search cloud. It supports deployment\n      lifecycle management, backup and restore operations,\
  \ node management, plan listing,\n      usage reporting, authentication configuration, webhook management, and ZooKeeper\n      configuration. Token-based authentication is used for most operations, with API\n      key authentication available for a subset of deployment management functions.\n\n  - aid: searchstax:searchstax-site-search-api\n    name: SearchStax Site Search API\n    tags:\n      - Search\n      - Site Search\n      - Studio\n      - Full-Text Search\n    humanURL: https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/\n    baseURL: https://search.searchstax.com\n    properties:\n      - url: https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/\n        type: Documentation\n    description: >-\n      The SearchStax Site Search API returns JSON search results from a SearchStax\n      Studio Site Search application. It provides real-time search via the /emselect\n      endpoint, supporting faceted search, auto-suggest, popular searches,\
  \ related\n      searches, and search analytics tracking.\n\nname: SearchStax\ntags:\n  - Search\n  - Solr\n  - Managed Search\n  - Search Infrastructure\n  - Full-Text Search\n  - Site Search\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  SearchStax is a managed Solr search infrastructure company that provides cloud-hosted\n  Apache Solr deployments and a Site Search platform. SearchStax eliminates the complexity\n  of running and scaling Solr by offering fully managed dedicated and serverless deployments\n  on AWS, Azure, and Google Cloud. The platform exposes a comprehensive REST Provisioning\n  API for managing deployments, backup and restore, authentication, webhooks, and infrastructure\n  configuration, along with a Site Search API for delivering search results from SearchStax\n  Studio applications.\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Website\n    url: https://www.searchstax.com\n    type: Website\n  - name: API Library Overview\n    url: https://www.searchstax.com/docs/hc/searchstax-api-library/\n    type: Documentation\n  - name: Managed Search APIs Overview\n    url: https://www.searchstax.com/docs/searchstax-cloud-apis-overview/\n    type: Documentation\n  - name: GitHub Organization\n    url: https://github.com/searchstax\n    type: GitHubOrganization\n  - name: Deployment API Documentation\n    url: https://www.searchstax.com/docs/searchstax-cloud-deployment-api/\n    type: Documentation\n  - name: Backup Restore API\n    url: https://www.searchstax.com/docs/searchstax-cloud-backup-restore-api/\n    type: Documentation\n  - name: Authentication API\n    url: https://www.searchstax.com/docs/searchstax-cloud-authentication-api/\n    type: Documentation\n  - url: json-schema/searchstax-deployment-schema.json\n    type: JSONSchema\n\
  \  - url: json-structure/searchstax-deployment-structure.json\n    type: JSONStructure\n  - url: json-ld/searchstax-context.jsonld\n    type: JSONLDContext\n  - url: examples/searchstax-list-deployments-example.json\n    type: Example\n  - url: rules/searchstax-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/search-infrastructure-management.yaml\n    type: NaftikoCapability\n  - url: vocabulary/searchstax-vocabulary.yml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml
tags:
- Search
- Solr
- Managed Search
- Search Infrastructure
- Full-Text Search
- Site Search
url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml
use_cases: []
---
