---
api_count: 1
apis:
- description: The AirLabs Cities API exposes a single GET /cities endpoint that returns a list of cities filterable by IATA city_code, ISO 2 country_code, or comma-separated _fields. Free-tier responses include nam
  name: AirLabs Cities API
  slug: airlabs-cities-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://airlabs.co/
- title: ''
  type: Documentation
  url: https://airlabs.co/docs
- title: ''
  type: Pricing
  url: https://airlabs.co/pricing
- title: ''
  type: Sign Up
  url: https://airlabs.co/signup
- title: ''
  type: Login
  url: https://airlabs.co/login
- title: ''
  type: Account
  url: https://airlabs.co/account
- title: ''
  type: Authentication
  url: https://airlabs.co/account/api-key
- title: ''
  type: Privacy Policy
  url: https://airlabs.co/privacy
- title: ''
  type: Terms of Service
  url: https://airlabs.co/terms
- title: ''
  type: Support
  url: https://airlabs.co/contact
- title: ''
  type: Status
  url: https://airlabs.co/status
- title: ''
  type: JSON-LD
  url: json-ld/cities-database-api-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cities-database-api-city-schema.json
- title: ''
  type: Spectral
  url: rules/cities-database-api-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cities-database-api-capabilities.yml
created: '2024-03-30'
description: The Cities Database API by AirLabs provides a global reference dataset of cities keyed to IATA metropolitan area codes, ISO country codes, and geographic coordinates. The API is consumed alongside the AirLabs Airports, Airlines, and Flights APIs to power travel search, mapping, geocoding, and clustering experiences. Authentication uses an api_key query parameter obtained from the AirLabs account dashboard. All responses are JSON arrays of city objects.
features: []
image: ''
integrations: []
jsonld:
- class_count: 13
  name: Cities Database Api Context
  property_count: 0
  slug: cities-database-api-context
layout: provider
modified: '2026-04-23'
name: Cities Database API
rules:
- name: Cities Database API API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: cities-database-api-rules
skills: []
slug: cities-database-api
solutions: []
source_yaml: "aid: cities-database-api\nname: Cities Database API\nurl: https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/apis.yml\ncreated: '2024-03-30'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Cities\n  - Data\n  - Geography\n  - Locations\n  - Reference Data\n  - Travel\ndescription: >-\n  The Cities Database API by AirLabs provides a global reference dataset of\n  cities keyed to IATA metropolitan area codes, ISO country codes, and\n  geographic coordinates. The API is consumed alongside the AirLabs Airports,\n  Airlines, and Flights APIs to power travel search, mapping, geocoding,\n  and clustering experiences. Authentication uses an api_key query parameter\n  obtained from the AirLabs account dashboard. All responses are JSON arrays\n  of city objects.\napis:\n  - aid: cities-database-api:airlabs-cities-api\n    name: AirLabs Cities API\n    tags:\n      - Cities\n      -\
  \ Geography\n      - IATA\n      - Reference Data\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://airlabs.co/api/v9\n    humanURL: https://airlabs.co/docs/cities\n    properties:\n      - url: https://airlabs.co/docs/cities\n        type: Documentation\n      - url: https://airlabs.co/docs\n        type: API Reference\n      - url: https://airlabs.co/account/api-key\n        type: Authentication\n      - url: openapi/cities-database-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The AirLabs Cities API exposes a single GET /cities endpoint that\n      returns a list of cities filterable by IATA city_code, ISO 2\n      country_code, or comma-separated _fields. Free-tier responses\n      include name, city_code, latitude, longitude, and country_code;\n      paid tiers add UN/LOCODE, elevation, timezone, population,\n      multilingual names, Wikipedia links, and SEO slugs. Authentication\n   \
  \   uses the api_key query parameter.\ncommon:\n  - type: Website\n    url: https://airlabs.co/\n  - type: Documentation\n    url: https://airlabs.co/docs\n  - type: Pricing\n    url: https://airlabs.co/pricing\n  - type: Sign Up\n    url: https://airlabs.co/signup\n  - type: Login\n    url: https://airlabs.co/login\n  - type: Account\n    url: https://airlabs.co/account\n  - type: Authentication\n    url: https://airlabs.co/account/api-key\n  - type: Privacy Policy\n    url: https://airlabs.co/privacy\n  - type: Terms of Service\n    url: https://airlabs.co/terms\n  - type: Support\n    url: https://airlabs.co/contact\n  - type: Status\n    url: https://airlabs.co/status\n  - type: JSON-LD\n    url: json-ld/cities-database-api-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cities-database-api-city-schema.json\n  - type: Spectral\n    url: rules/cities-database-api-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cities-database-api-capabilities.yml\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/apis.yml
tags:
- Cities
- Data
- Geography
- Locations
- Reference Data
- Travel
url: https://raw.githubusercontent.com/api-evangelist/cities-database-api/refs/heads/main/apis.yml
use_cases: []
---
