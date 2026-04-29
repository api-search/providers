---
api_count: 3
api_specs:
- filename: customer-io-track-api-openapi.yml
  format: yaml
  label: Customer.io Track API
  slug: track-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-track-api-openapi.yml
- filename: customer-io-app-api-openapi.yml
  format: yaml
  label: Customer.io App API
  slug: app-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-app-api-openapi.yml
- filename: customer-io-pipelines-api-openapi.yml
  format: yaml
  label: Customer.io Pipelines API
  slug: pipelines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/openapi/customer-io-pipelines-api-openapi.yml
apis:
- description: The Customer.io Track API allows developers to send behavioral data and customer profile information into Customer.io. It provides endpoints for identifying customers, tracking events, managing device
  name: Customer.io Track API
  slug: track-api
- description: The Customer.io App API enables developers to manage workspace resources and send messages programmatically. It provides endpoints for sending transactional messages, triggering broadcasts, managing c
  name: Customer.io App API
  slug: app-api
- description: The Customer.io Pipelines API is the newer data ingestion interface for getting customer and event data into Customer.io. It follows the Segment spec and supports identify, track, page, screen, group,
  name: Customer.io Pipelines API
  slug: pipelines-api
asyncapis:
- description: Customer.io Reporting Webhooks send real-time message activity events as JSON payloads via HTTP POST to a configured endpoint. These events include message sends, deliveries, opens, clicks, bounces, u
  name: Customer.io Reporting Webhooks
  slug: customer-io-reporting-webhooks-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://customer.io
- title: ''
  type: Documentation
  url: https://docs.customer.io
- title: ''
  type: AsyncAPI
  url: asyncapi/customer-io-reporting-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/customer-io-customer-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/customer-io-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/customer-io-webhook-payload-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/customer-io-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/customer-io-vocabulary.yml
- title: ''
  type: Rules
  url: rules/customer-io-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/customer-io-capabilities.yml
created: '2024-01-01'
description: Customer.io is a customer engagement platform that combines a customer data platform, marketing automation, and messaging delivery to send behavior-triggered email, push, SMS, and in-app messages. Its API surface includes the Track API for sending behavioral data and customer profile updates, the App API for managing workspace resources and sending transactional and broadcast messages, the Pipelines API which is a Segment-spec data ingestion interface, and outbound reporting webhooks that deliver message lifecycle events.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Customer Io Context
  property_count: 11
  slug: customer-io-context
layout: provider
modified: '2026-04-28'
name: Customer.io
rules:
- name: Customer.io API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: customer-io-rules
skills: []
slug: customer-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: customer-io\nurl: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/apis.yml\napis:\n  - aid: customer-io:track-api\n    name: Customer.io Track API\n    tags:\n      - Behavioral Data\n      - Customer Data\n      - Event Tracking\n      - Marketing Automation\n      - Messaging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://track.customer.io\n    humanURL: https://docs.customer.io/integrations/api/track/\n    properties:\n      - url: https://docs.customer.io/integrations/api/track/\n        type: Documentation\n      - url: openapi/customer-io-track-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Customer.io Track API allows developers to send behavioral data and customer\n      profile information into Customer.io. It provides endpoints for identifying\n      customers, tracking events, managing devices for push notifications, and sending\n      anonymous\
  \ events. The API uses basic authentication with a Site ID and API key,\n      and accepts JSON request bodies.\n  - aid: customer-io:app-api\n    name: Customer.io App API\n    tags:\n      - Broadcasts\n      - Campaigns\n      - Marketing Automation\n      - Messaging\n      - Segments\n      - Transactional Email\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.customer.io\n    humanURL: https://docs.customer.io/integrations/api/app/\n    properties:\n      - url: https://docs.customer.io/integrations/api/app/\n        type: Documentation\n      - url: openapi/customer-io-app-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Customer.io App API enables developers to manage workspace resources and\n      send messages programmatically. It provides endpoints for sending transactional\n      messages, triggering broadcasts, managing customers and segments, retrieving\n      campaign and newsletter data,\
  \ and exporting customer information.\n  - aid: customer-io:pipelines-api\n    name: Customer.io Pipelines API\n    tags:\n      - CDP\n      - Customer Data Platform\n      - Data Ingestion\n      - Marketing Automation\n      - Messaging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://cdp.customer.io\n    humanURL: https://docs.customer.io/integrations/data-in/connections/http-api/\n    properties:\n      - url: https://docs.customer.io/integrations/data-in/connections/http-api/\n        type: Documentation\n      - url: openapi/customer-io-pipelines-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Customer.io Pipelines API is the newer data ingestion interface for getting\n      customer and event data into Customer.io. It follows the Segment spec and supports\n      identify, track, page, screen, group, and alias calls. Customer.io recommends\n      the Pipelines API for new integrations because it is\
  \ easier to use, supports\n      outbound data integrations and transformations, and is the focus of ongoing\n      development.\ncommon:\n  - type: Website\n    url: https://customer.io\n  - type: Documentation\n    url: https://docs.customer.io\n  - type: AsyncAPI\n    url: asyncapi/customer-io-reporting-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/customer-io-customer-schema.json\n  - type: JSONSchema\n    url: json-schema/customer-io-event-schema.json\n  - type: JSONSchema\n    url: json-schema/customer-io-webhook-payload-schema.json\n  - type: JSON-LD\n    url: json-ld/customer-io-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/customer-io-vocabulary.yml\n  - type: Rules\n    url: rules/customer-io-rules.yml\n  - type: Capabilities\n    url: capabilities/customer-io-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.20'\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nname: Customer.io\ntags:\n\
  \  - Behavioral Data\n  - Broadcasts\n  - Campaigns\n  - CDP\n  - Customer Data\n  - Customer Data Platform\n  - Data Ingestion\n  - Email\n  - Event Tracking\n  - Marketing Automation\n  - Messaging\n  - Push Notifications\n  - Segments\n  - SMS\n  - Transactional Email\ndescription: >-\n  Customer.io is a customer engagement platform that combines a customer data platform,\n  marketing automation, and messaging delivery to send behavior-triggered email, push,\n  SMS, and in-app messages. Its API surface includes the Track API for sending behavioral\n  data and customer profile updates, the App API for managing workspace resources\n  and sending transactional and broadcast messages, the Pipelines API which is a\n  Segment-spec data ingestion interface, and outbound reporting webhooks that deliver\n  message lifecycle events.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/apis.yml
tags:
- Behavioral Data
- Broadcasts
- Campaigns
- CDP
- Customer Data
- Customer Data Platform
- Data Ingestion
- Email
- Event Tracking
- Marketing Automation
- Messaging
- Push Notifications
- Segments
- SMS
- Transactional Email
url: https://raw.githubusercontent.com/api-evangelist/customer-io/refs/heads/main/apis.yml
use_cases: []
---
