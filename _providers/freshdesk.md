---
api_count: 3
api_specs:
- filename: freshdesk-rest-api-openapi.yml
  format: yaml
  label: Freshdesk REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/openapi/freshdesk-rest-api-openapi.yml
- filename: freshdesk-webhook-api-asyncapi.yml
  format: yaml
  label: Freshdesk Webhook API
  slug: webhook-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/asyncapi/freshdesk-webhook-api-asyncapi.yml
apis:
- description: The Freshdesk REST API (v2) provides programmatic access to helpdesk data and operations within Freshdesk, a customer support platform by Freshworks. It exposes endpoints for managing tickets, contact
  name: Freshdesk REST API
  slug: rest-api
- description: The Freshdesk Webhook API enables real-time communication between Freshdesk and external systems by sending HTTP POST requests when specific events occur within the helpdesk. Webhooks can be triggered
  name: Freshdesk Webhook API
  slug: webhook-api
- description: 'The Freshdesk App SDK allows developers to build custom applications that extend the functionality of the Freshdesk helpdesk platform. Backed by a Platform-as-a-Service infrastructure that includes a '
  name: Freshdesk App SDK
  slug: app-sdk
asyncapis:
- description: The Freshdesk Webhook API enables real-time communication between Freshdesk and external systems by sending HTTP POST requests when specific events occur within the helpdesk. Webhooks can be triggered
  name: Freshdesk Webhook Events
  slug: freshdesk-webhook-api-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/freshdesk-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/freshdesk-ticket-schema.json
created: ''
description: Freshdesk API.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Freshdesk Context
  property_count: 8
  slug: freshdesk-context
layout: provider
modified: '2026-04-28'
name: freshdesk
skills: []
slug: freshdesk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: freshdesk\nurl: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/apis.yml\napis:\n  - aid: freshdesk:rest-api\n    name: Freshdesk REST API\n    tags:\n      - Agents\n      - Companies\n      - Contacts\n      - Customer Support\n      - Helpdesk\n      - Tickets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://yourdomain.freshdesk.com/api/v2\n    humanURL: https://developers.freshdesk.com/api/\n    properties:\n      - url: https://developers.freshdesk.com/api/\n        type: Documentation\n      - url: openapi/freshdesk-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Freshdesk REST API (v2) provides programmatic access to helpdesk data and\n      operations within Freshdesk, a customer support platform by Freshworks. It exposes\n      endpoints for managing tickets, contacts, companies, agents, groups, conversations,\n      products, email configurations,\
  \ SLA policies, and business hours. The API uses\n      JSON for request and response payloads, supports API key-based authentication,\n      and follows RESTful conventions for CRUD operations.\n  - aid: freshdesk:webhook-api\n    name: Freshdesk Webhook API\n    tags:\n      - Automation\n      - Customer Support\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://support.freshdesk.com/support/solutions/folders/272646\n    properties:\n      - url: https://support.freshdesk.com/support/solutions/folders/272646\n        type: Documentation\n      - url: asyncapi/freshdesk-webhook-api-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Freshdesk Webhook API enables real-time communication between Freshdesk\n      and external systems by sending HTTP POST requests when specific events occur\n      within the helpdesk. Webhooks\
  \ can be triggered by ticket creation, updates,\n      status changes, and other support events, allowing developers to build event-driven\n      integrations without polling the REST API.\n  - aid: freshdesk:app-sdk\n    name: Freshdesk App SDK\n    tags:\n      - Apps\n      - Extensions\n      - Marketplace\n      - Plugins\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developers.freshdesk.com/\n    properties:\n      - url: https://developers.freshdesk.com/\n        type: Documentation\n      - url: https://developers.freshworks.com/docs/app-sdk/v3.0/support_ticket/rest-apis/\n        type: Documentation\n    description: >-\n      The Freshdesk App SDK allows developers to build custom applications that extend\n      the functionality of the Freshdesk helpdesk platform. Backed by a Platform-as-a-Service\n      infrastructure that includes a data store and serverless runtimes,\
  \ the SDK provides\n      tools for creating front-end interfaces using the Crayons component library\n      and server-side logic through serverless apps.\ncommon:\n  - type: JSON-LD\n    url: json-ld/freshdesk-context.jsonld\n  - type: JSONSchema\n    url: json-schema/freshdesk-ticket-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Freshdesk API.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/apis.yml
use_cases: []
---
