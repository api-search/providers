---
api_count: 2
api_specs:
- filename: interactive-brokers-web-api-openapi.yml
  format: yaml
  label: Interactive Brokers Web API
  slug: web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/openapi/interactive-brokers-web-api-openapi.yml
apis:
- description: The Interactive Brokers Web API is a RESTful API that provides programmatic access to IBKR trading, portfolio management, market data, and account information. The API consolidates the Client Portal W
  name: Interactive Brokers Web API
  slug: web-api
- description: The Interactive Brokers Client Portal API is a REST API accessed through a locally running Java gateway that routes authenticated requests to IBKR systems. It provides a lightweight interface for trad
  name: Interactive Brokers Client Portal API
  slug: client-portal-api
common:
- title: ''
  type: Portal
  url: https://www.interactivebrokers.com/campus/ibkr-api-page/ibkr-api-home/
- title: ''
  type: Documentation
  url: https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/
- title: ''
  type: Website
  url: https://www.interactivebrokers.com/
- title: ''
  type: GitHub
  url: https://github.com/nicholasgasior/interactive-brokers-api
- title: ''
  type: Login
  url: https://www.interactivebrokers.com/sso/Login
created: '2026-03-21'
description: Interactive Brokers is an online brokerage firm providing trading access to stocks, options, futures, currencies, bonds, and funds across 150+ markets worldwide. IBKR offers comprehensive REST APIs that enable developers and traders to programmatically access trading, portfolio management, market data, and account management capabilities through the IBKR Web API and Client Portal API.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Interactive Brokers
skills: []
slug: interactive-brokers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: interactive-brokers\nname: Interactive Brokers\ndescription: >-\n  Interactive Brokers is an online brokerage firm providing trading access to\n  stocks, options, futures, currencies, bonds, and funds across 150+ markets\n  worldwide. IBKR offers comprehensive REST APIs that enable developers and\n  traders to programmatically access trading, portfolio management, market\n  data, and account management capabilities through the IBKR Web API and\n  Client Portal API.\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Brokerage\n  - Market Data\n  - Orders\n  - Portfolio\n  - Trading\nurl: https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: interactive-brokers:web-api\n    name: Interactive Brokers Web API\n    description: >-\n      The Interactive Brokers Web API is a RESTful API\
  \ that provides\n      programmatic access to IBKR trading, portfolio management, market data,\n      and account information. The API consolidates the Client Portal Web API,\n      Digital Account Management, and Flex Web Service into a unified\n      interface. It supports OAuth 2.0 authentication and provides endpoints\n      for order placement, portfolio monitoring, real-time and historical\n      market data, and account management across global markets.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/\n    baseURL: https://localhost:5000/v1/api\n    tags:\n      - Brokerage\n      - Market Data\n      - Orders\n      - Portfolio\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/\n      - type: OpenAPI\n        url: openapi/interactive-brokers-web-api-openapi.yml\n  -\
  \ aid: interactive-brokers:client-portal-api\n    name: Interactive Brokers Client Portal API\n    description: >-\n      The Interactive Brokers Client Portal API is a REST API accessed through\n      a locally running Java gateway that routes authenticated requests to\n      IBKR systems. It provides a lightweight interface for trading, viewing\n      portfolio information, accessing market data, and managing\n      authentication. The API uses a two-tiered session structure with\n      read-only and brokerage session levels.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://interactivebrokers.github.io/cpwebapi/\n    baseURL: https://localhost:5000/v1/api\n    tags:\n      - Authentication\n      - Brokerage\n      - Gateway\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://interactivebrokers.github.io/cpwebapi/\ncommon:\n  - type: Portal\n    url: https://www.interactivebrokers.com/campus/ibkr-api-page/ibkr-api-home/\n\
  \  - type: Documentation\n    url: https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/\n  - type: Website\n    url: https://www.interactivebrokers.com/\n  - type: GitHub\n    url: https://github.com/nicholasgasior/interactive-brokers-api\n  - type: Login\n    url: https://www.interactivebrokers.com/sso/Login\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/apis.yml
tags:
- Brokerage
- Market Data
- Orders
- Portfolio
- Trading
url: https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/apis.yml
use_cases: []
---
