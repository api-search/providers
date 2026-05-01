---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Meet API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/openapi/openapi.yml
apis:
- description: The Google Meet REST API enables creating and managing meeting spaces, retrieving conference records with participant and session data, accessing meeting recordings and transcripts, and controlling ac
  name: Google Meet API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://developers.google.com/workspace/meet/api/guides/overview
- title: ''
  type: Pricing
  url: https://cloud.google.com/meet/pricing
- title: ''
  type: JSONLD
  url: json-ld/json-ld.jsonld
created: '2026-03-13'
description: The Google Meet API provides programmatic access to Google Meet video conferencing functionality. It enables applications to create and manage meeting spaces, retrieve conference records including participant details, access recordings and transcripts, and end active conferences. The API supports building integrations that automate meeting workflows and extract meeting data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Json Ld Context
  property_count: 6
  slug: json-ld
layout: provider
modified: '2026-04-28'
name: Google Meet
rules:
- name: Google Meet API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-meet-spectral-rules
skills: []
slug: google-meet
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Google Meet\ndescription: >-\n  The Google Meet API provides programmatic access to Google Meet video\n  conferencing functionality. It enables applications to create and manage\n  meeting spaces, retrieve conference records including participant details,\n  access recordings and transcripts, and end active conferences. The API\n  supports building integrations that automate meeting workflows and extract\n  meeting data.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Google\n  - Google Workspace\n  - Meetings\n  - Recordings\n  - Transcripts\n  - Video Conferencing\napis:\n  - name: Google Meet API\n    description: >-\n      The Google Meet REST API enables creating and managing meeting spaces,\n      retrieving conference records with participant and session\
  \ data, accessing\n      meeting recordings and transcripts, and controlling active conferences.\n    humanURL: https://developers.google.com/workspace/meet/api/guides/overview\n    baseURL: https://meet.googleapis.com\n    properties:\n      - type: OpenAPI\n        url: openapi/openapi.yml\n      - type: JSONSchema\n        url: json-schema/json-schema.yml\n      - type: JSONLD\n        url: json-ld/json-ld.jsonld\n    tags:\n      - Meetings\n      - Recordings\n      - Transcripts\n      - Video Conferencing\ncommon:\n  - type: GettingStarted\n    url: https://developers.google.com/workspace/meet/api/guides/overview\n  - type: Pricing\n    url: https://cloud.google.com/meet/pricing\n  - type: JSONLD\n    url: json-ld/json-ld.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/apis.yml
tags:
- Google
- Google Workspace
- Meetings
- Recordings
- Transcripts
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/apis.yml
use_cases: []
---
