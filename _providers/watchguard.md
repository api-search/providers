---
api_count: 2
api_specs:
- filename: watchguard-cloud-platform-openapi.yml
  format: yaml
  label: WatchGuard Cloud Platform API
  slug: watchguard-cloud-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/openapi/watchguard-cloud-platform-openapi.yml
- filename: watchguard-endpoint-security-openapi.yml
  format: yaml
  label: WatchGuard Endpoint Security Management API
  slug: watchguard-endpoint-security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/openapi/watchguard-endpoint-security-openapi.yml
apis:
- description: RESTful API for managing WatchGuard Cloud accounts, sub-accounts, and users. Provides account creation and management, audience token generation for managed account access, hardware/license activation
  name: WatchGuard Cloud Platform API
  slug: watchguard-cloud-platform-api
- description: RESTful API for managing WatchGuard Endpoint Security (WES) devices and security operations. Provides device listing and protection status, device isolation and release, immediate scan initiation, sec
  name: WatchGuard Endpoint Security Management API
  slug: watchguard-endpoint-security-api
capabilities:
- description: Unified threat response capability combining WatchGuard Cloud Platform account management with Endpoint Security device management, security event monitoring, and risk assessment. Designed for securit
  name: WatchGuard Endpoint Threat Response
  slug: endpoint-threat-response
common:
- title: ''
  type: Website
  url: https://www.watchguard.com
- title: ''
  type: Documentation
  url: https://www.watchguard.com/help/docs/API/
- title: ''
  type: Developer Portal
  url: https://developer.cloud.watchguard.com/
- title: ''
  type: Getting Started
  url: https://www.watchguard.com/help/docs/API/Content/en-US/api_get_started/get_started.html
- title: ''
  type: OpenAPI
  url: openapi/watchguard-cloud-platform-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/watchguard-endpoint-security-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/watchguard-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/watchguard-device-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/watchguard-device-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/watchguard-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/watchguard-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/endpoint-threat-response.yaml
created: '2025-02-17'
description: WatchGuard provides cloud-managed network and endpoint security solutions including Firebox next-generation firewalls, WatchGuard Endpoint Security (WES), AuthPoint multi-factor authentication, and WatchGuard Wi-Fi. WatchGuard Cloud is the unified management platform exposing RESTful APIs for account management, device activation, asset allocation, endpoint device management, security event monitoring, and operator administration.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Watchguard Context
  property_count: 19
  slug: watchguard-context
layout: provider
modified: '2026-05-03'
name: WatchGuard
rules:
- name: WatchGuard API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 0
    warning: 4
  slug: watchguard-rules
skills: []
slug: watchguard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: watchguard\nname: WatchGuard\ndescription: >-\n  WatchGuard provides cloud-managed network and endpoint security solutions\n  including Firebox next-generation firewalls, WatchGuard Endpoint Security (WES),\n  AuthPoint multi-factor authentication, and WatchGuard Wi-Fi. WatchGuard Cloud\n  is the unified management platform exposing RESTful APIs for account management,\n  device activation, asset allocation, endpoint device management, security event\n  monitoring, and operator administration.\nurl: https://www.watchguard.com\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Security\n  - Endpoint Security\n  - Firewall\n  - MFA\n  - Network Security\n  - Zero Trust\ncreated: '2025-02-17'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: watchguard:watchguard-cloud-platform-api\n    name: WatchGuard Cloud Platform API\n    description: >-\n      RESTful API for managing WatchGuard Cloud\
  \ accounts, sub-accounts, and\n      users. Provides account creation and management, audience token generation\n      for managed account access, hardware/license activation, asset allocation,\n      and operator management. Uses OAuth 2.0 bearer tokens and WatchGuard API Key\n      header authentication.\n    humanURL: https://www.watchguard.com/help/docs/API/Content/en-US/watchguard-cloud/watchguard-cloud.html\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://www.watchguard.com/help/docs/API/Content/en-US/watchguard-cloud/watchguard-cloud.html\n      - type: OpenAPI\n        url: openapi/watchguard-cloud-platform-openapi.yml\n      - type: SpectralRules\n        url: rules/watchguard-rules.yml\n    tags:\n      - Account Management\n      - Activation\n      - Allocation\n      - Operators\n      - Platform\n  - aid: watchguard:watchguard-endpoint-security-api\n    name: WatchGuard\
  \ Endpoint Security Management API\n    description: >-\n      RESTful API for managing WatchGuard Endpoint Security (WES) devices and\n      security operations. Provides device listing and protection status, device\n      isolation and release, immediate scan initiation, security event counters\n      and exports, security overview, risk assessment summaries, and configuration\n      management.\n    humanURL: https://www.watchguard.com/help/docs/API/Content/en-US/endpoint_security/WES_endpoint_security/v1/WES_endpoint_security.html\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://www.watchguard.com/help/docs/API/Content/en-US/endpoint_security/WES_endpoint_security/v1/WES_endpoint_security.html\n      - type: OpenAPI\n        url: openapi/watchguard-endpoint-security-openapi.yml\n    tags:\n      - Device Management\n      - Endpoint Security\n      - Incident Response\n      -\
  \ Risk Assessment\ncommon:\n  - type: Website\n    url: https://www.watchguard.com\n  - type: Documentation\n    url: https://www.watchguard.com/help/docs/API/\n  - type: Developer Portal\n    url: https://developer.cloud.watchguard.com/\n  - type: Getting Started\n    url: https://www.watchguard.com/help/docs/API/Content/en-US/api_get_started/get_started.html\n  - type: OpenAPI\n    url: openapi/watchguard-cloud-platform-openapi.yml\n  - type: OpenAPI\n    url: openapi/watchguard-endpoint-security-openapi.yml\n  - type: SpectralRules\n    url: rules/watchguard-rules.yml\n  - type: JSONSchema\n    url: json-schema/watchguard-device-schema.json\n  - type: JSONStructure\n    url: json-structure/watchguard-device-structure.json\n  - type: JSON-LD\n    url: json-ld/watchguard-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/watchguard-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/endpoint-threat-response.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/watchguard/refs/heads/main/apis.yml
tags:
- Cloud Security
- Endpoint Security
- Firewall
- MFA
- Network Security
- Zero Trust
url: https://www.watchguard.com
use_cases: []
---
