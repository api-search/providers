---
api_count: 3
api_specs:
- filename: target-target-api-openapi.yml
  format: yaml
  label: Target API
  slug: target-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/openapi/target-target-api-openapi.yml
apis:
- description: Target provides partner APIs for product catalog access, inventory availability, order management, and store information. These APIs enable technology partners and affiliates to integrate with Target'
  name: Target API
  slug: target-api
- description: Redsky is Target's internal aggregation API platform that converts GraphQL queries into client-managed REST APIs. It serves product data, pricing, promotions, and fulfillment information for Target.co
  name: Target Redsky API
  slug: target-redsky-api
- description: Target's partner API program enables technology vendors, affiliates, and supply chain partners to integrate with Target's retail operations including product catalog, inventory management, order fulfi
  name: Target Partner API
  slug: target-partner-api
capabilities:
- description: Unified retail integration capability for Target partner integrations. Combines product catalog, inventory availability, store locator, and order management APIs into customer-facing workflows for e-c
  name: Target Retail Integration
  slug: retail-integration
common:
- title: ''
  type: Website
  url: https://www.target.com
- title: ''
  type: Developer Portal
  url: https://developer.target.com/
- title: ''
  type: Blog
  url: https://tech.target.com
- title: ''
  type: GitHub Org
  url: https://github.com/target
- title: ''
  type: Open Source
  url: https://tech.target.com/open-source
- title: ''
  type: Status
  url: https://status.target.com
- title: ''
  type: JSONSchema
  url: json-schema/target-product-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/target-store-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/target-product-structure.json
- title: ''
  type: JSONLD
  url: json-ld/target-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/target-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/retail-integration.yaml
created: '2024-01-01'
description: Target Corporation is one of the largest retailers in the United States, offering a wide assortment of general merchandise and food through more than 1,900 stores and digital channels. Target's technology platform powers partner integrations, internal services, and open-source tooling across their retail operations.
features: []
image: ''
integrations: []
jsonld:
- class_count: 32
  name: Target Context
  property_count: 0
  slug: target-context
layout: provider
modified: '2026-05-03'
name: target
rules:
- name: target API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 8
  slug: target-spectral-rules
skills: []
slug: target
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: target\nurl: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\ndescription: >-\n  Target Corporation is one of the largest retailers in the United States, offering a wide\n  assortment of general merchandise and food through more than 1,900 stores and digital\n  channels. Target's technology platform powers partner integrations, internal services,\n  and open-source tooling across their retail operations.\napis:\n  - aid: target:target-api\n    name: Target API\n    tags:\n      - E-Commerce\n      - Inventory\n      - Orders\n      - Products\n      - Retail\n      - Stores\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.target.com\n    humanURL: https://developer.target.com/\n    properties:\n      - url: https://developer.target.com/\n        type: Documentation\n      - url: openapi/target-target-api-openapi.yml\n        type:\
  \ OpenAPI\n      - url: rules/target-spectral-rules.yml\n        type: SpectralRules\n      - url: capabilities/shared/target-api.yaml\n        type: NaftikoCapability\n    description: >-\n      Target provides partner APIs for product catalog access, inventory availability,\n      order management, and store information. These APIs enable technology partners\n      and affiliates to integrate with Target's retail platform. The Redsky aggregation\n      platform powers client-managed REST APIs built on GraphQL queries covering product,\n      price, promotion, and fulfillment data.\n  - aid: target:target-redsky-api\n    name: Target Redsky API\n    tags:\n      - E-Commerce\n      - GraphQL\n      - Products\n      - Retail\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://redsky.target.com\n    humanURL: https://tech.target.com/blog/empowering-clients-api\n    properties:\n      - url: https://tech.target.com/blog/empowering-clients-api\n\
  \        type: Documentation\n    description: >-\n      Redsky is Target's internal aggregation API platform that converts GraphQL queries\n      into client-managed REST APIs. It serves product data, pricing, promotions, and\n      fulfillment information for Target.com and mobile applications. The platform manages\n      200+ unique APIs across 30 clients backed by 50+ integrations.\n  - aid: target:target-partner-api\n    name: Target Partner API\n    tags:\n      - E-Commerce\n      - Inventory\n      - Partners\n      - Retail\n      - Suppliers\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.target.com\n    humanURL: https://developer.target.com/\n    properties:\n      - url: https://developer.target.com/\n        type: Documentation\n    description: >-\n      Target's partner API program enables technology vendors, affiliates, and supply\n      chain partners to integrate with Target's retail operations including\
  \ product catalog,\n      inventory management, order fulfillment, and store data.\ncommon:\n  - type: Website\n    url: https://www.target.com\n  - type: Developer Portal\n    url: https://developer.target.com/\n  - type: Blog\n    url: https://tech.target.com\n  - type: GitHub Org\n    url: https://github.com/target\n  - type: Open Source\n    url: https://tech.target.com/open-source\n  - type: Status\n    url: https://status.target.com\n  - type: JSONSchema\n    url: json-schema/target-product-schema.json\n  - type: JSONSchema\n    url: json-schema/target-store-schema.json\n  - type: JSONStructure\n    url: json-structure/target-product-structure.json\n  - type: JSONLD\n    url: json-ld/target-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/target-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/retail-integration.yaml\ntags:\n  - E-Commerce\n  - Retail\n  - Products\n  - Inventory\n  - Fortune 100\n  - Stores\n  - Orders\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/apis.yml
tags:
- E-Commerce
- Retail
- Products
- Inventory
- Fortune 100
- Stores
- Orders
url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/apis.yml
use_cases: []
---
