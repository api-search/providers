---
api_count: 1
api_specs:
- filename: sysco-food-distribution-api-openapi.yml
  format: yaml
  label: Sysco Food Distribution API
  slug: food-distribution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/openapi/sysco-food-distribution-api-openapi.yml
apis:
- description: The Sysco Food Distribution API provides programmatic access to Sysco's food distribution platform for product catalog browsing, order management, delivery tracking, account management, and pricing. A
  name: Sysco Food Distribution API
  slug: food-distribution-api
capabilities:
- description: Unified food supply chain capability for Sysco food distribution operations. Combines product catalog browsing, order management, delivery tracking, and pricing into a cohesive workflow for restaurant
  name: Sysco Food Supply Chain
  slug: food-supply-chain
common:
- title: ''
  type: Website
  url: https://www.sysco.com
- title: ''
  type: DeveloperPortal
  url: https://apic-devportal.sysco.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/SyscoCorporation
- title: ''
  type: GraphQL
  url: https://www.apollographql.com/customers/sysco
- title: ''
  type: JSONLDContext
  url: json-ld/sysco-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sysco-vocabulary.yml
created: '2026-05-03'
description: Sysco is the global leader in selling, marketing, and distributing food products to restaurants, healthcare and educational facilities, lodging establishments, and other foodservice customers. Sysco's APIC Developer Portal provides REST APIs for product catalog browsing, order management, delivery tracking, account management, and pricing integration, enabling partners and customers to automate their food distribution workflows.
features: []
image: ''
integrations: []
jsonld:
- class_count: 24
  name: Sysco Context
  property_count: 4
  slug: sysco-context
layout: provider
modified: '2026-05-03'
name: Sysco
rules:
- name: Sysco API Rules
  rule_count: 13
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 6
  slug: sysco-rules
skills: []
slug: sysco
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sysco\nname: Sysco\ndescription: >-\n  Sysco is the global leader in selling, marketing, and distributing food products\n  to restaurants, healthcare and educational facilities, lodging establishments, and\n  other foodservice customers. Sysco's APIC Developer Portal provides REST APIs for\n  product catalog browsing, order management, delivery tracking, account management,\n  and pricing integration, enabling partners and customers to automate their food\n  distribution workflows.\nurl: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\ntags:\n  - Food Distribution\n  - Food Service\n  - Supply Chain\n  - Fortune 100\n  - Wholesale\napis:\n  - aid: sysco:food-distribution-api\n    name: Sysco Food Distribution API\n    description: >-\n      The Sysco Food Distribution API provides programmatic access to Sysco's food\n      distribution platform for product catalog browsing, order management,\
  \ delivery\n      tracking, account management, and pricing. Available through the Sysco APIC\n      Developer Portal, the APIs enable partners, restaurants, and food service\n      operators to integrate with Sysco's ordering systems, browse product catalogs\n      with over 30 data fields, track deliveries, and manage their food supply chain\n      operations.\n    humanURL: https://apic-devportal.sysco.com/\n    baseURL: https://api.sysco.com\n    tags:\n      - Food Distribution\n      - Ordering\n      - Restaurant\n      - Supply Chain\n      - Product Catalog\n      - Delivery Tracking\n    properties:\n      - type: Documentation\n        url: https://apic-devportal.sysco.com/\n      - type: OpenAPI\n        url: openapi/sysco-food-distribution-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.sysco.com\n  - type: DeveloperPortal\n    url: https://apic-devportal.sysco.com/\n  - type: GitHubOrg\n    url: https://github.com/SyscoCorporation\n  - type: GraphQL\n\
  \    url: https://www.apollographql.com/customers/sysco\n  - type: JSONLDContext\n    url: json-ld/sysco-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sysco-vocabulary.yml\nfeatures:\n  - Product Catalog with 30+ Data Fields\n  - Real-Time Stock Status\n  - Order Management\n  - Delivery Tracking\n  - Contract Pricing\n  - Account Management\n  - GraphQL API (Apollo)\n  - Staging and Production Environments\nuseCases:\n  - Food Service Ordering Automation\n  - Product Catalog Integration\n  - Delivery Schedule Management\n  - Supply Chain Visibility\n  - ERP Integration\n  - Restaurant Management System Integration\nintegrations:\n  - type: ApolloGraphQL\n    description: Sysco uses Apollo's graph-based API orchestration with domain subgraphs\n  - type: Portable\n    url: https://portable.io/connectors/sysco/postgresql\nsolutions:\n  - Restaurant Technology Integration\n  - Healthcare Food Service\n  - Education Food Service\n  - Hospitality Supply Chain\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/apis.yml
tags:
- Food Distribution
- Food Service
- Supply Chain
- Fortune 100
- Wholesale
url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/apis.yml
use_cases: []
---
