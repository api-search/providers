---
api_count: 3
apis:
- description: 'The CloudKit Web Services REST API is structured as /database/1/{container}/{environment}/{database}/{operation}, where database is one of public, private, or shared and environment is development or '
  name: CloudKit Web Services
  slug: web-services
- description: CloudKit JS is Apple's JavaScript SDK that wraps the CloudKit Web Services REST API for browser apps. It provides Sign in with Apple authentication, container/database/zone access, queries, record ope
  name: CloudKit JS
  slug: js
- description: The native CloudKit framework for iOS, iPadOS, macOS, tvOS, watchOS, and visionOS. Provides programmatic access to CloudKit containers, records, zones, subscriptions, and sharing. Out of band of the w
  name: CloudKit Framework
  slug: framework
capabilities:
- description: ''
  name: Cloudkit Records
  slug: cloudkit-records
common:
- title: ''
  type: Website
  url: https://www.icloud.com/
- title: ''
  type: Developer
  url: https://developer.apple.com/icloud/cloudkit/
- title: ''
  type: Documentation
  url: https://developer.apple.com/documentation/cloudkit
- title: ''
  type: Console
  url: https://icloud.developer.apple.com/dashboard/
- title: ''
  type: Privacy Policy
  url: https://www.apple.com/legal/privacy/
- title: ''
  type: JSON-LD
  url: json-ld/cloudkit-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudkit-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudkit-records.yaml
created: '2024-01-01'
description: Apple CloudKit is the cloud backend for iOS, iPadOS, macOS, tvOS, watchOS, visionOS, and the web. CloudKit Web Services is the public REST surface that lets non-Apple-platform clients (web apps, servers) read and write data into a CloudKit container's public, private, or shared database. The web service is hosted at api.apple-cloudkit.com and accepts either an API token (for end-user-authenticated access) or a server-to- server ECDSA key for backend access. Operations cover records, zones, subscriptions, assets, users, and database changes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudkit Context
  property_count: 8
  slug: cloudkit-context
layout: provider
modified: '2026-04-25'
name: Apple CloudKit
rules:
- name: Apple CloudKit API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 6
  slug: cloudkit-rules
skills: []
slug: cloudkit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudkit\nname: Apple CloudKit\ndescription: >-\n  Apple CloudKit is the cloud backend for iOS, iPadOS, macOS, tvOS,\n  watchOS, visionOS, and the web. CloudKit Web Services is the public REST\n  surface that lets non-Apple-platform clients (web apps, servers) read\n  and write data into a CloudKit container's public, private, or shared\n  database. The web service is hosted at api.apple-cloudkit.com and accepts\n  either an API token (for end-user-authenticated access) or a server-to-\n  server ECDSA key for backend access. Operations cover records,\n  zones, subscriptions, assets, users, and database changes.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloudkit/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-25'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n  - Apple\n  - Cloud Storage\n  - CloudKit\n  - Database\n  - iCloud\n  - Mobile\n\
  \  - Sync\n  - Web Services\napis:\n  - aid: cloudkit:web-services\n    name: CloudKit Web Services\n    tags:\n      - REST\n      - Records\n      - Zones\n      - Subscriptions\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.apple-cloudkit.com/database/1\n    humanURL: https://developer.apple.com/library/archive/documentation/DataManagement/Conceptual/CloudKitWebServicesReference/index.html\n    properties:\n      - url: https://developer.apple.com/library/archive/documentation/DataManagement/Conceptual/CloudKitWebServicesReference/index.html\n        type: Documentation\n      - url: https://developer.apple.com/library/archive/documentation/DataManagement/Conceptual/CloudKitWebServicesReference/SettingUpWebServices.html\n        type: Setup\n      - url: https://developer.apple.com/documentation/cloudkit/obtaining-an-api-token-for-an-icloud-container\n        type: API Tokens\n    description: >-\n      The CloudKit Web\
  \ Services REST API is structured as\n      /database/1/{container}/{environment}/{database}/{operation}, where\n      database is one of public, private, or shared and environment is\n      development or production. Operations include records lookup, query,\n      modify, delete, zone create/list/delete, subscription\n      create/list/delete, asset upload, user info and changes. Calls are\n      authenticated using an API token for user-authenticated access (with\n      ckWebAuthToken) or a server-to-server ECDSA key for backend access.\n  - aid: cloudkit:js\n    name: CloudKit JS\n    tags:\n      - JavaScript\n      - SDK\n      - Web\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.apple.com/documentation/cloudkitjs\n    properties:\n      - url: https://developer.apple.com/documentation/cloudkitjs\n        type: Documentation\n    description: >-\n      CloudKit JS is Apple's JavaScript SDK that wraps the CloudKit\
  \ Web\n      Services REST API for browser apps. It provides Sign in with Apple\n      authentication, container/database/zone access, queries, record\n      operations, subscriptions, and asset management.\n  - aid: cloudkit:framework\n    name: CloudKit Framework\n    tags:\n      - SDK\n      - Apple Platforms\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.apple.com/documentation/cloudkit\n    properties:\n      - url: https://developer.apple.com/documentation/cloudkit\n        type: Documentation\n    description: >-\n      The native CloudKit framework for iOS, iPadOS, macOS, tvOS, watchOS,\n      and visionOS. Provides programmatic access to CloudKit containers,\n      records, zones, subscriptions, and sharing. Out of band of the web\n      services REST surface but shares the same data model.\ncommon:\n  - type: Website\n    url: https://www.icloud.com/\n  - type: Developer\n    url: https://developer.apple.com/icloud/cloudkit/\n\
  \  - type: Documentation\n    url: https://developer.apple.com/documentation/cloudkit\n  - type: Console\n    url: https://icloud.developer.apple.com/dashboard/\n  - type: Privacy Policy\n    url: https://www.apple.com/legal/privacy/\n  - type: JSON-LD\n    url: json-ld/cloudkit-context.jsonld\n  - type: Spectral\n    url: rules/cloudkit-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudkit-records.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudkit/refs/heads/main/apis.yml
tags:
- Apple
- Cloud Storage
- CloudKit
- Database
- iCloud
- Mobile
- Sync
- Web Services
url: https://raw.githubusercontent.com/api-evangelist/cloudkit/refs/heads/main/apis.yml
use_cases: []
---
