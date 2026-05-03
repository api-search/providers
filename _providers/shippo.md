---
api_count: 1
api_specs:
- filename: shippo-openapi.yml
  format: yaml
  label: Shippo API
  slug: shippo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/openapi/shippo-openapi.yml
apis:
- description: Shippo is a multi-carrier shipping API that enables developers to add complete shipping functionality to their applications. The API supports address validation, carrier rate comparison across USPS, U
  name: Shippo API
  slug: shippo-api
capabilities:
- description: 'Unified shipping fulfillment workflow combining address validation, multi-carrier rate shopping, label generation, and package tracking. Designed for ecommerce developers and operations teams needing '
  name: Shippo Shipping Fulfillment
  slug: shipping-fulfillment
common:
- title: ''
  type: Documentation
  url: https://docs.goshippo.com/
- title: ''
  type: API Reference
  url: https://docs.goshippo.com/shippoapi/public-api
- title: ''
  type: SDKs
  url: https://docs.goshippo.com/docs/guides_general/clientlibraries
- title: ''
  type: Getting Started
  url: https://support.goshippo.com/hc/en-us/articles/4404415886491-Shippo-API-Quick-Start-Guide
- title: ''
  type: Pricing
  url: https://goshippo.com/pricing/api
- title: ''
  type: GitHub Organization
  url: https://github.com/goshippo
- title: ''
  type: Developer Portal
  url: https://goshippo.com/products/api
- title: ''
  type: Website
  url: https://goshippo.com
created: '2025-03-01'
description: Shippo provides a robust shipping API architecture that helps developers drive efficiency at scale. The Shippo API covers the complete shipping lifecycle from pre-purchase rate shopping across 80+ carriers to label generation, package tracking, and returns management. SDKs are available for Python, JavaScript, PHP, Java, Ruby, and Node.js.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 41
  name: Shippo Context
  property_count: 18
  slug: shippo-context
layout: provider
modified: '2026-05-02'
name: Shippo
rules:
- name: Shippo API Rules
  rule_count: 14
  severity_counts:
    error: 3
    hint: 0
    info: 4
    warn: 7
  slug: shippo-rules
skills: []
slug: shippo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shippo\nurl: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/apis.yml\napis:\n  - aid: shippo:shippo-api\n    name: Shippo API\n    tags:\n      - Ecommerce\n      - Labels\n      - Logistics\n      - Shipping\n      - Tracking\n    humanURL: https://docs.goshippo.com/\n    properties:\n      - url: https://docs.goshippo.com/\n        type: Documentation\n      - url: openapi/shippo-openapi.yml\n        type: OpenAPI\n      - url: https://docs.goshippo.com/spec/shippoapi/public-api.yaml\n        type: OpenAPI\n      - url: https://github.com/goshippo/shippo-python-sdk\n        type: SDK\n      - url: https://github.com/goshippo/shippo-javascript-sdk\n        type: SDK\n      - url: https://github.com/goshippo/shippo-php-client\n        type: SDK\n      - url: https://github.com/goshippo/shippo-java-client\n        type: SDK\n      - url: https://github.com/goshippo/shippo-ruby-client\n        type: SDK\n      - url: https://github.com/goshippo/shippo-node-client\n\
  \        type: SDK\n      - url: json-schema/shippo-shipment-schema.json\n        type: JSONSchema\n      - url: json-schema/shippo-transaction-schema.json\n        type: JSONSchema\n      - url: json-ld/shippo-context.jsonld\n        type: JSONLD\n      - url: rules/shippo-rules.yml\n        type: SpectralRules\n      - url: capabilities/shipping-fulfillment.yaml\n        type: NaftikoCapabilities\n      - url: vocabulary/shippo-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      Shippo is a multi-carrier shipping API that enables developers to add\n      complete shipping functionality to their applications. The API supports\n      address validation, carrier rate comparison across USPS, UPS, FedEx,\n      DHL, and 80+ other carriers, label generation, package tracking,\n      returns management, and webhook notifications. Shippo's API drives\n      efficiency at scale from pre-purchase to returns.\nname: Shippo\ntags:\n  - Ecommerce\n  - Labels\n  - Logistics\n  - Returns\n\
  \  - Shipping\n  - Tracking\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nposition: Consumer\ndescription: >-\n  Shippo provides a robust shipping API architecture that helps developers\n  drive efficiency at scale. The Shippo API covers the complete shipping\n  lifecycle from pre-purchase rate shopping across 80+ carriers to label\n  generation, package tracking, and returns management. SDKs are available\n  for Python, JavaScript, PHP, Java, Ruby, and Node.js.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://docs.goshippo.com/\n    type: Documentation\n  - url: https://docs.goshippo.com/shippoapi/public-api\n    type: API Reference\n  - url: https://docs.goshippo.com/docs/guides_general/clientlibraries\n    type: SDKs\n  - url: https://support.goshippo.com/hc/en-us/articles/4404415886491-Shippo-API-Quick-Start-Guide\n\
  \    type: Getting Started\n  - url: https://goshippo.com/pricing/api\n    type: Pricing\n  - url: https://github.com/goshippo\n    type: GitHub Organization\n  - url: https://goshippo.com/products/api\n    type: Developer Portal\n  - url: https://goshippo.com\n    type: Website\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/apis.yml
tags:
- Ecommerce
- Labels
- Logistics
- Returns
- Shipping
- Tracking
url: https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/apis.yml
use_cases: []
---
