---
api_count: 3
api_specs:
- filename: shopify-storefront-openapi.yml
  format: yaml
  label: Shopify Storefront API
  slug: shopify-storefront-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/openapi/shopify-storefront-openapi.yml
apis:
- description: The Shopify Storefront API is a GraphQL API for building headless commerce experiences. It provides access to products, collections, cart, checkout, customer accounts, and contextual pricing. All requ
  name: Shopify Storefront API
  slug: shopify-storefront-api
- description: Hydrogen is Shopify's opinionated React-based framework for building headless storefronts powered by the Storefront API. Hydrogen provides components, hooks, and utilities optimized for commerce inclu
  name: Shopify Hydrogen
  slug: shopify-hydrogen
- description: The Shopify JavaScript Buy SDK is a lightweight library that enables developers to integrate Shopify's storefront capabilities into any website or application. The SDK wraps the Storefront API and pro
  name: Shopify Buy SDK
  slug: shopify-buy-sdk
capabilities:
- description: Workflow capability for building headless Shopify commerce experiences. Combines product discovery, collection browsing, search, cart management, and customer account operations into a unified capabil
  name: Shopify Headless Commerce
  slug: headless-commerce
common: []
created: '2026-05-02'
description: The Shopify Storefront API is a GraphQL API that enables developers to build custom headless storefronts, purchasing flows, and commerce experiences using Shopify as a backend. The API provides programmatic access to products, collections, carts, checkout, customer accounts, and contextual pricing. It is designed for headless commerce architectures and powers the Shopify Hydrogen framework.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 43
  name: Shopify Storefront Context
  property_count: 1
  slug: shopify-storefront-context
layout: provider
modified: '2026-05-02'
name: Shopify Storefront API
rules:
- name: Shopify Storefront API API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 2
  slug: shopify-storefront-rules
skills: []
slug: shopify-storefront
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shopify-storefront\nname: Shopify Storefront API\ndescription: >-\n  The Shopify Storefront API is a GraphQL API that enables developers to build\n  custom headless storefronts, purchasing flows, and commerce experiences using\n  Shopify as a backend. The API provides programmatic access to products,\n  collections, carts, checkout, customer accounts, and contextual pricing.\n  It is designed for headless commerce architectures and powers the Shopify\n  Hydrogen framework.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Commerce\n  - Ecommerce\n  - Headless\n  - GraphQL\n  - Storefront\n  - Products\n  - Cart\n  - Checkout\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: shopify-storefront:shopify-storefront-api\n    name: Shopify Storefront API\n    description:\
  \ >-\n      The Shopify Storefront API is a GraphQL API for building headless commerce\n      experiences. It provides access to products, collections, cart, checkout,\n      customer accounts, and contextual pricing. All requests use GraphQL over\n      HTTPS and require a Storefront API access token. The Storefront API supports\n      both unauthenticated (public) and customer-authenticated access patterns.\n    humanURL: https://shopify.dev/docs/api/storefront\n    baseURL: https://{store_name}.myshopify.com/api/2024-10/graphql.json\n    tags:\n      - Commerce\n      - Ecommerce\n      - Headless\n      - GraphQL\n      - Products\n      - Cart\n      - Checkout\n    properties:\n      - type: Documentation\n        url: https://shopify.dev/docs/api/storefront\n      - type: Reference\n        url: https://shopify.dev/docs/api/storefront/latest\n      - type: GettingStarted\n        url: https://shopify.dev/docs/storefronts/headless/building-with-the-storefront-api/getting-started\n\
  \      - type: Authentication\n        url: https://shopify.dev/docs/storefronts/headless/building-with-the-storefront-api/get-started-with-the-storefront-api\n      - type: RateLimits\n        url: https://shopify.dev/docs/api/usage/rate-limits\n      - type: Versioning\n        url: https://shopify.dev/docs/api/usage/versioning\n      - type: OpenAPI\n        url: openapi/shopify-storefront-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shopify-storefront-product-schema.json\n      - type: JSONSchema\n        url: json-schema/shopify-storefront-cart-schema.json\n      - type: JSONLD\n        url: json-ld/shopify-storefront-context.jsonld\n      - type: SpectralRules\n        url: rules/shopify-storefront-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/headless-commerce.yaml\n      - type: Vocabulary\n        url: vocabulary/shopify-storefront-vocabulary.yml\n    contact:\n      - FN: Shopify Developer Support\n        url: https://shopify.dev/\n\
  \n  - aid: shopify-storefront:shopify-hydrogen\n    name: Shopify Hydrogen\n    description: >-\n      Hydrogen is Shopify's opinionated React-based framework for building\n      headless storefronts powered by the Storefront API. Hydrogen provides\n      components, hooks, and utilities optimized for commerce including streaming\n      SSR, React Server Components, and built-in Shopify data fetching.\n    humanURL: https://shopify.dev/docs/storefronts/headless/hydrogen\n    tags:\n      - Commerce\n      - Headless\n      - React\n      - Framework\n      - SSR\n    properties:\n      - type: Documentation\n        url: https://shopify.dev/docs/storefronts/headless/hydrogen\n      - type: GettingStarted\n        url: https://shopify.dev/docs/storefronts/headless/hydrogen/getting-started\n      - type: SDK\n        url: https://github.com/Shopify/hydrogen\n\n  - aid: shopify-storefront:shopify-buy-sdk\n    name: Shopify Buy SDK\n    description: >-\n      The Shopify JavaScript Buy SDK\
  \ is a lightweight library that enables\n      developers to integrate Shopify's storefront capabilities into any website\n      or application. The SDK wraps the Storefront API and provides methods for\n      fetching products, collections, and managing carts.\n    humanURL: https://shopify.github.io/js-buy-sdk/\n    tags:\n      - Commerce\n      - JavaScript\n      - SDK\n      - Cart\n    properties:\n      - type: Documentation\n        url: https://shopify.github.io/js-buy-sdk/\n      - type: SDK\n        url: https://github.com/Shopify/js-buy-sdk\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/apis.yml
tags:
- Commerce
- Ecommerce
- Headless
- GraphQL
- Storefront
- Products
- Cart
- Checkout
url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/apis.yml
use_cases: []
---
