---
api_count: 2
api_specs:
- filename: openapi
  format: yaml
  label: Roblox Open Cloud API
  slug: roblox-open-cloud-api
  spec_type: OpenAPI
  url: https://create.roblox.com/docs/cloud/reference/openapi
apis:
- description: The Roblox Engine API documents all classes, data types, enumerations, global functions, variables, and libraries available when scripting Roblox experiences in Luau. This is the primary reference for
  name: Roblox Engine API
  slug: roblox-engine-api
- description: The Roblox Open Cloud API is a REST API providing external programmatic access to Roblox platform resources. It supports experiences (universes), places, data stores, memory stores, users, groups, ass
  name: Roblox Open Cloud API
  slug: roblox-open-cloud-api
capabilities:
- description: Unified workflow capability for managing Roblox experiences using the Open Cloud API. Combines universe configuration, place publishing, data store management, cross-server messaging, player moderatio
  name: Roblox Experience Management
  slug: experience-management
common:
- title: ''
  type: Website
  url: https://www.roblox.com
- title: ''
  type: DeveloperPortal
  url: https://create.roblox.com
- title: ''
  type: Documentation
  url: https://create.roblox.com/docs
- title: ''
  type: DevForum
  url: https://devforum.roblox.com
- title: ''
  type: GitHub
  url: https://github.com/Roblox
- title: ''
  type: Blog
  url: https://blog.roblox.com
- title: ''
  type: PrivacyPolicy
  url: https://www.roblox.com/info/privacy
- title: ''
  type: TermsOfService
  url: https://en.help.roblox.com/hc/en-us/articles/115004647846
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-ld/roblox-engine-api-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/vocabulary/roblox-engine-api-vocabulary.yml
created: '2024-11-07'
description: Roblox provides a suite of developer APIs for building experiences on the Roblox platform. The Engine API documents all classes, data types, enumerations, functions, events, callbacks, and properties for in-experience scripting in Luau. The Open Cloud REST API provides external programmatic access to Roblox platform resources including experiences, places, data stores, users, groups, assets, messaging, and more. In March 2026 Roblox launched new unified Open Cloud reference documentation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Roblox Engine Api Context
  property_count: 0
  slug: roblox-engine-api-context
layout: provider
modified: '2026-05-02'
name: Roblox Engine API
rules:
- name: Roblox Engine API API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 4
    warn: 5
  slug: roblox-open-cloud-rules
skills: []
slug: roblox-engine-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: roblox-engine-api\nname: Roblox Engine API\ndescription: >-\n  Roblox provides a suite of developer APIs for building experiences on the\n  Roblox platform. The Engine API documents all classes, data types,\n  enumerations, functions, events, callbacks, and properties for in-experience\n  scripting in Luau. The Open Cloud REST API provides external programmatic\n  access to Roblox platform resources including experiences, places, data\n  stores, users, groups, assets, messaging, and more. In March 2026 Roblox\n  launched new unified Open Cloud reference documentation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Gaming\n  - Game Development\n  - Metaverse\n  - Roblox\n  - Open Cloud\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/apis.yml\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: roblox-engine-api:roblox-engine-api\n\
  \    name: Roblox Engine API\n    description: >-\n      The Roblox Engine API documents all classes, data types, enumerations,\n      global functions, variables, and libraries available when scripting\n      Roblox experiences in Luau. This is the primary reference for in-engine\n      development covering services, instances, and platform behaviors.\n    humanURL: https://create.roblox.com/docs/reference/engine\n    tags:\n      - Gaming\n      - Luau\n      - Scripting\n      - Engine\n    properties:\n      - type: Documentation\n        url: https://create.roblox.com/docs/reference/engine\n\n  - aid: roblox-engine-api:roblox-open-cloud-api\n    name: Roblox Open Cloud API\n    description: >-\n      The Roblox Open Cloud API is a REST API providing external programmatic\n      access to Roblox platform resources. It supports experiences (universes),\n      places, data stores, memory stores, users, groups, assets, messaging,\n      badges, game passes, and subscriptions. Authentication\
  \ uses API keys\n      scoped to specific resources. The API is organized into Open Cloud v2,\n      v1, and Legacy tiers.\n    humanURL: https://create.roblox.com/docs/cloud/reference\n    baseURL: https://apis.roblox.com\n    tags:\n      - Gaming\n      - Open Cloud\n      - REST API\n      - Data Stores\n      - Experiences\n      - Users\n      - Groups\n    properties:\n      - url: https://create.roblox.com/docs/cloud/reference\n        type: Documentation\n      - url: https://create.roblox.com/docs/cloud/reference/openapi\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/openapi/roblox-open-cloud-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/rules/roblox-open-cloud-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/capabilities/experience-management.yaml\n\
  \        type: NaftikoCapabilities\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-schema/roblox-universe-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-schema/roblox-user-schema.json\n        type: JSONSchema\n    contact:\n      - FN: Roblox Developer Relations\n        url: https://devforum.roblox.com\n    features:\n      - Experience Management\n      - Place Publishing\n      - Data Store Access\n      - Memory Store Operations\n      - User Management\n      - Group Management\n      - Asset Management\n      - Messaging Service\n      - Badge Management\n      - Game Pass Management\n      - Subscription Management\n      - Inventory Access\n    useCases:\n      - External automation of Roblox experiences\n      - Player data management\n      - Server-side economy and inventory\n      - Moderation tooling\n\
  \      - Community management\n      - Analytics integration\n    solutions:\n      - Game Development Platform\n      - Creator Tooling\n      - Developer Platform\n\ncommon:\n  - type: Website\n    url: https://www.roblox.com\n  - type: DeveloperPortal\n    url: https://create.roblox.com\n  - type: Documentation\n    url: https://create.roblox.com/docs\n  - type: DevForum\n    url: https://devforum.roblox.com\n  - type: GitHub\n    url: https://github.com/Roblox\n  - type: Blog\n    url: https://blog.roblox.com\n  - type: PrivacyPolicy\n    url: https://www.roblox.com/info/privacy\n  - type: TermsOfService\n    url: https://en.help.roblox.com/hc/en-us/articles/115004647846\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-ld/roblox-engine-api-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/vocabulary/roblox-engine-api-vocabulary.yml\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/apis.yml
tags:
- Gaming
- Game Development
- Metaverse
- Roblox
- Open Cloud
url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/apis.yml
use_cases: []
---
