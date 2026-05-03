---
api_count: 2
api_specs:
- filename: walk-score-openapi.yml
  format: yaml
  label: Walk Score API
  slug: walk-score-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-openapi.yml
- filename: walk-score-transit-openapi.yml
  format: yaml
  label: Walk Score Transit API
  slug: walk-score-transit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-transit-openapi.yml
apis:
- description: Returns the Walk Score, Transit Score, and Bike Score for any location specified by latitude/longitude coordinates and address. Walk Score measures walkability on a scale from 0 (car-dependent) to 100
  name: Walk Score API
  slug: walk-score-api
- description: 'Provides detailed public transit data for locations in supported cities including Transit Scores, nearby transit stops with route information, complete transit network data, individual stop and route '
  name: Walk Score Transit API
  slug: walk-score-transit-api
capabilities:
- description: 'Workflow capability combining Walk Score and Transit APIs for comprehensive location intelligence. Enables applications to assess any location''s walkability, transit accessibility, and bikeability in '
  name: Walk Score Location Intelligence
  slug: location-intelligence
common:
- title: ''
  type: Website
  url: https://www.walkscore.com
- title: ''
  type: Portal
  url: https://www.walkscore.com/professional/api.php
- title: ''
  type: Documentation
  url: https://walkscore-api.readthedocs.io/en/latest/
- title: ''
  type: SignUp
  url: https://www.walkscore.com/professional/api-sign-up.php
created: '2025-03-01'
description: Walk Score measures the walkability, transit accessibility, and bikeability of any address in the United States and Canada. The Walk Score API returns Walk Score, Transit Score, and Bike Score for any geographic location, supporting real estate platforms, commute calculators, urban planning tools, and location intelligence applications. The Public Transit API provides detailed transit data including nearby stops, route networks, and supported cities, enabling comprehensive transportation accessibility analysis.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Walk Score Context
  property_count: 7
  slug: walk-score-context
layout: provider
modified: '2026-05-03'
name: Walk Score
rules:
- name: Walk Score API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: walk-score-rules
skills: []
slug: walk-score
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: walk-score\nname: Walk Score\ndescription: >-\n  Walk Score measures the walkability, transit accessibility, and bikeability of any\n  address in the United States and Canada. The Walk Score API returns Walk Score,\n  Transit Score, and Bike Score for any geographic location, supporting real estate\n  platforms, commute calculators, urban planning tools, and location intelligence\n  applications. The Public Transit API provides detailed transit data including nearby\n  stops, route networks, and supported cities, enabling comprehensive transportation\n  accessibility analysis.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Walkability\n  - Transit\n  - Bikeability\n  - Location\n  - Real Estate\n  - Urban Planning\n  - Transportation\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: walk-score:walk-score-api\n    name: Walk Score API\n    description: >-\n      Returns the Walk Score, Transit Score, and Bike Score for any location specified\n      by latitude/longitude coordinates and address. Walk Score measures walkability\n      on a scale from 0 (car-dependent) to 100 (walker's paradise). Optionally\n      returns Transit Score and Bike Score in the same response. Supported in the\n      United States and Canada. API calls must originate from server-side scripts.\n    humanURL: https://www.walkscore.com/professional/api.php\n    baseURL: https://api.walkscore.com\n    tags:\n      - Walkability\n      - Walk Score\n      - Transit Score\n      - Bike Score\n      - Location Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.walkscore.com/professional/api.php\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-openapi.yml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/json-schema/walk-score-score-schema.json\n  - aid: walk-score:walk-score-transit-api\n    name: Walk Score Transit API\n    description: >-\n      Provides detailed public transit data for locations in supported cities including\n      Transit Scores, nearby transit stops with route information, complete transit\n      network data, individual stop and route details, and a list of supported cities.\n      Used for comprehensive transit accessibility analysis in real estate, city planning,\n      and commute optimization applications.\n    humanURL: https://www.walkscore.com/professional/public-transit-api.php\n    baseURL: https://transit.walkscore.com\n    tags:\n      - Public Transit\n      - Transit Data\n      - Transit Score\n      - Bus\n      - Rail\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://www.walkscore.com/professional/public-transit-api.php\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-transit-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.walkscore.com\n  - type: Portal\n    url: https://www.walkscore.com/professional/api.php\n  - type: Documentation\n    url: https://walkscore-api.readthedocs.io/en/latest/\n  - type: SignUp\n    url: https://www.walkscore.com/professional/api-sign-up.php\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml
tags:
- Walkability
- Transit
- Bikeability
- Location
- Real Estate
- Urban Planning
- Transportation
url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml
use_cases: []
---
