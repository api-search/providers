---
api_count: 3
apis:
- description: 'The Wine Vybe Wine API provides access to thousands of wines with data including wine regions, grape varieties, tasting notes, food pairing recommendations, awards, producer details, and custom taste '
  name: Wine Vybe Wine API
  slug: wine-vybe-api
- description: The Wine Vybe Beer API provides access to brewery details, ABV data, beer descriptions, food pairing recommendations, awards, packaging specifications, and tasting profiles for thousands of popular be
  name: Wine Vybe Beer API
  slug: wine-vybe-beer-api
- description: The Wine Vybe Liquor API provides access to spirits and liquor data including distillery information, tasting notes, food pairing, and product details for whisky, cognac, tequila, vodka, rum, gin, bra
  name: Wine Vybe Liquor API
  slug: wine-vybe-liquor-api
common:
- title: ''
  type: Website
  url: https://winevybe.com/
- title: ''
  type: Documentation
  url: https://winevybe.com/wine-api/
- title: ''
  type: Documentation
  url: https://winevybe.com/beer-api/
- title: ''
  type: Portal
  url: https://winevybe.com/apis/
- title: ''
  type: RapidAPI
  url: https://rapidapi.com/user/winevybe
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-ld/wine-vybe-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/vocabulary/wine-vybe-vocabulary.yml
created: '2026-03-16'
description: Wine Vybe is a wine, beer, and liquor database API platform that provides access to comprehensive beverage data including wine regions, grape varieties, tasting notes, food pairing recommendations, awards, producer information, brewery and distillery details, and custom taste profiles. The platform serves app developers and businesses through RESTful APIs hosted on RapidAPI.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 24
  name: Wine Vybe Context
  property_count: 0
  slug: wine-vybe-context
layout: provider
modified: '2026-05-03'
name: Wine Vybe
skills: []
slug: wine-vybe
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wine-vybe\nname: Wine Vybe\ndescription: >-\n  Wine Vybe is a wine, beer, and liquor database API platform that provides\n  access to comprehensive beverage data including wine regions, grape varieties,\n  tasting notes, food pairing recommendations, awards, producer information,\n  brewery and distillery details, and custom taste profiles. The platform\n  serves app developers and businesses through RESTful APIs hosted on RapidAPI.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Beverages\n  - Beer\n  - Database\n  - Food Pairing\n  - Liquor\n  - Recommendations\n  - Wine\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: wine-vybe:wine-vybe-api\n    name: Wine Vybe Wine API\n    description: >-\n      The Wine Vybe Wine API provides access to thousands of wines with data\n\
  \      including wine regions, grape varieties, tasting notes, food pairing\n      recommendations, awards, producer details, and custom taste profiles.\n      Available through RapidAPI with per-request pricing.\n    humanURL: https://winevybe.com/wine-api/\n    baseURL: https://winevybe.com\n    tags:\n      - Beverages\n      - Database\n      - Tasting Notes\n      - Wine\n    properties:\n      - type: Documentation\n        url: https://winevybe.com/wine-api/\n      - type: Portal\n        url: https://winevybe.com/apis/\n      - type: RapidAPI\n        url: https://rapidapi.com/user/winevybe\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-schema/wine-vybe-wine-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-structure/wine-vybe-wine-structure.json\n      - type: Example\n        url: >-\n       \
  \   https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/examples/wine-vybe-wine-example.json\n\n  - aid: wine-vybe:wine-vybe-beer-api\n    name: Wine Vybe Beer API\n    description: >-\n      The Wine Vybe Beer API provides access to brewery details, ABV data,\n      beer descriptions, food pairing recommendations, awards, packaging\n      specifications, and tasting profiles for thousands of popular beers.\n      Available through RapidAPI starting at $0.02 per request.\n    humanURL: https://winevybe.com/beer-api/\n    baseURL: https://winevybe.com\n    tags:\n      - Beer\n      - Beverages\n      - Brewery\n      - Database\n    properties:\n      - type: Documentation\n        url: https://winevybe.com/beer-api/\n      - type: Portal\n        url: https://winevybe.com/apis/\n      - type: RapidAPI\n        url: https://rapidapi.com/winevybe/api/beer9\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-schema/wine-vybe-beer-schema.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-structure/wine-vybe-beer-structure.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/examples/wine-vybe-beer-example.json\n\n  - aid: wine-vybe:wine-vybe-liquor-api\n    name: Wine Vybe Liquor API\n    description: >-\n      The Wine Vybe Liquor API provides access to spirits and liquor data\n      including distillery information, tasting notes, food pairing, and\n      product details for whisky, cognac, tequila, vodka, rum, gin, brandy,\n      armagnac, and more. Available through RapidAPI.\n    humanURL: https://winevybe.com/\n    baseURL: https://winevybe.com\n    tags:\n      - Beverages\n      - Database\n      - Distillery\n      - Liquor\n      - Spirits\n    properties:\n      - type: Documentation\n        url: https://winevybe.com/apis/\n      - type: Portal\n\
  \        url: https://winevybe.com/apis/\n      - type: RapidAPI\n        url: https://rapidapi.com/user/winevybe\n\ncommon:\n  - url: https://winevybe.com/\n    name: Wine Vybe\n    type: Website\n    description: Main website for Wine Vybe beverage database platform.\n  - url: https://winevybe.com/wine-api/\n    name: Wine API Documentation\n    type: Documentation\n    description: Documentation for the Wine Vybe Wine API.\n  - url: https://winevybe.com/beer-api/\n    name: Beer API Documentation\n    type: Documentation\n    description: Documentation for the Wine Vybe Beer API.\n  - url: https://winevybe.com/apis/\n    name: Wine Vybe APIs Portal\n    type: Portal\n    description: Portal listing all available Wine Vybe APIs.\n  - url: https://rapidapi.com/user/winevybe\n    name: Wine Vybe on RapidAPI\n    type: RapidAPI\n    description: Wine Vybe API listings on the RapidAPI marketplace.\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/json-ld/wine-vybe-context.jsonld\n\
  \    name: Wine Vybe JSON-LD Context\n    type: JSONLDContext\n    description: JSON-LD context for Wine Vybe beverage domain vocabulary.\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/vocabulary/wine-vybe-vocabulary.yml\n    name: Wine Vybe Vocabulary\n    type: Vocabulary\n    description: Domain vocabulary for the Wine Vybe beverage platform.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/apis.yml
tags:
- Beverages
- Beer
- Database
- Food Pairing
- Liquor
- Recommendations
- Wine
url: https://raw.githubusercontent.com/api-evangelist/wine-vybe/refs/heads/main/apis.yml
use_cases: []
---
