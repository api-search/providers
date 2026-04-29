---
api_count: 1
api_specs:
- filename: acuity-brands.json
  format: json
  label: Acuity Brands API
  slug: acuity-brands-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/openapi/acuity-brands.json
apis:
- description: B2B REST APIs for Acuity Brands distributors covering inventory availability, order status tracking, product catalog, and web content. Enables integration of Acuity Brands data into distributor ERP, e
  name: Acuity Brands API
  slug: acuity-brands-api
capabilities:
- description: Workflow for distributor integration with Acuity Brands covering inventory lookup, order status tracking, product catalog search, and shipment tracking. Used by electrical distributors integrating Acu
  name: Acuity Brands Distributor Integration
  slug: distributor-integration
common:
- title: ''
  type: Website
  url: https://www.acuity-brands.com
- title: ''
  type: Portal
  url: https://api-docs.acuitybrands.com/
- title: ''
  type: Documentation
  url: https://api-docs.acuitybrands.com/docs/intro/
- title: ''
  type: GitHubOrganization
  url: https://github.com/acuitybrands
- title: ''
  type: SpectralRules
  url: rules/acuity-brands-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/acuity-brands-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/distributor-integration.yaml
- title: ''
  type: JSONLD
  url: json-ld/acuity-brands-context.jsonld
created: ''
description: Acuity Brands is a provider of lighting, lighting controls, building management systems, and location-aware applications for commercial, industrial, institutional, and residential markets.
features: []
image: /assets/icons/acuity-brands.png
integrations: []
jsonld:
- class_count: 50
  name: Acuity Brands Context
  property_count: 7
  slug: acuity-brands-context
layout: provider
modified: '2026-04-19'
name: acuity-brands
rules:
- name: acuity-brands API Rules
  rule_count: 23
  severity_counts:
    error: 9
    hint: 0
    info: 2
    warn: 12
  slug: acuity-brands-spectral-rules
skills: []
slug: acuity-brands
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: acuity-brands\nurl: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n  - aid: acuity-brands:acuity-brands-api\n    name: Acuity Brands API\n    tags:\n      - Lighting\n      - B2B\n      - Inventory\n      - Order Management\n      - Building Controls\n    properties:\n      - type: HumanURL\n        url: https://api-docs.acuitybrands.com/\n      - type: BaseURL\n        url: https://api.acuitybrands.com/v1\n      - type: OpenAPI\n        url: openapi/acuity-brands.json\n      - type: JSONSchema\n        url: json-schema/\n      - type: JSONStructure\n        url: json-structure/\n      - type: Examples\n        url: examples/\n    description: >-\n      B2B REST APIs for Acuity Brands distributors covering inventory availability,\n      order status tracking, product catalog, and web content. Enables integration\n      of Acuity Brands data into distributor ERP, e-commerce, and ordering systems.\n\
  common:\n  - type: Website\n    url: https://www.acuity-brands.com\n  - type: Portal\n    url: https://api-docs.acuitybrands.com/\n  - type: Documentation\n    url: https://api-docs.acuitybrands.com/docs/intro/\n  - type: GitHubOrganization\n    url: https://github.com/acuitybrands\n  - type: SpectralRules\n    url: rules/acuity-brands-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/acuity-brands-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/distributor-integration.yaml\n  - type: JSONLD\n    url: json-ld/acuity-brands-context.jsonld\ndescription: >-\n  Acuity Brands is a provider of lighting, lighting controls, building management\n  systems, and location-aware applications for commercial, industrial, institutional,\n  and residential markets.\nfeatures:\n  - name: Inventory Availability\n    description: Real-time inventory availability by product number and warehouse location with estimated ship dates.\n    tags:\n      - Inventory\n      - Lighting\n\
  \  - name: Order Status Tracking\n    description: Full order status data including estimated and actual ship dates, line item status, and order totals.\n    tags:\n      - Orders\n      - B2B\n  - name: Shipment Tracking\n    description: Carrier name, PRO number, and tracking URLs for all shipments associated with an order.\n    tags:\n      - Shipments\n      - Logistics\n  - name: Product Catalog\n    description: Search and retrieve Acuity Brands product catalog with specifications, certifications, pricing, and images.\n    tags:\n      - Catalog\n      - Products\n  - name: Web Content\n    description: Product and category web pages with metadata and content for distributor e-commerce integration.\n    tags:\n      - Web Content\n      - E-Commerce\n  - name: Multi-Brand Coverage\n    description: APIs cover all major Acuity Brands brands including Lithonia Lighting, Holophane, nLight, Juno, and Distech Controls.\n    tags:\n      - Brands\n      - Lighting\nuseCases:\n  - name:\
  \ ERP Integration\n    description: Sync inventory and order data into distributor ERP systems for automated stock management and order tracking.\n    tags:\n      - ERP\n      - Integration\n  - name: E-Commerce Product Feeds\n    description: Pull product catalog, images, specs, and pricing into distributor e-commerce storefronts.\n    tags:\n      - E-Commerce\n      - Catalog\n  - name: Order Status Automation\n    description: Automatically surface order status and shipment tracking to customers without manual ADC lookups.\n    tags:\n      - Orders\n      - Automation\n  - name: Inventory Availability Checks\n    description: Check real-time stock availability before quoting or placing orders for Acuity Brands products.\n    tags:\n      - Inventory\n      - Quoting\nintegrations:\n  - name: SAP\n    description: Integrate Acuity Brands inventory and order data into SAP ERP for automated purchasing workflows.\n    tags:\n      - SAP\n      - ERP\n  - name: Salesforce\n    description:\
  \ Surface product availability and order status within Salesforce CRM for distributor sales reps.\n    tags:\n      - Salesforce\n      - CRM\n  - name: Epicor\n    description: Connect Acuity Brands order status to Epicor distribution ERP systems.\n    tags:\n      - Epicor\n      - ERP\nsolutions:\n  - name: Distributor API Access\n    description: API access available to authorized Acuity Brands distributors via request through the developer portal.\n    tags:\n      - Distributor\n      - Access\n  - name: B2B Digital Integration\n    description: Enable fully digital order-to-shipment workflows between Acuity Brands and electrical distributors.\n    tags:\n      - B2B\n      - Digital\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/acuity-brands/refs/heads/main/apis.yml
use_cases: []
---
