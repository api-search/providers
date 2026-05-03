---
api_count: 4
api_specs:
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Platform API
  slug: veeva-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
- filename: veeva-vault-openapi.yml
  format: yaml
  label: Veeva Vault Query Language (VQL) API
  slug: veeva-vault-query-language
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/openapi/veeva-vault-openapi.yml
apis:
- description: Veeva Vault provides life sciences cloud platform APIs for regulatory document management, quality management (QMS), clinical operations, and commercial content management. REST APIs enable document l
  name: Veeva Vault Platform API
  slug: veeva-vault-api
- description: 'The Veeva Vault Java SDK (VAPIL) is an open-source Java-based REST API client for the Vault REST API. Provides type-safe access to all Vault API operations including document management, object CRUD, '
  name: Veeva Vault Java SDK
  slug: veeva-vault-java-sdk
- description: Vault Query Language (VQL) provides SQL-like query capabilities for accessing and retrieving Vault data. Supports SELECT, FROM, WHERE, ORDER BY, relationship queries, and functions for querying docume
  name: Veeva Vault Query Language (VQL) API
  slug: veeva-vault-query-language
- description: 'The Veeva Vault Direct Data API provides high-speed, read-only bulk access to Vault data for integration, analytics, and reporting purposes. Supports bulk export of documents, objects, and attachment '
  name: Veeva Vault Direct Data API
  slug: veeva-vault-direct-data-api
common:
- title: ''
  type: Website
  url: https://www.veeva.com/
- title: ''
  type: Portal
  url: https://developer.veevavault.com/
- title: ''
  type: Documentation
  url: https://developer.veevavault.com/docs
- title: ''
  type: GettingStarted
  url: https://developer.veevavault.com/docs
- title: ''
  type: Authentication
  url: https://developer.veevavault.com/api/25.3/
- title: ''
  type: ChangeLog
  url: https://developer.veevavault.com/rn/25.3/
- title: ''
  type: SDKs
  url: https://developer.veevavault.com/sdk/
- title: ''
  type: Support
  url: https://support.veeva.com/hc/en-us
- title: ''
  type: PrivacyPolicy
  url: https://www.veeva.com/privacy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/veeva
- title: ''
  type: JSONSchema
  url: json-schema/veeva-vault-document-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/veeva-context.jsonld
created: ''
description: Veeva Systems is a leader in cloud-based software for the global life sciences industry, providing solutions to help pharmaceutical and biotechnology companies bring products to market more efficiently.
features: []
image: ''
integrations: []
jsonld:
- class_count: 25
  name: Veeva Context
  property_count: 7
  slug: veeva-context
layout: provider
modified: '2026-03-18'
name: veeva
skills: []
slug: veeva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veeva\nurl: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml\napis:\n  - aid: veeva:veeva-vault-api\n    name: Veeva Vault Platform API\n    tags:\n      - Clinical\n      - Life Sciences\n      - Pharma\n      - QMS\n      - Regulatory\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/\n    baseURL: https://myvault.veevavault.com/api/v25.3\n    properties:\n      - url: https://developer.veevavault.com/\n        type: Portal\n      - url: https://developer.veevavault.com/docs\n        type: Documentation\n      - url: https://developer.veevavault.com/api/25.3/\n        type: Reference\n      - url: https://developer.veevavault.com/api/25.3/\n        type: Authentication\n      - url: https://developer.veevavault.com/rn/25.3/\n        type: ChangeLog\n      - url: https://developer.veevavault.com/docs\n        type: GettingStarted\n      - url: openapi/veeva-vault-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      Veeva Vault provides life sciences cloud platform APIs for regulatory document\n      management, quality management (QMS), clinical operations, and commercial content\n      management. REST APIs enable document lifecycle management, workflow automation,\n      and compliance-validated data exchange.\n\n  - aid: veeva:veeva-vault-java-sdk\n    name: Veeva Vault Java SDK\n    tags:\n      - Java\n      - Life Sciences\n      - Pharma\n      - SDK\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/sdk/\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/sdk/\n        type: Documentation\n      - url: https://github.com/veeva/vault-api-library\n        type: SDKs\n    description: >-\n      The Veeva Vault Java SDK (VAPIL) is an open-source Java-based REST API client\n      for the Vault REST\
  \ API. Provides type-safe access to all Vault API operations\n      including document management, object CRUD, workflow execution, and administrative\n      functions.\n\n  - aid: veeva:veeva-vault-query-language\n    name: Veeva Vault Query Language (VQL) API\n    tags:\n      - Life Sciences\n      - Pharma\n      - Query Language\n      - SQL\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/vql/\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/vql/\n        type: Documentation\n      - url: openapi/veeva-vault-openapi.yml\n        type: OpenAPI\n    description: >-\n      Vault Query Language (VQL) provides SQL-like query capabilities for accessing\n      and retrieving Vault data. Supports SELECT, FROM, WHERE, ORDER BY, relationship\n      queries, and functions for querying documents, objects, users, workflows, and\n      system\
  \ data.\n\n  - aid: veeva:veeva-vault-direct-data-api\n    name: Veeva Vault Direct Data API\n    tags:\n      - Bulk Data\n      - Data Access\n      - Life Sciences\n      - Pharma\n    image: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/image.png\n    humanURL: https://developer.veevavault.com/docs\n    baseURL: https://myvault.veevavault.com/api\n    properties:\n      - url: https://developer.veevavault.com/docs\n        type: Documentation\n    description: >-\n      The Veeva Vault Direct Data API provides high-speed, read-only bulk access to\n      Vault data for integration, analytics, and reporting purposes. Supports bulk\n      export of documents, objects, and attachment field files for up to 500 records.\n\ncommon:\n  - url: https://www.veeva.com/\n    type: Website\n  - url: https://developer.veevavault.com/\n    type: Portal\n  - url: https://developer.veevavault.com/docs\n    type: Documentation\n  - url: https://developer.veevavault.com/docs\n\
  \    type: GettingStarted\n  - url: https://developer.veevavault.com/api/25.3/\n    type: Authentication\n  - url: https://developer.veevavault.com/rn/25.3/\n    type: ChangeLog\n  - url: https://developer.veevavault.com/sdk/\n    type: SDKs\n  - url: https://support.veeva.com/hc/en-us\n    type: Support\n  - url: https://www.veeva.com/privacy/\n    type: PrivacyPolicy\n  - url: https://github.com/veeva\n    type: GitHubOrganization\n  - url: json-schema/veeva-vault-document-schema.json\n    type: JSONSchema\n  - url: json-ld/veeva-context.jsonld\n    type: JSONLDContext\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-03-18'\ndescription: >-\n  Veeva Systems is a leader in cloud-based software for the global life sciences industry,\n  providing solutions to help pharmaceutical and biotechnology companies bring products\n  to market more efficiently.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/veeva/refs/heads/main/apis.yml
use_cases: []
---
