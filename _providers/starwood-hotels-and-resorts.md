---
api_count: 3
api_specs:
- filename: starwood-hotel-search-openapi.yml
  format: yaml
  label: Hotel Search API
  slug: hotel-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/openapi/starwood-hotel-search-openapi.yml
apis:
- description: The Starwood Hotel Search API allowed partners and developers to search Starwood's portfolio of hotels and resorts by location, dates, and availability. It supported querying by country, province, cit
  name: Hotel Search API
  slug: hotel-search-api
- description: The Starwood Preferred Guest (SPG) Loyalty API provided programmatic access to the SPG loyalty program, enabling partners to query member point balances, redeem Starpoints, look up member status and t
  name: SPG Loyalty API
  slug: spg-loyalty-api
- description: The Starwood Property Data API provided detailed information about individual hotel properties including room types, amenities, dining options, meeting and event spaces, photos, geo-coordinates, and c
  name: Property Data API
  slug: property-data-api
capabilities:
- description: Workflow capability for Starwood Hotels and Resorts hotel booking and travel planning. Combines hotel search, property lookup, and availability checking to support travel planning agents, OTA integrat
  name: Starwood Hotel Booking
  slug: hotel-booking
common:
- title: ''
  type: Website
  url: https://www.starwoodhotels.com
- title: ''
  type: Developer Portal
  url: https://github.com/StayExpert/starwood
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/starwoodhotels
- title: ''
  type: Facebook
  url: https://www.facebook.com/starwood
- title: ''
  type: Blog
  url: https://www.starwoodhotels.com/corporate/
- title: ''
  type: Acquisition
  url: https://marriott.gcs-web.com/news-releases/news-release-details/marriott-international-completes-acquisition-starwood-hotels
- title: ''
  type: Terms of Service
  url: https://www.starwoodhotels.com/corporate/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.starwoodhotels.com/corporate/privacy.html
- title: ''
  type: OpenAPI
  url: openapi/starwood-hotel-search-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/starwood-hotel-search-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/starwood-hotel-structure.json
- title: ''
  type: JSONLD
  url: json-ld/starwood-hotels-and-resorts-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/starwood-hotels-and-resorts-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/starwood-hotels-and-resorts-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/hotel-booking.yaml
created: ''
description: Starwood Hotels & Resorts Worldwide was a global hotel and leisure company headquartered in Stamford, Connecticut. Prior to its acquisition by Marriott International in September 2016, Starwood operated and franchised hotels, resorts, and residences under iconic brands including Sheraton, Westin, W Hotels, St. Regis, Le Méridien, Four Points, Tribute Portfolio, Design Hotels, Element, and Aloft. The company also operated the Starwood Preferred Guest (SPG) loyalty program, which was later merged into Marriott Bonvoy. At the time of acquisition, Starwood managed over 1,300 properties in approximately 100 countries. Starwood exposed APIs for hotel search, property data, and loyalty program integration that were consumed by travel platforms and partners.
features: []
image: ''
integrations: []
jsonld:
- class_count: 23
  name: Starwood Hotels And Resorts Context
  property_count: 8
  slug: starwood-hotels-and-resorts-context
layout: provider
modified: '2026-05-02'
name: Starwood Hotels and Resorts
rules:
- name: Starwood Hotels and Resorts API Rules
  rule_count: 13
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 9
  slug: starwood-hotels-and-resorts-rules
skills: []
slug: starwood-hotels-and-resorts
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: starwood-hotels-and-resorts\nurl: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/apis.yml\nmodified: '2026-05-02'\nname: Starwood Hotels and Resorts\ndescription: >-\n  Starwood Hotels & Resorts Worldwide was a global hotel and leisure company headquartered\n  in Stamford, Connecticut. Prior to its acquisition by Marriott International in September 2016,\n  Starwood operated and franchised hotels, resorts, and residences under iconic brands including\n  Sheraton, Westin, W Hotels, St. Regis, Le Méridien, Four Points, Tribute Portfolio, Design Hotels,\n  Element, and Aloft. The company also operated the Starwood Preferred Guest (SPG) loyalty program,\n  which was later merged into Marriott Bonvoy. At the time of acquisition, Starwood managed over\n  1,300 properties in approximately 100 countries. Starwood exposed APIs for hotel search, property\n  data, and loyalty program integration that were consumed by travel platforms\
  \ and partners.\napis:\n  - aid: starwood-hotels-and-resorts:hotel-search-api\n    name: Hotel Search API\n    description: >-\n      The Starwood Hotel Search API allowed partners and developers to search Starwood's\n      portfolio of hotels and resorts by location, dates, and availability. It supported\n      querying by country, province, city, and date range, returning property details\n      including name, address, category, best available rate, and SPG points redemption\n      options. This API underpinned partner booking integrations, OTA connections, and\n      travel management platform integrations.\n    humanURL: https://www.starwoodhotels.com/\n    baseURL: https://www.starwoodhotels.com/api\n    tags:\n      - Hotels\n      - Travel\n      - Hospitality\n      - Search\n      - Availability\n    properties:\n      - type: Documentation\n        url: https://github.com/StayExpert/starwood\n      - type: OpenAPI\n        url: openapi/starwood-hotel-search-openapi.yml\n\n \
  \ - aid: starwood-hotels-and-resorts:spg-loyalty-api\n    name: SPG Loyalty API\n    description: >-\n      The Starwood Preferred Guest (SPG) Loyalty API provided programmatic access to the\n      SPG loyalty program, enabling partners to query member point balances, redeem Starpoints,\n      look up member status and tier information, and book award nights. The program offered\n      Preferred, Gold, and Platinum status tiers with corresponding benefits. Following\n      the Marriott acquisition, SPG was eventually merged into the Marriott Bonvoy loyalty\n      program in 2019.\n    humanURL: https://www.starwoodhotels.com/preferredguest/\n    baseURL: https://www.starwoodhotels.com/api/spg\n    tags:\n      - Loyalty\n      - Rewards\n      - Hotels\n      - Travel\n      - Hospitality\n    properties:\n      - type: Documentation\n        url: https://www.starwoodhotels.com/preferredguest/\n\n  - aid: starwood-hotels-and-resorts:property-data-api\n    name: Property Data API\n    description:\
  \ >-\n      The Starwood Property Data API provided detailed information about individual hotel\n      properties including room types, amenities, dining options, meeting and event spaces,\n      photos, geo-coordinates, and contact information. Partners used this API to populate\n      travel booking sites and corporate travel management systems with accurate Starwood\n      property content.\n    humanURL: https://www.starwoodhotels.com/\n    baseURL: https://www.starwoodhotels.com/api/properties\n    tags:\n      - Hotels\n      - Properties\n      - Travel\n      - Content\n      - Hospitality\n    properties:\n      - type: Documentation\n        url: https://www.starwoodhotels.com/\n\ncommon:\n  - type: Website\n    url: https://www.starwoodhotels.com\n  - type: Developer Portal\n    url: https://github.com/StayExpert/starwood\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/starwoodhotels\n  - type: Facebook\n    url: https://www.facebook.com/starwood\n  - type: Blog\n\
  \    url: https://www.starwoodhotels.com/corporate/\n  - type: Acquisition\n    url: https://marriott.gcs-web.com/news-releases/news-release-details/marriott-international-completes-acquisition-starwood-hotels\n  - type: Terms of Service\n    url: https://www.starwoodhotels.com/corporate/terms.html\n  - type: Privacy Policy\n    url: https://www.starwoodhotels.com/corporate/privacy.html\n  - type: OpenAPI\n    url: openapi/starwood-hotel-search-openapi.yml\n  - type: JSONSchema\n    url: json-schema/starwood-hotel-search-schema.json\n  - type: JSONStructure\n    url: json-structure/starwood-hotel-structure.json\n  - type: JSONLD\n    url: json-ld/starwood-hotels-and-resorts-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/starwood-hotels-and-resorts-vocabulary.yml\n  - type: SpectralRules\n    url: rules/starwood-hotels-and-resorts-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/hotel-booking.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/apis.yml
use_cases: []
---
