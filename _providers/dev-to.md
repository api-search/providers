---
api_count: 2
api_specs:
- filename: dev-to-forem-api-openapi.yml
  format: yaml
  label: Dev.to Forem API
  slug: forem-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/openapi/dev-to-forem-api-openapi.yml
- filename: dev-to-webhooks-asyncapi.yml
  format: yaml
  label: Dev.to Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/asyncapi/dev-to-webhooks-asyncapi.yml
apis:
- description: The Dev.to Forem API (v1) is a RESTful API that provides programmatic access to the Dev.to developer community platform, which is built on the open-source Forem framework. The API enables developers t
  name: Dev.to Forem API
  slug: forem-api
- description: The Dev.to Webhooks API allows developers to subscribe to real-time notifications for events occurring on the Dev.to platform. By creating webhook subscriptions, applications can receive HTTP callback
  name: Dev.to Webhooks API
  slug: webhooks-api
asyncapis:
- description: The Dev.to Webhooks event-driven interface allows applications to receive real-time HTTP POST callbacks when specific events occur on the Dev.to platform. Webhook subscriptions are managed via the For
  name: Dev.to Webhooks Events
  slug: dev-to-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/dev-to-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/dev-to-article-schema.json
created: ''
description: Access Forem articles, users and other resources via API. For a real-world example of Forem in action, check out [DEV](https://www.dev.to). All endpoints can be accessed with the 'api-key' header and a accept header, but some of them are accessible publicly without authentication. Dates and date times, unless otherwise specified, must be in the [RFC 3339](https://tools.ietf.org/html/rfc3339) format.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Dev To Context
  property_count: 7
  slug: dev-to-context
layout: provider
modified: '2026-04-28'
name: dev-to
skills: []
slug: dev-to
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dev-to\nurl: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/apis.yml\napis:\n  - aid: dev-to:forem-api\n    name: Dev.to Forem API\n    tags:\n      - Articles\n      - Blogging\n      - Content Management\n      - Developer Community\n      - Social\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://dev.to/api\n    humanURL: https://developers.forem.com/api/v1\n    properties:\n      - url: https://developers.forem.com/api/v1\n        type: Documentation\n      - url: openapi/dev-to-forem-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Dev.to Forem API (v1) is a RESTful API that provides programmatic access\n      to the Dev.to developer community platform, which is built on the open-source\n      Forem framework. The API enables developers to create, read, update, and manage\n      articles (blog posts, discussions, help threads), comments, users, organizations,\n\
  \      tags, followers, listings, and webhooks. It uses API key authentication, requires\n      an accept header of application/vnd.forem.api-v1+json, and returns JSON responses.\n  - aid: dev-to:webhooks-api\n    name: Dev.to Webhooks API\n    tags:\n      - Automation\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://dev.to/api\n    humanURL: https://developers.forem.com/api/v1\n    properties:\n      - url: https://developers.forem.com/api/v1\n        type: Documentation\n      - url: asyncapi/dev-to-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Dev.to Webhooks API allows developers to subscribe to real-time\n      notifications for events occurring on the Dev.to platform. By creating\n      webhook subscriptions, applications can receive HTTP callbacks when\n      specific events happen, such as new articles being published. This\n    \
  \  enables event-driven integrations and automation workflows that respond\n      immediately to activity on the platform without the need to continuously\n      poll the REST API for changes.\ncommon:\n  - type: JSON-LD\n    url: json-ld/dev-to-context.jsonld\n  - type: JSONSchema\n    url: json-schema/dev-to-article-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Access Forem articles, users and other resources via API. For a real-world example\n  of Forem in action, check out [DEV](https://www.dev.to). All endpoints can be accessed\n  with the 'api-key' header and a accept header, but some of them are accessible publicly\n  without authentication. Dates and date times, unless otherwise specified, must be\n  in the [RFC 3339](https://tools.ietf.org/html/rfc3339) format.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/apis.yml
use_cases: []
---
