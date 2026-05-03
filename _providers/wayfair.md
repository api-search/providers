---
api_count: 1
api_specs:
- filename: wayfair-supplier-api.yml
  format: yaml
  label: Wayfair Supplier API
  slug: wayfair-supplier-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/openapi/wayfair-supplier-api.yml
apis:
- description: GraphQL-based API for Wayfair suppliers to manage orders, inventory, product catalogs, shipping notifications, and returns. Provides access to purchase orders, inventory updates, catalog management, a
  name: Wayfair Supplier API
  slug: wayfair-supplier-api
capabilities:
- description: Workflow capability combining Wayfair's GraphQL Supplier API to enable end-to-end supplier operations including order management, inventory synchronization, catalog management, and shipping automation
  name: Wayfair Supplier Operations
  slug: supplier-operations
common:
- title: Developer Portal
  type: Portal
  url: https://developer.wayfair.com/docs/
- title: Developer Portal (Introduction)
  type: Portal
  url: https://developer.wayfair.io/posts/introduction
- title: GraphQL Documentation
  type: Documentation
  url: https://developer.wayfair.io/posts/graphQL
- title: Sandbox API Testing
  type: Documentation
  url: https://developer.wayfair.io/posts/api-testing
- title: Wayfair Website
  type: Website
  url: https://www.wayfair.com/
- title: About Wayfair
  type: About
  url: https://www.aboutwayfair.com/
- title: Wayfair GitHub Organization
  type: GitHubOrganization
  url: https://github.com/wayfair
- title: Wayfair Spectral Rules
  type: SpectralRules
  url: rules/wayfair-spectral-rules.yml
- title: Supplier Operations Capability
  type: NaftikoCapability
  url: capabilities/supplier-operations.yaml
- title: Wayfair Vocabulary
  type: Vocabulary
  url: vocabulary/wayfair-vocabulary.yml
- title: Wayfair JSON-LD Context
  type: JSON-LD
  url: json-ld/wayfair-context.jsonld
created: '2025-03-01'
description: Wayfair Inc. is one of the world's largest online destinations for home goods and furniture, serving over 20 million customers and 10,000+ suppliers. Wayfair's Developer Portal provides GraphQL-based APIs enabling suppliers to manage purchase orders, inventory updates, product catalog management, advanced shipment notifications, and returns. The platform is built on federated GraphQL architecture using domain-oriented microservices, allowing suppliers to request only the data they need.
features:
- description: Unified GraphQL endpoint enabling suppliers to query and mutate data across orders, inventory, catalog, and shipping with precise data fetching.
  name: GraphQL Supplier API
- description: Suppliers retrieve, acknowledge, and manage purchase orders from Wayfair buyers through the GraphQL API.
  name: Purchase Order Management
- description: Real-time inventory updates and stock level management for the Wayfair marketplace catalog.
  name: Inventory Management
- description: Suppliers manage product listings, pricing, descriptions, and attributes through the Product Catalog Update API.
  name: Product Catalog Management
- description: Suppliers submit ASN (Advanced Shipment Notification) data to notify Wayfair of pending shipments, carrier details, and tracking numbers.
  name: Advanced Shipment Notifications
- description: Full sandbox environment at sandbox.api.wayfair.com/v1/graphql for integration testing without affecting production orders.
  name: Sandbox Testing Environment
- description: Client credentials flow authentication issuing temporary access tokens for secure API access.
  name: OAuth2 Token Authentication
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Full sandbox environment for integration testing before deploying to the production Wayfair platform.
  name: Wayfair Sandbox
- description: Wayfair's federated GraphQL architecture enables domain-oriented microservices composition behind a unified supplier API.
  name: Apollo GraphQL Federation
- description: Standard OAuth2 client credentials flow for secure supplier application authentication.
  name: OAuth2 Authentication
jsonld:
- class_count: 5
  name: Wayfair Context
  property_count: 15
  slug: wayfair-context
layout: provider
modified: '2026-05-03'
name: Wayfair
rules:
- name: Wayfair API Rules
  rule_count: 31
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 16
  slug: wayfair-spectral-rules
skills: []
slug: wayfair
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wayfair\nname: Wayfair\ndescription: >-\n  Wayfair Inc. is one of the world's largest online destinations for home\n  goods and furniture, serving over 20 million customers and 10,000+ suppliers.\n  Wayfair's Developer Portal provides GraphQL-based APIs enabling suppliers to\n  manage purchase orders, inventory updates, product catalog management, advanced\n  shipment notifications, and returns. The platform is built on federated\n  GraphQL architecture using domain-oriented microservices, allowing suppliers\n  to request only the data they need.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - E-Commerce\n  - Furniture\n  - Home Goods\n  - Retail\n  - Suppliers\n  - GraphQL\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: wayfair:wayfair-supplier-api\n    name: Wayfair Supplier API\n\
  \    description: >-\n      GraphQL-based API for Wayfair suppliers to manage orders, inventory,\n      product catalogs, shipping notifications, and returns. Provides access to\n      purchase orders, inventory updates, catalog management, and advanced\n      shipment notifications via a unified GraphQL endpoint at\n      api.wayfair.com/v1/graphql.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.wayfair.com/docs/\n    baseURL: https://api.wayfair.com/v1/graphql\n    tags:\n      - Catalog\n      - E-Commerce\n      - GraphQL\n      - Inventory\n      - Orders\n      - Shipping\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://developer.wayfair.com/docs/\n      - type: Documentation\n        url: https://developer.wayfair.io/posts/graphQL\n        title: GraphQL Documentation\n      - type: OpenAPI\n        url: openapi/wayfair-supplier-api.yml\n      - type: JSONSchema\n     \
  \   url: json-schema/wayfair-graph-ql-request-schema.json\n        title: GraphQL Request Schema\n      - type: JSONSchema\n        url: json-schema/wayfair-graph-ql-response-schema.json\n        title: GraphQL Response Schema\n      - type: JSONSchema\n        url: json-schema/wayfair-token-request-schema.json\n        title: Token Request Schema\n      - type: JSONSchema\n        url: json-schema/wayfair-token-response-schema.json\n        title: Token Response Schema\n      - type: JSONStructure\n        url: json-structure/wayfair-graph-ql-request-structure.json\n        title: GraphQL Request Structure\n      - type: JSONStructure\n        url: json-structure/wayfair-graph-ql-response-structure.json\n        title: GraphQL Response Structure\n      - type: Example\n        url: examples/wayfair-graph-ql-request-example.json\n        title: GraphQL Request Example\n      - type: Example\n        url: examples/wayfair-token-request-example.json\n        title: Token Request Example\n\
  common:\n  - type: Portal\n    url: https://developer.wayfair.com/docs/\n    title: Developer Portal\n  - type: Portal\n    url: https://developer.wayfair.io/posts/introduction\n    title: Developer Portal (Introduction)\n  - type: Documentation\n    url: https://developer.wayfair.io/posts/graphQL\n    title: GraphQL Documentation\n  - type: Documentation\n    url: https://developer.wayfair.io/posts/api-testing\n    title: Sandbox API Testing\n  - type: Website\n    url: https://www.wayfair.com/\n    title: Wayfair Website\n  - type: About\n    url: https://www.aboutwayfair.com/\n    title: About Wayfair\n  - type: GitHubOrganization\n    url: https://github.com/wayfair\n    title: Wayfair GitHub Organization\n  - type: SpectralRules\n    url: rules/wayfair-spectral-rules.yml\n    title: Wayfair Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/supplier-operations.yaml\n    title: Supplier Operations Capability\n  - type: Vocabulary\n    url: vocabulary/wayfair-vocabulary.yml\n\
  \    title: Wayfair Vocabulary\n  - type: JSON-LD\n    url: json-ld/wayfair-context.jsonld\n    title: Wayfair JSON-LD Context\n  - type: Features\n    data:\n      - name: GraphQL Supplier API\n        description: >-\n          Unified GraphQL endpoint enabling suppliers to query and mutate data\n          across orders, inventory, catalog, and shipping with precise data\n          fetching.\n      - name: Purchase Order Management\n        description: >-\n          Suppliers retrieve, acknowledge, and manage purchase orders from\n          Wayfair buyers through the GraphQL API.\n      - name: Inventory Management\n        description: >-\n          Real-time inventory updates and stock level management for the\n          Wayfair marketplace catalog.\n      - name: Product Catalog Management\n        description: >-\n          Suppliers manage product listings, pricing, descriptions, and\n          attributes through the Product Catalog Update API.\n      - name: Advanced Shipment\
  \ Notifications\n        description: >-\n          Suppliers submit ASN (Advanced Shipment Notification) data to notify\n          Wayfair of pending shipments, carrier details, and tracking numbers.\n      - name: Sandbox Testing Environment\n        description: >-\n          Full sandbox environment at sandbox.api.wayfair.com/v1/graphql for\n          integration testing without affecting production orders.\n      - name: OAuth2 Token Authentication\n        description: >-\n          Client credentials flow authentication issuing temporary access\n          tokens for secure API access.\n  - type: UseCases\n    data:\n      - name: Order Fulfillment Automation\n        description: >-\n          Suppliers automate purchase order retrieval, acknowledgment, and\n          fulfillment workflows to reduce manual processing time.\n      - name: Inventory Synchronization\n        description: >-\n          Real-time synchronization of warehouse inventory levels with the\n          Wayfair\
  \ marketplace to prevent overselling.\n      - name: Product Catalog Updates\n        description: >-\n          Batch and real-time updates to product listings, pricing, and\n          attributes in the Wayfair catalog.\n      - name: Shipping Notification Automation\n        description: >-\n          Automated submission of ASN data and tracking information when\n          orders are shipped from supplier warehouses.\n  - type: Integrations\n    data:\n      - name: Wayfair Sandbox\n        description: >-\n          Full sandbox environment for integration testing before deploying\n          to the production Wayfair platform.\n      - name: Apollo GraphQL Federation\n        description: >-\n          Wayfair's federated GraphQL architecture enables domain-oriented\n          microservices composition behind a unified supplier API.\n      - name: OAuth2 Authentication\n        description: >-\n          Standard OAuth2 client credentials flow for secure supplier\n          application\
  \ authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml
tags:
- E-Commerce
- Furniture
- Home Goods
- Retail
- Suppliers
- GraphQL
url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml
use_cases:
- description: Suppliers automate purchase order retrieval, acknowledgment, and fulfillment workflows to reduce manual processing time.
  name: Order Fulfillment Automation
- description: Real-time synchronization of warehouse inventory levels with the Wayfair marketplace to prevent overselling.
  name: Inventory Synchronization
- description: Batch and real-time updates to product listings, pricing, and attributes in the Wayfair catalog.
  name: Product Catalog Updates
- description: Automated submission of ASN data and tracking information when orders are shipped from supplier warehouses.
  name: Shipping Notification Automation
---
