---
api_count: 3
api_specs:
- filename: ticketmaster-discovery-openapi.yml
  format: yaml
  label: Ticketmaster Discovery API
  slug: ticketmaster-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/openapi/ticketmaster-discovery-openapi.yml
- filename: ticketmaster-commerce-openapi.yml
  format: yaml
  label: Ticketmaster Commerce API
  slug: ticketmaster-commerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/openapi/ticketmaster-commerce-openapi.yml
apis:
- description: The Ticketmaster Discovery API allows developers to search for events, attractions, venues, and classifications across the Ticketmaster platform. Provides access to over 230,000 events across the Unit
  name: Ticketmaster Discovery API
  slug: ticketmaster-discovery-api
- description: 'The Ticketmaster Commerce API enables developers to build ticket purchasing flows, retrieve event inventory, check seat availability, and manage ticket orders. Provides access to price ranges, ticket '
  name: Ticketmaster Commerce API
  slug: ticketmaster-commerce-api
- description: The Ticketmaster Partner API is a restricted API for authorized distribution partners that enables reserving, purchasing, and retrieving ticket and event information programmatically. Authentication u
  name: Ticketmaster Partner API
  slug: ticketmaster-partner-api
capabilities:
- description: Unified capability for event discovery applications, travel platforms, and entertainment apps to search and display live events, venues, and artists from Ticketmaster alongside ticket availability and
  name: Ticketmaster Event Discovery and Ticketing
  slug: event-discovery-and-ticketing
common:
- title: ''
  type: Portal
  url: https://developer.ticketmaster.com
- title: ''
  type: Documentation
  url: https://developer.ticketmaster.com/products-and-docs/
- title: ''
  type: Getting Started
  url: https://developer.ticketmaster.com/products-and-docs/apis/getting-started/
- title: ''
  type: API Explorer
  url: https://developer.ticketmaster.com/api-explorer/v2/
- title: ''
  type: Website
  url: https://www.ticketmaster.com
- title: ''
  type: Blog
  url: https://developer.ticketmaster.com/blog/
- title: ''
  type: Twitter
  url: https://twitter.com/ticketmaster
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/ticketmaster
- title: ''
  type: Terms of Service
  url: https://developer.ticketmaster.com/support/terms-of-use/
- title: ''
  type: Privacy Policy
  url: https://www.ticketmaster.com/h/privacy.html
- title: ''
  type: JSON-LD
  url: json-ld/ticketmaster-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/ticketmaster-event-schema.json
created: '2025-01-08'
description: Ticketmaster is the world's largest live entertainment ticketing company, providing access to tickets for concerts, sports, theater, and other live events globally. Their developer platform offers APIs for event discovery, ticket commerce, venue data, and partner integrations, giving developers access to over 230,000 events across dozens of countries.
features: []
image: https://www.ticketmaster.com/favicon.ico
integrations: []
jsonld:
- class_count: 31
  name: Ticketmaster Context
  property_count: 7
  slug: ticketmaster-context
layout: provider
modified: '2026-05-03'
name: Ticketmaster
rules:
- name: Ticketmaster API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 4
    warn: 4
  slug: ticketmaster-rules
skills: []
slug: ticketmaster
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ticketmaster\nurl: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/apis.yml\nname: Ticketmaster\ndescription: >-\n  Ticketmaster is the world's largest live entertainment ticketing company,\n  providing access to tickets for concerts, sports, theater, and other live\n  events globally. Their developer platform offers APIs for event discovery,\n  ticket commerce, venue data, and partner integrations, giving developers\n  access to over 230,000 events across dozens of countries.\nimage: https://www.ticketmaster.com/favicon.ico\ntags:\n  - Commerce\n  - Concerts\n  - Entertainment\n  - Events\n  - Sports\n  - Tickets\n  - Venues\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: ticketmaster:ticketmaster-discovery-api\n    name: Ticketmaster Discovery API\n    description: >-\n      The Ticketmaster Discovery API allows developers to search for events,\n      attractions, venues, and classifications\
  \ across the Ticketmaster platform.\n      Provides access to over 230,000 events across the United States, Canada,\n      Mexico, Australia, New Zealand, the UK, Ireland, and Europe. Content\n      sources include Ticketmaster, Universe, FrontGate Tickets, and\n      Ticketmaster Resale (TMR). Authentication is via API key in the query\n      string or header.\n    image: https://www.ticketmaster.com/favicon.ico\n    humanURL: https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/\n    baseURL: https://app.ticketmaster.com/discovery/v2\n    tags:\n      - Attractions\n      - Classifications\n      - Events\n      - Search\n      - Venues\n    properties:\n      - type: Documentation\n        url: https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/\n      - type: Portal\n        url: https://developer.ticketmaster.com\n      - type: OpenAPI\n        url: openapi/ticketmaster-discovery-openapi.yml\n\n  - aid: ticketmaster:ticketmaster-commerce-api\n\
  \    name: Ticketmaster Commerce API\n    description: >-\n      The Ticketmaster Commerce API enables developers to build ticket purchasing\n      flows, retrieve event inventory, check seat availability, and manage ticket\n      orders. Provides access to price ranges, ticket limits, and purchase links.\n    image: https://www.ticketmaster.com/favicon.ico\n    humanURL: https://developer.ticketmaster.com/products-and-docs/apis/getting-started/\n    baseURL: https://app.ticketmaster.com/commerce/v2\n    tags:\n      - Commerce\n      - Inventory\n      - Orders\n      - Tickets\n    properties:\n      - type: Documentation\n        url: https://developer.ticketmaster.com/products-and-docs/apis/getting-started/\n      - type: OpenAPI\n        url: openapi/ticketmaster-commerce-openapi.yml\n\n  - aid: ticketmaster:ticketmaster-partner-api\n    name: Ticketmaster Partner API\n    description: >-\n      The Ticketmaster Partner API is a restricted API for authorized\n      distribution partners\
  \ that enables reserving, purchasing, and retrieving\n      ticket and event information programmatically. Authentication uses API key\n      via query parameter or x-api-key header.\n    image: https://www.ticketmaster.com/favicon.ico\n    humanURL: https://developer.ticketmaster.com/products-and-docs/apis/partner/\n    baseURL: https://app.ticketmaster.com/partners/v1\n    tags:\n      - Commerce\n      - Partner\n      - Reservations\n      - Tickets\n    properties:\n      - type: Documentation\n        url: https://developer.ticketmaster.com/products-and-docs/apis/partner/\n      - type: FAQ\n        url: https://developer.ticketmaster.com/support/partner-api-faq/\n\ncommon:\n  - type: Portal\n    url: https://developer.ticketmaster.com\n  - type: Documentation\n    url: https://developer.ticketmaster.com/products-and-docs/\n  - type: Getting Started\n    url: https://developer.ticketmaster.com/products-and-docs/apis/getting-started/\n  - type: API Explorer\n    url: https://developer.ticketmaster.com/api-explorer/v2/\n\
  \  - type: Website\n    url: https://www.ticketmaster.com\n  - type: Blog\n    url: https://developer.ticketmaster.com/blog/\n  - type: Twitter\n    url: https://twitter.com/ticketmaster\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/ticketmaster\n  - type: Terms of Service\n    url: https://developer.ticketmaster.com/support/terms-of-use/\n  - type: Privacy Policy\n    url: https://www.ticketmaster.com/h/privacy.html\n  - type: JSON-LD\n    url: json-ld/ticketmaster-context.jsonld\n  - type: JSONSchema\n    url: json-schema/ticketmaster-event-schema.json\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/apis.yml
tags:
- Commerce
- Concerts
- Entertainment
- Events
- Sports
- Tickets
- Venues
url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/apis.yml
use_cases: []
---
