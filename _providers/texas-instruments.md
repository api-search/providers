---
api_count: 2
api_specs:
- filename: texas-instruments-store-openapi.yml
  format: yaml
  label: Texas Instruments Store API
  slug: ti-store-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/openapi/texas-instruments-store-openapi.yml
- filename: texas-instruments-product-information-openapi.yml
  format: yaml
  label: Texas Instruments Product Information API
  slug: ti-product-information-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/openapi/texas-instruments-product-information-openapi.yml
apis:
- description: The TI Store API enables enterprise customers to integrate with TI's ordering platform. It provides real-time inventory and pricing data, order creation and retrieval, advanced ship notice (ASN) track
  name: Texas Instruments Store API
  slug: ti-store-api
- description: The TI Product Information API suite provides access to TI's semiconductor product catalog including parametric data, quality and reliability information. Available as standard (multiple calls, 3,000/
  name: Texas Instruments Product Information API
  slug: ti-product-information-api
capabilities:
- description: Unified semiconductor procurement capability for electronics engineers, procurement teams, and supply chain managers. Combines TI's Store API and Product Information API to enable part research, inven
  name: Texas Instruments Semiconductor Procurement
  slug: semiconductor-procurement
common:
- title: ''
  type: Website
  url: https://www.texas-instruments.com
- title: ''
  type: Developer Portal
  url: https://api-portal.ti.com/
- title: ''
  type: Documentation
  url: https://www.ti.com/developer-api/overview.html
- title: ''
  type: Getting Started
  url: https://api-portal.ti.com/store-api-getstarted
- title: ''
  type: Support
  url: https://api-portal.ti.com/support
- title: ''
  type: FAQ
  url: https://api-portal.ti.com/faq
- title: ''
  type: OpenAPI
  url: openapi/texas-instruments-store-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/texas-instruments-product-information-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/ti-product-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/texas-instruments-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/texas-instruments-vocabulary.yml
created: '2026-03-21'
description: Texas Instruments is an American technology company that designs and manufactures semiconductors and various integrated circuits for industrial, automotive, personal electronics, communications equipment, and enterprise systems markets. TI provides a developer API portal at api-portal.ti.com offering Store APIs for inventory, ordering, and shipment tracking, as well as Product Information APIs for accessing parametric data, quality, and reliability information on TI's extensive semiconductor catalog.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Texas Instruments Context
  property_count: 26
  slug: texas-instruments-context
layout: provider
modified: '2026-05-03'
name: Texas Instruments
rules:
- name: Texas Instruments API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 3
  slug: texas-instruments-rules
skills: []
slug: texas-instruments
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: texas-instruments\nname: Texas Instruments\ndescription: >-\n  Texas Instruments is an American technology company that designs and\n  manufactures semiconductors and various integrated circuits for industrial,\n  automotive, personal electronics, communications equipment, and enterprise\n  systems markets. TI provides a developer API portal at api-portal.ti.com\n  offering Store APIs for inventory, ordering, and shipment tracking, as\n  well as Product Information APIs for accessing parametric data, quality,\n  and reliability information on TI's extensive semiconductor catalog.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ncreated: '2026-03-21'\ntype: Index\nspecificationVersion: '0.19'\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Electronics\n  - Ordering\n  - Semiconductors\n  - Supply Chain\napis:\n  - aid: texas-instruments:ti-store-api\n\
  \    name: Texas Instruments Store API\n    description: >-\n      The TI Store API enables enterprise customers to integrate with TI's\n      ordering platform. It provides real-time inventory and pricing data,\n      order creation and retrieval, advanced ship notice (ASN) tracking, and\n      financial document retrieval. OAuth 2.0 client credentials authentication\n      against transact.ti.com. Production base URL: https://transact.ti.com/v2/store\n    humanURL: https://www.ti.com/developer-api/store-api/getting-started.html\n    baseURL: https://transact.ti.com/v2/store\n    tags:\n      - Inventory\n      - Ordering\n      - Semiconductors\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://www.ti.com/developer-api/store-api/getting-started.html\n      - type: OpenAPI\n        url: openapi/texas-instruments-store-openapi.yml\n      - type: Portal\n        url: https://api-portal.ti.com/\n  - aid: texas-instruments:ti-product-information-api\n\
  \    name: Texas Instruments Product Information API\n    description: >-\n      The TI Product Information API suite provides access to TI's semiconductor\n      product catalog including parametric data, quality and reliability\n      information. Available as standard (multiple calls, 3,000/day limit)\n      and orchestrated (single call, 1,500/day limit) variants. Base URL:\n      https://transact.ti.com/v1\n    humanURL: https://www.ti.com/developer-api/product-information-api-suite/getting-started.html\n    baseURL: https://transact.ti.com/v1\n    tags:\n      - Electronics\n      - Product Data\n      - Semiconductors\n    properties:\n      - type: Documentation\n        url: https://www.ti.com/developer-api/product-information-api-suite/getting-started.html\n      - type: OpenAPI\n        url: openapi/texas-instruments-product-information-openapi.yml\n      - type: Portal\n        url: https://api-portal.ti.com/\ncommon:\n  - type: Website\n    url: https://www.texas-instruments.com\n\
  \  - type: Developer Portal\n    url: https://api-portal.ti.com/\n  - type: Documentation\n    url: https://www.ti.com/developer-api/overview.html\n  - type: Getting Started\n    url: https://api-portal.ti.com/store-api-getstarted\n  - type: Support\n    url: https://api-portal.ti.com/support\n  - type: FAQ\n    url: https://api-portal.ti.com/faq\n  - type: OpenAPI\n    url: openapi/texas-instruments-store-openapi.yml\n  - type: OpenAPI\n    url: openapi/texas-instruments-product-information-openapi.yml\n  - type: JSONSchema\n    url: json-schema/ti-product-schema.json\n  - type: JSON-LD\n    url: json-ld/texas-instruments-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/texas-instruments-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/apis.yml
tags:
- Electronics
- Ordering
- Semiconductors
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/apis.yml
use_cases: []
---
