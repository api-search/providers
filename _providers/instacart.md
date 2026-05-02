---
api_count: 5
api_specs:
- filename: instacart-developer-platform-api-openapi.yml
  format: yaml
  label: Instacart Developer Platform API
  slug: developer-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-developer-platform-api-openapi.yml
- filename: instacart-connect-fulfillment-api-openapi.yml
  format: yaml
  label: Instacart Connect Fulfillment API
  slug: connect-fulfillment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-connect-fulfillment-api-openapi.yml
- filename: instacart-connect-post-checkout-api-openapi.yml
  format: yaml
  label: Instacart Connect Post-Checkout API
  slug: connect-post-checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-connect-post-checkout-api-openapi.yml
- filename: instacart-catalog-api-openapi.yml
  format: yaml
  label: Instacart Catalog API
  slug: catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/openapi/instacart-catalog-api-openapi.yml
apis:
- description: The Instacart Developer Platform API is a REST-based API that allows app developers to add Instacart shopping capabilities to their websites and applications. It provides endpoints for creating produc
  name: Instacart Developer Platform API
  slug: developer-platform-api
- description: The Instacart Connect Fulfillment API enables retailers to integrate Instacart fulfillment capabilities directly into their e-commerce sites. It combines grocery, delivery, and pickup functionality in
  name: Instacart Connect Fulfillment API
  slug: connect-fulfillment-api
- description: 'The Instacart Connect Post-Checkout API allows retailers to provide their customers with real-time order tracking and shopper interaction after an order has been placed. Retailers can use this API to '
  name: Instacart Connect Post-Checkout API
  slug: connect-post-checkout-api
- description: 'The Instacart Catalog API enables retailers to programmatically manage their product catalogs on the Instacart platform. Retailers can use the API to create or update products and items, with partial '
  name: Instacart Catalog API
  slug: catalog-api
- description: Instacart Shopping Widgets are front-end web components that retailers can embed into their websites to add e-commerce functionalities powered by Instacart without interacting with any API directly. T
  name: Instacart Shopping Widgets
  slug: shopping-widgets
asyncapis:
- description: Instacart Connect notifies retailers of order status changes and fulfillment events through webhook callbacks. Retailers configure callback endpoints to receive real-time notifications about order lif
  name: Instacart Connect Event Callbacks
  slug: instacart-connect-events-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/instacart-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/instacart-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/instacart-product-schema.json
created: ''
description: Use the public Instacart APIs to add Instacart shopping capabilities to your applications, such as product shopping lists and recipe ingredients.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Instacart Context
  property_count: 8
  slug: instacart-context
layout: provider
modified: '2026-03-20'
name: instacart
skills: []
slug: instacart
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: instacart\nurl: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: instacart:developer-platform-api\n    name: Instacart Developer Platform API\n    tags:\n      - Delivery\n      - E-Commerce\n      - Grocery\n      - Products\n      - Recipes\n      - Shopping\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://connect.instacart.com\n    humanURL: https://docs.instacart.com/developer_platform_api/\n    properties:\n      - url: https://docs.instacart.com/developer_platform_api/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/instacart-developer-platform-api-openapi.yml\n    description: >-\n      The Instacart Developer Platform API is a REST-based API that allows app developers\n      to add Instacart shopping capabilities to their websites and applications. It\n      provides endpoints for creating product shopping\
  \ lists and recipe pages on Instacart\n      Marketplace, enabling users to select a store, add ingredients or products to\n      a cart, and check out.\n  - aid: instacart:connect-fulfillment-api\n    name: Instacart Connect Fulfillment API\n    tags:\n      - Delivery\n      - E-Commerce\n      - Fulfillment\n      - Grocery\n      - Pickup\n      - Retail\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://connect.instacart.com\n    humanURL: https://docs.instacart.com/connect/fulfillment/\n    properties:\n      - url: https://docs.instacart.com/connect/fulfillment/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/instacart-connect-fulfillment-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/instacart-connect-events-asyncapi.yml\n    description: >-\n      The Instacart Connect Fulfillment API enables retailers to integrate Instacart\n      fulfillment capabilities directly into their e-commerce\
  \ sites. It combines grocery,\n      delivery, and pickup functionality into a single API, allowing retailers to\n      offer full-service shopping where Instacart shoppers pick items and suggest\n      replacements, as well as same-day or scheduled delivery and pickup options.\n  - aid: instacart:connect-post-checkout-api\n    name: Instacart Connect Post-Checkout API\n    tags:\n      - Delivery\n      - Fulfillment\n      - Orders\n      - Retail\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://connect.instacart.com\n    humanURL: https://docs.instacart.com/connect/post-checkout/\n    properties:\n      - url: https://docs.instacart.com/connect/post-checkout/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/instacart-connect-post-checkout-api-openapi.yml\n    description: >-\n      The Instacart Connect Post-Checkout API allows retailers to provide their customers\n      with real-time\
  \ order tracking and shopper interaction after an order has been\n      placed. Retailers can use this API to build custom order status pages that display\n      order details, live tracking information, and shopper communication.\n  - aid: instacart:catalog-api\n    name: Instacart Catalog API\n    tags:\n      - Catalog\n      - E-Commerce\n      - Inventory\n      - Products\n      - Retail\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://connect.instacart.com\n    humanURL: https://docs.instacart.com/catalog/catalog_api/overview/\n    properties:\n      - url: https://docs.instacart.com/catalog/catalog_api/overview/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/instacart-catalog-api-openapi.yml\n    description: >-\n      The Instacart Catalog API enables retailers to programmatically manage their\n      product catalogs on the Instacart platform. Retailers can use the API to create\n      or update\
  \ products and items, with partial updates supported so that only the\n      attributes included in the request body are modified.\n  - aid: instacart:shopping-widgets\n    name: Instacart Shopping Widgets\n    tags:\n      - Embedding\n      - Retail\n      - Shopping\n      - Web Components\n      - Widgets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.instacart.com/widgets/\n    properties:\n      - url: https://docs.instacart.com/widgets/\n        type: Documentation\n    description: >-\n      Instacart Shopping Widgets are front-end web components that retailers can embed\n      into their websites to add e-commerce functionalities powered by Instacart without\n      interacting with any API directly. The widgets enable features such as product\n      search results, cart management, product collections, and user authentication.\ncommon:\n  - type: JSON-LD\n    url: json-ld/instacart-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/instacart-order-schema.json\n  - type: JSONSchema\n    url: json-schema/instacart-product-schema.json\ndescription: >-\n  Use the public Instacart APIs to add Instacart shopping capabilities to your applications,\n  such as product shopping lists and recipe ingredients.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/instacart/refs/heads/main/apis.yml
use_cases: []
---
