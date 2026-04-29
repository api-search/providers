---
api_count: 3
api_specs:
- filename: citizens-bank-accounts-api-openapi.yml
  format: yaml
  label: Citizens Bank Accounts API
  slug: accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/openapi/citizens-bank-accounts-api-openapi.yml
- filename: citizens-bank-atm-locator-api-openapi.yml
  format: yaml
  label: Citizens Bank ATM Locator API
  slug: atm-locator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/openapi/citizens-bank-atm-locator-api-openapi.yml
apis:
- description: The Citizens Bank Accounts API enables authenticated consumers to programmatically retrieve deposit account and transaction data for Citizens Bank customers. Designed exclusively for Savings and Check
  name: Citizens Bank Accounts API
  slug: accounts-api
- description: The Citizens Bank ATM Locator API enables users to locate all Citizens Bank ATMs throughout the USA. The API supports queries by zip code, street address, or latitude and longitude coordinates, return
  name: Citizens Bank ATM Locator API
  slug: atm-locator-api
- description: The Citizens Pay API enables merchants and partners to integrate Citizens Pay point-of-sale financing into their applications and checkout experiences. Citizens Pay provides consumer financing solutio
  name: Citizens Pay API
  slug: citizens-pay-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.citizensbank.com/
- title: ''
  type: Portal
  url: https://developer.citizensbank.com/
- title: ''
  type: Sandbox
  url: https://sandboxdeveloper.citizensbank.com/api
- title: ''
  type: Support
  url: https://developer.citizensbank.com/support
- title: ''
  type: Privacy Policy
  url: https://www.citizensbank.com/privacy
- title: ''
  type: JSON-LD
  url: json-ld/citizens-financial-context.jsonld
- title: ''
  type: Spectral
  url: rules/citizens-financial-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/citizens-financial-capabilities.yml
created: '2026-03-21'
description: Citizens Financial Group is one of the oldest and largest financial institutions in the United States, providing retail and commercial banking products and services to individuals, small businesses, middle-market companies, and large corporations. Citizens exposes its programmable surface through the Citizens developer portal at developer.citizensbank.com, with REST APIs for deposit account and transaction data, ATM location services, and point-of-sale consumer financing through Citizens Pay. Authentication is OAuth 2.0 and the portal provides both sandbox and production environments.
features: []
image: ''
integrations: []
jsonld:
- class_count: 14
  name: Citizens Financial Context
  property_count: 0
  slug: citizens-financial-context
layout: provider
modified: '2026-04-23'
name: Citizens Financial
rules:
- name: Citizens Financial API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: citizens-financial-rules
skills: []
slug: citizens-financial
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: citizens-financial\nname: Citizens Financial\nurl: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Accounts\n  - ATMs\n  - Banking\n  - Open Banking\n  - Payments\n  - Point of Sale\n  - Transactions\ndescription: >-\n  Citizens Financial Group is one of the oldest and largest financial\n  institutions in the United States, providing retail and commercial\n  banking products and services to individuals, small businesses,\n  middle-market companies, and large corporations. Citizens exposes its\n  programmable surface through the Citizens developer portal at\n  developer.citizensbank.com, with REST APIs for deposit account and\n  transaction data, ATM location services, and point-of-sale consumer\n  financing through Citizens Pay. Authentication is OAuth 2.0 and the\n  portal provides both\
  \ sandbox and production environments.\napis:\n  - aid: citizens-financial:accounts-api\n    name: Citizens Bank Accounts API\n    tags:\n      - Accounts\n      - Banking\n      - Open Banking\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.citizensbank.com\n    humanURL: https://developer.citizensbank.com/\n    properties:\n      - url: https://developer.citizensbank.com/\n        type: Portal\n      - url: https://developer.citizensbank.com/product/35/api/26\n        type: Documentation\n      - url: openapi/citizens-bank-accounts-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Citizens Bank Accounts API enables authenticated consumers to\n      programmatically retrieve deposit account and transaction data for\n      Citizens Bank customers. Designed exclusively for Savings and\n      Checking accounts, it provides structured access to account\n      metadata and detailed transaction\
  \ histories through a RESTful\n      interface.\n  - aid: citizens-financial:atm-locator-api\n    name: Citizens Bank ATM Locator API\n    tags:\n      - ATMs\n      - Banking\n      - Geolocation\n      - Locations\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.citizensbank.com\n    humanURL: https://developer.citizensbank.com/\n    properties:\n      - url: https://developer.citizensbank.com/\n        type: Documentation\n      - url: openapi/citizens-bank-atm-locator-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Citizens Bank ATM Locator API enables users to locate all\n      Citizens Bank ATMs throughout the USA. The API supports queries by\n      zip code, street address, or latitude and longitude coordinates,\n      returning ATM location details including hours of operation and\n      whether the location is a standalone ATM or part of another\n      entity.\n  - aid: citizens-financial:citizens-pay-api\n\
  \    name: Citizens Pay API\n    tags:\n      - Financing\n      - Lending\n      - Payments\n      - Point of Sale\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.citizenspay.com\n    humanURL: https://developer-citizenspay.citizensbank.com/\n    properties:\n      - url: https://developer-citizenspay.citizensbank.com/\n        type: Portal\n    description: >-\n      The Citizens Pay API enables merchants and partners to integrate\n      Citizens Pay point-of-sale financing into their applications and\n      checkout experiences. Citizens Pay provides consumer financing\n      solutions that allow customers to pay over time for purchases\n      through participating retailers.\ncommon:\n  - type: Website\n    url: https://www.citizensbank.com/\n  - type: Portal\n    url: https://developer.citizensbank.com/\n  - type: Sandbox\n    url: https://sandboxdeveloper.citizensbank.com/api\n  - type: Support\n    url: https://developer.citizensbank.com/support\n\
  \  - type: Privacy Policy\n    url: https://www.citizensbank.com/privacy\n  - type: JSON-LD\n    url: json-ld/citizens-financial-context.jsonld\n  - type: Spectral\n    url: rules/citizens-financial-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/citizens-financial-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/apis.yml
tags:
- Accounts
- ATMs
- Banking
- Open Banking
- Payments
- Point of Sale
- Transactions
url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/apis.yml
use_cases: []
---
