---
api_count: 5
api_specs:
- filename: manhattan-associates-omni-openapi.yml
  format: yaml
  label: Manhattan Active Omni and Enterprise Promise & Fulfill API
  slug: manhattan-active-omni-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-omni-openapi.yml
- filename: manhattan-associates-wms-openapi.yml
  format: yaml
  label: Manhattan Active Supply Chain API
  slug: manhattan-active-supply-chain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-wms-openapi.yml
apis:
- description: Manhattan Active Platform APIs provide core platform capabilities for authentication, tenant configuration, and integration with Manhattan Active solutions. REST APIs follow OAuth client credentials f
  name: Manhattan Active Platform API
  slug: manhattan-active-platform-api
- description: Manhattan Active Omni APIs enable omnichannel order management and fulfillment, including order promising, order orchestration, inventory availability, and customer service operations for retail and d
  name: Manhattan Active Omni and Enterprise Promise & Fulfill API
  slug: manhattan-active-omni-api
- description: Manhattan Active Supply Chain APIs provide warehouse management (WMS) capabilities including inventory tracking, order processing, labor management, yard management, and shipment execution for distrib
  name: Manhattan Active Supply Chain API
  slug: manhattan-active-supply-chain-api
- description: Manhattan Active Supply Chain Planning APIs provide demand forecasting, inventory optimization, and replenishment planning capabilities to optimize stock levels and reduce carrying costs across supply
  name: Manhattan Active Supply Chain Planning API
  slug: manhattan-active-supply-chain-planning-api
- description: Manhattan Associates provides warehouse management (WMS) and transportation management (TMS) APIs for supply chain execution. APIs enable order management, inventory tracking, shipment planning, labor
  name: Manhattan Associates TMS/WMS API
  slug: manhattan-associates-api
common:
- title: ''
  type: Portal
  url: https://developer.manh.com/
- title: ''
  type: Website
  url: https://www.manh.com/
- title: ''
  type: GettingStarted
  url: https://developer.manh.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.manh.com/docs/how-to/rest-api/
- title: ''
  type: Documentation
  url: https://api.developer.manh.com/
- title: ''
  type: TermsOfService
  url: https://www.manh.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.manh.com/privacy-policy
- title: ''
  type: Blog
  url: https://www.manh.com/our-insights/resources/blog
- title: ''
  type: Support
  url: https://www.manh.com/trust-center
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-omni-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-wms-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-schema/manhattan-associates-order-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-ld/manhattan-associates-context.jsonld
created: ''
description: Manhattan Associates is a leading provider of supply chain commerce solutions, enabling unified commerce across stores, warehouses, and inventory across the supply chain.
features: []
image: ''
integrations: []
jsonld:
- class_count: 22
  name: Manhattan Associates Context
  property_count: 13
  slug: manhattan-associates-context
layout: provider
modified: '2026-04-28'
name: manhattan-associates
skills: []
slug: manhattan-associates
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: manhattan-associates\nurl: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/apis.yml\napis:\n  - aid: manhattan-associates:manhattan-active-platform-api\n    name: Manhattan Active Platform API\n    tags:\n      - Logistics\n      - Platform\n      - SaaS\n      - Supply Chain\n    image: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/image.png\n    humanURL: https://platform.developer.manh.com/\n    baseURL: https://api.developer.manh.com\n    properties:\n      - url: https://platform.developer.manh.com/\n        type: Documentation\n      - url: https://developer.manh.com/docs/getting-started\n        type: GettingStarted\n      - url: https://developer.manh.com/docs/how-to/rest-api/\n        type: Authentication\n    description: >-\n      Manhattan Active Platform APIs provide core platform capabilities for authentication,\n      tenant configuration, and integration with Manhattan Active\
  \ solutions. REST\n      APIs follow OAuth client credentials flows and require platform administrator\n      setup.\n  - aid: manhattan-associates:manhattan-active-omni-api\n    name: Manhattan Active Omni and Enterprise Promise & Fulfill API\n    tags:\n      - Fulfillment\n      - Logistics\n      - Omnichannel\n      - Order Management\n    image: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/image.png\n    humanURL: https://omni.developer.manh.com/\n    baseURL: https://api.developer.manh.com\n    properties:\n      - url: https://omni.developer.manh.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-omni-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-schema/manhattan-associates-order-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-ld/manhattan-associates-context.jsonld\n\
  \        type: JSONLDContext\n    description: >-\n      Manhattan Active Omni APIs enable omnichannel order management and fulfillment,\n      including order promising, order orchestration, inventory availability, and\n      customer service operations for retail and distribution.\n  - aid: manhattan-associates:manhattan-active-supply-chain-api\n    name: Manhattan Active Supply Chain API\n    tags:\n      - Logistics\n      - Supply Chain\n      - Warehouse\n      - WMS\n    image: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/image.png\n    humanURL: https://supplychain.developer.manh.com/\n    baseURL: https://api.developer.manh.com\n    properties:\n      - url: https://supplychain.developer.manh.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-wms-openapi.yml\n        type: OpenAPI\n    description: >-\n      Manhattan Active Supply\
  \ Chain APIs provide warehouse management (WMS) capabilities\n      including inventory tracking, order processing, labor management, yard management,\n      and shipment execution for distribution center operations.\n  - aid: manhattan-associates:manhattan-active-supply-chain-planning-api\n    name: Manhattan Active Supply Chain Planning API\n    tags:\n      - Inventory Planning\n      - Logistics\n      - Planning\n      - Supply Chain\n    image: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/image.png\n    humanURL: https://scp.developer.manh.com/\n    baseURL: https://api.developer.manh.com\n    properties:\n      - url: https://scp.developer.manh.com/\n        type: Documentation\n    description: >-\n      Manhattan Active Supply Chain Planning APIs provide demand forecasting, inventory\n      optimization, and replenishment planning capabilities to optimize stock levels\n      and reduce carrying costs across supply chain networks.\n  - aid:\
  \ manhattan-associates:manhattan-associates-api\n    name: Manhattan Associates TMS/WMS API\n    tags:\n      - Logistics\n      - Supply Chain\n      - Transportation\n      - Warehouse\n    image: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/image.png\n    humanURL: https://www.manh.com/\n    baseURL: https://api.manh.example.com\n    properties:\n      - url: https://www.manh.com/\n        type: Documentation\n    description: >-\n      Manhattan Associates provides warehouse management (WMS) and transportation\n      management (TMS) APIs for supply chain execution. APIs enable order management,\n      inventory tracking, shipment planning, labor management, and yard management\n      for distribution and logistics operations.\ncommon:\n  - url: https://developer.manh.com/\n    type: Portal\n  - url: https://www.manh.com/\n    type: Website\n  - url: https://developer.manh.com/docs/getting-started\n    type: GettingStarted\n  - url: https://developer.manh.com/docs/how-to/rest-api/\n\
  \    type: Authentication\n  - url: https://api.developer.manh.com/\n    type: Documentation\n  - url: https://www.manh.com/terms-of-use\n    type: TermsOfService\n  - url: https://www.manh.com/privacy-policy\n    type: PrivacyPolicy\n  - url: https://www.manh.com/our-insights/resources/blog\n    type: Blog\n  - url: https://www.manh.com/trust-center\n    type: Support\n  - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-omni-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/openapi/manhattan-associates-wms-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-schema/manhattan-associates-order-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/json-ld/manhattan-associates-context.jsonld\n\
  \    type: JSONLDContext\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\nmodified: '2026-04-28'\ndescription: >-\n  Manhattan Associates is a leading provider of supply chain commerce solutions, enabling\n  unified commerce across stores, warehouses, and inventory across the supply chain.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/manhattan-associates/refs/heads/main/apis.yml
use_cases: []
---
