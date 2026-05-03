---
api_count: 1
api_specs:
- filename: dsco-platform-openapi.yml
  format: yaml
  label: Dsco Platform API
  slug: dsco-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/openapi/dsco-platform-openapi.yml
apis:
- description: The Dsco Platform API v3 provides dropship and marketplace commerce integration for retailers and suppliers. It supports order management, catalog synchronization, inventory updates, shipment tracking
  name: Dsco Platform API
  slug: dsco-platform-api
capabilities:
- description: Unified workflow capability for commerce operations on the Rithum / Dsco platform. Combines supplier and retailer workflows for order management, catalog synchronization, inventory updates, shipment t
  name: Rithum Commerce Operations
  slug: commerce-operations
common:
- title: ''
  type: Website
  url: https://www.rithum.com
- title: ''
  type: Documentation
  url: https://api.dsco.io/doc/v3/reference/
- title: ''
  type: Support
  url: https://knowledge.rithum.com
- title: ''
  type: Blog
  url: https://www.rithum.com/blog/
- title: ''
  type: PrivacyPolicy
  url: https://www.rithum.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.rithum.com/terms-of-service/
- title: ''
  type: Status
  url: https://status.rithum.com
- title: ''
  type: GitHub
  url: https://github.com/rithum
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-ld/rithum-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/vocabulary/rithum-vocabulary.yml
created: '2025-02-12'
description: Rithum is a commerce operations platform providing dropship, marketplace, and supply chain integration solutions for retailers, brands, and suppliers. Formerly known as CommerceHub and ChannelAdvisor, Rithum connects brands and retailers to manage product listings, inventory, order workflows, and performance across ecommerce channels. The platform powers the Dsco API for dropship and marketplace integrations. In 2025, Rithum launched RithumIQ, an AI engine for automated commerce recommendations and operational insights.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Rithum Context
  property_count: 0
  slug: rithum-context
layout: provider
modified: '2026-05-02'
name: Rithum
rules:
- name: Rithum API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 7
  slug: dsco-platform-rules
skills: []
slug: rithum
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rithum\nname: Rithum\ndescription: >-\n  Rithum is a commerce operations platform providing dropship, marketplace, and\n  supply chain integration solutions for retailers, brands, and suppliers.\n  Formerly known as CommerceHub and ChannelAdvisor, Rithum connects brands and\n  retailers to manage product listings, inventory, order workflows, and\n  performance across ecommerce channels. The platform powers the Dsco API\n  for dropship and marketplace integrations. In 2025, Rithum launched RithumIQ,\n  an AI engine for automated commerce recommendations and operational insights.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Commerce\n  - Dropship\n  - Marketplace\n  - Ecommerce\n  - Supply Chain\n  - Retail\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/apis.yml\ncreated: '2025-02-12'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rithum:dsco-platform-api\n\
  \    name: Dsco Platform API\n    description: >-\n      The Dsco Platform API v3 provides dropship and marketplace commerce\n      integration for retailers and suppliers. It supports order management,\n      catalog synchronization, inventory updates, shipment tracking, returns\n      processing, and invoice workflows via streaming and batch endpoints.\n      Authentication uses OAuth2 bearer tokens obtained from the token endpoint.\n    humanURL: https://api.dsco.io/\n    baseURL: https://api.dsco.io/api/v3\n    tags:\n      - Commerce\n      - Dropship\n      - Marketplace\n      - Orders\n      - Catalog\n      - Inventory\n    properties:\n      - url: https://api.dsco.io/doc/v3/reference/\n        type: Documentation\n      - url: https://api.dsco.io/doc/v3/guides/standard-api-guide.html\n        type: Guide\n      - url: https://api.dsco.io/doc/v3/guides/dropship-api-guide.html\n        type: Guide\n      - url: https://api.dsco.io/doc/v3/guides/marketplace-api-guide.html\n   \
  \     type: Guide\n      - url: https://knowledge.rithum.com/s/article/Getting-started-with-the-Rithum-V3-API\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/openapi/dsco-platform-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/rules/dsco-platform-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/capabilities/commerce-operations.yaml\n        type: NaftikoCapabilities\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-schema/dsco-order-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-schema/dsco-catalog-item-schema.json\n        type: JSONSchema\n    contact:\n      - FN: Rithum Support\n\
  \        url: https://knowledge.rithum.com\n    features:\n      - Order Management\n      - Catalog Synchronization\n      - Inventory Updates\n      - Shipment Tracking\n      - Returns Processing\n      - Invoice Workflows\n      - Streaming Events\n      - Batch Operations\n      - Dropship Integration\n      - Marketplace Integration\n    useCases:\n      - Retailer dropship order processing\n      - Supplier catalog and inventory sync\n      - Private marketplace management\n      - Multi-channel commerce operations\n    solutions:\n      - Commerce Operations\n      - Supply Chain Integration\n      - Retail Dropship\n    integrations:\n      - ChannelAdvisor\n      - Mirakl\n      - Shopify\n      - Salesforce Commerce Cloud\n\ncommon:\n  - type: Website\n    url: https://www.rithum.com\n  - type: Documentation\n    url: https://api.dsco.io/doc/v3/reference/\n  - type: Support\n    url: https://knowledge.rithum.com\n  - type: Blog\n    url: https://www.rithum.com/blog/\n  - type:\
  \ PrivacyPolicy\n    url: https://www.rithum.com/privacy-policy/\n  - type: TermsOfService\n    url: https://www.rithum.com/terms-of-service/\n  - type: Status\n    url: https://status.rithum.com\n  - type: GitHub\n    url: https://github.com/rithum\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-ld/rithum-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/vocabulary/rithum-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/apis.yml
tags:
- Commerce
- Dropship
- Marketplace
- Ecommerce
- Supply Chain
- Retail
url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/apis.yml
use_cases: []
---
