---
api_count: 6
api_specs:
- filename: relativityone-legal-hold-openapi.yml
  format: yaml
  label: Legal Hold API
  slug: legal-hold-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/openapi/relativityone-legal-hold-openapi.yml
apis:
- description: The Legal Hold API enables matter and project management integration with external systems like matter management platforms and HR systems. It provides endpoints for custodian management, preservation
  name: Legal Hold API
  slug: legal-hold-api
- description: The Object Manager API provides CRUD operations for documents and Relativity Dynamic Objects (RDOs). It supports bulk read, create, update, and delete operations with filtering and search capabilities
  name: Object Manager API
  slug: object-manager-api
- description: The Workspace Manager API provides CRUD operations for Relativity workspaces, including workspace creation, configuration, application installation, and environment management.
  name: Workspace Manager API
  slug: workspace-manager-api
- description: APIs for search and analytics operations in RelativityOne including dtSearch index management, keyword search, Analytics Conceptual Index for LSI and concept discovery, and Pivot queries for data anal
  name: Search and Analytics API
  slug: search-analytics-api
- description: APIs for identity and access management in RelativityOne. Includes user CRUD operations, permission assignment and management, group administration, and client management.
  name: User and Permission Manager API
  slug: user-permission-manager-api
- description: Import and Export Services API for handling document and Relativity Dynamic Object (RDO) transfers, including bulk import operations for large data sets.
  name: Import and Export API
  slug: import-export-api
capabilities:
- description: Unified legal hold management capability for RelativityOne. Combines legal hold project management, custodian tracking, data preservation workflows, HR entity integration, and communication management
  name: RelativityOne Legal Hold Management
  slug: legal-hold-management
common:
- title: ''
  type: Website
  url: https://www.relativity.com
- title: ''
  type: Documentation
  url: https://platform.relativity.com/
- title: ''
  type: Developer Documentation
  url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm
- title: ''
  type: API Reference
  url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Relativity_API_reference.htm
- title: ''
  type: Changelog
  url: https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-ld/relativityone-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/vocabulary/relativityone-vocabulary.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/rules/relativityone-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/capabilities/legal-hold-management.yaml
- title: ''
  type: GitHub Organization
  url: https://github.com/relativitydev
created: '2025-03-01'
description: RelativityOne is a cloud-based eDiscovery and legal technology platform that provides comprehensive REST APIs for legal hold management, document processing, search and analytics, workspace management, identity and access control, and billing insights. The platform integrates with Microsoft 365 and Google Workspace for data preservation and legal hold workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Relativityone Context
  property_count: 27
  slug: relativityone-context
layout: provider
modified: '2026-05-02'
name: RelativityOne
rules:
- name: RelativityOne API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 5
  slug: relativityone-rules
skills: []
slug: relativityone
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: relativityone\nname: RelativityOne\ndescription: >-\n  RelativityOne is a cloud-based eDiscovery and legal technology platform that\n  provides comprehensive REST APIs for legal hold management, document processing,\n  search and analytics, workspace management, identity and access control, and\n  billing insights. The platform integrates with Microsoft 365 and Google Workspace\n  for data preservation and legal hold workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - eDiscovery\n  - Legal\n  - Legal Hold\n  - Document Management\n  - Compliance\n  - Litigation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: relativityone:legal-hold-api\n    name: Legal Hold API\n    description: >-\n      The Legal Hold API enables matter and project management integration with\n\
  \      external systems like matter management platforms and HR systems. It provides\n      endpoints for custodian management, preservation workflows, task tracking,\n      entity management, and communication configuration. Authentication is handled\n      via Microsoft Graph API.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Legal Hold\n      - Custodian Management\n      - Preservation\n      - eDiscovery\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/openapi/relativityone-legal-hold-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-schema/relativityone-legal-hold-project-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-schema/relativityone-custodian-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-structure/relativityone-legal-hold-structure.json\n\n  - aid: relativityone:object-manager-api\n    name: Object Manager API\n    description: >-\n      The Object Manager API provides CRUD operations for documents and Relativity\n      Dynamic Objects (RDOs). It supports bulk read, create, update, and delete\n      operations with filtering and search capabilities across workspace objects.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Document Management\n      - Object Management\n      - CRUD Operations\n      - Workspace\n    properties:\n      - type:\
  \ Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n\n  - aid: relativityone:workspace-manager-api\n    name: Workspace Manager API\n    description: >-\n      The Workspace Manager API provides CRUD operations for Relativity workspaces,\n      including workspace creation, configuration, application installation, and\n      environment management.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Workspace Management\n      - Administration\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n\n  - aid: relativityone:search-analytics-api\n    name: Search and Analytics API\n    description: >-\n      APIs for search and analytics operations in RelativityOne including dtSearch\n      index management,\
  \ keyword search, Analytics Conceptual Index for LSI and\n      concept discovery, and Pivot queries for data analysis.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Search\n      - Analytics\n      - Full Text Search\n      - Concept Search\n      - Data Analysis\n    properties:\n      - type: Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n\n  - aid: relativityone:user-permission-manager-api\n    name: User and Permission Manager API\n    description: >-\n      APIs for identity and access management in RelativityOne. Includes user CRUD\n      operations, permission assignment and management, group administration, and\n      client management.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Identity\n\
  \      - Access Management\n      - Permissions\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n\n  - aid: relativityone:import-export-api\n    name: Import and Export API\n    description: >-\n      Import and Export Services API for handling document and Relativity Dynamic\n      Object (RDO) transfers, including bulk import operations for large data sets.\n    humanURL: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n    baseURL: https://relativity.rest/api\n    tags:\n      - Import\n      - Export\n      - Data Transfer\n      - Bulk Operations\n    properties:\n      - type: Documentation\n        url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n\ncommon:\n  - type: Website\n    url: https://www.relativity.com\n  - type: Documentation\n    url: https://platform.relativity.com/\n  - type:\
  \ Developer Documentation\n    url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm\n  - type: API Reference\n    url: https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Relativity_API_reference.htm\n  - type: Changelog\n    url: https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-ld/relativityone-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/vocabulary/relativityone-vocabulary.yml\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/rules/relativityone-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/capabilities/legal-hold-management.yaml\n\
  \  - type: GitHub Organization\n    url: https://github.com/relativitydev\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml
tags:
- eDiscovery
- Legal
- Legal Hold
- Document Management
- Compliance
- Litigation
url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml
use_cases: []
---
