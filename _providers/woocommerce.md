---
api_count: 3
api_specs:
- filename: woocommerce-rest-api-openapi.yml
  format: yaml
  label: WooCommerce REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-rest-api-openapi.yml
- filename: woocommerce-store-api-openapi.yml
  format: yaml
  label: WooCommerce Store API
  slug: store-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-store-api-openapi.yml
- filename: woocommerce-webhooks-asyncapi.yml
  format: yaml
  label: WooCommerce Webhook Events
  slug: webhook-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/asyncapi/woocommerce-webhooks-asyncapi.yml
apis:
- description: The WooCommerce REST API is the primary server-side interface for reading and writing WooCommerce store data programmatically. It follows REST conventions, uses JSON, and is integrated with the WordPr
  name: WooCommerce REST API
  slug: rest-api
- description: The WooCommerce Store API provides unauthenticated public REST endpoints for building customer-facing cart, checkout, and product functionality. Accessible under /wp-json/wc/store/v1/, it covers produ
  name: WooCommerce Store API
  slug: store-api
- description: WooCommerce delivers real-time event notifications via HTTP POST webhooks for orders, products, customers, coupons, and subscriptions lifecycle changes. Webhooks are configured in the WooCommerce admi
  name: WooCommerce Webhook Events
  slug: webhook-events
asyncapis:
- description: The WooCommerce webhook system delivers real-time HTTP POST event notifications to a subscriber-configured endpoint URL whenever specific store events occur. Supported topics cover create, update, del
  name: WooCommerce Webhook Events
  slug: woocommerce-webhooks-asyncapi
capabilities:
- description: Headless commerce capability combining the public WooCommerce Store API with authenticated REST API operations for building custom frontends. Used by frontend developers and headless architects buildi
  name: WooCommerce Headless Commerce
  slug: headless-commerce
- description: Unified store management capability combining the WooCommerce REST API and Store API for complete eCommerce operations. Used by store administrators and operations teams to manage products, process or
  name: WooCommerce Store Management
  slug: store-management
common:
- title: ''
  type: Website
  url: https://woocommerce.com
- title: ''
  type: DeveloperPortal
  url: https://developer.woocommerce.com
- title: ''
  type: Documentation
  url: https://developer.woocommerce.com/docs/
- title: ''
  type: GettingStarted
  url: https://developer.woocommerce.com/docs/getting-started/
- title: ''
  type: GitHub
  url: https://github.com/woocommerce/woocommerce
- title: ''
  type: GitHubOrganization
  url: https://github.com/woocommerce
- title: ''
  type: Blog
  url: https://developer.woocommerce.com/blog/
- title: ''
  type: Support
  url: https://woocommerce.com/support/
- title: ''
  type: Forum
  url: https://wordpress.org/support/plugin/woocommerce/
- title: ''
  type: ReleaseNotes
  url: https://developer.woocommerce.com/changelog/
- title: ''
  type: StatusPage
  url: https://status.woocommerce.com
- title: ''
  type: JSON-LD
  url: json-ld/woocommerce-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/woocommerce-spectral-rules.yml
- title: Store Management
  type: NaftikoCapability
  url: capabilities/store-management.yaml
- title: Headless Commerce
  type: NaftikoCapability
  url: capabilities/headless-commerce.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/woocommerce-vocabulary.yaml
- title: WooCommerce REST API JavaScript Library
  type: Tools
  url: https://github.com/woocommerce/woocommerce-rest-api-js-lib
- title: WooCommerce REST API PHP Library
  type: Tools
  url: https://github.com/woocommerce/wc-api-php
- title: WooCommerce QIT MCP Server
  type: Tools
  url: https://github.com/woocommerce/qit-mcp
- title: WooCommerce MCP Ability Plugin
  type: Tools
  url: https://github.com/woocommerce/wc-mcp-ability
- title: WooCommerce REST API JS Library (npm)
  type: SDK
  url: https://www.npmjs.com/package/@woocommerce/woocommerce-rest-api
created: '2026-05-03'
description: WooCommerce is the world's most popular open-source eCommerce platform, built on WordPress. It provides a comprehensive REST API for managing products, orders, customers, coupons, reports, webhooks, and store settings, plus a public-facing Store API for headless frontends. WooCommerce also delivers real-time events via webhooks for order, product, customer, and subscription lifecycle changes.
features:
- description: Create and manage products, variations, categories, attributes, tags, and shipping classes.
  name: Product Management
- description: Full order lifecycle management including creation, updates, notes, and refunds.
  name: Order Management
- description: Manage customer accounts with billing and shipping addresses.
  name: Customer Management
- description: Create and manage discount coupons with usage restrictions and expiry.
  name: Coupon System
- description: Real-time HTTP POST notifications for store events including orders, products, and customers.
  name: Webhook Events
- description: Store API provides unauthenticated endpoints for building custom frontends.
  name: Headless Commerce
- description: Configure and manage payment gateways programmatically.
  name: Payment Gateway API
- description: Manage shipping zones, methods, and rates via the REST API.
  name: Shipping Zones API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: WooCommerce runs as a WordPress plugin and uses the WordPress REST API infrastructure.
  name: WordPress
- description: Official PayPal payment gateway integration for WooCommerce.
  name: PayPal
- description: Official Stripe payment gateway integration.
  name: Stripe
- description: Order fulfillment and shipping integration.
  name: ShipStation
- description: Email marketing integration for customer segmentation and abandoned cart.
  name: Mailchimp
- description: Official Reddit for WooCommerce integration for ad conversion tracking.
  name: Reddit Ads
- description: Official Pinterest for WooCommerce integration for product sync.
  name: Pinterest
jsonld:
- class_count: 0
  name: Woocommerce Context
  property_count: 8
  slug: woocommerce-context
- class_count: 4
  name: Woocommerce Order Schema.Json Context
  property_count: 36
  slug: woocommerce-order-schema.json-context
- class_count: 5
  name: Woocommerce Product Schema.Json Context
  property_count: 57
  slug: woocommerce-product-schema.json-context
- class_count: 2
  name: Woocommerce Rest Api Batch Product Context
  property_count: 3
  slug: woocommerce-rest-api-batch-product-context
- class_count: 11
  name: Woocommerce Rest Api Context
  property_count: 81
  slug: woocommerce-rest-api-context
- class_count: 2
  name: Woocommerce Rest Api Coupon Context
  property_count: 12
  slug: woocommerce-rest-api-coupon-context
- class_count: 4
  name: Woocommerce Rest Api Customer Context
  property_count: 25
  slug: woocommerce-rest-api-customer-context
- class_count: 2
  name: Woocommerce Rest Api Line Context
  property_count: 12
  slug: woocommerce-rest-api-line-context
- class_count: 1
  name: Woocommerce Rest Api Meta Context
  property_count: 3
  slug: woocommerce-rest-api-meta-context
- class_count: 5
  name: Woocommerce Rest Api Order Context
  property_count: 25
  slug: woocommerce-rest-api-order-context
- class_count: 1
  name: Woocommerce Rest Api Order Note Context
  property_count: 3
  slug: woocommerce-rest-api-order-note-context
- class_count: 1
  name: Woocommerce Rest Api Order Refund Context
  property_count: 5
  slug: woocommerce-rest-api-order-refund-context
- class_count: 2
  name: Woocommerce Rest Api Payment Context
  property_count: 8
  slug: woocommerce-rest-api-payment-context
- class_count: 1
  name: Woocommerce Rest Api Payment Gateway Context
  property_count: 2
  slug: woocommerce-rest-api-payment-gateway-context
- class_count: 3
  name: Woocommerce Rest Api Product Category Context
  property_count: 3
  slug: woocommerce-rest-api-product-category-context
- class_count: 7
  name: Woocommerce Rest Api Product Context
  property_count: 33
  slug: woocommerce-rest-api-product-context
- class_count: 2
  name: Woocommerce Rest Api Product Variation Context
  property_count: 12
  slug: woocommerce-rest-api-product-variation-context
- class_count: 1
  name: Woocommerce Rest Api Sales Context
  property_count: 11
  slug: woocommerce-rest-api-sales-context
- class_count: 3
  name: Woocommerce Rest Api Shipping Context
  property_count: 8
  slug: woocommerce-rest-api-shipping-context
- class_count: 3
  name: Woocommerce Rest Api System Context
  property_count: 14
  slug: woocommerce-rest-api-system-context
- class_count: 2
  name: Woocommerce Rest Api Tax Context
  property_count: 10
  slug: woocommerce-rest-api-tax-context
- class_count: 2
  name: Woocommerce Rest Api Webhook Context
  property_count: 4
  slug: woocommerce-rest-api-webhook-context
- class_count: 1
  name: Woocommerce Store Api Add Cart Item Context
  property_count: 5
  slug: woocommerce-store-api-add-cart-item-context
- class_count: 3
  name: Woocommerce Store Api Attribute Context
  property_count: 3
  slug: woocommerce-store-api-attribute-context
- class_count: 3
  name: Woocommerce Store Api Cart Context
  property_count: 33
  slug: woocommerce-store-api-cart-context
- class_count: 2
  name: Woocommerce Store Api Cart Customer Context
  property_count: 12
  slug: woocommerce-store-api-cart-customer-context
- class_count: 2
  name: Woocommerce Store Api Cart Shipping Context
  property_count: 10
  slug: woocommerce-store-api-cart-shipping-context
- class_count: 3
  name: Woocommerce Store Api Checkout Context
  property_count: 24
  slug: woocommerce-store-api-checkout-context
- class_count: 3
  name: Woocommerce Store Api Context
  property_count: 37
  slug: woocommerce-store-api-context
- class_count: 1
  name: Woocommerce Store Api Product Collection Context
  property_count: 5
  slug: woocommerce-store-api-product-collection-context
- class_count: 10
  name: Woocommerce Store Api Store Context
  property_count: 61
  slug: woocommerce-store-api-store-context
- class_count: 7
  name: Woocommerce Store Api Store Product Context
  property_count: 26
  slug: woocommerce-store-api-store-product-context
- class_count: 4
  name: Woocommerce Webhook Schema.Json Context
  property_count: 10
  slug: woocommerce-webhook-schema.json-context
layout: provider
modified: '2026-05-03'
name: WooCommerce
rules:
- name: WooCommerce API Rules
  rule_count: 37
  severity_counts:
    error: 11
    hint: 0
    info: 5
    warn: 21
  slug: woocommerce-spectral-rules
skills: []
slug: woocommerce
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: woocommerce\nname: WooCommerce\ndescription: >-\n  WooCommerce is the world's most popular open-source eCommerce platform, built\n  on WordPress. It provides a comprehensive REST API for managing products,\n  orders, customers, coupons, reports, webhooks, and store settings, plus a\n  public-facing Store API for headless frontends. WooCommerce also delivers\n  real-time events via webhooks for order, product, customer, and subscription\n  lifecycle changes.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/apis.yml\ntags:\n  - eCommerce\n  - Open Source\n  - Orders\n  - Products\n  - WordPress\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\naccess: 3rd-Party\nposition: Consumer\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\napis:\n  - aid: woocommerce:rest-api\n    name: WooCommerce REST API\n    description: >-\n      The WooCommerce REST API is the primary\
  \ server-side interface for reading\n      and writing WooCommerce store data programmatically. It follows REST\n      conventions, uses JSON, and is integrated with the WordPress REST API\n      under /wp-json/wc/v3/. The API covers products, variations, categories,\n      attributes, orders, customers, coupons, tax rates, shipping zones, payment\n      gateways, settings, webhooks, reports, and system status. Authentication\n      uses Consumer Key and Consumer Secret pairs via HTTP Basic Auth or OAuth 1.0a.\n    humanURL: https://developer.woocommerce.com/docs/apis/rest-api/\n    baseURL: https://example.com/wp-json/wc/v3\n    tags:\n      - eCommerce\n      - Orders\n      - Products\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.woocommerce.com/docs/apis/rest-api/\n      - type: APIReference\n        url: https://woocommerce.github.io/woocommerce-rest-api-docs/\n      - type: Authentication\n        url: https://woocommerce.github.io/woocommerce-rest-api-docs/#authentication\n\
  \      - type: OpenAPI\n        url: openapi/woocommerce-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/woocommerce-rest-api-order-schema.json\n        title: Order Schema\n      - type: JSONSchema\n        url: json-schema/woocommerce-rest-api-product-schema.json\n        title: Product Schema\n      - type: JSONSchema\n        url: json-schema/woocommerce-rest-api-customer-schema.json\n        title: Customer Schema\n      - type: JSONSchema\n        url: json-schema/woocommerce-rest-api-coupon-schema.json\n        title: Coupon Schema\n  - aid: woocommerce:store-api\n    name: WooCommerce Store API\n    description: >-\n      The WooCommerce Store API provides unauthenticated public REST endpoints\n      for building customer-facing cart, checkout, and product functionality.\n      Accessible under /wp-json/wc/store/v1/, it covers products, categories,\n      attributes, tags, reviews, cart operations, checkout, and customer orders.\n      Write operations\
  \ require a nonce token from the cart response.\n    humanURL: https://developer.woocommerce.com/docs/apis/store-api/\n    baseURL: https://example.com/wp-json/wc/store/v1\n    tags:\n      - Cart\n      - Checkout\n      - eCommerce\n      - Headless\n      - Products\n    properties:\n      - type: Documentation\n        url: https://developer.woocommerce.com/docs/apis/store-api/\n      - type: OpenAPI\n        url: openapi/woocommerce-store-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/woocommerce-store-api-cart-schema.json\n        title: Cart Schema\n      - type: JSONSchema\n        url: json-schema/woocommerce-store-api-store-product-schema.json\n        title: Store Product Schema\n      - type: JSONSchema\n        url: json-schema/woocommerce-store-api-checkout-schema.json\n        title: Checkout Schema\n  - aid: woocommerce:webhook-events\n    name: WooCommerce Webhook Events\n    description: >-\n      WooCommerce delivers real-time event notifications\
  \ via HTTP POST webhooks\n      for orders, products, customers, coupons, and subscriptions lifecycle\n      changes. Webhooks are configured in the WooCommerce admin or via the REST\n      API and deliver JSON payloads signed with HMAC-SHA256.\n    humanURL: https://woocommerce.com/document/webhooks/\n    tags:\n      - Events\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://woocommerce.com/document/webhooks/\n      - type: AsyncAPI\n        url: asyncapi/woocommerce-webhooks-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/woocommerce-rest-api-webhook-schema.json\n        title: Webhook Schema\ncommon:\n  - type: Website\n    url: https://woocommerce.com\n  - type: DeveloperPortal\n    url: https://developer.woocommerce.com\n  - type: Documentation\n    url: https://developer.woocommerce.com/docs/\n  - type: GettingStarted\n    url: https://developer.woocommerce.com/docs/getting-started/\n  - type: GitHub\n    url: https://github.com/woocommerce/woocommerce\n\
  \  - type: GitHubOrganization\n    url: https://github.com/woocommerce\n  - type: Blog\n    url: https://developer.woocommerce.com/blog/\n  - type: Support\n    url: https://woocommerce.com/support/\n  - type: Forum\n    url: https://wordpress.org/support/plugin/woocommerce/\n  - type: ReleaseNotes\n    url: https://developer.woocommerce.com/changelog/\n  - type: StatusPage\n    url: https://status.woocommerce.com\n  - type: JSON-LD\n    url: json-ld/woocommerce-context.jsonld\n  - type: SpectralRules\n    url: rules/woocommerce-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/store-management.yaml\n    title: Store Management\n  - type: NaftikoCapability\n    url: capabilities/headless-commerce.yaml\n    title: Headless Commerce\n  - type: Vocabulary\n    url: vocabulary/woocommerce-vocabulary.yaml\n  - type: Tools\n    url: https://github.com/woocommerce/woocommerce-rest-api-js-lib\n    title: WooCommerce REST API JavaScript Library\n  - type: Tools\n    url: https://github.com/woocommerce/wc-api-php\n\
  \    title: WooCommerce REST API PHP Library\n  - type: Tools\n    url: https://github.com/woocommerce/qit-mcp\n    title: WooCommerce QIT MCP Server\n  - type: Tools\n    url: https://github.com/woocommerce/wc-mcp-ability\n    title: WooCommerce MCP Ability Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/@woocommerce/woocommerce-rest-api\n    title: WooCommerce REST API JS Library (npm)\n  - type: Features\n    data:\n      - name: Product Management\n        description: Create and manage products, variations, categories, attributes, tags, and shipping classes.\n      - name: Order Management\n        description: Full order lifecycle management including creation, updates, notes, and refunds.\n      - name: Customer Management\n        description: Manage customer accounts with billing and shipping addresses.\n      - name: Coupon System\n        description: Create and manage discount coupons with usage restrictions and expiry.\n      - name: Webhook Events\n        description:\
  \ Real-time HTTP POST notifications for store events including orders, products, and customers.\n      - name: Headless Commerce\n        description: Store API provides unauthenticated endpoints for building custom frontends.\n      - name: Payment Gateway API\n        description: Configure and manage payment gateways programmatically.\n      - name: Shipping Zones API\n        description: Manage shipping zones, methods, and rates via the REST API.\n  - type: UseCases\n    data:\n      - name: Headless Storefront\n        description: Build custom React or Vue frontends using the Store API for products, cart, and checkout.\n      - name: ERP Integration\n        description: Sync orders and inventory with ERP systems via the REST API and webhooks.\n      - name: Order Fulfillment\n        description: Automate order fulfillment workflows using webhook notifications and REST API updates.\n      - name: Product Catalog Sync\n        description: Sync product catalog from a PIM system\
  \ to WooCommerce via the REST API.\n      - name: Analytics and Reporting\n        description: Pull sales reports and customer data via the Reports API for BI tools.\n  - type: Integrations\n    data:\n      - name: WordPress\n        description: WooCommerce runs as a WordPress plugin and uses the WordPress REST API infrastructure.\n      - name: PayPal\n        description: Official PayPal payment gateway integration for WooCommerce.\n      - name: Stripe\n        description: Official Stripe payment gateway integration.\n      - name: ShipStation\n        description: Order fulfillment and shipping integration.\n      - name: Mailchimp\n        description: Email marketing integration for customer segmentation and abandoned cart.\n      - name: Reddit Ads\n        description: Official Reddit for WooCommerce integration for ad conversion tracking.\n      - name: Pinterest\n        description: Official Pinterest for WooCommerce integration for product sync.\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/apis.yml
tags:
- eCommerce
- Open Source
- Orders
- Products
- WordPress
url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/apis.yml
use_cases:
- description: Build custom React or Vue frontends using the Store API for products, cart, and checkout.
  name: Headless Storefront
- description: Sync orders and inventory with ERP systems via the REST API and webhooks.
  name: ERP Integration
- description: Automate order fulfillment workflows using webhook notifications and REST API updates.
  name: Order Fulfillment
- description: Sync product catalog from a PIM system to WooCommerce via the REST API.
  name: Product Catalog Sync
- description: Pull sales reports and customer data via the Reports API for BI tools.
  name: Analytics and Reporting
---
