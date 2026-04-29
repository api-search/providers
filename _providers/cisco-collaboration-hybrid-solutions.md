---
api_count: 7
apis:
- description: Core Webex platform APIs for messaging, meetings, teams, spaces, memberships, attachments, and webhooks.
  name: Webex APIs
  slug: webex-api
- description: Schedule, list, update, and cancel Webex meetings; manage participants, recordings, transcripts, and meeting templates.
  name: Webex Meetings API
  slug: webex-meetings
- description: Manage Webex Hybrid Calendar, Hybrid Call Service, Hybrid Message, Video Mesh nodes, and other connectors that bridge on-premises collaboration infrastructure to the Webex cloud.
  name: Webex Hybrid Services API
  slug: webex-hybrid-services
- description: Cloud calling capabilities including call control, dial plans, voicemail, voice portals, queues, hunt groups, and number provisioning.
  name: Webex Calling API
  slug: webex-calling
- description: Administer Webex organizations, users, licenses, audit events, and service settings programmatically.
  name: Control Hub API
  slug: control-hub
- description: Manage and control Webex Room and Desk Devices including remote configuration, status queries, and the device-side xAPI.
  name: Webex Devices API
  slug: webex-devices
- description: Create and manage Webex Webinars and large-format virtual events, including registration, panelists, and analytics.
  name: Webex Events API
  slug: webex-events
common:
- title: ''
  type: Portal
  url: https://developer.cisco.com/collaboration/
- title: ''
  type: Webex Developer Portal
  url: https://developer.webex.com/
- title: ''
  type: Getting Started
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/integrations
- title: ''
  type: Webhooks
  url: https://developer.webex.com/docs/api/guides/webhooks
- title: ''
  type: Change Log
  url: https://developer.webex.com/changelog
- title: ''
  type: Status
  url: https://status.webex.com/
- title: ''
  type: Community
  url: https://community.cisco.com/t5/collaboration-voice-and-video/bd-p/discussions-collaboration
- title: ''
  type: GitHub Organization
  url: https://github.com/WebexSamples
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-collaboration-context.jsonld
created: '2024-01-15'
description: APIs for Cisco's hybrid collaboration solutions that combine Webex cloud services with on-premises Unified Communications Manager (CUCM), Expressway, and supporting infrastructure. Hybrid Services let an organization keep calling, calendaring, and identity on-premises while using Webex for meetings, messaging, devices, and management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cisco Collaboration Context
  property_count: 7
  slug: cisco-collaboration-context
layout: provider
modified: '2026-04-23'
name: Cisco Collaboration Hybrid Solutions
skills: []
slug: cisco-collaboration-hybrid-solutions
solutions: []
source_filename: apis.yml
source_yaml: "aid: cisco-collaboration-hybrid-solutions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/apis.yml\nname: Cisco Collaboration Hybrid Solutions\ntags:\n  - Calling\n  - Collaboration\n  - Hybrid Cloud\n  - Meetings\n  - Messaging\n  - Unified Communications\n  - Webex\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-15'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  APIs for Cisco's hybrid collaboration solutions that combine Webex cloud\n  services with on-premises Unified Communications Manager (CUCM),\n  Expressway, and supporting infrastructure. Hybrid Services let an\n  organization keep calling, calendaring, and identity on-premises while\n  using Webex for meetings, messaging, devices, and management.\napis:\n  - aid: cisco-collaboration-hybrid-solutions:webex-api\n    name:\
  \ Webex APIs\n    tags:\n      - Collaboration\n      - Meetings\n      - Messaging\n      - Spaces\n      - Teams\n    humanURL: https://developer.webex.com/\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/getting-started\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n      - url: https://developer.webex.com/docs/integrations\n        type: Authentication\n      - url: https://developer.webex.com/docs/sdks\n        type: SDKs\n    description: >-\n      Core Webex platform APIs for messaging, meetings, teams, spaces,\n      memberships, attachments, and webhooks.\n  - aid: cisco-collaboration-hybrid-solutions:webex-meetings\n    name: Webex Meetings API\n    tags:\n      - Meetings\n      - Recordings\n      - Scheduling\n    humanURL: https://developer.cisco.com/docs/webex-meetings/\n    baseURL: https://webexapis.com/v1/meetings\n    properties:\n     \
  \ - url: https://developer.cisco.com/docs/webex-meetings/\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/meetings\n        type: Reference\n    description: >-\n      Schedule, list, update, and cancel Webex meetings; manage\n      participants, recordings, transcripts, and meeting templates.\n  - aid: cisco-collaboration-hybrid-solutions:webex-hybrid-services\n    name: Webex Hybrid Services API\n    tags:\n      - Calendar\n      - Connectors\n      - Hybrid\n      - Media\n    humanURL: https://developer.cisco.com/docs/webex-hybrid-services/\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.cisco.com/docs/webex-hybrid-services/\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/hybrid-clusters\n        type: Reference\n    description: >-\n      Manage Webex Hybrid Calendar, Hybrid Call Service, Hybrid Message,\n      Video Mesh nodes, and other connectors that bridge on-premises\n\
  \      collaboration infrastructure to the Webex cloud.\n  - aid: cisco-collaboration-hybrid-solutions:webex-calling\n    name: Webex Calling API\n    tags:\n      - Call Control\n      - Calling\n      - Telephony\n      - Voicemail\n    humanURL: https://developer.webex.com/docs/api/v1/webex-calling\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/webex-calling\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/call-controls\n        type: Reference\n    description: >-\n      Cloud calling capabilities including call control, dial plans,\n      voicemail, voice portals, queues, hunt groups, and number\n      provisioning.\n  - aid: cisco-collaboration-hybrid-solutions:control-hub\n    name: Control Hub API\n    tags:\n      - Administration\n      - Management\n      - Organizations\n      - Users\n    humanURL: https://developer.webex.com/docs/api/v1/organizations\n    baseURL: https://webexapis.com/v1\n\
  \    properties:\n      - url: https://developer.webex.com/docs/api/v1/organizations\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/admin-audit-events\n        type: Reference\n    description: >-\n      Administer Webex organizations, users, licenses, audit events, and\n      service settings programmatically.\n  - aid: cisco-collaboration-hybrid-solutions:webex-devices\n    name: Webex Devices API\n    tags:\n      - Devices\n      - Endpoints\n      - Room Systems\n    humanURL: https://developer.webex.com/docs/api/v1/devices\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/devices\n        type: Documentation\n      - url: https://roomos.cisco.com/xapi\n        type: xAPI Reference\n    description: >-\n      Manage and control Webex Room and Desk Devices including remote\n      configuration, status queries, and the device-side xAPI.\n  - aid: cisco-collaboration-hybrid-solutions:webex-events\n\
  \    name: Webex Events API\n    tags:\n      - Events\n      - Virtual Events\n      - Webinars\n    humanURL: https://developer.webex.com/docs/api/v1/events\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/events\n        type: Documentation\n    description: >-\n      Create and manage Webex Webinars and large-format virtual events,\n      including registration, panelists, and analytics.\ncommon:\n  - type: Portal\n    url: https://developer.cisco.com/collaboration/\n  - type: Webex Developer Portal\n    url: https://developer.webex.com/\n  - type: Getting Started\n    url: https://developer.webex.com/docs/getting-started\n  - type: Authentication\n    url: https://developer.webex.com/docs/integrations\n  - type: Webhooks\n    url: https://developer.webex.com/docs/api/guides/webhooks\n  - type: Change Log\n    url: https://developer.webex.com/changelog\n  - type: Status\n    url: https://status.webex.com/\n  - type: Community\n\
  \    url: https://community.cisco.com/t5/collaboration-voice-and-video/bd-p/discussions-collaboration\n  - type: GitHub Organization\n    url: https://github.com/WebexSamples\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\n  - type: JSON-LD\n    url: json-ld/cisco-collaboration-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/apis.yml
tags:
- Calling
- Collaboration
- Hybrid Cloud
- Meetings
- Messaging
- Unified Communications
- Webex
url: https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/apis.yml
use_cases: []
---
