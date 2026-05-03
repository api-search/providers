---
api_count: 1
api_specs:
- filename: new-york-public-library-whats-on-the-menu-openapi-original.yaml
  format: yaml
  label: NYPL What's On The Menu API
  slug: new-york-public-library-whats-on-the-menu
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-york-public-library-whats-on-the-menu/refs/heads/main/openapi/new-york-public-library-whats-on-the-menu-openapi-original.yaml
apis:
- description: The NYPL What's On The Menu API exposes the full Menus dataset for programmatic exploration. Endpoints cover menus and their pages, dishes, search across both, and filtering by year, status, and other
  name: NYPL What's On The Menu API
  slug: new-york-public-library-whats-on-the-menu
common:
- title: ''
  type: Website
  url: http://menus.nypl.org/
- title: ''
  type: Documentation
  url: http://nypl.github.io/menus-api/
created: '2024-11-14'
description: The New York Public Library's What's On The Menu project is a digital collection that showcases over 17,000 historical restaurant menus from the New York City area dating back to the 1850s. The companion API provides programmatic access to menus, pages, and dishes including prices, names, dates, and full-text search. Token-based authentication is required and rate limits apply (5,000 requests/day, 2 requests/second).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: New York Public Library What's On The Menu
skills: []
slug: new-york-public-library-whats-on-the-menu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: new-york-public-library-whats-on-the-menu\nname: New York Public Library What's On The Menu\ndescription: >-\n  The New York Public Library's What's On The Menu project is a digital\n  collection that showcases over 17,000 historical restaurant menus from the\n  New York City area dating back to the 1850s. The companion API provides\n  programmatic access to menus, pages, and dishes including prices, names,\n  dates, and full-text search. Token-based authentication is required and\n  rate limits apply (5,000 requests/day, 2 requests/second).\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Libraries\n  - Menus\n  - Restaurants\n  - History\n  - Open Data\n  - Food\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/new-york-public-library-whats-on-the-menu/refs/heads/main/apis.yml\ncreated: '2024-11-14'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: new-york-public-library-whats-on-the-menu:new-york-public-library-whats-on-the-menu\n    name: NYPL What's On The Menu API\n    description: >-\n      The NYPL What's On The Menu API exposes the full Menus dataset for\n      programmatic exploration. Endpoints cover menus and their pages,\n      dishes, search across both, and filtering by year, status, and other\n      properties. Responses are JSON or XML. Token-based authentication is\n      required (request access via menus@nypl.org). Daily rate limits and\n      pagination headers are provided.\n    humanURL: http://nypl.github.io/menus-api/\n    baseURL: http://api.menus.nypl.org\n    tags:\n      - Libraries\n      - Menus\n      - Restaurants\n      - History\n      - Open Data\n    properties:\n      - type: Documentation\n        url: http://nypl.github.io/menus-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/new-york-public-library-whats-on-the-menu/refs/heads/main/openapi/new-york-public-library-whats-on-the-menu-openapi-original.yaml\n\
  \      - type: Project Site\n        url: http://menus.nypl.org/\n      - type: Data Exports\n        url: http://menus.nypl.org/data\n    contact:\n      - FN: NYPL Menus Project\n        email: menus@nypl.org\ncommon:\n  - type: Website\n    url: http://menus.nypl.org/\n  - type: Documentation\n    url: http://nypl.github.io/menus-api/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/new-york-public-library-whats-on-the-menu/refs/heads/main/apis.yml
tags:
- Libraries
- Menus
- Restaurants
- History
- Open Data
- Food
url: https://raw.githubusercontent.com/api-evangelist/new-york-public-library-whats-on-the-menu/refs/heads/main/apis.yml
use_cases: []
---
