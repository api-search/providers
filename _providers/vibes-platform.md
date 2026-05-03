---
api_count: 2
api_specs:
- filename: vibes-platform-openapi.yml
  format: yaml
  label: Vibes Platform API
  slug: vibes-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/openapi/vibes-platform-openapi.yml
- filename: vibes-connect-openapi.yml
  format: yaml
  label: Vibes Connect API
  slug: vibes-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/openapi/vibes-connect-openapi.yml
apis:
- description: The Vibes Platform API provides programmatic access to broadcast messaging (SMS and push notifications), acquisition workflows, subscription list management, wallet pass management, and event-triggere
  name: Vibes Platform API
  slug: vibes-platform-api
- description: 'Vibes Connect provides aggregation-layer APIs for sending and receiving SMS and MMS messages via HTTP calls. Three APIs are offered: the HTTP Message API for SMS, the SMPP Gateway API for persistent S'
  name: Vibes Connect API
  slug: vibes-connect-api
capabilities:
- description: Unified mobile messaging capability combining the Vibes Platform API and Vibes Connect API for end-to-end mobile engagement workflows. Covers SMS/MMS sending, broadcast campaign management, push notif
  name: Vibes Mobile Messaging
  slug: mobile-messaging
common:
- title: ''
  type: Portal
  url: https://developer-platform.vibes.com/
- title: ''
  type: Documentation
  url: https://developer-platform.vibes.com/reference/our-apis
- title: ''
  type: Portal
  url: https://developer-aggregation.vibes.com
- title: ''
  type: Portal
  url: https://developer-rbm.vibes.com/
- title: ''
  type: Website
  url: https://www.vibes.com/
created: '2024-11-14'
description: Vibes is a mobile engagement platform that provides APIs for SMS messaging, push notifications, RCS for Business, and mobile marketing campaigns. The platform APIs support broadcast messaging, event-triggered messages, acquisition workflows, subscription list management, wallet pass management, and callback notifications for opt-ins and delivery status. Vibes operates as a Tier 1 provider with direct carrier connections in the US and Canada.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Vibes Platform Context
  property_count: 4
  slug: vibes-platform-context
layout: provider
modified: '2026-05-03'
name: Vibes Platform
rules:
- name: Vibes Platform API Rules
  rule_count: 13
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 11
  slug: vibes-platform-rules
skills: []
slug: vibes-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vibes-platform\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/apis.yml\napis:\n  - aid: vibes-platform:vibes-platform-api\n    name: Vibes Platform API\n    tags:\n      - Mobile Marketing\n      - Push Notifications\n      - SMS\n      - Broadcast\n      - Acquisition\n      - Subscription Management\n      - Wallet Passes\n    humanURL: https://developer-platform.vibes.com/\n    baseURL: https://public-api.vibescm.com\n    properties:\n      - url: https://developer-platform.vibes.com/reference/our-apis\n        type: Documentation\n      - url: https://developer-platform.vibes.com/reference/broadcast-api-1\n        type: Reference\n      - url: https://developer-platform.vibes.com/reference/acquisition-campaign-api-1\n        type: Reference\n      - url: https://developer-platform.vibes.com/reference/subscription-list-api\n        type: Reference\n      - url: https://developer-platform.vibes.com/reference/callbacks\n  \
  \      type: Reference\n      - url: https://developer-platform.vibes.com/reference/technical-details\n        type: Reference\n      - url: openapi/vibes-platform-openapi.yml\n        type: OpenAPI\n      - url: rules/vibes-platform-rules.yml\n        type: SpectralRuleset\n    description: >-\n      The Vibes Platform API provides programmatic access to broadcast messaging\n      (SMS and push notifications), acquisition workflows, subscription list\n      management, wallet pass management, and event-triggered message capabilities.\n      Broadcasts are delivered to subscribers within your mobile contact book.\n      Authentication uses HTTP Basic Auth with Base64-encoded credentials.\n      The US environment base URL is https://public-api.vibescm.com and the EU\n      environment base URL is https://public-api.eu.vibes.com.\n  - aid: vibes-platform:vibes-connect-api\n    name: Vibes Connect API\n    tags:\n      - SMS\n      - MMS\n      - Aggregation\n      - Messaging\n      - Mobile\n\
  \    humanURL: https://developer-aggregation.vibes.com\n    baseURL: https://messageapi.vibesapps.com\n    properties:\n      - url: https://developer-aggregation.vibes.com\n        type: Documentation\n      - url: https://developer-aggregation.vibes.com/reference/http-message-api\n        type: Reference\n      - url: openapi/vibes-connect-openapi.yml\n        type: OpenAPI\n    description: >-\n      Vibes Connect provides aggregation-layer APIs for sending and receiving\n      SMS and MMS messages via HTTP calls. Three APIs are offered: the HTTP\n      Message API for SMS, the SMPP Gateway API for persistent SMPP bindings,\n      and the MMS Message API using MM7 Protocol. Vibes is a Tier 1 provider\n      with direct connections to Verizon, AT&T, T-Mobile, and regional carriers.\n      US SMS endpoint: https://messageapi.vibesapps.com; US MMS endpoint:\n      https://messageapi-mms.vibesapps.com.\nname: Vibes Platform\ntags:\n  - Mobile Marketing\n  - Mobile Messaging\n  - Push Notifications\n\
  \  - SMS\n  - MMS\n  - Broadcast Messaging\n  - Acquisition Campaigns\n  - Subscription Management\n  - Wallet Passes\n  - RCS\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  Vibes is a mobile engagement platform that provides APIs for SMS messaging,\n  push notifications, RCS for Business, and mobile marketing campaigns. The\n  platform APIs support broadcast messaging, event-triggered messages,\n  acquisition workflows, subscription list management, wallet pass management,\n  and callback notifications for opt-ins and delivery status. Vibes operates\n  as a Tier 1 provider with direct carrier connections in the US and Canada.\ncommon:\n  - url: https://developer-platform.vibes.com/\n    name: Vibes Platform Developer Portal\n    type: Portal\n    description: Primary developer portal for Vibes Platform APIs.\n  - url: https://developer-platform.vibes.com/reference/our-apis\n\
  \    name: Our APIs - Vibes Platform\n    type: Documentation\n    description: Overview of all Vibes Platform APIs.\n  - url: https://developer-aggregation.vibes.com\n    name: Vibes Connect Developer Portal\n    type: Portal\n    description: Developer portal for Vibes Connect aggregation APIs (SMS/MMS).\n  - url: https://developer-rbm.vibes.com/\n    name: Vibes RCS for Business Developer Portal\n    type: Portal\n    description: Developer portal for Vibes RCS for Business (Rich Communication Services).\n  - url: https://www.vibes.com/\n    name: Vibes - Mobile Engagement Platform\n    type: Website\n    description: Official website for Vibes mobile engagement platform.\n  - url: https://www.vibes.com/platform/integrations\n    name: Vibes Platform Integrations\n    type: Integrations\n    description: Integration partners and connectors for the Vibes platform.\nfeatures:\n  - Broadcast SMS and MMS messaging\n  - Push notification delivery\n  - Acquisition campaign management\n  -\
  \ Subscription list management\n  - Wallet pass creation and management\n  - Event-triggered messages\n  - File-triggered messages\n  - Callback registrations for opt-in and delivery status\n  - RCS for Business (Rich Communication Services)\n  - Rate limiting with 429 Too Many Requests responses\n  - US and EU environment support\n  - HTTP Basic Authentication\n  - Direct Tier 1 carrier connections (AT&T, Verizon, T-Mobile)\nintegrations:\n  - Salesforce Marketing Cloud\n  - Adobe Campaign\n  - Oracle Eloqua\n  - Marketo\nartifacts:\n  - url: openapi/vibes-platform-openapi.yml\n    type: OpenAPI\n    name: Vibes Platform OpenAPI\n  - url: openapi/vibes-connect-openapi.yml\n    type: OpenAPI\n    name: Vibes Connect OpenAPI\n  - url: rules/vibes-platform-rules.yml\n    type: SpectralRuleset\n    name: Vibes Platform Spectral Rules\n  - url: capabilities/mobile-messaging.yaml\n    type: NaftikoCapability\n    name: Vibes Mobile Messaging Capability\n  - url: capabilities/shared/vibes-platform.yaml\n\
  \    type: NaftikoCapability\n    name: Vibes Platform Shared Capability\n  - url: capabilities/shared/vibes-connect.yaml\n    type: NaftikoCapability\n    name: Vibes Connect Shared Capability\n  - url: json-schema/vibes-platform-broadcast-schema.json\n    type: JSONSchema\n    name: Broadcast Schema\n  - url: json-schema/vibes-platform-person-schema.json\n    type: JSONSchema\n    name: Person Schema\n  - url: json-schema/vibes-platform-subscription-list-schema.json\n    type: JSONSchema\n    name: Subscription List Schema\n  - url: json-ld/vibes-platform-context.jsonld\n    type: JSONLDContext\n    name: Vibes Platform JSON-LD Context\n  - url: vocabulary/vibes-platform-vocabulary.yml\n    type: Vocabulary\n    name: Vibes Platform Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/apis.yml
tags:
- Mobile Marketing
- Mobile Messaging
- Push Notifications
- SMS
- MMS
- Broadcast Messaging
- Acquisition Campaigns
- Subscription Management
- Wallet Passes
- RCS
url: https://raw.githubusercontent.com/api-evangelist/vibes-platform/refs/heads/main/apis.yml
use_cases: []
---
