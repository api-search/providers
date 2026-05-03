---
api_count: 3
api_specs:
- filename: shopify-admin-rest-openapi.yml
  format: yaml
  label: Shopify Admin REST API
  slug: shopify-admin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/openapi/shopify-admin-rest-openapi.yml
apis:
- description: The Shopify Admin REST API lets you build apps and integrations that extend and enhance the Shopify admin. It provides access to products, customers, orders, inventory, fulfillment, shipping, and stor
  name: Shopify Admin REST API
  slug: shopify-admin-rest-api
- description: The Shopify Admin GraphQL API is the recommended API for building Shopify apps and integrations. It provides access to all Shopify admin resources including products, customers, orders, inventory, ful
  name: Shopify Admin GraphQL API
  slug: shopify-admin-graphql-api
- description: Shopify webhooks allow apps to subscribe to specific events that occur in a store. When an event occurs, Shopify sends an HTTP POST request with a JSON payload to the configured endpoint. Webhooks can
  name: Shopify Webhooks
  slug: shopify-webhooks
capabilities:
- description: Unified workflow capability for comprehensive Shopify store management. Combines product catalog management, customer relationship management, order processing, inventory tracking, and store configura
  name: Shopify Admin Store Management
  slug: store-management
common:
- title: ''
  type: Website
  url: https://shopify.dev/
- title: ''
  type: Documentation
  url: https://shopify.dev/docs/api
- title: ''
  type: Authentication
  url: https://shopify.dev/docs/apps/auth/get-access-tokens
- title: ''
  type: RateLimits
  url: https://shopify.dev/docs/api/usage/rate-limits
- title: ''
  type: Versioning
  url: https://shopify.dev/docs/api/usage/versioning
- title: ''
  type: ChangeLog
  url: https://shopify.dev/changelog
- title: ''
  type: Blog
  url: https://shopify.dev/blog
- title: ''
  type: GitHub
  url: https://github.com/Shopify
- title: ''
  type: JSONSchema
  url: json-schema/shopify-admin-product-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/shopify-admin-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/shopify-admin-customer-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/shopify-admin-product-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/shopify-admin-context.jsonld
- title: ''
  type: Examples
  url: examples/shopify-admin-list-products-example.json
- title: ''
  type: Examples
  url: examples/shopify-admin-create-order-example.json
- title: ''
  type: Vocabulary
  url: vocabulary/shopify-admin-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/shopify-admin-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/store-management.yaml
created: '2026-05-02'
description: The Shopify Admin API provides programmatic access to manage Shopify store administration. It enables app developers and merchants to manage products, customers, orders, inventory, shipping, fulfillment, collections, webhooks, and store settings. The Admin API is available in both REST and GraphQL formats. Shopify is transitioning from REST to GraphQL as the primary API, with GraphQL recommended for all new development.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 41
  name: Shopify Admin Context
  property_count: 3
  slug: shopify-admin-context
layout: provider
modified: '2026-05-02'
name: Shopify Admin API
rules:
- name: Shopify Admin API API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: shopify-admin-rules
skills: []
slug: shopify-admin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shopify-admin\nname: Shopify Admin API\ndescription: >-\n  The Shopify Admin API provides programmatic access to manage Shopify store\n  administration. It enables app developers and merchants to manage products,\n  customers, orders, inventory, shipping, fulfillment, collections, webhooks,\n  and store settings. The Admin API is available in both REST and GraphQL\n  formats. Shopify is transitioning from REST to GraphQL as the primary API,\n  with GraphQL recommended for all new development.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Commerce\n  - Ecommerce\n  - Admin\n  - Products\n  - Orders\n  - Customers\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: shopify-admin:shopify-admin-rest-api\n    name: Shopify Admin REST API\n    description: >-\n      The Shopify\
  \ Admin REST API lets you build apps and integrations that\n      extend and enhance the Shopify admin. It provides access to products,\n      customers, orders, inventory, fulfillment, shipping, and store\n      configuration. All requests require a valid Shopify access token\n      generated through OAuth. Note: Shopify is deprecating the REST Admin API\n      in favor of GraphQL; new development should use the GraphQL Admin API.\n    humanURL: https://shopify.dev/docs/api/admin-rest\n    baseURL: https://{store_name}.myshopify.com/admin/api/2024-10\n    tags:\n      - Commerce\n      - Ecommerce\n      - Admin\n      - REST\n      - Products\n      - Orders\n      - Customers\n    properties:\n      - type: Documentation\n        url: https://shopify.dev/docs/api/admin-rest\n      - type: Reference\n        url: https://shopify.dev/docs/api/admin-rest/latest\n      - type: Authentication\n        url: https://shopify.dev/docs/apps/auth/get-access-tokens\n      - type: RateLimits\n \
  \       url: https://shopify.dev/docs/api/usage/rate-limits\n      - type: Versioning\n        url: https://shopify.dev/docs/api/usage/versioning\n      - type: OpenAPI\n        url: openapi/shopify-admin-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shopify-admin-product-schema.json\n      - type: JSONSchema\n        url: json-schema/shopify-admin-order-schema.json\n      - type: JSONSchema\n        url: json-schema/shopify-admin-customer-schema.json\n      - type: JSONStructure\n        url: json-structure/shopify-admin-product-structure.json\n      - type: JSONLDContext\n        url: json-ld/shopify-admin-context.jsonld\n      - type: SpectralRules\n        url: rules/shopify-admin-rules.yml\n      - type: Capabilities\n        url: capabilities/store-management.yaml\n      - type: Vocabulary\n        url: vocabulary/shopify-admin-vocabulary.yml\n    contact:\n      - FN: Shopify Developer Support\n        url: https://shopify.dev/\n        email: api@shopify.com\n\
  \  - aid: shopify-admin:shopify-admin-graphql-api\n    name: Shopify Admin GraphQL API\n    description: >-\n      The Shopify Admin GraphQL API is the recommended API for building Shopify\n      apps and integrations. It provides access to all Shopify admin resources\n      including products, customers, orders, inventory, fulfillment, and\n      analytics. GraphQL enables efficient data fetching with precise field\n      selection, real-time subscriptions, and access to advanced platform\n      features not available in REST.\n    humanURL: https://shopify.dev/docs/api/admin-graphql\n    baseURL: https://{store_name}.myshopify.com/admin/api/2024-10/graphql.json\n    tags:\n      - Commerce\n      - Ecommerce\n      - Admin\n      - GraphQL\n      - Products\n      - Orders\n      - Customers\n    properties:\n      - type: Documentation\n        url: https://shopify.dev/docs/api/admin-graphql\n      - type: Reference\n        url: https://shopify.dev/docs/api/admin-graphql/latest\n \
  \     - type: GettingStarted\n        url: https://shopify.dev/docs/api/usage/graphql\n      - type: Explorer\n        url: https://shopify.dev/docs/api/usage/api-exploration/admin-graphiql-explorer\n      - type: Authentication\n        url: https://shopify.dev/docs/apps/auth/get-access-tokens\n      - type: RateLimits\n        url: https://shopify.dev/docs/api/usage/rate-limits\n    contact:\n      - FN: Shopify Developer Support\n        url: https://shopify.dev/\n  - aid: shopify-admin:shopify-webhooks\n    name: Shopify Webhooks\n    description: >-\n      Shopify webhooks allow apps to subscribe to specific events that occur in\n      a store. When an event occurs, Shopify sends an HTTP POST request with\n      a JSON payload to the configured endpoint. Webhooks can be configured for\n      events across all major Shopify resources including orders, products,\n      customers, inventory, fulfillment, and app-specific events.\n    humanURL: https://shopify.dev/docs/api/webhooks\n\
  \    tags:\n      - Commerce\n      - Ecommerce\n      - Webhooks\n      - Events\n    properties:\n      - type: Documentation\n        url: https://shopify.dev/docs/api/webhooks\n      - type: Reference\n        url: https://shopify.dev/docs/api/webhooks/2024-10\n    contact:\n      - FN: Shopify Developer Support\n        url: https://shopify.dev/\n\ncommon:\n  - type: Website\n    url: https://shopify.dev/\n  - type: Documentation\n    url: https://shopify.dev/docs/api\n  - type: Authentication\n    url: https://shopify.dev/docs/apps/auth/get-access-tokens\n  - type: RateLimits\n    url: https://shopify.dev/docs/api/usage/rate-limits\n  - type: Versioning\n    url: https://shopify.dev/docs/api/usage/versioning\n  - type: ChangeLog\n    url: https://shopify.dev/changelog\n  - type: Blog\n    url: https://shopify.dev/blog\n  - type: GitHub\n    url: https://github.com/Shopify\n  - type: JSONSchema\n    url: json-schema/shopify-admin-product-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/shopify-admin-order-schema.json\n  - type: JSONSchema\n    url: json-schema/shopify-admin-customer-schema.json\n  - type: JSONStructure\n    url: json-structure/shopify-admin-product-structure.json\n  - type: JSONLDContext\n    url: json-ld/shopify-admin-context.jsonld\n  - type: Examples\n    url: examples/shopify-admin-list-products-example.json\n  - type: Examples\n    url: examples/shopify-admin-create-order-example.json\n  - type: Vocabulary\n    url: vocabulary/shopify-admin-vocabulary.yml\n  - type: SpectralRules\n    url: rules/shopify-admin-rules.yml\n  - type: Capabilities\n    url: capabilities/store-management.yaml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml
tags:
- Commerce
- Ecommerce
- Admin
- Products
- Orders
- Customers
url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/apis.yml
use_cases: []
---
