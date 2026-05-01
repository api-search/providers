---
api_count: 3
api_specs:
- filename: Looker.4.0.oas.json
  format: json
  label: Looker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/looker-open-source/sdk-codegen/main/spec/Looker.4.0.oas.json
- filename: rest
  format: yaml
  label: Looker (Google Cloud core) API
  slug: ''
  spec_type: OpenAPI
  url: https://looker.googleapis.com/$discovery/rest?version=v1
apis:
- description: The Looker API provides programmatic access to Looker functionality for managing users, content, queries, and more.
  name: Looker API
  slug: ''
- description: The Looker (Google Cloud core) REST API provides programmatic access to manage Looker instances, backups, and operations within Google Cloud projects and locations.
  name: Looker (Google Cloud core) API
  slug: ''
- description: 'The Looker Studio API allows you to search for and manage Looker Studio assets programmatically, enabling automation and migration of Looker Studio resources within Google Workspace or Cloud Identity '
  name: Looker Studio API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://cloud.google.com/looker
- title: ''
  type: Getting Started
  url: https://cloud.google.com/looker/docs/getting-started
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/products/data-analytics
- title: ''
  type: Terms of Service
  url: https://cloud.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://cloud.google.com/privacy
- title: ''
  type: Release Notes
  url: https://cloud.google.com/looker/docs/release-notes
- title: ''
  type: Looker Studio
  url: https://cloud.google.com/looker-studio
- title: ''
  type: Community Connectors
  url: https://developers.google.com/looker-studio/connector
- title: ''
  type: Community Connectors Reference
  url: https://developers.google.com/looker-studio/connector/reference
created: '2024-01-01'
description: A collection of APIs for Google Looker, a modern business intelligence and analytics platform.
features: []
image: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png
integrations: []
jsonld:
- class_count: 16
  name: context Context
  property_count: 0
  slug: context
layout: provider
modified: '2026-04-28'
name: Google Looker
rules:
- name: Google Looker API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-looker-spectral-rules
skills: []
slug: google-looker
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-looker\nname: Google Looker\ndescription: >-\n  A collection of APIs for Google Looker, a modern business intelligence and analytics\n  platform.\nimage: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png\nurl: https://cloud.google.com/looker\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - name: Looker API\n    description: >-\n      The Looker API provides programmatic access to Looker functionality for managing\n      users, content, queries, and more.\n    image: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png\n    humanURL: https://cloud.google.com/looker/docs/api-overview\n    baseURL: https://your-instance.cloud.looker.com:19999/api/4.0\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Data Visualization\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/looker/docs/reference/looker-api/latest\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/looker-open-source/sdk-codegen/main/spec/Looker.4.0.oas.json\n      - type: Authentication\n        url: https://cloud.google.com/looker/docs/api-auth\n      - type: SDK\n        url: https://github.com/looker-open-source/sdk-codegen\n      - type: Pricing\n        url: https://cloud.google.com/looker/pricing\n      - type: Status\n        url: https://status.looker.com/\n      - type: Support\n        url: https://cloud.google.com/looker/docs/support\n      - type: Getting Started\n        url: https://cloud.google.com/looker/docs/api-getting-started\n      - type: API Explorer\n        url: https://cloud.google.com/looker/docs/api-explorer\n      - type: Versioning\n        url: https://cloud.google.com/looker/docs/api-versioning\n  - name: Looker (Google Cloud core) API\n    description: >-\n      The Looker (Google Cloud core) REST API provides programmatic access to manage\n      Looker instances, backups, and\
  \ operations within Google Cloud projects and locations.\n    image: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png\n    humanURL: https://cloud.google.com/looker/docs/reference/rest\n    baseURL: https://looker.googleapis.com\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Cloud Management\n      - Instance Management\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/looker/docs/reference/rest\n      - type: OpenAPI\n        url: https://looker.googleapis.com/$discovery/rest?version=v1\n  - name: Looker Studio API\n    description: >-\n      The Looker Studio API allows you to search for and manage Looker Studio assets\n      programmatically, enabling automation and migration of Looker Studio resources\n      within Google Workspace or Cloud Identity organizations.\n    image: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png\n    humanURL: https://developers.google.com/looker-studio/integrate/api\n\
  \    baseURL: https://datastudio.googleapis.com/v1\n    tags:\n      - Analytics\n      - Assets\n      - Business Intelligence\n      - Data Visualization\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/api\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/api/reference\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://cloud.google.com/looker\n  - type: Getting Started\n    url: https://cloud.google.com/looker/docs/getting-started\n  - type: Blog\n    url: https://cloud.google.com/blog/products/data-analytics\n  - type: Terms of Service\n    url: https://cloud.google.com/terms\n  - type: Privacy Policy\n    url: https://cloud.google.com/privacy\n  - type: Release Notes\n    url: https://cloud.google.com/looker/docs/release-notes\n  - type: Looker Studio\n    url: https://cloud.google.com/looker-studio\n\
  \  - type: Community Connectors\n    url: https://developers.google.com/looker-studio/connector\n  - type: Community Connectors Reference\n    url: https://developers.google.com/looker-studio/connector/reference\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-looker/refs/heads/main/apis.yml
tags: []
url: https://cloud.google.com/looker
use_cases: []
---
