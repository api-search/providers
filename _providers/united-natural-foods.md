---
api_count: 2
api_specs:
- filename: unfi-supplier-openapi.yml
  format: yaml
  label: UNFI Harmony Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/openapi/unfi-supplier-openapi.yml
apis:
- description: UNFI's Harmony Core API provides read-only access to 42 data files covering supplier, product, inventory, and sales data across UNFI's distribution network. Consumers can perform SQL-style queries inc
  name: UNFI Harmony Core API
  slug: ''
- description: UNFI supports Electronic Data Interchange (EDI) for automated exchanges of purchase orders, invoices, and fulfillment data between UNFI and its supplier and retail partners. EDI integration supports t
  name: UNFI EDI Integration
  slug: ''
capabilities:
- description: United Natural Foods (UNFI) supplier management capability combining product catalog, purchase order management, fulfillment tracking, and supply chain analytics. Used by suppliers, retailers, and dat
  name: UNFI Supplier Management
  slug: supplier-management
common:
- title: ''
  type: Website
  url: https://www.unfi.com
- title: ''
  type: Supplier Portal
  url: https://suppliers.unfi.com
- title: ''
  type: Customer Portal
  url: https://www.myunfi.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/unfi
- title: ''
  type: X
  url: https://twitter.com/UNFIInc
- title: ''
  type: Investor Relations
  url: https://ir.unfi.com
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/openapi/unfi-supplier-openapi.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/rules/unfi-supplier-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/capabilities/supplier-management.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-schema/unfi-supplier-product-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-schema/unfi-supplier-order-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-ld/united-natural-foods-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/vocabulary/united-natural-foods-vocabulary.yml
created: '2026-03-21'
description: United Natural Foods, Inc. (UNFI) is the largest publicly traded wholesale distributor of health and specialty food in the United States and Canada. UNFI supplies natural, organic, specialty, and conventional foods to over 30,000 retail locations. UNFI provides digital supplier and customer portals including myUNFI, supplier portal, EDI integration, and the Harmony Core API for data access.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: United Natural Foods Context
  property_count: 28
  slug: united-natural-foods-context
layout: provider
modified: '2026-05-03'
name: United Natural Foods (UNFI)
rules:
- name: United Natural Foods (UNFI) API Rules
  rule_count: 15
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 9
  slug: unfi-supplier-rules
skills: []
slug: united-natural-foods
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-natural-foods\nurl: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nname: United Natural Foods (UNFI)\ndescription: >-\n  United Natural Foods, Inc. (UNFI) is the largest publicly traded wholesale\n  distributor of health and specialty food in the United States and Canada. UNFI\n  supplies natural, organic, specialty, and conventional foods to over 30,000 retail\n  locations. UNFI provides digital supplier and customer portals including myUNFI,\n  supplier portal, EDI integration, and the Harmony Core API for data access.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Food Distribution\n  - Wholesale\n  - Natural Foods\n  - Supply Chain\n  - Fortune 500\napis:\n  - name: UNFI Harmony Core API\n    description: >-\n      UNFI's Harmony Core API provides read-only access to 42 data files covering\n      supplier, product, inventory,\
  \ and sales data across UNFI's distribution network.\n      Consumers can perform SQL-style queries including field selection and multi-table\n      joins. Used by suppliers, retailers, and analytics platforms like Crisp to\n      access UNFI Insights data.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://suppliers.unfi.com\n    baseURL: https://api.unfi.com/v1\n    tags:\n      - Food Distribution\n      - Supply Chain\n      - Analytics\n      - Wholesale\n      - Data API\n    properties:\n      - type: Documentation\n        url: https://suppliers.unfi.com\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/openapi/unfi-supplier-openapi.yml\n  - name: UNFI EDI Integration\n    description: >-\n      UNFI supports Electronic Data Interchange (EDI) for automated exchanges of\n      purchase orders, invoices, and fulfillment data between UNFI and its supplier\n    \
  \  and retail partners. EDI integration supports the procure-to-pay lifecycle\n      for both suppliers and retailers.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://suppliers.unfi.com\n    baseURL: https://api.unfi.com/v1\n    tags:\n      - EDI\n      - Supply Chain\n      - Procurement\n      - Invoicing\n    properties:\n      - type: Documentation\n        url: https://suppliers.unfi.com\ncommon:\n  - type: Website\n    url: https://www.unfi.com\n  - type: Supplier Portal\n    url: https://suppliers.unfi.com\n  - type: Customer Portal\n    url: https://www.myunfi.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/unfi\n  - type: X\n    url: https://twitter.com/UNFIInc\n  - type: Investor Relations\n    url: https://ir.unfi.com\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/openapi/unfi-supplier-openapi.yml\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/rules/unfi-supplier-rules.yml\n\
  \  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/capabilities/supplier-management.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-schema/unfi-supplier-product-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-schema/unfi-supplier-order-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/json-ld/united-natural-foods-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/vocabulary/united-natural-foods-vocabulary.yml\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/apis.yml
tags:
- Food Distribution
- Wholesale
- Natural Foods
- Supply Chain
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/apis.yml
use_cases: []
---
