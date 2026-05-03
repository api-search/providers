---
api_count: 3
api_specs:
- filename: sisense-rest-api-openapi.yml
  format: yaml
  label: Sisense REST API v1
  slug: rest-api-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/openapi/sisense-rest-api-openapi.yml
apis:
- description: 'The Sisense REST API v1 provides programmatic access to dashboards, users, groups, Elasticubes, data security rules, and builds. It supports both extract-based Elasticube models and live data models. '
  name: Sisense REST API v1
  slug: rest-api-v1
- description: The Sisense REST API v2 provides access to Datamodels (the v2 replacement for Elasticubes), builds, and advanced data model management capabilities including schema management, field configuration, an
  name: Sisense REST API v2
  slug: rest-api-v2
- description: The Sisense User and Role Management API (RBAC) enables administrators to manage users, roles, and permissions programmatically. Available on select plans through contact with Customer Success Manager
  name: Sisense User and Role Management API
  slug: user-role-management-api
capabilities:
- description: Unified analytics administration workflow for Sisense BI platform management. Combines dashboard management, user and group access control, Elasticube data model management, and data security rule con
  name: Sisense Analytics Administration
  slug: analytics-administration
common:
- title: ''
  type: Website
  url: https://www.sisense.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.sisense.com/
- title: ''
  type: Documentation
  url: https://docs.sisense.com/
- title: ''
  type: Pricing
  url: https://www.sisense.com/pricing/
- title: ''
  type: Blog
  url: https://www.sisense.com/blog/
- title: ''
  type: GitHubOrg
  url: https://github.com/sisense
- title: ''
  type: Community
  url: https://community.sisense.com/
- title: ''
  type: TermsOfService
  url: https://www.sisense.com/legal/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.sisense.com/legal/privacy-policy/
- title: ''
  type: Support
  url: https://support.sisense.com/
created: '2025-01-08'
description: Sisense is a business intelligence and analytics platform that enables organizations to build and embed analytics into applications and workflows. It provides REST APIs for managing dashboards, data models (Elasticubes and live models), users, groups, data security rules, and builds. The platform supports both extract-based and live data model architectures with comprehensive programmatic administration capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Sisense Context
  property_count: 6
  slug: sisense-context
layout: provider
modified: '2026-05-02'
name: Sisense
rules:
- name: Sisense API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: sisense-rules
skills: []
slug: sisense
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sisense\nname: Sisense\ndescription: >-\n  Sisense is a business intelligence and analytics platform that enables organizations\n  to build and embed analytics into applications and workflows. It provides REST APIs\n  for managing dashboards, data models (Elasticubes and live models), users, groups,\n  data security rules, and builds. The platform supports both extract-based and live\n  data model architectures with comprehensive programmatic administration capabilities.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data Models\n  - Embedded Analytics\ncreated: '2025-01-08'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sisense:rest-api-v1\n    name: Sisense REST API v1\n    description: >-\n     \
  \ The Sisense REST API v1 provides programmatic access to dashboards, users,\n      groups, Elasticubes, data security rules, and builds. It supports both\n      extract-based Elasticube models and live data models. Authentication uses\n      Bearer tokens obtained via the login endpoint or from User Profiles settings.\n    humanURL: https://developer.sisense.com/guides/restApi/v1/\n    baseURL: https://your-sisense-host/api/v1\n    tags:\n      - Dashboards\n      - Users\n      - Groups\n      - Elasticubes\n      - Data Models\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://developer.sisense.com/guides/restApi/v1/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/openapi/sisense-rest-api-openapi.yml\n\n  - aid: sisense:rest-api-v2\n    name: Sisense REST API v2\n    description: >-\n      The Sisense REST API v2 provides access to Datamodels (the v2 replacement for\n    \
  \  Elasticubes), builds, and advanced data model management capabilities including\n      schema management, field configuration, and live data model operations.\n    humanURL: https://developer.sisense.com/guides/restApi/v2/\n    baseURL: https://your-sisense-host/api/v2\n    tags:\n      - Data Models\n      - Builds\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://developer.sisense.com/guides/restApi/v2/\n\n  - aid: sisense:user-role-management-api\n    name: Sisense User and Role Management API\n    description: >-\n      The Sisense User and Role Management API (RBAC) enables administrators to\n      manage users, roles, and permissions programmatically. Available on select\n      plans through contact with Customer Success Manager.\n    humanURL: https://dtdocs.sisense.com/article/user-and-role-management-api-rbac\n    baseURL: https://your-sisense-host/api/v1\n    tags:\n      - Users\n      - Roles\n      - RBAC\n      - Identity\n    properties:\n\
  \      - type: Documentation\n        url: https://dtdocs.sisense.com/article/user-and-role-management-api-rbac\n\ncommon:\n  - type: Website\n    url: https://www.sisense.com/\n  - type: DeveloperPortal\n    url: https://developer.sisense.com/\n  - type: Documentation\n    url: https://docs.sisense.com/\n  - type: Pricing\n    url: https://www.sisense.com/pricing/\n  - type: Blog\n    url: https://www.sisense.com/blog/\n  - type: GitHubOrg\n    url: https://github.com/sisense\n  - type: Community\n    url: https://community.sisense.com/\n  - type: TermsOfService\n    url: https://www.sisense.com/legal/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.sisense.com/legal/privacy-policy/\n  - type: Support\n    url: https://support.sisense.com/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Models
- Embedded Analytics
url: https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml
use_cases: []
---
