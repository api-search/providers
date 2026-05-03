---
api_count: 1
api_specs:
- filename: ups-shipping-openapi.yml
  format: yaml
  label: UPS Shipping API
  slug: ups-shipping
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/openapi/ups-shipping-openapi.yml
apis:
- description: The UPS Shipping API enables developers to create and manage shipments, generate shipping labels, validate addresses, retrieve rates, track packages, schedule pickups, and access time-in-transit infor
  name: UPS Shipping API
  slug: ups-shipping
capabilities:
- description: Workflow capability for UPS shipping and logistics operations, combining rate shopping, shipment creation, package tracking, address validation, pickup scheduling, and transit time estimation into a u
  name: UPS Shipping and Logistics
  slug: shipping-and-logistics
common:
- title: ''
  type: Website
  url: https://www.ups.com
- title: ''
  type: Developer Portal
  url: https://developer.ups.com
- title: ''
  type: API Catalog
  url: https://developer.ups.com/catalog
- title: ''
  type: Getting Started
  url: https://developer.ups.com/get-started
created: '2025-03-01'
description: UPS, or United Parcel Service, is a Fortune 500 global logistics company that specializes in package delivery and supply chain management services. UPS provides a comprehensive REST API platform with OAuth 2.0 authentication covering shipping, tracking, rating, address validation, pickup scheduling, paperless international documents, and time-in-transit estimation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Ups Context
  property_count: 17
  slug: ups-context
layout: provider
modified: '2026-05-03'
name: UPS
rules:
- name: UPS API Rules
  rule_count: 6
  severity_counts:
    error: 0
    hint: 0
    info: 3
    warn: 3
  slug: ups-rules
skills: []
slug: ups
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ups\nurl: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/apis.yml\napis:\n  - aid: ups:ups-shipping\n    name: UPS Shipping API\n    description: >-\n      The UPS Shipping API enables developers to create and manage shipments,\n      generate shipping labels, validate addresses, retrieve rates, track packages,\n      schedule pickups, and access time-in-transit information via OAuth 2.0\n      authenticated REST API calls.\n    humanURL: https://developer.ups.com/\n    baseURL: https://onlinetools.ups.com/api\n    tags:\n      - Shipping\n      - Logistics\n      - Tracking\n      - Rating\n      - Address Validation\n    properties:\n      - type: Documentation\n        url: https://developer.ups.com/\n      - type: Getting Started\n        url: https://developer.ups.com/get-started\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/openapi/ups-shipping-openapi.yml\nname: UPS\ntags:\n  - Logistics\n\
  \  - Shipping\n  - Fortune 500\n  - Supply Chain\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  UPS, or United Parcel Service, is a Fortune 500 global logistics company\n  that specializes in package delivery and supply chain management services.\n  UPS provides a comprehensive REST API platform with OAuth 2.0 authentication\n  covering shipping, tracking, rating, address validation, pickup scheduling,\n  paperless international documents, and time-in-transit estimation.\ncommon:\n  - type: Website\n    url: https://www.ups.com\n  - type: Developer Portal\n    url: https://developer.ups.com\n  - type: API Catalog\n    url: https://developer.ups.com/catalog\n  - type: Getting Started\n    url: https://developer.ups.com/get-started\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/apis.yml
tags:
- Logistics
- Shipping
- Fortune 500
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/apis.yml
use_cases: []
---
