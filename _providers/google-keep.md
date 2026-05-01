---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Keep API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/openapi/openapi.yml
apis:
- description: The Google Keep API enables enterprise administrators to manage Google Keep notes, including creating, listing, deleting, downloading note attachments, and managing permissions on notes.
  name: Google Keep API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://developers.google.com/workspace/keep/api/guides
- title: ''
  type: Pricing
  url: https://workspace.google.com/pricing
- title: ''
  type: JSONLD
  url: json-ld/json-ld.jsonld
created: '2026-03-13'
description: The Google Keep API provides programmatic access to Google Keep notes for enterprise administrators. It enables creating, listing, retrieving, and deleting notes, downloading note attachments, and managing note permissions. The API is designed for enterprise use cases where administrators need to manage Keep notes across their organization.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Json Ld Context
  property_count: 3
  slug: json-ld
layout: provider
modified: '2026-04-28'
name: Google Keep
rules:
- name: Google Keep API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-keep-spectral-rules
skills: []
slug: google-keep
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Google Keep\ndescription: >-\n  The Google Keep API provides programmatic access to Google Keep notes for\n  enterprise administrators. It enables creating, listing, retrieving, and\n  deleting notes, downloading note attachments, and managing note permissions.\n  The API is designed for enterprise use cases where administrators need to\n  manage Keep notes across their organization.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Google\n  - Google Workspace\n  - Notes\n  - Organization\n  - Productivity\napis:\n  - name: Google Keep API\n    description: >-\n      The Google Keep API enables enterprise administrators to manage Google Keep\n      notes, including creating, listing, deleting, downloading note\n      attachments, and managing permissions on\
  \ notes.\n    humanURL: https://developers.google.com/workspace/keep/api/guides\n    baseURL: https://keep.googleapis.com\n    properties:\n      - type: OpenAPI\n        url: openapi/openapi.yml\n      - type: JSONSchema\n        url: json-schema/json-schema.yml\n      - type: JSONLD\n        url: json-ld/json-ld.jsonld\n      - type: Spectral Rules\n        url: rules/google-keep-spectral-rules.yml\n    tags:\n      - Attachments\n      - Notes\n      - Permissions\ncommon:\n  - type: GettingStarted\n    url: https://developers.google.com/workspace/keep/api/guides\n  - type: Pricing\n    url: https://workspace.google.com/pricing\n  - type: JSONLD\n    url: json-ld/json-ld.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/apis.yml
tags:
- Google
- Google Workspace
- Notes
- Organization
- Productivity
url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/apis.yml
use_cases: []
---
