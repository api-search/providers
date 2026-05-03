---
api_count: 1
api_specs:
- filename: regal-cinema-openapi.yml
  format: yaml
  label: Regal Cinema API
  slug: regal-cinema-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/openapi/regal-cinema-openapi.yml
apis:
- description: The Regal Cinema API provides access to movie showtimes, theatre information, ticketing, and Regal Crown Club loyalty reward integrations via the Regal API Management developer portal powered by Azure
  name: Regal Cinema API
  slug: regal-cinema-api
capabilities:
- description: Workflow capability for discovering movies, finding nearby Regal theatres, checking showtimes, and purchasing tickets with Regal Crown Club loyalty integration. Designed for mobile apps, concierge ser
  name: Regal Cinema Ticketing
  slug: cinema-ticketing
common:
- title: ''
  type: Website
  url: https://www.regmovies.com
- title: ''
  type: DeveloperPortal
  url: https://developer.regmovies.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/regal-entertainment-group
- title: ''
  type: Twitter
  url: https://x.com/regalmovies
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/openapi/regal-cinema-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/vocabulary/regal-entertainment-group-vocabulary.yml
created: ''
description: Regal Entertainment Group operates one of the largest motion picture theatre circuits in the United States, with theatres located in densely populated metropolitan markets. Regal provides a developer API portal at developer.regmovies.com, built on Azure API Management, enabling partners and developers to integrate movie showtimes, theatre listings, ticketing, and loyalty reward capabilities into applications. Regal was acquired by Cineworld Group in 2018 and continues to operate under the Regal brand.
features: []
image: ''
integrations: []
jsonld:
- class_count: 35
  name: Regal Entertainment Group Context
  property_count: 0
  slug: regal-entertainment-group-context
layout: provider
modified: '2026-05-02'
name: regal-entertainment-group
rules:
- name: regal-entertainment-group API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: regal-cinema-rules
skills: []
slug: regal-entertainment-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: regal-entertainment-group\nurl: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/apis.yml\nmodified: '2026-05-02'\ndescription: >-\n  Regal Entertainment Group operates one of the largest motion picture theatre\n  circuits in the United States, with theatres located in densely populated\n  metropolitan markets. Regal provides a developer API portal at\n  developer.regmovies.com, built on Azure API Management, enabling partners and\n  developers to integrate movie showtimes, theatre listings, ticketing, and\n  loyalty reward capabilities into applications. Regal was acquired by Cineworld\n  Group in 2018 and continues to operate under the Regal brand.\napis:\n  - aid: regal-entertainment-group:regal-cinema-api\n    name: Regal Cinema API\n    description: >-\n      The Regal Cinema API provides access to movie showtimes, theatre\n      information, ticketing, and Regal Crown Club loyalty reward integrations\n      via the Regal\
  \ API Management developer portal powered by Azure API\n      Management. Partners authenticate using an Ocp-Apim-Subscription-Key\n      obtained from developer.regmovies.com.\n    humanURL: https://developer.regmovies.com\n    baseURL: https://api.regmovies.com/v1\n    tags:\n      - Cinema\n      - Movies\n      - Showtimes\n      - Ticketing\n      - Theatres\n      - Entertainment\n      - Loyalty\n    properties:\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/openapi/regal-cinema-openapi.yml\n      - type: Documentation\n        url: https://developer.regmovies.com/apis\n      - type: DeveloperPortal\n        url: https://developer.regmovies.com\n      - type: SignUp\n        url: https://developer.regmovies.com/signup/\n      - type: Products\n        url: https://developer.regmovies.com/products\n    contact:\n      - FN: Regal API Manager\n        email: apimanager@regalcinemas.com\ncommon:\n  - type:\
  \ Website\n    url: https://www.regmovies.com\n  - type: DeveloperPortal\n    url: https://developer.regmovies.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/regal-entertainment-group\n  - type: Twitter\n    url: https://x.com/regalmovies\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/openapi/regal-cinema-openapi.yml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/vocabulary/regal-entertainment-group-vocabulary.yml\ntags:\n  - Cinema\n  - Entertainment\n  - Movies\n  - Ticketing\n  - Loyalty\n  - Theatre\n  - Fortune 500\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/apis.yml
tags:
- Cinema
- Entertainment
- Movies
- Ticketing
- Loyalty
- Theatre
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/apis.yml
use_cases: []
---
