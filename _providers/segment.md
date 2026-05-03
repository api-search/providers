---
api_count: 5
api_specs:
- filename: segment-public-api-openapi.yml
  format: yaml
  label: Segment Public API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-public-api-openapi.yml
- filename: segment-http-tracking-api-openapi.yml
  format: yaml
  label: Segment HTTP Tracking API
  slug: http-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-http-tracking-api-openapi.yml
- filename: segment-profile-api-openapi.yml
  format: yaml
  label: Segment Profile API
  slug: profile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-profile-api-openapi.yml
- filename: segment-config-api-openapi.yml
  format: yaml
  label: Segment Config API
  slug: config-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-config-api-openapi.yml
- filename: segment-pixel-tracking-api-openapi.yml
  format: yaml
  label: Segment Pixel Tracking API
  slug: pixel-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/openapi/segment-pixel-tracking-api-openapi.yml
apis:
- description: 'The Segment Public API allows developers to programmatically manage Segment workspaces and their resources. It supports full CRUD operations for sources, destinations, warehouses, tracking plans, and '
  name: Segment Public API
  slug: public-api
- description: The Segment HTTP Tracking API enables developers to record analytics data from any website or application by sending HTTP requests directly to Segment servers. It supports identify, track, page, scree
  name: Segment HTTP Tracking API
  slug: http-tracking-api
- description: The Segment Profile API provides a single endpoint to read user-level and account-level customer data from Segment Unify. Developers can query the entire user or account object programmatically, inclu
  name: Segment Profile API
  slug: profile-api
- description: The Segment Config API allows programmatic management of Segment workspaces, sources, destinations, and other configuration resources. It provides endpoints to list workspace sources and destinations,
  name: Segment Config API
  slug: config-api
- description: 'The Segment Pixel Tracking API provides a way to collect analytics data using image pixel requests, which is useful in environments where JavaScript cannot execute, such as email clients. It supports '
  name: Segment Pixel Tracking API
  slug: pixel-tracking-api
asyncapis:
- description: 'Segment Webhooks submit real-time user data to HTTP endpoints as POST requests. When configured as a destination, Segment forwards identify, track, page, screen, group, and alias events to up to five '
  name: Segment Webhook Events
  slug: segment-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/segment-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/segment-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/segment-source-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/segment-destination-schema.json
created: ''
description: Segment is a customer data platform that helps companies collect, clean, and route customer data to hundreds of tools used for analytics, marketing, and data warehousing.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Segment Context
  property_count: 9
  slug: segment-context
layout: provider
modified: '2026-03-20'
name: segment
skills: []
slug: segment
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: segment\nurl: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: segment:public-api\n    name: Segment Public API\n    tags:\n      - Analytics\n      - Customer Data\n      - Destinations\n      - Sources\n      - Workspace Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.segmentapis.com\n    humanURL: https://docs.segmentapis.com/\n    properties:\n      - url: https://docs.segmentapis.com/\n        type: Documentation\n      - url: openapi/segment-public-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Segment Public API allows developers to programmatically manage\n      Segment workspaces and their resources. It supports full CRUD operations\n      for sources, destinations, warehouses, tracking plans, and catalog\n      entries. The API follows REST conventions with standard HTTP methods and\n   \
  \   predictable resource-oriented URLs. It is available for Team and Business\n      tier customers and is the recommended API going forward, replacing the\n      older Config API.\n  - aid: segment:http-tracking-api\n    name: Segment HTTP Tracking API\n    tags:\n      - Analytics\n      - Customer Data\n      - Events\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.segment.io\n    humanURL: https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api\n    properties:\n      - url: https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api\n        type: Documentation\n      - url: openapi/segment-http-tracking-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/segment-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Segment HTTP Tracking API enables developers to record analytics\n      data from any website\
  \ or application by sending HTTP requests directly\n      to Segment servers. It supports identify, track, page, screen, group,\n      and alias calls, and Segment routes the collected data to configured\n      destinations. The API accepts batch requests up to 500 KB and requires\n      each payload to include a userId or anonymousId. It is a server-side\n      alternative to Segment's client-side SDKs.\n  - aid: segment:profile-api\n    name: Segment Profile API\n    tags:\n      - Customer Data\n      - Identity Resolution\n      - Profiles\n      - Unify\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://profiles.segment.com\n    humanURL: https://www.twilio.com/docs/segment/unify/profile-api\n    properties:\n      - url: https://www.twilio.com/docs/segment/unify/profile-api\n        type: Documentation\n      - url: openapi/segment-profile-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Segment Profile\
  \ API provides a single endpoint to read user-level\n      and account-level customer data from Segment Unify. Developers can\n      query the entire user or account object programmatically, including\n      external IDs, traits, and events that make up a user's journey. The\n      API uses basic authentication and typically delivers p95 response times\n      under 200ms for the traits endpoint. It is commonly used for real-time\n      personalization and customer data retrieval.\n  - aid: segment:config-api\n    name: Segment Config API\n    tags:\n      - Configuration\n      - Destinations\n      - Legacy\n      - Sources\n      - Workspace Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://platform.segmentapis.com\n    humanURL: https://www.twilio.com/docs/segment/api/config-api\n    properties:\n      - url: https://www.twilio.com/docs/segment/api/config-api\n        type: Documentation\n      - url: openapi/segment-config-api-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Segment Config API allows programmatic management of Segment\n      workspaces, sources, destinations, and other configuration resources.\n      It provides endpoints to list workspace sources and destinations, create\n      or delete destinations, and manage tracking plans. As of early 2024,\n      Segment has stopped issuing new Config API tokens and recommends\n      migrating to the Public API for access to the latest features. The\n      Config API remains functional for existing users but is no longer\n      actively developed.\n  - aid: segment:pixel-tracking-api\n    name: Segment Pixel Tracking API\n    tags:\n      - Analytics\n      - Email\n      - Pixel\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.segment.io\n    humanURL: https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api\n    properties:\n\
  \      - url: https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api\n        type: Documentation\n      - url: openapi/segment-pixel-tracking-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Segment Pixel Tracking API provides a way to collect analytics\n      data using image pixel requests, which is useful in environments where\n      JavaScript cannot execute, such as email clients. It supports identify,\n      track, page, screen, group, and alias calls through pixel endpoints\n      under the api.segment.io domain. This API is particularly suited for\n      tracking email opens, ad impressions, and other contexts where\n      embedding a tracking pixel is the only viable data collection method.\ncommon:\n  - type: JSON-LD\n    url: json-ld/segment-context.jsonld\n  - type: JSONSchema\n    url: json-schema/segment-event-schema.json\n  - type: JSONSchema\n    url: json-schema/segment-source-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/segment-destination-schema.json\ndescription: >-\n  Segment is a customer data platform that helps companies collect, clean, and route\n  customer data to hundreds of tools used for analytics, marketing, and data warehousing.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml
use_cases: []
---
