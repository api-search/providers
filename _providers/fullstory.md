---
api_count: 5
api_specs:
- filename: fullstory-server-api-openapi.yml
  format: yaml
  label: FullStory Server API
  slug: server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-server-api-openapi.yml
- filename: fullstory-segments-export-api-openapi.yml
  format: yaml
  label: FullStory Segments Export API
  slug: segments-export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-segments-export-api-openapi.yml
- filename: fullstory-sessions-api-openapi.yml
  format: yaml
  label: FullStory Sessions API
  slug: sessions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-sessions-api-openapi.yml
- filename: fullstory-webhooks-api-openapi.yml
  format: yaml
  label: FullStory Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-webhooks-api-openapi.yml
apis:
- description: 'The FullStory Server API is a RESTful API that enables developers to programmatically send user and event data to FullStory. It supports creating and updating individual users, batch importing users, '
  name: FullStory Server API
  slug: server-api
- description: The FullStory Segments Export API provides an asynchronous workflow for downloading captured event data from FullStory. Developers can initiate export jobs to aggregate segment data, query for the sta
  name: FullStory Segments Export API
  slug: segments-export-api
- description: The FullStory Sessions API allows developers to retrieve session replay URLs for specific users. By querying with a user email address or user ID, the API returns a list of session URLs that can be us
  name: FullStory Sessions API
  slug: sessions-api
- description: The FullStory Webhooks API enables developers to create, update, retrieve, and manage webhook endpoints that receive real-time notifications from FullStory. Supported event types include segment creat
  name: FullStory Webhooks API
  slug: webhooks-api
- description: The FullStory Browser SDK is a JavaScript library that enables developers to manage FullStory data capture on websites, retrieve deep links to session replays, and send custom events. It provides func
  name: FullStory Browser SDK
  slug: browser-sdk
asyncapis:
- description: FullStory delivers real-time webhook notifications when specific events occur within the platform. Supported event types include segment creation, segment threshold alerts, custom event processing, an
  name: FullStory Webhook Events
  slug: fullstory-webhooks-asyncapi
common:
- title: ''
  type: Website
  url: https://www.fullstory.com/
- title: ''
  type: Portal
  url: https://developer.fullstory.com/
- title: ''
  type: Documentation
  url: https://developer.fullstory.com/server/getting-started/
- title: ''
  type: Login
  url: https://app.fullstory.com/login
- title: ''
  type: Support
  url: https://help.fullstory.com/
- title: ''
  type: Blog
  url: https://www.fullstory.com/blog/
- title: ''
  type: PrivacyPolicy
  url: https://www.fullstory.com/legal/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.fullstory.com/legal/terms-and-conditions/
- title: ''
  type: JSONLD
  url: json-ld/fullstory-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/fullstory-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fullstory-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fullstory-segment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fullstory-session-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fullstory-webhook-endpoint-schema.json
created: '2026-03-20'
description: FullStory is a digital experience intelligence platform that captures and analyzes user interactions across websites and mobile apps. The FullStory developer platform exposes server-side REST APIs for sending user and event data, exporting behavioral segments, retrieving session replay URLs, and managing webhook destinations, plus a Browser SDK for client-side data capture and custom events.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Fullstory Context
  property_count: 7
  slug: fullstory-context
layout: provider
modified: '2026-04-28'
name: FullStory
skills: []
slug: fullstory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fullstory\nname: FullStory\ndescription: >-\n  FullStory is a digital experience intelligence platform that captures and\n  analyzes user interactions across websites and mobile apps. The FullStory\n  developer platform exposes server-side REST APIs for sending user and event\n  data, exporting behavioral segments, retrieving session replay URLs, and\n  managing webhook destinations, plus a Browser SDK for client-side data\n  capture and custom events.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nposition: Consumer\nurl: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Digital Experience\n  - Session Replay\n  - Webhooks\n  - Data Export\napis:\n  - aid: fullstory:server-api\n    name: FullStory Server API\n    tags:\n      - Analytics\n      - Digital Experience\n\
  \      - Events\n      - Session Replay\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fullstory.com\n    humanURL: https://developer.fullstory.com/server/getting-started/\n    properties:\n      - url: https://developer.fullstory.com/server/getting-started/\n        type: Documentation\n      - url: openapi/fullstory-server-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FullStory Server API is a RESTful API that enables developers to\n      programmatically send user and event data to FullStory. It supports\n      creating and updating individual users, batch importing users, sending\n      server-side events, and batch importing events. The API uses JSON for\n      request and response bodies and authenticates via API keys. Developers\n      can use it to enrich FullStory session data with server-side context\n      that is not available in the browser or mobile app.\n  - aid: fullstory:segments-export-api\n\
  \    name: FullStory Segments Export API\n    tags:\n      - Analytics\n      - Data Export\n      - Digital Experience\n      - Segments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fullstory.com\n    humanURL: https://developer.fullstory.com/server/v1/segments/create-segment-export/\n    properties:\n      - url: https://developer.fullstory.com/server/v1/segments/create-segment-export/\n        type: Documentation\n      - url: openapi/fullstory-segments-export-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FullStory Segments Export API provides an asynchronous workflow for downloading\n      captured event data from FullStory. Developers can initiate export jobs to aggregate\n      segment data, query for the status of running jobs, and retrieve download URLs\n      for completed exports. Two types of segment data are available for export: individuals\n      matching a segment and events performed\
  \ by those individuals.\n  - aid: fullstory:sessions-api\n    name: FullStory Sessions API\n    tags:\n      - Analytics\n      - Digital Experience\n      - Session Replay\n      - Sessions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fullstory.com\n    humanURL: https://developer.fullstory.com/server/getting-started/\n    properties:\n      - url: https://developer.fullstory.com/server/getting-started/\n        type: Documentation\n      - url: openapi/fullstory-sessions-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FullStory Sessions API allows developers to retrieve session replay\n      URLs for specific users. By querying with a user email address or user\n      ID, the API returns a list of session URLs that can be used to view\n      recorded sessions in the FullStory platform. This is particularly useful\n      for building integrations that link customer support tickets, CRM records,\n\
  \      or other tools directly to relevant FullStory session replays.\n  - aid: fullstory:webhooks-api\n    name: FullStory Webhooks API\n    tags:\n      - Events\n      - Notifications\n      - Segments\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fullstory.com\n    humanURL: https://developer.fullstory.com/destinations/v1/webhooks/getting-started/\n    properties:\n      - url: https://developer.fullstory.com/destinations/v1/webhooks/getting-started/\n        type: Documentation\n      - url: openapi/fullstory-webhooks-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/fullstory-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The FullStory Webhooks API enables developers to create, update, retrieve,\n      and manage webhook endpoints that receive real-time notifications from\n      FullStory. Supported event types include segment creation, segment\n      threshold\
  \ alerts, and custom event notifications. Webhooks allow\n      event-driven integrations that respond immediately to behavioral signals\n      detected by FullStory, eliminating the need for polling and enabling\n      automated workflows based on user activity patterns.\n  - aid: fullstory:browser-sdk\n    name: FullStory Browser SDK\n    tags:\n      - Browser\n      - Custom Events\n      - Data Capture\n      - JavaScript\n      - Session Replay\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.fullstory.com/browser/getting-started/\n    properties:\n      - url: https://developer.fullstory.com/browser/getting-started/\n        type: Documentation\n      - url: https://www.npmjs.com/package/@fullstory/browser\n        type: Distribution\n    description: >-\n      The FullStory Browser SDK is a JavaScript library that enables developers to\n      manage FullStory data capture on websites, retrieve deep links to\
  \ session replays,\n      and send custom events. It provides functions for identifying users, setting\n      user properties, tracking custom events with the FS.event API, and generating\n      session replay URLs for integration with other platforms.\ncommon:\n  - type: Website\n    url: https://www.fullstory.com/\n  - type: Portal\n    url: https://developer.fullstory.com/\n  - type: Documentation\n    url: https://developer.fullstory.com/server/getting-started/\n  - type: Login\n    url: https://app.fullstory.com/login\n  - type: Support\n    url: https://help.fullstory.com/\n  - type: Blog\n    url: https://www.fullstory.com/blog/\n  - type: PrivacyPolicy\n    url: https://www.fullstory.com/legal/privacy-policy/\n  - type: TermsOfService\n    url: https://www.fullstory.com/legal/terms-and-conditions/\n  - type: JSONLD\n    url: json-ld/fullstory-context.jsonld\n  - type: JSONSchema\n    url: json-schema/fullstory-user-schema.json\n  - type: JSONSchema\n    url: json-schema/fullstory-event-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/fullstory-segment-schema.json\n  - type: JSONSchema\n    url: json-schema/fullstory-session-schema.json\n  - type: JSONSchema\n    url: json-schema/fullstory-webhook-endpoint-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/apis.yml
tags:
- Analytics
- Digital Experience
- Session Replay
- Webhooks
- Data Export
url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/apis.yml
use_cases: []
---
