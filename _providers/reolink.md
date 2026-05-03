---
api_count: 1
api_specs:
- filename: reolink-camera-api-openapi.yml
  format: yaml
  label: Reolink Camera HTTP API
  slug: camera-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/openapi/reolink-camera-api-openapi.yml
apis:
- description: The Reolink Camera HTTP API provides a JSON-based interface for controlling and configuring Reolink IP cameras and NVRs. All commands are sent as HTTP POST requests to the /cgi-bin/api.cgi endpoint. T
  name: Reolink Camera HTTP API
  slug: camera-http-api
capabilities:
- description: Unified workflow for managing and monitoring Reolink IP cameras and NVRs. Combines device system management, PTZ control, recording search and playback, AI-powered object detection, motion alarm confi
  name: Reolink Camera Management
  slug: camera-management
common:
- title: ''
  type: Website
  url: https://reolink.com
- title: ''
  type: Forum
  url: https://community.reolink.com/
- title: ''
  type: Support
  url: https://support.reolink.com/
- title: ''
  type: Blog
  url: https://reolink.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/ReolinkCameraAPI
created: '2025-01-01'
description: Reolink is a provider of security cameras and smart home surveillance technology. Their cameras offer an HTTP API that enables direct device control and configuration through JSON-based POST requests. The API supports comprehensive camera management including PTZ control, video encoding settings, recording search and playback, motion and AI-powered object detection, network configuration, LED control, and user authentication. The API is accessible on the local network via the device IP address.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Reolink Context
  property_count: 10
  slug: reolink-context
layout: provider
modified: '2026-05-02'
name: Reolink
rules:
- name: Reolink API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 4
  slug: reolink-rules
skills: []
slug: reolink
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reolink\nname: Reolink\ndescription: >-\n  Reolink is a provider of security cameras and smart home surveillance\n  technology. Their cameras offer an HTTP API that enables direct device\n  control and configuration through JSON-based POST requests. The API\n  supports comprehensive camera management including PTZ control, video\n  encoding settings, recording search and playback, motion and AI-powered\n  object detection, network configuration, LED control, and user\n  authentication. The API is accessible on the local network via the\n  device IP address.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - IoT\n  - Security Cameras\n  - Surveillance\n  - Smart Home\n  - AI Detection\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: reolink:camera-http-api\n    name: Reolink Camera\
  \ HTTP API\n    description: >-\n      The Reolink Camera HTTP API provides a JSON-based interface for controlling\n      and configuring Reolink IP cameras and NVRs. All commands are sent as HTTP POST\n      requests to the /cgi-bin/api.cgi endpoint. The API covers 11 functional modules\n      including authentication, system management, security, network configuration,\n      video and image settings, encoding, recording and playback, PTZ control, alarm\n      and motion detection, LED control, and AI-powered object detection with auto-tracking.\n    humanURL: https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023\n    tags:\n      - IoT\n      - Security Cameras\n      - Surveillance\n      - Smart Home\n      - AI Detection\n    properties:\n      - url: https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023\n        type: Documentation\n      - url: openapi/reolink-camera-api-openapi.yml\n        type:\
  \ OpenAPI\n      - url: json-schema/device-info.json\n        type: JSONSchema\n      - url: json-schema/command-request.json\n        type: JSONSchema\n      - url: json-schema/command-response.json\n        type: JSONSchema\n      - url: json-schema/login.json\n        type: JSONSchema\n      - url: json-schema/ptz-control.json\n        type: JSONSchema\n      - url: json-schema/recording-search.json\n        type: JSONSchema\n      - url: json-schema/alarm-settings.json\n        type: JSONSchema\n      - url: json-schema/network-settings.json\n        type: JSONSchema\n      - url: json-ld/reolink-context.jsonld\n        type: JSONLD\n      - url: rules/reolink-rules.yml\n        type: Rules\n      - url: capabilities/camera-management.yaml\n        type: Capabilities\n      - url: json-structure/reolink-device-structure.json\n        type: JSONStructure\n      - url: vocabulary/reolink-vocabulary.yml\n        type: Vocabulary\n      - url: examples/reolink-login-example.json\n    \
  \    type: Example\n      - url: examples/reolink-ptz-control-example.json\n        type: Example\ncommon:\n  - url: https://reolink.com\n    name: Reolink\n    type: Website\n    description: Reolink security camera manufacturer homepage\n  - url: https://community.reolink.com/\n    name: Reolink Community Forum\n    type: Forum\n    description: Community discussion and API documentation\n  - url: https://support.reolink.com/\n    name: Reolink Support\n    type: Support\n    description: Official technical support portal\n  - url: https://reolink.com/blog/\n    name: Reolink Blog\n    type: Blog\n    description: Product news and smart home tips\n  - url: https://github.com/ReolinkCameraAPI\n    name: Reolink Camera API Community\n    type: GitHubOrganization\n    description: Community-maintained Reolink API SDKs and documentation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml
tags:
- IoT
- Security Cameras
- Surveillance
- Smart Home
- AI Detection
url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml
use_cases: []
---
