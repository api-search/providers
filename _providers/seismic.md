---
api_count: 4
api_specs:
- filename: seismic-content-openapi.yml
  format: yaml
  label: Seismic Content API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-content-openapi.yml
- filename: seismic-livedocs-openapi.yml
  format: yaml
  label: Seismic LiveDocs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-livedocs-openapi.yml
- filename: seismic-analytics-openapi.yml
  format: yaml
  label: Seismic Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-analytics-openapi.yml
- filename: seismic-user-management-openapi.yml
  format: yaml
  label: Seismic User Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-user-management-openapi.yml
apis:
- description: API for managing and accessing content within the Seismic platform, including documents, presentations, folders, and other sales materials. Supports uploading, organizing, searching, delivering, and m
  name: Seismic Content API
  slug: ''
- description: API for creating and managing LiveDocs, Seismic's dynamic document generation solution. Enables automated creation of personalized proposals, presentations, and sales materials by merging CRM and othe
  name: Seismic LiveDocs API
  slug: ''
- description: API for accessing analytics and reporting data on content usage, user engagement, and sales effectiveness. Provides insights into content performance, user adoption, buyer engagement, and exportable r
  name: Seismic Analytics API
  slug: ''
- description: 'API for managing users, groups, roles, teams, and permissions within the Seismic platform. Supports creating and organizing users, managing group hierarchies, assigning roles, and team structures for '
  name: Seismic User Management API
  slug: ''
capabilities:
- description: Unified workflow capability for managing sales enablement content in Seismic — combining content management, folder organization, search, and analytics for content teams and sales managers.
  name: Seismic Content Management
  slug: content-management
- description: Unified workflow capability for sales enablement workflows in Seismic — combining dynamic document generation, user management, analytics, and content delivery for sales reps, managers, and enablement
  name: Seismic Sales Enablement
  slug: sales-enablement
common:
- title: ''
  type: Portal
  url: https://developer.seismic.com/
- title: ''
  type: Getting Started
  url: https://developer.seismic.com/seismicsoftware/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.seismic.com/seismicsoftware/docs/authentication
- title: ''
  type: Rate Limits
  url: https://developer.seismic.com/seismicsoftware/docs/rate-limits
- title: ''
  type: Webhooks
  url: https://developer.seismic.com/seismicsoftware/docs/webhooks
- title: ''
  type: Support
  url: https://seismic.com/support/
- title: ''
  type: Privacy Policy
  url: https://seismic.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://seismic.com/terms-of-service/
- title: ''
  type: Status
  url: https://status.seismic.com/
- title: ''
  type: Documentation
  url: https://developer.seismic.com/seismicsoftware/docs
- title: ''
  type: Change Log
  url: https://developer.seismic.com/seismicsoftware/changelog
- title: ''
  type: Website
  url: https://seismic.com
- title: ''
  type: Blog
  url: https://seismic.com/resources/blog/
- title: ''
  type: Login
  url: https://login.seismic.com/
- title: ''
  type: SpectralRules
  url: rules/seismic-rules.yml
- title: ''
  type: JSONLDContext
  url: json-ld/seismic-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/seismic-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/content-management.yaml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/sales-enablement.yaml
created: '2025-02-10'
description: Seismic is the global leader in enablement, helping organizations engage customers, enable teams, and ignite revenue growth. The Seismic platform provides content management, learning and coaching, dynamic document generation, and buyer engagement capabilities through a comprehensive suite of APIs.
features: []
image: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg
integrations: []
jsonld:
- class_count: 13
  name: Seismic Context
  property_count: 23
  slug: seismic-context
layout: provider
modified: '2026-05-02'
name: Seismic
rules:
- name: Seismic API Rules
  rule_count: 14
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 8
  slug: seismic-rules
skills: []
slug: seismic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Seismic\ndescription: >-\n  Seismic is the global leader in enablement, helping organizations engage customers,\n  enable teams, and ignite revenue growth. The Seismic platform provides content\n  management, learning and coaching, dynamic document generation, and buyer\n  engagement capabilities through a comprehensive suite of APIs.\nimage: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg\nurl: https://seismic.com\ncreated: '2025-02-10'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\napis:\n  - name: Seismic Content API\n    description: >-\n      API for managing and accessing content within the Seismic platform, including\n      documents, presentations, folders, and other sales materials. Supports uploading,\n      organizing, searching, delivering, and managing content items.\n    image: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg\n    humanURL: https://seismic.com/products/content-management/\n    baseURL: https://api.seismic.com/integration/v2\n\
  \    tags:\n      - Content\n      - Content Management\n      - Documents\n      - Sales Enablement\n    properties:\n      - type: Documentation\n        url: https://developer.seismic.com/seismicsoftware/reference/content-api\n      - type: OpenAPI\n        url: openapi/seismic-content-openapi.yml\n      - type: Authentication\n        url: https://developer.seismic.com/seismicsoftware/docs/authentication\n      - type: JSONSchema\n        url: json-schema/seismic-content-item-schema.json\n      - type: JSONSchema\n        url: json-schema/seismic-folder-schema.json\n      - type: JSONStructure\n        url: json-structure/seismic-content-item-structure.json\n    contact:\n      - FN: Seismic Support\n        email: support@seismic.com\n        url: https://seismic.com/support/\n  - name: Seismic LiveDocs API\n    description: >-\n      API for creating and managing LiveDocs, Seismic's dynamic document generation\n      solution. Enables automated creation of personalized proposals,\
  \ presentations,\n      and sales materials by merging CRM and other data into templates.\n    image: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg\n    humanURL: https://seismic.com/products/livedocs/\n    baseURL: https://api.seismic.com/integration/v2\n    tags:\n      - Document Generation\n      - Dynamic Content\n      - LiveDocs\n      - Sales Enablement\n    properties:\n      - type: Documentation\n        url: https://developer.seismic.com/seismicsoftware/reference/livedocs-api\n      - type: OpenAPI\n        url: openapi/seismic-livedocs-openapi.yml\n      - type: JSONSchema\n        url: json-schema/seismic-livedoc-template-schema.json\n    contact:\n      - FN: Seismic Support\n        email: support@seismic.com\n        url: https://seismic.com/support/\n  - name: Seismic Analytics API\n    description: >-\n      API for accessing analytics and reporting data on content usage, user engagement,\n      and sales effectiveness. Provides insights into content\
  \ performance, user adoption,\n      buyer engagement, and exportable reports.\n    image: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg\n    humanURL: https://seismic.com/products/analytics/\n    baseURL: https://api.seismic.com/integration/v2\n    tags:\n      - Analytics\n      - Insights\n      - Metrics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.seismic.com/seismicsoftware/reference/analytics-api\n      - type: OpenAPI\n        url: openapi/seismic-analytics-openapi.yml\n    contact:\n      - FN: Seismic Support\n        email: support@seismic.com\n        url: https://seismic.com/support/\n  - name: Seismic User Management API\n    description: >-\n      API for managing users, groups, roles, teams, and permissions within the Seismic\n      platform. Supports creating and organizing users, managing group hierarchies,\n      assigning roles, and team structures for access control.\n    image: https://seismic.com/wp-content/uploads/2023/02/seismic-logo.svg\n\
  \    humanURL: https://seismic.com\n    baseURL: https://api.seismic.com/integration/v2\n    tags:\n      - Administration\n      - Groups\n      - Permissions\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.seismic.com/seismicsoftware/reference/user-management-api\n      - type: OpenAPI\n        url: openapi/seismic-user-management-openapi.yml\n      - type: JSONSchema\n        url: json-schema/seismic-user-schema.json\n      - type: JSONSchema\n        url: json-schema/seismic-group-schema.json\n    contact:\n      - FN: Seismic Support\n        email: support@seismic.com\n        url: https://seismic.com/support/\ncommon:\n  - type: Portal\n    url: https://developer.seismic.com/\n  - type: Getting Started\n    url: https://developer.seismic.com/seismicsoftware/docs/getting-started\n  - type: Authentication\n    url: https://developer.seismic.com/seismicsoftware/docs/authentication\n  - type: Rate Limits\n    url: https://developer.seismic.com/seismicsoftware/docs/rate-limits\n\
  \  - type: Webhooks\n    url: https://developer.seismic.com/seismicsoftware/docs/webhooks\n  - type: Support\n    url: https://seismic.com/support/\n  - type: Privacy Policy\n    url: https://seismic.com/privacy-policy/\n  - type: Terms of Service\n    url: https://seismic.com/terms-of-service/\n  - type: Status\n    url: https://status.seismic.com/\n  - type: Documentation\n    url: https://developer.seismic.com/seismicsoftware/docs\n  - type: Change Log\n    url: https://developer.seismic.com/seismicsoftware/changelog\n  - type: Website\n    url: https://seismic.com\n  - type: Blog\n    url: https://seismic.com/resources/blog/\n  - type: Login\n    url: https://login.seismic.com/\n  - type: SpectralRules\n    url: rules/seismic-rules.yml\n  - type: JSONLDContext\n    url: json-ld/seismic-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/seismic-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/content-management.yaml\n  - type: NaftikoCapabilities\n    url:\
  \ capabilities/sales-enablement.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/apis.yml
tags: []
url: https://seismic.com
use_cases: []
---
