---
api_count: 1
api_specs:
- filename: dana-aftermarket-api-openapi.yml
  format: yaml
  label: Dana Aftermarket API
  slug: aftermarket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/openapi/dana-aftermarket-api-openapi.yml
apis:
- description: The Dana Aftermarket API provides programmatic access to Dana's aftermarket e-commerce platform with eight active APIs including advanced shipping notification, availability, deep linking, order statu
  name: Dana Aftermarket API
  slug: aftermarket-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dana.com/
- title: ''
  type: Portal
  url: https://developer.danaaftermarket.com/
- title: ''
  type: JSON-LD
  url: json-ld/dana-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dana-vocabulary.yml
created: '2026-03-21'
description: Dana Incorporated is a global supplier of fully integrated drivetrain and electrified propulsion systems for passenger vehicles, commercial trucks, and off-highway equipment. Dana operates a developer portal at developer.danaaftermarket.com offering eight APIs for aftermarket parts search, availability, pricing, ordering, and shipment tracking across its global distribution network.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Dana Context
  property_count: 13
  slug: dana-context
layout: provider
modified: '2026-04-28'
name: Dana
rules:
- name: Dana API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dana-aftermarket-api-rules
skills: []
slug: dana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dana\nname: Dana\nurl: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/apis.yml\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Aftermarket\n  - Auto Parts\n  - Drivetrain\n  - eCommerce\n  - Supply Chain\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\napis:\n  - aid: dana:aftermarket-api\n    name: Dana Aftermarket API\n    tags:\n      - Aftermarket\n      - Auto Parts\n      - Drivetrain\n      - eCommerce\n      - Supply Chain\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.danaaftermarket.com\n    humanURL: https://developer.danaaftermarket.com/\n    properties:\n      - url: https://developer.danaaftermarket.com/\n        type: Portal\n      - url: https://developer.danaaftermarket.com/\n        type: Documentation\n      - url: openapi/dana-aftermarket-api-openapi.yml\n\
  \        type: OpenAPI\n      - url: json-schema/part.json\n        type: JSONSchema\n      - url: json-schema/order.json\n        type: JSONSchema\n      - url: rules/dana-aftermarket-api-rules.yml\n        type: Rules\n      - url: capabilities/dana-aftermarket-api-capabilities.yml\n        type: Capabilities\n    description: >-\n      The Dana Aftermarket API provides programmatic access to Dana's\n      aftermarket e-commerce platform with eight active APIs including advanced\n      shipping notification, availability, deep linking, order status, part\n      details, part search by application, place order, and pricing. The APIs\n      enable customers to display inventory availability from Dana's global\n      distribution network, obtain real-time quotes, and manage orders with\n      confirmation, shipping details, packing slips, and tracking numbers.\ncommon:\n  - type: Website\n    url: https://www.dana.com/\n  - type: Portal\n    url: https://developer.danaaftermarket.com/\n\
  \  - type: JSON-LD\n    url: json-ld/dana-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dana-vocabulary.yml\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\ndescription: >-\n  Dana Incorporated is a global supplier of fully integrated drivetrain and\n  electrified propulsion systems for passenger vehicles, commercial trucks,\n  and off-highway equipment. Dana operates a developer portal at\n  developer.danaaftermarket.com offering eight APIs for aftermarket parts\n  search, availability, pricing, ordering, and shipment tracking across its\n  global distribution network.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/apis.yml
tags:
- Aftermarket
- Auto Parts
- Drivetrain
- eCommerce
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/apis.yml
use_cases: []
---
