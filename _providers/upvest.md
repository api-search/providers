---
api_count: 1
api_specs:
- filename: upvest-investment-api-openapi.yml
  format: yaml
  label: Upvest Investment API
  slug: investment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/openapi/upvest-investment-api-openapi.yml
apis:
- description: The Upvest Investment API provides a unified interface for building embedded investment experiences. It supports placing and managing orders, creating portfolios, configuring savings plans, handling s
  name: Upvest Investment API
  slug: investment-api
asyncapis:
- description: The Upvest Investment API uses an asynchronous, event-driven architecture where events represent state changes within the system. Webhook subscriptions allow your application to receive real-time noti
  name: Upvest Investment Events
  slug: upvest-investment-events-asyncapi
common:
- title: ''
  type: Website
  url: https://upvest.co/
- title: ''
  type: Portal
  url: https://upvest.co/developers
- title: ''
  type: Documentation
  url: https://docs.upvest.co/
- title: ''
  type: Blog
  url: https://upvest.co/blog/investment-api-docs
- title: ''
  type: Sign Up
  url: https://upvest.co/
- title: ''
  type: JSON-LD
  url: json-ld/upvest-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/upvest-webhook-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/upvest-order-schema.json
created: '2026-03-24'
description: Upvest is a Berlin-based API-first investment infrastructure provider that enables banks, brokers, and wealth managers to build and launch investment experiences through a single modular API. Founded in 2017, Upvest is a regulated securities institution in Europe and the UK, covering trading, custody, and back-office operations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Upvest Context
  property_count: 10
  slug: upvest-context
layout: provider
modified: '2026-03-24'
name: Upvest
skills: []
slug: upvest
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: upvest\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml\nname: Upvest\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking Infrastructure\n  - Fintech\n  - Investments\n  - Securities\ndescription: >-\n  Upvest is a Berlin-based API-first investment infrastructure provider that enables\n  banks, brokers, and wealth managers to build and launch investment experiences through\n  a single modular API. Founded in 2017, Upvest is a regulated securities institution\n  in Europe and the UK, covering trading, custody, and back-office operations.\ncreated: '2026-03-24'\nmodified: '2026-03-24'\nspecificationVersion: '0.19'\napis:\n  - aid: upvest:investment-api\n    name: Upvest Investment API\n    tags:\n      - Custody\n      - Investments\n      - Orders\n      - Portfolios\n      - Securities\n      - Trading\n    humanURL: https://docs.upvest.co/\n    baseURL: https://api.upvest.co\n\
  \    properties:\n      - url: https://docs.upvest.co/api\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/upvest-investment-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/upvest-investment-events-asyncapi.yml\n    description: >-\n      The Upvest Investment API provides a unified interface for building embedded\n      investment experiences. It supports placing and managing orders, creating portfolios,\n      configuring savings plans, handling securities transfers, and managing user\n      accounts and positions. The API covers the full order lifecycle with asynchronous\n      processing and webhook notifications for real-time event handling.\ncommon:\n  - type: Website\n    url: https://upvest.co/\n  - type: Portal\n    url: https://upvest.co/developers\n  - type: Documentation\n    url: https://docs.upvest.co/\n  - type: Blog\n    url: https://upvest.co/blog/investment-api-docs\n  - type: Sign Up\n    url: https://upvest.co/\n  - type: JSON-LD\n\
  \    url: json-ld/upvest-context.jsonld\n  - type: JSONSchema\n    url: json-schema/upvest-webhook-event-schema.json\n  - type: JSONSchema\n    url: json-schema/upvest-order-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml
tags:
- Banking Infrastructure
- Fintech
- Investments
- Securities
url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml
use_cases: []
---
