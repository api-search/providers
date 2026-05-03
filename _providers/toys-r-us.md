---
api_count: 1
api_specs:
- filename: toys-r-us-commerce-openapi.yml
  format: yaml
  label: Toys R Us Commerce API
  slug: logicbroker-commerce
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/openapi/toys-r-us-commerce-openapi.yml
apis:
- description: The Toys R Us Commerce API, powered by LogicBroker, enables supplier and dropship vendor integrations for the complete order lifecycle. Supports purchase order retrieval (EDI 850), order acknowledgeme
  name: Toys R Us Commerce API
  slug: logicbroker-commerce
capabilities:
- description: Unified dropship fulfillment workflow for Toys R Us supplier integrations. Combines order retrieval, acknowledgement, shipment notification, invoice submission, and product catalog synchronization for
  name: Toys R Us Dropship Fulfillment
  slug: dropship-fulfillment
common:
- title: ''
  type: Website
  url: https://www.toysrus.com
- title: ''
  type: SupplierPortal
  url: https://toysrus.logicbroker.com
- title: ''
  type: Documentation
  url: https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation
- title: ''
  type: DeveloperPortal
  url: https://dev.logicbroker.com
created: '2026-03-24'
description: Toys 'R' Us is a leading toys and juvenile-products retailer offering a vast selection of toys, games, baby products, and children's apparel through retail stores and e-commerce sites. The brand integrates with suppliers and dropship vendors via the LogicBroker commerce platform, providing APIs for order management, shipment processing, product catalog synchronization, and invoice workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Toys R Us Context
  property_count: 0
  slug: toys-r-us-context
layout: provider
modified: '2026-05-03'
name: Toys R Us
rules:
- name: Toys R Us API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: toys-r-us-rules
skills: []
slug: toys-r-us
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toys-r-us\nname: Toys R Us\ndescription: >-\n  Toys 'R' Us is a leading toys and juvenile-products retailer offering a vast\n  selection of toys, games, baby products, and children's apparel through retail\n  stores and e-commerce sites. The brand integrates with suppliers and dropship\n  vendors via the LogicBroker commerce platform, providing APIs for order\n  management, shipment processing, product catalog synchronization, and invoice\n  workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Commerce\n  - Dropship\n  - E-Commerce\n  - Retail\n  - Supply Chain\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: toys-r-us:logicbroker-commerce\n    name: Toys R Us Commerce API\n    description: >-\n      The Toys R Us Commerce API, powered by LogicBroker, enables supplier\
  \ and\n      dropship vendor integrations for the complete order lifecycle. Supports\n      purchase order retrieval (EDI 850), order acknowledgement (EDI 855),\n      shipment notification (EDI 856), invoice processing (EDI 810), and\n      product catalog synchronization. Vendors authenticate using an API\n      subscription key.\n    humanURL: https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation\n    baseURL: https://commerceapi.io\n    tags:\n      - Commerce\n      - Dropship\n      - E-Commerce\n      - Invoices\n      - Order Management\n      - Retail\n      - Shipments\n      - Supplier Integration\n    properties:\n      - type: Documentation\n        url: https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation\n      - type: OpenAPI\n        url: openapi/toys-r-us-commerce-openapi.yml\n      - type: JSONSchema\n        url: json-schema/toys-r-us-order-schema.json\n      - type: JSONStructure\n        url: json-structure/toys-r-us-order-structure.json\n\
  \      - type: JSONLd\n        url: json-ld/toys-r-us-context.jsonld\n      - type: SpectralRules\n        url: rules/toys-r-us-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/dropship-fulfillment.yaml\n      - type: Vocabulary\n        url: vocabulary/toys-r-us-vocabulary.yml\n      - type: Swagger\n        url: https://commerceapi.io/swagger/ui/index\n      - type: SwaggerStage\n        url: https://stage.commerceapi.io/swagger/ui/index\ncommon:\n  - type: Website\n    url: https://www.toysrus.com\n  - type: SupplierPortal\n    url: https://toysrus.logicbroker.com\n  - type: Documentation\n    url: https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation\n  - type: DeveloperPortal\n    url: https://dev.logicbroker.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/apis.yml
tags:
- Commerce
- Dropship
- E-Commerce
- Retail
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/apis.yml
use_cases: []
---
