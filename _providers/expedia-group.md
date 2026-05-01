---
api_count: 5
api_specs:
- filename: expedia-rapid-openapi-original.yml
  format: yaml
  label: Expedia Rapid API
  slug: rapid
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/openapi/expedia-rapid-openapi-original.yml
- filename: expedia-fraud-protection-openapi-original.yml
  format: yaml
  label: Expedia Fraud Protection API
  slug: fraud-protection
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/openapi/expedia-fraud-protection-openapi-original.yml
- filename: expedia-lodging-product-openapi-original.yml
  format: yaml
  label: Expedia Lodging API
  slug: lodging
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/openapi/expedia-lodging-product-openapi-original.yml
- filename: expedia-deposit-openapi-original.yml
  format: yaml
  label: Expedia EPS Deposit API
  slug: deposit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/openapi/expedia-deposit-openapi-original.yml
- filename: expedia-loyalty-openapi-original.yml
  format: yaml
  label: Expedia Loyalty Earn API
  slug: loyalty
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/openapi/expedia-loyalty-openapi-original.yml
apis:
- description: Expedia Rapid provides access to Expedia Group's hotel inventory, rates, and availability for booking integration.
  name: Expedia Rapid API
  slug: rapid
- description: API for fraud prevention and protection services within the Expedia Group platform.
  name: Expedia Fraud Protection API
  slug: fraud-protection
- description: API for lodging supply and property management within the Expedia Group partner network.
  name: Expedia Lodging API
  slug: lodging
- description: The EPS Deposit API manages the deposit policy for a property, offering operations to create, update, read, and delete deposit policies for Expedia partner properties.
  name: Expedia EPS Deposit API
  slug: deposit
- description: The Loyalty Earn API provides access to loyalty earn transactions across configurable date ranges, returning sorted transaction data for membership programs.
  name: Expedia Loyalty Earn API
  slug: loyalty
common:
- title: ''
  type: Portal
  url: https://developers.expediagroup.com/docs/
- title: ''
  type: SDKs
  url: https://developers.expediagroup.com/docs/sdk
- title: ''
  type: Blog
  url: https://medium.com/expedia-group-tech
- title: ''
  type: Support
  url: https://developers.expediagroup.com/docs/support
- title: ''
  type: Status
  url: https://status.developers.expediagroup.com/
created: '2024-06-07'
description: Expedia Group is an American travel technology company that owns and operates travel fare aggregators and travel metasearch engines, including Expedia, Hotels.com, Vrbo, Travelocity, Hotwire.com, Orbitz, Ebookers, CheapTickets, CarRentals.com, and Trivago. Their developer platform provides APIs for travel inventory, lodging, and analytics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Expedia Group
skills: []
slug: expedia-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: expedia-group\nname: Expedia Group\ndescription: >-\n  Expedia Group is an American travel technology company that owns and operates\n  travel fare aggregators and travel metasearch engines, including Expedia,\n  Hotels.com, Vrbo, Travelocity, Hotwire.com, Orbitz, Ebookers, CheapTickets,\n  CarRentals.com, and Trivago. Their developer platform provides APIs for\n  travel inventory, lodging, and analytics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Flights\n  - Hotels\n  - Lodging\n  - Travel\nurl: https://developers.expediagroup.com/docs/\ncreated: '2024-06-07'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: expedia-group:rapid\n    name: Expedia Rapid API\n    description: >-\n      Expedia Rapid provides access to Expedia Group's hotel inventory,\n      rates, and availability for booking integration.\n    humanURL: https://developers.expediagroup.com/docs/products/rapid\n\
  \    tags:\n      - Availability\n      - Hotels\n      - Rates\n    properties:\n      - type: Documentation\n        url: https://developers.expediagroup.com/docs/products/rapid\n      - type: OpenAPI\n        url: openapi/expedia-rapid-openapi-original.yml\n  - aid: expedia-group:fraud-protection\n    name: Expedia Fraud Protection API\n    description: >-\n      API for fraud prevention and protection services within the Expedia\n      Group platform.\n    humanURL: https://developers.expediagroup.com/docs/products/fraud-prevention\n    tags:\n      - Fraud\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developers.expediagroup.com/docs/products/fraud-prevention\n      - type: OpenAPI\n        url: openapi/expedia-fraud-protection-openapi-original.yml\n  - aid: expedia-group:lodging\n    name: Expedia Lodging API\n    description: >-\n      API for lodging supply and property management within the Expedia\n      Group partner network.\n    humanURL:\
  \ https://developers.expediagroup.com/supply/lodging\n    tags:\n      - Hotels\n      - Lodging\n      - Property Management\n    properties:\n      - type: Documentation\n        url: https://developers.expediagroup.com/supply/lodging\n      - type: OpenAPI\n        url: openapi/expedia-lodging-product-openapi-original.yml\n  - aid: expedia-group:deposit\n    name: Expedia EPS Deposit API\n    description: >-\n      The EPS Deposit API manages the deposit policy for a property,\n      offering operations to create, update, read, and delete deposit\n      policies for Expedia partner properties.\n    humanURL: https://expediaconnectivity.com/developer\n    tags:\n      - Deposit\n      - Lodging\n      - Property Management\n    properties:\n      - type: Documentation\n        url: https://expediaconnectivity.com/developer\n      - type: OpenAPI\n        url: openapi/expedia-deposit-openapi-original.yml\n  - aid: expedia-group:loyalty\n    name: Expedia Loyalty Earn API\n    description:\
  \ >-\n      The Loyalty Earn API provides access to loyalty earn transactions\n      across configurable date ranges, returning sorted transaction data\n      for membership programs.\n    humanURL: https://developers.expediagroup.com/analytics\n    tags:\n      - Analytics\n      - Loyalty\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://developers.expediagroup.com/analytics\n      - type: OpenAPI\n        url: openapi/expedia-loyalty-openapi-original.yml\ncommon:\n  - type: Portal\n    url: https://developers.expediagroup.com/docs/\n  - type: SDKs\n    url: https://developers.expediagroup.com/docs/sdk\n  - type: Blog\n    url: https://medium.com/expedia-group-tech\n  - type: Support\n    url: https://developers.expediagroup.com/docs/support\n  - type: Status\n    url: https://status.developers.expediagroup.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/expedia-group/refs/heads/main/apis.yml
tags:
- Flights
- Hotels
- Lodging
- Travel
url: https://developers.expediagroup.com/docs/
use_cases: []
---
