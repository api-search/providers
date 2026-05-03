---
api_count: 3
api_specs:
- filename: rainbow-application-openapi.yml
  format: yaml
  label: Rainbow Application Portal API
  slug: rainbow-application-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-application-openapi.yml
- filename: rainbow-messaging-openapi.yml
  format: yaml
  label: Rainbow Messaging API
  slug: rainbow-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-messaging-openapi.yml
- filename: rainbow-contacts-openapi.yml
  format: yaml
  label: Rainbow Contacts API
  slug: rainbow-contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/openapi/rainbow-contacts-openapi.yml
apis:
- description: The Rainbow Application Portal REST API allows developers to manage Rainbow applications, register OAuth clients, and access provisioning and administration functions for the Rainbow platform.
  name: Rainbow Application Portal API
  slug: rainbow-application-api
- description: REST API for sending and receiving messages, managing conversations, and handling chat bubbles (group rooms) within the Rainbow platform.
  name: Rainbow Messaging API
  slug: rainbow-messaging-api
- description: REST API for searching, listing, and managing contacts in the Rainbow directory, including enterprise contacts and public profiles.
  name: Rainbow Contacts API
  slug: rainbow-contacts-api
capabilities:
- description: Unified communications platform capability combining Rainbow CPaaS messaging, contacts, and directory. Used by developers building enterprise communication applications with chat, group collaboration,
  name: Rainbow Communications Platform
  slug: communications-platform
common:
- title: ''
  type: Website
  url: https://www.openrainbow.com
- title: ''
  type: Developer
  url: https://developers.openrainbow.com/
- title: ''
  type: SignUp
  url: https://hub.openrainbow.com/
- title: ''
  type: GitHub
  url: https://github.com/Rainbow-CPaaS
- title: ''
  type: SDKNode
  url: https://github.com/Rainbow-CPaaS/Rainbow-Node-SDK
- title: ''
  type: SDKIOS
  url: https://github.com/Rainbow-CPaaS/Rainbow-iOS-SDK
- title: ''
  type: SDKCS
  url: https://github.com/Rainbow-CPaaS/Rainbow-CSharp-SDK-Samples
- title: ''
  type: CLI
  url: https://github.com/Rainbow-CPaaS/Rainbow-CLI-SDK
- title: ''
  type: SpectralRules
  url: rules/rainbow-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/communications-platform.yaml
- title: ''
  type: JSONLD
  url: json-ld/rainbow-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rainbow-vocabulary.yml
created: '2025-02-06'
description: Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets developers enrich applications with chat, group chat, voice, video, file sharing, and telephony PBX features through more than 200 APIs, REST interfaces, and multi-language SDKs including Node.js, C#, iOS, and Android.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Rainbow Context
  property_count: 10
  slug: rainbow-context
layout: provider
modified: '2026-05-02'
name: Rainbow
rules:
- name: Rainbow API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: rainbow-rules
skills: []
slug: rainbow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rainbow\nname: Rainbow\ndescription: >-\n  Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets\n  developers enrich applications with chat, group chat, voice, video, file\n  sharing, and telephony PBX features through more than 200 APIs, REST\n  interfaces, and multi-language SDKs including Node.js, C#, iOS, and Android.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Communications\n  - CPaaS\n  - Chat\n  - Voice\n  - Video\n  - Telephony\n  - Messaging\n  - Collaboration\n  - Unified Communications\ncreated: '2025-02-06'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: rainbow:rainbow-application-api\n    name: Rainbow Application Portal API\n    description: >-\n      The Rainbow Application Portal REST API allows developers to manage\n\
  \      Rainbow applications, register OAuth clients, and access provisioning\n      and administration functions for the Rainbow platform.\n    humanURL: https://developers.openrainbow.com/doc/hub/api\n    baseURL: https://openrainbow.com/api/rainbow\n    tags:\n      - Applications\n      - Administration\n      - OAuth\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://developers.openrainbow.com/doc/hub/api\n      - type: OpenAPI\n        url: openapi/rainbow-application-openapi.yml\n  - aid: rainbow:rainbow-messaging-api\n    name: Rainbow Messaging API\n    description: >-\n      REST API for sending and receiving messages, managing conversations,\n      and handling chat bubbles (group rooms) within the Rainbow platform.\n    humanURL: https://developers.openrainbow.com/\n    baseURL: https://openrainbow.com/api/rainbow\n    tags:\n      - Messaging\n      - Chat\n      - Conversations\n      - Bubbles\n    properties:\n      - type: Documentation\n\
  \        url: https://developers.openrainbow.com/doc/hub/api\n      - type: OpenAPI\n        url: openapi/rainbow-messaging-openapi.yml\n  - aid: rainbow:rainbow-contacts-api\n    name: Rainbow Contacts API\n    description: >-\n      REST API for searching, listing, and managing contacts in the Rainbow\n      directory, including enterprise contacts and public profiles.\n    humanURL: https://developers.openrainbow.com/\n    baseURL: https://openrainbow.com/api/rainbow\n    tags:\n      - Contacts\n      - Directory\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developers.openrainbow.com/doc/hub/api\n      - type: OpenAPI\n        url: openapi/rainbow-contacts-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.openrainbow.com\n  - type: Developer\n    url: https://developers.openrainbow.com/\n  - type: SignUp\n    url: https://hub.openrainbow.com/\n  - type: GitHub\n    url: https://github.com/Rainbow-CPaaS\n  - type: SDKNode\n    url:\
  \ https://github.com/Rainbow-CPaaS/Rainbow-Node-SDK\n  - type: SDKIOS\n    url: https://github.com/Rainbow-CPaaS/Rainbow-iOS-SDK\n  - type: SDKCS\n    url: https://github.com/Rainbow-CPaaS/Rainbow-CSharp-SDK-Samples\n  - type: CLI\n    url: https://github.com/Rainbow-CPaaS/Rainbow-CLI-SDK\n  - type: SpectralRules\n    url: rules/rainbow-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/communications-platform.yaml\n  - type: JSONLD\n    url: json-ld/rainbow-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/rainbow-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/apis.yml
tags:
- Communications
- CPaaS
- Chat
- Voice
- Video
- Telephony
- Messaging
- Collaboration
- Unified Communications
url: https://raw.githubusercontent.com/api-evangelist/rainbow/refs/heads/main/apis.yml
use_cases: []
---
