---
api_count: 7
api_specs:
- filename: squarespace-commerce-api-openapi.yml
  format: yaml
  label: Squarespace Commerce API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-commerce-api-openapi.yml
- filename: squarespace-orders-api-openapi.yml
  format: yaml
  label: Squarespace Orders API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-orders-api-openapi.yml
- filename: squarespace-products-api-openapi.yml
  format: yaml
  label: Squarespace Products API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-products-api-openapi.yml
- filename: squarespace-inventory-api-openapi.yml
  format: yaml
  label: Squarespace Inventory API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-inventory-api-openapi.yml
- filename: squarespace-profiles-api-openapi.yml
  format: yaml
  label: Squarespace Profiles API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-profiles-api-openapi.yml
- filename: squarespace-transactions-api-openapi.yml
  format: yaml
  label: Squarespace Transactions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-transactions-api-openapi.yml
- filename: squarespace-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Squarespace Webhook Subscriptions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-webhook-subscriptions-api-openapi.yml
apis:
- description: The Squarespace Commerce API provides programmatic access to the commerce features of a Squarespace merchant site. It enables developers to manage products, process orders, track inventory, access cus
  name: Squarespace Commerce API
  slug: ''
- description: The Squarespace Orders API provides access to order history for a Squarespace merchant site, supporting both one-time purchases and subscription orders. Developers can retrieve, create, and manage ord
  name: Squarespace Orders API
  slug: ''
- description: The Squarespace Products API allows developers to manage the product catalog of a Squarespace merchant site. It supports physical products, service products, gift cards, and digital downloads, along w
  name: Squarespace Products API
  slug: ''
- description: The Squarespace Inventory API enables developers to retrieve and update inventory quantities for product variants on a Squarespace merchant site. It supports bulk inventory queries and individual vari
  name: Squarespace Inventory API
  slug: ''
- description: The Squarespace Profiles API allows reading customer profiles, mailing list subscribers, and donors for a Squarespace site. It supports filtering by profile type and retrieving individual profile deta
  name: Squarespace Profiles API
  slug: ''
- description: The Squarespace Transactions API provides access to financial transaction records for a Squarespace merchant site. Developers can retrieve transaction history, including payment amounts, fees, and ass
  name: Squarespace Transactions API
  slug: ''
- description: The Squarespace Webhook Subscriptions API allows developers to manage webhook endpoint subscriptions for a merchant site. It supports creating, listing, updating, and deleting subscriptions that trigg
  name: Squarespace Webhook Subscriptions API
  slug: ''
asyncapis:
- description: The Squarespace webhook system delivers real-time event notifications to registered endpoint URLs when commerce activity occurs on a merchant site. Supported events include order creation, order updat
  name: Squarespace Webhook Events
  slug: squarespace-webhooks-asyncapi
capabilities:
- description: Unified commerce management capability combining Squarespace Orders, Products, and Inventory APIs. Enables e-commerce operators, integration developers, and automation tools to manage the full product
  name: Squarespace Commerce Management
  slug: commerce-management
- description: 'Unified capability combining Squarespace Profiles, Transactions, and Webhook Subscriptions APIs. Enables CRM integrations, financial reporting tools, and event-driven automation workflows. Suited for '
  name: Squarespace Customer and Reporting
  slug: customer-and-reporting
common:
- title: ''
  type: Website
  url: https://www.squarespace.com
- title: ''
  type: DeveloperPortal
  url: https://developers.squarespace.com
- title: ''
  type: Documentation
  url: https://developers.squarespace.com/commerce-apis/overview
- title: ''
  type: APIKeys
  url: https://support.squarespace.com/hc/en-us/articles/236297987-Squarespace-API-keys
- title: ''
  type: TermsOfService
  url: https://www.squarespace.com/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.squarespace.com/privacy
- title: ''
  type: StatusPage
  url: https://status.squarespace.com
- title: ''
  type: Blog
  url: https://www.squarespace.com/blog
created: '2026-05-02'
description: Squarespace is an all-in-one website building and e-commerce platform that enables individuals and businesses to create, manage, and scale their online presence. Squarespace provides a suite of Commerce APIs for developers to build integrations managing products, orders, inventory, customer profiles, transactions, and webhook notifications. All APIs use HTTPS REST conventions with API key or OAuth authentication.
features: []
image: https://static1.squarespace.com/static/ta/5134cbefe4b0c6fb04df8065/10007/assets/logomark.svg
integrations: []
jsonld:
- class_count: 0
  name: Squarespace Context
  property_count: 12
  slug: squarespace-context
layout: provider
modified: '2026-05-02'
name: Squarespace
rules:
- name: Squarespace API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 7
  slug: squarespace-rules
skills: []
slug: squarespace
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: squarespace\nname: Squarespace\ndescription: >-\n  Squarespace is an all-in-one website building and e-commerce platform that enables\n  individuals and businesses to create, manage, and scale their online presence.\n  Squarespace provides a suite of Commerce APIs for developers to build integrations\n  managing products, orders, inventory, customer profiles, transactions, and webhook\n  notifications. All APIs use HTTPS REST conventions with API key or OAuth authentication.\nimage: https://static1.squarespace.com/static/ta/5134cbefe4b0c6fb04df8065/10007/assets/logomark.svg\nurl: https://www.squarespace.com\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n  - name: Squarespace Commerce API\n    description: >-\n      The Squarespace Commerce API provides programmatic access to the commerce\n      features of a Squarespace merchant site. It enables developers to manage\n      products, process orders, track inventory, access customer profiles, retrieve\n      financial\
  \ transactions, and configure webhook subscriptions. All endpoints\n      use HTTPS and follow REST principles.\n    humanUrl: https://developers.squarespace.com/commerce-apis/overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Commerce\n      - E-Commerce\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/commerce-apis/overview\n      - type: OpenAPI\n        url: openapi/squarespace-commerce-api-openapi.yml\n      - type: Authentication\n        url: https://developers.squarespace.com/commerce-apis/making-requests\n      - type: SpectralRules\n        url: rules/squarespace-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/commerce-management.yaml\n      - type: NaftikoCapabilities\n        url: capabilities/customer-and-reporting.yaml\n      - type: JSONLD\n        url: json-ld/squarespace-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/squarespace-vocabulary.yml\n\
  \  - name: Squarespace Orders API\n    description: >-\n      The Squarespace Orders API provides access to order history for a Squarespace\n      merchant site, supporting both one-time purchases and subscription orders.\n      Developers can retrieve, create, and manage orders, as well as import orders\n      from third-party sales channels into Squarespace.\n    humanUrl: https://developers.squarespace.com/commerce-apis/orders-overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Commerce\n      - Orders\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/commerce-apis/orders-overview\n      - type: OpenAPI\n        url: openapi/squarespace-orders-api-openapi.yml\n  - name: Squarespace Products API\n    description: >-\n      The Squarespace Products API allows developers to manage the product catalog\n      of a Squarespace merchant site. It supports physical products, service products,\n      gift cards,\
  \ and digital downloads, along with their images and variants.\n    humanUrl: https://developers.squarespace.com/commerce-apis/products-overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Commerce\n      - Products\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/commerce-apis/products-overview\n      - type: OpenAPI\n        url: openapi/squarespace-products-api-openapi.yml\n  - name: Squarespace Inventory API\n    description: >-\n      The Squarespace Inventory API enables developers to retrieve and update\n      inventory quantities for product variants on a Squarespace merchant site.\n      It supports bulk inventory queries and individual variant stock management.\n    humanUrl: https://developers.squarespace.com/commerce-apis/inventory-overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Commerce\n      - Inventory\n      - REST API\n    properties:\n      - type: Documentation\n\
  \        url: https://developers.squarespace.com/commerce-apis/inventory-overview\n      - type: OpenAPI\n        url: openapi/squarespace-inventory-api-openapi.yml\n  - name: Squarespace Profiles API\n    description: >-\n      The Squarespace Profiles API allows reading customer profiles, mailing list\n      subscribers, and donors for a Squarespace site. It supports filtering by\n      profile type and retrieving individual profile details.\n    humanUrl: https://developers.squarespace.com/commerce-apis/profiles-overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - CRM\n      - Customer Profiles\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/commerce-apis/profiles-overview\n      - type: OpenAPI\n        url: openapi/squarespace-profiles-api-openapi.yml\n  - name: Squarespace Transactions API\n    description: >-\n      The Squarespace Transactions API provides access to financial transaction\n  \
  \    records for a Squarespace merchant site. Developers can retrieve transaction\n      history, including payment amounts, fees, and associated order or subscription\n      references.\n    humanUrl: https://developers.squarespace.com/commerce-apis/transactions-overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Commerce\n      - Finance\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/commerce-apis/transactions-overview\n      - type: OpenAPI\n        url: openapi/squarespace-transactions-api-openapi.yml\n  - name: Squarespace Webhook Subscriptions API\n    description: >-\n      The Squarespace Webhook Subscriptions API allows developers to manage webhook\n      endpoint subscriptions for a merchant site. It supports creating, listing,\n      updating, and deleting subscriptions that trigger notifications for order\n      events, extension uninstalls, and other commerce activities.\n    humanUrl:\
  \ https://developers.squarespace.com/webhooks/overview\n    baseUrl: https://api.squarespace.com/1.0\n    tags:\n      - Webhooks\n      - Event Notifications\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.squarespace.com/webhooks/overview\n      - type: OpenAPI\n        url: openapi/squarespace-webhook-subscriptions-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/squarespace-webhooks-asyncapi.yml\ncommon:\n  - type: Website\n    url: https://www.squarespace.com\n  - type: DeveloperPortal\n    url: https://developers.squarespace.com\n  - type: Documentation\n    url: https://developers.squarespace.com/commerce-apis/overview\n  - type: APIKeys\n    url: https://support.squarespace.com/hc/en-us/articles/236297987-Squarespace-API-keys\n  - type: TermsOfService\n    url: https://www.squarespace.com/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.squarespace.com/privacy\n  - type: StatusPage\n    url: https://status.squarespace.com\n\
  \  - type: Blog\n    url: https://www.squarespace.com/blog\nmaintainers:\n  - name: Squarespace Developer Support\n    url: https://developers.squarespace.com\ntags:\n  - Commerce\n  - E-Commerce\n  - Marketing\n  - Payments\n  - Retail\n  - Website Builder\n  - Webhooks\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/apis.yml
tags:
- Commerce
- E-Commerce
- Marketing
- Payments
- Retail
- Website Builder
- Webhooks
url: https://www.squarespace.com
use_cases: []
---
