---
api_count: 3
api_specs:
- filename: trello-rest-api-openapi.yml
  format: yaml
  label: Trello REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/openapi/trello-rest-api-openapi.yml
- filename: trello-webhooks-asyncapi.yml
  format: yaml
  label: Trello Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/asyncapi/trello-webhooks-asyncapi.yml
apis:
- description: The Trello REST API provides programmatic access to Trello boards, lists, cards, members, labels, checklists, and other resources that make up the Trello project management platform. Developers can cr
  name: Trello REST API
  slug: rest-api
- description: The Trello Webhooks API allows developers to receive real-time notifications when changes occur on Trello models such as boards, lists, and cards. Rather than polling the REST API for updates, webhook
  name: Trello Webhooks API
  slug: webhooks-api
- description: Trello Power-Ups are a framework for extending and integrating with the Trello platform. Power-Ups allow developers to add custom functionality to Trello boards, including custom fields, board buttons
  name: Trello Power-Ups
  slug: power-ups
asyncapis:
- description: The Trello Webhooks API delivers real-time notifications when changes occur on Trello models such as boards, lists, cards, and members. Rather than polling the REST API for updates, webhooks push even
  name: Trello Webhooks Events
  slug: trello-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/trello-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/trello-board-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trello-card-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trello-webhook-payload-schema.json
created: ''
description: Trello is a web-based, kanban-style, list-making application that allows users to organize tasks, projects, and workflows using boards, lists, and cards.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Trello Context
  property_count: 13
  slug: trello-context
layout: provider
modified: '2026-03-20'
name: trello
skills: []
slug: trello
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trello\nurl: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: trello:rest-api\n    name: Trello REST API\n    tags:\n      - Atlassian\n      - Boards\n      - Cards\n      - Collaboration\n      - Kanban\n      - Project Management\n      - Task Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trello.com\n    humanURL: https://developer.atlassian.com/cloud/trello/rest/\n    properties:\n      - url: https://developer.atlassian.com/cloud/trello/rest/\n        type: Documentation\n      - url: openapi/trello-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trello REST API provides programmatic access to Trello boards, lists,\n      cards, members, labels, checklists, and other resources that make up the\n      Trello project management platform. Developers can create, read, update,\n      and delete\
  \ Trello objects, manage team collaboration workflows, and\n      automate task management processes. The API uses key and token based\n      authentication and returns JSON responses for all endpoints.\n  - aid: trello:webhooks-api\n    name: Trello Webhooks API\n    tags:\n      - Events\n      - Notifications\n      - Real-Time\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trello.com\n    humanURL: https://developer.atlassian.com/cloud/trello/guides/rest-api/webhooks/\n    properties:\n      - url: https://developer.atlassian.com/cloud/trello/guides/rest-api/webhooks/\n        type: Documentation\n      - url: asyncapi/trello-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Trello Webhooks API allows developers to receive real-time\n      notifications when changes occur on Trello models such as boards, lists,\n      and cards. Rather than polling the REST API for updates,\
  \ webhooks push\n      event data to a specified callback URL via HTTP POST requests containing\n      JSON payloads. Webhook requests are signed with HMAC-SHA1 for\n      verification, and webhooks are scoped to the permissions of the token\n      used to create them.\n  - aid: trello:power-ups\n    name: Trello Power-Ups\n    tags:\n      - Customization\n      - Extensions\n      - Integrations\n      - Plugins\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.atlassian.com/cloud/trello/power-ups/\n    properties:\n      - url: https://developer.atlassian.com/cloud/trello/power-ups/\n        type: Documentation\n    description: >-\n      Trello Power-Ups are a framework for extending and integrating with the\n      Trello platform. Power-Ups allow developers to add custom functionality\n      to Trello boards, including custom fields, board buttons, card buttons,\n      card\
  \ badges, and card detail sections. The Power-Up framework provides a\n      client library with utilities and helpers for interacting with the Trello\n      interface, managing authorization, and accessing the REST API from within\n      the Power-Up context.\ncommon:\n  - type: JSON-LD\n    url: json-ld/trello-context.jsonld\n  - type: JSONSchema\n    url: json-schema/trello-board-schema.json\n  - type: JSONSchema\n    url: json-schema/trello-card-schema.json\n  - type: JSONSchema\n    url: json-schema/trello-webhook-payload-schema.json\ndescription: >-\n  Trello is a web-based, kanban-style, list-making application that allows users to\n  organize tasks, projects, and workflows using boards, lists, and cards.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/trello/refs/heads/main/apis.yml
use_cases: []
---
