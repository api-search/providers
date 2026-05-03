---
api_count: 2
api_specs:
- filename: urban-outfitters-affiliate-api-openapi.yml
  format: yaml
  label: Urban Outfitters Affiliate Program
  slug: affiliate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/openapi/urban-outfitters-affiliate-api-openapi.yml
- filename: urban-outfitters-marketplace-api-openapi.yml
  format: yaml
  label: Urban Outfitters Marketplace (UO MRKT) Integration
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/openapi/urban-outfitters-marketplace-api-openapi.yml
apis:
- description: Urban Outfitters affiliate program managed through Rakuten Advertising (formerly LinkShare) network. Provides affiliate tracking links, banner ads, marketing copy, and product data feeds for affiliate
  name: Urban Outfitters Affiliate Program
  slug: affiliate-api
- description: Urban Outfitters operates a curated third-party marketplace called UO MRKT for independent lifestyle and fashion brands. Seller integration is managed through EDI and third-party connectors such as Co
  name: Urban Outfitters Marketplace (UO MRKT) Integration
  slug: marketplace-api
capabilities:
- description: ''
  name: Retail Commerce
  slug: retail-commerce
common:
- title: ''
  type: Website
  url: https://www.urban-outfitters.com
- title: ''
  type: Website
  url: https://www.urbanoutfitters.com
- title: Affiliate Portal
  type: Portal
  url: https://www.urbanoutfitters.com/help/affiliate
- title: ''
  type: GitHubOrganization
  url: https://github.com/urbn
- title: ''
  type: JSONLD
  url: json-ld/urban-outfitters-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/urban-outfitters-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/urban-outfitters-vocabulary.yaml
- title: Retail Commerce
  type: NaftikoCapability
  url: capabilities/retail-commerce.yaml
- title: Affiliate API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/affiliate-api.yaml
- title: Marketplace API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/marketplace-api.yaml
created: '2026-03-24'
description: Urban Outfitters is a multi-channel lifestyle retailer offering an eclectic mix of women's, men's, and kids apparel, footwear, accessories, beauty, and home goods. Part of URBN, Inc. (which also owns Anthropologie, Free People, Bhldn, and Nuuly), Urban Outfitters operates stores in the US, Europe, and Canada alongside a robust ecommerce platform. The brand provides affiliate marketing integration through the Rakuten Advertising network and a third-party seller marketplace program (UO MRKT) that accepts independent brands selling through EDI and third-party integration platforms. Urban Outfitters uses Stripe for payment processing, Stripe Connect for marketplace seller payouts, and Stripe Terminal for in-store payments.
features:
- description: Product catalog data feeds for affiliate partners to display and link Urban Outfitters products.
  name: Affiliate Product Data Feeds
- description: Unique tracking links and banner ads through Rakuten Advertising for commission tracking.
  name: Affiliate Tracking Links
- description: EDI and API-based integration for third-party brands selling through the UO MRKT marketplace.
  name: Marketplace Seller Integration
- description: Real-time inventory synchronization between seller systems and Urban Outfitters marketplace.
  name: Inventory Sync
- description: Automated order routing and fulfillment management for marketplace sellers.
  name: Order Routing
- description: Stripe-powered payment processing for both online checkout and in-store POS via Stripe Terminal.
  name: Stripe Payments
- description: Automated marketplace seller payouts through Stripe Connect.
  name: Stripe Connect Payouts
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Affiliate network platform managing Urban Outfitters affiliate program tracking and payouts.
  name: Rakuten Advertising
- description: EDI integration platform for Urban Outfitters marketplace seller connectivity.
  name: ConnectPointz EDI
- description: Multi-channel inventory management platform with Urban Outfitters marketplace connector.
  name: SellerCloud
- description: European multi-channel selling platform with Urban Outfitters marketplace integration.
  name: e-tailize
- description: Payment processing and marketplace payout infrastructure powering all URBN brands.
  name: Stripe
- description: Alternative affiliate network offering higher commission rates for Urban Outfitters.
  name: Skimlinks
jsonld:
- class_count: 26
  name: Urban Outfitters Context
  property_count: 48
  slug: urban-outfitters-context
layout: provider
modified: '2026-05-03'
name: Urban Outfitters
rules:
- name: Urban Outfitters API Rules
  rule_count: 31
  severity_counts:
    error: 10
    hint: 9
    info: 0
    warn: 12
  slug: urban-outfitters-spectral-rules
skills: []
slug: urban-outfitters
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: urban-outfitters\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml\nname: Urban Outfitters\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Retail\n  - Fashion\n  - Apparel\n  - Ecommerce\n  - Affiliate\n  - Marketplace\ndescription: >-\n  Urban Outfitters is a multi-channel lifestyle retailer offering an eclectic mix\n  of women's, men's, and kids apparel, footwear, accessories, beauty, and home goods.\n  Part of URBN, Inc. (which also owns Anthropologie, Free People, Bhldn, and Nuuly),\n  Urban Outfitters operates stores in the US, Europe, and Canada alongside a robust\n  ecommerce platform. The brand provides affiliate marketing integration through the\n  Rakuten Advertising network and a third-party seller marketplace program (UO MRKT)\n  that accepts independent brands selling through EDI and third-party integration\n  platforms. Urban Outfitters uses Stripe\
  \ for payment processing, Stripe Connect for\n  marketplace seller payouts, and Stripe Terminal for in-store payments.\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: urban-outfitters:affiliate-api\n    name: Urban Outfitters Affiliate Program\n    description: >-\n      Urban Outfitters affiliate program managed through Rakuten Advertising\n      (formerly LinkShare) network. Provides affiliate tracking links, banner\n      ads, marketing copy, and product data feeds for affiliates to promote\n      Urban Outfitters products. Commission rates are approximately 2% per\n      confirmed sale, with a 30-day cookie window and monthly payouts.\n    humanURL: https://www.urbanoutfitters.com/help/affiliate\n    baseURL: https://api.rakutenadvertising.com\n    tags:\n      - Affiliate\n      - Marketing\n      - Product Feed\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://www.urbanoutfitters.com/help/affiliate\n\
  \      - type: OpenAPI\n        url: openapi/urban-outfitters-affiliate-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/affiliate-api-product-schema.json\n      - type: JSONSchema\n        url: json-schema/affiliate-api-affiliate-link-schema.json\n      - type: JSONSchema\n        url: json-schema/affiliate-api-commission-report-schema.json\n      - type: JSONSchema\n        url: json-schema/affiliate-api-creative-schema.json\n  - aid: urban-outfitters:marketplace-api\n    name: Urban Outfitters Marketplace (UO MRKT) Integration\n    description: >-\n      Urban Outfitters operates a curated third-party marketplace called UO MRKT\n      for independent lifestyle and fashion brands. Seller integration is managed\n      through EDI and third-party connectors such as ConnectPointz, SellerCloud,\n      and e-tailize. Provides product catalog sync, inventory management, order\n      routing, and shipment tracking for approved sellers.\n    humanURL: https://www.urbanoutfitters.com/mrkt-seller-form\n\
  \    baseURL: https://www.urbanoutfitters.com\n    tags:\n      - Marketplace\n      - Sellers\n      - EDI\n      - Inventory\n      - Orders\n    properties:\n      - type: Documentation\n        url: https://www.urbanoutfitters.com/mrkt-seller-form\n      - type: OpenAPI\n        url: openapi/urban-outfitters-marketplace-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/marketplace-api-seller-product-schema.json\n      - type: JSONSchema\n        url: json-schema/marketplace-api-order-schema.json\n      - type: JSONSchema\n        url: json-schema/marketplace-api-shipment-schema.json\n      - type: JSONSchema\n        url: json-schema/marketplace-api-inventory-update-schema.json\ncommon:\n  - type: Website\n    url: https://www.urban-outfitters.com\n  - type: Website\n    url: https://www.urbanoutfitters.com\n  - type: Portal\n    url: https://www.urbanoutfitters.com/help/affiliate\n    title: Affiliate Portal\n  - type: GitHubOrganization\n    url: https://github.com/urbn\n\
  \  - type: JSONLD\n    url: json-ld/urban-outfitters-context.jsonld\n  - type: SpectralRules\n    url: rules/urban-outfitters-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/urban-outfitters-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/retail-commerce.yaml\n    title: Retail Commerce\n  - type: NaftikoCapability\n    url: capabilities/shared/affiliate-api.yaml\n    title: Affiliate API (Shared)\n  - type: NaftikoCapability\n    url: capabilities/shared/marketplace-api.yaml\n    title: Marketplace API (Shared)\n  - type: Features\n    data:\n      - name: Affiliate Product Data Feeds\n        description: Product catalog data feeds for affiliate partners to display and link Urban Outfitters products.\n      - name: Affiliate Tracking Links\n        description: Unique tracking links and banner ads through Rakuten Advertising for commission tracking.\n      - name: Marketplace Seller Integration\n        description: EDI and API-based integration for\
  \ third-party brands selling through the UO MRKT marketplace.\n      - name: Inventory Sync\n        description: Real-time inventory synchronization between seller systems and Urban Outfitters marketplace.\n      - name: Order Routing\n        description: Automated order routing and fulfillment management for marketplace sellers.\n      - name: Stripe Payments\n        description: Stripe-powered payment processing for both online checkout and in-store POS via Stripe Terminal.\n      - name: Stripe Connect Payouts\n        description: Automated marketplace seller payouts through Stripe Connect.\n  - type: UseCases\n    data:\n      - name: Content Creator Monetization\n        description: Bloggers, influencers, and content creators earning commissions by promoting Urban Outfitters products.\n      - name: Comparison Shopping\n        description: Price comparison and product discovery platforms integrating Urban Outfitters product catalog.\n      - name: Independent Brand Sales\n \
  \       description: Independent fashion and lifestyle brands expanding distribution through Urban Outfitters marketplace.\n      - name: Inventory Management\n        description: Sellers using EDI or integration platforms to sync inventory and orders with Urban Outfitters.\n  - type: Integrations\n    data:\n      - name: Rakuten Advertising\n        description: Affiliate network platform managing Urban Outfitters affiliate program tracking and payouts.\n      - name: ConnectPointz EDI\n        description: EDI integration platform for Urban Outfitters marketplace seller connectivity.\n      - name: SellerCloud\n        description: Multi-channel inventory management platform with Urban Outfitters marketplace connector.\n      - name: e-tailize\n        description: European multi-channel selling platform with Urban Outfitters marketplace integration.\n      - name: Stripe\n        description: Payment processing and marketplace payout infrastructure powering all URBN brands.\n    \
  \  - name: Skimlinks\n        description: Alternative affiliate network offering higher commission rates for Urban Outfitters.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml
tags:
- Retail
- Fashion
- Apparel
- Ecommerce
- Affiliate
- Marketplace
url: https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml
use_cases:
- description: Bloggers, influencers, and content creators earning commissions by promoting Urban Outfitters products.
  name: Content Creator Monetization
- description: Price comparison and product discovery platforms integrating Urban Outfitters product catalog.
  name: Comparison Shopping
- description: Independent fashion and lifestyle brands expanding distribution through Urban Outfitters marketplace.
  name: Independent Brand Sales
- description: Sellers using EDI or integration platforms to sync inventory and orders with Urban Outfitters.
  name: Inventory Management
---
