---
api_count: 3
api_specs:
- filename: marqeta-core-api-openapi.yml
  format: yaml
  label: Marqeta Core API
  slug: core-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/openapi/marqeta-core-api-openapi.yml
- filename: marqeta-diva-api-openapi.yml
  format: yaml
  label: Marqeta DiVA API
  slug: diva-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/openapi/marqeta-diva-api-openapi.yml
- filename: marqeta-webhooks-asyncapi.yml
  format: yaml
  label: Marqeta Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/asyncapi/marqeta-webhooks-asyncapi.yml
apis:
- description: The Marqeta Core API is a RESTful interface that enables developers to build and manage card payment programs programmatically. It provides endpoints for creating and managing cardholders, issuing phy
  name: Marqeta Core API
  slug: core-api
- description: 'The Marqeta DiVA (Data insights, Visualization, and Analytics) API is a RESTful interface that provides programmatic access to production data from a Marqeta card program. It surfaces the data behind '
  name: Marqeta DiVA API
  slug: diva-api
- description: Marqeta Webhooks deliver real-time event notifications to a developer- configured endpoint when specific events occur within a card program. Each program supports up to five active webhook configurati
  name: Marqeta Webhooks
  slug: webhooks
asyncapis:
- description: Marqeta delivers real-time event notifications to a developer-configured HTTPS endpoint when specific events occur within a card program. Each program supports up to five active webhook configurations
  name: Marqeta Webhooks
  slug: marqeta-webhooks-asyncapi
common:
- title: ''
  type: JSONSchema
  url: json-schema/marqeta-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/marqeta-cardholder-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/marqeta-card-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/marqeta-context.jsonld
created: ''
description: Marqeta is a modern card issuing platform that empowers innovators to build configurable payment cards and provides issuer processor services to power digital banking, financial services, and commerce.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Marqeta Context
  property_count: 13
  slug: marqeta-context
layout: provider
modified: '2026-04-28'
name: marqeta
skills: []
slug: marqeta
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: marqeta\nurl: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: marqeta:core-api\n    name: Marqeta Core API\n    tags:\n      - Card Issuing\n      - Fintech\n      - Payment Processing\n      - Payments\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://sandbox-api.marqeta.com/v3\n    humanURL: https://www.marqeta.com/docs/core-api/introduction\n    properties:\n      - url: https://www.marqeta.com/docs/core-api/introduction\n        type: Documentation\n      - url: openapi/marqeta-core-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Marqeta Core API is a RESTful interface that enables developers to build\n      and manage card payment programs programmatically. It provides endpoints for\n      creating and managing cardholders, issuing physical and virtual cards, defining\n      spending controls, and\
  \ retrieving transaction data. The API supports use cases\n      including prepaid cards, expense management, earned wage access, and buy now\n      pay later programs. Authentication uses HTTP Basic Auth, and the API communicates\n      using JSON over HTTPS.\n\n  - aid: marqeta:diva-api\n    name: Marqeta DiVA API\n    tags:\n      - Analytics\n      - Data\n      - Fintech\n      - Reporting\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://diva-api.marqeta.com/data/v2\n    humanURL: https://www.marqeta.com/docs/diva-api/introduction\n    properties:\n      - url: https://www.marqeta.com/docs/diva-api/introduction\n        type: Documentation\n      - url: openapi/marqeta-diva-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Marqeta DiVA (Data insights, Visualization, and Analytics) API is a RESTful\n      interface that provides programmatic access to production data from a Marqeta\n    \
  \  card program. It surfaces the data behind Marqeta's reporting and analytics\n      tools, enabling developers to retrieve large datasets in JSON or CSV format.\n      The API supports filtering, sorting, aggregation, and pagination for customized\n      responses.\n\n  - aid: marqeta:webhooks\n    name: Marqeta Webhooks\n    tags:\n      - Events\n      - Fintech\n      - Notifications\n      - Real-Time\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-server.example.com/webhooks\n    humanURL: https://www.marqeta.com/docs/developer-guides/webhooks-landing-page\n    properties:\n      - url: https://www.marqeta.com/docs/developer-guides/webhooks-landing-page\n        type: Documentation\n      - url: asyncapi/marqeta-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Marqeta Webhooks deliver real-time event notifications to a developer-\n      configured endpoint when specific events\
  \ occur within a card program. Each\n      program supports up to five active webhook configurations, and events cover\n      card transactions, authorizations, declines, and other platform activity.\n      Webhook payloads are delivered as HTTP POST requests in JSON format to the\n      receiving endpoint. This allows applications to respond immediately to card\n      activity without polling the Core API for updates.\n\ncommon:\n  - type: JSONSchema\n    url: json-schema/marqeta-transaction-schema.json\n  - type: JSONSchema\n    url: json-schema/marqeta-cardholder-schema.json\n  - type: JSONSchema\n    url: json-schema/marqeta-card-schema.json\n  - type: JSON-LD\n    url: json-ld/marqeta-context.jsonld\ndescription: >-\n  Marqeta is a modern card issuing platform that empowers innovators to build configurable\n  payment cards and provides issuer processor services to power digital banking, financial\n  services, and commerce.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/marqeta/refs/heads/main/apis.yml
use_cases: []
---
