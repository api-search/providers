---
api_count: 3
api_specs:
- filename: calendly-scheduling-api-openapi.yml
  format: yaml
  label: Calendly Scheduling API
  slug: scheduling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/openapi/calendly-scheduling-api-openapi.yml
- filename: calendly-webhook-api-asyncapi.yml
  format: yaml
  label: Calendly Webhook API
  slug: webhook-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/asyncapi/calendly-webhook-api-asyncapi.yml
apis:
- description: The Calendly Scheduling API (v2) is a RESTful API that allows developers to programmatically manage scheduling workflows. It provides endpoints for managing users, organizations, event types, schedule
  name: Calendly Scheduling API
  slug: scheduling-api
- description: 'The Calendly Webhook API enables developers to receive real-time notifications when scheduling events occur in Calendly. By creating webhook subscriptions, applications can automatically receive data '
  name: Calendly Webhook API
  slug: webhook-api
- description: 'The Calendly Embed API allows developers to integrate Calendly scheduling pages directly into their websites and applications. It supports inline embeds, popup widgets, and popup text options, giving '
  name: Calendly Embed API
  slug: embed-api
asyncapis:
- description: 'The Calendly Webhook API enables developers to receive real-time notifications when scheduling events occur in Calendly. By creating webhook subscriptions, applications can automatically receive data '
  name: Calendly Webhook Events
  slug: calendly-webhook-api-asyncapi
common:
- title: ''
  type: Portal
  url: https://developer.calendly.com/
- title: ''
  type: Documentation
  url: https://developer.calendly.com/api-docs
- title: ''
  type: Website
  url: https://calendly.com/
- title: ''
  type: Privacy Policy
  url: https://calendly.com/privacy
- title: ''
  type: Terms of Service
  url: https://calendly.com/terms
- title: ''
  type: Blog
  url: https://calendly.com/blog
- title: ''
  type: Login
  url: https://calendly.com/login
- title: ''
  type: JSON-LD
  url: json-ld/calendly-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/calendly-event-type-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/calendly-scheduled-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/calendly-invitee-schema.json
created: '2026-03-20'
description: Calendly is a scheduling automation platform that helps individuals, teams, and organizations automate the meeting lifecycle by removing the back-and-forth of scheduling. Their developer platform provides APIs for programmatically managing scheduling workflows, receiving real-time event notifications via webhooks, and embedding scheduling interfaces directly into third-party applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Calendly Context
  property_count: 9
  slug: calendly-context
layout: provider
modified: '2026-04-23'
name: Calendly
skills: []
slug: calendly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: calendly\nname: Calendly\nurl: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n  - Appointments\n  - Automation\n  - Booking\n  - Calendars\n  - Meetings\n  - Scheduling\ncreated: '2026-03-20'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  Calendly is a scheduling automation platform that helps individuals, teams, and\n  organizations automate the meeting lifecycle by removing the back-and-forth of\n  scheduling. Their developer platform provides APIs for programmatically managing\n  scheduling workflows, receiving real-time event notifications via webhooks, and\n  embedding scheduling interfaces directly into third-party applications.\napis:\n  - aid: calendly:scheduling-api\n    name: Calendly Scheduling API\n    tags:\n      - Appointments\n      - Automation\n      - Booking\n      - Calendars\n      -\
  \ Meetings\n      - Scheduling\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.calendly.com\n    humanURL: https://developer.calendly.com/api-docs\n    properties:\n      - url: https://developer.calendly.com/api-docs\n        type: Documentation\n      - url: openapi/calendly-scheduling-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Calendly Scheduling API (v2) is a RESTful API that allows developers to\n      programmatically manage scheduling workflows. It provides endpoints for managing\n      users, organizations, event types, scheduled events, invitees, and routing forms.\n      The API uses JSON for request and response bodies, standard HTTP methods, and\n      supports authentication via personal access tokens and OAuth 2.1.\n  - aid: calendly:webhook-api\n    name: Calendly Webhook API\n    tags:\n      - Events\n      - Notifications\n      - Scheduling\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.calendly.com\n    humanURL: https://developer.calendly.com/api-docs\n    properties:\n      - url: https://developer.calendly.com/api-docs\n        type: Documentation\n      - url: asyncapi/calendly-webhook-api-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Calendly Webhook API enables developers to receive real-time\n      notifications when scheduling events occur in Calendly. By creating\n      webhook subscriptions, applications can automatically receive data\n      whenever invitees schedule, cancel, or reschedule meetings. This\n      eliminates the need for polling the API and allows for event-driven\n      integrations that respond immediately to changes in scheduling activity.\n  - aid: calendly:embed-api\n    name: Calendly Embed API\n    tags:\n      - Embedding\n      - Scheduling\n      - Web Components\n      - Widgets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n\
  \    humanURL: https://developer.calendly.com/\n    properties:\n      - url: https://developer.calendly.com/\n        type: Documentation\n    description: >-\n      The Calendly Embed API allows developers to integrate Calendly scheduling\n      pages directly into their websites and applications. It supports inline\n      embeds, popup widgets, and popup text options, giving developers\n      flexibility in how they present scheduling interfaces to users. The Embed\n      API enables customization of the embedded experience and provides\n      JavaScript callbacks for tracking when events are scheduled, allowing\n      seamless integration of Calendly booking flows within third-party\n      applications.\ncommon:\n  - type: Portal\n    url: https://developer.calendly.com/\n  - type: Documentation\n    url: https://developer.calendly.com/api-docs\n  - type: Website\n    url: https://calendly.com/\n  - type: Privacy Policy\n    url: https://calendly.com/privacy\n  - type: Terms of Service\n\
  \    url: https://calendly.com/terms\n  - type: Blog\n    url: https://calendly.com/blog\n  - type: Login\n    url: https://calendly.com/login\n  - type: JSON-LD\n    url: json-ld/calendly-context.jsonld\n  - type: JSONSchema\n    url: json-schema/calendly-event-type-schema.json\n  - type: JSONSchema\n    url: json-schema/calendly-scheduled-event-schema.json\n  - type: JSONSchema\n    url: json-schema/calendly-invitee-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/apis.yml
tags:
- Appointments
- Automation
- Booking
- Calendars
- Meetings
- Scheduling
url: https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/apis.yml
use_cases: []
---
