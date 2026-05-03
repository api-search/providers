---
api_count: 1
api_specs:
- filename: seatgeek-platform-openapi.yml
  format: yaml
  label: SeatGeek Platform API
  slug: seatgeek-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/openapi/seatgeek-platform-openapi.yml
apis:
- description: The SeatGeek Platform API provides access to SeatGeek's comprehensive dataset of live events in the United States and Canada. The API enables developers to search events, performers, and venues, retri
  name: SeatGeek Platform API
  slug: seatgeek-platform-api
capabilities:
- description: Unified event discovery capability combining SeatGeek's events, performers, venues, and recommendation APIs. Enables applications to build comprehensive live event discovery experiences with geolocati
  name: SeatGeek Event Discovery
  slug: event-discovery
common:
- title: ''
  type: Website
  url: https://seatgeek.com
- title: ''
  type: Portal
  url: https://seatgeek.com/build
- title: ''
  type: Documentation
  url: https://seatgeek.github.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/seatgeek
- title: ''
  type: SDK
  url: https://github.com/seatgeek/SGAPI
- title: ''
  type: Support
  url: https://github.com/seatgeek/api-support
- title: ''
  type: TermsOfService
  url: https://seatgeek.com/api-terms
- title: ''
  type: JSONSchema
  url: json-schema/seatgeek-event-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/seatgeek-event-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/seatgeek-context.jsonld
- title: ''
  type: Example
  url: examples/seatgeek-list-events-example.json
- title: ''
  type: SpectralRuleset
  url: rules/seatgeek-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/event-discovery.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/seatgeek-vocabulary.yml
created: '2026-05-02'
description: SeatGeek is a live event ticketing and discovery platform that aggregates ticket inventory from multiple sources and provides a transparent, data-driven ticket buying experience. The SeatGeek Platform API gives developers access to a canonical dataset of live events including concerts, sports, and theater performances, along with performer and venue information, seating maps, ticket pricing, and personalized event recommendations. The API uses HTTP Basic Auth or query parameter authentication with a client ID and supports RESTful access to events, performers, venues, and taxonomies.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Seatgeek Context
  property_count: 4
  slug: seatgeek-context
layout: provider
modified: '2026-05-02'
name: SeatGeek
rules:
- name: SeatGeek API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: seatgeek-rules
skills: []
slug: seatgeek
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: seatgeek\nurl: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml\napis:\n  - aid: seatgeek:seatgeek-platform-api\n    name: SeatGeek Platform API\n    tags:\n      - Events\n      - Tickets\n      - Performers\n      - Venues\n      - Live Events\n    humanURL: https://seatgeek.com/build\n    baseURL: https://api.seatgeek.com/2\n    properties:\n      - url: openapi/seatgeek-platform-openapi.yml\n        type: OpenAPI\n      - url: https://seatgeek.github.io/\n        type: Documentation\n      - url: https://seatgeek.com/build\n        type: Portal\n    description: >-\n      The SeatGeek Platform API provides access to SeatGeek's comprehensive dataset\n      of live events in the United States and Canada. The API enables developers to\n      search events, performers, and venues, retrieve seat maps, get event recommendations,\n      and deep-link users directly to the SeatGeek ticketing purchase flow. It supports\n      JSON, JSONP, and\
  \ XML response formats, with pagination, geolocation filtering,\n      and price-range filtering across all event types including sports, concerts, and\n      theater.\n\nname: SeatGeek\ntags:\n  - Events\n  - Tickets\n  - Live Events\n  - Concerts\n  - Sports\n  - Venues\n  - Ticketing\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  SeatGeek is a live event ticketing and discovery platform that aggregates ticket\n  inventory from multiple sources and provides a transparent, data-driven ticket buying\n  experience. The SeatGeek Platform API gives developers access to a canonical dataset\n  of live events including concerts, sports, and theater performances, along with performer\n  and venue information, seating maps, ticket pricing, and personalized event recommendations.\n  The API uses HTTP Basic Auth or query parameter authentication\
  \ with a client ID and\n  supports RESTful access to events, performers, venues, and taxonomies.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Website\n    url: https://seatgeek.com\n    type: Website\n  - name: Developer Portal\n    url: https://seatgeek.com/build\n    type: Portal\n  - name: API Documentation\n    url: https://seatgeek.github.io/\n    type: Documentation\n  - name: GitHub Organization\n    url: https://github.com/seatgeek\n    type: GitHubOrganization\n  - name: iOS SDK\n    url: https://github.com/seatgeek/SGAPI\n    type: SDK\n  - name: API Support\n    url: https://github.com/seatgeek/api-support\n    type: Support\n  - name: API Terms\n    url: https://seatgeek.com/api-terms\n    type: TermsOfService\n  - url: json-schema/seatgeek-event-schema.json\n    type: JSONSchema\n  - url: json-structure/seatgeek-event-structure.json\n    type: JSONStructure\n  - url: json-ld/seatgeek-context.jsonld\n  \
  \  type: JSONLDContext\n  - url: examples/seatgeek-list-events-example.json\n    type: Example\n  - url: rules/seatgeek-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/event-discovery.yaml\n    type: NaftikoCapability\n  - url: vocabulary/seatgeek-vocabulary.yml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml
tags:
- Events
- Tickets
- Live Events
- Concerts
- Sports
- Venues
- Ticketing
url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/apis.yml
use_cases: []
---
