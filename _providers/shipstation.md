---
api_count: 2
api_specs:
- filename: shipstation-v1-openapi.yml
  format: yaml
  label: ShipStation V1 API
  slug: shipstation-v1-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/openapi/shipstation-v1-openapi.yml
apis:
- description: The ShipStation V1 API provides programmatic access to ShipStation's shipping platform for ecommerce businesses. Endpoints cover order management, shipment creation, label generation, carrier rate sho
  name: ShipStation V1 API
  slug: shipstation-v1-api
- description: The ShipStation V2 API is the next-generation shipping and inventory API built on ShipEngine technology. It provides improved endpoints for creating orders, managing customers, querying order and ship
  name: ShipStation V2 API
  slug: shipstation-v2-api
capabilities:
- description: Unified ecommerce shipping workflow combining order management, multi-carrier rate shopping, label generation, warehouse management, and store integration. Designed for ecommerce operations teams mana
  name: ShipStation Ecommerce Shipping
  slug: ecommerce-shipping
common:
- title: ''
  type: Documentation
  url: https://www.shipstation.com/docs/api/
- title: ''
  type: API Reference
  url: https://docs.shipstation.com/
- title: ''
  type: Getting Started
  url: https://docs.shipstation.com/getting-started
- title: ''
  type: Authentication
  url: https://www.shipstation.com/docs/api/requirements/
- title: ''
  type: OpenAPI
  url: https://docs.shipstation.com/openapi/downloads
- title: ''
  type: Support
  url: https://help.shipstation.com/hc/en-us/articles/360025856212-ShipStation-API
- title: ''
  type: Terms of Service
  url: https://www.shipstation.com/legal/terms-of-service/
- title: ''
  type: Privacy Policy
  url: https://www.shipstation.com/legal/privacy-policy/
- title: ''
  type: Website
  url: https://www.shipstation.com
created: '2025-03-01'
description: ShipStation is a leading shipping platform for ecommerce businesses providing APIs to integrate shipping workflows into applications. The ShipStation API enables developers to automate order management, create shipments, generate labels, track packages, manage warehouses, and connect to multiple carriers. ShipStation offers both V1 (ssapi.shipstation.com) and V2 (ShipEngine-powered) API versions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 43
  name: Shipstation Context
  property_count: 20
  slug: shipstation-context
layout: provider
modified: '2026-05-02'
name: ShipStation
rules:
- name: ShipStation API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 3
    warn: 5
  slug: shipstation-rules
skills: []
slug: shipstation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shipstation\nurl: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/apis.yml\napis:\n  - aid: shipstation:shipstation-v1-api\n    name: ShipStation V1 API\n    tags:\n      - Ecommerce\n      - Labels\n      - Order Management\n      - Shipping\n    humanURL: https://www.shipstation.com/docs/api/\n    properties:\n      - url: https://www.shipstation.com/docs/api/\n        type: Documentation\n      - url: openapi/shipstation-v1-openapi.yml\n        type: OpenAPI\n      - url: json-schema/shipstation-order-schema.json\n        type: JSONSchema\n      - url: json-schema/shipstation-shipment-schema.json\n        type: JSONSchema\n      - url: json-ld/shipstation-context.jsonld\n        type: JSONLD\n      - url: rules/shipstation-rules.yml\n        type: SpectralRules\n      - url: capabilities/ecommerce-shipping.yaml\n        type: NaftikoCapabilities\n      - url: vocabulary/shipstation-vocabulary.yml\n        type: Vocabulary\n    description:\
  \ >-\n      The ShipStation V1 API provides programmatic access to ShipStation's\n      shipping platform for ecommerce businesses. Endpoints cover order\n      management, shipment creation, label generation, carrier rate shopping,\n      package tracking, warehouse management, product management, and store\n      integrations. Authentication uses HTTP Basic auth with API key and secret.\n      Base URL is https://ssapi.shipstation.com with a rate limit of 40 requests\n      per minute.\n  - aid: shipstation:shipstation-v2-api\n    name: ShipStation V2 API\n    tags:\n      - Ecommerce\n      - Labels\n      - Order Management\n      - Shipping\n    humanURL: https://docs.shipstation.com/\n    properties:\n      - url: https://docs.shipstation.com/\n        type: Documentation\n      - url: https://docs.shipstation.com/rest\n        type: API Reference\n    description: >-\n      The ShipStation V2 API is the next-generation shipping and inventory API\n      built on ShipEngine technology.\
  \ It provides improved endpoints for\n      creating orders, managing customers, querying order and shipping data,\n      and integrating with ShipStation's multi-carrier shipping platform.\n      Available to Standard plan and higher accounts with the API add-on.\nname: ShipStation\ntags:\n  - Ecommerce\n  - Labels\n  - Logistics\n  - Order Management\n  - Shipping\n  - Warehousing\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nposition: Consumer\ndescription: >-\n  ShipStation is a leading shipping platform for ecommerce businesses providing\n  APIs to integrate shipping workflows into applications. The ShipStation API\n  enables developers to automate order management, create shipments, generate\n  labels, track packages, manage warehouses, and connect to multiple carriers.\n  ShipStation offers both V1 (ssapi.shipstation.com) and V2 (ShipEngine-powered)\n  API versions.\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://www.shipstation.com/docs/api/\n    type: Documentation\n  - url: https://docs.shipstation.com/\n    type: API Reference\n  - url: https://docs.shipstation.com/getting-started\n    type: Getting Started\n  - url: https://www.shipstation.com/docs/api/requirements/\n    type: Authentication\n  - url: https://docs.shipstation.com/openapi/downloads\n    type: OpenAPI\n  - url: https://help.shipstation.com/hc/en-us/articles/360025856212-ShipStation-API\n    type: Support\n  - url: https://www.shipstation.com/legal/terms-of-service/\n    type: Terms of Service\n  - url: https://www.shipstation.com/legal/privacy-policy/\n    type: Privacy Policy\n  - url: https://www.shipstation.com\n    type: Website\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/apis.yml
tags:
- Ecommerce
- Labels
- Logistics
- Order Management
- Shipping
- Warehousing
url: https://raw.githubusercontent.com/api-evangelist/shipstation/refs/heads/main/apis.yml
use_cases: []
---
