---
api_count: 4
apis:
- description: The Tuya Device Management API provides endpoints to query, control, and manage IoT devices registered to a Tuya cloud project. Capabilities include device information retrieval, factory reset, device
  name: Tuya Device Management API
  slug: device-management
- description: The Tuya Smart Home API provides management capabilities for smart home deployments, including home and room management, device grouping, scene automation (tap-to-run and automation rules), member man
  name: Tuya Smart Home API
  slug: smart-home
- description: The Tuya Authorization API handles authentication for cloud-to-cloud integrations. Supports HMAC-SHA256 request signing using Access ID and Access Secret credentials. Provides token management endpoin
  name: Tuya Authorization API
  slug: authorization
- description: The Tuya Industry API provides enterprise IoT capabilities for non-consumer deployments including industrial device registration, device management, status queries, device control, user management, an
  name: Tuya Industry API
  slug: industry
capabilities:
- description: IoT device management and control capability for smart home applications. Combines device querying, real-time status monitoring, device commands, and operation log analysis. Used by smart home app dev
  name: Tuya Smart Home Control
  slug: smart-home-control
common:
- title: ''
  type: Website
  url: https://developer.tuya.com/en/
- title: ''
  type: Documentation
  url: https://developer.tuya.com/en/docs/cloud/
- title: ''
  type: Sign Up
  url: https://auth.tuya.com/
- title: ''
  type: Getting Started
  url: https://developer.tuya.com/en/docs/iot/quick-start1?id=K95ztz9u9t89n
- title: ''
  type: API Explorer
  url: https://developer.tuya.com/en/docs/cloud
- title: ''
  type: GitHub Organization
  url: https://github.com/tuya
- title: ''
  type: Authentication
  url: https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun
- title: ''
  type: Terms of Service
  url: https://developer.tuya.com/en/docs/iot/compliance?id=Ka9t0qa3qihn3
- title: ''
  type: Portal
  url: https://iot.tuya.com/
- title: ''
  type: OpenAPI
  url: openapi/tuya-device-management-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/tuya-device-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tuya-command-schema.json
- title: ''
  type: JSONLD
  url: json-ld/tuya-context.jsonld
- title: ''
  type: Spectral Rules
  url: rules/tuya-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tuya-vocabulary.yml
created: '2025-03-01'
description: 'Tuya Smart is a global leading AI cloud platform service provider (NYSE: TUYA; HKEX: 2391) that enables IoT device manufacturers, solution providers, and app developers to build smart home and industrial IoT applications. The platform provides APIs for device management, smart home management, scene automation, data analytics, and industry-specific integrations across smart home, energy, security, and industrial verticals. Tuya operates six global data centers and handles over 100 million concurrent requests.'
features: []
image: https://images.tuya.com/smart/tuya-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Tuya Context
  property_count: 6
  slug: tuya-context
layout: provider
modified: '2026-05-03'
name: Tuya
rules:
- name: Tuya API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 7
  slug: tuya-rules
skills: []
slug: tuya
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tuya\nname: Tuya\ndescription: >-\n  Tuya Smart is a global leading AI cloud platform service provider (NYSE: TUYA;\n  HKEX: 2391) that enables IoT device manufacturers, solution providers, and\n  app developers to build smart home and industrial IoT applications. The platform\n  provides APIs for device management, smart home management, scene automation,\n  data analytics, and industry-specific integrations across smart home, energy,\n  security, and industrial verticals. Tuya operates six global data centers and\n  handles over 100 million concurrent requests.\ntype: Contract\naccess: 3rd-Party\nimage: https://images.tuya.com/smart/tuya-logo.png\ntags:\n  - IoT\n  - Smart Home\n  - Devices\n  - Cloud Platform\n  - Automation\n  - Industrial IoT\n  - Device Management\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tuya:device-management\n\
  \    name: Tuya Device Management API\n    description: >-\n      The Tuya Device Management API provides endpoints to query, control, and\n      manage IoT devices registered to a Tuya cloud project. Capabilities include\n      device information retrieval, factory reset, device renaming, sub-device\n      listing, operation log queries, and user-device association management.\n    humanURL: https://developer.tuya.com/en/docs/cloud/device-management?id=K9g6rfntdz78a\n    baseURL: https://openapi.tuyaus.com\n    tags:\n      - Devices\n      - IoT\n      - Device Management\n    properties:\n      - type: Documentation\n        url: https://developer.tuya.com/en/docs/cloud/device-management?id=K9g6rfntdz78a\n      - type: Getting Started\n        url: https://developer.tuya.com/en/docs/iot/quick-start1?id=K95ztz9u9t89n\n\n  - aid: tuya:smart-home\n    name: Tuya Smart Home API\n    description: >-\n      The Tuya Smart Home API provides management capabilities for smart home\n      deployments,\
  \ including home and room management, device grouping, scene\n      automation (tap-to-run and automation rules), member management, and\n      data services. Enables developers to build full-featured smart home\n      applications.\n    humanURL: https://developer.tuya.com/en/docs/cloud/smart_home_paas?id=Kakujwbddm7fv\n    baseURL: https://openapi.tuyaus.com\n    tags:\n      - Smart Home\n      - IoT\n      - Automation\n      - Scene Management\n    properties:\n      - type: Documentation\n        url: https://developer.tuya.com/en/docs/cloud/smart_home_paas?id=Kakujwbddm7fv\n\n  - aid: tuya:authorization\n    name: Tuya Authorization API\n    description: >-\n      The Tuya Authorization API handles authentication for cloud-to-cloud\n      integrations. Supports HMAC-SHA256 request signing using Access ID and\n      Access Secret credentials. Provides token management endpoints for\n      obtaining, refreshing, and revoking access tokens. Supports both cloud\n      authorization\
  \ (server-to-server) and app authorization (user-scoped) modes.\n    humanURL: https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun\n    baseURL: https://openapi.tuyaus.com\n    tags:\n      - Authentication\n      - Authorization\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun\n      - type: API Reference\n        url: https://developer.tuya.com/en/docs/iot/api-reference?id=Ka7qb7vhber64\n\n  - aid: tuya:industry\n    name: Tuya Industry API\n    description: >-\n      The Tuya Industry API provides enterprise IoT capabilities for non-consumer\n      deployments including industrial device registration, device management,\n      status queries, device control, user management, and asset management.\n      Designed for B2B scenarios in real estate, energy, manufacturing, and\n      facilities management.\n    humanURL: https://developer.tuya.com/en/docs/cloud\n   \
  \ baseURL: https://openapi.tuyaus.com\n    tags:\n      - Industrial IoT\n      - Enterprise\n      - Asset Management\n    properties:\n      - type: Documentation\n        url: https://developer.tuya.com/en/docs/cloud\n\ncommon:\n  - type: Website\n    url: https://developer.tuya.com/en/\n  - type: Documentation\n    url: https://developer.tuya.com/en/docs/cloud/\n  - type: Sign Up\n    url: https://auth.tuya.com/\n  - type: Getting Started\n    url: https://developer.tuya.com/en/docs/iot/quick-start1?id=K95ztz9u9t89n\n  - type: API Explorer\n    url: https://developer.tuya.com/en/docs/cloud\n  - type: GitHub Organization\n    url: https://github.com/tuya\n  - type: Authentication\n    url: https://developer.tuya.com/en/docs/iot/guide-explanation?id=Ke0wpiw0dwxun\n  - type: Terms of Service\n    url: https://developer.tuya.com/en/docs/iot/compliance?id=Ka9t0qa3qihn3\n  - type: Portal\n    url: https://iot.tuya.com/\n  - type: OpenAPI\n    url: openapi/tuya-device-management-openapi.yml\n\
  \  - type: JSONSchema\n    url: json-schema/tuya-device-schema.json\n  - type: JSONSchema\n    url: json-schema/tuya-command-schema.json\n  - type: JSONLD\n    url: json-ld/tuya-context.jsonld\n  - type: Spectral Rules\n    url: rules/tuya-rules.yml\n  - type: Vocabulary\n    url: vocabulary/tuya-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/apis.yml
tags:
- IoT
- Smart Home
- Devices
- Cloud Platform
- Automation
- Industrial IoT
- Device Management
url: https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/apis.yml
use_cases: []
---
