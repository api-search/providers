---
api_count: 1
api_specs:
- filename: google-drive-openapi.yml
  format: yaml
  label: Google Drive API v3
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/openapi/google-drive-openapi.yml
apis:
- description: REST API for managing files and folders in Google Drive. Supports file metadata operations, content upload and download, sharing and permissions, revisions, comments, and changes feeds.
  name: Google Drive API v3
  slug: ''
common:
- title: ''
  type: Portal
  url: https://console.cloud.google.com/
- title: ''
  type: Getting Started
  url: https://developers.google.com/drive/api/v3/enable-drive-api
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: Change Log
  url: https://developers.google.com/drive/api/v3/releases
- title: ''
  type: Rate Limits
  url: https://developers.google.com/drive/api/v3/handle-errors#rate-limit-exceeded
- title: ''
  type: Status
  url: https://www.google.com/appsstatus
- title: ''
  type: JSON-LD
  url: json-ld/google-drive-context.jsonld
created: '2024-01-15'
description: The Google Drive API allows developers to integrate with Google Drive to create, read, update, and delete files and folders stored in Google Drive. The v3 REST API supports file metadata operations, content upload and download, folder hierarchies, sharing and permissions, and search across a user's Drive.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Google Drive Context
  property_count: 0
  slug: google-drive-context
layout: provider
modified: '2026-04-28'
name: Google Drive
rules:
- name: Google Drive API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-drive-spectral-rules
skills: []
slug: google-drive
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-drive\nname: Google Drive\ndescription: >-\n  The Google Drive API allows developers to integrate with Google Drive to\n  create, read, update, and delete files and folders stored in Google Drive.\n  The v3 REST API supports file metadata operations, content upload and\n  download, folder hierarchies, sharing and permissions, and search across a\n  user's Drive.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Cloud Storage\n  - Collaboration\n  - Document Management\n  - Drive\n  - Files\n  - Google\n  - Storage\napis:\n  - name: Google Drive API v3\n    description: >-\n      REST API for managing files and folders in Google Drive. Supports file\n      metadata operations, content upload and download, sharing and permissions,\n      revisions,\
  \ comments, and changes feeds.\n    image: https://www.gstatic.com/images/branding/product/2x/drive_48dp.png\n    humanURL: https://developers.google.com/drive/api/v3/about-sdk\n    baseURL: https://www.googleapis.com/drive/v3\n    tags:\n      - Cloud\n      - Collaboration\n      - Files\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/drive/api/v3/reference\n      - type: OpenAPI\n        url: openapi/google-drive-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-drive-file-schema.json\n      - type: Authentication\n        url: https://developers.google.com/drive/api/v3/about-auth\n      - type: Quickstart\n        url: https://developers.google.com/drive/api/v3/quickstart/python\n      - type: Pricing\n        url: https://workspace.google.com/pricing\n      - type: Terms of Service\n        url: https://developers.google.com/terms\n      - type: OAuth Scopes\n        url: https://developers.google.com/drive/api/v3/about-auth#OAuth2Authorizing\n\
  \    contact:\n      - type: Support\n        url: https://developers.google.com/drive/api/v3/support\ncommon:\n  - type: Portal\n    url: https://console.cloud.google.com/\n  - type: Getting Started\n    url: https://developers.google.com/drive/api/v3/enable-drive-api\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: Change Log\n    url: https://developers.google.com/drive/api/v3/releases\n  - type: Rate Limits\n    url: https://developers.google.com/drive/api/v3/handle-errors#rate-limit-exceeded\n  - type: Status\n    url: https://www.google.com/appsstatus\n  - type: JSON-LD\n    url: json-ld/google-drive-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/apis.yml
tags:
- Cloud Storage
- Collaboration
- Document Management
- Drive
- Files
- Google
- Storage
url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/apis.yml
use_cases: []
---
