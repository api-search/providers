---
api_count: 2
api_specs:
- filename: lyft-ride-sharing-openapi.yml
  format: yaml
  label: Lyft Ride-Sharing API
  slug: ride-sharing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/openapi/lyft-ride-sharing-openapi.yml
- filename: lyft-concierge-openapi.yml
  format: yaml
  label: Lyft Concierge API
  slug: concierge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/openapi/lyft-concierge-openapi.yml
apis:
- description: The Lyft Ride-Sharing API provides developers with programmatic access to Lyft's rideshare platform. It includes endpoints for retrieving cost estimates between locations, estimating pickup ETAs, list
  name: Lyft Ride-Sharing API
  slug: ride-sharing-api
- description: The Lyft Concierge API allows organizations to request rides on behalf of their customers, patients, or employees without requiring those individuals to have a Lyft account. It is designed for enterpr
  name: Lyft Concierge API
  slug: concierge-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/lyft-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/lyft-ride-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/lyft-ride-type-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/lyft-cost-estimate-schema.json
created: ''
description: Lyft is a transportation network company that develops, markets, and operates a mobile app offering ride-hailing, vehicles for hire, motorized scooters, bicycle-sharing, and food delivery services.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Lyft Context
  property_count: 9
  slug: lyft-context
layout: provider
modified: '2026-04-28'
name: lyft
skills: []
slug: lyft
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lyft\nurl: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/apis.yml\napis:\n  - aid: lyft:ride-sharing-api\n    name: Lyft Ride-Sharing API\n    tags:\n      - Drivers\n      - Estimates\n      - Rides\n      - Rideshare\n      - Transportation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.lyft.com\n    humanURL: https://developer.lyft.com/docs\n    properties:\n      - url: https://developer.lyft.com/docs\n        type: Documentation\n      - url: openapi/lyft-ride-sharing-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Lyft Ride-Sharing API provides developers with programmatic access to Lyft's\n      rideshare platform. It includes endpoints for retrieving cost estimates between\n      locations, estimating pickup ETAs, listing available ride types in a given area,\n      and checking nearby driver availability. The API uses OAuth 2.0 for user-authenticated\n\
  \      requests and client tokens for public endpoints.\n  - aid: lyft:concierge-api\n    name: Lyft Concierge API\n    tags:\n      - Concierge\n      - Enterprise\n      - Healthcare\n      - Rideshare\n      - Transportation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.lyft.com\n    humanURL: https://www.lyft.com/developers/products/concierge-api\n    properties:\n      - url: https://www.lyft.com/developers/products/concierge-api\n        type: Documentation\n      - url: openapi/lyft-concierge-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Lyft Concierge API allows organizations to request rides on behalf of their\n      customers, patients, or employees without requiring those individuals to have\n      a Lyft account. It is designed for enterprise use cases such as healthcare patient\n      transportation, corporate employee transit, and customer service scenarios.\n      The API enables organizations\
  \ to build customized transportation workflows,\n      schedule rides in advance, track ride status in real time, and manage ride programs\n      at scale.\ncommon:\n  - type: JSON-LD\n    url: json-ld/lyft-context.jsonld\n  - type: JSONSchema\n    url: json-schema/lyft-ride-schema.json\n  - type: JSONSchema\n    url: json-schema/lyft-ride-type-schema.json\n  - type: JSONSchema\n    url: json-schema/lyft-cost-estimate-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Lyft is a transportation network company that develops, markets, and operates a\n  mobile app offering ride-hailing, vehicles for hire, motorized scooters, bicycle-sharing,\n  and food delivery services.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/apis.yml
use_cases: []
---
