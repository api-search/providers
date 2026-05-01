---
api_count: 2
api_specs:
- filename: eloqua-rest-openapi.yml
  format: yaml
  label: Eloqua REST API
  slug: eloqua-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/openapi/eloqua-rest-openapi.yml
- filename: eloqua-bulk-openapi.yml
  format: yaml
  label: Eloqua Bulk API
  slug: eloqua-bulk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/openapi/eloqua-bulk-openapi.yml
apis:
- description: The primary REST API for Oracle Eloqua, providing access to marketing automation, contact management, campaign operations, and analytics.
  name: Eloqua REST API
  slug: eloqua-rest-api
- description: Bulk API for high-volume data operations including imports, exports, and synchronization of large datasets.
  name: Eloqua Bulk API
  slug: eloqua-bulk-api
common:
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/GettingStarted.html
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/Authentication.html
- title: ''
  type: Support
  url: https://support.oracle.com/
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: SDKs
  url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/SDKs.html
created: '2025-01-01'
description: Oracle Eloqua is a marketing automation platform that provides tools for lead management, email marketing, and marketing campaign management through comprehensive REST APIs. It enables marketing teams to create, execute, and measure the effectiveness of marketing programs and campaigns.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Eloqua Context
  property_count: 10
  slug: eloqua-context
layout: provider
modified: '2026-03-16'
name: Oracle Eloqua
skills: []
slug: eloqua
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: eloqua\nname: Oracle Eloqua\ndescription: >-\n  Oracle Eloqua is a marketing automation platform that provides tools for\n  lead management, email marketing, and marketing campaign management through\n  comprehensive REST APIs. It enables marketing teams to create, execute, and\n  measure the effectiveness of marketing programs and campaigns.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CRM\n  - Email Marketing\n  - Lead Management\n  - Marketing Automation\nurl: https://www.oracle.com/marketingcloud/products/marketing-automation/\ncreated: '2025-01-01'\nmodified: '2026-03-16'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: eloqua:eloqua-rest-api\n    name: Eloqua REST API\n    description: >-\n      The primary REST API for Oracle Eloqua, providing access to marketing\n      automation, contact management, campaign operations, and analytics.\n    humanURL: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/\n\
  \    baseURL: https://secure.p01.eloqua.com/API/REST/2.0/\n    tags:\n      - Campaigns\n      - Contacts\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/\n      - type: OpenAPI\n        url: openapi/eloqua-rest-openapi.yml\n  - aid: eloqua:eloqua-bulk-api\n    name: Eloqua Bulk API\n    description: >-\n      Bulk API for high-volume data operations including imports, exports,\n      and synchronization of large datasets.\n    humanURL: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/BulkAPI.html\n    baseURL: https://secure.p01.eloqua.com/API/Bulk/2.0/\n    tags:\n      - Bulk Operations\n      - Data Export\n      - Data Import\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/BulkAPI.html\n      - type: OpenAPI\n        url: openapi/eloqua-bulk-openapi.yml\ncommon:\n  - type: GettingStarted\n    url:\
  \ https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/GettingStarted.html\n  - type: Authentication\n    url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/Authentication.html\n  - type: Support\n    url: https://support.oracle.com/\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: SDKs\n    url: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/SDKs.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/apis.yml
tags:
- CRM
- Email Marketing
- Lead Management
- Marketing Automation
url: https://www.oracle.com/marketingcloud/products/marketing-automation/
use_cases: []
---
