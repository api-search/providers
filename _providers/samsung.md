---
api_count: 7
api_specs:
- filename: samsung-smartthings-openapi.yml
  format: yaml
  label: SmartThings API
  slug: smartthings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/samsung/refs/heads/main/openapi/samsung-smartthings-openapi.yml
apis:
- description: The SmartThings REST API provides programmatic access to the SmartThings platform for controlling connected devices, creating automations, managing locations, and building smart home integrations. Sup
  name: SmartThings API
  slug: smartthings
- description: 'Samsung Knox provides enterprise-grade device management and security APIs. Knox Cloud APIs enable programmatic access to Knox Deployment Program, Knox Mobile Enrollment, Knox Configure, Knox Manage, '
  name: Knox Cloud APIs
  slug: knox-cloud
- description: 'The Samsung Health SDK enables developers to create health and fitness applications for Galaxy Watch and smartphones, providing access to health data including steps, heart rate, sleep, workouts, and '
  name: Samsung Health SDK
  slug: health-sdk
- description: Samsung Galaxy mobile SDKs provide access to device-specific hardware and software features including S Pen Remote, DeX desktop mode, AR Emoji, foldable device optimization, Samsung Blockchain, eSE (e
  name: Galaxy Mobile SDKs
  slug: galaxy-mobile
- description: The Samsung Smart TV developer platform enables development of Tizen-based applications for Samsung Smart TVs, including access to TV-specific APIs for media playback, user interface, smart signage, h
  name: Samsung Smart TV SDK
  slug: smart-tv
- description: The Bixby developer platform allows developers to integrate Samsung's voice assistant into their applications and create custom Bixby capsules (skills) that respond to natural language commands across
  name: Bixby Developer API
  slug: bixby
- description: Samsung Wallet API allows developers to add digital passes, tickets, boarding passes, loyalty cards, coupons, and payment cards to the Samsung Wallet app on Galaxy devices.
  name: Samsung Wallet API
  slug: samsung-wallet
capabilities:
- description: Smart home control and automation workflow capability using the Samsung SmartThings REST API. Provides unified access to connected device control, location and room management, scene activation, and a
  name: Samsung SmartThings Smart Home Control
  slug: smart-home-control
common:
- title: Samsung Developer Portal
  type: Documentation
  url: https://developer.samsung.com/
- title: Samsung Knox Developer Documentation
  type: Documentation
  url: https://docs.samsungknox.com/dev/
- title: SmartThings Developer Documentation
  type: Documentation
  url: https://developer.smartthings.com/docs/
- title: SmartThings Community GitHub
  type: GitHubOrganization
  url: https://github.com/SmartThingsCommunity
- title: Samsung GitHub Organization
  type: GitHubOrganization
  url: https://github.com/samsung
- title: Samsung API Spectral Rules
  type: SpectralRules
  url: rules/samsung-rules.yml
- title: Samsung SmartThings Smart Home Control Capability
  type: NaftikoCapability
  url: capabilities/smart-home-control.yaml
- title: Samsung SmartThings Device Schema
  type: JSONSchema
  url: json-schema/samsung-smartthings-device-schema.json
- title: Samsung SmartThings Device Structure
  type: JSONStructure
  url: json-structure/samsung-smartthings-device-structure.json
- title: Samsung JSON-LD Context
  type: JSONLDContext
  url: json-ld/samsung-context.jsonld
- title: Samsung SmartThings List Devices Example
  type: Example
  url: examples/samsung-list-devices-example.json
- title: Samsung SmartThings Execute Device Command Example
  type: Example
  url: examples/samsung-execute-device-command-example.json
- title: Samsung Developer Vocabulary
  type: Vocabulary
  url: vocabulary/samsung-vocabulary.yml
created: '2025-02-08'
description: Samsung Electronics is a global technology leader offering developer platforms for building applications and services across mobile devices, IoT, smart home, enterprise security, and entertainment. The Samsung Developer ecosystem spans SmartThings (IoT and smart home platform), Knox (enterprise device security and management), Galaxy mobile SDKs, Smart TV, and Tizen cross-platform development. Samsung provides REST APIs, SDKs, and tools that enable developers to create connected experiences for hundreds of millions of Galaxy devices and Samsung smart home products worldwide.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 43
  name: Samsung Context
  property_count: 0
  slug: samsung-context
layout: provider
modified: '2026-05-02'
name: Samsung
rules:
- name: Samsung API Rules
  rule_count: 13
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 9
  slug: samsung-rules
skills: []
slug: samsung
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: samsung\nname: Samsung\ndescription: >-\n  Samsung Electronics is a global technology leader offering developer platforms\n  for building applications and services across mobile devices, IoT, smart home,\n  enterprise security, and entertainment. The Samsung Developer ecosystem spans\n  SmartThings (IoT and smart home platform), Knox (enterprise device security and\n  management), Galaxy mobile SDKs, Smart TV, and Tizen cross-platform development.\n  Samsung provides REST APIs, SDKs, and tools that enable developers to create\n  connected experiences for hundreds of millions of Galaxy devices and Samsung\n  smart home products worldwide.\nurl: https://developer.samsung.com/\ntags:\n  - Consumer Electronics\n  - Developer Platform\n  - IoT\n  - Mobile\n  - Smart Home\n  - Smart TV\n  - Wearables\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2025-02-08'\nmodified: '2026-05-02'\n\
  specificationVersion: '0.19'\napis:\n  - aid: samsung:smartthings\n    name: SmartThings API\n    description: >-\n      The SmartThings REST API provides programmatic access to the SmartThings\n      platform for controlling connected devices, creating automations, managing\n      locations, and building smart home integrations. Supports OAuth 2.0 and\n      personal access tokens. Base URL: https://api.smartthings.com/v1.\n    humanURL: https://developer.smartthings.com/\n    baseURL: https://api.smartthings.com/v1\n    tags:\n      - Automations\n      - Connected Devices\n      - IoT\n      - Locations\n      - Rules\n      - Scenes\n      - Smart Home\n      - SmartThings\n    properties:\n      - type: Documentation\n        url: https://developer.smartthings.com/docs/\n      - type: Documentation\n        url: https://developer.smartthings.com/docs/api/public\n      - type: OpenAPI\n        url: openapi/samsung-smartthings-openapi.yml\n  - aid: samsung:knox-cloud\n    name: Knox\
  \ Cloud APIs\n    description: >-\n      Samsung Knox provides enterprise-grade device management and security APIs.\n      Knox Cloud APIs enable programmatic access to Knox Deployment Program,\n      Knox Mobile Enrollment, Knox Configure, Knox Manage, Knox E-FOTA, Knox Guard,\n      Knox Asset Intelligence, and Knox MSP Portal for enterprise device lifecycle\n      management.\n    humanURL: https://docs.samsungknox.com/dev/\n    tags:\n      - Device Management\n      - Enterprise\n      - Knox\n      - MDM\n      - Mobile Device Management\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.samsungknox.com/dev/\n      - type: Documentation\n        url: https://developer.samsungknox.com/develop\n  - aid: samsung:health-sdk\n    name: Samsung Health SDK\n    description: >-\n      The Samsung Health SDK enables developers to create health and fitness\n      applications for Galaxy Watch and smartphones, providing access to health\n      data including\
  \ steps, heart rate, sleep, workouts, and body measurements.\n    humanURL: https://developer.samsung.com/health\n    tags:\n      - Fitness\n      - Galaxy Watch\n      - Health\n      - Wearables\n    properties:\n      - type: Documentation\n        url: https://developer.samsung.com/health\n  - aid: samsung:galaxy-mobile\n    name: Galaxy Mobile SDKs\n    description: >-\n      Samsung Galaxy mobile SDKs provide access to device-specific hardware and\n      software features including S Pen Remote, DeX desktop mode, AR Emoji, foldable\n      device optimization, Samsung Blockchain, eSE (embedded secure element), TEEGRIS\n      trusted execution environment, and Galaxy Performance SDK.\n    humanURL: https://developer.samsung.com/\n    tags:\n      - Android\n      - Foldable\n      - Galaxy\n      - Mobile\n      - S Pen\n      - Samsung DeX\n    properties:\n      - type: Documentation\n        url: https://developer.samsung.com/\n  - aid: samsung:smart-tv\n    name: Samsung Smart\
  \ TV SDK\n    description: >-\n      The Samsung Smart TV developer platform enables development of Tizen-based\n      applications for Samsung Smart TVs, including access to TV-specific APIs\n      for media playback, user interface, smart signage, hospitality displays,\n      and TV input management.\n    humanURL: https://developer.samsung.com/smarttv\n    tags:\n      - Media\n      - Smart TV\n      - Streaming\n      - Tizen\n      - TV\n    properties:\n      - type: Documentation\n        url: https://developer.samsung.com/smarttv\n  - aid: samsung:bixby\n    name: Bixby Developer API\n    description: >-\n      The Bixby developer platform allows developers to integrate Samsung's voice\n      assistant into their applications and create custom Bixby capsules (skills)\n      that respond to natural language commands across Galaxy devices, Smart TVs,\n      and appliances.\n    humanURL: https://bixby.developer.samsung.com/\n    tags:\n      - AI\n      - Bixby\n      - Natural\
  \ Language Processing\n      - Voice Assistant\n    properties:\n      - type: Documentation\n        url: https://bixby.developer.samsung.com/\n  - aid: samsung:samsung-wallet\n    name: Samsung Wallet API\n    description: >-\n      Samsung Wallet API allows developers to add digital passes, tickets,\n      boarding passes, loyalty cards, coupons, and payment cards to the Samsung\n      Wallet app on Galaxy devices.\n    humanURL: https://developer.samsung.com/wallet\n    tags:\n      - Digital Wallet\n      - Loyalty\n      - Passes\n      - Payments\n      - Wallet\n    properties:\n      - type: Documentation\n        url: https://developer.samsung.com/wallet\ncommon:\n  - type: Documentation\n    url: https://developer.samsung.com/\n    title: Samsung Developer Portal\n  - type: Documentation\n    url: https://docs.samsungknox.com/dev/\n    title: Samsung Knox Developer Documentation\n  - type: Documentation\n    url: https://developer.smartthings.com/docs/\n    title: SmartThings\
  \ Developer Documentation\n  - type: GitHubOrganization\n    url: https://github.com/SmartThingsCommunity\n    title: SmartThings Community GitHub\n  - type: GitHubOrganization\n    url: https://github.com/samsung\n    title: Samsung GitHub Organization\n  - type: SpectralRules\n    url: rules/samsung-rules.yml\n    title: Samsung API Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/smart-home-control.yaml\n    title: Samsung SmartThings Smart Home Control Capability\n  - type: JSONSchema\n    url: json-schema/samsung-smartthings-device-schema.json\n    title: Samsung SmartThings Device Schema\n  - type: JSONStructure\n    url: json-structure/samsung-smartthings-device-structure.json\n    title: Samsung SmartThings Device Structure\n  - type: JSONLDContext\n    url: json-ld/samsung-context.jsonld\n    title: Samsung JSON-LD Context\n  - type: Example\n    url: examples/samsung-list-devices-example.json\n    title: Samsung SmartThings List Devices Example\n  - type: Example\n\
  \    url: examples/samsung-execute-device-command-example.json\n    title: Samsung SmartThings Execute Device Command Example\n  - type: Vocabulary\n    url: vocabulary/samsung-vocabulary.yml\n    title: Samsung Developer Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/samsung/refs/heads/main/apis.yml
tags:
- Consumer Electronics
- Developer Platform
- IoT
- Mobile
- Smart Home
- Smart TV
- Wearables
url: https://developer.samsung.com/
use_cases: []
---
